# 李欣

> 中国上海 | 男 | 1997 年 9 月 17 日 | [justindelladam@live.com](mailto:justindelladam@live.com) | +86 180 1601 5760 | [GitHub](https://github.com/realJustinLee)

**高级软件工程师，拥有 6 年以上分布式系统、云平台、数据保护管控面与 AI 时代架构治理经验。擅长子系统架构设计、人类 + AI 混合决策治理、大规模性能重构，以及跨团队技术领导。**

# 核心能力

- 英语流利，雅思 **7.5** 分
- **AI 增强的架构决策治理**：设计并主持人类 + AI 混合的高风险架构评审机制，在明确人类决策归属的前提下，引入 `GPT`、`Gemini`、`Qwen`、`DeepSeek` 作为结构化质询者。
- AI 时代基础设施、管控面架构、分布式系统、云存储、数据保护、性能与可靠性工程
- 技术领导力：子系统 owner、跨团队设计评审、质量治理与 Tech Lead 培养
- 专利：**2 项美国专利**、**2 项中国专利**
    1. 美国专利 `US 2024/0111810 A1`：[Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111810)
    2. 美国专利 `US 2024/0111836 A1`：[Method, Electronic Device, and Computer Program for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111836)
    3. 中国专利 `202211217524.7`：数据处理方法、电子设备和计算机程序产品
    4. 中国专利 `202211215669.3`：数据读取方法、数据更新方法、电子设备和程序产品
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

## 华为 - 数据保护架构与设计

**高级工程师 A (17B) / Committer** | **2024 年 10 月 - 现在**

- 负责 `OceanProtect` 管控业务团队中保护引擎、系统管理和基础平台等团队间的子系统架构设计与技术路线规划。
- 协同三支团队推进跨模块架构决策、接口边界治理、质量门禁与疑难问题攻关，在高风险需求和现网问题中承担技术负责人角色。
- 为保护引擎、系统管理和基础平台相关议题的 `DEG` 评审设计并落地人类主导、AI Agent 辅助的架构决策机制。
- 作为人类决策负责人及联合主持人，引入 `GPT`、`Gemini`、`Qwen`、`DeepSeek` 等 AI Agent 作为结构化质询者，识别系统在可扩展性、安全性和长期可维护性上的潜在风险，并通过决策留痕与决策后验证机制，在实现前避免了多起高风险架构回退与设计缺陷。
- 在满并发场景下重构任务调度器，将任务从发起到执行的时延从 **35+ 分钟** 降至 **20 秒以内**，并将时间复杂度从 `O(n^2 * m)` 优化为 `O(n * m)`。
- 主导 **22+** 项性能优化与重构，覆盖备份、查询、导出和事件处理链路。代表性成果包括：10,000 台虚拟机扫描从 **2 小时** 缩短到 **10 分钟**，10,000 个副本归档队列的 `Redis` 内存占用从 **2 GB** 降至 **56 MB**，批量取消从 **1 分钟/任务** 降至 **0.5 秒/任务**，400 万条告警/事件转储从 **24 小时** 缩短到 **35 秒**。
- 设计并交付 `OceanProtect` 四眼审批 / `MPA` 模块，支撑产品满足 `GB/T 35273-2020`、`DORA`、`EBA` 等中国和欧盟合规要求。
- 在 **3 天** 内设计实现 `ProtectManager` 的 `Nutanix` 备份插件，产出 **3.3K+** 行代码，转测 **0 缺陷**。
- 主导 **75+** 起关键现网问题的定位与解决，覆盖 Petrobras、微众银行、中国移动、Emaar 等全球企业客户。
- 作为部门级 `Java` / `Python` Committer，累计向 `master` 分支提交 **54.5K+** 行代码，并推动三支团队的代码评审和缺陷预防，累计输出 **621+** 条检视意见，识别 **15** 个安全问题和 **5** 个数据库性能问题，并培养 **5** 名 Tech Lead。
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

- 担任 `OBS Metadata Layer 1` 与 `OSA Fortress` 团队 Scrum Lead，并担任 `ECS` / `OBS` DevOps Framework Release 虚拟团队的中方联络人，负责跨地域执行协同与版本节奏推进。
- 协同中国与海外团队推进 `ECS` 与 `ObjectScale` 分布式存储交付，聚焦元数据与数据链路性能、工程化能力，以及从 `VMware` 版 `ECS` 向 `Kubernetes` 版 `OBS` 的演进。
- 设计 `DT` 写入链路优化算法，使 `ECS` / `OBS` 的写入性能提升 **15%**。
- 参与 `DT Automation` 与 `Fortress-Diag` 等内部工程框架建设，为 `DT` 模块补充自动诊断与修复流程，并完成 `qTest` 与现有 `Jenkins` `CI` / `CD` 自动化工作流的集成。
- 设计新的存储数据结构，使存储占用下降 **5%**、对象序列化效率提升 **7%**。
- 支撑面向高盛、摩根士丹利、花旗、RBC 等全球金融机构使用的企业级对象存储平台。
- 专利
    1. 美国专利 `US 2024/0111810 A1`：[Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111810)
    2. 美国专利 `US 2024/0111836 A1`：[Method, Electronic Device, and Computer Program for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111836)
    3. 中国专利 `202211217524.7`：数据处理方法、电子设备和计算机程序产品
    4. 中国专利 `202211215669.3`：数据读取方法、数据更新方法、电子设备和程序产品
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
- 1 年内在 `amdgpu-pro` 与 `GIM` 相关栈上闭环解决 **160+** 个驱动与虚拟化问题单，在问题定位、修复实现和验证交付上体现出很强执行力。
- 设计 VM 渲染请求协调状态机，使虚拟化性能从 **60%** 提升至 **80%** 的裸机 FPS 水平。
- 将虚拟化自动测试系统通过率从 **75%** 提升至 **95%**，并多次进行 Linux 内核、算法和数据结构内部技术分享。

## NI (美国国家仪器) - R&D Shanghai

**Software Engineer** | **2019 年 3 月 - 2020 年 2 月**

- 识别重复验证与人工回归瓶颈，使用 `PyTest`、`scrapy` 和仪表板搭建自动化测试平台，并通过内部 RESTful API 集成到团队日常敏捷流程中。
- 参与 `OneRT` Linux feed 管理，使平均 bundle 体积下降 **5%**，体现了偏向实用主义的工程创新思维。
- 奖项
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

# 教育

## 上海大学 - 计算机工程与科学学院

**学士 计算机科学** | **2015 年 9 月 - 2019 年 7 月**

- 上海大学开源社区讲师
- 奖项
    1. _上海大学优秀毕业论文_
    2. _上海大学创新创业奖学金_
    3. _上海大学物联网创新创业竞赛一等奖_
    4. _上海大学第四届计算机应用能力大赛三等奖_
    5. _上海大学学生社区科创之星_

# 项目作品集

## `OceanProtect` 保护引擎、系统管理与基础平台

**华为 - 数据保护架构与设计**

- 项目角色：保护引擎、系统管理和基础平台的子系统架构负责人、跨团队技术负责人、AI 增强 `DEG` 联合主持人。
- `OceanProtect` 是华为面向下一代数据中心与多云的统一数据保护平台，覆盖备份、恢复、副本管理、网络韧性，以及一体机形态下的 `WORM`、防删除、`Air Gap` 等安全能力。
- 我负责保护引擎、系统管理和基础平台等团队间的技术路线、接口边界与方案决策。
- 我引入 AI 增强 `DEG` 治理，在明确人类决策归属的前提下，让 `GPT`、`Gemini`、`Qwen`、`DeepSeek` 参与结构化质询。
- 我还主导了调度器重构、副本归档队列 `Redis` 内存优化、告警 / 事件链路重构，以及 `MPA` 合规能力和 `Nutanix` 备份插件交付。

## `ECS` / `ObjectScale` 分布式对象存储平台

**Dell Technologies - Dell EMC**

- 项目角色：Scrum Lead、跨地域技术协调者，以及元数据、写入链路与 `DT` 自动化 / 诊断方向负责人。
- `ECS` 是 Dell 的企业级对象存储平台，提供 S3 接口、全局分布式架构与统一命名空间；`ObjectScale` 在此基础上演进为基于 `Kubernetes` 的 AI-ready 架构，并延续 `ECS` 的核心工作流与 API。
- 我负责跨地域元数据与写入链路交付、`DT` 写入优化、存储数据结构设计、`DT Automation` / `Fortress-Diag`，以及从 `VMware` 版 `ECS` 到 `Kubernetes` 版 `OBS` / `ObjectScale` 的演进。

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
- AMD GPU 虚拟化技术栈基于 `MxGPU` / `SR-IOV`，支持 `QEMU` / `KVM` 虚拟机共享加速资源，`amdgpu-pro` 与 `GIM` 贴近内核驱动、分区、调度和验证链路。
- 我负责 Linux 驱动与虚拟化特性开发、高数量问题单闭环、VM 渲染请求状态机，以及自动化验证覆盖和通过率改进。

## 自动化验证平台与 `OneRT` Feed 工程

**NI (美国国家仪器) - R&D Shanghai**

- 项目角色：项目负责人、后端设计者、主要开发者。
- 项目思路与 NI 以 `TestStand`、`SystemLink`、看板、可追溯性、API 和分布式测试系统部署为核心的自动化测试体系一致。
- 我搭建了包含自动执行、数据采集、看板、内部 RESTful API 与 `OneRT` feed / package 管理的轻量验证平台，降低人工回归与运维成本。

## NI Shanghai 资产管理系统

**NI (美国国家仪器) - R&D Shanghai** | **2019 Tech Week**

- 项目角色：项目负责人、后端架构设计者、主要开发者。
- 基于 `Flask` 与 `Docker` 开发后端，通过 RESTful API 接入公司微信小程序，将资产损失成本降低 **10%**。
- 认可
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

## LiCMS - 开源内容管理系统

**GitHub：** [https://github.com/realJustinLee/LiCMS](https://github.com/realJustinLee/LiCMS) | **在线预览：** [https://www.1a2.org](https://www.1a2.org)

- 项目角色：项目发起人、系统架构设计者、独立开发者。
- 从 0 到 1 设计、开发并持续演进开源 `LiCMS`，从首个 commit 到可部署产品全程主导，基于 **321 次 commit** 将其从脚手架逐步打磨为完整内容平台。
- 设计基于 `Flask` App Factory + Blueprint 的模块化架构，拆分 `main`、`auth`、`api`、`dev_ops` 四类边界，结合 `SQLAlchemy` 模型、数据库迁移和 `development` / `testing` / `docker` / `heroku` / `unix` 多环境配置，支撑长期演进。
- 逐步实现完整产品能力，包括基于角色的权限控制、邮箱确认注册、Markdown 帖子、评论、关注关系与时间线、Paste 分享、基于 `JWT` 的 API 认证、基于 `TOTP` 的 2FA，以及建立在签名 token 之上的邮箱 / 密码 / 2FA 自助恢复链路。
- 自建工程与运维闭环，提供 Flask CLI 的 `test` / `profile` / `deploy` 命令、单元测试 / API 测试 / Selenium 测试与覆盖率报告，并通过 `Docker Compose` + `MariaDB` + `Nginx` + `Certbot` + `gunicorn` 形成可直接部署的生产栈。
- 持续推进安全和技术演进，包括依赖治理、将签名 token 流程从 `itsdangerous` 迁移到 `JWT`、`SQLAlchemy` 现代化、`Bootstrap 5` 升级，以及 HTTPS、反向代理和错误邮件告警等运行能力建设。

## LiAg - 开源 3D 角色生成器

**GitHub：** [https://github.com/realJustinLee/LiAg](https://github.com/realJustinLee/LiAg) | **在线预览：** [https://liag.1a2.org](https://liag.1a2.org)

- 项目角色：项目发起人、前端 / 图形架构设计者、独立开发者。
- 从 0 到 1 设计并开发开源浏览器端 3D 角色生成系统，完整负责界面交互、渲染链路、资源组织和可打印模型导出体验。
- 设计 `React.js` + `Three.js` / `WebGL` 的前端架构，以可复用的场景控制器、模块化部件库、挂接元数据和姿态定义为核心，支持角色按部件自由装配。
- 在浏览器中实现部件选择、姿态编辑和实时渲染，并扩展 `STL` 导出链路，将蒙皮网格碎片融合为单个可打印模型，同时将导出 `STL` 文件体积缩小 **30%**。
- 将运行时与资源管线建立在 `GLTF` 模型和 JSON 姿态 / 部件库之上，使新部件、新姿态和新打印变体可以持续扩展。
