---
date: '2025-06-15T13:14:48Z'
draft: false
title: '南西海域(7-X)'
weight: 4
---

### 7-1 ブルネイ泊地沖 `ブルネイ泊地沖哨戒`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD7-1.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - 舰队船数=6<br>&nbsp;&nbsp;- SS系>=1 大概率去B, 小概率去D<br>&nbsp;&nbsp;- 其余去B<br>- 舰队船数=5<br>&nbsp;&nbsp;- SS系>=1 随机去B/D<br>&nbsp;&nbsp;- BB系+CV系>=1 去B<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数<=4<br>&nbsp;&nbsp;- SS系>=1 随机去B/D/F<br>&nbsp;&nbsp;- BB系+CV系>=1 去B<br>&nbsp;&nbsp;- AO>=1 去D<br>&nbsp;&nbsp;- 其余去F |
| B | - CV+CVB>=1 去A<br>- BB系>=1 去A<br>- CVL>=2 去A<br>- CA系>=3 去A<br>- DD+DE>=2 去C<br>- 其余随机去A/C |
| D | - DD+DE=5 去E<br>- DD+DE=4<br>&nbsp;&nbsp;- CL=1 且 DD=4 去E<br>&nbsp;&nbsp;- CT>=1 去E<br>&nbsp;&nbsp;- AO>=1 去E<br>&nbsp;&nbsp;- DE=3 去E<br>&nbsp;&nbsp;- AV=0 去C<br>&nbsp;&nbsp;- AV>=1: 约65%去C, 35%去E<br>- DD+DE<=3<br>&nbsp;&nbsp;- AO>=1 且 DE=3 去E<br>&nbsp;&nbsp;- 其余去C |
| H | - CL=1 且 DD>=4 去K<br>- DD>=1 且 DE>=3 去K<br>- BB系+CV系>=3 去J<br>- AV>=1: 65%去K, 35%去I<br>- 其余大概率去K, 中概率去I, 小概率去J<br>&nbsp;&nbsp;- BB系+CV系越多越容易去J?<br>&nbsp;&nbsp;- AO、AS、CT更容易去I? |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->D->E->G->H->K | 0 | 0 | 1CL+4DD |

### 7-2 タウイタウイ泊地沖 `セレベス海戦闘哨戒`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD7-2.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - SS系>=1 去A<br>- DD+DE<=1 去A<br>- 舰队船数=6<br>&nbsp;&nbsp;- CV+CVB>=2 去A<br>&nbsp;&nbsp;- BB系+CV+CVB>=4 去A<br>&nbsp;&nbsp;- CL+CT>=3 去A<br>&nbsp;&nbsp;- 其余去B<br>- 舰队船数=5<br>&nbsp;&nbsp;- CV+CVB>=3 去A<br>&nbsp;&nbsp;- BB系+CV+CVB>=1 去B<br>&nbsp;&nbsp;- CL+CT>=2 去B<br>&nbsp;&nbsp;- DE<=2 去B<br>&nbsp;&nbsp;- 其余去C<br>- 舰队船数<=4<br>&nbsp;&nbsp;- BB系+CV+CVB>=1 去B<br>&nbsp;&nbsp;- DD+DE<=2 去B<br>&nbsp;&nbsp;- 其余去C |
| C | - AO>=1 去D<br>- SS系>=1 去D<br>- 舰队船数=6<br>&nbsp;&nbsp;- BB系+CV+CVB>=1 去D<br>&nbsp;&nbsp;- DD+DE>=4 去E<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数=5<br>&nbsp;&nbsp;- BB系+CV+CVB>=2 去D<br>&nbsp;&nbsp;- DD+DE>=4 去E<br>&nbsp;&nbsp;- DE>=3 去E<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数<=4<br>&nbsp;&nbsp;- BB系+CV+CVB>=2 去D<br>&nbsp;&nbsp;- DD+DE>=3 去E<br>&nbsp;&nbsp;- DE>=2 去E<br>&nbsp;&nbsp;- 其余去D |
| D | - 高速+/最速舰队 去I<br>- BB系+CV系>=4 去H<br>- BB系+CV系=3<br>&nbsp;&nbsp;- 低速舰队 去H<br>&nbsp;&nbsp;- 高速舰队 去I<br>- BB系+CV系=2<br>&nbsp;&nbsp;- 低速舰队 35%去H, 65%去I<br>&nbsp;&nbsp;- 高速舰队 去I<br>- BB系+CV系<=1 去I |
| E | - 舰队船数<=5 去G<br>- DD+DE>=5 去G<br>- DE=3 去G<br>- 分歧点系数=4<br>&nbsp;&nbsp;- 索敌>=`47` 去G<br>&nbsp;&nbsp;- 索敌不足去F |
| I | - AO>=1 去J<br>- AV>=1 且 DD+DE>=3 去J<br>- 分歧点系数=4<br>&nbsp;&nbsp;- 索敌>=`69` 去M<br>&nbsp;&nbsp;- 索敌`63~69` 随机去L/M, 索敌越高去M概率越高<br>&nbsp;&nbsp;- 索敌<`63` 去L? |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| (P1)1->C->E->G | 0 | 0 | 3CVL+2DE |
| (P2)1->B->C->D->I->M | 69<sub>4</sub> | 359 | FBB+CVB+2DD+CTL+CVL 高速 |

