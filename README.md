# Awesome-Employee-Engagement-Platform

## Top Employee Engagement Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Engagement Surveys, Pulse Feedback & Employee Experience Analytics*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Employee Engagement Platforms**. These tools enable organizations to measure employee sentiment, run pulse surveys, collect anonymous feedback, and analyze engagement drivers—helping leaders understand what keeps employees motivated and what drives them away.



**Examples** include Workday Peakon Employee Voice, Culture Amp, Lattice, Glint, Qualtrics EmployeeXM, 15Five, Perceptyx, Leapsome, Officevibe, and Workvivo (the category leaders).



**Open-source emphasis**: Employee Engagement is a domain where open-source tooling is **sparse and early-stage**. The strongest active project is **Alignify**, an AI-powered anonymous survey platform with automated question generation and sentiment classification using Qwen and DistilBERT . **Check-Ins** (Object Computing) provides a broader team engagement platform including pulse surveys and feedback management . However, no open-source platform matches the sentiment analytics depth, benchmark data, and action-planning workflows of Workday Peakon or Culture Amp. Organizations requiring sophisticated engagement analytics should plan for commercial platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Workday Peakon Employee Voice](https://www.workday.com/)**  

  AI-powered employee engagement platform with scalable pulse surveys, NLP sentiment analytics for open-ended comments, and benchmark data; users praise its scalability for global directories and real-time data aggregation.



- **[Culture Amp](https://www.cultureamp.com/)**  

  Employee experience platform with engagement surveys, sentiment analysis, heat maps, and AI coaches; users report that native AI analysis eliminates the need for external tools to summarize verbatim comments.



- **[Lattice](https://lattice.com/)**  

  Performance and engagement platform with surveys, goals, 1:1s, and continuous feedback; AI capabilities reduce review preparation time and encourage consistent feedback.



- **[Glint (Microsoft Viva)](https://www.microsoft.com/en-us/microsoft-viva)**  

  Employee engagement platform integrated into Microsoft Viva; convenient for organizations already using Microsoft 365 and Teams, providing engagement insights within the productivity ecosystem.



- **[Qualtrics EmployeeXM](https://www.qualtrics.com/)**  

  Enterprise experience management platform with employee engagement surveys and analytics; users note the dashboard is straightforward for HR teams but API data export can be messy for technical teams.



- **[15Five](https://www.15five.com/)**  

  Performance management with weekly check-ins, engagement surveys, and manager-employee conversations.



- **[Perceptyx](https://www.perceptyx.com/)**  

  Employee listening platform with surveys, analytics, and action planning for enterprise organizations.



- **[Leapsome](https://www.leapsome.com/)**  

  Comprehensive performance management with goals, engagement surveys, and development features.



- **[Officevibe](https://officevibe.com/)**  

  Employee engagement platform with pulse surveys, eNPS scoring, anonymous feedback, and team insights (now part of Workleap).



- **[Workvivo](https://www.workvivo.com/)**  

  Employee communication and engagement platform (acquired by Zoom) with social feeds, recognition, and surveys.



## Open-Source GitHub Projects



- **[Alignify](https://github.com/iam-tsr/alignify)**  

  AI-powered employee engagement platform (early beta) with anonymous survey collection; uses **Qwen model for automated question generation** (~8 seconds for 10 questions) and **DistilBERT for feedback sentiment classification** (~2 seconds per classification); management dashboard provides graphical insights and AI-generated improvement suggestions . Python/CSS/JavaScript stack with Dockerfile included. **The most purpose-built open-source employee engagement tool** with genuine AI automation, though early-stage with a single contributor.



- **[Check-Ins](https://github.com/objectcomputing/check-ins)**  

  Comprehensive open-source team engagement platform built on Micronaut and React, deployable on-premises or GCP; features **Pulse Surveys** for gauging team sentiment, feedback management, performance reviews, public Kudos, skill tracking, and mentor program management . Actively used at Object Computing. **Broader HRIS/engagement suite** rather than engagement-specific, but includes core pulse survey functionality.



- **[Good Job](https://github.com/dongitran/Good-Job)**  

  Open-source employee recognition and reward platform (React/NestJS/PostgreSQL); features peer-to-peer kudos with points tied to core values, dual-balance points system (giveable + redeemable), reward catalog with stock tracking, admin analytics for engagement metrics, and real-time feed via SSE . **Recognition-focused** rather than survey-based engagement, but addresses a key engagement driver (appreciation) with a modern, well-tested stack (170 E2E tests).



- **[Plugiva Pulse](https://wordpress.org/plugins/plugiva-pulse/)**  

  Lightweight open-source WordPress plugin for creating quick feedback forms and polls; supports yes/no, emoji, or short text questions with AJAX-powered frontend, CSV export, and privacy-conscious local data storage . **Minimal but functional**—suitable for WordPress-based intranets needing simple pulse collection without a dedicated platform.



### Additional Strong Open-Source Options



- **employee-pulse-survey-enps-engine** — Open-source enterprise pulse survey platform (Python/FastAPI) for weekly sentiment feedback, eNPS calculation, and burnout trend identification; includes Docker and CI/CD workflows . **Early-stage** with no community traction (0 stars), but demonstrates the architecture for an eNPS engine.

- **PulseForms** — Open-source survey platform (Django/MySQL) with role-based access, conditional logic, and statistics/CSV export . **General survey tool** that can be configured for employee pulses, but not purpose-built for engagement.

- **eXo Platform** — Open-source digital workplace with employee recognition and engagement features; starting at $3/user/month for the supported edition . **Broader digital workplace** rather than a dedicated engagement platform.



**Frameworks for building custom systems**: **Alignify** provides the most focused open-source foundation for anonymous engagement surveys with AI sentiment classification . **Check-Ins** provides a broader engagement platform including pulse surveys and feedback . **Good Job** addresses recognition as an engagement driver with a well-architected points system . A complete engagement platform would require combining survey collection (Alignify or Plugiva Pulse), sentiment analytics (Alignify's DistilBERT or custom NLP), and action planning workflows—with no single open-source platform providing the full lifecycle.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Employee engagement platforms handling sensitive feedback data must comply with applicable privacy regulations (GDPR, CCPA) and organizational data governance policies; **anonymity guarantees are critical**—employees must trust that their feedback cannot be traced back to them.

- **Open-source employee engagement remains early-stage**—Alignify provides AI-powered anonymous surveys but is in beta with a single contributor ; Check-Ins provides broader engagement features but less engagement-specific analytics . No open-source platform matches Workday Peakon's NLP sentiment depth or Culture Amp's benchmark data. Organizations requiring enterprise-scale engagement analytics should budget for commercial platforms.

- Verify license terms for commercial use; Alignify and Check-Ins are open-source (check repositories), Good Job is open-source, and Plugiva Pulse is a WordPress plugin.



---



**Made for HR leaders, engagement managers, people analytics teams, and employee experience practitioners.**  

Let's make employee engagement more open, anonymous, and action-oriented.
