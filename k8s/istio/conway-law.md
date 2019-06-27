## 康威定律如何解释微服务的合理性
      
### 了解了康威定律是什么，再来看看他如何在半个世纪前就奠定了微服务架构的理论基础。

- 人与人的沟通是非常复杂的，一个人的沟通精力是有限的，所以当问题太复杂需要很多人解决的时候，我们需要做拆分组织来达成对沟通效率的管理
- 组织内人与人的沟通方式决定了他们参与的系统设计，管理者可以通过不同的拆分方式带来不同的团队间沟通方式，从而影响系统设计
- 如果子系统是内聚的，和外部的沟通边界是明确的，能降低沟通成本，对应的设计也会更合理高效
- 复杂的系统需要通过容错弹性的方式持续优化，不要指望一个大而全的设计或架构，好的架构和设计都是慢慢迭代出来的

## 带来的具体的实践建议是：

- 我们要用一切手段提升沟通效率，比如slack，github，wiki。能2个人讲清楚的事情，就不要拉更多人，每个人每个系统都有明确的分工，出了问题知道马上找谁，避免踢皮球的问题。
- 通过MVP的方式来设计系统，通过不断的迭代来验证优化，系统应该是弹性设计的。
- 你想要什么样的系统设计，就架构什么样的团队，能扁平化就扁平化。最好按业务来划分团队，这样能让团队自然的自治内聚，明确的业务边界会减少和外部的沟通成本，每个小团队都对自己的模块的整个生命周期负责，没有边界不清，没有无效的扯皮，inter-operate, not integrate。
- 做小而美的团队，人多会带来沟通的成本，让效率下降。亚马逊的Bezos有个逗趣的比喻，如果2个披萨不够一个团队吃的，那么这个团队就太大了。事实上一般一个互联网公司小产品的团队差不多就是7，8人左右（包含前后端测试交互用研等，可能身兼数职）。

## 再对应下衡量微服务的标准，我们很容易会发现他们之间的密切关系：

- 分布式服务组成的系统
- 按照业务而不是技术来划分组织
- 做有生命的产品而不是项目
- Smart endpoints and dumb pipes（我的理解是强服务个体和弱通信）
- 自动化运维（DevOps）
- 容错
- 快速演化

## Reference

- http://www.cnblogs.com/gudi/p/6685474.html