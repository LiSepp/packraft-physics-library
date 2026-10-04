# Packraft Physics Lab｜论文目录与阅读路线

更新：2026-10-04。依据本目录 **24 篇实际 PDF** 的首页、摘要和相关结论整理；关联阅读的题名用 DOI 元数据核对。此处的 S/A/B/C 是对“理解背包船推进、控船和白水”的**阅读收益**排序，不代表论文质量。当前不用再批量下载。

## 目录

| 文件夹 | 解决的问题 | 篇数 |
|---|---|---:|
| `01_桨叶推进与划桨力学` | 桨叶怎样受力；一桨的力随时间怎样变化 | 3 |
| `02_艇体水动力与性能` | 阻力、速度、稳定性、转弯；充气艇与柔性结构的对照 | 7 |
| `03_激流回旋与控船` | 选线、上水门、回旋技术及其证据 | 3 |
| `04_白水河流流体力学` | 回流、剪切层、水跃、波列、河床湍流 | 7 |
| `05_人体生物力学与训练` | 人、桨、艇协同的总览 | 1 |
| `90_低优先级或参考` | 特定竞速桨技术、测量方法及迁移距离较远的模型 | 3 |

两份现有中文术语 Markdown 文件保留在根目录，没有移动。文件名保留原样，避免旧引用失效；下表以分类为唯一存放位置。**S：优先精读；A：下一轮重点读；B：先看摘要、图和结论；C：需要时查。**

论文中文翻译现在使用两层术语库：[Packraft 中文术语标准 v2.4](<Packraft 中文术语标准 v2.4.md>) 管背包船与白水通用概念，[划艇物理／生物力学补充术语表 v1.1](划艇物理_生物力学补充术语表_v1.1.md) 管本批论文的力学与试验词。v1.0 保留作历史记录。

2026-10-02 核对下载目录的三份 PDF 时：Fang、Liu & Stoesser 2017 是新增；中文文件名的 Messias 2021 与 Helmer 2011 分别与下表已有 PDF 的 SHA-256 完全相同，因此没有在论文目录再存重复副本，下载目录中的这两份原文件仍保留。

2026-10-04 上午首次核对：当时目录为 21 篇。最近修改的 Fang 2017 PDF 已改用完整英文题名，其 SHA-256 与此前收录文件相同（`41948a2a807722fdd64021fbd738914b21ccaedeab011c43be5d8d35b2126542`），属于同一文件的改名。本次修复其链接，并依据原文方法与结论补充阅读建议。

2026-10-04 本轮新增：从下载目录移入 3 篇不同 PDF，总数为 24。两篇 Halswell 柔性充气艇文献放入 `02_艇体水动力与性能`，CFD 水滑道载具文献放入 `90_低优先级或参考`；沿用现有六类，不新建文件夹。Halswell 两篇内容重叠较多，但不是同一 PDF，保留原文件名。

## 每篇论文与迁移价值

