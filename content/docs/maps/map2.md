---
date: '2025-06-15T13:14:48Z'
draft: false
title: '南西諸島海域(2-X)'
weight: 2
---

### 2-1 南西諸島近海 `南西諸島哨戒`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD2-1.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| C | - CV系>=3 去B<br>- BBV>=2 去B<br>- AO>=1 且 SS+SSV=0 去B<br>- BBV=1<br>&nbsp;&nbsp;- AV+AS>=1: 70%去B, 30%去E<br>&nbsp;&nbsp;- AV+AS=0: 70%去B, 30%去D<br>- BBV=0<br>&nbsp;&nbsp;- AV+AS>=1 去E<br>&nbsp;&nbsp;- AV+AS=0: 50%去D, 50%去E |
| E | - BB系+CV系>=5 去F<br>- 舰队船数=6<br>&nbsp;&nbsp;- BB系+CV系>=1 去D<br>&nbsp;&nbsp;- DD+DE=6 去H<br>&nbsp;&nbsp;- CL=1 且 DD+DE=5 去H<br>&nbsp;&nbsp;- CL=1 且 DD=4 且 高速舰队 去H<br>&nbsp;&nbsp;- 其余去D<br>- 舰队船数<=5<br>&nbsp;&nbsp;- DD+DE=5 去H<br>&nbsp;&nbsp;- CL=1 且 DD+DE=4 去H<br>&nbsp;&nbsp;- CL=1 且 DD=3 且 高速舰队 去H<br>&nbsp;&nbsp;- 其余60%去D, 40%去F |
| F | - BB系+CV系>=5 去G<br>- DD>=3 去H<br>- CL>=1 且 DD>=2 去H<br>- 其余40%去G, 60%去H |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->C->E->H | 0 | 162 | 1CL+1AV+4DD |
| 1->C->E->D->H | 0 | 0 | 6SS |

### 2-2 バシー海峡 `柳作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD2-2.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| C | - CV系>=3 去B<br>- BBV>=2 去B<br>- AO>=1 且 SS+SSV=0 去B<br>- BBV=1<br>&nbsp;&nbsp;- AV+AS>=1: 70%去B, 30%去E<br>&nbsp;&nbsp;- AV+AS=0: 70%去B, 30%去D<br>- BBV=0<br>&nbsp;&nbsp;- AV+AS>=1 去E<br>&nbsp;&nbsp;- AV+AS=0: 50%去D, 50%去E |
| E | - BB系+CV系>=4 去G<br>- DE>=2 去F<br>- BB系+CV系=3: 70%去G, 30%去K<br>- BB系+CV系=2: 50%去G, 50%去K<br>- BB系+CV系=1: 30%去G, 70%去K<br>- BB系+CV系=0<br>&nbsp;&nbsp;- DD+DE>=3 且 AS>=1 去F<br>&nbsp;&nbsp;- DD+DE>=2 且 CL>=1 且 高速舰队 去K<br>&nbsp;&nbsp;- DD+DE>=2: 30%去F, 70%去K<br>&nbsp;&nbsp;- 其余50%去G, 50%去K |
| G | - CV系>=1 去H<br>- DD=0 去H<br>- BB系>=3: 70%去H, 30%去K?<br>- BB系<=2: 30%去H, 70%去K? |
| H | - BB系+CV系>=4: 约60%去I, 40%去K<br>- CV系+AV+CAV>=1 去K<br>- SS系>=1: 约70%去I, 30%去K<br>- DD+DE=0: 随机去I/K<br>- DD+DE=1: 随机去I/J/K<br>- DD+DE>=2: 随机去J/K |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->C->E->F->H->K | 0 | 81 | 1SS+2CVL+1AV+2DE |
| 1->C->E->K | 0 | 81 | 1CL+1AV+4DD 高速 |

### 2-3 東部オリョール海 `オリョール哨戒`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD2-3.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - 舰队中只包含AS和SS系 去C<br>- 其余50%去A, 50%去B |
| C | - 60%去D, 40%去F |
| D | - AV+AO>=1 且 DD+DE>=2 去G<br>- AS>=1 且 SS+SSV>=2 去G<br>- 舰队中只包含SS系 35%去F, 65%去G |
| F | - CV系+AV>=1 90%去J, 10%去G<br>- CL>=1 80%去J, 20%去G<br>- AO>=1 35%去J, 65%去G?<br>- AS>=1 且 SS系>=2 35%去J, 65%去G<br>- 其余35%去H, 42.25%去J, 22.75%去G |
| G | - 舰队中只包含AS和SS系 55%去I, 45%去K<br>- AS>=1 且 SS系>=2 60%去I, 40%去K<br>- AV+AO>=1 且 DD+DE>=2 65%去I, 35%去K<br>- CL+DD+DE<=1 去K |
| J | - 舰队中只包含SS系 10%去M, 90%去N<br>- BB系+CV系=6 去L<br>- BB系+CV系=5 80%去L<br>- CL=1 且 CA=5 去N<br>- CL>=1 且 DD+DE>=4 去N<br>- DD+DE>=3 80%去N<br>- CA系>=4 65%去N<br>- CAV>=1 65%去N<br>- AV>=1 65%去N<br>- CV系>=1 65%去N<br>- CL>=1 50%去N<br>- SS系>=1 35%去M<br>- 其余去L |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| * | 0 | 162 | 3DD+2CVL+1AV |

