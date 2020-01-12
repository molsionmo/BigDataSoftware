# Flink

## 学习路径参考

学习一门新技术时，一定要注重系统性，也要注意总结留存

* [学习工程](https://github.com/zhisheng17/flink-learning)其实是一位网友在学习Flink过程中的源码积累
* [大数据实时计算引擎 Flink 实战与性能优化](https://gitbook.cn/gitchat/column/5dad4a20669f843a1a37cb4f)是这位网友系统性的内容输出
* 围绕着{系统性学习}+{学习实践}进行，{学习实践}将开放源码，{系统性学习}将包含核心内容+实践+线上问题汇总，将被用于商业化，开放于GitChat，知识星球
* 技术的先驱如果有新的推动可以输出成博客[zhisheng个人博客](http://www.54tianzhisheng.cn/)，后面实践总结后再切入{系统性学习中}，用于商业化付费

## FLink CEP

Flink CEP参考的是[Efficient Pattern Matching over Event Streams](https://people.cs.umass.edu/~yanlei/publications/sase-sigmod08.pdf)中的NFA模型,在这篇论文中，提到了NFA，也就是Non-determined Finite Automaton，叫做不确定的有限状态机，指的是状态有限，但是每个状态可能被转换成多个状态(不确定).需要理解清楚这个NFA的整体过程才能理解整个CEP的设计.

## 论文相关

1. [Streaming 101: 批处理之上的世界（一）](https://zhuanlan.zhihu.com/p/59798824)
2. [Streaming 102: 批处理之上的世界（二）（上）](https://zhuanlan.zhihu.com/p/59993580)
3. [Streaming 102: 批处理之上的世界（二）（下）](https://zhuanlan.zhihu.com/p/60236077)
4. [《基于事件流的高效模式匹配》(简易版翻译)](https://www.jianshu.com/p/e162e9cc73f7)