| 类别 | 论文 PDF | 级别 | 对 packraft 的一句话价值与边界 |
|---|---|---|---|
| 01 | [Hémon 2018｜Sea kayak paddles](../../中文资料/01_桨叶推进与划桨力学/SRC-001/原始证据/Hemon2018_Sea_Kayak_Paddles.pdf) | **S** | 用桨周围水的惯性及阻力/升力解释“抓水”；研究的是海艇传统桨与现代桨，不能把效率排名照搬到白水桨。 |
| 01 | [Gomes 2015｜Paddling Force Profiles](../../中文资料/01_桨叶推进与划桨力学/SRC-002/原始证据/Gomes2015_Paddling_Force_Profiles.pdf) | **A** | 看不同桨频下的力—时间曲线，理解有效发力阶段；样本是精英静水竞速桨手。 |
| 01 | [Banks 2014｜Kayak blade–hull interactions](<../../中文资料/01_桨叶推进与划桨力学/SRC-003/原始证据/Kayak blade–hull interactions - A body force approach for self-propelled simulations.pdf>) | **B** | 提醒桨与艇体流场相互影响；计算对象是竞速艇，文中的小幅阻力差不是 packraft 实测。 |
| 02 | [Jackson 1995｜Performance prediction for Olympic kayaks](<../../中文资料/02_艇体水动力与性能/SRC-004/原始证据/Performance prediction for Olympic kayaks.pdf>) | **A** | 建立“桨效率—艇体阻力—功率—艇速”的预测链；参数属于奥运竞速艇。 |
| 02 | [Prétot 等 2022｜On the Physics of Kayaking](../../中文资料/02_艇体水动力与性能/SRC-005/原始证据/论皮划艇运动的物理学-english.pdf) | **S** | 用实测桨力、放任减速和起步试验连接推力、阻力、加速度；模型是静水 K1。 |
| 02 | [Ki 2012｜Inflatable Kayak Evaluation Method](../../中文资料/02_艇体水动力与性能/SRC-006/原始证据/Ki2012_Inflatable_Kayak_Evaluation_Method.pdf) | **B** | 借鉴倾斜、转弯和阻力测试的设计，作为充气艇系列的方法篇；试验艇与背包船不同。 |
| 02 | [Hah 2013｜Inflatable Kayak Hydrodynamics](../../中文资料/02_艇体水动力与性能/SRC-007/原始证据/Hah2013_Inflatable_Kayak_Hydrodynamics.pdf) | **B** | 比较不同充气艇的稳性、转弯与阻力，帮助识别设计取舍；与 2015 篇有内容重叠。 |
| 02 | [Hah 等 2015｜New Inflatable Kayak Hydrodynamics](../../中文资料/02_艇体水动力与性能/SRC-008/原始证据/Hah2015_New_Inflatable_Kayak_Hydrodynamics.pdf) | **S** | 同一框架比较不同船底充气艇的稳性、转弯和阻力；只迁移比较方法，不迁移绝对数值。 |
| 02 | [Halswell 等 2012｜Hydroelastic Inflatable Boats](<../../中文资料/02_艇体水动力与性能/SRC-009/原始证据/Hydroelastic Inflatable Boats: Relevant Literature and New Design Considerations.pdf>) | **A（选读）** | 补充“艇体变形与水动力相互影响”的水弹性框架；对象为机动滑行救生艇，不能据此证明背包船更软就更快、更稳或冲击更小。 |
| 02 | [Halswell 等 2011｜Flexibility and Environmental Considerations](<../../中文资料/02_艇体水动力与性能/SRC-010/原始证据/Design and Performance of Inflatable Boats: Flexibility and Environmental Considerations.pdf>) | **B** | 同一团队的早期会议论文，柔性、船底变形与砰击内容和 2012 篇高度重叠；看摘要与结构图即可，发动机噪声部分当前可跳过。 |
| 03 | [Hunter 2009｜Upstream Gate Trajectory](../../中文资料/03_激流回旋与控船/SRC-011/原始证据/Hunter2009_Upstream_Gate_Trajectory.pdf) | **S** | 用上水门轨迹分析选线与耗时，能启发进回水路径；**没有直接测量 eddy line 的流场**。 |
| 03 | [Messias 等 2021｜Canoe Slalom Review](../../中文资料/03_激流回旋与控船/SRC-012/原始证据/Messias2021_Canoe_Slalom_Performance_Review.pdf) | **A** | 快速找到回旋项目中机械、生理和技术证据及研究限制；不是具体控船动作的因果证明。 |
| 03 | [Messias 等 2018｜Novel Paddle Stroke Analysis](../../中文资料/03_激流回旋与控船/SRC-013/原始证据/精英激流回旋皮划艇运动员的新型划桨动作分析：与力参数的关系-english.pdf) | **B** | 了解精英回旋桨手的桨次与测力指标；系绳全力测试不等于真实过回水线。 |
| 04 | [Mignot 等 2016｜Lateral Cavity Mixing Interface](<../../中文资料/04_白水河流流体力学/SRC-014/原始证据/Coherent turbulent structures at the mixing-interface of a square open-channel lateral cavity.pdf>) | **S** | 看主流与侧向回流之间的剪切层和大尺度涡；水槽侧腔是回水的简化模型。 |
| 04 | [Kieffer 1985｜Crystal Rapid Hydraulic Jump](<../../中文资料/04_白水河流流体力学/SRC-015/原始证据/The 1983 Hydraulic Jump in Crystal Rapid - Implications for River-Running and Geomorphic Evolution in the Grand Canyon.pdf>) | **S** | 把天然急流大波、水跃和河道收缩放在同一案例中；个案不构成普遍行船规则。 |
| 04 | [Chanson 2009｜Hydraulic Jumps Review](<../../中文资料/04_白水河流流体力学/SRC-016/原始证据/Current knowledge in hydraulic jumps and related phenomena. A survey of experimental results.pdf>) | **A** | 区分起伏水跃、破碎水跃、滚水及掺气，建立浪和洞的概念框架。 |
| 04 | [Wyrick & Pasternack 2008｜River Steps](<../../中文资料/04_白水河流流体力学/SRC-017/原始证据/Modeling energy dissipation and hydraulic jump regime responses to channel nonuniformity at river steps.pdf>) | **A** | 理解同一落差随流量、淹没程度和河道几何变化而呈现不同水跃形态。 |
| 04 | [Han 等 2017｜Shallow Mixing Layer](<../../中文资料/04_白水河流流体力学/SRC-018/原始证据/Shallow Mixing Layer Downstream from a Sudden Expansion.pdf>) | **A** | 研究突然扩宽后的主流、回流及其边界，可接在 Mignot 后看；仍是理想化几何。 |
| 04 | [Fang、Liu & Stoesser 2017｜Submerged Boulder Arrays](<../../中文资料/04_白水河流流体力学/SRC-019/原始证据/Influence of Boulder Concentration on Turbulence and Sediment Transport in Open-Channel Flow Over Submerged Boulders.pdf>) | **B** | 帮助理解石块间距如何改变尾流及局部剪应力；固定水深、采用刚盖水面的大涡模拟，不能直接解释水位变化、水面浪洞或背包船停靠回水。 |
| 04 | [Cameron 等 2017｜Rough-bed Open-channel Flow](<../../中文资料/04_白水河流流体力学/SRC-020/原始证据/Very-large-scale motions in rough-bed open-channel flow.pdf>) | **B** | 提醒河床粗糙度和大尺度湍流会改变实际来流；当前控船学习先看图与结论。 |
| 05 | [Michael 等 2009｜Determinants of Kayak Paddling Performance](<../../中文资料/05_人体生物力学与训练/SRC-021/原始证据/Determinants of kayak paddling performance.pdf>) | **A** | 把人、桨、艇与竞速表现串成知识地图；多是静水竞速证据。 |
| 90 | [Kendal & Sanders 1992｜Wing Paddle Technique](<../../中文资料/90_低优先级或参考/SRC-022/原始证据/The Technique of Elite Flatwater Kayak Paddlers Using the Wing Paddle.pdf>) | **C** | 可看桨叶相对水的轨迹测量；翼桨和白水桨差异大，不按其动作练习。 |
| 90 | [Helmer 等 2011｜Instrumented Kayak Paddle](../../中文资料/90_低优先级或参考/SRC-023/原始证据/皮划艇桨的仪器化研究以探究桨叶:水的相互作用-english-Instrumentation-of-a-kayak-paddle-to-investigate-blade-_2011_Procedia-Engine.pdf) | **C** | 若以后自制测力桨，可参考传感器布置；论文也说明单点压力并不能直接给出整桨力。 |
| 90 | [Aksoy & Kükner 2023｜Inflatable Boat Motion CFD](<../../中文资料/90_低优先级或参考/SRC-024/原始证据/Simulation of Inflatable Boat Motion with CFD on Free Surface Flows.pdf>) | **C** | 自由水面 CFD 与惯性测量对照可作方法参考，但图 18 的工况是水滑道中的充气载具；忽略艇内空气作用与柔性变形，不补背包船水弹性或回水控船缺口。 |

