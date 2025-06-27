---
date: '2025-06-15T13:14:48Z'
draft: false
title: '鎮守府海域(1-X)'
weight: 1
---

### 1-1 鎮守府正面海域 `近海警備`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD1-1.webp)

{{% details title="分歧条件" closed="true" %}}

| 舰队船数 | 去B概率 | 去C概率 |
| --- | --- | --- |
| 1 | 20% | 80% |
| 2 | 25% | 75% |
| 4 | 35% | 65% |
| 5 | 40% | 60% |
| 6 | 45% | 55% |

{{% /details %}}


### 1-2 南西諸島沖 `南西諸島沖警備`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD1-2.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | 舰队船数<=5 且 DD+DE=4 去A |
| A | - 高速以上舰队 去E<br>- DD+DE<=3 去D<br>- DD+DE=6 去E<br>- CL+CT=1 且 DD+DE=5 去E<br>- CL=1 且 DD=4 去E<br>- 其余65%去E, 35%去D |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->A->E | 0 | 0 | 1CL+4DD |

### 1-3 製油所地帯沿岸 `海上護衛作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD1-3.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - AO>=1 去A<br>- AV>=1 去A<br>- CV系>=1 去C<br>- 其余50%去A, 50%去C |
| A | - AO>=1去D<br>- DE>=4 去D<br>- AV>=1 80%去D, 20%去E<br>- DD+DE>=4 80%去D, 20%去E<br>- DD+DE<=3<br>&nbsp;&nbsp;- SS系>=1 去E<br>&nbsp;&nbsp;- 其余50%去D, 50%去E<br> |
| F | - CV+CVB>=1 去H<br>- BB>=1 去H<br>- DD>=4 去J<br>- CAV>=1 且 DD>=2 去J<br>- CL+CT>=1 且 DD+DE>=4 去J<br>- CA系>=4 25%去H, 75%去J?<br>- CL系>=1 且 DD>=2 且 CL系+DD=舰队船数 25%去H, 75%去J<br>- BBV>=1 75%去H, 25%去J<br>- AO+LHA>=1 75%去H, 25%去J<br>- SS系>=1 75%去H, 25%去J<br>- DD+DE>=4 75%去H, 25%去J<br>- 其余50%去H, 50%去J |
| H | - AO>=1 去G<br>- AV>=1 去J<br>- CAV>=1 去J<br>- CL+CT>=1<br>&nbsp;&nbsp;- DD>=2 去J<br>&nbsp;&nbsp;- 其余65%去I, 35%去J<br>- CL+CT=0<br>&nbsp;&nbsp;- DD<=1 70%去I, 30%去J<br>&nbsp;&nbsp;- DD>=2 40%去G, 15%去I, 45%去J |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| *->F->J | 0 | 0 | 2CVL+4DD |

### 1-4 南西諸島防衛線 `南1号作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD1-4.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | 50%去A, 50%去B |
| B | - CV系>=3 去D<br>- BB系>=3 去D<br>- DD+DE=0 去D<br>- DD+DE>=3 去C<br>- AO>=1 且 DD+DE>=2 去C<br>- CL>=1 80%去C, 20%去D<br>- CL=0 60%去C, 40%去D |
| D | - AS>=1 去E<br>- AV>=1 去G<br>- 其余50%去E, 50%去G |
| F | - DD+DE>=4 去E<br>- DD+DE<=1 50%去H, 50%去I<br>- AV>=1 去E<br>- AO>=1 去E<br>- AS>=1 去E<br>- BBV>=2 去E<br>- DD+DE=3 80%去E, 20%去H<br>- DD+DE=2 60%去E, 40%去H |
| J | - CL>=1 且 AV>=1 且 DD+DE>=2 去L<br>- DD>=4 去L<br>- DD=`2~3` 75%去L, 25%去K<br>- DD=`0~1` 65%去L, 35%去K |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| *->D->E->H->L | 0 | 60 | 1AS+3DD+2CVL |
| *->J->L | 0 | 60 | 4DD+2(CVL/CL) |
| *->J->L | 0 | 60 | 1CL+1AV+2DD+2CVL |

### 1-5 鎮守府近海 `鎮守府近海対潜哨戒`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD1-5.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| C | - 舰队中只包含DE 去J<br>- SS系>=1 去B<br>- 舰队船数>=5 去B<br>- 舰队船数=`2~4` 随机去B/J?<br>- 舰队船数=1 去B |
| D | - 舰队船数=1 去E<br>- 舰队船数=2-4<br>&nbsp;&nbsp;- SS系>=1 去F<br>&nbsp;&nbsp;- AO>=1 去E<br>&nbsp;&nbsp;- 舰队中只包含DE 去E<br>&nbsp;&nbsp;- 其余去F<br>- 舰队船数=`5~6`<br>&nbsp;&nbsp;- SS系>=1 去F<br>&nbsp;&nbsp;- 其余65%去E，35%去F |
| E | - 舰队船数>=5 去C<br>- 舰队中只包含DE 去J<br>- 其余去C |
| F | - BB+FBB>=1 去I<br>- CV+CVB>=1 去I<br>- SS+SSV>=1 去I<br>- CVL>=2 去I<br>- CL>=3 去I<br>- 其余去G<br> |
| G | - 舰队船数<=4 去J<br>- 其余去H |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->A->D->E->J | 0 | 0 | 4DE |
| 1->A->D->F->G->J | 0 | 0 | 1(CVL/BBV/CL/DD)+3(DD/DE) |

### 1-6 鎮守府近海航路 `輸送船団護衛作戦`
![](https://r2.sakamoto.dpdns.org/imgs/MapHD1-6.webp)

{{% details title="分歧条件" closed="true" %}}

| 分岐点 | 条件 |
| --- | --- |
| 1 | - BBV+CVL+CA>=1 去C<br>- CAV>=2 去C<br>- DD+DE<=3 去C<br>- 其余去A |
| G | - CL=1 且 DD+DE=5 去F<br>- 75%去F，25%去K |
| M | - BBV+CA+CVL>=3 去L<br>- BBV+CA+CAV>=3 去L<br>- DD+DE<=2 去L<br>- 分岐点系数=3，30索敌以上去J(司令部系数0.35，36索敌)<br>&nbsp;&nbsp;- `28~30`索敌随机去J/L<br>&nbsp;&nbsp;- 28索敌以下去L |

{{% /details %}}

| 路线 | 索敌 | 制空 | 配置 |
| --- | --- | --- | --- |
| 1->A->E->G->F->B->N | 0 | 0 | 1CL+5(DD/DE) |
