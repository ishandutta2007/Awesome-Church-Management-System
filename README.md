# Awesome-Church-Management-System

## Top Church Management System (ChMS) Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Congregation Management, Giving & Donations, Event Planning & Volunteer Coordination*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Church Management Systems (ChMS)**. These tools help churches, ministries, and faith-based organizations manage member databases, track contributions, coordinate volunteers, plan events, and communicate with their congregations.



**Examples** include Planning Center, Faithlife, Church Community Builder (Pushpay), Breeze ChMS, FellowshipOne, Tithe.ly ChMS, Realm, Elvanto, ChurchTrac, Servant Keeper, Rock RMS, and TouchPoint (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom ministry workflows, and transparent member data — ideal for churches that need full control over their congregation data without per-member SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Planning Center](https://www.planningcenter.com/)**  

  The most widely adopted ChMS platform, used by over 70,000 churches. Modular architecture with separate products for People (member database), Services (volunteer scheduling), Giving (donations), Check-Ins (children's ministry), Groups, and Registrations. Known for excellent volunteer scheduling and worship team planning tools.



- **[Faithlife](https://faithlife.com/)**  

  Church management platform (formerly Logos Bible Software ecosystem). Integrates church management, giving, and community features with Bible study tools and Logos integration.



- **[Church Community Builder (Pushpay)](https://www.pushpay.com/)**  

  Comprehensive ChMS with member management, giving, groups, volunteer scheduling, and communication tools. Acquired by Pushpay and integrated into their giving platform.



- **[Breeze ChMS](https://www.breezechms.com/)**  

  Simple, affordable church management system popular with small to mid-sized churches. Provides people management, giving tracking, volunteer scheduling, and check-in.



- **[FellowshipOne](https://www.fellowshipone.com/)**  

  Enterprise ChMS for larger churches and multi-site ministries. Provides member management, contributions, groups, check-in, and reporting.



- **[Tithe.ly ChMS](https://get.tithe.ly/)**  

  Giving-focused church management platform. Combines online giving, member management, and communication tools in an affordable package.



- **[Realm](https://www.onrealm.org/)**  

  Church management software from ACS Technologies. Provides member management, giving, groups, events, and communication for churches of all sizes.



- **[Elvanto](https://www.elvanto.com/)**  

  Cloud-based church management and volunteer rostering platform. Strong scheduling and communication features, popular in Australia and the UK.



- **[ChurchTrac](https://www.churchtrac.com/)**  

  Affordable church management software. Provides member management, giving, attendance, and accounting features at accessible price points.



- **[Servant Keeper](https://www.servantkeeper.com/)**  

  Church management software with a focus on member records, contributions, and ministry tracking. Available as desktop or cloud.



## Open-Source GitHub Projects



- **[Rock RMS](https://github.com/SparkDevNetwork/Rock)**  

  **The most mature and widely deployed open-source ChMS.** An open-source CMS, Relationship Management System (RMS), and Church Management System all rolled into one . **684 stars, 415 forks** on the main SparkDevNetwork/Rock repository, with recent updates as of September 2026 . Built in **C#** (.NET). Provides comprehensive functionality: person and family records, groups, check-in, contributions, communications, workflows, and a powerful **Lava templating engine** for customization . **Extensive ecosystem** with migration tools (Slingshot, Bulldozer), WordPress integration (ft-rockpress), VS Code syntax extensions, SendGrid transport, and Ruby API wrappers . Used by churches of all sizes including NewPointe Community Church. **Open source**.



- **[ChurchCRM](https://github.com/ChurchCRM/CRM)**  

  **The second most adopted open-source ChMS with 631 stars and 445 forks.** Free, open-source church management software to help congregations manage membership data, groups, events, and finances . Written in **PHP** (86.2% of codebase), with JavaScript, TypeScript, and Twig components . **1,400+ commits** across 59 contributors . Supports **40+ languages** through localization efforts on poeditor.com . Modern **Docker image** (kolumbus120/churchcrm) with PHP 8.4, auto-updates every Tuesday and Friday, multi-architecture support (amd64/arm64), and environment-variable configuration . Features member management, groups, events, finances, and communication tools . **Open source**.



- **[B1Admin](https://github.com/ChurchApps/B1Admin)**  

  **Completely free, open-source church management software** with a modern, comprehensive feature set . Provides member and guest information tracking, attendance management with **self check-in app**, group coordination, **donation tracking with detailed reports**, and **custom form creation** . **Self-hosting in beta** with Docker Compose: `docker compose up -d` brings up B1Admin, member portal, API, and MySQL database . Supports **Stripe, PayPal, and KingdomFunding** payment gateways for online donations . Frontend built with **Next.js/React** (npm-based development workflow). **Open source**.



- **[Corpus Christi](https://github.com/corpus-christi/corpus-christi)**  

  **Open-source, fully internationalized church management suite** developed under the **Center for Missions Computing at Taylor University** . Three core modules: **groups** (Home Church management and tracking), **courses** (Teaching ministry management), and **events** (Event planning and registration). Built with **Vue** . **30 stars, 7 forks** . Focused on simplicity and internationalization for missions contexts. **Open source**.



- **[IES Church Management System](https://github.com/Goldwin/ies-pik-cms)**  

  **Open-source alternative for church management applications.** Explicit goal: **"provide cheaper alternatives to small churches that can't afford to use paid software to manage the church"** . Built in **Go** with modular architecture (`SERVICE_MODULES=AUTH,PEOPLE,EVENTS`). Uses **MongoDB** for data persistence and **Redis** for caching . Features authentication (with email OTP), people management, and events modules. Environment-variable configuration for deployment. **Open source**.



- **[EcclesiaCRM](https://github.com/phili67/ecclesiacrm)**  

  **CRM software for church management** with **42 stars and 21 forks** . PHP-based, **514 MB repository** . Active development with recent updates. Provides church CRM functionality including member management and relationship tracking. **Open source**.



- **[MinistryX](https://github.com/CrazyCoder254/MinistryX)**  

  **Full-stack church management website** written primarily in **PHP** . Features adding new church members, districts, church events, fundraising activities, and a fully-fledged calendar of activities . **10,400 commits** . Built on ChurchCRM foundation with customizations. **Open source**.



- **[jornada](https://github.com/fabianoaljava/jornada)**  

  **Church Management System designed to help churches using web-based solutions manage everyday processes.** **JavaScript-based** (26.3 MB) . **Open source**.



### Additional Strong Open-Source Options



- **Mature Platforms**: **Rock RMS** (C#, most mature, extensive ecosystem), **ChurchCRM** (PHP, 631 stars, 40+ languages) .

- **Modern Stacks**: **B1Admin** (Next.js/React, Docker self-hosting, payment gateways), **Corpus Christi** (Vue, Taylor University) .

- **Lightweight/Go**: **IES Church Management System** (Go + MongoDB, small church focus) .

- **CRM-Focused**: **EcclesiaCRM** (PHP, 42 stars) .

- **Migration Tools**: **Slingshot** (Rock RMS migration), **Bulldozer** (multi-system conversion) .



**Frameworks for building custom systems**: Combine **Rock RMS** for a mature, feature-rich ChMS with extensive ecosystem, **ChurchCRM** for a proven PHP-based solution with broad language support, **B1Admin** for a modern Next.js/React stack with Docker deployment, and **Corpus Christi** for a lightweight, internationalized suite. Add **PostgreSQL** or **MySQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Church management platforms handle sensitive member and giving data; ensure compliance with data protection regulations and internal policies.

- **Open-source reality**: The open-source ecosystem for church management is **mature and production-ready**. **Rock RMS** is a full-featured, widely adopted platform with an extensive ecosystem of extensions and migration tools . **ChurchCRM** provides a proven, PHP-based solution with 40+ language support and modern Docker deployment . **B1Admin** offers a modern React/Next.js alternative with self-hosting support and payment gateway integrations . **Corpus Christi** delivers a lightweight, internationalized suite from Taylor University . For churches seeking a free, self-hosted ChMS, these open-source options are **genuinely viable alternatives** to commercial platforms like Planning Center and Breeze.



---



**Made for church administrators, ministry leaders, IT volunteers, and faith-based organization technologists.**

Let's make church management more open, transparent, and ministry-focused.