### 7-3 ペナン島沖 `マラッカ海峡を抜けて`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD7-3.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| A | - 舰队船数=1 去C<br>- CV系>=1 去B<br>- DD+DE=0 去B<br>- P1阶段 且 舰队船数>=5 去B<br>- `羽黑`=0 且 BB系>=1 去B<br>- `神风`+`羽黑`=2 去C<br>- AO>=1 且 DD+DE>=3 去C<br>- CA=0 去B<br>- 舰队船数<=3<br>&nbsp;&nbsp;- CA+CL+DD+DE=舰队船数 去C<br>&nbsp;&nbsp;- 其余去B<br>- `羽黑`=0 且 低速舰队 去B<br>- DD+DE>=3 去C<br>- 舰队船数>=5 去B<br>- CL=1 且 DD+DE=2 去C<br>- 其余去B |
| C | - BB系+CV系>=1 去D<br>- DD+DE=0 去D<br>- 舰队船数=6<br>&nbsp;&nbsp;- P1阶段 去D<br>&nbsp;&nbsp;- DD+DE<=1 去D<br>&nbsp;&nbsp;- [最速]的舰队 去I<br>&nbsp;&nbsp;- CA系+CLT+AV>=3 去D<br>&nbsp;&nbsp;- [高速+]的舰队 去I<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数=5<br>&nbsp;&nbsp;- P1阶段 去D<br>&nbsp;&nbsp;- DD+DE<=1 去D<br>&nbsp;&nbsp;- [最速]的舰队 去I<br>&nbsp;&nbsp;- `神风`+`羽黑`=2<br>&nbsp;&nbsp;&nbsp;&nbsp;- `足柄`=1 去I<br>&nbsp;&nbsp;&nbsp;&nbsp;- [高速+]以上的舰队 去I<br>&nbsp;&nbsp;&nbsp;&nbsp;- CL>=1 去I<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去D<br>&nbsp;&nbsp;- DD>=4 且 [高速+]以上的舰队 去I<br>&nbsp;&nbsp;- CL=1 且 DD=3 且 [高速+]以上的舰队 去I<br>&nbsp;&nbsp;- CA=1 且 CL=1 且 DD=3 且 高速以上的舰队 去I<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数=4<br>&nbsp;&nbsp;- `神风`+`羽黑`=2<br>&nbsp;&nbsp;&nbsp;&nbsp;- P2阶段 且 [最速]的舰队 去I<br>&nbsp;&nbsp;&nbsp;&nbsp;- CA系>=3 去D<br>&nbsp;&nbsp;&nbsp;&nbsp;- `足柄`+妙高>=1 去E<br>&nbsp;&nbsp;&nbsp;&nbsp;- DD+DE>=2 去E<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去D<br>&nbsp;&nbsp;- `神风`=1 且 DD+DE=4 去E<br>&nbsp;&nbsp;- `羽黑`=1 且 DD+DE=3 去E<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数=3<br>&nbsp;&nbsp;- `神风`+`羽黑`=2 且 `足柄`+妙高=1 去E<br>&nbsp;&nbsp;- CA系>=2 去D<br>&nbsp;&nbsp;- CA+DD+DE=3 去E<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数<=2 去E |
| D | - P1阶段<br>&nbsp;&nbsp;&nbsp;&nbsp;- BB系+CV系>=1 去F<br>&nbsp;&nbsp;&nbsp;&nbsp;- CA系>=4 去F<br>&nbsp;&nbsp;&nbsp;&nbsp;- CAV>=2 去F<br>&nbsp;&nbsp;&nbsp;&nbsp;- 舰队船数=6 去F<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去E<br>- P2阶段<br>&nbsp;&nbsp;&nbsp;&nbsp;- BB系>=3 去F<br>&nbsp;&nbsp;&nbsp;&nbsp;- CV系>=3 去F<br>&nbsp;&nbsp;&nbsp;&nbsp;- CAV>=3 去F<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去G |
| G | - AO>=1 且 DD+DE>=2 且 CA=0 去H<br>- AV>=2 且 DD+DE>=2 且 CA=0 去H<br>- SS系>=1 去I<br>- BB系+CV系>=1 去J<br>- `神风`+`羽黑`=2<br>&nbsp;&nbsp;- 舰队船数<=4 去P<br>&nbsp;&nbsp;- DD<=2 去J<br>&nbsp;&nbsp;- 低速舰队 去J<br>&nbsp;&nbsp;- [高速+]以上的舰队 去P<br>&nbsp;&nbsp;- CA系>=3<br>&nbsp;&nbsp;&nbsp;&nbsp;- `足柄`+妙高+高雄=2 去K<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去J<br>&nbsp;&nbsp;- CA系<=2<br>&nbsp;&nbsp;&nbsp;&nbsp;- `足柄`=1 去P<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去K<br>- `神风`+`羽黑`<=1<br>&nbsp;&nbsp;- 低速舰队 去J<br>&nbsp;&nbsp;- DD<=2 去J<br>&nbsp;&nbsp;- CA系>=3 去J<br>&nbsp;&nbsp;- 其余去I |
| I | - SS系>=1 去J<br>- BB系+CV系>=1 去J<br>- CA系>=3 去J<br>- DD+DE=0 去J<br>- `神风`+`羽黑`=2<br>&nbsp;&nbsp;- DD+DE>=3<br>&nbsp;&nbsp;&nbsp;&nbsp;- [高速+]以上的舰队 去J<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去M<br>&nbsp;&nbsp;- DD+DE=2<br>&nbsp;&nbsp;&nbsp;&nbsp;- [最速]的舰队 去M<br>&nbsp;&nbsp;&nbsp;&nbsp;- 其余去L<br>&nbsp;&nbsp;- DD+DE=1 去L<br>- `神风`+`羽黑`<=1<br>&nbsp;&nbsp;- DD>=3 且 [最速]的舰队 去J<br>&nbsp;&nbsp;- `神风`+`羽黑`+`足柄`=2 且 DD+DE>=3 去M<br>&nbsp;&nbsp;- 其余去L |
| J | - BB系+CV系>=1 去M<br>- 低速舰队 去M<br>- DD<=1 去M<br>- DD=2<br>&nbsp;&nbsp;- `神风`+`羽黑`+`足柄`+妙高+高雄=5 去P<br>&nbsp;&nbsp;- CA系>=4 去M<br>&nbsp;&nbsp;- `神风`+`羽黑`+`足柄`=3 去P<br>&nbsp;&nbsp;- 其余去M<br>- DD>=3<br>&nbsp;&nbsp;- `神风`+`羽黑`+`足柄`>=2 去P<br>&nbsp;&nbsp;- CA系>=3 去M<br>&nbsp;&nbsp;- 其余去P |
| M | - CV+CVB>=1 去N<br>- `神风`+`羽黑`+`足柄`=3 且 BB+FBB+CVL=0 去P?<br>- BB系+CVL>=2 去N<br>- SS系>=4? 去N<br>- BB=1 去O<br>- AO>=1 去O<br>- AV>=2 去O<br>- 其余去P |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| (P1)1->A->C->E | 0 | 0 | 羽黑+神风+1DD+1CA系/CL系/AV |
| (P2)1->A->C->D->G->P | 0 | 0 | 羽黑+足柄+神风+2DD+1CL/AV, 高速 |

