# Justin Xin Li

> Shanghai, China | [justindelladam@live.com](mailto:justindelladam@live.com) | +86 180 1601 5760 | [GitHub](https://github.com/realJustinLee)

**Systems Architect with 7+ years of software engineering experience spanning GPU virtualization, distributed storage, cloud platforms, data protection, and legal AI. Strengths in system architecture, large-scale performance optimization, AI-assisted architecture governance, and LLM applications, backed by experience in low-level systems development, enterprise product delivery, and cross-team technical leadership.**

# Core Expertise

- Fluent English, IELTS **7.5**
- **AI-augmented architecture decision governance**: designed and chaired a human-plus-AI review mechanism for high-risk architecture decisions, with clear human decision ownership and `GPT`, `Gemini`, `Qwen`, and `DeepSeek` acting as structured challengers.
- **Legal AI**: experience designing and delivering `RAG` solutions for legal knowledge retrieval, question answering, and drafting; exploring `LLM Wiki` for legal knowledge organization, with citation verification and domain expert evaluation to improve output quality.
- AI-era infrastructure, control-plane architecture, distributed systems, cloud storage, data protection, performance, and reliability engineering
- Technical leadership: system architecture ownership, cross-team design reviews, quality governance, and Tech Lead development
- Patents: **2 US patents** and **2 Chinese patents**
    1. US Patent `US 2024/0111810 A1`: [Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111810)
    2. US Patent `US 2024/0111836 A1`: [Method, Electronic Device, and Computer Program for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111836)
    3. Chinese Patent `202211215669.3`: 数据读取方法、数据更新方法、电子设备和程序产品
    4. Chinese Patent `202211217524.7`: 数据处理方法、电子设备和计算机程序产品
- Certifications
    1. HSDC Professional, `Java`
    2. HSDC Professional, `Python`
    3. [Registered Product Owner™](https://s3.amazonaws.com/scruminc-certs/RPO-6903098)
    4. [Registered Scrum Master™](https://s3.amazonaws.com/scruminc-certs/RSM-2901977)
- Professional Member of the China Computer Federation (CCF)
- Stack Overflow reputation: 890
- GitHub Arctic Code Vault Contributor, GitHub Sponsor, and GitHub Developer Program Member
- Languages: `Java`, `Python`, `C/C++`, `JavaScript`, `SQL`
- Platforms & tools: `Kubernetes`, `Docker`, `Linux`, `KVM`, `SR-IOV`, `Spring`, `Flask`, `React.js`, `Three.js`, `WebGL`

# Work Experience

## LexisNexis - LexisNexis Legal & Professional

**Machine Learning Engineering Lead** | **June 2026 - Present**

### Hong Kong BU | Lead Data Scientist (Acting)

- Owned Hong Kong data science requirements, roadmap planning, technical decisions, and delivery quality, coordinating priorities and dependencies across teams. Led the team to meet key delivery targets for `Cowork`, sentencing content, and Traditional Chinese capabilities ahead of schedule, with positive subject-matter expert (SME) evaluations and customer feedback.
- Proposed and led native `DOCX` editing for `Cowork` to address formatting loss from Markdown round trips. Used LLM-guided content understanding and edit localization to modify document XML selectively, preserving existing structure and styles wherever possible. Oversaw service integration, direct Word output, and end-to-end validation, improving template fidelity and document usability.
- Led Traditional Chinese `Upload` / `Vault` localization, covering Chinese character counting, clause and heading parsing, and prompts. In a controlled experiment with **24 test cases** and **137 required facts**, weighted fact recall was **28.5%** for the `RAG` baseline and **99.3%** and **100%** across two `MapReduce` evaluation rounds. Used the findings to define an optimized `RAG` primary path with budget-constrained `MapReduce` supplementation; led delivery of language controls, original-text preservation, and structured timelines.
- Led integration of updated Hong Kong sentencing content and exploration of `LLM Wiki` alongside existing `RAG`, coordinating content, engineering, and SMEs. Oversaw question-answering validation, drafting impact analysis, version isolation, and citation checks to deliver sentencing content and question-answering capabilities for Hong Kong legal use cases.
- Independently built and delivered an internal Hong Kong SME scoring and scheduling platform using AI-assisted development. Unified fragmented spreadsheet schedules, shared evaluation progress, and consolidated scoring analysis, improving evaluation coordination and accelerating data science feature delivery.
- Led the team's UK legal content integration and research workflow validation for `ICS UK`, passing the first assessment without adjustments or rescoring.
- Oversaw citation verification and case-name filtering, and guided `Vault` email and letter drafting through SME review into a controlled rollout. Coordinated new-model enablement and quality and latency evaluations for drafting and Web search.

### New Zealand BU | Machine Learning Engineering Lead

- Owned New Zealand roadmap planning, technical decisions, and engineering delivery for legal research and drafting. Led commercial release of document subset selection and source links, expanding supported document count from **1 to 10**; oversaw the technical release of full-text drafting from document management systems (`DMS`) and enhanced drafting source links.
- Led customer-facing delivery of agentic legal workflows spanning `Planner`, `Cowork` MVP, multi-prompt execution, and `LexisNexis` / Web content integration. Partnered with the application team on answer retries and `Canvas` revision export, supporting task execution, answer refinement, and document output.
- Led `Vault` infrastructure expansion, increasing the character limit to **4 million** and the per-file limit from **20 MB to 100 MB**. Oversaw customer-accessible delivery of `General AI` local hosting, lightweight `DMS` connectivity, and deeper `DMS` integration for `Protege 2.0` drafting.

## Huawei - Data Protection Architecture & Design

**Senior Engineer A (17B) / Committer** | **Oct 2024 - Mar 2026**

- Served as subsystem architect across the Protection Engine, System Management, and Infrastructure Platform teams within the `OceanProtect` Control Business Team, leading architecture design and technical roadmap planning.
- Worked across the three teams to drive cross-module architecture decisions, interface-boundary governance, quality gates, and deep-dive troubleshooting, serving as the technical lead on high-risk requirements and production issues.
- Designed and rolled out a human-led, AI-agent-assisted architecture decision mechanism for `DEG` reviews on topics spanning the Protection Engine, System Management, and Infrastructure Platform teams.
- Served as the human decision owner and co-chair, bringing in AI agents such as `GPT`, `Gemini`, `Qwen`, and `DeepSeek` as structured challengers to surface scalability, security, and long-term maintainability risks, with explicit decision logging and post-decision validation that prevented multiple high-risk architectural rollbacks and design defects before implementation.
- Re-architected the job scheduler under peak concurrency, reducing initiation-to-execution latency from **35+ minutes** to **under 20 seconds** and improving time complexity from `O(n^2 * m)` to `O(n * m)`.
- Led **22+** performance optimization and refactoring efforts across backup, query, export, and event-processing paths. Representative wins include reducing a **10,000-VM** scan from **2 hours** to **10 minutes**, cutting `Redis` memory usage for a **10,000-copy** archival queue from **2 GB** to **56 MB**, accelerating batch cancellation from **1 minute per job** to **0.5 seconds**, and reducing a **4 million-record** alarm/event dump from **24 hours** to **35 seconds**.
- Designed and delivered the `OceanProtect` `Four-Eyes Authentication` / `MPA` module, helping the product meet Chinese and EU regulatory requirements including `GB/T 35273-2020`, `DORA`, and `EBA` ICT security guidance.
- Designed and implemented a `Nutanix` backup plugin for `ProtectManager` in **3 days** with **3.3K+ LOC**, and handed it off with **zero defects** in testing.
- Led diagnosis and resolution of **75+** critical production issues across global enterprise customers including Petrobras, WeBank, China Mobile, and Emaar.
- Contributed **54.5K+ LOC** merged into `master` as a department-level `Java` / `Python` committer and drove code review and defect prevention across the three teams: produced **621+** review findings, identified **15** security issues and **5** database performance issues, and developed **5** Tech Leads.
- Certifications
    1. HSDC Professional, Java
    2. HSDC Professional, Python
- Awards
    1. _2025 Data Management PDU Quality Excellence Award_
    2. _2025 Data Protection Development Department Best Committer of June_
    3. _2025 Architect DP Excellent Trainee/Winning Team_
    4. _2025 DEDP Excellent Trainee/Winning Team_
    5. _2024 NEO Excellent Trainee/Winning Team/Top Class Committee Member_

## Dell Technologies - Dell EMC

**Software Engineer 2 (IC-6)** | **Aug 2021 - Oct 2024**

- Served as Scrum Lead for the `OBS Metadata Layer 1` and `OSA Fortress` teams, and as China coordinator for the `ECS` / `OBS` DevOps framework release virtual team, aligning multi-site execution and release readiness.
- Led cross-site technical collaboration on distributed storage delivery for `ECS` and `ObjectScale`, covering metadata, data-path performance, engineering tooling, and the transition from `VMware`-based `ECS` to `Kubernetes`-based `OBS`.
- Designed a `DT` write-path optimization algorithm, improving `ECS` / `OBS` write performance by **15%**.
- Contributed to internal engineering frameworks including `DT Automation` and `Fortress-Diag`, adding automatic diagnosis/repair flows for the `DT` module and integrating `qTest` with the existing `Jenkins` `CI` / `CD` automation workflow.
- Designed a storage data structure that reduced storage footprint by **5%** and improved object serialization efficiency by **7%**.
- Delivered engineering support for enterprise storage platforms adopted by major global financial institutions including Goldman Sachs, Morgan Stanley, Citibank, and RBC.
- Patents
    1. US Patent `US 2024/0111810 A1`: [Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111810)
    2. US Patent `US 2024/0111836 A1`: [Method, Electronic Device, and Computer Program for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111836)
    3. Chinese Patent `202211215669.3`: 数据读取方法、数据更新方法、电子设备和程序产品
    4. Chinese Patent `202211217524.7`: 数据处理方法、电子设备和计算机程序产品
- Certifications
    1. `RPO-6903098`: [Registered Product Owner™](https://s3.amazonaws.com/scruminc-certs/RPO-6903098)
    2. `RSM-2901977`: [Registered Scrum Master™](https://s3.amazonaws.com/scruminc-certs/RSM-2901977)
- Awards
    1. _2023 Team of The Year: Innovation_
    2. _Achievement: OBS Metadata Layer 1 First 2 Features Completed_
    3. _Giving & Impact: Making a positive impact in the year 2023_
    4. _Innovation: Nice work on the 2023 Hackathon Project_
    5. _Achievement: Awesome work for DT automation_
    6. _Winning Together: Epoch Release Branching and Pipeline Monitoring_
    7. _2021 Team of The Year_

## AMD - Virtualization SRDC

**Software Development Engineer 1** | **Mar 2020 - Jul 2021**

- Delivered Linux GPU virtualization and kernel-mode driver features across the `amdgpu-pro` / `GIM` stack on `SR-IOV`, `KVM`, and `QEMU`.
- Closed **160+** driver and virtualization tickets across `amdgpu-pro` and `GIM` in one year, far above the typical team throughput and with strong end-to-end execution on issue diagnosis, fixing, and validation.
- Implemented a state machine to coordinate VM render requests and improved virtualization performance from **60%** to **80%** of bare-metal FPS.
- Raised the pass rate of the virtualization automated test system from **75%** to **95%**, and shared implementation lessons through internal talks on Linux kernel development, algorithms, and data structures.

## NI (National Instruments) - R&D Shanghai

**Software Engineer** | **Mar 2019 - Feb 2020**

- Identified repetitive validation bottlenecks and built an automated testing platform with `PyTest`, `scrapy`, and dashboards, integrating it with internal `RESTful APIs` and the team's daily agile workflow.
- Improved `OneRT` Linux feed management and reduced average bundle size by **5%**, reflecting a pragmatic engineering mindset.
- Awards
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

# Education

## Shanghai University - School of Computer Engineering and Science

**B.Eng. in Computer Science and Technology** | **Sep 2015 - Jul 2019**

- Lecturer at Shanghai University Open Source Community
- Awards
    1. _Excellent graduation thesis from Shanghai University_
    2. _Innovation and Entrepreneurship Scholarship of Shanghai University_
    3. _1st Prize of IoT Innovation and Entrepreneurship Competition of Shanghai University_
    4. _3rd Prize of the 4th Computer Application Ability Competition of Shanghai University_
    5. _Science and Innovation Star of Shanghai University Student Community_

# Portfolio

## `Protégé` Legal AI Agent Platform

**LexisNexis - LexisNexis Legal & Professional**

- Role: Machine Learning Engineering Lead, also serving as Lead Data Scientist (Acting) for the Hong Kong BU, with responsibility for technical solutions and delivery across Hong Kong and New Zealand.
- Led Hong Kong legal content integration and Traditional Chinese capabilities, advancing `RAG` optimization, `LLM Wiki` exploration, citation verification, and quality evaluation.
- Proposed and led native `DOCX` editing for `Cowork`, improving document formatting fidelity and output usability.
- Coordinated New Zealand delivery of `Planner`, multi-prompt execution, `DMS` integration, and `Vault` expansion, bringing legal AI agent workflows to customers.

## `OceanProtect` Protection Engine, System Management, and Infrastructure Platform

**Huawei - Data Protection Architecture & Design**

- Role: subsystem architect, cross-team technical lead, and AI-augmented `DEG` co-chair across the Protection Engine, System Management, and Infrastructure Platform teams.
- `OceanProtect` is Huawei's unified data-protection platform for next-generation data centers and multicloud, covering backup, recovery, copy management, cyber resilience, and appliance-grade security capabilities such as `WORM`, anti-deletion, and `Air Gap`.
- Drove roadmap planning, interface-boundary governance, and solution decisions across the Protection Engine, System Management, and Infrastructure Platform teams.
- Introduced AI-augmented `DEG` governance with clear human decision ownership, using `GPT`, `Gemini`, `Qwen`, and `DeepSeek` as structured challengers before implementation.
- Led scheduler redesign, `Redis` archival-queue memory optimization, alarm / event path refactoring, `MPA` compliance delivery, and the `Nutanix` backup plugin.

## `ECS` / `ObjectScale` Distributed Object Storage Platform

**Dell Technologies - Dell EMC**

- Role: Scrum Lead, cross-site coordinator, and engineering owner for metadata, write path, and `DT` automation / diagnostics.
- `ECS` is Dell's enterprise object-storage platform with S3-compatible access, global distribution, and a single namespace for large-scale unstructured data; `ObjectScale` extends it with a `Kubernetes`-based, AI-ready architecture while retaining `ECS` workflows and APIs.
- Drove cross-site metadata and write-path delivery, `DT` write optimization, storage data-structure design, `DT Automation` / `Fortress-Diag`, and the `VMware` `ECS` to `Kubernetes` `OBS` / `ObjectScale` transition.

## Distributed Object Store Management by Mixed Recursive Cloud Delegation

**Dell Technologies - Dell EMC** | **2023 Hackathon Project**

- Role: project lead, solution architect, and primary developer.
- Designed a self-recursive, cost-controlled object-storage architecture with a unified interface across multiple storage backends.
- Supported both single-instance deployments such as cloud-drive fusion and self-recursive clusters that could store local data while delegating to other clouds.
- Recognition
    1. _Innovation: Nice work on the 2023 Hackathon Project_

## AMD GPU Virtualization Stack

**AMD - Virtualization SRDC**

- Role: primary developer and execution owner for `amdgpu-pro` / `GIM` virtualization delivery and validation.
- AMD's GPU virtualization stack uses `MxGPU` / `SR-IOV` to share accelerators across `QEMU` / `KVM` VMs, with `amdgpu-pro` and `GIM` close to kernel-mode driver, partitioning, scheduling, and validation paths.
- Built Linux driver and virtualization features, closed high-volume issues end to end, coordinated VM render requests with a state machine, and improved automated validation coverage and pass rates.

## Automated Validation Platform and `OneRT` Feed Engineering

**NI (National Instruments) - R&D Shanghai**

- Role: backend designer and primary developer.
- The project aligned with NI's automated test software model, centered on `TestStand`, `SystemLink`, dashboards, traceability, APIs, and software deployment for distributed test systems.
- Built a lightweight validation platform around automated execution, data collection, dashboards, internal `RESTful APIs`, and `OneRT` feed / package management, reducing manual regression and operational overhead.

## NI Shanghai Asset Management System

**NI (National Instruments) - R&D Shanghai** | **2019 Tech Week**

- Role: project lead, backend architect, and primary developer.
- Built the backend with `Flask` and `Docker`, integrated it with the company's `WeChat` mini-app through `RESTful APIs`, and reduced asset-loss costs by **10%**.
- Recognition
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

## `LiCMS` - Open Source Content Management System

**GitHub:** [https://github.com/realJustinLee/LiCMS](https://github.com/realJustinLee/LiCMS) | **Online Preview:** [https://www.1a2.org](https://www.1a2.org)

- Role: founder, architect, and sole developer.
- Built `LiCMS` from scratch and continued evolving it from the first commit into a deployable content platform, personally leading the full journey through **321 commits**.
- Designed a modular `Flask` `App Factory` + `Blueprint` architecture with dedicated `main`, `auth`, `api`, and `dev_ops` boundaries, layered configuration for `development`, `testing`, `docker`, `heroku`, and `unix`, plus `SQLAlchemy` models and migrations for sustainable evolution.
- Implemented end-to-end product capabilities including role-based access control, email-confirmed registration, Markdown-based posts, comments, follow graph and timeline, paste-sharing, `JWT`-backed API authentication, `TOTP`-based 2FA, and self-service email/password/2FA recovery flows built on signed tokens.
- Built the engineering and operations toolchain around the product, including `Flask CLI` commands for `test`, `profile`, and `deploy`, unit / API / `Selenium` test suites with coverage reports, and a deployable `Docker Compose` stack integrating `MariaDB`, `Nginx`, `Certbot`, `gunicorn`, `HTTPS` renewal, and production error email alerts.
- Continued hardening and evolving the system through dependency governance, migration of signed token flows from `itsdangerous` to `JWT`, `SQLAlchemy` modernization, `Bootstrap 5` migration, and runtime improvements including `HTTPS`, reverse proxying, and error-alert email notifications.

## `LiAg` - Open Source 3D Avatar Generator

**GitHub:** [https://github.com/realJustinLee/LiAg](https://github.com/realJustinLee/LiAg) | **Online Preview:** [https://liag.1a2.org](https://liag.1a2.org)

- Role: founder, front-end / graphics architect, and sole developer.
- Built an open-source browser-based 3D avatar modeling system from scratch, owning the UI workflow, rendering pipeline, asset organization, and export experience for printable custom models.
- Designed a `React.js` + `Three.js` / `WebGL` architecture centered on a reusable scene controller, modular body-part libraries, attachment metadata, pose definitions, and runtime loaders for composable character assembly.
- Implemented interactive part selection and pose editing in the browser, and extended the `STL` export pipeline to merge skinned mesh fragments into a single printable model while reducing exported `STL` file size by **30%**.
- Structured the runtime and asset pipeline around `GLTF` models and JSON-based pose and component libraries, making it easy to add new parts, poses, and printable variants over time.
