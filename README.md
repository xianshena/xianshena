![xianshena — learning through experiments](assets/profile-header.svg)

<div align="center">

### 🌸 Learning, one careful experiment at a time
**通过小实验理解模型，用可复核的记录持续学习。**

Memory-conditioned decisions · Small-model training · Reproducible experiments

</div>

---

### Currently exploring / 正在探索

I learn by building small experiments, inspecting failures, and keeping the evidence close to the code. My current interests are explicit experience memory, numerical decision models, and practical evaluation controls.

我关注显式经验记忆怎样影响决策、小模型训练，以及让实验结果更容易复核。希望逐步把想法变成可运行、可检查、可以改进的代码。

### MemLite

**Reproducible Memory-Conditioned Decision Learning**

An early project in synthetic scenes, with a low-resource CPU example and recorded 308M training results across three seeds.

| What to inspect | What it covers |
|---|---|
| CPU example | Explicit object memory and G0/G1a controls |
| Three recorded 308M seeds | Daily-choice accuracy (daily subset n=1,600 per seed): 94.125%, 94.0625%, 94.125% |
| Ablations and audits | History-swap, clear-memory, frozen-data scoring and individual decisions |
| Open questions | Learned memory writing, real perception and independent replication |

The public repository is being prepared. Results concern synthetic numerical scenes; navigation uses deterministic BFS. The exploratory 4B-teacher / 1.85B-student appendix has no independent test and does not inherit the 308M scores.

项目仍处于早期阶段，尚无已核验的外部使用证据。持续记录限制与失败，是我学习过程的一部分。

---

<div align="center">
<sub>Small steps, clear evidence, steady learning. / 小步尝试，认真记录，持续进步。</sub>
</div>
