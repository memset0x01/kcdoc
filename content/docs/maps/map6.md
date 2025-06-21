---
date: '2025-06-15T13:14:48Z'
draft: false
title: '中部海域(6-X)'
weight: 7
---

### 6-1 中部海域哨戒線 `潜水艦作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD6-1.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - BB系+CV系+CA系>=3 去B<br>- BB系>=2 去B<br>- SS系>=3 且 SS系=舰队船数 去A<br>- AS=1 且 SS系>=3 且 AS+SS系=舰队船数 去A<br>- AS=1 且 SS系=3 且 DD=2 去A<br>- AS=1 且 SS系=4 且 CL+DD=1 去A<br>- CL+DD=0 去B<br>- 其余去C |
| A | - AS>=1 去F<br>- 其余去D |
| G | - SS+SSV<=2去I<br>- BB系+CV系+CA系>=2去I<br>- AS=0, 15%去I<br>- 去I判定失败<br>&nbsp;&nbsp;- 分歧点系数=4<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌>=`16`去H<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌<`12`去I<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌`12~16`随机去H/I |
| H | - AS>=1<br>&nbsp;&nbsp;- 分歧点系数=4<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌>=`25`去K(司令部系数0.35, 索敌>=`31`)<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌<`20`去E<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌`20~25`随机去K/E<br>- AS=0<br>&nbsp;&nbsp;- 分歧点系数=4<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌>=`36`去K(司令部系数0.35, 索敌>=`42`)<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌`25~36`随机去J/K<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌`20~25`随机去E/J/K<br>&nbsp;&nbsp;&nbsp;&nbsp;- 索敌<`20`去E |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->C->F->G->H->K | 25<sub>4</sub> | 126 | 3SS+CV+1CL+1CLT |
| 1->A->F->G->H->K | 25<sub>4</sub> | 126 | 大鲸+1CL+4SS系 |

### 6-2 MS諸島沖 `MS諸島防衛戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD6-2.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - CL+DD>=4 去B<br>- BBV+CAV+AV+LHA>=2 去C<br>- BB系+CV系>=5 去B<br>- BB系+CV系=4: 65%去B, 35%去C<br>- BB系+CV系<=3 去C |
| B | - CL+DD>=5 去D<br>- CV系>=3 去C<br>- BB系>=1 去C<br>- 其余70%去C, 30%去D |
| C | - BB系+CV系>=5 去A<br>- BB系+CV系+CA系=6 去A<br>- BB系+CV系+SS系=6 去A<br>- BB系+CV系>=3 去D<br>- 其余去E |
| D | - BB系+CV系>=1 去F<br>- DD<=2 去F<br>- CL+DD<=4 去F<br>- 其余去H |
| E | - DD<=1 去F<br>- BB系>=2 去F<br>- CV系>=2 去F<br>- 分歧点系数=3<br>&nbsp;&nbsp;- 索敌>=`50` 去J<br>&nbsp;&nbsp;- 索敌`43~50` 随机去I/J<br>&nbsp;&nbsp;- 索敌<`43` 去I |
| H | - 分歧点系数=3, 样本太少索敌边界不明<br>&nbsp;&nbsp;- 可能`40`以上去K |
| I | - SS系>=4 去G<br>- 分歧点系数=3<br>&nbsp;&nbsp;- 索敌>=`40` 去K<br>&nbsp;&nbsp;- 索敌`35~40` 随机去K/G<br>&nbsp;&nbsp;- 索敌<`35` 去G |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->C->E->I/J->K | 50<sub>3</sub> | 153 | 1BB+1CV+2DD+2CA/CAV/CLT |

### 6-3 グアノ環礁沖海域 `K作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD6-3.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| E | - CL>=3 去F<br>- AV>=2 去F<br>- CL<=1 且 DD>=3 去G<br>- 其余60%去F, 40%去G |
| H | - 分歧点系数=3<br>&nbsp;&nbsp;- 索敌>=`38` 去J<br>&nbsp;&nbsp;- 索敌`36~38` 随机去J/I<br>&nbsp;&nbsp;- 索敌<`36` 去I |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->A-C-E-G-H-J | 38<sub>3</sub> | 0 | 1AV+1CL+4DD |
| 1->A-C-E-F-H-J | 38<sub>3</sub> | 0 | 1AV+3CL+2DD |

