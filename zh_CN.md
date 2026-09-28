# 李欣

> 中国上海 | 男 | 1997 年 9 月 17 日 | [justindelladam@live.com](mailto:justindelladam@live.com) | +86 180 1601 5760 | [GitHub](https://github.com/realJustinLee)

**系统架构师，拥有 7 年以上软件工程经验，职业经历涵盖 GPU 虚拟化、分布式存储、云平台、数据保护及法律垂类 AI。擅长系统架构设计、大规模性能优化、AI 辅助架构治理与 LLM 应用，兼具底层系统开发、企业级产品交付和跨团队技术领导经验。**

# 核心能力

- 英语流利，雅思 **7.5** 分
- **AI 增强的架构决策治理**：设计并主持人类 + AI 混合的高风险架构评审机制，在明确人类决策归属的前提下，引入 `GPT`、`Gemini`、`Qwen`、`DeepSeek` 作为结构化质询者。
- **法律垂类 AI**：具备法律知识检索、问答与起草的 `RAG` 方案设计及交付经验，探索 `LLM Wiki` 法律知识组织方式，并结合引用验证与领域专家评估提升输出质量。
- AI 时代基础设施、管控面架构、分布式系统、云存储、数据保护、性能与可靠性工程
- 技术领导力：系统架构统筹、跨团队设计评审、质量治理与 Tech Lead 培养
- 专利：**2 项美国专利**、**2 项中国专利**
    1. 美国专利 `US 12,072,937 B2`：[Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12072937)
    2. 美国专利 `US 12,566,824 B2`：[Method, Electronic Device, and Computer Program Product for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12566824)
    3. 中国专利 `202211215669.3`：数据读取方法、数据更新方法、电子设备和程序产品
    4. 中国专利 `202211217524.7`：数据处理方法、电子设备和计算机程序产品
- 能力证书
    1. 华为软件开发能力认证专业级（`Java`）
    2. 华为软件开发能力认证专业级（`Python`）
    3. [Registered Product Owner™](https://s3.amazonaws.com/scruminc-certs/RPO-6903098)
    4. [Registered Scrum Master™](https://s3.amazonaws.com/scruminc-certs/RSM-2901977)
- 中国计算机学会（CCF）专业会员
- Stack Overflow 声望值：890
- GitHub Arctic Code Vault Contributor、GitHub Sponsor、GitHub Developer Program Member
- 编程语言：`Java`、`Python`、`C/C++`、`JavaScript`、`SQL`
- 平台与技术：`Kubernetes`、`Docker`、`Linux`、`KVM`、`SR-IOV`、`Spring`、`Flask`、`React.js`、`Three.js`、`WebGL`

# 工作经历

## LexisNexis - LexisNexis Legal & Professional

**Machine Learning Engineering Lead** | **2026 年 6 月 - 至今**

### 香港 BU | Lead Data Scientist (Acting)

- 作为香港数据科学交付的第一负责人，主导需求梳理、路线图规划、技术决策与质量管理，协调内容、工程及领域专家（SME）之间的协作与交付依赖；推动团队在 `Cowork`、量刑内容与繁体中文能力上提前完成关键交付目标，获得 SME 与客户的积极反馈。
- 针对 `Cowork` 文档经 Markdown 往返转换后的格式失真，提出并主导原生 `DOCX` 结构编辑方案：由 LLM 理解内容并定位修改位置，对文档 XML 进行局部插入或更新，尽可能保留原有结构与样式；组织团队完成服务适配、Word 文档输出与端到端验证，提升模板还原度、格式一致性与文档可用性。
- 主导繁体中文 `Upload` / `Vault` 本地化，覆盖文档结构解析、条款编号、提示词与检索评估。在 **24 个控制用例、137 个必要事实点**的受控实验中，`RAG` 基线加权事实召回率为 **28.5%**，`MapReduce` 两轮评估分别达到 **99.3%** 和 **100%**；据此制定“优化 `RAG` 主路径 + 受预算约束的 `MapReduce` 补充”方案，并交付语言控制、原文保留与结构化时间线能力。
- 主导香港最新版量刑内容接入与场景验证，在既有 `RAG` 基础上探索基于 `LLM Wiki` 的法律知识组织方式；统筹问答验证、起草影响分析、版本隔离与引用检查，完成香港法律场景的内容与问答能力交付。
- 运用 AI 辅助编程独立开发并交付香港内部 SME 评分调度平台，集中管理原先分散于 Excel 的评估排期，并提供共享日程、评分进度跟踪与结果分析，提升评估协作效率，加快数据科学功能交付。
- 统筹 `ICS UK` 英国法律内容集成、研究链路验证与评估准备，首轮评估即通过，无需调整或重新评分。
- 组织团队完善引用验证与案例名称过滤，推动 `Vault` 邮件 / 信函起草通过 SME 复核并进入受控上线；统筹新模型启用，并完成起草与 Web 搜索的质量和延迟评估。

### 新西兰 BU | Machine Learning Engineering Lead

- 负责新西兰机器学习工程方向的路线图规划、技术决策与工程交付，推动法律研究与起草能力产品化。推动文档子集选择、来源链接及多文档支持能力完成商业发布，支持文档数量由 **1 份扩至 10 份**；完成文档管理系统（`DMS`）全文起草与起草来源链接增强的技术发布。
- 统筹 `Agentic` 法律工作流交付，覆盖 `Planner`、`Cowork` MVP、多提示词执行及 `LexisNexis` / Web 内容集成，并面向客户开放；协同应用团队完善回答重试与 `Canvas` 修订导出。
- 组织团队完成 `Vault` 扩容，将字符上限扩至 **400 万**、单文件上限由 **20 MB 提升至 100 MB**；交付 `General AI` 本地托管、轻量 `DMS` 连接及 `Protégé 2.0` 起草的 `DMS` 深度集成，并面向客户开放。

## 华为 - 数据保护架构与设计

**高级工程师 A (17B) / Committer** | **2024 年 10 月 - 2026 年 3 月**

- 担任 `OceanProtect` 管控业务团队中保护引擎、系统管理和基础平台相关领域的子系统架构师，负责子系统架构设计与技术路线规划。
- 协同三支团队推进跨模块架构决策、接口边界治理、质量门禁与疑难问题攻关，在高风险需求和现网问题中承担技术负责人角色。
- 为保护引擎、系统管理和基础平台相关议题的 `DEG` 评审设计并落地人类主导、AI Agent 辅助的架构决策机制。
- 作为人类决策负责人及联合主持人，引入 `GPT`、`Gemini`、`Qwen`、`DeepSeek` 等 AI Agent 作为结构化质询者，识别可扩展性、安全性和长期可维护性风险；通过决策留痕与后续验证，在实现前发现并规避多项可能导致架构回退的高风险设计缺陷。
- 在满并发场景下重构任务调度器，将任务从发起到执行的时延从 **35+ 分钟** 降至 **20 秒以内**，并将时间复杂度从 `O(n^2 * m)` 优化为 `O(n * m)`。
- 主导 **22+** 项性能优化与重构，覆盖备份、查询、导出和事件处理链路。代表性成果包括：10,000 台虚拟机扫描从 **2 小时** 缩短到 **10 分钟**，10,000 个副本归档队列的 `Redis` 内存占用从 **2 GB** 降至 **56 MB**，批量取消从 **1 分钟/任务** 降至 **0.5 秒/任务**，400 万条告警/事件转储从 **24 小时** 缩短到 **35 秒**。
- 设计并交付 `OceanProtect` `四眼认证` / `MPA` 模块，支撑产品满足 `GB/T 35273-2020`、`DORA` 及 `EBA` ICT 安全指南中的相关要求。
- 在 **3 天** 内设计实现 `ProtectManager` 的 `Nutanix` 备份插件，产出 **3.3K+** 行代码，转测 **0 缺陷**。
- 主导 **75+** 起关键现网问题的定位与解决，覆盖 Petrobras、微众银行、中国移动、Emaar 等全球企业客户。
- 作为部门级 `Java` / `Python` Committer，累计向 `master` 分支合入 **54.5K+** 行代码；推动三支团队的代码评审与缺陷预防，累计输出 **621+** 条检视意见，识别 **15** 个安全问题和 **5** 个数据库性能问题，并培养 **5** 名 Tech Lead。
- 证书
    1. 华为软件开发能力认证 —— 专业级证书（Java）
    2. 华为软件开发能力认证 —— 专业级证书（Python）
- 奖项
    1. _2025 数据管理产品部质量标杆_
    2. _2025 数据保护开发部 6 月月度最佳 Committer_
    3. _2025 架设 DP 优秀学员/优胜小组_
    4. _2025 DEDP 优秀学员/优胜小组_
    5. _2024 NEO 优秀学员/优胜小组/最强班委_

## Dell Technologies - Dell EMC

**Software Engineer 2 (IC-6)** | **2021 年 8 月 - 2024 年 10 月**

- 担任 `OBS Metadata Layer 1` 与 `OSA Fortress` 团队的 Scrum Lead，并担任 `ECS` / `OBS` DevOps Framework Release 虚拟团队的中方联络人，负责跨地域协作与版本发布协调。
- 协同中国与海外团队推进 `ECS` 与 `ObjectScale` 分布式存储交付，聚焦元数据与数据链路性能、工程化能力，以及从 `VMware` 版 `ECS` 向 `Kubernetes` 版 `OBS` 的演进。
- 设计 `DT` 写入链路优化算法，使 `ECS` / `OBS` 的写入性能提升 **15%**。
- 参与 `DT Automation` 与 `Fortress-Diag` 等内部工程框架建设，为 `DT` 模块补充自动诊断与修复流程，并完成 `qTest` 与现有 `Jenkins` `CI` / `CD` 自动化工作流的集成。
- 设计新的存储数据结构，使存储占用下降 **5%**、对象序列化效率提升 **7%**。
- 为高盛、摩根士丹利、花旗、RBC 等全球金融机构使用的企业级对象存储平台提供工程支持。
- 专利
    1. 美国专利 `US 12,072,937 B2`：[Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12072937)
    2. 美国专利 `US 12,566,824 B2`：[Method, Electronic Device, and Computer Program Product for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12566824)
    3. 中国专利 `202211215669.3`：数据读取方法、数据更新方法、电子设备和程序产品
    4. 中国专利 `202211217524.7`：数据处理方法、电子设备和计算机程序产品
- 证书
    1. `RPO-6903098`: [Registered Product Owner™](https://s3.amazonaws.com/scruminc-certs/RPO-6903098)
    2. `RSM-2901977`: [Registered Scrum Master™](https://s3.amazonaws.com/scruminc-certs/RSM-2901977)
- 奖项
    1. _2023 Team of The Year: Innovation_
    2. _Achievement: OBS Metadata Layer 1 First 2 Features Completed_
    3. _Giving & Impact: Making a positive impact in the year 2023_
    4. _Innovation: Nice work on the 2023 Hackathon Project_
    5. _Achievement: Awesome work for DT automation_
    6. _Winning Together: Epoch Release Branching and Pipeline Monitoring_
    7. _2021 Team of The Year_

## AMD - Virtualization SRDC

**Software Development Engineer 1** | **2020 年 3 月 - 2021 年 7 月**

- 参与 `amdgpu-pro` / `GIM` 技术栈上的 Linux GPU 虚拟化与内核驱动功能开发，技术栈涵盖 `SR-IOV`、`KVM`、`QEMU`。
- 1 年内解决 **160+** 个 `amdgpu-pro` / `GIM` 驱动与虚拟化问题单，覆盖问题定位、修复和验证全流程。
- 设计 VM 渲染请求协调状态机，将虚拟化环境下的 FPS 从裸机水平的 **60%** 提升至 **80%**。
- 将虚拟化自动化测试系统通过率从 **75%** 提升至 **95%**，并多次开展 Linux 内核、算法和数据结构的内部技术分享。

## NI (美国国家仪器) - R&D Shanghai

**Software Engineer** | **2019 年 3 月 - 2020 年 2 月**

- 识别重复验证与人工回归瓶颈，使用 `pytest`、`Scrapy` 和仪表板搭建自动化测试平台，并通过内部 `RESTful API` 集成到团队日常敏捷流程中。
- 参与优化 `OneRT` Linux 软件源（feed）管理，使平均软件包（bundle）体积下降 **5%**。
- 奖项
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

# 教育

## 上海大学 - 计算机工程与科学学院

**工学学士 计算机科学与技术** | **2015 年 9 月 - 2019 年 7 月**

- 上海大学开源社区讲师
- 奖项
    1. _上海大学优秀毕业论文_
    2. _上海大学创新创业奖学金_
    3. _上海大学物联网创新创业竞赛一等奖_
    4. _上海大学第四届计算机应用能力大赛三等奖_
    5. _上海大学学生社区科创之星_

# 项目作品集

## `Protégé` 法律 AI Agent 平台

**LexisNexis - LexisNexis Legal & Professional**

- 项目角色：Machine Learning Engineering Lead，兼任香港 BU Lead Data Scientist (Acting)，负责香港与新西兰相关能力的技术方案与交付。
- 主导香港法律知识接入与繁体中文能力建设，推进 `RAG` 优化、`LLM Wiki` 探索、引用验证及质量评估。
- 提出并主导 `Cowork` 原生 `DOCX` 编辑方案，提升文档格式保真度与输出可用性。
- 统筹新西兰 `Planner`、多提示词执行、`DMS` 集成与 `Vault` 扩容，推动法律 AI Agent 工作流面向客户交付。

## `OceanProtect` 保护引擎、系统管理与基础平台

**华为 - 数据保护架构与设计**

- 项目角色：保护引擎、系统管理和基础平台的子系统架构师、跨团队技术负责人、AI 增强 `DEG` 联合主持人。
- `OceanProtect` 是华为面向下一代数据中心与多云的统一数据保护平台，覆盖备份、恢复、副本管理、网络韧性，以及一体机形态下的 `WORM`、防删除、`Air Gap` 等安全能力。
- 负责保护引擎、系统管理和基础平台等团队间的技术路线、接口边界与方案决策。
- 引入 AI 增强 `DEG` 治理，在明确人类决策归属的前提下，让 `GPT`、`Gemini`、`Qwen`、`DeepSeek` 参与结构化质询。
- 主导调度器重构、副本归档队列 `Redis` 内存优化、告警 / 事件链路重构，以及 `MPA` 合规能力和 `Nutanix` 备份插件交付。

## `ECS` / `ObjectScale` 分布式对象存储平台

**Dell Technologies - Dell EMC**

- 项目角色：Scrum Lead、跨地域技术协调者，以及元数据、写入链路与 `DT` 自动化 / 诊断方向负责人。
- `ECS` 是 Dell 的企业级对象存储平台，提供 S3 接口、全局分布式架构与统一命名空间；`ObjectScale` 在此基础上演进为基于 `Kubernetes` 的 AI-ready 架构，并延续 `ECS` 的核心工作流与 API。
- 负责跨地域元数据与写入链路交付、`DT` 写入优化、存储数据结构设计、`DT Automation` / `Fortress-Diag`，以及从 `VMware` 版 `ECS` 到 `Kubernetes` 版 `OBS` / `ObjectScale` 的演进。

## 通过混合递归云委托进行分布式对象存储管理

**Dell Technologies - Dell EMC** | **2023 Hackathon Project**

- 项目角色：项目负责人、方案架构师、主要开发者。
- 设计自递归、成本可控的对象存储架构，通过统一接口接入多种存储后端。
- 同时支持云盘融合这类单例部署，以及既可持有本地数据又可委托其他云的自递归集群。
- 认可
    1. _Innovation: Nice work on the 2023 Hackathon Project_

## AMD GPU 虚拟化技术栈

**AMD - Virtualization SRDC**

- 项目角色：`amdgpu-pro` / `GIM` 虚拟化交付与验证改进的核心开发者与执行负责人。
- AMD GPU 虚拟化技术栈基于 `MxGPU` / `SR-IOV`，支持 `QEMU` / `KVM` 虚拟机共享加速资源，`amdgpu-pro` 与 `GIM` 涉及内核驱动、资源分区、调度和验证链路。
- 负责 Linux 驱动与虚拟化特性开发、问题定位与修复、VM 渲染请求状态机设计，以及自动化验证覆盖与通过率改进。

## 自动化验证平台与 `OneRT` Feed 工程

**NI (美国国家仪器) - R&D Shanghai**

- 项目角色：后端设计者、主要开发者。
- 项目思路与 NI 以 `TestStand`、`SystemLink`、看板、可追溯性、API 和分布式测试系统部署为核心的自动化测试体系一致。
- 搭建轻量验证平台，集成自动执行、数据采集、看板、内部 `RESTful API` 及 `OneRT` 软件源与软件包管理，降低人工回归与运维成本。

## NI Shanghai 资产管理系统

**NI (美国国家仪器) - R&D Shanghai** | **2019 Tech Week**

- 项目角色：项目负责人、后端架构设计者、主要开发者。
- 基于 `Flask` 与 `Docker` 开发后端，通过 `RESTful API` 接入公司微信小程序，将资产损失成本降低 **10%**。
- 认可
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

## `LiCMS` - 开源内容管理系统

**GitHub：** [https://github.com/realJustinLee/LiCMS](https://github.com/realJustinLee/LiCMS) | **在线预览：** [https://www.1a2.org](https://www.1a2.org)

- 项目角色：项目发起人、系统架构设计者、独立开发者。
- 从 0 到 1 设计、开发并持续维护开源 `LiCMS`，通过 **321 次 commit** 将其从初始框架完善为可部署的内容管理平台。
- 设计基于 `Flask` `App Factory` + `Blueprint` 的模块化架构，拆分 `main`、`auth`、`api`、`dev_ops` 四类边界，结合 `SQLAlchemy` 模型、数据库迁移和 `development` / `testing` / `docker` / `heroku` / `unix` 多环境配置，支撑长期演进。
- 实现基于角色的权限控制、邮箱验证注册、Markdown 帖子、评论、关注关系与时间线、Paste 分享、基于 `JWT` 的 API 认证及基于 `TOTP` 的 2FA，并通过签名 token 支持邮箱、密码和 2FA 的自助恢复。
- 建设开发、测试与运维工具链，提供 `Flask CLI` 的 `test` / `profile` / `deploy` 命令、单元测试 / API 测试 / `Selenium` 测试及覆盖率报告，并通过 `Docker Compose` + `MariaDB` + `Nginx` + `Certbot` + `gunicorn` 构建可直接部署的生产环境。
- 持续推进安全和技术演进，包括依赖治理、将签名 token 流程从 `itsdangerous` 迁移到 `JWT`、`SQLAlchemy` 现代化、`Bootstrap 5` 升级，以及 `HTTPS`、反向代理和错误邮件告警等运行能力建设。

## `LiAg` - 开源 3D 角色生成器

**GitHub：** [https://github.com/realJustinLee/LiAg](https://github.com/realJustinLee/LiAg) | **在线预览：** [https://liag.1a2.org](https://liag.1a2.org)

- 项目角色：项目发起人、前端 / 图形架构设计者、独立开发者。
- 从 0 到 1 设计并开发开源浏览器端 3D 角色生成系统，完整负责界面交互、渲染链路、资源组织和可打印模型导出体验。
- 设计 `React.js` + `Three.js` / `WebGL` 的前端架构，以可复用的场景控制器、模块化部件库、挂接元数据和姿态定义为核心，支持角色按部件自由装配。
- 在浏览器中实现部件选择、姿态编辑和实时渲染，并扩展 `STL` 导出链路，将蒙皮网格片段合并为单个可打印模型，同时将导出 `STL` 文件体积缩小 **30%**。
- 基于 `glTF` 模型和 JSON 姿态 / 部件库组织运行时与资源管线，便于持续扩展部件、姿态及可打印模型。
