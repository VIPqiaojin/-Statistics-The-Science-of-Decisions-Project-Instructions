**1. 我们的自变量是什么？因变量是什么？**  
    自变量：显示文字颜色和打印颜色是否一致  
    因变量：反应时间  
  
**2. 此任务的适当假设集是什么？你想执行什么类型的统计测试？为你的选择提供正当理由。**  
    假设：  
    H0: μ1>=μ2（假设平均反应时间与显示文字颜色和打印颜色是否一致无关 或 颜色一致平均反应时间更长）  
    HA: μ1<μ2（假设显示文字颜色和打印颜色不一致的平均反应时间更长)  
    (μ1：显示文字颜色和打印颜色一致的平均反应时间; μ2：显示文字颜色和打印颜色不一致的平均反应时间)  
    检验种类：负向单尾t检验(相依变量--重复测量设计)
    选择检验的依据:
- 选择 t 检验还是 z 检验?  
     总体参数未知,不能使用 z 检验.[参考网址](http://www.statisticshowto.com/probability-and-statistics/hypothesis-testing/t-score-vs-z-score/)
- 选择是相依样本还是独立样本?  
     相依样本.本次实验前后两组测试间并不会相互影响.[参考网址](http://support.minitab.com/en-us/minitab/17/topic-library/basic-statistics-and-graphs/hypothesis-tests/tests-of-means/how-are-dependent-and-independent-samples-different/)
- 应当是单尾检验还是双尾检验?  
     根据假设,我们想知道的是颜色不同是否会显著降低平均反应时间,因此是负向单尾t检验.[参考资料](http://stats.idre.ucla.edu/other/mult-pkg/faq/general/faq-what-are-the-differences-between-one-tailed-and-two-tailed-tests/)
- t 检验的前提要求还有哪些?  
     [参考资料](http://www.csic.cornell.edu/Elrod/t-test/t-test-assumptions.html) ,[优达学城论坛](https://discussions.youdaxue.com/t/topic/42566/3)  
     依次排查t检验前提:  
        1. 两组自变量：颜色一致的时间和颜色不一致的时间,符合  
        2. 连续的因变量：共24个连续的时间数据,符合  
        3. 每一个（μ1-μ2）都互相独立:符合  
        4. 符合正态分布:可假设总体符合正态分布
  
**3. 报告关于此数据集的一些描述性统计。包含至少一个集中趋势测量和至少一个变异测量。**  
    均值：X1=14.05 , X2=22.02
    标准差：SD1=3.56 , SD2=4.80

**4. 提供显示样本数据分布的一个或两个可视化。用一两句话说明你从图中观察到的结果。**  
    箱线图:  
    ![](https://raw.githubusercontent.com/vipqiaojin/Udacity/master/task1/boxplot.png)  
    可以观察到：图案一致的反应时间基本小于图案不一致反应时间。

**5. 现在，执行统计测试并报告你的结果。你的置信水平和关键统计值是多少？你是否成功拒绝零假设？对试验任务得出一个结论。结果是否与你的期望一致？**  
    X1=14.05，X2=22.02,点估数据μ1 - μ2 = X1 - X2 = -7.96  
    Sd=4.86
    t(stastic) = (X1 - X2)/(Sd / sqrt(n))= -7.96/(4.86/sqrt(24))= - 8.02  
    查询 t 值表:(df= 23，a=0.05)  
    ![](https://raw.githubusercontent.com/vipqiaojin/Udacity/master/t-table.jpg)  
    得到：t(critical) = -1.714  
    t(stastic)  < t(critical), 故拒绝原假设H0，接受对立假设HA.  
    结论：图案一致的反应时间小于图案不一致的反应时间.  
    95%置信区间：CI(-15.56 , -5.91)表示字母和背景颜色一样的反应时间比不一致颜色反应时间平均少 6s 到 16s  

**6. 可选：你觉得导致所观察到的效应的原因是什么？你是否能想到会取得类似效应的替代或类似任务？进行一些调查研究将有助于你思考这两个问题！**  
    原因：单词暗示了颜色，导致思想发生错乱。  
    例子：当学习时，由已学到的知识去学习相关的知识更加容易，但是如果学一个没有任何相关的抽象知识会很困难。
