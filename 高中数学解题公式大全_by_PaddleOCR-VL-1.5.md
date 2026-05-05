## 第 1 章 集合、命题、不等式、复数

1、有限集合子集个数：子集个数：$2^{n}$个，真子集个数：$2^{n-1}$个；

2、集合里面重要结论：
①$A \cap B = A \Rightarrow A \subseteq B$；②$A \cup B = A \Rightarrow B \subseteq A$；③$A \Rightarrow B \Leftrightarrow A \subseteq B$；④$A \Leftrightarrow B \Leftrightarrow A = B$
3、同时满足求交集，分类讨论求并集

4、集合元素个数公式：$n(A \cup B) = n(A) + n(B) - n(A \cap B)$

5、常见的数集：Z：整数集；R：实数集；Q：有理数集；N：自然数集；C：复数集；其中正整数集：$Z^* = N^* = \{1, 2, 3, \ldots\}$

6、均值不等式：若 a, b > 0 时，则$a + b \geq 2\sqrt{ab}$; 若 a, b < 0 时，则$a + b \leq -2\sqrt{ab}$;

7、均值不等式变形形式：$a^{2}+b^{2}\geq2ab(a,b\in R)$；$\frac{b}{a}+\frac{a}{b}\geq2(ab>0)$；$\frac{b}{a}+\frac{a}{b}\leq-2(ab<0)$

8、积定和最小：若 ab = p 时，则$a + b \geq 2\sqrt{ab} = 2\sqrt{p}$

9、和定积最大：若$a+b=k$时，则$ab \leq \frac{(a+b)^{2}}{4} = \frac{k^{2}}{4}$

10、基本不等式：$\frac{2}{\frac{1}{a}+\frac{1}{b}}\leq\sqrt{ab}\leq\frac{a+b}{2}\leq\sqrt{\frac{a^{2}+b^{2}}{2}}$

11、一元二次不等式的解法：大于取两边，小于取中间

12、含参数一元二次不等式讨论步骤：(1)二次项系数 a；(2)判别式$\Delta$；(3)两根$x_{1}, x_{2}$大小比较；(4)$x_{1}, x_{2}$与定义域的端点值值作比较（常用韦达定理）全部资料电子版在公众号：逆袭墙

