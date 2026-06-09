# 医疗 AI 领域知识库

## 领域历史知识摘要

### 当前阶段判断
医疗 AI 已进入"规模化验证与合规重置期"：Philips 全球调研（2026-06-09）以量化数据证实 AI 临床时间节省效应（每年 16 个工作日），代理 AI 在 EHR 和公共医疗系统同步投入日常运营，EU AI Act 医疗器械合规截止从 2026 年 8 月延至 2028 年 8 月（Omnibus 协议）给 MedTech 行业释放缓冲空间，AI 药物发现则因 Isomorphic Labs 21 亿美元 B 轮和 FDA RTCT 试点启动进入"资本 + 监管双加速"阶段。

### 主要趋势（5条）

1. **AI 医疗基础设施走向多年期深度生态绑定**：NHS England 向 50.5 万名医务人员部署 Microsoft 365 Copilot（2026-10 完成），为全球最大单次企业医疗 AI 部署；Mayo Clinic + Microsoft 于 6 月 2 日宣布联合开发医疗专用前沿基础模型（Mayo 所有权，通过 Azure Foundry API 对外开放）；NVIDIA + Foxconn 与台湾医疗中心联合启动 15 亿美元"健康台湾"计划（COMPUTEX 2026），生态绑定已从欧美扩展至亚洲公共医疗系统。

2. **自主 AI 代理从试点走向头部机构日常运营，联邦授权路径进入实施**：Epic Agent Factory 在 Advocate Health 投产，ARPA-H ADVOCATE 于 6 月完成创新团队遴选（提供 3 年 FDA 授权路径），Abridge 从环境听写升级为主动上下文助手（整合 UpToDate 诊间循证推荐）；大规模研究（1,800 名临床医生）确认环境 AI 每 8 小时节省 16 分钟文档时间，效益数据从个案走向统计验证。

3. **AI 药物发现进入"资本 + 监管双加速"阶段**：Isomorphic Labs 完成 21 亿美元 B 轮（Thrive Capital 领投，含 Alphabet、UK Sovereign AI Fund），首批肿瘤候选药临床试验预计 2026 年底启动；Eli Lilly 落成 LillyPod——全球首台制药 AI 超算（1,016 块 NVIDIA Blackwell Ultra GPU，9,000+ petaflops）；FDA 实时临床试验（RTCT）试点以 AstraZeneca 和 Amgen 药物为 POC，预期缩短 20-40% 试验周期；Insilico rentosertib Phase III H2 2026 入组确认启动。

4. **AI 临床效益进入量化验证期，部署差距与人员培训成最大阻力**：Philips Future Health Index 2026（10 国 2,000+ 临床医生）以量化数据确认：AI 每年为临床医生节省 16+ 工作日，接诊能力提升（每周多 8 名患者），39% 称 AI 预防了医疗差错；但 70% 指出培训不足是广泛部署的主要障碍，IT 碎片化是次要障碍——表明 AI 技术本身已不是瓶颈，组织能力建设是决定规模化速度的关键变量。

5. **全球监管格局重置：EU 宽限延期，美国加速开绿灯**：EU AI Act Omnibus 临时协议（2026-05-07）将医疗器械高风险 AI 合规截止从 2026-08 延至 2028-08，为 MedTech 行业释放约两年缓冲；与此同时美国持续加速：FDA RTCT 试点降低临床试验周期，CPT Category I AI 代码打通报销通道，ARPA-H ADVOCATE 提供联邦级授权路径——欧美监管节奏正式出现系统性分化。

### 技术热点
- **医疗专用前沿基础模型竞赛**：Mayo Clinic + Microsoft 联合模型（多源临床数据 + Azure 超算）、Tempus 多模态肿瘤模型（病理图像 + 基因组 + 临床记录）、Epic Curiosity 系列（匿名真实 EHR 训练）三路并进，医学 AI 基础模型正快速从通用向高度专科化、多模态演进。
- **多代理编排平台**：Foxconn CoDoClaw（统一管理乳腺癌筛查/ECG/眼底成像/冠脉分析）、Epic Agent Factory（无代码可视化）、ARPA-H ADVOCATE 监督代理架构，多代理系统协调成为医疗 AI 的下一个核心工程挑战。
- **AI 药物设计算力基础设施化**：LillyPod（9,000+ petaflops 制药专用超算）标志着 AI 药物发现从云端借用算力转向企业自有专项基础设施，降低大型药企对外部计算资源的依赖。
- **环境 AI 向主动临床助手演进**：Abridge 整合 UpToDate 循证推荐，环境 AI 产品从"记录工具"升级为"诊间决策辅助"，差异化从准确率转向上下文推理深度。

