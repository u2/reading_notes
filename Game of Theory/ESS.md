## ESS

### Evolutionary Stability Strategy的定义之一：

在一个2-player，对称策略中，纯策略 s 是 ES 的，那么它满足：

1）如果 (s, s) 是 NE，那么 u(s,s) >= u(s', s')，在对所有 s‘，s’表示突变策略，并且

2）如果 (s, s) 不是严格的 NE，也就是 u (s,s) >= u (s',s') ，存在  u (s,s) = u (s',s')  的策略，那么必须 u (s,s‘) > u (s',s') 

### Hawk-Dove (同物种的策略)

|      | H            | D        |
| ---- | ------------ | -------- |
| H    | v-c/2, v-c/2 | v, 0     |
| D    | 0, v         | v/2, v/2 |

(Prize v > 0, Cost of fight c > 0)

1. is Dove an ESS?
   * (D,D) is NE? No, so it is not ESS?
2. Is H and ESS?
   * if v>c, H is an ESS.
3. if c > V?

假设一个对称混合NE为U(p, 1-p)
$$
\begin{cases}
u(h, p) = p(v-c)/2 + (1-p)/v \\
u(d, p) = p*0 + (1-p)v/2
\end{cases}
$$
求得 p = v/c

Identification: we can tell what v/c is from data!!

结论：我们可以通过数据来算出v/c



|      | S    | B    | T    |
| ---- | ---- | ---- | ---- |
| S    | 1,1  | v,0  | 0,v  |
| B    | 0,v  | 1,1  | v,0  |
| T    | v,0  | 0,v  | 1,1  |

（1< V< 2)

唯一可能的ESS是 u(1/3,1/3,1/3)，pay off 是 (1+v)/3

但是因为u(s,s)的收益是1，大于u(1/3,1/3,1/3)，所以唯一存在的ESS策略也不是stable的。

所以不存在ESS。在自然界中意义在于，是一个不断循环的过程。

自然选择，并不是一个绝对的大自然筛选，存在群体博弈，而个体的变异和选择又是随机化的。

