# Justin Xin Li

> Senior Engineer A **17B** | Huawei | justindelladam@live.com | +86 180 1601 5760 | Shanghai, P.R.China

- Fluent English, IELTS **7.5**.
- Professional Member of the China Computer Federation.
- Proficient in `Java`, `Java` Concurrency, `JVM` optimization, Algorithms, Data Structure, and Distributed Storage.
- Skilled in `Docker`, `Kubernetes`, `KVM`, and `SR-IOV`.
- Also, Skilled in `Python`, `Javascript`, `React.js`, `C/C++`, `Jenkins`, `qTest`, and more.
- StackOverflow reputation: `890`.
- GitHub Arctic Code Vault Contributor, Sponsor.
- GitHub Developer Program Member.
- Heavy user of `macOS`, `Linux`, `homebrew` & `shell` scripts.
- In-depth love of coding and open source movement, committing to excellence.
- Skilled in using Apple iWork and Microsoft Office Suite, proficient in Keynote and PowerPoint.

# Skills

- Team Management: [Registered Product Owner™](https://s3.amazonaws.com/scruminc-certs/RPO-6903098), [Registered Scrum Master™](https://s3.amazonaws.com/scruminc-certs/RSM-2901977).
- Languages: `Java`, `Python`, `C/C++`, `JavaScript`, `SQL`.
- Technologies: `Java` High Concurrency, `JVM` optimization, `Git`, Algorithms, Data Structure, Distrusted Storage, `Spring`, `Flask`, `React.js`, `Unix`/`Linux`, `Docker`, `PyTorch`, `WebGL`.
- GitHub: [https://github.com/realJustinLee](https://github.com/realJustinLee)

# Work Experience

## Huawei - Data Protection Architecture & Design

**Senior Software Engineer A (17B) / Committer** | **Oct 2024 - Present**

- Served as Subsystem Architect, Feature SE, and DEG Leader for the `System Management & Protection Engine Business Team`. Acted as DE and FO for the `Protection Engine Team`, and as DE for both the `System Management Team` and the `Infrastructure Platform Team`: Oversaw requirements analysis, solution design, troubleshooting, and quality control across the full system lifecycle
    1. Coding net contribution
        - Code submitted into `master` branch: Over 54.1K lines.
        - Valid code review comments: Over 601 `issues`.
    2. Fixed and resolved over 135 difficult or performance related issue tickets.
    3. Improved job scheduling performance by **10,400%**: Under peak concurrency, reduced job schedule initiation-to-execution time from over 35 minutes to less than 20 seconds, optimized time complexity from `O(n^2 * m)` to `O(n * m)`.
    4. Designed and developed a `Nutanix` backup plugin for `ProtectManager`, producing over 3.3K lines of code in 3 days, with 0 defects during testing.
    5. Designed and developed the `OceanProtect` Four-Eyes Authentication / MPA (Multi-Person Authorization) module, enabling the `OceanProtect` product to meet multiple regulatory and certification requirements across China and the European Union
        - National Standard of the People's Republic of China `GB/T 35273-2020`: [Information security technology — Personal information security specification](https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=4568F276E0F8346EB0FBA097AA0CE05E)
        - EU `DORA`: [Digital Operational Resilience Act](https://www.applytosupply.digitalmarketplace.service.gov.uk/g-cloud/services/293002179752718)
        - EU `EBA` Guidelines: [EBA Guidelines on ICT and security risk management](https://www.eba.europa.eu/sites/default/files/document_library/Publications/Guidelines/2020/GLs%20on%20ICT%20and%20security%20risk%20management/872936/Final%20draft%20Guidelines%20on%20ICT%20and%20security%20risk%20management.pdf)
    6. Led the identification and resolution of over 75 critical issues at key clients sites in the production environment: This involved high-priority clients such as Petrobras (Brazil), China Pacific Insurance, WeBank, China Mobile, China Securities Depository and Clearing Corporation, Huaxia Bank, Litasco (Switzerland), AN1 (Algeria), and Emaar (UAE). Addressed 1 Level I ITR, 3 Level II ITRs, 4 Level III ITRs, and multiple Pre-ITRs.
    7. Routine distribution of FST analysis reports and weekly quality reports to all staff via email, overseeing the software quality within the `System Management & Protection Engine Business Team`. Adjusted development processes to reduce the number of new bugs introduced during fixes and regressions, leading to a significant decline compared to previous periods.
    8. Lead the operation of the `System Management & Protection Engine Business Team` DEG, driving the standardized operation of internal business processes
        - Overseeing the review of alarm codes, event codes, error codes, and `RESTful` APIs for the `OceanProtect` product.
        - Establishing and promoting the implementation of standards for log printing, `UT` / `LLT`, code reviews, `RESTful` API design, and the review of alarm/event/error codes.
    9. Participated in and rotated as the host for the `Data Protection Development Department`'s CCB, NodePC, SEG, and ST meetings, effectively overseeing software quality.
    10. Tracked, analyzed, and organized over 90 `BUGLIST` entries, developed corrective plans, drove their implementation, and applied lessons learned. This effectively improved the quality of internal business processes.
    11. Proposed over 9 architecture improvement suggestions and led more than 22 performance optimizations
        - Refactored the `VMware` backup plug-in scanning logic of `ProtectManager`, improving performance by **1,100%**: reduced the scan time for a 10,000-VM cluster from 2 hours to 10 minutes.
        - Optimized the `Redis` memory usage efficiency of the copy archival jobs by **3,557%**: reduced memory consumption of the archival job queue for 10,000 copies from 2 GB to 56 MB.
        - Optimized the performance of batch job cancellation by **11,900%**: improved processing speed from over 1 minute per job to 0.5 seconds per job, with support for 10-way concurrency.
        - Optimized the performance of batch copy deletion job delivery by **1,900%**: improved execution efficiency from over 1 minute per job to 3 seconds per job, with support for 10-way concurrency.
        - Optimized copy summary query performance by **37,400%**: improved million-copy queries from immediate OOM to returning results within 5 seconds, and reduced 200,000-copy query time from 5 minutes to 0.8 seconds.
        - Optimized log export performance by **19,900%**: reduced page response time under heavy-load scenarios from 3 minutes to within 0.9 seconds.
        - Optimized the upgrade speed of the `protectmanager-system-base` and `protectmanager-biz-service` pods by **1,000%**: reduced the pod upgrade process from 12 minutes to 90 seconds.
        - Refactored the backup job delivery workflow for virtual machine groups, improving delivery speed by **13,400%**: reduced full-scale VM group backup job delivery time from 1.5 hours to 40 seconds.
        - Optimized the progress reporting mechanism for virtual machine group backup jobs. Through database operation improvements and finer-grained locks and transactions, resolved the issue where lock timeouts during reporting caused job status to remain unchanged for an hour and then fail automatically.
        - Refactored the alarm and event dump mechanism, improving performance by **246,757%**: reduced the dump time for 4 million alarm/event records from 24 hours to 35 seconds.
        - Designed and refactored the heartbeat reporting logic of the backup agent, increasing the number of agents managed per node by **1,000%**.
- Served as the requirements analysis expert for the `Data Protection PDT`’s RAT backup software control-plane features, and as the feature SE for the `System Management & Protection Engine Business Team`
    1. Oversaw solution design for the `System Management & Protection Engine Business Team`, completing the analysis and decision-making of over 100 pending RAT requirements in real time.
    2. Oversaw solution implementation for the `System Management & Protection Engine Business Team`, completing the implementation and handling of over 35 pending RAT requirements in real time.
- Served as the `Java`/`Python` Committer for the `Data Protection Development Department` across the `Protection Engine Team`, `System Management Team,` and `Infrastructure Platform Team`, ensuring high-quality code and fostering a strong code review culture
    1. Drove systematic remediation of security issues identified during reviews within the team’s DEG, promoting cross-module security scans and coordinating with PLs in each module to ensure full closure of issues.
    2. Enhanced the team’s code review culture by establishing review density as a key metric in the weekly quality report, and by sharing major review insights and issue-fixing experience in the daily 10-minute review briefing, significantly improving participation and review quality across modules
        - `Protection Engine Team`: monthly per-capita review comments increased by **2,277%**, from 1.8 to 41.
        - `System Management Team`: monthly per-capita review comments increased by **400%**, from 11 to 44.
        - `Base Platform Team`: monthly per-capita review comments increased by **500%**, from 7 to 35.
    3. Received the Quality Guardian Award (June 2025): submitted 153 review comments—the highest in the entire development department (TOP 1). Among them were 58 performance and functional issues, plus identification of 15 security issues (including incomplete API authorization and hard-coded keys) and 5 database performance issues, effectively improving code quality before repository submission.
- Trained 5 MDEs for talent pipeline building
    1. 2 for the `Protection Engine Team`
    2. 2 for the `System Management Team`
    3. 1 for the `Infrastructure Platform Team`
- Certifications
    1. HSDC Professional, Java
- Awards
    1. _2025 `Data Management PDU` Quality Excellence Award_
    2. _2025 `Data Protection Development Department` Best Committer of June_
    3. _2025 Architect DP Excellent Trainee/Winning Team_
    4. _2025 DEDP Excellent Trainee/Winning Team_
    5. _2024 NEO Excellent Trainee/Winning Team/Top Class Committee Member_

## Dell Technologies - Dell EMC

**Software Engineer 2 (IC-6)** | **Aug 2021 - Oct 2024**

- Scrum Lead of `OBS Metadata Layer 1` team.
- Scrum Lead of `OSA Fortress` team.
- China Coordinator of `ECS/OBS DevOps Framework Release` V-team.
- Released 2 US patents and 2 Chinese patents.
- Developed a dumping algorithm and sped up the `ECS`/`OBS` `DT` write performance by **15%**.
- Developed a storage data structure that saved the storage space by **5%** and sped up the object serialization efficiency by **7%**.
- Provide high-efficiency `Java` code to the Elastic Cloud Storage System `ECS` and Object Storage `OBS`.
- Provide `ECS` and `OBS` development support to various leading financial institutions worldwide (e.g., Goldman Sachs, Morgan Stanley, Citibank, RBC, etc.)
- Dedicate to `JVM` Optimization, Distributed Cloud Storage, and High-concurrency `Java` development.
- Participated in the transformation of `VMware`-based `ECS` to `Kubernetes`-based `OBS`.
- Participated in the development of an automatic diagnosis and repair framework for the `DT` module called `DT Automation`.
- Participated in the integration of `qTest` and existing test automation framework.
- Publications
    1. Patent `US 2024/0111810 A1`: [Data Read Method, Data Update Method, Electronic Device, and Program Product](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111810)
    2. Patent `US 2024/0111836 A1`: [Method, Electronic Device, and Computer Program for Data Processing](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20240111836)
    3. Patent China `202211217524.7`: 数据处理方法、电子设备和计算机程序产品
    4. Patent China `202211215669.3`: 数据读取方法、数据更新方法、电子设备和程序产品
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

- Fixed over 160 tickets for Linux KMD `amdgpu-pro` and `gim` in 1 year (normally, people fix 5 to 6 tickets per month)
- Helped tech lead to improve the pass rate of the Virtualization Automatic Test System from **75%** to **95%**.
- Designed and implemented a state machine to coordinate VM render requests and improve virtualization performance from **60%** to **80%**. (Ps. Virtualization performance = `sum(VM_FPS)/Bare_Metal_FPS`)
- Lectured multiple times in internal tech sharing events about Linux Kernel development, algorithms, and data structure.

## NI - R&D Shanghai

**Software Engineer** | **Mar 2019 - Feb 2020**

- Designed and implemented an automated testing system with a result dashboard with `PyTest` and `scrapy`, integrated into the company's internal test platform using `RESTful` APIs and leveraged it into the everyday agile process of the team.
- Provided `OneRT` Linux feed management and reduced the overall average bundle size by **5%**.
- Designed and Developed NISH Asset Management System Backend with `Flask` and `Docker`, integrated into the company's WeChat mini-app using `RESTful` APIs vastly improved the management of the site assets and saved **10%** of the asset lost cost.
- Awards
    1. _2019 2nd Most Popular National Instruments Tech Week Project_

# Education

## Shanghai University - School of Computer Engineering and Science

**B.Sc. Computer Science** | **Sep 2015 - Jul 2019**

- Lecturer at Shanghai University Open-Source Community
- Awards
    1. _Excellent graduation thesis from Shanghai University_
    2. _Innovation and Entrepreneurship Scholarship of Shanghai University_
    3. _1st Prize of IoT Innovation and Entrepreneurship Competition of Shanghai University_
    4. _3rd Prize of the 4th Computer Application Ability Competition of Shanghai University_
    5. _Science and Innovation Star of Shanghai University Student Community_

# Portfolio

## `OceanProtect` - The Data Prtoection Solution by Huawei

- Served as Subsystem Architect, Feature SE, and DEG Leader for the `System Management & Protection Engine Business Team`. Acted as DE and FO for the `Protection Engine Team`, and as DE for both the `System Management Team` and the `Infrastructure Platform Team`
    1. Coding net contribution
       - Code submitted into `master` branch: Over 52.2K lines.
       - Valid code review comments: Over 561 `issues`.
    2. Fixed and resolved over 135 difficult or performance related issue tickets.
- Improved job scheduling performance by **10,400%**: Under peak concurrency, reduced job schedule initiation-to-execution time from over 35 minutes to less than 20 seconds, optimized time complexity from `O(n^2 * m)` to `O(n * m)`.
- Designed and developed a `Nutanix` backup plugin for `ProtectManager`, producing over 3.3K lines of code in 3 days, with 0 defects during testing.
- Designed and developed the `OceanProtect` Four-Eyes Authentication / MPA (Multi-Person Authorization) module, enabling the `OceanProtect` product to meet multiple regulatory and certification requirements across China and the European Union.
- Proposed over 9 architecture improvement suggestions and led more than 22 performance optimizations
    1. Refactored the `VMware` backup plug-in scanning logic of `ProtectManager`, improving performance by **1,100%**: reduced the scan time for a 10,000-VM cluster from 2 hours to 10 minutes.
    2. Optimized the `Redis` memory usage efficiency of the copy archival jobs by **3,557%**: reduced memory consumption of the archival job queue for 10,000 copies from 2 GB to 56 MB.
    3. Optimized the performance of batch job cancellation by **11,900%**: improved processing speed from over 1 minute per job to 0.5 seconds per job, with support for 10-way concurrency.
    4. Optimized the performance of batch copy deletion job delivery by **1,900%**: improved execution efficiency from over 1 minute per job to 3 seconds per job, with support for 10-way concurrency.
    5. Optimized copy summary query performance by **37,400%**: improved million-copy queries from immediate OOM to returning results within 5 seconds, and reduced 200,000-copy query time from 5 minutes to 0.8 seconds.
    6. Optimized log export performance by **19,900%**: reduced page response time under heavy-load scenarios from 3 minutes to within 0.9 seconds.
    7. Optimized the upgrade speed of the `protectmanager-system-base` and `protectmanager-biz-service` pods by **1,000%**: reduced the pod upgrade process from 12 minutes to 90 seconds.
    8. Refactored the backup job delivery workflow for virtual machine groups, improving delivery speed by **13,400%**: reduced full-scale VM group backup job delivery time from 1.5 hours to 40 seconds.
    9. Optimized the progress reporting mechanism for virtual machine group backup jobs. Through database operation improvements and finer-grained locks and transactions, resolved the issue where lock timeouts during reporting caused job status to remain unchanged for an hour and then fail automatically.
    10. Refactored the alarm and event dump mechanism, improving performance by **246,757%**: reduced the dump time for 4 million alarm/event records from 24 hours to 35 seconds.
    11. Designed and refactored the heartbeat reporting logic of the backup agent, increasing the number of agents managed per node by **1,000%**.

## Distributed Object Store Management by Mixed Recursive Cloud Delegation

- Provided a self-recursive and cost-effective solution to provide a service in that users can store objects to multiple storage solutions while using a unified interface.
- Typical singleton deployment could be a Cloud Drive fusion service.
- Typical cluster deployment could be a self-recursive object storage cloud that could both hold local storage and delegate storage to other cloud services.

## `DT Automation` and `Fortress-Diag`

- Scrum Lead of `OSA Fortress` team.
- Participated in the development of an automatic diagnosis and repair framework for the `DT` module called `DT Automation`.
- Participated in the integration of `qTest` and existing `Jenkins` `CI`/`CD` framework.
- Tech Stack: `Python` + `Java` + `qTest` + `Jenkins` + `Docker`

## `ECS` and `OBS` - `Elastic Cloud Storage` and `ObjectScale`

Project Link: [https://www.dell.com/en-us/dt/storage/ecs/index.htm](https://www.dell.com/en-us/dt/storage/ecs/index.htm)

- Scrum Lead of `OBS Metadata Layer 1` team.
- Released 2 US patents and 2 Chinese patents.
- Developed a dumping algorithm and sped up the `ECS`/`OBS` `DT` write performance by **15%**.
- Developed a storage data structure that saved the storage space by **5%** and sped up the object serialization efficiency by **7%**.
- `OBS` is the `Kubernetes` deployment version of `ECS` and the future of `ECS`.
- Tech Stack: `Java` + `Spring` + `ProtoBuf` + `Kubernetes` + `Docker` + `Jenkins` + `Grafana`

## `andgpu-pro` and `gim`

- Fixed over 160 tickets for Linux KMD `amdgpu-pro` and `gim` in 1 year (normally, people fix 5 to 6 tickets per month)
- Helped tech lead to improve the pass rate of the Virtualization Automatic Test System from **75%** to **95%**.
- Designed and implemented a state machine to coordinate VM render requests and improve virtualization performance from **60%** to **80%**. (Ps. Virtualization performance = `sum(VM_FPS)/Bare_Metal_FPS`)
- Tech Stack: `C` + `Linux Kernel` + `SR-IOV` + `qemu` + `KVM`

## LiCMS - Li Xin Content Management System

GitHub Link: [https://github.com/realJustinLee/LiCMS](https://github.com/realJustinLee/LiCMS) | Online Preview: [https://www.1a2.org](https://www.1a2.org)

- Designed and developed a full-stack Content Management System that allows people to use it as a blog system.
- Implemented the front-end interface with both the `RESTful` API solution, website solution (based on `Bootstrap5`) and Two-Factor Authentication.
- Implemented the backend module with `Flask` and `SQLAlchemy` to provide a lightweight and database-independent system. Containerized the app using `Docker`.
- Implemented multiple running environments (`Linux`, `Docker`, and `Heroku`).
- Tech Stack: `Python` + `Flask` + `MySql` + `Docker` + `BootStrap`

## LiAg - Li Xin Avatar Generator

GitHub Link: [https://github.com/realJustinLee/LiAg](https://github.com/realJustinLee/LiAg) | Online Preview: [https://liag.1a2.org](https://liag.1a2.org)

- Designed and developed a 3D modeling system with `WebGL` and `React.js` for people to model their favorite movie avatars and print them with a 3D printer.
- Developed the interface system with `React.js` and webpage 3D modeling and rendering with `WebGL`. Containerized the app using `Docker`.
- Extended and Developed a custom `STLExporter` to fuze every model fragment into one 3D model and reduced the output `STL` model file size by **30%**.
- Tech Stack: `JavaScript` + `React.js` + `Three.js` + `WebGL` + `Docker`
