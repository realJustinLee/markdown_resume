# Justin Xin Li

> Shanghai, China | [justindelladam@live.com](mailto:justindelladam@live.com) | +86 180 1601 5760 | [GitHub](https://github.com/realJustinLee)

**Systems Architect with 7+ years of software engineering experience spanning GPU virtualization, distributed storage, cloud platforms, data protection, and legal AI. Skilled in system architecture, large-scale performance optimization, AI-assisted architecture governance, and LLM applications, with experience in low-level systems development, enterprise product delivery, and cross-team technical leadership.**

# Core Expertise

- Fluent English, IELTS **7.5**
- **AI-assisted architecture decision governance**: designed and chaired a human-led review process for high-risk architecture decisions, with clear human accountability and `GPT`, `Gemini`, `Qwen`, and `DeepSeek` systematically challenging proposals.
- **Legal AI**: design and delivery of `RAG` solutions for legal knowledge retrieval, question answering, and drafting; exploration of `LLM Wiki` for legal knowledge organization, with citation verification and domain expert evaluation to improve output quality.
- AI-era infrastructure, control-plane architecture, distributed systems, cloud storage, data protection, performance, and reliability engineering
- Technical leadership: system architecture ownership, cross-team design reviews, quality governance, and Tech Lead development
- Patents: **2 US patents** and **2 Chinese patents**
    1. US Patent `US 12,072,937 B2`: [Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12072937)
    2. US Patent `US 12,566,824 B2`: [Method, Electronic Device, and Computer Program Product for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12566824)
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
- Proposed and led a native `DOCX` editing approach for `Cowork` to address formatting loss from Markdown round trips. Used LLMs to interpret content and locate edits, updating document XML selectively while preserving existing structure and styles wherever possible. Oversaw service integration, direct Word output, and end-to-end validation, improving template fidelity and document usability.
- Led Traditional Chinese `Upload` / `Vault` localization, covering Chinese character counting, clause and heading parsing, and prompt localization. In a controlled experiment with **24 test cases** and **137 required facts**, weighted fact recall was **28.5%** for the `RAG` baseline, compared with **99.3%** and **100%** in two `MapReduce` evaluation rounds, respectively. Used the findings to define an optimized `RAG` primary path with budget-constrained `MapReduce` supplementation; led delivery of language controls, original-text preservation, and structured timelines.
- Led integration of updated Hong Kong sentencing content and exploration of `LLM Wiki` alongside existing `RAG`, coordinating content, engineering, and SMEs. Oversaw question-answering validation, drafting impact analysis, version isolation, and citation checks to deliver sentencing content and question-answering capabilities for Hong Kong legal use cases.
- Independently built and delivered an internal Hong Kong SME scoring and scheduling platform using AI-assisted development. Consolidated schedules from fragmented spreadsheets and provided shared calendars, progress tracking, and scoring analysis, improving evaluation coordination and accelerating data science feature delivery.
- Led the team's UK legal content integration, research workflow validation, and assessment preparation for `ICS UK`; the team passed the first assessment without adjustments or rescoring.
- Oversaw citation verification and case-name filtering, and guided `Vault` email and letter drafting through SME review into a controlled rollout. Coordinated new model activation and evaluations of quality and latency for drafting and web search.

### New Zealand BU | Machine Learning Engineering Lead

- Owned New Zealand roadmap planning, technical decisions, and engineering delivery for legal research and drafting. Led the commercial release of document subset selection and source links, increasing the number of supported documents from **1 to 10**; oversaw the technical release of full-text drafting from document management systems (`DMS`) and enhanced drafting source links.
- Led delivery of agentic legal workflows to customers, covering `Planner`, `Cowork` MVP, multi-prompt execution, and `LexisNexis` / web content integration. Partnered with the application team on answer retries and `Canvas` revision export, supporting task execution, answer refinement, and document output.
- Led `Vault` infrastructure expansion, increasing the character limit to **4 million** and the per-file limit from **20 MB to 100 MB**. Oversaw delivery of local hosting for `General AI`, lightweight `DMS` connectivity, and deeper `DMS` integration for `Protégé 2.0` drafting, making these capabilities available to customers.

## Huawei - Data Protection Architecture & Design

**Senior Engineer A (17B) / Committer** | **Oct 2024 - Mar 2026**

- Served as a subsystem architect across the Protection Engine, System Management, and Infrastructure Platform teams within the `OceanProtect` Control Business Team, leading architecture design and technical roadmap planning.
- Coordinated cross-module architecture decisions, interface boundaries, quality gates, and complex troubleshooting across the three teams, serving as the technical lead on high-risk requirements and production issues.
- Designed and introduced a human-led architecture decision process supported by AI agents for `DEG` reviews across the Protection Engine, System Management, and Infrastructure Platform teams.
- Served as decision owner and co-chair, using AI agents such as `GPT`, `Gemini`, `Qwen`, and `DeepSeek` to challenge proposals and identify scalability, security, and long-term maintainability risks. Documented decisions and validated them after review to identify and address multiple high-risk design defects before implementation, avoiding potential architectural rollbacks.
- Re-architected the job scheduler under peak concurrency, reducing initiation-to-execution latency from **35+ minutes** to **under 20 seconds** and reducing time complexity from `O(n^2 * m)` to `O(n * m)`.
- Led **22+** performance optimization and refactoring efforts across backup, query, export, and event-processing paths. Results included reducing a **10,000-VM** scan from **2 hours** to **10 minutes**, cutting `Redis` memory usage for a **10,000-copy** archival queue from **2 GB** to **56 MB**, accelerating batch cancellation from **1 minute per job** to **0.5 seconds per job**, and reducing the time to export **4 million** alarm/event records from **24 hours** to **35 seconds**.
- Designed and delivered the `OceanProtect` `Four-Eyes Authentication` / `MPA` module to support compliance with relevant requirements in `GB/T 35273-2020`, `DORA`, and `EBA` ICT security guidance.
- Designed and implemented a `Nutanix` backup plugin for `ProtectManager` in **3 days**, producing **3.3K+ LOC** with **zero defects** recorded at the testing handoff.
- Led diagnosis and resolution of **75+** critical production issues across global enterprise customers including Petrobras, WeBank, China Mobile, and Emaar.
- Contributed **54.5K+ LOC** to `master` as a department-level `Java` / `Python` committer and led code review and defect prevention across the three teams. Produced **621+** review findings, identified **15** security issues and **5** database performance issues, and mentored **5** Tech Leads.
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

- Served as Scrum Lead for the `OBS Metadata Layer 1` and `OSA Fortress` teams, and as China coordinator for the `ECS` / `OBS` DevOps Framework Release virtual team, coordinating work and release readiness across sites.
- Coordinated cross-site technical collaboration on distributed storage delivery for `ECS` and `ObjectScale`, covering metadata, data-path performance, engineering tooling, and the transition from `VMware`-based `ECS` to `Kubernetes`-based `OBS`.
- Designed a `DT` write-path optimization algorithm, improving `ECS` / `OBS` write performance by **15%**.
- Contributed to internal engineering frameworks including `DT Automation` and `Fortress-Diag`, adding automated diagnostic and repair workflows for the `DT` module and integrating `qTest` with the existing `Jenkins` CI/CD workflow.
- Designed a storage data structure that reduced storage footprint by **5%** and improved object serialization efficiency by **7%**.
- Provided engineering support for enterprise storage platforms used by major global financial institutions including Goldman Sachs, Morgan Stanley, Citibank, and RBC.
- Patents
    1. US Patent `US 12,072,937 B2`: [Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12072937)
    2. US Patent `US 12,566,824 B2`: [Method, Electronic Device, and Computer Program Product for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12566824)
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

- Contributed to Linux GPU virtualization and kernel-mode driver development across the `amdgpu-pro` / `GIM` stack using `SR-IOV`, `KVM`, and `QEMU`.
- Resolved **160+** driver and virtualization tickets across `amdgpu-pro` and `GIM` in one year, covering diagnosis, fixes, and validation.
- Implemented a state machine to coordinate VM rendering requests, increasing virtualized FPS from **60%** to **80%** of bare-metal performance.
- Raised the pass rate of the automated virtualization test system from **75%** to **95%**, and shared implementation lessons through internal talks on Linux kernel development, algorithms, and data structures.

## NI (National Instruments) - R&D Shanghai

**Software Engineer** | **Mar 2019 - Feb 2020**

- Identified bottlenecks in repetitive validation and built an automated testing platform with `pytest`, `Scrapy`, and dashboards, integrating it with internal RESTful APIs and the team's daily agile workflow.
- Contributed to improvements in `OneRT` Linux feed management, reducing average bundle size by **5%**.
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
- Led Hong Kong legal content integration and delivery of Traditional Chinese capabilities, including `RAG` optimization, `LLM Wiki` exploration, citation verification, and quality evaluation.
- Proposed and led a native `DOCX` editing approach for `Cowork`, improving document formatting fidelity and output usability.
- Coordinated New Zealand delivery of `Planner`, multi-prompt execution, `DMS` integration, and `Vault` expansion, bringing legal AI agent workflows to customers.

## `OceanProtect` Protection Engine, System Management, and Infrastructure Platform

**Huawei - Data Protection Architecture & Design**

- Role: subsystem architect, cross-team technical lead, and AI-augmented `DEG` co-chair across the Protection Engine, System Management, and Infrastructure Platform teams.
- `OceanProtect` is Huawei's unified data-protection platform for next-generation data centers and multicloud environments, covering backup, recovery, copy management, cyber resilience, and appliance security features such as `WORM`, deletion protection, and `Air Gap`.
- Led roadmap planning, interface-boundary coordination, and technical decisions across the Protection Engine, System Management, and Infrastructure Platform teams.
- Introduced AI-assisted `DEG` reviews with clear human accountability, using `GPT`, `Gemini`, `Qwen`, and `DeepSeek` to systematically challenge proposals before implementation.
- Led scheduler redesign, `Redis` archival-queue memory optimization, alarm / event path refactoring, `MPA` compliance delivery, and the `Nutanix` backup plugin.

## `ECS` / `ObjectScale` Distributed Object Storage Platform

**Dell Technologies - Dell EMC**

- Role: Scrum Lead, cross-site coordinator, and engineering owner for metadata, write-path development, and `DT` automation / diagnostics.
- `ECS` is Dell's enterprise object-storage platform with S3-compatible access, global distribution, and a single namespace for large-scale unstructured data; `ObjectScale` extends it with a `Kubernetes`-based, AI-ready architecture while retaining `ECS` workflows and APIs.
- Drove cross-site metadata and write-path delivery, `DT` write optimization, storage data-structure design, `DT Automation` / `Fortress-Diag`, and the `VMware` `ECS` to `Kubernetes` `OBS` / `ObjectScale` transition.

## Distributed Object Store Management by Mixed Recursive Cloud Delegation

**Dell Technologies - Dell EMC** | **2023 Hackathon Project**

- Role: project lead, solution architect, and primary developer.
- Designed a self-recursive, cost-controlled object-storage architecture with a unified interface across multiple storage backends.
- Supported both single-instance deployments, such as cloud-drive aggregation, and self-recursive clusters that could store data locally while delegating storage to other clouds.
- Recognition
    1. _Innovation: Nice work on the 2023 Hackathon Project_

## AMD GPU Virtualization Stack

**AMD - Virtualization SRDC**

- Role: primary developer and delivery owner for `amdgpu-pro` / `GIM` virtualization and validation.
- AMD's GPU virtualization stack uses `MxGPU` / `SR-IOV` to share accelerators across `QEMU` / `KVM` VMs; the `amdgpu-pro` / `GIM` stack covers kernel-mode drivers, partitioning, scheduling, and validation.
- Built Linux driver and virtualization features, resolved a large volume of issues end to end, coordinated VM rendering requests with a state machine, and improved automated validation coverage and pass rates.

## Automated Validation Platform and `OneRT` Feed Engineering

**NI (National Instruments) - R&D Shanghai**

- Role: backend designer and primary developer.
- The project aligned with NI's automated test software model, centered on `TestStand`, `SystemLink`, dashboards, traceability, APIs, and software deployment for distributed test systems.
- Built a lightweight validation platform around automated execution, data collection, dashboards, internal RESTful APIs, and `OneRT` feed / package management, reducing manual regression testing and operational overhead.

## NI Shanghai Asset Management System

**NI (National Instruments) - R&D Shanghai** | **2019 Tech Week**

- Role: project lead, backend architect, and primary developer.
- Built the backend with `Flask` and `Docker`, integrated it with the company's `WeChat` mini program through RESTful APIs, and reduced asset-loss costs by **10%**.
- Recognition
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

## `LiCMS` - Open Source Content Management System

**GitHub:** [https://github.com/realJustinLee/LiCMS](https://github.com/realJustinLee/LiCMS) | **Online Preview:** [https://www.1a2.org](https://www.1a2.org)

- Role: founder, architect, and sole developer.
- Built `LiCMS` from scratch and evolved it into a deployable content platform over **321 commits**.
- Designed a modular `Flask` `App Factory` + `Blueprint` architecture with separate `main`, `auth`, `api`, and `dev_ops` components, configuration for `development`, `testing`, `docker`, `heroku`, and `unix`, and `SQLAlchemy` models and migrations.
- Implemented role-based access control, registration with email confirmation, Markdown posts, comments, user follows and timelines, paste sharing, `JWT` API authentication, `TOTP` 2FA, and self-service recovery flows for email, passwords, and 2FA using signed tokens.
- Built the engineering and operations toolchain, including `Flask CLI` commands for `test`, `profile`, and `deploy`, unit, API, and `Selenium` tests with coverage reports, and a deployable `Docker Compose` stack integrating `MariaDB`, `Nginx`, `Certbot`, and `gunicorn`.
- Hardened and evolved the system through dependency management, migration of signed token flows from `itsdangerous` to `JWT`, `SQLAlchemy` modernization, `Bootstrap 5` migration, and runtime improvements including `HTTPS`, reverse proxying, and email error alerts.

## `LiAg` - Open Source 3D Avatar Generator

**GitHub:** [https://github.com/realJustinLee/LiAg](https://github.com/realJustinLee/LiAg) | **Online Preview:** [https://liag.1a2.org](https://liag.1a2.org)

- Role: founder, frontend and graphics architect, and sole developer.
- Built an open-source browser-based 3D avatar modeling system from scratch, owning the UI workflow, rendering pipeline, asset organization, and export experience for printable custom models.
- Designed a `React.js` + `Three.js` / `WebGL` architecture centered on a reusable scene controller, modular body-part libraries, attachment metadata, pose definitions, and runtime loaders for composable character assembly.
- Implemented interactive part selection and pose editing in the browser, and extended the `STL` export pipeline to merge skinned mesh fragments into a single printable model while reducing exported `STL` file size by **30%**.
- Structured the runtime and asset pipeline around `glTF` models and JSON pose and component libraries, supporting the addition of new parts, poses, and printable variants.
