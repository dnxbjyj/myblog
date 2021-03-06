> 声明：本系列文章参考了《MATLAB 8.X实战指南（R2014a中文版）》（清华大学出版社，赵小川等编著），仅用于个人学习总结和交流，禁止作为商业用途转载或使用。

本文分四步走策略：第一，Matlab是个什么玩意；第二，为什么要学Matlab；第三，怎样轻松、无痛、少走弯路地学习Matlab；第四，怎样写一个Matlab的Hello World。通过这四步走，达到初步搞清楚Matlab是啥的地步。

# Matlab是个什么玩意
本人也是多年前在学习信号系统这门课的时候使用过Matlab，记得当时是用它来做一些求微分方程、傅里叶变换、拉普拉斯变化等等之类的事情，只是觉得它非常厉害，是一个万能的计算器，能算各种手工算起来超复杂的数学运算，包括但不限于下列功能：

* 基本初等数学运算（四则运算、幂指对数、三角函数、多项式计算等）：简直是一个增强版的、犹如瑞士军刀一样的超级计算器。
* 矩阵运算：这就不用说了，线性代数里面那些让你痛苦不堪的行列式、矩阵、求解线性方程组等的计算，Matlab都是分分钟几行代码搞定的事。
* 概率统计分析：各种概率分布、概率密度、统计特性的计算，也是Matlab十分擅长做的。
* 符号计算：包括求微分方程、傅里叶变换、拉普拉斯变换等等。
* 绘制各种二维、三维图像。
* 支持程序化编程，支持GUI（图形用户界面）编程。
* 信号仿真：学习信号与线性系统的好帮手（就像本人当年那样）。
...

一言以蔽之，Matlab是一个：只有你想不到、没有它做不到的功能的解决各种科学计算问题的瑞士军刀。

# 为什么要学Matlab
问得好，学一个东西前，必须要解决"为什么要学"的问题，这是能够学好一个东西的基石。为什么是学习这个东西而不是学习别的东西？学了它之后我可以用来做什么？下面列举五个无法拒绝学习Matlab的理由：

* 功能强大，在科学计算领域，只有你想不到，没有它做不到的功能，可以解决你在这些领域遇到的99.999%的计算难题。
* 代替手工计算，效率翻番何止十倍。以往手工算一个数学题可能需要密密麻麻写满几大张草稿纸，而Matlab只需几行代码即可优雅解决。
* 交互式的学习环境，所见即所得，让你能瞬间看到刚刚所敲代码的运行结果，容易产生浸入式的流体验。
* 业界通用，有千千万万的工程师、分析师等等各色人等都在用；解决各个行业的问题都可以用，从数学、统计学到物理学、生物学、电信、电力，再到经济学、金融，再到数据分析处理、人工智能，简直无所不能。
* 最后一点，也是最重要的，它可以解决你学习或工作中的一些切身"痛点"。比如可以缩短我做复杂的概率论作业的时间从而腾出来更多时间来一局游戏。

# 怎样轻松、无痛、少走弯路地学习Matlab

* 在Matlab交互式环境上实际操作。交互环境下，所见即所得，体验每个命令、每个函数的作用和效果。
* 用实际需要驱动学习。比如：我想用Matlab来做高斯消元法解线性方程组，那么不要犹豫，just do it! 不要想着等到把Matlab这个东西的所有规则、语法、套路都了熟于胸的时候才动手去做，而是从现在、此刻就开始去做、去实现这个需求，在做中一步步学具体的知识点。
* 做点好玩的。实际的需求难免枯燥乏味，这个时候如果想深入、持续地去学习，就要自己找点"乐子"来做，比如去尝试怎么画出一个心形曲线，怎么画出一个狂拽酷炫的三维图像，等等。
* 多使用`demo`命令看Matlab自带的短小精悍的demo程序。

# 怎样写一个Matlab的Hello World
### 环境安装
由于Matlab是一个商业软件，其本身体积非常大，且收费，所以为了方便起见，本人下载了一个超精简版、免安装的Matlab 5.3绿色版本（[这里是下载地址](http://pan.baidu.com/s/1c1N0Vb6)），整个软件包只有70多MB，打开即用。虽然是精简版的，但对于基础功能的练习足够了。

其界面的画风是这样的：
![](http://upload-images.jianshu.io/upload_images/8819542-3c1ac04b4d6b0319.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


简直简洁（简陋）到没朋友，一打开就是交互式命令行，我敲了一个算式：`1 + 1`，然后回车，它就算出来了结果：`2`

### Hello World
`Hello World`应该是在程序员界最为知名的一句话，任何一门编程语言的入门级教程里第一页（或前几页）都写有这句话。当然Matlab也是一种编程语言，这里我们也用Matlab的`disp`函数来输出`Hello World`来开启我们的入门之旅。
![](http://upload-images.jianshu.io/upload_images/8819542-0a1cb29497d037d4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
