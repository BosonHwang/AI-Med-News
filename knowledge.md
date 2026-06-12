# 医疗 AI 领域知识库

## 领域历史知识摘要

### 当前阶段判断
医疗 AI 在"临床 AI 操作系统化"深化的同时，叠加了"治理危机与监管碎片化"新张力：2/3 医疗从业者因机构 AI 滞后转而使用未授权"影子 AI"，折射部署速度与治理能力之间的系统性裂口；美国国会阻止 CMS WISeR 医疗 AI 预授权试点、科罗拉多州三法叠加 6 月底截止，标志监管反弹开始与 AI 商业化同步提速，行业进入"加速落地+治理补课"并行阶段。

### 主要趋势（5条）

1. **AI 医疗基础设施走向多年期深度生态绑定**：NHS England 向 50.5 万名医务人员部署 Microsoft 365 Copilot（试点节省 43 分钟/人/天，7 月起分波段上线）；Mayo Clinic + Microsoft 联合开发医疗专用基础模型；NVIDIA + Foxconn 启动 15 亿美元"健康台湾"计划；Philips 与 WellSpan Health 签署 7 年战略联盟，算力与服务绑定延伸至社区医疗层级。

2. **环境 AI 从听写工具进化为医疗操作系统**：Abridge 发布"以患者为中心的临床智能平台"，将就诊对话原生连接账单编码、实时理赔审核、循证决策和临床试验筛查（300+ 医疗系统、1 亿+ 对话/年）；NVIDIA 联合开发首个临床对话专用基础模型（Nemotron 架构）；礼来战略投资打通制药试验招募入口。

3. **AI 诊断与精准肿瘤 AI 平台加速规模化**：REDMOD/PANORAMA 证实 AI 胰腺癌 CT 检测全面超越人类专家（灵敏度 73% vs 39%，提前 475 天）；Tempus AI 获 FDA 批准 xT CDx 实体瘤测序、扩展 Next 平台至 6 种新癌症实时临床智能，并深化与 BMS 和 Gilead 合作；SOPHiA+MSK 拟建纽约精准肿瘤枢纽，通过 35 国网络将顶级癌症中心 AI 发现全球化。

4. **AI 药物发现进入多制剂验证与大规模算力部署并行阶段**：Isomorphic Labs 完成 21 亿美元 B 轮，首批肿瘤候选药 2026 年底入临床；rentosertib Phase III（H2 2026）启动；礼来 LillyPod（9,000+ petaflops）+ Abridge 合作形成从分子设计到患者招募的完整 AI 链路。

5. **影子 AI 治理危机倒逼机构 AI 加速，ROI 验证双面加压**：2/3 医疗从业者使用未授权私人 AI（HIPAA 合规风险），证明官方 AI 部署严重滞后于实际需求；另一面，Philips 调研确认 AI 每年节省 132+ 小时、27% 受访者称 AI 防止医疗差错，UnitedHealth $15 亿 AI 投入预期 $10 亿节省——治理危机与 ROI 验证同时加压，倒逼医疗机构加速 AI 正规化。

### 技术热点
- **临床对话专用基础模型**：NVIDIA + Abridge 联合开发，基于 Nemotron 开源架构，原生训练于真实医生-患者对话，区别于通用 LLM 适配路线。
- **精准肿瘤 AI 平台整合**：Tempus AI xT CDx FDA 清关 + Next 平台扩展至 6 种新癌症实时临床智能，AI 肿瘤诊断向多癌种批量规模化转型。
- **临床 AI 代理系统**：ARPA-H ADVOCATE 6 月内宣布获奖团队，将启动全球首个 FDA 授权心血管 24/7 护理 AI 代理开发（患者面代理 + 监督层代理双架构）。
- **中国医疗 AI 基础设施**：国家 AI 应用中试基地（医疗）+ 中国联通亿元高质量数据集专项（150TB+，10+ 专科），形成中国"数据-算力-模型-应用"国家队体系。
- **数字病理 AI 分子替代**：H&E 切片直接提取基因组级分子信息（Hetairos 脑肿瘤 100+ 亚型）；SOPHiA+MSK 枢纽将加速发现成果全球化。