### 7-4 昭南本土航路 `ヒ船団海上護衛作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD7-4.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - SS系>=1 去C<br>- BB+FBB+CV+CVB>=1 去C<br>- CA系>=2 去C<br>- CL系>=2 去C<br>- LHA>=1 且 DD+DE>=3 且 DE>=2 去A<br>- BBV+CVL+あきつ丸>=3 去C<br>- DD+DE>=3 去A<br>- DE>=2 去A<br>- 其余去C |
| C | - SS系>=1 去D<br>- BB+FBB+CV+CVB>=1 去D<br>- CVL+あきつ丸>=3 去D<br>- DD+DE>=4 去E<br>- DD+DE>=3 且 CT>=1 去E<br>- DE>=3 去E<br>- DD>=2 且 [高速+]以上舰队 去E<br>- 其余去D |
| E | - CVL+あきつ丸>=2 去J<br>- AO+LHA=0 去J<br>- 大鹰级+AO+LHA+CT+DD+DE<=5 去J<br>- DE>=4 去G<br>- CT>=1 且 DE>=3 去G<br>- 其余去J |
| G | - 分歧点系数=4<br>&nbsp;&nbsp;- 索敌>=37? 去L<br>&nbsp;&nbsp;- 33<=索敌<37? 随机去I/L<br>&nbsp;&nbsp;- 索敌<33? 去I |
| J | - 分歧点系数=4<br>&nbsp;&nbsp;- 索敌<33 去K<br>&nbsp;&nbsp;- 33<=索敌<37 随机去K<br>&nbsp;&nbsp;- 去K判定失败 或 索敌>=37 继续下面的判定<br>- 经过F点的舰队 去K<br>- 舰队只包含DE 去P?<br>- 舰队船数=3 且 DD=1 且 DE=2 去P?<br>- 舰队船数=4 且 大鹰级=1 且 DE=3 去P?<br>- 舰队船数=5<br>&nbsp;&nbsp;- 大鹰级+CT+DD+DE=5 且 大鹰级=1 且 DE>=3 去P?<br>&nbsp;&nbsp;- 大鹰级+CT+DD+DE=5 且 DD=1 且 DE>=3 去P?<br>- 其余去L |
| K | - 目前全部K-M, 没有K-P的数据 |
| M | - CT=1 且 DE>=3 且 大鹰级+CT+DD+DE=5 且 舰队船数=5 去P?<br>- 分歧点系数=4<br>&nbsp;&nbsp;- 索敌<45 去N<br>&nbsp;&nbsp;- 45<=索敌<47 随机去N<br>&nbsp;&nbsp;- 去N判定失败 或 索敌>=47 继续下面的判定<br>- 分歧点系数=4 索敌<`57`? 去O<br>- BB+CV+CVB>=1 去O<br>- FBB>=2 去O<br>- BBV>=2 去O<br>- CVL+あきつ丸>=2 去O<br>- AV>=2 去O<br>- CA系>=3 去O<br>- DD+DE<=1 去O<br>- 其余去P |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->A->B->E->J->L->P | 37<sub>4</sub> | 300 | 3DD+1CL+2CVL |