13、一元二次不等式恒成立：(1)若$ax^{2}+bx+c>0$恒成立$\Leftrightarrow \left\{\begin{aligned}a&>0\\ \Delta&<0\end{aligned}\right.$

(2) 若$ax^{2} + bx + c \leq 0$恒成立$\Leftrightarrow \left\{\begin{aligned}a & < 0 \\ \Delta & \leq 0\end{aligned}\right.$

14、任意性问题：①$\forall x \in I, a > f(x) \Rightarrow a > f(x)_{\max}$②$\forall x \in I, a \leq f(x) \Rightarrow a \leq f(x)_{\min}$

15、存在性问题：①$\exists x \in I, a > f(x) \Rightarrow a > f(x)_{\min}$；②$\exists x \in I, a \leq f(x) \Rightarrow a \leq f(x)_{\max}$。

16、距离型目标函数：$d=\sqrt{(x-a)^{2}+(y-b)^{2}}$可行域内的点$(x,y)$到定点$(a,b)$的距离；

17、斜率型目标函数:$k=\frac{y-b}{x-a}$可行域内的点$(x,y)$到定点$(a,b)$的斜率；

18、线性型目标函数:$z = ax + by$过可行域内的点$(x, y)$且斜率为$-\frac{b}{a}$的直线截距的 b 倍;

19、p 是 q 充分不必要条件：$p \Rightarrow q, q \nRightarrow p$；则集合关系是：$p \subsetneq q$

20、$p$是$q$必要不充分条件：$q \Rightarrow p, p \nRightarrow q$；则集合关系是：$q \subsetneq 1$

21、p 是 q 既不充分也不必要条件：$p \neq q, q \neq p$；则集合关系是：p, q 无包含关系

22、p 是 q 充要条件：$p \Rightarrow q, q \Rightarrow p$；则集合关系是：p = q

23、全称命题及否定形式：$P:\forall x\in M,\Rightarrow p(x);\neg P:\exists x_{0}\in M,\exists\neg p(x_{0});$

24、特称命题及否定形式：$P: \exists x_0 \in M, \exists p(x_0); \neg P: \forall x \in M, \Rightarrow \neg p(x);$

25、命题否定形式的书写方法：任意变存在，存在变任意，条件不变，结论否定

26、共轭复数：$\overline{z}=a-bi$（实部相同，虚部相反），共轭复数的性质：$z\times\overline{z}=a^{2}+b^{2}$

27、复数模长：$|z|=|a+bi|=\sqrt{a^{2}+b^{2}}$

28、复数的除法：$\frac{z_{1}}{z_{2}}=\frac{z_{1}\cdot z_{2}}{z_{2}\cdot z_{2}}$（分子、分母同乘分母的共轭复数）

## 第 2 章 函数及导数

29、几个近似值：$\sqrt{2} \approx 1.414, \sqrt{3} \approx 1.732, \sqrt{5} \approx 2.236, \pi \approx 3.142, e \approx 2.718$

30、指数公式

(1)$a^{\frac{n}{m}}=\sqrt[m]{a^{n}}$

(2)$\sqrt[n]{a^n}=\begin{cases}|a| & n为偶数 \\ a & n为奇数\end{cases}$

31、对数公式

(1).$a^x = N \Leftrightarrow x = \log_a N$

(2).$a^{\log_{a}N}=N$

(3).$\log_{a}(MN)=\log_{a}M+\log_{a}N$

(4).$\log_{a}\left(\frac{M}{N}\right)=\log_{a}M-\log_{a}N$

(5).$\log_{a}M^{n}=n\log_{a}M$

(6).$\log_{a}a^{n}=n$

(7).$\log_{a}a=1$

(8).$\log_{a}1 = 0$

(9).$\log_{a^m} b^n = \frac{n}{m} \log_a b$

(10).$\log_{a}b = \frac{\log_{c}b}{\log_{c}a}$

(11).$\log_{a}b = \frac{1}{\log_{b}a}$

(12).$\log_{a}b\log_{b}c\log_{c}a=1$

32、函数定义域的求法

(1). 分式的分母$\neq 0$; 全部资料电子版在公众号: 逆袭墙

(2). 偶次方根的被开方数$\geq 0$;

(3). 对数函数的真数 > 0；

(4).0 次幂的底数$\neq 0$;

(5).正切函数的自变量$\neq\frac{\pi}{2}+k\pi$;

(6). 满足几个条件时列不等式组的求交集；

33、增函数的标志：①任意$x_{1}<x_{2}\Leftrightarrow f(x_{1})<f(x_{2})$；②导函数$f'(x)\geq0$；③$\frac{f(x_{1})-f(x_{2})}{x_{1}-x_{2}}>0$；

34、减函数的标志：①任意$x_{1}<x_{2}\Leftrightarrow f(x_{1})>f(x_{2})$；②导函数$f'(x)\leq0$：③$\frac{f(x_{1})-f(x_{2})}{x_{1}-x_{2}}<0$

35、单调性的快速法：①. 增 + 增 → 增；增—减 → 增；②. 减 + 减 → 减；减—增 → 减；

③.乘正加常，单调不变：④.乘负取倒，单调改变：

36、奇偶性的快速法：①. 奇±奇→奇；偶±偶→偶；

②. 奇$\times(\div)$奇$\rightarrow$偶；偶$\times(\div)$偶$\rightarrow$偶；奇$\times(\div)$偶$\rightarrow$奇；

37、常见的奇函数：$y = kx$，$y = \frac{k}{x}$，$y = \sin x$，$y = \tan x$，$y = x^{奇数}$，$y = \pm(e^{x} - e^{-x})$，$y = \ln(\sqrt{x^{2} + 1} - x)$

38、常见的偶函数：$y = C$，$y = x^2$，$y = \cos x$，$y = x^{偶数}$，$y = e^x + e^x$，$y = f(|x|)$

39、函数的周期性：$\forall x \in D \Rightarrow f(x+T) = f(x)$，则称$f(x)$为周期函数，其中 T 为函数的一个周期。

40、周期性标志：①.$f(x+a)=f(x+b)\Rightarrow T=\left|a-b\right|$；

②.$f(x+a)=-f(x)\Rightarrow T=2a$；

③.$f(x+a)=\pm\frac{1}{f(x)}\Rightarrow T=2a$

40、对称轴标志：$f(x+a)=f(b-x)\Rightarrow$对称轴为$x=\frac{a+x+b-x}{2}=\frac{a+b}{2}$；如常见的对称轴有：

$f(x+1)=f(1-x)\Rightarrow$对称轴为 x=1；$f(x)=f(2-x)\Rightarrow$对称轴为 x=1

41、对称中心标志：$f(x+a)=-f(b-x)\Rightarrow$对称中心为$\left(\frac{a+b}{2},0\right)$；如常见的对称中心有：$f(x+a)=-f(a-x)\Rightarrow$对称中心为$(a,0)$；$f(x+1)=-f(1-x)\Rightarrow$对称中心为$(1,0)$；

42、奇函数的周期是对称轴的 4 倍：以$y = \sin x$为例；

43、偶函数的周期是对称轴的 2 倍：以$y = \cos x$为例；

44、函数图像平移规则：横加左减右，纵加上减下；

45、函数图像翻折变换：$f(|x|)$：偶函数，右不变，右翻左；$|f(x)|$：上不变，下翻上；

46、函数图像伸缩变换：$f(wx)$：纵不变，横为原来的$\frac{1}{w}$倍；$Af(x)$：横不变，纵为原来的A倍；

47、零点存在性定理：函数$y = f(x)$在区间$(a, b)$有零点

$\Leftrightarrow 1$、函数$y = f(x)$在区间$(a, b)$连续；2、$f(a)f(b) < 0$

48、解与零点的关系：方程$f(x)=0$的解$\Leftrightarrow$函数$y=f(x)$的零点；

49、零点与交点的关系：函数$y = f(x) - g(x)$的零点个数

$\Leftrightarrow$方程$f(x)-g(x)=0$的解的个数；

$\Leftrightarrow$方程$f(x)=g(x)$的解的个数；

$\Leftrightarrow$函数$y_{1}=f(x)$,$y_{2}=g(x)$图像交点的个数；

注意：两个函数$y_{1}=f(x)$，$y_{2}=g(x)$图象可画，两函数为常见函数。

50、常函数的导数：$f(x)=C$，则$f'(x)=0$；全部资料电子版在公众号：逆袭墙

51、幂函数的导数：$f(x)=x^{\alpha}$，则$f'(x)=\alpha x^{\alpha-1}$;

52、正弦函数的导数：$f(x)=\sin x$，则$f'(x)=\cos x$；

53、余弦函数的导数：$f(x)=\cos x$，则$f'(x)=-\sin x$；

54、指数函数的导数：$f(x)=a^{x}$，则$f'(x)=a^{x}\ln a$；（特别地：$f(x)=e^{x}$，则$f'(x)=e^{x}$）

55、对数函数的导数：$f(x)=\log_{a}x$，则$f'(x)=\frac{1}{x\ln a}$；（特别地：$f(x)=\ln x$，则$f'(x)=\frac{1}{x}$）

56、和差求导数法则：$(f(x) \pm g(x))' = f'(x) \pm g'(x)$

57、乘法求导数法则：$[f(x)g(x)]' = f'(x)g(x) + f(x)g'(x)$

58、商的求导数法则：$\left[\frac{f(x)}{g(x)}\right]^{\prime}=\frac{f^{\prime}(x)g(x)-f(x)g^{\prime}(x)}{g^{2}(x)}$

59、复合函数求导法则：若$y = f[g(x)]$，令$t = g(x)$，则$y = f(t) \Rightarrow \sqrt{y' = f'(t)t' = f'[g(x)]g'(x)}$

60、切线 l 的方程：$y - y_{0} = f'(x_{0})(x - x_{0})$，其中切点：$P(x_{0}, y_{0})$；斜率：$k = f'(x_{0})$

61、切点的三大性质：(1).切线的斜率等于该点的导函数值；即$k=f'(x_{0})$

(2).切点在曲线$y = f(x)$上；

(3).切点在切线 l 上

62、常见的不定积分表

|   函数名   |            被积函数             |                 原函数                  |
| :--------: | :-----------------------------: | :-------------------------------------: |
|   常函数   |           $f(x)=c$            |              $F(x)=cx+C$              |
|   幂函数   |$f(x)=x^{\alpha}(\alpha\neq-1)$|$F(x)=\frac{1}{\alpha+1}x^{\alpha+1}+C$|
| 反比例函数 |      $f(x)=\frac{1}{x}$     |            $F(x)=\ln x+C$             |
|  正弦函数  |         $f(x)=\sin x$         |           $F(x)=-\cos x+C$            |
|  余弦函数  |         $f(x)=\cos x$         |            $F(x)=\sin x+C$            |

63、积分的性质

(1).$\int kf(x)dx = k\int f(x)dx$;

(2).$\int f[(x) + g(x)]\,dx = \int f(x)\,dx + \int g(x)\,dx$

64、积分的几何意义：面积就是积分值。

定义在$[a,b]$上的函数$f(x)$与 x 轴，$x=a,x=b,y=f(x)$构成曲边梯形的面积就为$f(x)$在$[a,b]$的定积分值。$S=\int_{a}^{b}f(x)dx$

65、求积分的三种思路：(1)牛莱公式；(2)奇偶性质；(3)转圆求面积。

66、奇偶函数求积分：(1) 奇函数对称区间上积分为 0；(2) 偶函数对称区间上积分为$[0, a]$的两倍。

67、转圆求积分：(1)$\int_{-a}^{a}\sqrt{a^{2}-x^{2}}dx=\frac{1}{2}\pi a^{2}$（半圆）；(2)$\int_{0}^{2}\sqrt{4-x^{2}}dx=\frac{1}{4}\pi2^{2}=\pi$（四分之一圆）。

68、牛顿-莱布尼茨公式：$\int_{a}^{b}f(x)dx=F(x)\bigg|_{a}^{b}=F(b)-F(a)$. 其作用：计算曲边梯形的面积。

69、不等式任意性：$\forall x\in D,a>f(x)\Rightarrow a>f(x)_{\max}$；$\forall x\in D,a\leq f(x)\Rightarrow a\leq f(x)_{\min}$

70、不等式存在性：$\exists x\in D,a>f(x)\Rightarrow a>f(x)_{\min}$；$\exists x\in D,a\leq f(x)\Rightarrow a\leq f(x)_{\max}$

71、不等式相同性：任意$x \in D$，证明：$f(x) > g(x) \Leftrightarrow h(x) = f(x) - g(x) > 0 \Leftrightarrow h(x)_{\min} > 0$

存在$x \in D$，证明：$f(x) \leq g(x) \Leftrightarrow h(x) = f(x) - g(x) \leq 0 \Leftrightarrow h(x)_{\min} \leq 0$

72、不等式相异性：任意$x_{1}, x_{2} \in D$，证明：$f(x_{1}) < g(x_{2}) \Leftrightarrow x \in D, f(x)_{\max} < g(x)_{\min}$

存在$x_{1}, x_{2} \in D$，证明：$f(x_{1}) > g(x_{2}) \Leftrightarrow x \in D, f(x)_{\max} > g(x)_{\min}$

73、函数有零点$\Leftrightarrow f(x)_{\max}\leq0$且$f(x)_{\min}\geq0\Leftrightarrow\left\{\begin{aligned}f(x)_{\min}&\leq0\\ f(x)_{\max}&\geq0\end{aligned}\right.$

74、函数无零点$\Leftrightarrow f(x)_{\max}\leq0$或$f(x)_{\min}\geq0$全部资料电子版在公众号：逆袭墙

75、抽象函数具体化：若构造一个具体的特殊函数满足所有的已知条件，那么这个具体函数一定是符合所求问题的一个函数。

76、抽象函数对数型：若$f(xy)=f(x)+f(y)$，则$f(x)=\log_{a}x$;

77、抽象函数指数型：若$f(x+y)=f(x)f(y)$，则$f(x)=a^{x}$;

78、抽象函数正比型：若$f(x+y)=f(x)+f(y)$，则$f(x)=kx$；

79、抽象函数一次型：若$f'(x)=c$，则$f(x)=cx+b$；

80、抽象函数导数型：若$f'(x) = f(x)$，则$f(x) = k e^{x}$或$f(x) = 0$;

81、指数不等式：$e^{x} \geq x + 1$（当且仅当x = 0时“=”成立）

82、对数不等式：$\ln x \leq x - 1$（当且仅当$x = 1$时“=”成立）

83、指对综合不等式：$\begin{cases}e^{x}\geq x+1\\\ln x\leq x-1\end{cases}\Rightarrow\ln(x+1)\leq x\leq e^{x}-1$（当且仅当x=0时“=”成立）

85. 绝对值不等式：$|a|-|b|\leq|a\pm b|\leq|a|+|b|$；

86、函数绝对值不等式：$\left|f(x_{1})-f(x_{2})\right|\leq a\Leftrightarrow f(x)_{\max}-f(x)_{\min}\leq a$

*87、柯西不等式：①.向量模型：$|\vec{a}||\vec{b}|\geq|\vec{a}\cdot\vec{b}|$； ②.数字模型：$\sqrt{x_{1}^{2}+y_{1}^{2}}\sqrt{x_{2}^{2}+y_{2}^{2}}\geq x_{1}x_{2}+y_{1}y_{2}$

*88、伯努利不等式：$\begin{cases} (1+x)^n \geq x^n + nx & n \geq 1 \\ (1+x)^n \leq 1 + nx & 0 \leq n < 1 \end{cases}$

*89、洛必达法则：$\lim_{x\to a}\frac{f(x)}{g(x)}=\lim_{x\to a}\frac{f'(x)}{g'(x)}$（当$\frac{f(x)}{g(x)}\rightarrow\frac{0}{0}$或$\frac{\infty}{\infty}$时使用）

90、恒成立问题：(1)$a \geq f(x) \Leftrightarrow a \geq f(x)_{\max}$; (2)$a < f(x) \Leftrightarrow a < f(x)_{\min}$

91、证明$f(x) > g(x)$思路：思路 1：(1)$h(x) = f(x) - g(x) \Leftrightarrow h(x) > 0$（常规首选方法）

思路 2:$f(x)_{\min} > g(x)_{\max}$（思路 1 无法完成）

## 第 3 章 数列

92、等差数列通项公式：$a_{n}=a_{1}+(n-1)d=kn+b$（一次函数模型）

93、等差数列通项公式：$S_{n}=\frac{n(a_{1}+a_{n})}{2}=na_{1}+\frac{n(n-1)}{2}d=An^{2}+Bn$（二次函数模型）

94、等比数列通项公式：$a_{n}=a_{1}q^{n-1}$全部资料电子版在公众号:逆袭墙

95、等比数列通项公式：$S_{n}=\frac{a_{1}(1-q^{n})}{1-q}=\frac{a_{1}-a_{n}q}{1-q}=A-Aq^{n}$

96、等差数列的性质：若$m+n=p+q$，则$a_{m}+a_{n}=a_{p}+a_{q}$

97、等比数列的性质：若$m+n=p+q$，则$a_{m}a_{n}=a_{p}a_{q}$

98、等差中项：若 a, A, b 成等差数列，则$2A = a + b$

99、等比中项：若 a, G, b 成等比数列，则$G^{2} = ab$

100、裂项相消法 1：若$\frac{1}{n(n+1)} = \frac{1}{n} - \frac{1}{n+1}$，则有$T_{n} = 1 - \frac{1}{n+1} = \frac{n}{n+1}$

101、裂项相消法 2：若$\frac{1}{n(n+2)}=\frac{1}{2}\left(\frac{1}{n}-\frac{1}{n+2}\right)$，则有$T_{n}=\frac{1}{2}(1+\frac{1}{2}-\frac{1}{n+1}-\frac{1}{n+2})$

102、裂项相消法 3：若$\frac{1}{a_{n+1}a_n} = \frac{1}{d} \left( \frac{1}{a_n} - \frac{1}{a_{n+1}} \right)$，则有$T_n = \frac{1}{d} \left( \frac{1}{a_1} - \frac{1}{a_{n+1}} \right)$

103、裂项相消法 4：若$\frac{1}{(2n+1)(2n-1)}=\frac{1}{2}\left(\frac{1}{2n-1}-\frac{1}{2n+1}\right)$，则有$T_{n}=\frac{1}{2}(1-\frac{1}{2n+1})$

104、分组求和法：
$$S_{n}=(1+\frac{1}{2})+(3+\frac{1}{4})+(5+\frac{1}{8})+\cdots+[(2n-1)+\frac{1}{2^{n}}]=(1+3+\cdots+2n-1)+(\frac{1}{2}+\frac{1}{4}+\cdots+\frac{1}{2^{n}})$$

*105、错位相减法求和通式：$T_{n}=\frac{a_{1}b_{1}}{1-q}+\frac{dq(b_{1}-b_{n})}{(1-q)^{2}}-\frac{a_{n}b_{n}q}{1-q}$

106、自然数的平方和：$1^{2}+2^{2}+3^{2}+\cdots+n^{2}=\frac{n(n+1)(2n+1)}{6}$

107、自然数的立方和：$1^{3}+2^{3}+3^{3}+\cdots+n^{3}=\frac{n^{2}(n+1)^{2}}{4}$

108、去$S_{n}$留$a_{n}$思想：$S_{n}=f(a_{n})\Rightarrow\left\{\begin{aligned}S_{n}&=f(a_{n})\\ S_{n+1}&=f(a_{n+1})\end{aligned}\right.\Rightarrow a_{n+1}=f(a_{n+1})-f(a_{n})$

109、去$a_{n}$留$S_{n}$思想：$a_{n}=f(S_{n})\Rightarrow a_{n+1}=S_{n+1}-S_{n}\Rightarrow S_{n+1}-S_{n}=f(S_{n})$

## 第 4 章 三角函数

110、三角函数的定义：正弦：$\sin\alpha=\frac{y}{r}$；余弦：$\cos\alpha=\frac{x}{r}$；正切：$\tan\alpha=\frac{y}{x}$；其中：$r=\sqrt{x^{2}+y^{2}}$

111、诱导公式：$\pi$倍加减名不变，符号只需看象限；半$\pi$加减名要变，符号还是看象限。

112、和差公式：①$\sin(\alpha\pm\beta)=\sin\alpha\cos\beta\pm\cos\alpha\sin\beta$（伞科科伞，符号不反）

②$\cos(\alpha\pm\beta)=\cos\alpha\cos\beta\mp\sin\alpha\sin\beta$（科科伞伞，符号相反）

③$\tan(\alpha \pm \beta) = \frac{\tan \alpha \pm \tan \beta}{1 \mp \tan \alpha \tan \beta}$（上同下相反）全部资料电子版在公众号:逆袭墙

113、二倍角公式：  ①$\sin 2\alpha = 2\sin \alpha \cos \alpha$

​									②$\cos 2\alpha = \cos^{2}\alpha - \sin^{2}\alpha = 1 - 2\sin^{2}\alpha = 2\cos^{2}\alpha - 1$

​									③$\tan2\alpha=\frac{2\tan\alpha}{1-\tan^{2}\alpha}$

114、平方关系：①.$\sin^{2}\alpha+\cos^{2}\alpha=1$②.$(\sin\alpha\pm\cos\alpha)^{2}=1\pm\sin2\alpha$

115、齐次式求值：①.$\frac{\sin\alpha+2\cos\alpha}{3\sin\alpha-\cos\alpha}=\frac{\tan\alpha+2}{3\tan\alpha-1}$②.$\sin\alpha\cos\alpha=\frac{\sin\alpha\cos\alpha}{\sin^{2}\alpha+\cos^{2}\alpha}=\frac{\tan\alpha}{\tan^{2}\alpha+1}$

116、辅助角公式:$a \sin wx \pm b \cos wx = \sqrt{a^{2} + b^{2}} \sin(wx \pm \varphi)$. ($\tan \varphi = \frac{b}{a}$,$a, b > 0$)

117、三角函数不等式：$\sin x \leq x \leq \tan x$，当$x \in \left(0, \frac{\pi}{2}\right)$时恒成立；

118、$y=\sin x$单调性：增区间：$\left[-\frac{\pi}{2}+2k\pi,\frac{\pi}{2}+2k\pi,\right]$；减区间：$\left[\frac{\pi}{2}+2k\pi,\frac{3\pi}{2}+2k\pi,\right]$

119、$y=\cos x$单调性：增区间：$\left[-\pi+2k\pi,2k\pi\right]$；减区间：$\left[2k\pi,\pi+2k\pi\right]$

120、$y=\tan x$单调性：增区间：$\left(-\frac{\pi}{2}+k\pi,\frac{\pi}{2}+k\pi\right)$

121、对称轴方程：(1)$y=\sin x$对称轴方程：$x=\frac{\pi}{2}+k\pi$；(2)$y=\cos x$对称轴方程：$x=k\pi$

122、对称中心：(1)$y = \sin x$中$(k\pi, 0)$；(2)$y = \cos x$中$\left(\frac{\pi}{2} + k\pi, 0\right)$；(3)$y = \tan x$中$\left(\frac{k\pi, 0}{2}, 0\right)$；

123、周期性：(1)$y=\sin x$中$T=\frac{2\pi}{w}$；(2)$y=\cos x$中$T=\frac{2\pi}{w}$；(3)$y=\tan x$中$T=\frac{\pi}{w}$；

124、正弦定理：$\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=2R$

125、余弦定理：①$\cos A = \frac{b^{2} + c^{2} - a^{2}}{2bc} \Leftrightarrow a^{2} = b^{2} + c^{2} - 2bc\cos A$

$$\cos B=\frac{a^{2}+c^{2}-b^{2}}{2ac}\Leftrightarrow b^{2}=a^{2}+c^{2}-2ac\cos B$$

 ③$\cos C=\frac{a^{2}+b^{2}-c^{2}}{2ab}\Longleftrightarrow c^{2}=a^{2}+b^{2}-2ab\cos C$

 126、射影定理：$a\cos B+b\cos A=c,$

​							$a\cos C + c\cos A = b,$

​							$b\cos C + c\cos B = a,$

127、边大角大思想：大角对大边，大边对大角。$a > b \Leftrightarrow \sin A > \sin B \Leftrightarrow A > B$

128、边变角思想：(1)、公式：$a=2R\sin A$；$b=2R\sin B$；$c=2R\sin C$

(2)、“=”两边为边、角(正弦)同次式；

(3)、正余弦的混合组；

129、角变边思想：(1)公式：$\sin A=\frac{a}{2R}$;$\sin A=\frac{a}{2R}$;$\sin A=\frac{a}{2R}$

(2)“=”两边为边角(正弦)同次式;

(3)只有一个余弦$\cos$

130、正弦定理使用情况：已知条件为：AAS、ASA、边角同次式、角多用正弦

131、余弦定理使用情况：已知条件为：SSS、SAS、边的二次式、边多用余弦

132、三角形两角和关系：$\sin(A+B)=\sin C;\cos(A+B)=-\cos C;\tan(A+B)=-\tan C.$

133、正弦值双相等：若$\sin A = \sin B \Rightarrow A = B \Rightarrow$等腰三角形；

134、正余弦值相等：$\sin A = \cos B \Leftrightarrow A + B = \frac{\pi}{2} \Rightarrow$直角三角形；

$\Leftrightarrow A - B = \frac{\pi}{2} \Rightarrow A = \frac{\pi}{2} + B > \frac{\pi}{2} \Rightarrow$钝角三角形；

135、余弦值双相等：$\cos A = \cos B \Leftrightarrow A = B \Rightarrow$等腰三角形；

136、二倍正弦值相等：$\sin 2A = \sin 2B \Leftrightarrow 2A = 2B \Rightarrow$等腰三角形；

$$\Leftrightarrow2A+2B=\pi\Rightarrow A+B=\frac{\pi}{2}\Rightarrow 直角三角形 ;$$

137、余弦值正负号：$\cos A > 0 \Leftrightarrow$锐角三角形；$\cos A = 0 \Leftrightarrow$直角三角形；$\cos A < 0 \Leftrightarrow$钝角三角形；

138、三角形最值原理：三角形中一个角及其对边已知时，另外两边或两角相等时周长取得最小值，面积取得最大值；

## 第 5 章 平面向量

139、向量加法的作图：上终下起，中间消去；$\overrightarrow{AB}+\overrightarrow{BC}=\overrightarrow{AC}$

140、向量减法的作图：起点相同，倒回来读；$\overrightarrow{AC}-\overrightarrow{AB}=\overrightarrow{BC}$

141、向量平行的判定：(1)向量法：$\vec{a} // \vec{b} \Leftrightarrow \vec{b} = \lambda \vec{a}$；(2)坐标法：$\vec{a} // \vec{b} \Leftrightarrow x_1 y_2 - x_2 y_1 = 0$

142、向量垂直的判定：(1)向量法：$\vec{a} \perp \vec{b} \Leftrightarrow \vec{a} \cdot \vec{b} = 0$；(2)坐标法：$\vec{a} \perp \vec{b} \Leftrightarrow x_{1}x_{2} + y_{1}y_{2} = 0$

143、向量的数量积公式：(1)向量法：$\vec{a}\cdot\vec{b}=|\vec{a}||\vec{b}|\cos\theta$; (2)坐标法：$\vec{a}\cdot\vec{b}=x_{1}x_{2}+y_{1}y_{2}$

144、向量的模长公式：(1)向量法：$\left|\vec{a}+2\vec{b}\right|=\sqrt{(\vec{a}+2\vec{b})^2}$（先平方，再根号）；(2)坐标法：$\left|\vec{a}\right|=\sqrt{x_1^2+y_1^2}$

145、向量的投影：(1)$\vec{a}$在$\vec{b}$方向的投影：$|\vec{a}|\cos\theta=\frac{\vec{a}\cdot\vec{b}}{|\vec{b}|}$；(2)$\vec{b}$在$\vec{a}$方向的投影：$|\vec{b}|\cos\theta=\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|}$；

146、向量的夹角公式：(1)向量法：$\cos\theta=\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}$; (2)坐标法：$\cos\theta=\frac{x_{1}x_{2}+y_{1}y_{2}}{\sqrt{x_{1}^{2}+y_{1}^{2}}\sqrt{x_{2}^{2}+y_{2}^{2}}}$

147、$\vec{a}$方向上的单位向量：(1)向量法：$\vec{e}=\frac{\vec{a}}{|\vec{a}|}$; (2)坐标法：$\vec{e}=\frac{\vec{a}}{|\vec{a}|}=\left(\frac{x_{1}}{\sqrt{x_{1}^{2}+y_{1}^{2}}},\frac{y_{1}}{\sqrt{x_{1}^{2}+y_{1}^{2}}}\right)$

 148、证明A、B、C三点共线两种方法：

​									（1）两个向量$$\overrightarrow{AB},\overrightarrow{AC}$$共线且有一个公共点A；

​									（2）$\overrightarrow{PA} = x\overrightarrow{PB} + y\overrightarrow{PC} (x + y = 1)$

## 第 6 章 立体几何

149、线线平行三方法：

①、线面平行的性质：一条直线和一个平面平行，过这条直线的平面和已知平面相交的交线和已知直线平行；

②、面面平行的性质：第三个平面与两个平行平面相交，则两条交线平行；

②、线面垂直的性质：垂直于同一平面的两条直线互相平行；

150、线线垂直两方法：线面垂直的性质：一条直线垂直一个平面，这条直线垂直这个平面内的所有直线。

151、线面平行两方法：①、线面平行的判定：线线平行→线面平行（一内一外一平行）

②、面面平行的性质：两个平面平行，一个平面内任意直线平行第二个平面

152、面面平行两方法：①、面面平行的判定：线面平行→面面平行（两内一交两平行）

②、面面平行的推论：两个平面内两组相交直线分别对应平行，则这两个平面平行

面垂直两方法：①、线面垂直的判定：线线垂直→线面平行（两内一交两垂直）

②、面面垂直的性质：两个平面垂直，一个平面内垂直于交线的直线必垂直第二个平面

154、面面垂直一方法：①、面面垂直的定义：两个平面的二面角为

②、面面垂直的判定：线面垂直→线面平行（一内一垂）

155、证明四点共面三方法：①两平行条线确定一个平面；

②两条相交直线确定一个平面；

③直线及直线外一点确定一个平面；

156、证明三点共线原理：两个平面有一个公共点，那么两个平面有且仅有一条过该点的直线。

157、证明三点共线方法：① A 分别属于两个平面$\alpha, \beta : A \in \alpha, A \in \beta$

②B,C 在平面$\alpha$,$\beta$的交线 l 上：$\alpha \cap \beta = l$, B,C$\in$l

③$A \in l$即：$A, B, C \in l$

即 A, B, C 三点共线；

158、法向量行列式公式：$\overrightarrow{m}=\left(\begin{vmatrix}y_{1}&z_{1}\\ y_{2}&z_{2}\end{vmatrix},-\begin{vmatrix}x_{1}&z_{1}\\ x_{2}&z_{2}\end{vmatrix},\begin{vmatrix}x_{1}&y_{1}\\ x_{2}&y_{2}\end{vmatrix}\right)$。其中$\begin{vmatrix}a&b\\ \frac{1}{2}a\frac{1}{2}b=\frac{a}{2}b=\frac{b}{2}\end{vmatrix}$

159、线线角向量法公式：$\cos\theta=\frac{\left|\vec{a}\cdot\vec{b}\right|}{\left|\vec{a}\right|\left|\vec{b}\right|}$；其中$\theta\in\left[0,\frac{\pi}{2}\right]$

160、线面角：(1)向量法公式：$\sin\theta=\frac{\left|\vec{a}\cdot\vec{m}\right|}{\left|\vec{a}\right|\left|\vec{m}\right|}$；(2)几何法公式：$\sin\theta=\frac{h_{x}}{a}$；其中$\theta\in\left[0,\frac{\pi}{2}\right]$

161、二面角：(1)向量法公式：$\cos\theta=\pm\frac{\left|\overrightarrow{m}\cdot\overrightarrow{n}\right|}{\left|\overrightarrow{m}\right|\left|\overrightarrow{n}\right|}$；(2)几何法公式：$\cos\theta=\frac{S_{射影}}{S_{原图}}$；其中$\theta\in[0,\pi]$

162、点面距：(1)向量法公式：$h_{x}=\frac{\left|\overrightarrow{m}\cdot\overrightarrow{AB}\right|}{\left|\overrightarrow{m}\right|}$；(2)几何法公式：$h_{x}=\frac{S_{1}h_{1}}{S_{2}}$

163、不定点设法：(1)P 在线段 AB 上：$\overrightarrow{AP}=t\overrightarrow{AB}(t\in[0,1])$

(2)P 在直线 AB 上：$\overrightarrow{AP}=t\overrightarrow{AB}(t\in R)$

164、多面体的内切球半径：$r=\frac{3V}{S_{表}}=\frac{3V}{S_{1}+S_{2}+\cdots+S_{n}}$

165、长方体的外接球半径：$2R=\sqrt{a^{2}+b^{2}+c^{2}}$

166、直棱锥的外接球半径：$\left\{\begin{aligned}R^{2}&=r^{2}+\left(\frac{h}{2}\right)^{2}\\ 2r&=\frac{a}{\sin A}\end{aligned}\right.$（直棱柱，圆柱也满足）

167、正棱锥的外接球半径：$\left\{\begin{aligned}R^{2}&=r^{2}+(h-R)^{2}\\ 2r&=\frac{a}{\sin A}\end{aligned}\right.$（正四面体，圆锥也满足）

168、正三角形的性质：高：$h=\frac{\sqrt{3}}{2}a$，面积：$S=\frac{\sqrt{3}}{4}a^{2}$

169、正三角形与圆：内切圆半径：$r=\frac{\sqrt{3}}{6}a$，外接圆半径：$R=\frac{\sqrt{3}}{3}a$，且$\frac{R}{r}=\frac{2}{1}$

170、正四面体的高：斜高：$h_{斜}=\frac{\sqrt{3}}{2}a$，正高：$h_{正}=\frac{\sqrt{6}}{3}a$

171、正四面体与球：内切球半径 r，外接圆半径 R，且$\frac{R}{r} = \frac{3}{1}$且$r + R = h_{正}$

## 第 7 章 解析几何

172、圆的定义: 若$PA \perp PB$，则 P 的轨迹为以 AB 为直径的圆

173、椭圆的定义: 若$PF_{1} + PF_{2} = 2a(2a > |F_{1}F_{2}|)$，则 P 的轨迹为以$F_{1}F_{2}$为焦点，2a 为长轴的椭圆

174、双曲线的定义：若$\|PF_{1}| - |PF_{2}| = 2a (2a < |F_{1}F_{2}|)$，则 P 的轨迹为以$F_{1}F_{2}$为焦点，2a 为实轴的双曲线

175、抛物线的定义：到定点$F(\frac{p}{2},0)$和到定直线：$x=-\frac{p}{2}$的距离相等的点 P 的轨迹为抛物线

176、求曲线方程常见的方法：①直接法；②代入法；③定义法；④待定系数法

177、直线的斜截式方程：$y = kx + b$；直线过 y 轴上点为$B(0, b)$且不竖直于 x 轴

178、直线的横截式方程：$x=my+a$；直线过x轴上点为$A(a,0)$且不平行于x轴

179、直线平行：$l_{1} \mathbin{/\mskip-5mu/} l_{2} \Leftrightarrow k_{1} = k_{2}(b_{1} \neq b_{2})$；或$A_{1}B_{2} - A_{2}B_{1} = 0$

180、直线垂直：$l_{1}\perp l_{2}\Leftrightarrow k_{1}k_{2}=-1$；或$A_{1}A_{2}+B_{1}B_{2}=0$

181、点点距公式：$\left|AB\right|=\sqrt{(x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2}}$

182、点线距公式：$d=\frac{\left|Ax_{0}+By_{0}+C\right|}{\sqrt{A^{2}+B^{2}}}$

183、线线距公式：$d=\frac{\left|C_{1}-C_{2}\right|}{\sqrt{A^{2}+B^{2}}}$

184、直线方程：（1）斜截式：$y = kx + b$；（2）点斜式：$y - y_{0} = k(x - x_{0})$；

（3）截距式：$\frac{x}{a}+\frac{y}{b}=1$；（4）一般式；$Ax+By+C=0$；

185、平行直线系：$Ax + By + \lambda = 0 (\lambda \neq C)$；$(A, B$相同，$C$不相同）

186、垂直直线系：$Bx-Ay+\mathit{\lambda}=0$；（A,B互换，符号变反）

187、交点直线系方程：$A_{1}x+B_{1}y+C_{1}+\lambda(A_{2}x+B_{2}y+C_{2})=0$

188、直线一般式与斜截式的互换：$k=-\frac{A}{B},b=-\frac{C}{B}$

189、直线的斜率公式：$k=\tan\alpha$，$k=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}$

190、斜率取值范围确定：过定点，作垂线；有交点，两k外；无交点，两k间；

191、圆与圆的位置关系

相离：$d>R+r$

外切：$d=R+r$

相交：$R-r<d<R+r$

内切：$d=R-r$

内含：$0 \leq d < R - r$

192、通用弦长公式：$l=\sqrt{1+k^{2}}\sqrt{(x_{1}+x_{2})^{2}-4x_{1}x_{2}}, l=\sqrt{(1+\frac{1}{k^{2}})(y_{1}+y_{2})^{2}-4y_{1}y_{2}}]$

193、圆的弦长公式：$l=2\sqrt{r^{2}-d^{2}}$

194、椭圆的离心率公式：$e=\frac{c}{a}=\sqrt{1-\frac{b^{2}}{a^{2}}}\in(0,1)$

195、双曲线的离心率公式：$e=\frac{c}{a}=\sqrt{1+\frac{b^{2}}{a^{2}}}=\sqrt{1+k_{渐}^{2}}\in(1,+\infty)$

196、离心率范围：(1)椭圆：$e \in (0,1)$；(2)双曲线：$e \in (1,+\infty)$；(3)抛物线：e=1

197、双曲线的渐近线方程：$y=\pm\frac{b}{a}x$

198、双曲线的焦渐距为：$b$（虚半轴）

199、通径公式 2t：(1)椭圆、双曲线：$2t=\frac{2b^{2}}{a}$；(2)抛物线：$2t=2p$

*200、焦半径公式（带坐标）：圆锥曲线上点$M(x_{0},y_{0})$到焦点F的距离

(1)椭圆中：$\left|MF\right|=a\pm ex_{0}$；(2)双曲线：$\left|MF\right|=ex_{0}\pm a$；(3)抛物线：$\left|MF\right|=x_{0}+\frac{p}{2}$

*201、焦半径公式（倾斜角）：$\frac{t}{(1 \pm e \cos \alpha)}$(t:半通径；知焦点弦倾斜角，即等心率)

(1)椭圆中：$\frac{b^{2}}{a(1\pm e\cos\alpha)}$；(2)双曲线：$\frac{b^{2}}{a(1\pm e\cos\alpha)}$；(3)抛物线：$\frac{p}{1\pm\cos\alpha}$

*202、焦点弦公式（倾斜角）：$\frac{2t}{(1-e^{2}\cos^{2}\alpha)}(t:\text{半通径};\alpha:\text{焦点弦倾斜角};e:\text{离心率})$

(1)椭圆中：$\frac{2b^{2}}{a(1-e^{2}\cos^{2}\alpha)}$；(2)双曲线：$\frac{2b^{2}}{a(1-e^{2}\cos^{2}\alpha)}$；(3)抛物线：$\frac{2p}{\sin^{2}\alpha}$

203、切线方程：(1)椭圆：$\frac{x_{0}x}{a^{2}}+\frac{y_{0}y}{b^{2}}=1$；(2)双曲线：$\frac{x_{0}x}{a^{2}}-\frac{y_{0}y}{b^{2}}=1$；(3)抛物线：$y_{0}y=p(x_{0}+x)$

204、抛物线的焦点弦长：$l=x_{1}+x_{2}+p=\frac{2k^{2}+2}{k^{2}}p=\frac{2p}{\sin^{2}\alpha}$

205、特殊弦长公式：(1)圆的弦长公式：$l=2\sqrt{r^{2}-d^{2}}$；(2)抛物线焦点弦长：$l=x_{1}+x_{2}+p$

206、焦点三角形面积：(1)椭圆中：$S_{\Delta F_{1}MF_{2}}=b^{2}\tan\frac{\theta}{2}$；(2)双曲线：$S_{\Delta F_{1}MF_{2}}=b^{2}\cot\frac{\theta}{2}$

(3)通用面积：$S_{\Delta F_{1}MF_{2}}=\frac{1}{2}d_{1}d_{2}\sin\theta$

*207、圆锥曲线的离心率公式：$|e\cos\alpha|=\frac{|\lambda-1|}{|\lambda+1|}$

208、抛物线焦点弦圆：以抛物线焦点弦为直径的圆必与准线相切；

209、抛物线焦点弦性质：$\frac{1}{|AF|}+\frac{1}{|BF|}=\frac{2}{p}$

210、抛物线焦点直线的韦达定理：$x_{1}x_{2}=\frac{p^{2}}{4},\quad x_{1}+x_{2}=\frac{k^{2}+2}{k^{2}}p,\quad y_{1}y_{2}=-p^{2},\quad y_{1}+y_{2}=\frac{2p}{k}$

211、点差法的斜率公式：$k_{椭}=-\frac{b^{2}x_{0}}{a^{2}y_{0}},\quad k_{双}=\frac{b^{2}x_{0}}{a^{2}y_{0}},\quad k_{抛}=\frac{p}{y_{0}}$

212、解析几何中的向量问题：$\overrightarrow{OA}\cdot\overrightarrow{OB}=x_{1}x_{2}+y_{1}y_{2},\overrightarrow{OA}+\overrightarrow{OB}=(x_{1}+x_{2},y_{1}+y_{2})$

213、向量与夹角问题：(1)$\angle AOB$钝角$\Leftrightarrow \overrightarrow{OA} \cdot \overrightarrow{OB} < 0$;

(2)$\angle AOB$锐角$\Leftrightarrow \overrightarrow{OA} \cdot \overrightarrow{OB} > 0$;

(3)$\angle AOB$直角（$OA \perp OB$）$\Leftrightarrow \overrightarrow{OA} \cdot \overrightarrow{OB} = 0$

214、向量与圆的问题：P 与以 AB 为直径的圆的位置关系：

(1) P 在圆内：$\angle APB$钝角$\Leftrightarrow \overrightarrow{PA} \cdot \overrightarrow{PB} < 0$;

(2) P 在圆上：$\angle APB$直角$\Leftrightarrow \overrightarrow{PA} \cdot \overrightarrow{PB} = 0$;

(3) P 在圆外：$\angle APB$锐角$\Leftrightarrow \overrightarrow{PA} \cdot \overrightarrow{PB} > 0$;

215、坐标轴平分角问题：$k_{1}=-k_{2}\Leftrightarrow k_{1}+k_{2}=0$

216、定点与定值问题：特殊位置，锁定答案；设而不求，再作验证；

217、均值思想：当两个正数变量的和或积为定值时求另一个量的最值，当这两个正数变量相等时，则所求变量取得最值；

## 第 8 章 概率统计

218、简单随机抽样：随机数表法、抽签法(抓阄法).

219、系统抽样：按等差数列通项抽取，其中第i个编号为$a_{i}=a_{1}+(i-1)d$.

220、分层抽样：按比例抽取$\frac{n}{N}=\frac{n_{1}}{N_{1}}=\frac{n_{2}}{N_{2}}=\frac{n_{3}}{N_{3}}=\cdots$

221、频方图的频率 = 小矩形面积：$f_{i} = S_{i} = y_{i} \times d = \frac{n_{i}}{\lambda I}$；频率 = 频数 / 总数.

222、频方图的频率之和：$f_{1}+f_{2}+\cdots+f_{n}=1$；同时$S_{1}+S_{2}+\cdots+S_{n}=1$。

223、频方图的众数：最高小矩形底边的中点.

224、频方图的平均数：$\overline{x}=x_{_{中1}}f_{_{1}}+x_{_{中2}}f_{_{2}}+x_{_{中3}}f_{_{3}}+\cdots+x_{_{中n}}f_{_{n}}$$\overline{x}=x_{_{中1}}S_{_{1}}+x_{_{中2}}S_{_{2}}+x_{_{中3}}S_{_{3}}+\cdots+x_{_{中n}}S_{_{n}}$

225、频方图的中位数：从左到右或者从右到左累加，面积等于0.5时x的值.

226、频方图的方差：$s^{2}=(x_{中1}-\overline{x})^{2}f_{1}+(x_{中2}-\overline{x})^{2}f_{2}+\cdots+(x_{中n}-\overline{x})^{2}f_{n}$

227、线性回归方程：$\hat{y}=\hat{b}x+\hat{a}$，$\hat{b}=\frac{\sum_{i=1}^{n}(x_{i}-\overline{x})(y_{i}-\overline{y})}{\sum_{i=1}^{n}(x_{i}-\overline{x})^{2}}=\frac{\sum_{i=1}^{n}x_{i}y_{i}-n\overline{xy}}{\sum_{i=1}^{n}x_{i}^{2}-n\overline{x}^{2}}$，$\hat{a}=\overline{y}-\hat{b}\overline{x}$。

228、线性回归直线方程必过样本中心：$(\bar{x},\bar{y})$

229、斜率$\hat{b}$的意义：$\hat{b}>0$:正相关；$\hat{b}<0$:负相关.

230、残差：$\hat{e}_{i}=y_{i}-\hat{y}_{i}$（残差=真实值—预报值）.分析：$|\hat{e}_{i}|$越小越好.

231、残差平方和：$\sum_{i=1}^{n}(y_{i}-\hat{y}_{i})^{2}=(y_{1}-\hat{y}_{1})^{2}+(y_{2}-\hat{y}_{2})^{2}+\cdots+(y_{n}-\hat{y}_{n})^{2}$. 分析：越小越好.

232、拟合度(相关指数)：$R^{2}=1-\frac{\sum_{i=1}^{n}(y_{i}-\hat{y}_{i})^{2}}{\sum_{i=1}^{n}(y_{i}-\overline{y})^{2}}$.分析：①.$R^{2}\in(0,1]$的常数；②.越大越好.

233、线性相关系数$r: r=\frac{\sum_{i=1}^{n}(x_{i}-\overline{x})(y_{i}-\overline{y})}{\sqrt{\sum_{i=1}^{n}(x_{i}-\overline{x})^{2}\sum_{i=1}^{n}(y_{i}-\overline{y})^{2}}}=\frac{\sum_{i=1}^{n}x_{i}y_{i}-n\overline{x}\cdot\overline{y}}{\sqrt{\sum_{i=1}^{n}(x_{i}-\overline{x})^{2}\sum_{i=1}^{n}(y_{i}-\overline{y})^{2}}}$

234、相关系数 r 分析：

①.$r\in[-1,1]$的常数；

②.$r>0$:正相关；$r<0$:负相关

③.$\left|r\right|\in[0,0.25]$，相关性很弱；$\left|r\right|\in(0.25,0.75)$，相关性一般；$\left|r\right|\in[0.75,1]$，相关性很强；

235、独立性检验$2 \times 2$列联表：

|       |$x_1$|$x_2$|    合计     |
| :---: | :---: | :---: | :---------: |
|$y_1$| $a$ | $b$ |   $a+b$   |
|$y_2$| $c$ | $d$ |   $c+d$   |
| 合计  |$a+c$|$b+d$|$n=a+b+c+d$|

236、独立性检验公式：$k^{2}=\frac{n(ad-bc)^{2}}{(a+b)(c+d)(a+c)(b+d)}$

237、独立性检验步骤：①．计算观察值$k^{2}$，②．查找临界值$k_{0}$，③.下结论.

238、常见的排列问题：任职问题、数字问题、排队照相问题、逐个抽取问题。

239、排列公式：$A_{n}^{m}=n(n-1)\cdots(n-m+1)$.

240、常见的组合问题：产品抽查问题、一次性抽取问题.

241、组合公式：$C_{n}^{m}=\frac{n(n-1)\cdots(n-m+1)}{m(m-1)\cdots3\times2\times1}$

242、常见排列组合顺口溜：

特殊元素先考虑，特殊位置先安排；分类讨论找特殊，分类复杂对立法；相邻问题捆绑法，相隔问题插空法；定序问题除阶乘，定序限制乘比例；染色问题多到少，对角之时须讨论；平均分组除阶乘，非平分组即组合；先分后排须谨记，后排即乘全排列。

243、古典概型公式：$P(A)=\frac{n_{A}}{n_{\Omega}}$

244、几何概型公式：$P(A)=\frac{l_{A}}{l_{\Omega}}=\frac{S_{A}}{S_{\Omega}}=\frac{V_{A}}{V_{\Omega}}=\frac{\alpha_{A}}{\alpha_{\Omega}}$

245、几何概型中面积问题：积分问题、双变量问题、线性规划问题.

246、任意事件概率公式：$P(A \cup B) = P(A) + P(B) - P(A \cap B)$.

247、互斥事件概率公式：$P(A+B)=P(A)+P(B)$.

248、对立事件概率公式：$P(\overline{A})=1-P(A)$(题目含有“至多、至少等关键词”).

249、条件概率公式：$P(B|A)=\frac{P(AB)}{P(A)}=\frac{n_{AB}}{n_{A}}$

250、独立事件概率公式：$P(AB)=P(A)P(B)$.

251、独立事件的性质：若A与B独立，则A与$\overline{B}$、$\overline{A}$与B、$\overline{A}$与$\overline{B}$也独立.

252、独立事件至少有一个发生概率公式：$P(A \cup B) = 1 - P(\overline{A}\overline{B})$.

253、超几何分布的概率公式：$P(x=k)=\frac{C_{M}^{k}C_{N-M}^{n-k}}{C_{N}^{n}}$

254、超几何分布的均值公式：$E(X)=n\frac{M}{N}$

255、无放回抽取：①一次性抽取→超几何分布；②逐一抽取→独立事件.

256、有放过抽取：等可能性→二项分布.

257、二项分布的概率公式：$P(x=k)=C_{n}^{k}p^{k}(1-p)^{n-k}$

258、二项分布的性质：有限性、等可能性、独立性.

259、二项分布的均值与方差：$E(X)=np$；方差：$D(X)=np(1-p)$.

260、均值公式：$E(X)=x_{1}p_{1}+x_{2}p_{2}+\cdots+x_{n}p_{n}$

261、方差公式：$D(X)=[x_{1}-E(x)]^{2}p_{1}+[x_{2}-E(x)]^{2}p_{2}+\cdots+[x_{n}-E(x)]^{2}p_{n}$

262、正态分布$X \sim N(\mu, \sigma^{2})$：$\mu$: 期望$E(X)$，$\sigma$: 标准差$\sqrt{D(X)}$

263、正态分布对称性：图像关于直线$x=\mu$成轴对称.

264、正态分布全区间概率：$P(x \in R) = \int_{-\infty}^{+\infty} \varphi(x) dx = 1$.

265、正态分布半区间概率：$P(x \leq \mu) = \int_{-\infty}^{\mu} \varphi(x) dx = 0.5$. 

$$P(\mu-\sigma<x<\mu+\sigma)=0.6826$$

266、正态分布$3\sigma$区间概率：$P(\mu-2\sigma<x<\mu+2\sigma)=0.9545$.

$$P(\mu-3\sigma<x<\mu+3\sigma)=0.9973$$

267、二项式定理展开式：$(ax+b)^{n}=C_{n}^{o}(ax)^{n}+C_{n}^{1}(ax)^{n-1}b+\cdots+C_{n}^{k}(ax)^{n-k}b^{k}+\cdots+C_{n}^{n}b^{n}$

268、两个系数：其中$(ax+b)^{n}$展开式中第$r+1$项为：$T_{r+1}=C_{n}^{r}(ax)^{n-r}b^{r}=C_{n}^{r}a^{n-r}b^{r}x^{n-r}$

(1)、二项式系数：$C_{n}^{r}$(2)、项的系数：$C_{n}^{r}a^{n-r}b^{r}$

269、所有二项式系数为$2^{n}$：$C_{n}^{0}+C_{n}^{1}+C_{n}^{2}+\cdots+C_{n}^{n}=2^{n}$

270、所有奇数项、偶数项二项式系数为$2^{n-1}$:$C_{n}^{0} + C_{n}^{2} + C_{n}^{4} + \cdots = 2^{n-1}$;$C_{n}^{1} + C_{n}^{3} + C_{n}^{5} + \cdots = 2^{n-1}$.

271、展开式系数：设$(ax+b)^{n}=a_{0}+a_{1}x+a_{2}x^{2}+a_{3}x^{3}+\cdots+a_{n}x^{n}$的展开式中.

272、各项系数和：令 x=1 时，$a_{0}+a_{1}+\cdots+a_{n}=(a+b)^{n}$①

奇偶项系数和：令 x=-1 时，$a_{n}-a_{i}+a_{i}-a_{i}+\cdots=(-a+b)^{n}$②(将①、②相加减即可得到

275、其他赋值：令$x=\frac{1}{2}$时，$a_{0}+\frac{a_{1}}{2}+\frac{a_{2}}{4}+\frac{a_{3}}{8}+\cdots+\frac{a_{n}}{2^{n}}=\left(\frac{1}{2}a+b\right)^{n}$

276、系数前提：求导后令 x=1 时，$a_{1}+2a_{2}+3a_{3}\cdots+na_{n}=an(a+b)^{n-1}$

## 第 9 章 极参方程

277、极坐标方程与直角方程互换：$\left\{\begin{aligned}\rho&=\sqrt{x^{2}+y^{2}},\tan\theta=\frac{y}{x}\\ x&=\rho\cos\theta,y=\rho\sin\theta,x^{2}+y^{2}=\rho^{2}\end{aligned}\right.$

278、极坐标点$M(\rho, \theta)$的意义：$\rho = |OM|$,$\theta = \angle xOM$

279、过原点且倾斜角$\alpha$的直线极坐标方程：$\theta = \alpha (\rho \in \mathbb{R})$

280、过原点且倾斜角$\alpha$的射线极坐标方程：$\theta = \alpha$或$\theta = \alpha (\rho \geq$

281、极坐标方程为$\theta = \alpha (\rho \in R)$的直线上两点的距离公式：$|AB| = |\rho_1 - \rho_2|$，$|OA| = \rho_1$，$|OB| = \rho_2$

282、圆的参数方程：$\begin{cases} x=a+r\cos\theta \\ y=b+r\sin\theta \end{cases}$（$\theta$为参数）

283、直线的参数方程：$\begin{cases}x=a+t\cos\alpha\\y=b+t\sin\alpha\end{cases}$（t为参数）

284、椭圆的参数方程：$\begin{cases} x=a\cos\theta \\ y=b\sin\theta \end{cases}$（$\theta$为参数）

285、参数方程的意义：$\begin{cases} x = f(\theta) \\ y = g(\theta) \end{cases}$（$\theta$为参数）上的任意点P的坐标可表示成：$P(f(\theta), g(\theta))$

286、直线参数 t 的意义 1:$\left|PA\right|=\left|t_{1}\right|$,$\left|PB\right|=\left|t_{2}\right|$

287、直线参数 t 的意义 2:$|PA||PB|=|t_{1}t_{2}|$

288、直线参数 t 的意义 3:$\left|AB\right|=\left|t_{1}-t_{2}\right|=\sqrt{\left(t_{1}+t_{2}\right)^{2}-4t_{1}t_{2}}$

289、直线参数 t 的意义 4:$\left|PA\right|+\left|PB\right|=\left|t_{1}\right|+\left|t_{2}\right|=\begin{cases}\left|t_{1}+t_{2}\right|&t_{1}、t_{2} 同号 \\ \left|t_{1}-t_{2}\right|&t_{1}、t_{2} 异号 \end{cases}$
