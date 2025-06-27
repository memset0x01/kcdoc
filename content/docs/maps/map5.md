---
date: '2025-06-15T13:14:48Z'
draft: false
title: '南方海域(5-X)'
weight: 6
---

### 5-1 南方海域前面 `南方海域進出作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD5-1.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - BB系+CV系>=5 去A<br>- CA系>=4 且 CL>=1 去B<br>- CA系>=2 且 CL=1 去B<br>- DD>=2 且 BB系+CV系<=2 去B<br>- DD>=2 且 CL>=1 且 CV+CVB=0: 25%去A, 75%去B<br>- BB系+CV系>=4: 90%去A, 10%去B<br>- 其余75%去A, 25%去B |
| B | - CV+CVB>=1 去E<br>- CVL>=2 去E<br>- BB系<=2 去C<br>- CL=1 去E<br>- DD>=2 去C<br>- 其余随机去C/E? |
| F | - 最速舰队 去J(优先级待测试)<br>- 舰队中只包含SS系 去G?<br>- BB系+CV系>=4 去H<br>- BB系+CV系=3 随机去G/H/J<br>- BB系+CV系<=2<br>&nbsp;&nbsp;- CL>=1<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD>=2 去J<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD<=1 去G<br>&nbsp;&nbsp;- CL=0<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD>=4 去J<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD=3 约5%去G, 95%去J<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD=2 约40%去G, 60%去J<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD=1 去G?<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD=0 去H? |
| G | - BB系+CV系>=5 去I<br>- CA系>=2 且 [高速+]或以上的舰队 去J<br>- CA系>=4 且 CA系+CL+DD=6 去J<br>- CA系>=4 75%去J, 25%去I<br>- CV+CVB>=1 35%去J, 65%去I<br>- CA系>=2 且 DD>=2 去J<br>- CA系=3 35%去J, 65%去I<br>- CA系=2 85%去J, 15%去I<br>- BB系+CVL<=2 且 DD>=2 去J<br>- CVL=0 且 CL>=1 且 DD>=2 去J<br>- CL=1 且 DD<=1 85%去J, 15%去I<br>- 其余35%去J, 65%去I |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->B-C-F-J | 0 | 252 | `1~2`BB+`0~1`CVL+1CL+2DD+1CA/CAV/CLT |

### 5-2 珊瑚諸島沖 `珊瑚諸島沖海戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD5-2.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - SS系=`1~2`: 35%去A<br>- SS=3: 55%去A<br>- SS=`4~6`: 70%去A<br>- BB系+CV系=5: 65%去A<br>- BB系+CV系=6: 80%去A<br>- CV+CVB>=3: 50%去A<br>- BB系>=4: 一定概率去A<br>- 以上逐条依次判定, 去A判定失败时去B |
| C | - 舰队中包含 `翔鹤` 和 `瑞鹤`<br>&nbsp;&nbsp;- DD<=1 去E<br>&nbsp;&nbsp;- CA系>=2 去D<br>&nbsp;&nbsp;- 高速以上的舰队 去D<br>&nbsp;&nbsp;- 低速舰队 去E<br>- BB系+CLT>=1 去E<br>- DD>=2<br>&nbsp;&nbsp;- CV系=0 去E<br>&nbsp;&nbsp;- CA系>=2 去D<br>&nbsp;&nbsp;- CV+CVB>=1 去E<br>&nbsp;&nbsp;- CVL>=3 去E<br>&nbsp;&nbsp;- 高速以上的舰队<br>&nbsp;&nbsp;&nbsp;&nbsp;- CA系=1 去D<br>&nbsp;&nbsp;&nbsp;&nbsp;- CA系=0 且 CVL=2 去D<br>- DD<=1<br>&nbsp;&nbsp;- CV+CVB>=1 去E<br>&nbsp;&nbsp;- CVL>=4 去E<br>- 上述判定全部失败时<br>&nbsp;&nbsp;- 舰队中包含 `夕张` 且 DD+CA系+AO+CVL=5 去D<br>&nbsp;&nbsp;- 舰队中包含 `祥凤` 且 DD+CA系+AO+CL+CT=5 去D<br>&nbsp;&nbsp;- 其余去E |
| D | - 舰队中 包含`祥凤` 且 包含`夕张`<br>&nbsp;&nbsp;- DD=2 且 CA=2 去G<br>&nbsp;&nbsp;- DD=2 且 AO=2 去G<br>&nbsp;&nbsp;- 其余去F<br>- 舰队中 包含`祥凤` 且 不包含`夕张`<br>&nbsp;&nbsp;- DD=3 且 CA=1 且 CL=1 去G<br>&nbsp;&nbsp;- DD=3 且 CA=1 且 AO=1 去G<br>&nbsp;&nbsp;- DD=3 且 AO=2 去G<br>&nbsp;&nbsp;- 其余去F<br>- 舰队中 不包含`祥凤` 且 包含`夕张`<br>&nbsp;&nbsp;- DD=5 去G<br>&nbsp;&nbsp;- DD=4 且 AO=1 去G<br>&nbsp;&nbsp;- DD=3 且 AO=2 去G<br>&nbsp;&nbsp;- DD=2 且 AO=1 且 CA=2 去G<br>&nbsp;&nbsp;- DD=2 且 AO=2 且 CA=1 去G<br>&nbsp;&nbsp;- 其余去F<br>- 舰队中 不包含`祥凤` 且 不包含`夕张` 去F |
| F | - 分歧点系数=2<br>- 63索敌以下去H<br>- 63~70索敌随机去H, 索敌越低去H概率越高<br>- 去H判定失败时 或 70以上索敌(司令部系数0.35, 索敌>=76)<br>&nbsp;&nbsp;- BB系<=2 且 CV系<=2 去O<br>&nbsp;&nbsp;- BB系+CV+CVB>=5 去I<br>&nbsp;&nbsp;- 其余约75%去I, 25%去O |
| G | - 随机去J/L? |
| L | - 高速+以上舰队 去K?<br>- 分歧点系数=2<br>- 索敌>=62 去K (司令部系数0.35, 索敌>=68)<br>- 60~62索敌 随机去M/K<br>- 索敌<60 去M<br>- 目前没有去N的记录 |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->B-C-D-F-O | 70<sub>2</sub> | 351 | 翔鹤+瑞鹤+2FBB+2DD |

