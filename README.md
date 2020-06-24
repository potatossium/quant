本文希望通过机器学习的方法构造与股价涨幅相关性更高的因子，并尝试根据树回归模型预测未来股价涨幅。此种方法建立在如下两个假设之上： 
假设1：股价属于非随机游走时间序列，有一定可预测性，否则所有因子分析都是无效的。 
假设2：不同时段的因子有效性是变化的，而因子有效性会持续一段时间。比如这个月市盈率低的股票有更多资金涌入，而下个月市盈率高的股票更受青睐。
如果假设成立，那么使用固定公式计算股价是局限的。我们希望用机器学习找出资金的暂时性逻辑。

股票池选取的条件是沪股通深股通持股比例大于1%。

[聚宽研究环境notebook地址](https://www.joinquant.com/research)

[聚宽回测主页](https://www.joinquant.com/)

[聚宽API文档](https://www.joinquant.com/help/api/help?name=api)
