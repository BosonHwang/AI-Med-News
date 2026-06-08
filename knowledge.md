# 医疗 AI 领域知识库

## 领域历史知识摘要

### 当前阶段判断
医疗 AI 已进入"规模化部署与合规双重压力期"：代理 AI 在头部 EHR（Epic Agent Factory 投产于 Advocate Health）和公共医疗体系（NHS 50.5 万人 Microsoft 365 Copilot 部署）同步从试点走向规模运营，AI 报销瓶颈被 2026 CPT Category I 代码突破，EU AI Act 高风险合规截止日（2026-08-02）倒逼全球 MedTech 完成治理体系重构，药物发现 AI 则以 rentosertib Phase III 启动和 Tempus 多模态基础模型为节点进入成果验证关键窗口。

### 主要趋势（5条）

1. **AI 医疗基础设施走向多年期深度生态绑定**：NHS England 6 月 8 日宣布 50.5 万名医务人员部署 Microsoft 365 Copilot（2026 年 10 月前完成），成为全球医疗史最大单次企业 AI 部署，预计月均夺回 250 万临床工时；此前 Microsoft Dragon Copilot 在 HIMSS 2026 升级为开放平台（日活 10 万+ 临床医生、9 国），Philips-WellSpan 7 年联盟、AHA-West Health 1200 万美元三年期 AI 加速器等长期绑定协议持续涌现，深度生态锁定已成头部玩家标配。

2. **自主 AI 代理从试点走向头部机构日常运营**：Epic Agent Factory 于 6 月 1 日在 Advocate Health 正式投产，85% 的 Epic 客户已使用 AI 功能；ARPA-H ADVOCATE 于 6 月进入联邦级临床代理 AI 授权路径创新团队甄选；Elation Health 收购 Aster 打造基层医疗代理 OS；eClinicalWorks 在 HIMSS 26 推出 AI API Workbench；代理 AI 正从"演示阶段"整体进入头部机构部署阶段。

3. **AI 药物发现加速进入临床验证期，专项基础模型持续迭代**：OpenAI GPT-Rosalind 发布功能升级版（新增代理编码、生物信息学工作流插件），继续向全球受控访问机构开放；Insilico rentosertib Phase III 确认 H2 2026 启动（吸入制剂同期获中国 IND 批准）；Relay Zovegalisib Phase 3 全球入组中（mPFS 11.1 月，FDA 突破性疗法认定）；全球 AI 发现药物 Phase III 管线数量稳定在 15+ 并持续扩大。

4. **AI 诊断报销瓶颈开始松动，商业规模化路径趋于清晰**：2026 年 CPT 代码集首次引入 AI 辅助诊断 Category I 代码（含 RVU 价值），覆盖影像、病理、心脏、败血症/卒中等场景，部分解除 AI 医疗器械商业化最大障碍；FDA 清关速率达 2026 年 3 月单月 24 款（约每 31 小时 1 款），累计 1,357 款；Tempus AI 获 FDA 批准 xT CDx 仅肿瘤适应症，成全球首家双路径 CDx 获批实验室。

5. **数据信任与合规执行从原则声明走向双向压力**：Palantir NHS 3.3 亿英镑合同因数据治理违约面临议会施压退出（2027 年 2 月触发条款），与 NHS England 同期大规模部署 Microsoft Copilot（合同内含数据训练禁用条款、数据中心锁英国）形成鲜明对比——相同 NHS 场景，治理条款设计决定社会接受度；EU AI Act 高风险合规 8 月截止，Apple Watch 高血压检测 JAMA 研究（灵敏度仅 41%）揭示可穿戴临床声称与实际精度的落差。

### 技术热点
- **EHR 原生代理平台竞争**：Epic Agent Factory（无代码可视化）、eClinicalWorks AI API Workbench（开发者开放）、Elation-Aster（基层医疗 OS）三条路线并行，代理 AI 嵌入 EHR 成为 2026 年最活跃的技术整合方向。
- **多模态肿瘤基础模型**：Tempus AI 在 ASCO 2026 发布多模态基础模型结果（跨病理图像 + 基因组 + 临床记录），与 Epic Curiosity 系列代表医学 AI 从单模态向多模态预测的代际升级。
- **生命科学专项 LLM 持续进化**：GPT-Rosalind 升级版（代理编码 + 生物信息学插件）迭代周期加快，与 Tempus Lens 代理平台路线形成专项模型 vs. 代理平台的路线之争。
- **可穿戴临床精度争议**：Apple Watch 高血压检测 JAMA 分析（灵敏度 41%）、Oura/Google 积累高血压数据但未达 FDA 门槛，可穿戴"消费级精度 vs. 临床级标准"的界定成为下一个监管焦点。