### 商业格局
- **平台层**：Microsoft 三线并进（NHS Copilot 生态 + Dragon Copilot 开放平台 + Mayo 定制基础模型），Philips 以 Future Health Index 全球品牌影响力持续领先医疗 AI 叙事；NVIDIA 通过 Foxconn 进入亚洲公共医疗市场（台湾 15 亿美元），算力层向医疗终端延伸。
- **AI 药物发现**：Isomorphic Labs（21 亿美元 B 轮）与 Insilico（rentosertib Phase III）领跑"AI 原生药企"，Eli Lilly LillyPod 代表传统大药企以自建算力基础设施加入竞争，药物发现 AI 格局从初创主导向大型制药企业深度参与转变。
- **临床代理与听写市场**：Abridge（250+ 医疗系统，KLAS 两连冠）以主动助手升级强化壁垒；voize 完成 5000 万美元 A 轮进入美国护理市场（非医生细分），精神健康 AI（Blossom Health $20M、Jimini Health $17M、The Path $14.3M）成为新融资热点。
- **医疗 AI 投融资**：Q1 2026 达 74 亿美元（8 家新独角兽），AI 专项占健康科技总融资 75%；2026 全年大额轮次持续（Isomorphic $2.1B、Abridge $300M+ 等）。

### 监管走向
- **EU AI Act 医疗器械合规重置（最新）**：Omnibus 临时协议（2026-05-07）将内嵌于医疗器械的高风险 AI 合规截止延至 2028-08-02（独立 Annex III 系统延至 2027-12-02），正式文本预计 2026-08-02 前通过；但 AI 素养义务（Article 4）维持 2026-08-02 截止不变——这一延期从根本上改变了此前知识库中的"60 天合规倒计时"判断，行业整体压力降低，但 Article 4 培训合规依然迫切。
- **美国 AI 报销 + 授权双通道**：2026 CPT AI 代码打通报销，ARPA-H ADVOCATE 提供 3 年 FDA 授权路径，FDA RTCT 缩短临床验证时间，美国正构建完整的"发现→验证→清关→报销"AI 医疗产品化链条。
- **Mount Sinai 全球政策碎片化研究**：240 项政策分析（2016-2025）揭示医疗 AI 监管高度碎片化，无统一框架——提示跨国医疗 AI 公司的合规复杂度将持续上升。

### 值得持续跟踪的信号
- **NHS Copilot 实际效益数据（7 月起分波段上线）**：50.5 万用户规模是全球最大医疗 AI 效益验证实验，实际数据将与 Philips 全球调研（16 工作日/年）形成交叉验证。
- **EU AI Act Article 4 执行（2026-08-02 截止）**：延期后首个不变的合规节点，70% 临床医生反映培训不足，执法强度将揭示 EU 对医疗 AI 合规的实际立场。
- **EU AI Act Omnibus 正式文本通过时间**：若在 2026-08-02 前未完成立法程序，将产生短暂的法律真空，引发 MedTech 市场不确定性。
- **Isomorphic Labs 首批肿瘤候选药临床试验启动**：2026 年底目标，启动后将成为 AI 原生大额融资的最近期临床验证节点。
- **rentosertib Phase III 入组速度与 LillyPod 首批分子**：两者将分别代表 AI 独立药企和大型制药企业 AI 战略的最近期临床节点。
- **ARPA-H ADVOCATE 入选团队首年进展**：联邦级代理 AI 授权路径的实际推进速度，将定义美国临床 AI 代理的监管标杆。
- **Mayo Clinic 前沿 AI 模型发布时间线**：与 Microsoft 合作开发的医疗专用模型何时通过 Azure Foundry 对外开放，以及首批使用机构的临床结果。
## 抽象搜索特征

### 机构与人物
- 行业领军企业
- 顶级研究机构
- 知名医疗 AI 学者
- FDA/NMPA 监管动态
- 头部医院 AI 落地

### 商业信号
- 估值超高
- 大额融资
- 并购整合
- IPO 上市
- 战略合作

### 技术信号
- 突破性进展
- 临床验证通过
- 大规模部署
- 开源发布
- 性能超越人类

### 风险信号
- 监管受阻
- 临床失败
- 数据隐私争议
- 算法偏见
- 市场退出

## 具体搜索描述

### 产品与技术方向
- Medical LLM
- Clinical AI agent
- Diagnostic AI
- Wearable AI health monitor
- AI-assisted surgery
- Pathology AI
- Radiology AI
- Drug discovery AI
- Clinical trial AI
- EHR AI copilot
- Medical imaging foundation model
- AI triage system

### 重点公司/产品
- Google Med-PaLM
- Microsoft DAX Copilot
- Nuance AI
- Tempus AI
- Viz.ai
- Nabla
- Abridge
- Suki AI

### 监管与标准
- FDA AI/ML action plan
- EU AI Act medical device
- NMPA 人工智能医疗器械
- SaMD（Software as Medical Device）

### 数据与基础设施
- Federated learning healthcare
- Medical foundation model
- Clinical NLP
- FHIR AI integration