## 建议阅读顺序

1. **建立桨—船模型：**Hémon 2018 → Prétot 2022 → Jackson 1995 → Gomes 2015。边读边画出“桨受力 → 身体传力 → 船加速 → 阻力让船减速”。
2. **把模型放到充气艇：**Hah 2015 → Ki 2012/Hah 2013 的图表 → Halswell 2012 的结构、水弹性与砰击部分。前半段看稳性、阻力和转弯，后半段补“受水力后船形也会改变”的反馈；不要套用竞速艇或滑行救生艇的绝对数值。Halswell 2011 仅在需要早期背景或环境噪声议题时补读。
3. **理解主流与回水：**Mignot 2016 → Han 2017 → Hunter 2009。前两篇讲水流结构，Hunter 讲运动员选择的船轨迹；把两类证据分开。若想进一步理解石块群之间的尾流干扰，再插入 Fang 2017 的图 1、4、5。
4. **理解浪、洞与落差：**Kieffer 1985 → Chanson 2009 → Wyrick & Pasternack 2008。先看河流实例，再用综述补术语，最后看流量和几何条件如何改变水跃。
5. **按需补充：**Michael 2009 和 Messias 2021 用作索引；Banks、Messias 2018、Cameron 2017 看图和结论。Fang 2017 接在 Mignot/Han 之后看尾流图，重点辨认其“淹没石块、近河床”的研究范围；`90_` 暂不精读。

