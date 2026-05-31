# 医疗 AI 领域知识库

## 领域历史知识摘要

### 当前阶段判断
医疗 AI 已进入"规模化临床部署与盈利验证期"：环境感知文档从单一医院生态扩展至联邦政府（VA 全国 130+ 站点铺开），多模态病理 AI 进入乳腺癌精准治疗决策，可穿戴健康平台启动 IPO（Oura 秘密申报），但 Nature Medicine 元分析揭示 99% 以上 LLM 医疗研究仅在模拟环境验证，"实验室优秀、临床存疑"成为行业必须正面回答的系统性问题。

### 主要趋势（5条）

1. **环境感知 AI 文书覆盖范围从医院扩展至政府体系**：美国 VA 签约将环境 AI 文书铺至全国 130+ 医学中心（最大政府单笔部署），Athenahealth 对全平台用户免费开放 athenaAmbient，Oracle Health 覆盖 30+ 专科；环境文书工具从"付费增值模块"升级为各主要 EHR 的基础能力标配，行业格局加速固化。

2. **多模态病理 AI 突破乳腺癌风险分层，进入治疗决策辅助**：ArteraAI Breast 于 5 月 6 日获 FDA 510(k) 清关，成为首个 FDA 认可的乳腺癌数字病理风险分层工具（HR+/HER2-），基于常规组织切片同日出具结果；继 Mosaic Cognita CXR 获放射学突破性器械认定后，病理 AI 完成从"形态识别辅助"到"治疗风险预测"的跨越。

3. **AI 药物发现进入疗效大规模验证窗口**：Phase I 成功率约 80-90%（历史均值 52%），rentosertib Phase IIa 已在人体证明疗效，173 个 AI 原生药物项目在研，2026 年全年 Phase III 密集读出；"AI 能否以规模化数据证明超越传统药物"成为年内最高关注度命题。

4. **付款方与大型卫生系统开始量化 AI ROI**：UnitedHealth 预测 AI 节省近 10 亿美元、HCA Healthcare 约 4 亿美元，说明 AI 价值从叙事层进入财务可量化阶段；这一信号将加速医院采购决策，也将提高对未能展示量化 ROI 的厂商的门槛。

5. **LLM 临床验证危机浮现，推动"真实世界证据优先"监管导向**：Nature Medicine 元分析揭示不足 1% 的 LLM 医疗研究在真实临床环境中验证，引发监管机构（FDA、EU AI Act）和付款方对 LLM 工具临床证据标准的重新审视，可能触发强制要求提交真实世界证据的新监管框架。

### 技术热点
- **多模态病理 AI + 治疗风险分层**：ArteraAI 模式（组织学图像 + 临床变量 → 治疗方案分层）将成为肿瘤病理报告新标准，前列腺癌 + 乳腺癌双适应症均已获清关，下一步适应症扩展在即。
- **环境感知 AI 文书（跨平台全覆盖阶段）**：Epic、Oracle Health、Athenahealth、VA 政府体系均已上线，差异化竞争转向准确率、专科适配与 EHR 深度集成。
- **自主 AI 肿瘤学代理**：Nature Cancer 论文验证自主 AI 代理（多工具 + 多模态）在肿瘤临床决策达 91% 准确率，较单纯 GPT-4 提升逾 60 个百分点，为 ARPA-H ADVOCATE 心血管代理提供学术背书。
- **患者端 AI 健康界面（B2C 化）**：Microsoft Copilot Health、Amazon 健康 AI 助手将 AI 推至患者一侧，消费级 AI 成为医疗"第一接触点"，可及性与健康公平性成为新政策议题。

### 商业格局
- **Oura IPO 申报**（5 月 21 日）是可穿戴健康赛道首次大规模公开市场测试，110 亿美元估值、20 亿美元年收入预期将为后续融资定价；Oura Ring 5 同步发布强化临床叙事。
- **ASCO 2026（5 月 29 日 - 6 月 2 日）**：Canopy、Tempus、Mayo Clinic 等密集输出真实世界肿瘤 AI 数据，预计驱动下一轮肿瘤 AI 融资事件；ArteraAI 在 Tempus 生态内已开始商业化落地。
- **消费级平台入局**：Microsoft、Amazon 相继推出面向患者的 AI 健康助手，B2B 与 B2C 两条线并行，平台层竞争边界扩大。
- **平台层**：Microsoft（Nuance DAX/Dragon Copilot，77% 医院覆盖）维持企业级环境 AI 领导地位；Oracle Health 通过内嵌 Clinical AI Agent 覆盖 30+ 专科加速追赶。

### 监管走向
- **FDA TEMPO 试点**：每个慢性病领域约 10 家厂商可获预市审批执法豁免，配合 CMS ACCESS 模型大幅压缩临床 AI 上市周期，是 1 月 CDS 松绑政策的具体落实机制，预计引发中小厂商密集申报。
- **FDA 就 AI 早期临床试验发布 RFI**（4 月 29 日）：监管框架从 AI 诊断器械延伸至 AI 在新药研发全链路中的角色，为药物发现 AI 的未来监管路径探路。
- **欧盟 AI 法案高风险条款**：2026 年 8 月高风险 AI 义务生效，2027 年 8 月医疗设备 AI 全面合规，对欧洲及出口欧洲市场的厂商形成时间压力。
- **特朗普 AI 行政令推迟**（5 月 21 日）：联邦层面的自愿安全共享框架悬而未决，政策不确定性延续，医疗 AI 联邦采购和标准制定节奏受影响。

### 值得持续跟踪的信号
- **ARPA-H ADVOCATE 团队遴选结果（2026 年 6 月，即将揭晓）**：首批入选团队的技术路线将定义"自主 AI 处方权"的监管边界，同时为同类创业公司提供路线图。
- **Oura IPO 路演与定价**：完整财务数据公开后，可穿戴 AI 健康商业模式将首次接受公开市场检验；路演期间的机构投资人反馈将影响 Abridge 等候场 IPO 的择时决策。
- **ASCO 2026 AI 数据后续影响**（6 月 2 日闭幕）：Canopy 和 ArteraAI 的真实世界数据质量将直接影响肿瘤 AI 商业化落地信心与融资窗口。
- **Nature Medicine 元分析引发的"LLM 临床验证运动"**：FDA TEMPO、EU AI Act 是否将其作为新增监管要求的依据，将直接决定数百个待审 LLM 医疗工具的时间表和合规成本。
- **AI 药物 Phase III 密集读数（2026 年全年）**：rentosertib 及其他 AI 原生药物的 Phase III 成败，是判断"AI 药物发现"从技术叙事走向真实商业价值的最关键数据节点。

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