### 5-3 サブ島沖海域 `第一次サーモン沖海戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD5-3.webp)

{{% details title="分歧条件" closed="true" %}}

> 大发系: 大発動艇, 特大発動艇, 大発動艇(八九式中戦車&陸戦隊), 特二式内火艇, 武装大発

| 分岐点 | 条件 |
| --- | --- |
| 1 | - 高速+以上的舰队 去D<br>- BB系+CV系>=3 去C<br>- BB系+CV系=2 且 低速舰队 去C<br>- SS系>=1: 40%去C, 60%去D<br>- 其余去D |
| B | - 65%去A, 35%去F? |
| E | - SS系>=1: 大概率去B, 小概率去Q<br>- BB系>=1 且 DD<=1 随机去Q/B<br>- CL>=1 去Q<br>- CA+CAV>=4 去Q<br>- DD>=4 去Q<br>- 其余随机去Q/B |
| G | - SS+SSV>=1 去J<br>- BBV>=1 去J<br>- CV+CVB>=1 去J<br>- DD=0 去I<br>- CVL>=2 去I<br>- CVL=1 去J<br>- DD=1 去I<br>- BB<=1 去I<br>- 其余去J |
| I | - CVL>=1 去J<br>- BB系>=3 去J<br>- DD>=3 去O<br>- DD=2<br>&nbsp;&nbsp;- CL+CT>=1 去O<br>&nbsp;&nbsp;- BB系>=2 去J<br>&nbsp;&nbsp;- 其余去O<br>- DD<=1<br>&nbsp;&nbsp;- CL>=1<br>&nbsp;&nbsp;&nbsp;&nbsp;- CA+CAV>=4 且 DD+CL+CA+CAV=6 去O<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余约65%去J, 35%去O<br>&nbsp;&nbsp;- CL=0<br>&nbsp;&nbsp;&nbsp;&nbsp;- BB系>=1 去J<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余约80%去J, 60%去O? |
| J | - SS系>=1 随机去L/M/N<br>- CV+CVB>=1 去M<br>- CVL>=2 去M<br>- BB系+CVL>=4 去M<br>- CVL=1<br>&nbsp;&nbsp;- BB>=2 去N<br>&nbsp;&nbsp;- BBV>=1 随机去L/N<br>&nbsp;&nbsp;- DD>=3 去L<br>&nbsp;&nbsp;- DD=2<br>&nbsp;&nbsp;&nbsp;&nbsp;- CL>=1 去L<br>&nbsp;&nbsp;&nbsp;&nbsp;- CA+CAV>=3 去L?<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去N<br>&nbsp;&nbsp;- DD<=1 随机去L/N?<br>- CVL=0 随机去L/N |
| K | - DD>=4 去H<br>- DD>=3 且 CL>=1 去H<br>- DD>=2<br>&nbsp;&nbsp;- BBV>=1 去H<br>&nbsp;&nbsp;- AO>=1 去H<br>&nbsp;&nbsp;- AS>=1 去H<br>&nbsp;&nbsp;- 高速+以上的舰队 去H<br>&nbsp;&nbsp;- 装备[ドラム缶]的船数>=2 去H<br>&nbsp;&nbsp;- 装备[大发系]的船数>=2 去H<br>- 其余去E |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->D->G->I->O->K->E->Q | 0 | 140 | 1BB+2CA/CAV+1CL+2DD |
| 1->D->G->I->O->K->E->Q | 0 | 0 | 1BB+2CLT+1CL+2DD |
| 1->D->G->I->O->K->E->Q | 0 | 140 | 1CL+5CA/CAV |

### 5-4 サーモン海域 `東京急行`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD5-4.webp)

{{% details title="分歧条件" closed="true" %}}

