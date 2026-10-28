# 🧪 GPU 实验

[返回个人主页](../README.md) · [完整实验时间线](https://github.com/xianshena/memlite/blob/main/docs/TIMELINE.zh-CN.md)

这里收集可公开的实验方法、结果和复核入口。优先从问题开始读，再看配置和数字；失败、补跑与限制也保留。

| 想理解什么 | 阅读入口 |
| --- | --- |
| 历史经验如何影响日常选择；3.08 亿参数模型三种子训练 | [MemLite 中文说明](https://github.com/xianshena/memlite/blob/main/README.zh-CN.md) |
| 训练、部署、量化、RAG、文字/对象记忆等阶段如何衔接 | [已公开实验总目录](https://github.com/xianshena/memlite/blob/main/docs/EXPERIMENTS.zh-CN.md) |
| 不同指令结构、长程事实、操作顺序与生成对照 | [结构与记忆显微镜阶段入口](https://github.com/xianshena/memlite/blob/main/docs/experiments/microscope-20261027/README.zh-CN.md) |
| 哪项先做、何时写入文档、哪些发生日尚未核实 | [时间线](https://github.com/xianshena/memlite/blob/main/docs/TIMELINE.zh-CN.md) |

## 分模块读结构与记忆显微镜

- [C：像素 MLP / CNN / ViT 与图 MLP / GNN / 图注意力](https://github.com/xianshena/memlite/blob/main/docs/experiments/microscope-20261027/C-visual-and-graph.zh-CN.md)
- [D：深度、残差与已有 Euler / RK4 数值参考](https://github.com/xianshena/memlite/blob/main/docs/experiments/microscope-20261027/D-depth-and-ode.zh-CN.md)
- [E：AR / VAE / WGAN-GP / DDPM / Flow](https://github.com/xianshena/memlite/blob/main/docs/experiments/microscope-20261027/E-generative.zh-CN.md)

各页含实际配置、测试分母、结果图与失败边界。它们整理的是已有合成实验，未重新训练；原始输入、逐条预测、未授权源码与大权重不随阅读摘要发布。

这些链接是已经公开的记录；目录不是每个历史实验完整原包均已公开的承诺。更多 GPU 材料需按具体文件去除私密信息后再整理。学习资料、个人原文、未授权代码与权重不放在这里。

结果仅适用于各自协议、数据和计算预算。CPU 示例与 GPU 训练是不同层次；合成任务的高分不等于真实机器人能力。