### 6-4 中部北海域ピーコック島沖 `離島再攻略作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD6-4.webp)

{{% details title="分歧条件" closed="true" %}}

> 1=左側, 2=右側

| 分岐点 | 条件 |
| --- | --- |
| 1 | - LHA>=1 从2出发<br>- CV系>=1 从2出发<br>- CAV>=3 从2出发<br>- DD<=1 从2出发<br>- BB系>=2 且 舰队中包含`长门改二`/`陆奥改二`以外的BB系 从2出发<br>- 其余从1出发 |
| 1 | - 低速舰队 去A<br>- CL旗舰 且 DD>=3 去B<br>- DD>=4 去B<br>- 其余去A |
| A | - 舰队中包含 `秋津洲`<br>&nbsp;&nbsp;- CAV=1 去D<br>&nbsp;&nbsp;- CL>=1 去D<br>&nbsp;&nbsp;- DD>=3 去D<br>&nbsp;&nbsp;- 其余去E<br>- 舰队中不包含 `秋津洲`<br>&nbsp;&nbsp;- BB系>=1 去E<br>&nbsp;&nbsp;- 低速舰队 去E<br>&nbsp;&nbsp;- CL旗舰 去D<br>&nbsp;&nbsp;- DD>=3 去D<br>&nbsp;&nbsp;- 其余去E |
| E | - 舰队中包含 `秋津洲` 去D<br>- 舰队中包含 `如月` 去D<br>- 低速舰队 去G<br>- CAV=2 去G<br>- CA>=2 去G<br>- CL=0 去G<br>- 其余去D |
| J | - CL=0 去L<br>- DD<=1 去L<br>- BB系+CV系>=3 且 `长门改二`+`陆奥改二`<=1 去L<br>- LHA>=1 去N<br>- CV系<=1 去I<br>- 高速舰队 去I<br>- 低速舰队 去L |
| K | - BB系>=2 去H<br>- BB系+CA系>=3 去H<br>- DD<=1 去H<br>- 其余去J |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->B->D->C->F->N | 0 | 0 | CL旗舰+3DD+1CL+1BB系, 高速 |
| - | 0 | 0 | 4DD+1CL+1BB系, 高速 |
| - | 0 | 0 | CL旗舰+3DD+长门改二+陆奥改二 |
| - | 0 | 0 | 4DD+长门改二+陆奥改二 |
| 1->A->D->C->F->N | 0 | 0 | 秋津洲+2DD+1CL/CAV+1BB系+1CL系 |
| - | 0 | 0 | 秋津洲+2DD+1CL/CAV+长门改二+陆奥改二 |
| 2->M->K->J->I->N | 0 | 396 | 1CV+1BB系+1CAV+1CL+2DD |

### 6-5 KW環礁沖海域 `空母機動部隊迎撃戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD6-5.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - CV系>=1 从1出发<br>- CLT>=1 从1出发<br>- BB系>=4 从1出发<br>- CL=0 从1出发<br>- 其余从2出发 |
| B | - BB系>=3 去C<br>- DD<=1 去C<br>- 其余去F |
| C | - DD=0 去E<br>- BB系+CV系>=4 去E<br>- BB系+CV系+CA系>=5 去E<br>- CLT>=2 去E<br>- 其余去D |
| E | - DD=0 去I<br>- CL=0 去I<br>- CV系=0 去I<br>- 其余去H |
| G | - 分歧点系数=3, 索敌>=50去M<br>- 索敌不足, 去K |
| I | - CL=0 去H<br>- DD>=2 去J<br>- BB系>=1 去H<br>- CV系>=3 去H<br>- CV系+CA系>=5 去H<br>- 其余去J |
| J | - 分歧点系数=3, 索敌>=35去M<br>- 索敌不足, 去L |
{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->B->F->I->J->M | 35<sub>3</sub>sub> | 158 | BB+BBV+CL+CAV+2DD |