建议每篇只记三个问题：研究对象是什么？测到了什么？其中哪一条机制可以迁移到我的船？白水中的船头和船尾可能处在不同流速的水里，但上述静水艇论文很少直接测这个过程。**水跃、驻波、滚水也不是必然依次出现的一条固定序列**，应按具体流量、河床和上下游水深判断。

### 本轮三篇：柔性充气艇怎样接入路线

**分类依据是主要研究问题。**水弹性讨论艇体结构与水动力耦合，沿用 `02` 即可；CFD 一篇虽有 “inflatable boat” 题名，实际滑道工况与背包船差异大，放 `90`。当前两篇相关文献不足以另建“软船结构”分类。

#### Halswell 等 2012：A 级选读，接在 Hah 2015 后

题名与 DOI 由本地首页及[南安普顿大学作者稿](https://eprints.soton.ac.uk/208257/1/Final_Format_IJSCT_125tn.pdf)核对：技术短文，DOI **10.3940/rina.ijsct.2012.b1.125tn**。它是一份机制与研究方法的综述，不是背包船实测。其 IB1 是约 5 米、50 马力的机动充气救生艇，与人力背包船在船底、结构、载荷及速度上有显著差别。

- **先读结构与整体变形：**PDF 第 3–4 页，图 2、3，以及 “Global Hydroelasticity”。建立“水力改变船形，改变后的船形又影响水力”的反馈；材料、气压、船底预张力和连接刚度都可能参与。
- **再读船底变形的取舍：**PDF 第 4–5 页，图 4、5。文中引用的柔性实艇与刚性缩尺模型比较，并没有证明柔性一定减阻；滑行面变形和纵倾也可能损害性能。图中的高速滑行现象不能直接套用背包船。
- **最后看入水砰击：**PDF 第 5–6 页的 “Hydroelastic Slamming”，图 7、8，以及第 8–9 页讨论与结论。柔性可能改变冲击峰值和持续时间，但作者也指出相关收益尚有不确定性；不要直接推出“降低气压就更安全、更舒适”。
- **可跳过：**详细数值方法、滑行性能设计循环和高速喷溅优化，除非之后专门研究软船设计。页码指 12 页本地 PDF 的页序。

**对背包船的收益：**以前的静水艇模型主要把船形视为给定；这篇补上了船形会随载荷和水力变化的概念。它仍不提供 Mini Shark 气压—刚度—阻力—转弯响应的实测关系，也不证明重心或立刃动作的效果。

#### Halswell 等 2011：B 级，避免重复精读

[大学馆藏记录](https://eprints.soton.ac.uk/183099)确认这是 2011 年 HSMV 会议论文，10 页。与 2012 篇的作者、IB1 案例、三类水弹性问题及研究方法高度重叠；这里仅认定内容重叠，不假定正式版本继承关系。先读摘要、结构说明与图；读过 2012 篇后不必再整篇翻译精读。环境噪声部分主要讨论机动艇，目前对人力背包船价值低。

#### Aksoy & Kükner 2023：C 级，放在路线末尾

[会议官方日程](https://int-nam.com/wp-content/uploads/2023/10/PROGRAM_INT-NAM_2023_rev07.pdf)列有该报告；按会议年份记为 2023。本地是 18 页、带编辑模板提示的稿件，未据此确认正式排版版本或 DOI。

先看 **图 18（PDF 第 15 页）**：模型布置是水滑道，其验证不是背包船在天然河流中的漂流或转向试验。模型使用自由水面 VOF，但摘要明确忽略艇内空气作用，亦未建模柔性结构的反馈。**模拟自由水面不等于模拟软船水弹性。**

若将来做传感器或运动仿真，再看第 13–17 页的测量与运动对照。文中把 CFD 得到的底部剪切作用换成基于重量的摩擦系数，用于 SolidWorks 运动模型；这不是完整背包船阻力模型。表 4、5 的误差是该工况的运动时长误差，不是全部流场、受力或船轨迹都已得到相同精度的验证。当前看摘要、图 18 和结论即可。

### Fang 2017：怎样读最划算

**维持 B 级，先看图和结论，无需整篇精读。**它补充的是“相邻淹没石块的尾流如何相互影响”，与 Mignot/Han 的侧腔或扩宽回流模型形成互补；对实际船体受力的帮助仍是间接的。

- **先看方法边界：**原 PDF 第 4–5 页、§2.2。比较无石块和纵向间距为石块直径 10、5、2 倍的三组石块阵列；水深始终为石块直径的 3.5 倍，平均流速固定。水面采用无摩擦刚盖与自由滑移条件，未模拟变形自由水面。因此不能用这篇判断同一石块在涨水时何时产生浪、洞或可用回水。
- **再看图：**图 1（PDF 第 23 页）认清理想化阵列；图 4（第 26 页）比较近床减速区；图 5（第 27 页）看石后方三维流线随间距变化。需要理解河床受力时再看图 8（第 30 页），不要把近床剪应力图当成船在水面受到的力。
- **最后看结论：**§5（PDF 第 17 页）。记住“石块之间的距离会改变尾流恢复与干扰，局部流场不能只用一条平均流速代表”即可。上述规律来自该模拟条件，文中的尾流长度不能当作实河回水长度公式。泥沙输运公式与输沙预测误差暂可跳过。

本地已有[中文译稿](../../中文资料/04_白水河流流体力学/SRC-019/中文译文.md)，可配合原 PDF 图表阅读；本次未校对译稿。页码指这份 39 页作者稿的 PDF 页序。

## 此前点名的核心文献覆盖情况

已覆盖 **全部 16 篇/项 PDF**：Hémon 2018、Jackson 1995、Prétot 2022、Hunter 2009、充气艇 2012/2013/2015 三篇、Gomes 2015、Banks 2014、Messias 2021、Mignot 2016、Kieffer 1985、Chanson 2009、Wyrick & Pasternack 2008、Han 2017、Cameron 2017。这里将“inflatable kayak hydrodynamics 系列”按三篇计数。**没有点名核心论文缺失。**另有 Michael 2009、Messias 2018、Kendal 1992、Helmer 2011、Fang 2017 五篇；本轮另加 Halswell 2011、Halswell 2012、Aksoy & Kükner 2023 三篇。

## 你给的关联 DOI：是否还要下载？

下面的题名按 DOI 核对。**目前没有一篇需要为第一轮理解 packraft 而立即新增下载并精读。**“摘要/图”表示网页摘要已够决定取舍；如以后要做桨力仪器，才考虑 1992 年 Aitken & Neal 的全文。赛艇（rowing）是桨经桨架传力、通常有滑座的另一套系统，不能把桨架、脚撑高度和赛艇测功仪结果直接当作手持双叶桨证据。

| DOI 对应论文 | 判断 | 原因 |
|---|---|---|
| [Baudouin & Hawkins 2002｜Rowing biomechanics review](https://doi.org/10.1136/bjsm.36.6.396) | **只看摘要/图** | 是赛艇；通用的推力与阻力概念已被本地皮艇文献覆盖。 |
| [Three-Axes Gyro System Quantifying the Specific Balance of Rowing 1993](https://doi.org/10.1055/s-2007-1021222) | **基本不用读** | 赛艇平衡测量，不回答背包船立刃或回水控船。 |
| [Kendal & Sanders 1992｜Wing Paddle Technique](https://doi.org/10.1123/ijsb.8.3.233) | **已收录，C** | 本地已有 PDF；翼桨技术只作参考。 |
| [Stretcher Height and Rowing Effectiveness 2005](https://doi.org/10.1123/jab.21.3.286) | **基本不用读** | 赛艇测功仪的脚撑高度问题。 |
| [Olympic Sprint Canoe/Kayak Morphology 2003](https://doi.org/10.1016/S1440-2440(03)80022-1) | **只看摘要/图** | 运动员体型信息；与当前水动力问题关系弱。 |
| [Oarsman Force and Boat Speed 1987](https://doi.org/10.1080/02640418708729769) | **基本不用读** | 赛艇力学；本地 Jackson/Prétot 更直接。 |
| [Rowing Performance Biomechanics 2004](https://doi.org/10.1016/j.jbiomech.2003.11.011) | **基本不用读** | 研究赛艇而不是皮艇。 |
| [Aitken & Neal 1992｜On-Water Kayak Force Analysis System](https://doi.org/10.1123/ijsb.8.2.165) | **只看摘要/图；做测力桨时再下载** | 皮艇实船测力方法有用，但现阶段读 Gomes 和 Helmer 已足够。 |
| [The Flatwater Kayak Stroke 1985](https://doi.org/10.1519/0744-0049(1985)007%3C0004:TFKS%3E2.3.CO;2) | **基本不用读** | 静水竞速技术短文，证据较旧。 |
| [Towards Optimizing Rowing Technique 1986](https://doi.org/10.1249/00005768-198608000-00016) | **基本不用读** | 赛艇技术优化。 |
| [Rowing Ergometer Instrumentation 1997](https://doi.org/10.1080/026404197367434) | **基本不用读** | 赛艇测功仪可靠性。 |
| [Shephard 1987｜Science and Medicine of Canoeing and Kayaking](https://doi.org/10.2165/00007256-198704010-00003) | **只看摘要/图** | 主要是竞赛生理与运动医学；若转向训练负荷再查。 |
| [Kayak and Basilisk Propulsion 1998](https://doi.org/10.1088/0143-0807/19/5/003) | **只看摘要/图** | 可作物理启蒙，但与本地桨力/艇速模型重叠。 |
| [Ergometer Rowing Musculoskeletal Loads 2004](https://doi.org/10.1123/jab.20.3.317) | **基本不用读** | 赛艇测功仪肌骨负荷。 |
| [Olympic Flatwater Kayaking/Canoeing Biomechanics 1979](https://doi.org/10.1080/00345377.1979.10615632) | **只看摘要/图** | 历史动作影像分析，可作背景，不必优先复刻动作。 |
| [Olympic-Style Flatwater Kayak Stroke 1980](https://doi.org/10.1249/00005768-198023000-00010) | **只看摘要/图** | 早期动作与重心分析；本地较新综述可先读。 |
| [Jackson 1995｜Performance Prediction](https://doi.org/10.1080/02640419508732233) | **已收录，A** | 本地已有 PDF，无需再下载。 |
| [Biomechanics Feedback for Rowing 2002](https://doi.org/10.1080/026404102320675639) | **基本不用读** | 赛艇反馈方法，不是当前物理缺口。 |

## 真正还缺的方向与下载边界

1. **石块后方的真实回流与水深变化。**Fang 2017 已收录，补上了淹没石块群近河床尾流的模型视角；Mignot/Han 则是侧腔或扩宽水槽。三者都不能直接代表不同水位下可供背包船停靠的水面回水。若读完仍有这个具体问题，再看 [UCL 的 2025 年相对淹没深度研究](https://discovery.ucl.ac.uk/id/eprint/10211372/)摘要与流场图，暂不叠加下载。
2. **船跨速度梯度时的直接受力，以及软船立刃/重心的实测。**本目录没有一篇直接测 packraft 船头入回水、船尾留主流时的力矩，也没有 Mini Shark 的立刃响应实测。Halswell 2012 补上了水弹性概念与设计问题，但研究对象是滑行救生艇，尚未补上背包船气压、载荷、变形与受力之间的实测；Aksoy 2023 的滑道模型也不解决该问题。当前更值得用安全环境中的观察记录或小实验提出问题，再定向找论文；不能用硬壳回旋艇或充气皮艇的数值填这个空白。

**结论：先读现有 S/A 文献。关联 DOI 不必批量下载。**每读完一个主题，再决定是否补一篇针对具体疑问的论文。
