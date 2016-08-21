听完网易[《可汗学院公开课：概率》](http://open.163.com/special/Khan/probability.html])，课程整体来讲通俗易懂，适合没有基础的人来听，也可以用来回顾曾经学过的知识。每个知识点有单独的小节，学起来很轻松，讲解也比较生动。不足之处，就是内容有很多重复的地方，章节安排是不够严谨，如果概率论学过或者有一定基础，可以一边快进一边看，适当跳过部分内容。

---

### 泊松分布

以下摘自维基百科：

[泊松分布](https://zh.wikipedia.org/zh-hans/%E6%B3%8A%E6%9D%BE%E5%88%86%E4%BD%88)

在[二项分布](https://zh.wikipedia.org/wiki/%E4%BA%8C%E9%A1%B9%E5%88%86%E5%B8%83)的[伯努利试验](https://zh.wikipedia.org/wiki/%E4%BC%AF%E5%8A%AA%E5%88%A9%E8%A9%A6%E9%A9%97)中，如果试验次数n很大，二项分布的概率p很小，且乘积λ= *np*比较适中，则事件出现的次数的概率可以用泊松分布来逼近。事实上，二项分布可以看作泊松分布在离散时间上的对应物。

证明如下。首先，回顾*e*的定义：

 ![163448ac05b0672de07336945cf8c0e8fbcbf508](/Users/u2/Desktop/163448ac05b0672de07336945cf8c0e8fbcbf508.svg)


二项分布的定义：

 ![94cdf18e27c5641888c81d31d97dd447dbaa72fe](/Users/u2/Desktop/94cdf18e27c5641888c81d31d97dd447dbaa72fe.svg)

如果令 ![p = \lambda/n](https://wikimedia.org/api/rest_v1/media/math/render/svg/138086d0e6e280e1f03522ff76266e2b730b200d), ![n](https://wikimedia.org/api/rest_v1/media/math/render/svg/a601995d55609f2d9f5e233e36fbe9ea26011b3b)趋于无穷时![P](https://wikimedia.org/api/rest_v1/media/math/render/svg/b4dc73bf40314945ff376bd363916a738548d40a)的极限：

 ![7f3305a795ed8b2ce32f86487f67b44ecd5f69cb](/Users/u2/Desktop/7f3305a795ed8b2ce32f86487f67b44ecd5f69cb.svg)



相关链接：

泊松分布1：http://open.163.com/movie/2011/3/O/C/M82IF3HFQ_M83C5Q1OC.html

泊松分布2：http://open.163.com/movie/2011/3/7/A/M82IF3HFQ_M83C67I7A.html

泊松分布：https://zh.wikipedia.org/zh-hans/%E6%B3%8A%E6%9D%BE%E5%88%86%E4%BD%88

延伸阅读：泊松分布与美国枪击案：http://www.ruanyifeng.com/blog/2013/01/poisson_distribution.html

### 贝叶斯定理

概率8：http://open.163.com/movie/2011/3/U/V/M82IF3HFQ_M83212GUV.html

以下摘自维基百科：

## 陈述

贝叶斯定理是关于随机事件A和B的[条件概率](https://zh.wikipedia.org/wiki/%E6%9D%A1%E4%BB%B6%E6%A6%82%E7%8E%87)的一则定理。


其中P(A|B)是在B发生的情况下A发生的可能性。

在贝叶斯定理中，每个名词都有约定俗成的名称：

- P(*A*|*B*)是已知B发生后A的[条件概率](https://zh.wikipedia.org/wiki/%E6%9D%A1%E4%BB%B6%E6%A6%82%E7%8E%87)，也由于得自B的取值而被称作A的[后验概率](https://zh.wikipedia.org/wiki/%E5%90%8E%E9%AA%8C%E6%A6%82%E7%8E%87)。
- P(*B*|*A*)是已知A发生后B的条件概率，也由于得自A的取值而被称作B的[后验概率](https://zh.wikipedia.org/wiki/%E5%90%8E%E9%AA%8C%E6%A6%82%E7%8E%87)。
- P(*A*)是A的[先验概率](https://zh.wikipedia.org/wiki/%E5%85%88%E9%AA%8C%E6%A6%82%E7%8E%87)或（或[边缘概率](https://zh.wikipedia.org/wiki/%E8%BE%B9%E7%BC%98%E6%A6%82%E7%8E%87)）。之所以称为"先验"是因为它不考虑任何B方面的因素。
- P(*B*)是B的[先验概率](https://zh.wikipedia.org/wiki/%E5%85%88%E9%AA%8C%E6%A6%82%E7%8E%87)或边缘概率。

按这些术语，贝叶斯定理可表述为：


也就是说，后验概率与先验概率和相似度的乘积成正比。

另外，比例P(*B*|*A*)/P(*B*)也有时被称作标准相似度（standardised likelihood），贝叶斯定理可表述为：

## 从条件概率推导贝氏定理

根据[条件概率](https://zh.wikipedia.org/wiki/%E6%9D%A1%E4%BB%B6%E6%A6%82%E7%8E%87)的定义。在事件*B*发生的条件下事件*A*发生的概率是[[1\]](https://zh.wikipedia.org/zh-hans/%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%AE%9A%E7%90%86#cite_note-1)：

 ![c7f0ff7bcd50dd11514f9f02b1273dab360a4cef](c7f0ff7bcd50dd11514f9f02b1273dab360a4cef.svg)


同样地，在事件*A*发生的条件下事件*B*发生的概率

 ![087dafd1afed425d2acb943da2e708603639eef7](087dafd1afed425d2acb943da2e708603639eef7.svg)


整理与合并这两个方程式，我们可以找\到

 ![0eba64686e8cab42885e8c317968d3ea93124d48](0eba64686e8cab42885e8c317968d3ea93124d48.svg)


这个引理有时称作概率乘法规则。上式两边同除以P(*A*)，若P(*A*)是非零的，我们可以得到贝叶斯 定理:

 ![d52ddeb606fd9f4f5659836d538a351c3201d02e](d52ddeb606fd9f4f5659836d538a351c3201d02e.svg)


链接：

贝叶斯定理：https://zh.wikipedia.org/wiki/%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%AE%9A%E7%90%86

延伸阅读：

贝叶斯推断及其互联网应用（－）：http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_one.html

贝叶斯推断及其互联网应用（二）：http://www.ruanyifeng.com/blog/2011/08/bayesian_inference_part_two.html



