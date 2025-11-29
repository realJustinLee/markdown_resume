# 李欣

> 高级工程师 A `17B` | 华为 | justindelladam@live.com | +86 180 1601 5760 | 中国上海

- 英语流利，雅思`7.5`分。
- 中国计算机学会专业会员。
- 精通`Java`、`Java`高并发、`JVM`优化、算法、数据结构和分布式存储。
- 熟练掌握`Docker`、`Kubernetes`、`KVM`和`SR-IOV`。
- 亦熟练掌握`Python`、`Javascript`、`React.js`、`C/C++`、`Jenkins`、`qTest`、等等。
- StackOverflow reputation: `890`.
- GitHub Arctic Code Vault Contributor, Sponsor.
- GitHub Developer Program Member.
- 重度使用`macOS`、`Linux`、`homebrew`和`shell`脚本。
- 深爱开源运动，追求卓越。
- 熟练使用苹果 iWork 和微软 Office 套件，精通 Keynote 和 PowerPoint。
- 乐于在团队中担任润滑剂的角色，也追求在代码和创新上的贡献。

# 技能

- 团队管理：[Registered Product Owner™](https://s3.amazonaws.com/scruminc-certs/RPO-6903098)、[Registered Scrum Master™](https://s3.amazonaws.com/scruminc-certs/RSM-2901977)。
- 编程语言：`Java`、`Python`、`C/C++`、`JavaScript`、`SQL`。
- 技术：`Java`、`Java`高并发、`JVM`优化、算法、数据结构、分布式存储、`Spring`、`Flask`、`React.js`、`Unix`/`Linux`、`Docker`、`PyTorch`、`WebGL`。
- GitHub: [https://github.com/realJustinLee](https://github.com/realJustinLee)

# 工作经验

## 华为 - 数据保护架构与设计

**高级工程师 A (17B) / Committer** | **2024 年 10 月 - 现在**

- 担任`管控业务团队`的子系统架构师、特性 SE、DEG Leader，`保护引擎组`的 DE、FO，`系统管理组`的 DE，`基础平台组`的 DE：端到端看护核心需求分析、方案设计、疑难问题攻关和质量控制
  1. 编码绝对贡献
      - 上`master`库代码总量：52.2K+ 行。
      - 输出检视意见：561+ 个`issue`。
  2. 修改、处理疑难、性能问题单 135+ 个。
  3. 提升任务调度性能 10,400%：在满并发规格下，任务从发起调度到代理执行任务从最高 35+ 分钟缩短至 20 秒以内，时间复杂度从`O(n^2 * m)`优化至`O(n * m)`。
  4. 设计并开发`ProtectManager`的`Nutanix`备份插件，3 天输出 3.3K+ 行 代码，转测 0 缺陷。
  5. 设计并开发`OceanProtect`四眼认证/MPA（多人审批授权）模块，助力`OceanProtect`产品通过欧洲和中国多款法规和认证
      - 中华人民共和国国家标准 `GB/T 35273-2020`：[信息安全技术 个人信息安全规范](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=4568F276E0F8346EB0FBA097AA0CE05E)
      - 中国网络安全审查技术与认证中心`CCRC`：信息安全服务资质认证
      - 欧盟`DORA`法规: [Digital Operational Resilience Act](https://www.applytosupply.digitalmarketplace.service.gov.uk/g-cloud/services/293002179752718)
      - 欧盟`EBA`规范: [EBA ICT 与安全风险管理指南](https://www.eba.europa.eu/sites/default/files/document_library/Publications/Guidelines/2020/GLs%20on%20ICT%20and%20security%20risk%20management/872936/Final%20draft%20Guidelines%20on%20ICT%20and%20security%20risk%20management.pdf)
  6. 牵头 75+ 关键局点线现网问题的定位与解决：涵盖巴西石油、中国太平洋保险、微众银行、中国移动、中国证券登记结算、华夏银行、瑞士 Litasco、阿尔及利亚 AN1 和阿联酋 Emmar 等关键战略 NA 客户，拦截一级 ITR 1 个、二级 ITR 3 个、三级 ITR 4 个、预 ITR 若干。
  7. 例行输出 FST 分析报告、`管控业务团队`质量周报，看护组内软件质量，修改引入和回归不通过数量比往期呈明显下降趋势。
  8. 领导运作`管控业务团队` DEG，推动组内业务流程的规范化运行
      - 看护 `OceanProtect` 产品告警码、事件码、错误码和 `RESTful` API 的评审。
      - 制定日志打印规范、`UT` / `LLT` 规范、代码检视规范、`RESTful` API 设计规范、告警/事件/错误码评审规范，并推动落地执行。
  9. 参与和轮值主持`数据保护开发部`的 CCB、NodePC、SEG、ST 会议运作，有效看护软件质量。
  10. 完成 90+ `BUGLSIT` 的回溯、分析和整理，输出整改方案并推动落地，并举一反三，有效提升了组内业务质量。
  11. 提出 9+ 项架构整改建议，主导 22+ 项性能优化
      - 重构 `ProtectManager` 的 `VMware` 备份插件扫描逻辑，提升性能 1,100%：实现 10,000 台虚拟机集群扫描时间从 2 小时缩短至 10 分钟。
      - 优化副本归档任务 `Redis` 内存使用效率 3,557%：使 10,000 个副本的归档任务队列内存占用从 2 GB 内存降低至 56 MB.
      - 优化批量取消任务性能 11,900%：处理速度从峰值 1 分钟/个提升至 0.5 秒/个且支持 10 并发。
      - 优化批量下发副本删除任务性能 1,900%：执行效率从峰值 1 分钟/个提升至 3 秒/个且支持 10 并发。
      - 优化副本 summary 查询性能 37,400%： 百万级副本查询从直接 OOM 改进为 5 秒内返回，20 万副本查询从 5 分钟优化至 0.8 秒内返回。
      - 改进日志导出性能 19,900%：大负载场景下日志导出页面响应从 3 分钟优化至 0.9 秒内。
      - 优化 `protectmanager-system-base` 和 `protectmanager-biz-service` POD 升级重启速度 1,000%：POD 升级过程从 12 分钟优化至 90 秒。
      - 重构虚拟机组备份任务下发流程，提升下发速度 13,400%：使满规格虚拟机组备份任务下发时间从 1.5 小时缩短至 40 秒。
      - 优化虚拟机组备份任务进度上报机制，通过数据库操作优化及锁和事务粒度细化，解决虚拟机组备份上报过程中锁超时导致的任务状态一小时不更新而自动失败的问题。
      - 重构告警和事件转储机制，优化性能 246,757%：使 400 万条告警/事件转储事件从 24 小时缩短到 35 秒。
      - 设计重构备份代理心跳上报逻辑，提升单个 Agent 管理个数 1,000%.
- 担任`数据保护 PDT` RAT 备份软件管控面需求分析专家、`管控业务团队`特性 SE
  1. 看护`管控业务团队`项目方案设计，即时完成 RAT 100 + 待分析/决策需求的分析与决策。
  2. 看护`管控业务团队`项目方案实现，即时完成 RAT 35 + 待实现需求的实现与处理。
- 担任`数据保护开发部` - `保护引擎组`、`系统管理组`、`基础平台组` - `Java`/`Python` Committer，强效看护组内代码质量、推动代码检视氛围建设
  1. 在团队 DEG 内依据检视过程中发现的问题，推动同类安全问题排查整改，协同模块内各 PL 推动排查整改落地闭环。
  2. 通过 DEG 内明确检视密度作为质量周报的重要指标，晨会检视十分钟分享重点检视意见和质量问题排查修改经验，极大提升了模块内的检视氛围
      - `保护引擎组`：月人均检视意见数量提升 2,277%：从 1.8 个提升至 41 个。
      - `系统管理组`：月人均检视意见数量提升 400%：从 11 个提升至 44 个。
      - `基础平台组`：月人均检视意见数量提升 500%：从 7 个提升至 35 个。
  3. 获得 2025 年 6 月质量守护奖：当月提出检视意见 153 个，位列开发部 TOP 1，其中包含性能和业务类问题共计 58 个，识别出接口鉴权不完整、Key 硬编码等 15 个安全问题，5 个数据库性能问题，有效提升上库代码质量。
- 建设人才梯队，培养 5 名 MDE
  1. `保护引擎组` 2 名
  2. `系统管理组` 2 名
  3. `基础平台组` 1 名
- 证书
  1. 华为团建开发能力认证 —— 专业级证书（Java）
- 奖项
  1. _2025 `数据管理产品部` 质量标杆_
  2. _2025 `数据保护开发部` 6 月月度最佳 Committer_
  3. _2025 架设 DP 优秀学员/优胜小组_
  4. _2025 DEDP 优秀学员/优胜小组_
  5. _2024 NEO 优秀学员/优胜小组/最强班委_

## Dell Technologies - Dell EMC

**Software Engineer 2 (IC-6)** | **2021 年 8 月 - 2024 年 10 月**

- 担任`OBS Metadata Layer 1`团队的 Scrum Lead。
- 担任`OSA Fortress`团队的 Scrum Lead。
- 担任`ECS/OBS DevOps Framework Release`虚拟团队的中方联络人。
- 发布 2 项美国专利和 2 项中国专利。
- 开发了一个加快`ECS`/`OBS` `DT`写入性能 15% 的 dumping 算法。
- 开发了一个节省了 5% 存储空间并加快了 7% 对象序列化效率的数据结构。
- 为弹性云存储系统`ECS`和对象存储`OBS`提供高效的`Java`代码。
- 为全球各大金融机构（例如高盛、摩根士丹利、花旗银行、加拿大皇家银行等）提供`ECS`和`OBS`开发支持
- 致力于`JVM`优化、分布式云存储和高并发`Java`开发。
- 参与基于`VMware`的`ECS`到基于`Kubernetes`的`OBS`的迁移开发。
- 参与开发了`DT`模块的自动诊断和修复框架`DT Automation`。
- 参与了`qTest`和现有测试自动化框架的集成。
- 专利
  1. 美国专利`US 2024/0111810 A1`: [Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111810)
  1. 美国专利`US 2024/0111836 A1`: [Method, Electronic Device, and Computer Program for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111836)
  1. 中国专利`202211217524.7`：数据处理方法、电子设备和计算机程序产品
  1. 中国专利`202211215669.3`：数据读取方法、数据更新方法、电子设备和程序产品
- 证书
  1. `RPO-6903098`: [Registered Product Owner™](https://s3.amazonaws.com/scruminc-certs/RPO-6903098)
  1. `RSM-2901977`: [Registered Scrum Master™](https://s3.amazonaws.com/scruminc-certs/RSM-2901977)
- 奖项
  1. _2023 Team of The Year: Innovation_
  1. _Achievement: OBS Metadata Layer 1 First 2 Features Completed_
  1. _Giving & Impact: Making a positive impact in the year 2023_
  1. _Innovation: Nice work on the 2023 Hackathon Project_
  1. _Achievement: Awesome work for DT automation_
  1. _Winning Together: Epoch Release Branching and Pipeline Monitoring_
  1. _2021 Team of The Year_

## AMD - Virtualization SRDC

**Software Development Engineer 1** | **2020 年 3 月 - 2021 年 7 月**

- 一年内修复了超过 160 个 Linux KMD `amdgpu-pro` 和 `gim` 的 ticket。
- 帮助 Tech Lead 将虚拟化自动测试系统的通过率从 75% 提高到 95%。
- 设计并实现了一个状态机来协调虚拟机渲染请求并将虚拟化性能从 60% 提高到 80%。（虚拟化性能 = `sum(VM_FPS)/Bare_Metal_FPS`）
- 在内部技术分享活动中多次发表有关 Linux 内核开发、算法和数据结构的演讲。

## NI - R&D Shanghai

**Software Engineer** | **2019 年 3 月 - 2020 年 2 月**

- 使用`PyTest`和`scrapy`设计并实现了带有结果仪表板的自动化测试系统，使用`RESTful` API 集成到公司的内部测试平台中，并将其运用到团队的日常 Scrum 流程中。
- 参与`OneRT` Linux feed 开发管理，并将总体平均包大小减少 5%。
- 使用`Flask`和`Docker`设计和开发 NISH 资产管理系统后端，使用`RESTful` API 集成到公司的微信小应用程序中，极大地改善了办公室资产的管理，并节省了 10％ 的资产损失成本。
- 奖项
  1. _2019 2nd Most Popular National Instruments Tech Week Project_

# 教育

## 上海大学 - 计算机工程与科学学院

**学士 计算机科学** | **2015 年 9 月 - 2019 年 7 月**

- 上海大学开源社区讲师
- 奖项
  1. _上海大学优秀毕业论文_
  1. _上海大学创新创业奖学金_
  1. _上海大学物联网创新创业竞赛一等奖_
  1. _上海大学第四届计算机应用能力大赛三等奖_
  1. _上海大学学生社区科创之星_

# 项目

## `OceanProtect` - 华为数据保护解决方案

- 担任`管控业务团队`的子系统架构师、特性 SE、DEG Leader，`保护引擎组`的 DE、FO，`系统管理组`的 DE，`基础平台组`的 DE
  1. 编码绝对贡献
      - 上`master`库代码总量：52.2K+ 行。
      - 输出检视意见：561+ 个`issue`。
  2. 修改、处理疑难、性能问题单 135+ 个。
- 提升任务调度性能 10,400%：在满并发规格下，任务从发起调度到代理执行任务从最高 35+ 分钟缩短至 20 秒以内，时间复杂度从`O(n^2 * m)`优化至`O(n * m)`。
- 设计并开发`ProtectManager`的`Nutanix`备份插件，3 天输出 3.3K+ 行 代码，转测 0 缺陷。
- 设计并开发`OceanProtect`四眼认证/MPA（多人审批授权）模块，助力`OceanProtect`产品通过欧洲和中国多款法规和认证。
- 提出 9+ 项架构整改建议，主导 22+ 项性能优化
  1. 重构 `ProtectManager` 的 `VMware` 备份插件扫描逻辑，提升性能 1,100%：实现 10,000 台虚拟机集群扫描时间从 2 小时缩短至 10 分钟。
  2. 优化副本归档任务 `Redis` 内存使用效率 3,557%：使 10,000 个副本的归档任务队列内存占用从 2 GB 内存降低至 56 MB.
  3. 优化批量取消任务性能 11,900%：处理速度从峰值 1 分钟/个提升至 0.5 秒/个且支持 10 并发。
  4. 优化批量下发副本删除任务性能 1,900%：执行效率从峰值 1 分钟/个提升至 3 秒/个且支持 10 并发。
  5. 优化副本 summary 查询性能 37,400%： 百万级副本查询从直接 OOM 改进为 5 秒内返回，20 万副本查询从 5 分钟优化至 0.8 秒内返回。
  6. 改进日志导出性能 19,900%：大负载场景下日志导出页面响应从 3 分钟优化至 0.9 秒内。
  7. 优化 `protectmanager-system-base` 和 `protectmanager-biz-service` POD 升级重启速度 1,000%：POD 升级过程从 12 分钟优化至 90 秒。
  8. 重构虚拟机组备份任务下发流程，提升下发速度 13,400%：使满规格虚拟机组备份任务下发时间从 1.5 小时缩短至 40 秒。
  9. 优化虚拟机组备份任务进度上报机制，通过数据库操作优化及锁和事务粒度细化，解决虚拟机组备份上报过程中锁超时导致的任务状态一小时不更新而自动失败的问题。
  10. 重构告警和事件转储机制，优化性能 246,757%：使 400 万条告警/事件转储事件从 24 小时缩短到 35 秒。
  11. 设计重构备份代理心跳上报逻辑，提升单个 Agent 管理个数 1,000%.

## 通过混合递归云委托进行分布式对象存储管理

- 提供了一种自递归且经济有效的解决方案，以提供用户可以使用统一接口将对象存储到多个存储解决方案的服务。
- 典型的单例部署可以是云驱动融合服务。
- 典型的集群部署可能是自递归对象存储云，它既可以保存本地存储，也可以将存储委托给其他云服务。

## `DT Automation` 和 `Fortress-Diag`

- 担任`OSA Fortress`团队的 Scrum Lead。
- 参与开发了`DT`模块的自动诊断和修复框架`DT Automation`。
- 参与了`qTest`和现有测试自动化框架的集成。
- 技术栈：`Python` + `Java` + `qTest` + `Jenkins` + `Docker`

## `ECS` 和 `OBS` - `Elastic Cloud Storage` 弹性云存储系统和 `ObjectScale` 对象存储系统

项目链接：[https://www.dell.com/en-us/dt/storage/ecs/index.htm](https://www.dell.com/en-us/dt/storage/ecs/index.htm)

- 担任`OBS Metadata Layer 1`团队的 Scrum Lead。
- 发布 2 项美国专利和 2 项中国专利。
- 开发了一个加快`ECS`/`OBS` `DT`写入性能 15% 的 dumping 算法。
- 开发了一个节省了 5% 存储空间并加快了 7% 对象序列化效率的数据结构。
- `OBS`是`Kubernetes`部署版本的`ECS`也是`ECS`的未来。
- 技术栈：`Java` + `Spring` + `ProtoBuf` + `Kubernetes` + `Docker` + `Jenkins` + `Grafana`

## `andgpu-pro` 和 `gim`

- 一年内修复了超过 160 个 Linux KMD `amdgpu-pro` 和 `gim` 的 ticket。
- 帮助 Tech Lead 将虚拟化自动测试系统的通过率从 75% 提高到 95%。
- 设计并实现了一个状态机来协调虚拟机渲染请求并将虚拟化性能从 60% 提高到 80%。（虚拟化性能 = `sum(VM_FPS)/Bare_Metal_FPS`）
- 技术栈：`C` + `Linux Kernel` + `SR-IOV` + `qemu` + `KVM`

## LiCMS 内容管理系统

GitHub 链接：[https://github.com/realJustinLee/LiCMS](https://github.com/realJustinLee/LiCMS) | 在线预览：[https://www.1a2.org](https://www.1a2.org)

- 设计和开发了一个全栈内容管理系统，允许人们将其用作博客系统。
- 提供`RESTful` API 和网站（基于`Bootstrap5`）两种方案, 并有两步验证。
- 使用`Flask`和`SQLAlchemy`实现后端模块，以提供轻量级且独立于数据库的系统；使用`Docker`对应用程序进行容器化。
- 实现了多个运行环境（`Linux`、`Docker` 和 `Heroku`）。
- 技术栈：`Python` + `Flask` + `MySql` + `Docker` + `BootStrap`

## LiAg 模型生成器

GitHub 链接：[https://github.com/realJustinLee/LiAg](https://github.com/realJustinLee/LiAg) | 在线预览：[https://liag.1a2.org](https://liag.1a2.org)

- 使用`WebGL`和`React.js`设计和开发了一个 3D 建模系统，供人们建模他们最喜欢的电影手办并用 3D 打印机打印。
- 使用`React.js`开发界面系统，使用`WebGL`开发网页 3D 建模和渲染；使用`Docker`对应用程序进行容器化。
- 扩展和开发了`STLExporter`，将每个模型零件融合为一整个 3D 模型，并将输出`STL`模型文件体积减少了 30%。
- 技术栈：`JavaScript` + `React.js` + `Three.js` + `WebGL` + `Docker`