### 商业格局
- **平台层**：Microsoft 三线并进（NHS Copilot + Dragon Copilot 平台化 + Mayo 定制基础模型）；NVIDIA 双向布局（Abridge 基础模型共建 + 台湾公共医疗）。
- **临床 AI 操作系统层**：Abridge（NVIDIA + 礼来双锚，300+ 医疗系统）；Tempus AI 向"精准肿瘤数据+AI 平台"整合，BMS+Gilead 深化合作夯实多组学数据护城河。
- **支付方层**：UnitedHealth $15 亿 AI 投入验证规模化 ROI；但国会对 AI 预授权的政治阻力（WISeR 被叫停）划定了支付方 AI 应用的政策边界。
- **中国国家队**：中国联通 + 国家 AI 中试基地（医疗）构建高质量数据资产；腾讯医疗 AI（吴文达）强调聚焦与克制策略。
- **AI 药物发现**：Isomorphic Labs（21 亿美元 B 轮）与 Insilico（rentosertib Phase III）领跑；礼来 LillyPod 超算 + Abridge 试验招募形成制药 AI 全链路范本。

### 监管走向
- **美国国会阻止 AI 驱动医疗预授权（新）**：众议院拨款委员会投票禁止为 CMS WISeR 模型拨款，AI 在传统医疗保险中的预授权应用遭政治阻击，监管边界由国会划定。
- **科罗拉多州三法叠加截止（2026-06-30）**：SB24-205（通用 AI 法）+ HB 26-1139（AI 健康保险审查）+ HB 26-1195（AI 心理治疗限制）同步推进，成为全美医疗 AI 合规最密集实验场；替代法案（延至 2027-01-01）能否通过仍悬而未决。
- **EU AI Act 医疗器械合规**：Article 4 AI 素养义务维持 2026-08-02 不变（70% 临床医生培训不足）；高风险 AI 截止延至 2028-08-02。
- **ARPA-H ADVOCATE 联邦授权路径**：6 月内选定获奖团队，构建首个联邦主导的临床代理 AI FDA 授权路径示范；与此同时，FDA 对低风险数字健康 AI 持续松绑。

### 值得持续跟踪的信号
- **Colorado AI Act 6 月 30 日截止**：替代法案能否在截止前通过，决定美国最复杂医疗 AI 合规场景的走向，各州立法节奏的重要参照。
- **ARPA-H ADVOCATE 获奖团队公告**：6 月内宣布，揭示联邦主导心血管 AI 代理开发者（大型科技 vs. 专业医疗 AI）及技术路线背书。
- **WISeR 国会阻击最终结局**：众议院修正案能否进入最终拨款法案，决定 AI 驱动医疗预授权在传统医疗保险中的短期命运。
- **NVIDIA-Abridge 临床对话基础模型年内发布**：首个原生训练于真实医患对话的专用模型，"专科化 vs. 通用适配"路线的关键数据点。
- **Abridge 实时理赔对齐（Real-Time Claims）采用率**："临床对话→支付方审核"直连，测试"临床 AI 操作系统"商业模式可行性的核心指标。
- **NHS Copilot 7 月正式上线效益数据**：50.5 万用户部署，与 43 分钟/天试点数据的真实验证，全球最大单一医疗 AI 效益实验。
- **EU AI Act Article 4 执行（2026-08-02）**：医疗 AI 合规实际执法力度揭示节点。
- **Isomorphic Labs 首批肿瘤候选药临床试验（2026 年底目标）**：AI 设计药物进入 Phase I 的最近期里程碑。
- **Tempus AI xT CDx + Next 平台精准肿瘤商业化进展**：FDA 获批后的大型癌症中心扩展速度，精准肿瘤 AI 商业化近期关键指标。
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
