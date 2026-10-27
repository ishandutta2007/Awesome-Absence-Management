# Awesome-Absence-Management
**Top Absence Management (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Leave Tracking, PTO Accrual, Compliance Automation & Employee Self-Service*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Absence Management**. These tools enable organizations to manage employee leave requests, track time-off balances, automate accrual calculations, ensure regulatory compliance, and provide managers with visibility into workforce availability—from fully managed enterprise suites with built-in payroll and HRIS to self-hosted applications that give teams complete control over their data and infrastructure.

**Examples** include Workday Absence Management, UKG Ready, ADP Workforce Now, Timetastic, Factorial, BambooHR, AbsenceSoft, Replicon, and Paycom (the category leaders in commercial space).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, leave tracking, and open HR infrastructure—ideal for developers, HR teams, and organizations seeking transparent, vendor-independent absence management.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Workday Absence Management](https://www.workday.com/)**
  **Enterprise-grade absence and leave tracking** integrated with Workday HCM. **Pricing**: Quote-only; Absence module licensed separately per full-time equivalent (FSE) at approximately $6/FSE/year according to third-party estimates . **Free tier**: None. **Best for**: large enterprises already on Workday seeking deep integration between absence, time tracking, and payroll .

- **[UKG Ready](https://www.ukg.com/)**
  **All-in-one HR, payroll, and workforce management** for small to midsize organizations. Includes Leave Manager for automating federal, state, and organization-specific leave policies with self-service tools . **Pricing**: Quote-only; UKG recommends contacting sales for personalized bundle guidance . **Free tier**: None. **Best for**: SMBs wanting bundled HR, payroll, and leave management without replacing their platform as they grow .

- **[ADP Workforce Now](https://www.adp.com/)**
  **Comprehensive HR and payroll platform** with integrated time and attendance. Time tracking supports badge swipes, PINs, biometrics, and geo-fencing, with automatic payroll integration . **Pricing**: Quote-only; implementations may involve substantial configuration work . **Free tier**: None. **Best for**: organizations already using ADP payroll wanting unified time, attendance, and leave data .

- **[Timetastic](https://timetasticapp.com/)**
  **Simple and affordable PTO tracking** with burnout alerts and Slack/Teams integration. **Pricing**: **Standard** at $1.50/user/month; **Pro** at $2.50/user/month adds burnout alerts, accrued leave, capped leave types, and SSO . **Free tier**: 30-day free trial, no credit card required. **Best for**: small teams wanting paperless vacation planning without HR suite complexity.

- **[Factorial](https://factorial.com/)**
  **Modern HR platform** with leave management and shift planning. Automatically syncs approved absences with shift schedules, adjusting balances by hours or days . **Pricing**: Starting around $8/user/month according to third-party listings . **Free tier**: Trial available. **Best for**: SMBs wanting HR and leave management in a single modern interface.

- **[BambooHR](https://www.bamboohr.com/)**
  **HR platform with dedicated Time Off management**. Features custom policy builder, accrual calculator, Who's Out calendar, and mobile request/approval . **Pricing**: Quote-only; a $125 monthly account management fee applies in certain payroll maintenance scenarios . **Free tier**: None. **Best for**: SMBs wanting polished time-off tracking with strong employee self-service .

- **[AbsenceSoft](https://absencesoft.com/)**
  **Specialized leave of absence management** platform with Compliance Engine covering 200+ state and federal leave laws . Automates eligibility calculations, communications, and case management. **Pricing**: Quote-only; no free trial or free version . **Free tier**: None. **Best for**: organizations with complex FMLA/ADA compliance needs requiring dedicated leave administration .

- **[Replicon](https://www.replicon.com/)**
  **Time tracking and leave management** with global compliance focus. Supports country-specific rules including France part-time leave deductions and Brazil vacation validations . **Pricing**: Starting around $6/user/month according to third-party listings . **Free tier**: Trial available. **Best for**: global teams needing labor law compliance across multiple jurisdictions.

- **[Paycom](https://www.paycom.com/)**
  **Full HCM with built-in time-off requests** and PTO balance visibility via mobile app . **Pricing**: Quote-only; third-party estimates place full-suite at $25–$36 PEPM . Implementation fees typically 10–30% of annualized contract value . **Free tier**: None. **Best for**: organizations wanting payroll, HR, and leave management from a single vendor.

- **[LeaveStar](https://www.leavestar.com/)**
  **Dedicated absence management platform** for tracking employee leaves, FMLA, and return-to-work processes. **Pricing**: Quote-only; contact vendor for demo and pricing. **Free tier**: None. **Best for**: HR teams needing focused leave administration without full HRIS overhead.

## Open-Source GitHub Projects

- **[TimeOff.Management](https://github.com/timeoff-management/timeoff-management-application)**
  **Simple yet powerful absence management software for small and medium businesses** (MIT) — **the most popular dedicated open-source leave tracker** with ~922 GitHub stars . **Features**: Leave request/approval workflow, allowance tracking, department calendars, and email notifications. **Tech stack**: Node.js, Express, Sequelize, SQLite/PostgreSQL/MySQL. **Deploy**: Docker, YunoHost package available. **Best for**: teams wanting a focused, self-hosted PTO tracker without HR suite bloat.

- **[Frappe HR](https://github.com/frappe/hrms)**
  **Open-source HR and payroll suite** (GPL-3.0) with comprehensive Leave and Attendance module. **Features**: Configurable leave policies, regional holiday import, leave balance tracking, attendance with geolocation check-in, and mobile app for leave applications . **Tech stack**: Python (Frappe Framework), Vue.js (Frappe UI). **Deploy**: Self-hosted or Frappe Cloud. **Best for**: organizations wanting a full HRMS where leave management integrates with payroll and employee lifecycle .

- **[Skapp](https://github.com/SkappHQ/skapp)**
  **Open-source people management and HR platform** (AGPL-3.0) for growing teams. **Features**: Leave management, attendance tracking with clock in/out, timesheet management, and people directory . **Award**: Gold Award Winner at APICTA 2025. **Tech stack**: React, TypeScript, Tailwind (frontend); Node.js, NestJS (backend); Docker/Kubernetes ready. **Best for**: startups wanting a modern, actively maintained HR platform with leave as a core module .

- **[MintHCM](https://github.com/minthcm/minthcm)**
  **Free, open-source Human Capital Management system** (GPL-3.0) installable on your own server. **Features**: Leave and attendance tracking with real-time visibility, performance management, training, and document management . **Tech stack**: PHP (SugarCRM-based). **Deploy**: Self-hosted; mobile companion app available. **Best for**: organizations wanting a CRM-adjacent HCM with leave management and no per-user fees.

- **[AlekSIS-App-Kolego](https://github.com/AlekSIS-App-Kolego)**
  **School Information System module for staff and absence management** (AGPL-3.0). **Note**: This is an **education-specific absence management tool**, not a general HR leave tracker. **Best for**: schools and educational institutions managing teacher and staff absences within the AlekSIS ecosystem .

### Additional Strong Open-Source Options

- **OrangeHRM** — Open-source HR management system (GPL-2.0). Includes Leave module with configurable leave types, accrual rules, and approval workflows. **Best for**: organizations wanting a full HRIS with leave tracking and no license fees.
- **Sentrifugo** — Open-source HRMS (GPL-3.0). Includes leave management with multi-level approval and balance tracking. **Best for**: teams wanting a PHP-based HRMS with leave as part of a broader suite.
- **IceHrm** — Open-source HR management (Apache-2.0). Features leave management, attendance, and employee self-service. **Best for**: small teams wanting a lightweight, self-hosted HR solution.
- **CoreLog** — Lightweight employee attendance tracking with optional face recognition (MIT, per repo). **Note**: Primarily attendance check-in/out, not leave request management. **Best for**: organizations needing basic attendance logging with anti-buddy-punching .

**Frameworks for building custom systems**: Combine **TimeOff.Management** for focused PTO tracking with **Frappe HR** for full HRMS integration, **Skapp** for a modern React-based people platform, and **MintHCM** for CRM-integrated HCM—creating a comprehensive absence management stack matched to each organization's constraints.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Absence management platforms handling employee health and leave data must comply with data protection regulations (GDPR, HIPAA where applicable, CCPA, etc.) and implement appropriate access controls.
- **The "specialized leave platform vs. full HR suite" distinction matters.** **AbsenceSoft, LeaveStar, and Timetastic** focus narrowly on leave/PTO—faster to deploy, but limited beyond absence workflows. **Workday, UKG, ADP, and Paycom** bundle leave into full HCM suites—more integrated, but heavier implementation and higher cost. **Choose based on whether leave is a standalone problem or one module of a larger HR strategy.**
- **TimeOff.Management is the clear open-source leader for pure absence tracking.** ~922 GitHub stars, MIT licensed, Node.js stack, and a focused feature set . **The trade-off**: minimal payroll integration, no built-in compliance engine for FMLA/ADA, and requires self-hosting maintenance. **Frappe HR** is the better open-source choice when leave must integrate with payroll and employee lifecycle .
- **Compliance depth varies dramatically.** **AbsenceSoft** claims coverage of 200+ leave laws with automated eligibility calculation . **Replicon** emphasizes country-specific rules for France, Brazil, and Ireland . **Open-source tools generally lack built-in regulatory compliance engines**—you configure policies manually and assume compliance risk yourself. **If FMLA/ADA/statutory compliance is critical, budget for either a specialized SaaS or significant internal configuration.**
- **Pricing transparency is poor across enterprise vendors.** Workday, UKG, ADP, BambooHR, AbsenceSoft, LeaveStar, and Paycom all require sales contact for quotes. Timetastic is the exception with public per-user pricing . **Third-party estimates for enterprise tools vary widely and should be validated with direct vendor conversations.**
- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Absence data is sensitive**—ensure your hosting meets your organization's security and privacy requirements before deploying.

---

**Made for developers, HR teams, and organizations building transparent absence management solutions.**
Let's make Absence Management more open, data-driven, and employee-friendly.