### 2-4 沖ノ島海域 `あ号艦隊決戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD2-4.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| B | - AO=1 且 CA+CAV=1 且 CL+CT=1 且 DD+DE=3 去G<br>- CL+CT=1 且 DD+DE>=4 且 DD+DE+CL+CT+CA+CAV=6 去G<br>- DD=6 去G<br>- DD+DE=3 60%去G<br>- BB系+CV+CVB>=3 去C<br>- CV系>=3 去C<br>- CV+CVB>=1 70%去C, 30%去G<br>- BB系>=2 70%去C, 30%去G<br>- SS系>=1 60%去C, 40%去G<br>- 其余40%去C, 60%去G |
| C | - AO+AS>=1 去G<br>- 其余50%去F, 50%去G |
| F | - CVL>=1 75%去J<br>- DD>=2 75%去J<br>- 其余去A |
| H | - CA+CAV+CL+CT+DD=6 且 CA+CAV<=1 且 CL+CT>=1 且 DD>=4 去L<br>- 其余去I |
| I | - DE>=2 约50%去E<br>- CVL>=1 70%去K<br>- CL>=1 60%去K<br>- 其余60%去E, 40%去K |
| J | - BB系+CV系>=4 去L<br>- BB系+CV系=3 去M<br>- BB系+CV系<=2<br>&nbsp;&nbsp;- CV+CVB=0 去L<br>&nbsp;&nbsp;- CV+CVB=1 35%去L, 65%去M<br>&nbsp;&nbsp;- CV+CVB=2 去M |
| K | - AO+AS>=2 去N<br>- AV+AO+AS>=1 且 DE>=2 去N?<br>- AV+AO+AS>=1 40%去N<br>- DE>=2 随机去N<br>- DD+DE>=2 去L<br>- BB系+CV系>=4 约50%去O<br>- DD+DE=1 65%去L<br>- DD+DE=0 35%去L<br>- 其余去O |
| L | - BB系+CV系=4 去M<br>- BB系+CV+CVB<=2 去P<br>- CL=1 且 DD=2 去P<br>- 其余60%去M, 40%去P |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->B->G->H->L->P | 0 | 168 | 1CAV+1CL+4DD |
| *->L->P | 0 | 168 | 2CVL+1CLT+1CL+2DD |

### 2-5 沖ノ島沖 `沖ノ島沖戦闘哨戒`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD2-5.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - SS系>=4 去B<br>- SS系>=1 随机去B/C<br>- 舰队船数<=2 去C<br>- CV系>=1 去C<br>- AV>=2 去C<br>- 装备[ドラム缶]的船数>=2 去B<br>- DD+DE>=4 去B<br>- CL>=1 且 DD+DE>=3 去B<br>- BB系>=1 去C<br>- DD+DE>=3: 约80%去B, 20%去C<br>- DD+DE=2<br>&nbsp;&nbsp;- CA系<=3 且 CL=0 去C<br>&nbsp;&nbsp;- 其余约80%去B, 20%去C<br>- DD+DE=1<br>&nbsp;&nbsp;- CL>=3 去B<br>&nbsp;&nbsp;- CL=0 去C<br>&nbsp;&nbsp;- CA系=2 去C<br>&nbsp;&nbsp;- 其余约80%去B, 20%去C<br>- DD+DE=0<br>&nbsp;&nbsp;- CL+CLT+AV>=1 且 CA系>=2 去C<br>&nbsp;&nbsp;- 其余15%去B, 85%去C |
| B | - SS系>=3 去A<br>- 其余去F |
| C | - BB系>=3 去D<br>- CV系>=3 去D<br>- DD>=2<br>&nbsp;&nbsp;- CL>=1去E<br>&nbsp;&nbsp;- CAV>=2去E<br>- 其余30%去D, 70%去E |
| E | - BB系>=1 去G<br>- CV+CVB+CA+CAV>=2 去G<br>- CL>=1 且 DD+DE>=4 去I<br>- CL>=1 且 DD+DE>=3 且 高速舰队 去I<br>- 其余去G |
| F | - 低速舰队 去J<br>- DD>=3 去E<br>- CL>=1 且 DD>=2 去E<br>- BB系>=3 去J<br>- DD=2: 约50%去E, 50%去J<br>- 其余35%去E, 65%去J |
| G | - DD>=4 且 BB系+CV系<=1 去I<br>- DD=3 且 CL>=1 且 BB系+CV系=0 去I<br>- 分歧点系数=1, 索敌>=41 去L<br>- 索敌<35 去K<br>- 索敌`35~41`之间 随机去K/L |
| I | - 分歧点系数=1, 索敌>=34 去O<br>- 索敌`33~34`之间65%去O, 35%去H<br>- 索敌`31~33`之间35%去O, 65%去H<br>- 索敌<31 去H |
| J | - 分歧点系数=1, 索敌<42 去H<br>- `42~49`之间随机去H, 索敌越高去H概率越低<br>- 索敌>=49 或 去H判定失败<br>&nbsp;&nbsp;- SS系>=1 随机去M/O<br>&nbsp;&nbsp;- DE>=3 去M?<br>&nbsp;&nbsp;- BB系<=3 去O<br>&nbsp;&nbsp;- 其余随机去M/O |
| L | - CL>=1 且 DD>=2 去O<br>- BB系+CV系=0: 约40%去N, 60%去O<br>- BB系+CV系>=1: 约60%去N, 40%去O |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->C->E->I->O | 34<sub>系数1</sub> | 168 | 1CV+1CVL+1CL+3DD 高速 |
| 1->B->F->J->O | 49<sub>系数1</sub> | 168 | 1BBV+3CA+1CAV(ド)+1CL(ド) 低速 |