### 7-5 ジャワ島沖 `スラバヤ沖海戦・バタビア沖海戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD7-5.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| B | - [高速+]或以上的舰队 去D<br>- CV+CVB>=2 去C<br>- BB>=2 去C<br>- CL=0 去C<br>- DD+DE<=1 去C<br>- DD+DE>=3 去D<br>- CV+CVB>=1 去C<br>- CVL>=2 去C<br>- BB系>=3 去C<br>- CA系>=3 去C<br>- 其余去D |
| D | - [最速]舰队 去F<br>- BB系+CV+CVB+CA系>=3 去E<br>- CV系>=3 去E<br>- CV+CVB>=2 去E<br>- CL+DD+DE=0 去E<br>- [高速+]舰队 去F<br>- CL+DD+DE=1 去E<br>- 高速舰队 去F<br>- CL>=1 且 DD+DE>=3 去F<br>- BB系+CV+CVB>=2 去E<br>- SS系>=1 去E<br>- 其余去F |
| I | - 分歧点系数=4, 设固定去M的索敌值>=x<br>&nbsp;&nbsp;- 基础x=55, 在满足下列条件时, x取其中的最大值<br>&nbsp;&nbsp;- CV系=1, x=60<br>&nbsp;&nbsp;- BB系>=2, x=65<br>&nbsp;&nbsp;- CV系>=2, x=70<br>- 索敌在x-2~x之间, 随机去M/L<br>- 索敌小于x-2 固定去L |
| J | - CVL=1 且 CA系=2 且 CL=1 且 DD+DE=2 去O<br>- [高速+]或以上的舰队 去O<br>- CV+CVB>=1 去N<br>- CVL>=3 去N<br>- BB>=2 去N<br>- BB系+CA系>=3 去N<br>- DD+DE<=1 去N<br>- DD+DE>=3 去O<br>- 高速舰队 去O<br>- 其余去N |
| P | - 分歧点系数=4, 设固定不去S的索敌值>=x<br>&nbsp;&nbsp;- 基础x=58, 在满足下列条件时, x取其中的最大值<br>&nbsp;&nbsp;- CV系=1, x=63<br>&nbsp;&nbsp;- BB系>=2, x=68<br>&nbsp;&nbsp;- CV系>=2, x=73<br>&nbsp;&nbsp;- (司令部系数应为0.35, 基础64)<br>- 索敌在x-2~x之间, 随机去S<br>- 索敌小于x-2 固定去S<br>- [最速]舰队 去T<br>- CV+CVB>=1 去R<br>- BB系+CVL>=2 去R<br>- BB系+CA系>=3 去R<br>- CL=0 去R<br>- 其余去T |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| (P1)1->A->B->D->F->G->H->K | 0 | 0 | 1BBV+1CAV+1AV+1CL+2DD |
| 1->A->B->D->F->G->H->I->M | 0 | 0 | 1BBV+1CAV+1AV+1CL+2DD |
| (P2)1->A->B->D->F->J->O->Q | 0 | 0 | 1BBV+1CAV+1CL+3DD |
| (P3)1->A->B->D->F->J->O->P->T | 0 | 0 | 1BBV+1CAV+1AV+1CL+2DD, 高速 |
