功能名称： (填写任务的名称, 在 Paddle 中实现 Common Subexpression Elimination（公共子表达式删除）的图优化 pass)

开始日期：（填写提交时候的日期，YYYY-MM-DD）

RFC PR：[PaddlePaddle#33333]()

GitHub Issue：[PaddlePaddle#35993](https://github.com/PaddlePaddle/Paddle/issues/35993)

# 总结
一段关于该功能的解释。

# 动机
我们为什么要这样做？它支持哪些用例？预期的结果是什么？

# 使用指南级别的说明
解释这个rfc，就好像它已经包含在 PaddlePaddle 中，而且你正在教一个 PaddlePaddle 用户。

这通常意味着。

- 引入新的命名概念。
- 解释该功能能够实现什么（提示：用例子来思考）。
- 如果适用，提供错误信息样本、废弃警告或迁移指导。
- 对于新功能的RFC，这部分应该提供一个以实例为导向的介绍，并具体解释其影响。

# 参考文献级别的说明
这是RFC的技术部分。对这个设计进行足够详细的解释，即

- 它与其他功能的交互是清楚的。
- 合理地清楚该功能将如何实现。
- 通过实例剖析corner cases。
- 该部分应该回到上一节给出的例子，并更充分地解释详细的建议如何使这些例子发挥作用。

# 缺点
为什么我们不应该这样做？

# 理论依据和替代方案
为什么这个设计在可能的设计思路中是最好的？
还有哪些设计被考虑过，不选择这些设计的理由是什么？
不这样做的影响是什么？

# 现有技术
讨论现有技术，包括好的和坏的，与本rfc有关的。可以包括以下几个例子。

- 这个功能在其他深度学习框架中是否存在，讨论他们的社区所做的实验？
- 对于社区建议。这个功能是否由其他社区完成，他们的经验是什么？
- 对于其他团队来说。我们可以从其他社区所做的事情中吸取什么教训？
- 论文。是否有任何已发表的论文或帖子来讨论这个问题？如果你有一些相关的论文可以参考，这可以作为一个更详细的理论背景。
- 如果没有先例，那也没关系--无论你的未来的可能性想法是全新的还是从其他语言改编的，对我们来说都是有趣的。

请注意，虽然其他深度学习框架的先例是某种动力，但它本身并不能成为RFC的动力。也请考虑到 PaddlePaddle 有意与其他深度学习框架有所区别。

# 未解决的问题

- 在合并前，你希望通过RFC程序解决设计中的哪些部分？
- 在功能稳定前，你希望通过实现这个功能来解决哪些部分的设计问题？
- 你认为哪些相关问题超出了本RFC的范围，可以在未来独立于本RFC的解决方案来解决？

# 未来的可能性
想一想你的RFC的自然延伸和演变，以及它将如何全面影响项目。试着把这部分作为一个工具，在你的RFC中更全面地考虑与框架所有可能的互动。还要考虑这一切如何与项目和相关的子团队的路线图相适应。

这也是一个 "倾倒想法 "的好地方，如果这些想法超出了你所写的RFC的范围，但又与之相关。

如果你已经尝试过，但想不出任何未来的可能性，你可以简单地说，你什么都想不出来。

请注意，在未来可能性部分写下一些东西并不是接受当前或未来RFC的理由；这种说明应该放在本篇或后续RFC的动机或理由部分。该部分只是提供额外的信息。

参考：[tvm/rfc-template](https://github.com/apache/tvm-rfcs/blob/main/0000-template.md)