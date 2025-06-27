---
date: '2025-06-24T03:55:54Z'
draft: false
title: '奇妙小工具'
weight: 7
---

#### PAC

```js
// define dmm list
const dmm_list = {
    "www.dmm.com": 0,
    "osapi.dmm.com": 0,
    "accounts.dmm.com": 0,
    "cdnjs.cloudflare.com": 0,
    "ajax.googleapis.com": 0,
};

function FindProxyForURL(url, host) {
    
    if (dnsDomainIs(host, ".kancolle-server.com")) {
        if (shExpMatch(url, "*.kancolle-server.com/kcsapi/*")) {
            // kcsapi -> japan proxy
            return "PROXY 127.0.0.1:8123";
        } else {
            // static assets -> other proxy, fallback to direct
            return "SOCKS5 127.0.0.1:1080; DIRECT";
        }
    }

    // same as kcsapi
    if (host in dmm_list) return "PROXY 127.0.0.1:8123";

    // local ips -> direct
    if (
        isInNet(host, "127.0.0.0", "255.0.0.0") || 
        isInNet(host, "10.0.0.0", "255.0.0.0") || 
        isInNet(host, "172.16.0.0", "255.240.0.0") || 
        isInNet(host, "192.168.0.0", "255.255.0.0")
    ) return "DIRECT";
    
    // final -> block everthing
    // 1. using an unused port
    // 2. deploy another proxy tool, listen port 4444, send inbound to blackhole
    return "PROXY 127.0.0.1:4444";
}
```