> 大发系: 大発動艇, 特大発動艇, 大発動艇(八九式中戦車&陸戦隊), 特二式内火艇, 武装大発

| 分岐点 | 条件 |
| --- | --- |
| 1 | - CV系>=1 去B<br>- BB系>=3 去A<br>- CA系>=5 去A<br>- 装备[ドラム缶]的船数+装备[大发系]的船数>=5 去B (一船同时装备桶和大发计算两次)<br>- DD>=4 去B<br>- DD=3<br>&nbsp;&nbsp;- CL=1 去B<br>&nbsp;&nbsp;- 其余去A<br>- DD<=2 去A |
| A | - SS系>=1 去D<br>- DD>=2 去D<br>- CA系>=3 去D<br>- BB系>=5 去D<br>- 其余去F |
| B | - CV系>=1 去C<br>- SS系>=1 去C<br>- BB系>=1 且 低速舰队 去D<br>- BB+BBV>=2 去D<br>- 高速+以上的舰队 去E<br>- DD>=3 去E<br>- DD=`1~2` 随机去D/E<br>- DD=0 去D |
| D | - SS+SSV>=1 去F<br>- BB>=2 去F<br>- BB系>=3 去F<br>- DD<=1 去F<br>- 其余去E |
| G | - SS+SSV>=1 去K?<br>- BB系>=4 去K?<br>- CV+CVB<=2 去L<br>- 其余约65%去K, 35%去L |
| L | - BB系+CV+CVB>=5 随机去N<br>- 高速+以上的舰队去P<br>- 分歧点系数=2<br>&nbsp;&nbsp;- 索敌>=`60` 去P(司令部系数0.35, 索敌>=`66`)<br>&nbsp;&nbsp;- 索敌`56~60` 随机去N/P, 索敌越高去P概率越高<br>&nbsp;&nbsp;- 索敌<`56` 去N |
| M | - SS系>=1 随机去O<br>- 高速+以上的舰队去P<br>- 分歧点系数=2<br>&nbsp;&nbsp;- 索敌>=`45` 去P(司令部系数0.35, 索敌>=`51`)<br>&nbsp;&nbsp;- 索敌`41~45` 随机去O/P, 索敌越高去P概率越高<br>&nbsp;&nbsp;- 索敌<`41` 去O |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->B->E->H->M->P | 45<sub>2</sub> | 141 | 1CL+3DD+1BB系+1FBB/CA系/CLT, 高速 |

### 5-5 サーモン海域北方 `第二次サーモン海戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD5-5.webp)

{{% details title="分歧条件" closed="true" %}}

> 大发系: 大発動艇, 大発動艇(八九式中戦車&陸戦隊), 特大発動艇, 武装大発, 大発動艇(II号戦車/北アフリカ仕様), 特大発動艇+一式砲戦車, 特二式内火艇, 特四式内火艇, 特四式内火艇改

| 分岐点 | 条件 |
| --- | --- |
| 1 | - DD>=4 去A<br>- 装备[ドラム缶]的船数>=4 去A<br>- 装备[大发系]的船数>=4 去A<br>- 其余去B |
| B | - CV+CVB>=3 去K<br>- BB系+CLT>=4 去K<br>- DD>=2 去F<br>- 其余去K |
| E | - 最速舰队 去H<br>- DD>=2 且 高速+舰队 去H<br>- 去G |
| H | - 最速舰队 去N<br>- BB系+CV系>=4 去P<br>- 高速+舰队 去N<br>- DD>=2 去N<br>- DD<=1 去L |
| I | - BB系+CV系>=4 去M<br>- BB系+CV系<=2 去M<br>- DD<=1 去M<br>- 其余去L |
| M | - 经过N的舰队 去O<br>- BB系+CV系>=4 去L<br>- DD<=1 去L<br>- 其余去O |
| N | - 经过M的舰队 去O<br>- 高速+、最速舰队 去O<br>- AO>=1 去O<br>- CV+CVB>=1去M<br>- BB系+CVL>=3 去M<br>- DD>=2 去O<br>- DD<=1 去M |
| O | - 高速+、最速舰队 去S<br>- SS+SSV>=1: 35%去R<br>- 分歧点系数=2, 索敌>=`66` 去S(司令部系数0.35, 索敌>=`72`)<br>&nbsp;&nbsp;- 索敌`63~66`, 索敌越高去S概率越高<br>&nbsp;&nbsp;- 索敌不足`63` 去R |
| P | - 最速舰队 去S<br>- 高速+舰队 且 BB系+CV系<=5 去S<br>- BB系+CV系>=5: 35%去Q<br>- SS+SSV>=1: 35%去Q<br>- 分歧点系数=2, 索敌>=`80` 去S(司令部系数0.35, 索敌>=`86`)<br>&nbsp;&nbsp;- 索敌`73~80`, 索敌越高去S概率越高<br>&nbsp;&nbsp;- 索敌不足`73` 去Q |
{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->B->F->D->H->N->O->S | 66<sub>2</sub> | 138 | 大和+武蔵+加賀+宗谷+2DD |