### 商业格局
- **平台层**：Microsoft 再下一城——NHS 50.5 万人 Copilot 部署（2026-10 完成）将成全球最大医疗 AI 合同参考案例，Dragon Copilot 开放平台 + Copilot Health 消费者端 + Mayo 定制模型三线并进，生态宽度无竞争对手。
- **EHR 代理竞争**：Epic（Agent Factory + Curiosity）vs. 新兴代理 EHR（Elation-Aster）vs. 中型 EHR 开放平台（eClinicalWorks API Workbench），代理 AI 成为 EHR 市场份额争夺的新战场。
- **肿瘤精准医学**：Tempus AI 以 FDA xT CDx 双路径 + ASCO 多模态模型 + Lens 代理平台构建端到端肿瘤 AI 基础设施；Relay Zovegalisib Phase 3 是 AI 设计药物的最近期临床验证节点。
- **护理 AI 新赛道**：voize（德国，护士环境 AI，$50M A 轮）于 2026 Q1 进入美国市场，对应护士文档需求的"非医生"细分场景正成为新的融资热点。
- **医疗 AI 投融资**：Q1 2026 达 74 亿美元（8 家新独角兽），AI 专项占健康科技总融资 75%；大额轮次持续（Abridge $300M、Ambiance $243M、Function Health $300M）。

### 监管走向
- **EU AI Act 高风险合规截止日（2026-08-02）**：距截止不足 60 天，AI 影像诊断软件、临床决策支持 SaMD 被自动归为高风险，需完成双重框架（AI Act + MDR/IVDR）文件，违规罚款最高 3% 全球年营业额；相当比例中小 MedTech 尚未完成合规技术文件，预计将出现合规截止后的集中整改潮。
- **美国 AI 报销突破**：2026 CPT 代码集首次纳入 AI 辅助诊断 Category I 代码（含 RVU），从根本上改变"FDA 清关但无法收费"的商业化障碍，AI 医疗器械进入"可清关 + 可收费"双轮驱动新阶段。
- **ARPA-H ADVOCATE 联邦授权路径**：6 月甄选团队中，将成为美国首个系统化临床代理 AI 授权范本（3 年 FDA 授权路径），AMA 对无监督心血管 AI 的安全警告持续存在。
- **Palantir NHS 数据治理案例**：英国议会压力持续，2027 年 2 月退出条款成为全球公立医疗 AI 采购的反面教材，"可验证数据访问权限"将成标准合同条款。

### 值得持续跟踪的信号
- **NHS Copilot 部署实际节省数据**：50.5 万人规模从 7 月开始分波段上线，实际临床工时节省与预期（1 小时 40 分/天）的差距将成全球最大的医疗 AI 效益验证实验。
- **EU AI Act 8 月合规截止后执法态势**：首批不合规企业被执法案例将设定整个欧洲 MedTech AI 监管的实际执行强度。
- **Epic Agent Factory 规模扩张速度**：Advocate Health 试点后的第二、三批头部医疗系统上线节奏，将验证无代码代理 EHR 的可复制性。
- **rentosertib Phase III 入组速度与首批安全数据**：H2 2026 患者入组启动后，首批数据是 AI 药物发现赛道 2026 年最受关注的临床节点。
- **Relay Zovegalisib ReDiscover-2 Phase 3 中期分析**：AI 辅助设计的选择性 PI3Kα 抑制剂若 Phase 3 PFS 达终点，将成 AI 药物发现赛道迄今最强临床验证。
- **2026 CPT AI 代码实际报销落地情况**：新代码从生效到医保实际覆盖的执行差距，及 CMS 2027 年是否扩大 AI 诊断报销范围。
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
