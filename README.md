<div align="center">

# 🎓 Summer 2027 Tech Internships

**A self-updating engine that tracks tech internships so you don't have to.**

[![CI](https://img.shields.io/github/actions/workflow/status/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/ci.yml?branch=main&label=tests&style=flat-square&color=3fb950)](https://github.com/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/actions/workflows/ci.yml)&nbsp;[![Open roles](https://img.shields.io/badge/dynamic/json?label=open%20roles&query=open_total&url=https%3A%2F%2Fheyinihere.github.io%2FAutomated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships%2Fapi%2Fstats.json&color=2f81f7&style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/)&nbsp;![Updates](https://img.shields.io/badge/updates-every%20hour-3fb950?style=flat-square)&nbsp;[![RSS](https://img.shields.io/badge/RSS-subscribe-e67e22?style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/feed.xml)

### 590 open roles (399 listed below) · 314 new this week

4,277 employers tracked · updated Sep 02, 2026 at 23:18 UTC

_323 have a cycle the employer stated · 267 are recent postings whose cycle isn't stated (listed separately, never mixed in)._

**[🖥️ Live dashboard](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/)** · **[📡 RSS](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/feed.xml)** · **[⚙️ JSON API](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/api/jobs.json)** · **[✉️ Email alerts](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/#subscribe)**

</div>

> [!TIP]
> **⭐ Star this repo** to save it and get updates when new roles are added.

Instead of refreshing a dozen career pages by hand, it reads company hiring feeds directly and keeps one live list, newest roles on top, refreshed automatically throughout the day.

**🔔 New roles in your inbox:** [subscribe by email](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/#subscribe) - one email a day, only when new internships actually appeared, unsubscribe from any email in two clicks. (Prefer RSS-to-email? [Feedrabbit works too](https://feedrabbit.com/subscriptions/new?url=https%3A%2F%2Fraw.githubusercontent.com%2FHeyIniHere%2FAutomated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships%2Fmain%2Fdocs%2Ffeed.xml).)

---

## What this is

This is an engine, not a hand-kept list. It polls company career feeds several times a day, finds the internships, removes duplicates, and rebuilds this page on its own. Every link comes straight from the source, so it's real and current, not a stale list someone forgot to update (speed matters).

## What makes this different

- **📅 [Drop Radar](#drop-radar)** - a forecast of **what's coming**: each marquee company's typical opening window, replaced by the real drop date the moment the engine catches it live. Windows are estimates and labelled as such; only dates the engine observed itself are marked verified.
- **Visa intel, computed** - 🇺🇸 / 🛂 flags detected automatically from every job description, plus ✓ for employers with a real H-1B track record (official USCIS data, FY2022-23 - a history, not a promise). The big lists crowdsource this by hand; here it's code. Most postings say nothing either way, and those are shown as unknown rather than guessed.
- **A date on nearly every role** - taken from the job portal itself where the portal states one, so newest-first actually means newest. The exact coverage figure is printed at the bottom of this page every run.
- **Skill tags + pay, extracted** - every posting's text is scanned for the stack it wants (Python, C++, PyTorch, ...) and the pay it states - searchable on the [dashboard](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/), included in the CSV and API.
- **Alerts your way** - [email digests](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/#subscribe) or [RSS](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/feed.xml) (point any reader, or a Slack/Discord RSS integration, at it) - plus a [live dashboard](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/) with search, filters, and a saved-roles list that never leaves your browser.
- **An engine, not a spreadsheet** - 4,382 job-board endpoints (4,277 distinct employers; some run more than one board) polled every hour across 12 ATS platforms, full source and tests in this repo.

## Scope

| | |
|---|---|
| **Roles** | Software Engineering, Data Science & Machine Learning (and closely related technical internships) |
| **Region** | United States |
| **Cycles** | Summer 2027 and Fall 2026 |

## About

I'm an international student studying in the United States, so I built this for the search I'm doing myself. The list is US roles only for now - that's where I'm searching. Use it to spot roles early and apply before they fill up - being first genuinely helps.

## Where this is going

I'm building this in the open and adding to it as it grows. Recently shipped: **email alerts**, the **Drop Radar**, **auto-detected sponsorship flags**, and the **live dashboard**. Next up: personalized alerts (pick your categories), per-company hiring pages, and a ghost-posting detector. If it helps you, a star means a lot and tells me to keep going.

## How to use

<details>
<summary><b>Reading the table — flags, dates, and the cycle split</b> (click to expand)</summary>

- Roles are grouped by cycle below - **newest posting on top, oldest at the bottom.**
- A cycle section holds only roles whose **employer stated that cycle** - in the title, or in the posting's own text. Postings that name no cycle anywhere are in *Recently posted — cycle not stated* further down, with **no cycle guessed for them**. Same quality bar, different amount of evidence.
- The **Posted** column is the date the company published the role.
- **Flags:** 🇺🇸 = requires U.S. citizenship or a security clearance · 🛂 = the posting says it won't sponsor a work visa · 🏠 = the location says remote · 🆕 = spotted in the last 48 hours. Sponsorship flags are detected automatically from each job description - treat them as a strong hint and confirm on the posting.
- **✓ after a company name** = a real H-1B track record: USCIS approved 10+ petitions for that employer in FY2022–2023 (matched automatically against the official [H-1B Employer Data Hub](https://www.uscis.gov/tools/reports-and-studies/h-1b-employer-data-hub)). No ✓ doesn't mean they won't sponsor - it means we can't prove they have.
- Track your applications with [`data/internships.csv`](data/internships.csv) (opens in Excel / Google Sheets).
- Missing a company? Adding one takes a single line, see [CONTRIBUTING.md](CONTRIBUTING.md).

</details>

---

## Summer 2027  (194 employer-stated)

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| General Motors ✓ | 2027 Summer Intern – Manufacturing Engineering – Body Center 🆕 | Hardware | Warren +2 more | Sep 02, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Warren-Michigan-United-States-of-America/XMLNAME-2027-Summer-Intern---Manufacturing-Engineering---Body-Center_JR-202619475) |
| General Matter | Summer 2027 Internship - Embedded Software Engineering 🆕 | Software | Los Angeles, CA | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/generalmatter/jobs/5377131008) |
| ABB ✓ | Mechanical Design Engineer Intern- Summer 2027 🛂 🆕 | Hardware | Fort Smith +2 more | Sep 02, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Fort-Smith-Arkansas-United-States-of-America/Mechanical-Design-Engineer-Intern--Summer-2027_JR00045727) |
| Allied Solutions | AI Solutions Intern 🆕 | Data & ML/AI | Carmel, IN | Sep 02, 2026 | [Apply](https://alliedsolutions.wd501.myworkdayjobs.com/Allied_External/job/Carmel-IN/AI-Solutions-Intern_R-011074) |
| Allied Solutions | Data Science Intern 🆕 | Data & ML/AI | Carmel, IN | Sep 02, 2026 | [Apply](https://alliedsolutions.wd501.myworkdayjobs.com/Allied_External/job/Carmel-IN/Data-Science-Intern_R-011077) |
| Allied Solutions | Software Delivery Management Intern 🆕 | Software | Carmel, IN | Sep 02, 2026 | [Apply](https://alliedsolutions.wd501.myworkdayjobs.com/Allied_External/job/Carmel-IN/Software-Delivery-Management-Intern_R-011086) |
| United Parcel Service (UPS) | 2027 Industrial Engineering Summer Intern - Bayonne NJ 🇺🇸 🆕 | Hardware | US - BAYONNE CENTER (NJBAY) | Sep 02, 2026 | [Apply](https://hcmportal.wd5.myworkdayjobs.com/Search/job/US---BAYONNE-CENTER-NJBAY/XMLNAME-2027-Industrial-Engineering-Summer-Intern---Bayonne-NJ_R26030793) |
| United Parcel Service (UPS) | 2027 Industrial Engineering Summer Intern - Atlanta, GA 🇺🇸 🆕 | Hardware | US - UPS CORPORATE OFFICES (GACOR) | Sep 02, 2026 | [Apply](https://hcmportal.wd5.myworkdayjobs.com/Search/job/US---UPS-CORPORATE-OFFICES-GACOR/XMLNAME-2027-Industrial-Engineering-Summer-Intern---Atlanta--GA_R26030769) |
| HD Supply ✓ | Graduate Intern, Artificial Intelligence & Data Science - Summer 2027 🆕 | Data & ML/AI | Atlanta-GA-US | Sep 02, 2026 | [Apply](https://hdsupply.wd1.myworkdayjobs.com/External/job/Atlanta-GA-US/Graduate-Intern--Artificial-Intelligence---Data-Science---Summer-2027_R26004952) |
| Roblox ✓ | [Summer 2027] Product Management Intern 🆕 | Software | San Mateo, CA, United States | Sep 02, 2026 | [Apply](https://careers.roblox.com/jobs/8143981?gh_jid=8143981) |
| Grant Thornton ✓ | Cybersecurity and Privacy Intern - Summer 2027 🛂 🆕 | Security | Los Angeles, CA, United States | Sep 02, 2026 | [Apply](https://ehzq.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/115752) |
| Cigna Group | Artificial Intelligence Innovation Development Program (AIIDP) Summer Internship 🆕 | Data & ML/AI | NC +2 more | Sep 02, 2026 | [Apply](https://cigna.wd5.myworkdayjobs.com/cignacareers/job/NC-Raleigh-701-Corporate-Center-Dr-STE-200/Ai-Innovation-Development-Program--AIIDP--Summer-internship_26010712) |
| RTX | Software Engineering Co-op (Summer/Fall 2027) 🇺🇸 🆕 | Software | US-IA-CEDAR RAPIDS-105 ~ 400 Collins Rd… | Sep 02, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-105--400-Collins-Rd-NE--BLDG-105/Software-Engineering-Co-op--Summer-Fall-2027-_01870194) |
| United Parcel Service (UPS) | 2027 Industrial Engineering Summer Intern - Portland, OR 🇺🇸 🆕 | Hardware | US - PORTLAND HUB (ORPOR) | Sep 02, 2026 | [Apply](https://hcmportal.wd5.myworkdayjobs.com/Search/job/US---PORTLAND-HUB-ORPOR/XMLNAME-2027-Industrial-Engineering-Summer-Intern---Portland--OR_R26030709) |
| Northrop Grumman | 2027 Software Engineer Intern - Linthicum Maryland 🇺🇸 🆕 | Software | United States-Maryland-Linthicum | Sep 02, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Maryland-Linthicum/XMLNAME-2027-Software-Engineer-Intern---Linthicum-Maryland_R10248910) |
| AECOM ✓ | Structural Engineering Intern - Bridge & Transportation Structures 🆕 | Hardware | Glen Allen, VA, United States | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000146989469) |
| Auto-Owners Insurance | Business Intelligence Developer Internship - Summer 2027 🆕 | Software | Lansing, MI | Sep 02, 2026 | [Apply](https://aoins.wd5.myworkdayjobs.com/AutoOwners/job/Lansing-MI/Business-Intelligence-Developer-Internship---Summer-2027_R_14417) |
| Hermeus | Manufacturing Engineering Intern - Spring/Summer 2027 🇺🇸 🆕 | Hardware | Atlanta, GA | Sep 02, 2026 | [Apply](https://jobs.lever.co/hermeus/1bdf3754-5649-4a50-913e-b05140cb004f) |
| Hermeus | Structures/Mechanical Engineering Intern - Spring/Summer 2027 🇺🇸 🆕 | Hardware | Atlanta, GA | Sep 02, 2026 | [Apply](https://jobs.lever.co/hermeus/60b5d40a-1065-4bd2-8c72-6b2fb69d4761) |
| IAT Insurance Group | Cyber Security Internship 🛂 🆕 | Security | Raleigh NC | Sep 01, 2026 | [Apply](https://iatinsurancegroup.wd1.myworkdayjobs.com/iat/job/Raleigh-NC/Cyber-Security-Internship_JR100410) |
| Tarrant Regional Water District | Summer 2027 Infrastructure Engineering Intern (T036) 🆕 | Software | Fort Worth, TX | Sep 01, 2026 | [Apply](https://trwd.wd1.myworkdayjobs.com/TRWDCareers/job/Fort-Worth-TX/Summer-2027-Infrastructure-Engineering-Intern--T036-_JR100218) |
| General Motors ✓ | 2027 Summer Intern – Global Manufacturing Electrical & SDV 🆕 | Hardware | Warren +2 more | Sep 01, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Warren-Michigan-United-States-of-America/XMLNAME-2027-Summer-Intern---Global-Manufacturing-Electrical---SDV_JR-202619352) |
| General Motors ✓ | 2027 Summer Intern - Manufacturing Engineering— Global Propulsion Systems 🆕 | Hardware | Warren +2 more | Sep 01, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Warren-Michigan-United-States-of-America/XMLNAME-2027-Summer-Intern---Manufacturing-Engineering--Global-Propulsion-Systems_JR-202619351) |
| Northrop Grumman | 2027 Industrial Engineering Intern 🇺🇸 🆕 | Hardware | United States-Mississippi-Iuka | Sep 01, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Mississippi-Iuka/XMLNAME-2027-Industrial-Engineering-Intern_R10248838) |
| HP IQ | Software Engineering Intern, Connectivity (Summer 2027) 🆕 | Software | San Francisco, CA | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/hpiq/jobs/6176783004) |
| Hermeus | Software Engineering Intern (Modeling & Simulation) - Spring/Summer 2027 🇺🇸 🆕 | Software | Los Angeles, CA | Sep 01, 2026 | [Apply](https://jobs.lever.co/hermeus/445db430-6f81-41cf-847a-56a947afb936) |
| First National Bank ✓ | Summer 2027 AI/ML Modeler Intern 🛂 🆕 | Data & ML/AI | Pittsburgh, PA | Sep 01, 2026 | [Apply](https://fnbcorp.wd501.myworkdayjobs.com/FNBCORP/job/Pittsburgh-PA/Summer-2027-AI-ML-Modeler-Intern_2026-01851) |
| Johnson & Johnson | Software Engineering Co-Op. Summer 2027 🆕 | Software | Cincinnati +2 more | Sep 01, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cincinnati-Ohio-United-States-of-America/Software-Engineering-Co-Op-Summer-2027_R-096743) |
| Mondelez International | Manufacturing- Process Engineering Co-Op(For Naperville, IL Local Candidates Only) 🆕 | Hardware | Naperville, Illinois, United States | Sep 01, 2026 | [Apply](https://wd3.myworkdaysite.com/recruiting/mdlz/External/job/Naperville-Illinois-United-States/Manufacturing--Process-Engineering-Co-Op-For-Naperville--IL-Local-Candidates-Only-_R-176632) |
| Vermeer | IT Software Engineer Internship Summer 2027 🆕 | Software | Pella, Iowa, USA - Corporate Office | Sep 01, 2026 | [Apply](https://vermeer.wd5.myworkdayjobs.com/externalcareersite/job/Pella-Iowa-USA---Corporate-Office/IT-Software-Engineer-Internship-Summer-2027_REQ-22178) |
| General Matter | Summer 2027 Internship - Mechanical Engineering (HVAC) 🆕 | Hardware | Los Angeles, CA | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/generalmatter/jobs/5377104008) |
| Michael Baker International ✓ | Bridge Structural Intern 🆕 | Hardware | Chicago, IL, United States | Sep 01, 2026 | [Apply](https://ebxs.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/309794) |
| Booz Allen ✓ | University - 2027 Summer Games, Data Scientist Intern - Honolulu, HI 🇺🇸 🆕 | Data & ML/AI | Honolulu, HI | Sep 01, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/Honolulu-HI/University---2027-Summer-Games--Data-Scientist-Intern---Honolulu--HI_R0248406) |
| Booz Allen ✓ | University - 2027 Summer Games Cyber Security Intern - Honolulu, HI 🇺🇸 🆕 | Security | Honolulu, HI | Sep 01, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/Honolulu-HI/University---2027-Summer-Games-Cyber-Security-Intern---Honolulu--HI_R0248411) |
| Booz Allen ✓ | University - 2027 Summer Games Software Developer Intern - Honolulu, HI 🇺🇸 🆕 | Software | Honolulu, HI | Sep 01, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/Honolulu-HI/University---2027-Summer-Games-Software-Developer-Intern---Honolulu--HI_R0248393) |
| Clarios ✓ | IT Digital/AI Intern (Summer 2027) 🛂 🆕 | Data & ML/AI | United States, Wisconsin, Milwaukee | Sep 01, 2026 | [Apply](https://clarios.wd5.myworkdayjobs.com/clarioscareers/job/United-States-Wisconsin-Milwaukee/IT-Digital-AI-Intern--Summer-2027-_WD49910) |
| Teledyne | EADSIM Software Engineering Intern (Summer 2027) 🇺🇸 🆕 | Software | US - Huntsville, AL | Sep 01, 2026 | [Apply](https://flir.wd1.myworkdayjobs.com/flircareers/job/US---Huntsville-AL/EADSIM-Software-Engineering-Intern--Summer-2027-_REQ36667) |
| Johnson & Johnson | Data Science Co-Op, Summer 2027 🆕 | Data & ML/AI | Cincinnati +2 more | Sep 01, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cincinnati-Ohio-United-States-of-America/Data-Science-Co-Op--Summer-2027_R-096746) |
| Newrez ✓ | 2027 Summer Internship - Software Developer 🆕 | Software | TX, Coppell | Sep 01, 2026 | [Apply](https://newrez.wd1.myworkdayjobs.com/NRZ/job/TX-Coppell/XMLNAME-2027-Summer-Internship---Software-Developer_R10390) |
| Northrop Grumman | 2027 Cybersecurity Analyst Intern -  Boulder CO 🇺🇸 🆕 | Security | United States-Colorado-Boulder | Sep 01, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Colorado-Boulder/XMLNAME-2027-Cybersecurity-Analyst-Intern----Boulder-CO_R10248677) |
| Philips | Co-op - Software Development Engineer - Cambridge, MA - Jan-Aug 2027 🆕 | Software | Cambridge (US) +2 more | Sep 01, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Cambridge-US-Massachusetts-United-States/Co-op---Software-Development-Engineer---Cambridge--MA---Jan-Aug-2027_590095) |
| Philips | Co-op – Software Engineering (APM) - Cambridge, MA - Jan - Aug 2027 🆕 | Software | Cambridge (US) +2 more | Sep 01, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Cambridge-US-Massachusetts-United-States/Co-op---Software-Engineering--APM----Cambridge--MA---Jan---Aug-2027_590097) |
| Philips | Co-op-Manufacturing Engineering-Murrysville, PA-January-June 2027 🆕 | Hardware | Murrysville, Pennsylvania, United States | Sep 01, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Murrysville-Pennsylvania-United-States/Co-op-Manufacturing-Engineering-Murrysville--PA-January-June-2027_580754) |
| Stanley Black & Decker ✓ | Embedded Engineering Summer Intern 2027 🆕 | Software | Towson, MD, United States | Sep 01, 2026 | [Apply](https://sbdinc.wd1.myworkdayjobs.com/Stanley_Black_Decker_Career_Site/job/Towson-MD-United-States/Embedded-Engineering-Summer-Intern-2027_REQ-1000052019) |
| Stanley Black & Decker ✓ | Mechanical Engineering Intern Summer 2027 🆕 | Hardware | Towson, MD, United States | Sep 01, 2026 | [Apply](https://sbdinc.wd1.myworkdayjobs.com/Stanley_Black_Decker_Career_Site/job/Towson-MD-United-States/Mechanical-Engineering-Intern-Summer-2027_REQ-1000052017) |
| Texas Instruments ✓ | IT Infrastructure Intern - Summer 2027 🆕 | Software | Pella, IA, United States | Sep 01, 2026 | [Apply](https://ebgj.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/253297) |
| Texas Instruments ✓ | Software Intern - Summer 2027 🆕 | Software | Pella, IA, United States | Sep 01, 2026 | [Apply](https://ebgj.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/253299) |
| Texas Instruments ✓ | Data Engineer Intern - Summer 2027 🆕 | Data & ML/AI | Pella, IA, United States | Sep 01, 2026 | [Apply](https://ebgj.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/253304) |
| Vermeer | Embedded Software Engineer Internship Summer 2027 🆕 | Software | Pella, Iowa, USA - Corporate Office | Sep 01, 2026 | [Apply](https://vermeer.wd5.myworkdayjobs.com/externalcareersite/job/Pella-Iowa-USA---Corporate-Office/Embedded-Software-Engineer-Internship-Summer-2027_REQ-22165) |
| BlueCross BlueShield of Nebraska | Cyber Intern: Summer 2027 🆕 | Security | Omaha, NE | Aug 31, 2026 | [Apply](https://nebraskablue.wd1.myworkdayjobs.com/BCBSNE/job/Omaha-NE/Cyber-Intern--Summer-2027_JR101407) |
| BlueCross BlueShield of Nebraska | IS Intern: AI & Automation (Managed Services) Summer 2027 🆕 | Data & ML/AI | Omaha, NE | Aug 31, 2026 | [Apply](https://nebraskablue.wd1.myworkdayjobs.com/BCBSNE/job/Omaha-NE/IS-Intern--Summer-2027_JR101411) |
| HP IQ | Software Engineer Intern, Cloud Services (Summer 2027) | Software | San Francisco, CA | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/hpiq/jobs/6111955004) |
| HP IQ | Software Engineering Intern, AML Platform (Summer 2027) | Software | San Francisco, CA | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/hpiq/jobs/6114781004) |
| Olsson | Mechanical Engineering Internship - Data Center Facilities | Data & ML/AI | Dallas +9 more | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5396012008) |
| Olsson | Structural Engineering Internship - Federal Infrastructure | Hardware | Overland Park, KS | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5396073008) |
| Olsson | Mechanical Engineering Internship - Federal Infrastructure | Hardware | Overland Park, KS | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5396095008) |
| DraftKings ✓ | Software Engineer Intern (Summer 2027) | Software | Boston, MA | Aug 31, 2026 | [Apply](https://draftkings.wd1.myworkdayjobs.com/Campus_Career_Portal/job/Boston-MA/Software-Engineer-Intern--Summer-2027-_JR14929) |
| Michelin | Summer 2027 Internship: Mechanical Engineer (Emporia, KS) | Hardware | EMPORIA, KS | Aug 31, 2026 | [Apply](https://michelinhr.wd3.myworkdayjobs.com/Michelin/job/EMPORIA-KS/XMLNAME-2027-Summer-Mechanical-Engineer--Emporia--KS-_R-2026030587) |
| Vermeer | Advanced Manufacturing Intern - Summer 2027 | Hardware | Pella, Iowa, USA - The Center | Aug 31, 2026 | [Apply](https://vermeer.wd5.myworkdayjobs.com/externalcareersite/job/Pella-Iowa-USA---The-Center/Advanced-Manufacturing-Intern---Summer-2027_REQ-22140) |
| Awetomaton | Platform Engineering Intern 🇺🇸 | Software | Beavercreek, OH | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/awetomaton/jobs/5394046008) |
| Lexington Medical | Mechanical Engineering Intern | Hardware | Bedford, MA | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/lexingtonmedical/jobs/5400185008) |
| Lexington Medical | Manufacturing Engineering Intern | Hardware | Bedford, MA | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/lexingtonmedical/jobs/5404584008) |
| Alcon ✓ | Spring + Summer 2027 Co-Op - Manufacturing Science & Technology | Hardware | Houston, Texas | Aug 31, 2026 | [Apply](https://alcon.wd5.myworkdayjobs.com/careers_alcon/job/Houston-Texas/Fall---Spring-2026-2027-Co-Op---Manufacturing-Science---Technology_R-2026-47959) |
| Barr | Internship – Mechanical Engineer (Hybrid) 🛂 | Hardware | Minneapolis, MN | Aug 31, 2026 | [Apply](https://barr.wd1.myworkdayjobs.com/barrcareers/job/Minneapolis-MN/Internship---Mechanical-Engineer--Hybrid-_R-102306) |
| DraftKings ✓ | Software Engineer Intern (Summer 2027) | Software | Boston, MA | Aug 31, 2026 | [Apply](https://draftkings.wd1.myworkdayjobs.com/Campus_Career_Portal/job/Boston-MA/Software-Engineer-Intern--Summer-2027-_JR14928) |
| Equifax ✓ | Site Reliability Engineer Intern | Software | USA - Missouri - St. Louis - Lackland | Aug 30, 2026 | [Apply](https://equifax.wd5.myworkdayjobs.com/UR_External/job/USA---Missouri---St-Louis---Lackland/Site-Reliability-Engineer-Intern_J00178674) |
| Northwood Space | Mechanical Engineering Intern (2027 Summer Internship) 🇺🇸 | Hardware | Torrance, CA | Aug 29, 2026 | [Apply](https://jobs.ashbyhq.com/northwoodspace/6081eebf-7021-4a3f-a34f-78c91c94fcd3) |
| Northwood Space | Software Engineering Intern (2027 Summer Internship) 🇺🇸 | Software | Torrance, CA | Aug 29, 2026 | [Apply](https://jobs.ashbyhq.com/northwoodspace/ce3d4b73-461e-4128-a6f1-f933897e8119) |
| Northwood Space | Embedded Software Engineering Intern (2027 Summer Internship) 🇺🇸 | Software | Torrance, CA | Aug 29, 2026 | [Apply](https://jobs.ashbyhq.com/northwoodspace/d0cca9dd-ea90-4c3b-94b4-17761932d11c) |
| Workiva | Summer 2027 Intern - Software Engineering 🏠 | Software | USA - Remote | Aug 28, 2026 | [Apply](https://workiva.wd503.myworkdayjobs.com/careers/job/USA---Remote/Summer-2027-Intern---Software-Engineering_R12190) |
| Conagra Brands ✓ | Cybersecurity Internship - Summer 2027 | Security | Omaha, Nebraska | Aug 28, 2026 | [Apply](https://conagrabrands.wd1.myworkdayjobs.com/Careers_US/job/Omaha-Nebraska/Cybersecurity-Internship---Summer-2027_Req-039965) |
| Charles River Associates (CRA) | (2028 Bachelor's/Master's graduates) Cyber and Forensic Technology Consulting Analyst/Associate Intern (Summer 2027) | Security | Boston +11 more | Aug 28, 2026 | [Apply](https://job-boards.greenhouse.io/charlesriverassociates/jobs/8128811) |
| Shield AI | Summer 2027 - Advanced Manufacturing Engineering Intern | Hardware | Dallas, Texas | Aug 27, 2026 | [Apply](https://jobs.lever.co/shieldai/c41c41a2-83d8-41a0-8a3b-ff8b84dc1c8a) |
| Brunswick ✓ | Mercury Marine: Mechanical Engineering Intern | Hardware | Fond du Lac, WI | Aug 27, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Fond-du-Lac-WI/Mercury-Marine--Mechanical-Engineering-Intern_JR-051390) |
| Brunswick ✓ | Manufacturing Engineering Intern 🛂 | Hardware | New York Mills, MN | Aug 27, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/New-York-Mills-MN/Manufacturing-Engineering-Intern_JR-051341-1) |
| Workiva | Spring & Summer 2027 Intern - Product Management 🏠 | Software | USA - Remote | Aug 27, 2026 | [Apply](https://workiva.wd503.myworkdayjobs.com/careers/job/USA---Remote/Spring---Summer-2027-Intern---Product-Management_R12355) |
| Workiva | Summer 2027 Intern - Machine Learning Engineering 🏠 | Data & ML/AI | USA - Remote | Aug 27, 2026 | [Apply](https://workiva.wd503.myworkdayjobs.com/careers/job/USA---Remote/Summer-2027-Intern---Machine-Learning-Engineering_R12194-1) |
| AnaVation | Computer Science Internship Summer 2027 🇺🇸 | Software | Huntsville, AL | Aug 27, 2026 | [Apply](https://jobs.lever.co/anavationllc/f7c83978-8510-409c-a5a3-17618511f819) |
| Amazon ✓ | Software Development Engineer Intern, Annapurna Labs - 2027 | Software | Cupertino, California, USA | Aug 27, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10517567/software-development-engineer-intern-annapurna-labs-2027) |
| AbbVie ✓ | 2027 Business Technology Solutions Intern - Cybersecurity (Undergraduate) | Security | North Chicago, IL, United States | Aug 27, 2026 | [Apply](https://jobs.smartrecruiters.com/AbbVie/3743990014896329) |
| AbbVie ✓ | 2027 Business Technology Solutions Intern - Cybersecurity (Undergraduate) | Security | Irvine, CA, United States | Aug 27, 2026 | [Apply](https://jobs.smartrecruiters.com/AbbVie/3743990014900496) |
| AbbVie ✓ | 2027 Business Technology Solutions Intern - Cybersecurity (Undergraduate) | Security | South San Francisco, CA, United States | Aug 27, 2026 | [Apply](https://jobs.smartrecruiters.com/AbbVie/3743990014900536) |
| ABB ✓ | Manufacturing Engineering Intern - Summer 2027 🛂 | Hardware | USA, NJ, Hackettstown | Aug 27, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/USA-NJ-Hackettstown/Manufacturing-Engineering-Intern---Summer-2027_JR00044977) |
| Air Products ✓ | Summer Intern- IT & Cyber Audit (2027) | Security | Allentown, Pennsylvania | Aug 27, 2026 | [Apply](https://airproducts.wd5.myworkdayjobs.com/AP0001/job/Allentown-Pennsylvania/Summer-Intern--IT---Cyber-Audit--2027-_JR-2026-21954) |
| Air Products ✓ | Summer Intern/Co-op-Mechanical Engineering (2027) | Hardware | Allentown, Pennsylvania | Aug 27, 2026 | [Apply](https://airproducts.wd5.myworkdayjobs.com/AP0001/job/Allentown-Pennsylvania/Summer-Intern-Co-op-Mechanical-Engineering--2027-_JR-2026-21956) |
| Johns Manville (JM) | Product Management Intern- Summer 2027 | Software | Denver CO WHQ | Aug 27, 2026 | [Apply](https://jm.wd103.myworkdayjobs.com/External/job/Denver-CO-WHQ/Product-Management-Intern--Summer-2027_R26_1432) |
| Chamberlain Group ✓ | Manufacturing Process Documentation Intern (Summer 2027) | Hardware | Malvern, AR | Aug 26, 2026 | [Apply](https://chamberlain.wd1.myworkdayjobs.com/Chamberlain_Group/job/Malvern-AR/Manufacturing-Process-Documentation-Intern--Summer-2027-_JR31463) |
| Axon ✓ | 2027 US Embedded Engineering Internship | Software | Seattle, Washington, United States | Aug 26, 2026 | [Apply](https://job-boards.greenhouse.io/axontalentcommunity/jobs/7800627003) |
| AECOM ✓ | Structural Engineering Intern - Bridge & Transportation Structures | Hardware | Arlington, VA, United States | Aug 26, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000145837999) |
| IMEG ✓ | Mechanical Engineering Intern / Columbus, OH | Hardware | Columbus, OH | Aug 26, 2026 | [Apply](https://wd1.myworkdaysite.com/recruiting/imeg/Imeg_Careers/job/Columbus-OH/Mechanical-Engineering-Intern---Columbus--OH_R-16523) |
| Leidos ✓ | Cybersecurity Analyst Intern 🇺🇸 | Security | Odenton, MD | Aug 26, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Odenton-MD/Cybersecurity-Analyst-Intern_R-00190663) |
| Leidos ✓ | Cybersecurity Analyst Intern 🇺🇸 | Security | Pearl Harbor, HI | Aug 26, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Pearl-Harbor-HI/Cybersecurity-Analyst-Intern_R-00190665) |
| Leidos ✓ | Cybersecurity Analyst Intern 🇺🇸 | Security | Sunset, UT | Aug 26, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Sunset-UT/Cybersecurity-Analyst-Intern_R-00190664) |
| The Hartford | Tech & Data Program Summer 2027 - Data Engineer Intern (Chicago) 🛂 | Data & ML/AI | Chicago, IL | Aug 26, 2026 | [Apply](https://thehartford.wd5.myworkdayjobs.com/Careers_External/job/Chicago-IL/Tech---Data-Program-Summer-2027---Data-Engineer-Intern--Chicago-_R2626650) |
| Wavetronix | Computer Science Internship Summer 2027 | Software | Springville, UT | Aug 26, 2026 | [Apply](https://wavetronix.breezy.hr/p/565668353504-computer-science-internship-summer-2027) |
| Verisk | AI Intern / Summer Internship Program | Data & ML/AI | Jersey City, NJ, United States | Aug 26, 2026 | [Apply](https://fa-ewmy-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/4682) |
| Ardian | Infrastructure Intern – February 2027 I NYC | Software | New York | Aug 26, 2026 | [Apply](https://ardian.wd103.myworkdayjobs.com/ArdianCareers/job/New-York/Infrastructure-Intern---February-2027-I-NYC_JR1002214) |
| The Hartford | Tech & Data Program Summer 2027 – Data Engineer Intern (Charlotte) 🛂 | Data & ML/AI | Charlotte, NC | Aug 26, 2026 | [Apply](https://thehartford.wd5.myworkdayjobs.com/Careers_External/job/Charlotte-NC/Tech---Data-Program-Summer-2027---Data-Engineer-Intern--Charlotte-_R2626648) |
| The Hartford | Tech & Data Program Summer 2027 - Software Engineer Intern (Charlotte) 🛂 | Data & ML/AI | Charlotte, NC | Aug 26, 2026 | [Apply](https://thehartford.wd5.myworkdayjobs.com/Careers_External/job/Charlotte-NC/Tech---Data-Program-Summer-2027---Software-Engineer-Intern--Charlotte-_R2626649) |
| WhiteWater Midstream | Data Science Intern - Summer 2027 | Data & ML/AI | Austin, TX | Aug 26, 2026 | [Apply](https://job-boards.greenhouse.io/whitewatermidstream/jobs/5217853007) |
| QTS | Summer 2027 Internship: Internal Data Center Infrastructure Projects 🇺🇸 | Data & ML/AI | Irving, TX | Aug 26, 2026 | [Apply](https://qtsdatacenters.wd5.myworkdayjobs.com/qts/job/Irving-TX/Summer-2027-Internship--Internal-Data-Center-Infrastructure-Projects_R2026-1906) |
| AECOM ✓ | Structural Engineering Intern - Hiring Event with AECOM - Philadelphia | Hardware | Philadelphia, PA, United States | Aug 26, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000145646379) |
| Brunswick ✓ | Mercury Marine: Advanced Manufacturing/Operations Analytics Engineering Co-op | Data & ML/AI | Fond du Lac, WI | Aug 25, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Fond-du-Lac-WI/Mercury-Marine--Advanced-Manufacturing-Operations-Analytics-Engineering-Co-op_JR-051238) |
| Verkada ✓ | Backend Software Engineering Intern 2027 | Software | San Mateo, CA United States | Aug 25, 2026 | [Apply](https://job-boards.greenhouse.io/verkada/jobs/5210813007) |
| Verkada ✓ | Frontend Software Engineering Intern 2027 | Software | San Mateo, CA United States | Aug 25, 2026 | [Apply](https://job-boards.greenhouse.io/verkada/jobs/5210942007) |
| Verkada ✓ | Embedded Software Engineering Intern 2027 | Software | San Mateo, CA United States | Aug 25, 2026 | [Apply](https://job-boards.greenhouse.io/verkada/jobs/5211595007) |
| IMEG ✓ | Structural Intern / Fairfax, VA | Hardware | Washington, DC | Aug 25, 2026 | [Apply](https://wd1.myworkdaysite.com/recruiting/imeg/Imeg_Careers/job/Washington-DC/Structural-Intern---Fairfax--VA_R-16618) |
| Sensata ✓ | Mechanical Engineer Intern (Dynapower) - Summer 2027 🇺🇸 | Hardware | Dynapower South Burlington, VT | Aug 25, 2026 | [Apply](https://sensata.wd1.myworkdayjobs.com/Sensata-Careers/job/Dynapower-South-Burlington-VT/Mechanical-Engineer-Intern--Dynapower----Summer-2027_IRC98334) |
| GlobalFoundries ✓ | Cybersecurity Intern (Summer 2027) | Security | USA - New York - Malta | Aug 25, 2026 | [Apply](https://globalfoundries.wd1.myworkdayjobs.com/External/job/USA---New-York---Malta/Cybersecurity-Intern--Summer-2027-_JR-2604459) |
| BTI360 | Software Engineering Intern 🇺🇸 | Software | Herndon,VA | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/bti36021/jobs/8155152) |
| Sage | Software Engineering Intern (Full Stack) – Summer 2027 | Software | New York, New York, United States | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/sage49/jobs/6131185004) |
| Sage | Software Engineering Intern (Edge) – Summer 2027 | Software | New York, New York, United States | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/sage49/jobs/6131191004) |
| Advanced Space | 2027 Software Engineering Summer Internship | Software | Westminster, CO | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/advancedspace/jobs/4324855009) |
| Advanced Space | 2027 Machine Learning Summer Internship | Data & ML/AI | Westminster, CO | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/advancedspace/jobs/4324875009) |
| Advanced Space | 2027 DevOps Summer Internship | Software | Westminster, CO | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/advancedspace/jobs/4333179009) |
| Freddie Mac | Multifamily Software Development Intern – Summer 2027 | Software | McLean, VA | Aug 24, 2026 | [Apply](https://freddiemac.wd5.myworkdayjobs.com/External/job/McLean-VA/Multifamily-Software-Development-Intern---Summer-2027_JR17564) |
| Watts Water | Manufacturing Engineer Intern Summer 2027 | Hardware | St Pauls, NC | Aug 24, 2026 | [Apply](https://wattswater.wd5.myworkdayjobs.com/Intern-External/job/St-Pauls-NC/Manufacturing-Engineer-Intern-Summer-2027_10017388) |
| Freddie Mac | Single-Family Software Developer Intern- Summer 2027 | Software | McLean, VA | Aug 24, 2026 | [Apply](https://freddiemac.wd5.myworkdayjobs.com/External/job/McLean-VA/Single-Family-Software-Developer-Intern--Summer-2027_JR17544) |
| Motorola ✓ | Android Applications Developer Intern - Summer 2027 🇺🇸 | Software | Chicago, IL | Aug 24, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Chicago-IL/Android-Applications-Developer-Intern---Summer-2027_R67740) |
| InfiniteQuant | Quantitative Developer - Internship - Summer 2027 🏠 | Quant | New York +2 more | Aug 24, 2026 | [Apply](https://jobs.smartrecruiters.com/InfiniteQuant/744000145263134) |
| The Walt Disney Company | Walt Disney World Workforce Management Industrial Engineering Intern, Spring/Summer 2027 | Hardware | Lake Buena Vista, FL, USA | Aug 24, 2026 | [Apply](https://disney.wd5.myworkdayjobs.com/disneycareer/job/Lake-Buena-Vista-FL-USA/Walt-Disney-World-Workforce-Management-Industrial-Engineering-Intern--Spring-Summer-2027_10158144) |
| Elanco | Manufacturing Scientist/Technical Services Intern – Elanco Technology Center (Summer 2027) | Hardware | Indianapolis, IN | Aug 21, 2026 | [Apply](https://elanco.wd5.myworkdayjobs.com/External_Career/job/Indianapolis-IN/Manufacturing-Scientist-Technical-Services-Intern---Elanco-Technology-Center--Summer-2027-_R0026897) |
| Dev Technology Group | React/Node Developer Intern (Summer 2027) 🇺🇸 🆕 | Software | Reston, Virginia | Aug 20, 2026 | [Apply](https://job-boards.greenhouse.io/devtechnology/jobs/8726212002) |
| General Matter | Summer 2027 Internship - Manufacturing Engineering | Hardware | Los Angeles, CA | Aug 20, 2026 | [Apply](https://job-boards.greenhouse.io/generalmatter/jobs/5376060008) |
| Elanco | Manufacturing Associate Intern – Elwood, Kansas (Summer 2027) | Hardware | Elwood, KS | Aug 20, 2026 | [Apply](https://elanco.wd5.myworkdayjobs.com/External_Career/job/Elwood-KS/Manufacturing-Associate-Intern---Elwood--Kansas--Summer-2027-_R0026899) |
| IMEG ✓ | Mechanical Engineering Intern / Greenwood Village, CO | Hardware | Denver Metro, CO | Aug 20, 2026 | [Apply](https://wd1.myworkdaysite.com/recruiting/imeg/Imeg_Careers/job/Denver-Metro-CO/Mechanical-Engineering-Intern---Greenwood-Village--CO_R-16570-1) |
| Fannie Mae ✓ | Campus – Data Science Intern (Analytics & Modeling Program) 🛂 | Data & ML/AI | Washington, DC | Aug 20, 2026 | [Apply](https://fanniemae.wd1.myworkdayjobs.com/FannieMaeCareers/job/Washington-DC/Campus---Data-Science-Intern--Analytics---Modeling-Program-_JR2815) |
| Fifth Third Bank ✓ | Information Security Co-op – Identity & Access Management – Summer 2027 | Security | Cincinnati, OH | Aug 20, 2026 | [Apply](https://fifththird.wd5.myworkdayjobs.com/53careers/job/Cincinnati-OH/Information-Security-Co-op---Identity---Access-Management---Summer-2027_R71591) |
| Fifth Third Bank ✓ | Information Security Co-op - Cyber Threat Interdiction - Summer 2027 | Security | Cincinnati, OH | Aug 20, 2026 | [Apply](https://fifththird.wd5.myworkdayjobs.com/53careers/job/Cincinnati-OH/Information-Security-Co-op---Cyber-Threat-Interdiction---Summer-2027_R71582) |
| Dev Technology Group | AI/ML Intern (Summer 2027) 🇺🇸 🆕 | Data & ML/AI | Reston, Virginia | Aug 19, 2026 | [Apply](https://job-boards.greenhouse.io/devtechnology/jobs/8726074002) |
| Dev Technology Group | Microsoft Power Platform & AI Intern (Summer 2027) 🇺🇸 🆕 | Data & ML/AI | Reston, Virginia | Aug 19, 2026 | [Apply](https://job-boards.greenhouse.io/devtechnology/jobs/8726259002) |
| Freeform | Manufacturing Engineering Intern (Summer 2027) | Hardware | Los Angeles, CA (On-site) | Aug 19, 2026 | [Apply](https://job-boards.greenhouse.io/freeformfuturecorp/jobs/7895700003) |
| Freeform | Materials Engineering Intern (Summer 2027) | Hardware | Los Angeles, CA (On-site) | Aug 19, 2026 | [Apply](https://job-boards.greenhouse.io/freeformfuturecorp/jobs/7907965003) |
| Elanco | Manufacturing Scientist/Technical Services Intern – Clinton, Indiana (Summer 2027) | Hardware | Clinton, IN | Aug 19, 2026 | [Apply](https://elanco.wd5.myworkdayjobs.com/External_Career/job/Clinton-IN/Manufacturing-Scientist-Technical-Services-Intern---Clinton--Indiana--Summer-2027-_R0026869-1) |
| Continental Resources | Data Analyst Intern (Summer 2027) | Data & ML/AI | Oklahoma City, OK | Aug 18, 2026 | [Apply](https://clr.wd5.myworkdayjobs.com/CLR_Careers/job/Oklahoma-City-OK/Data-Analyst-Intern--Summer-2027-_R02591-1) |
| Freeform | Mechanical Engineering Intern (Summer 2027) | Hardware | Los Angeles, CA (On-site) | Aug 18, 2026 | [Apply](https://job-boards.greenhouse.io/freeformfuturecorp/jobs/7894117003) |
| H3X Technologies | Advanced Manufacturing Engineering Intern (Spring) | Hardware | Louisville, Colorado | Aug 18, 2026 | [Apply](https://jobs.ashbyhq.com/h3x-technologies/6af49576-a61d-480c-b155-3e034e2ed5be) |
| PIMCO ✓ | 2027 Summer Intern - Technology Analyst, Software Engineering | Software | Austin, TX USA | Aug 18, 2026 | [Apply](https://pimco.wd1.myworkdayjobs.com/pimco-careers/job/Austin-TX-USA/XMLNAME-2027-Summer-Intern---Technology-Analyst--Software-Engineering_R106745) |
| Conagra Brands ✓ | IT Infrastructure Internship - Summer 2027 | Software | Omaha, Nebraska | Aug 17, 2026 | [Apply](https://conagrabrands.wd1.myworkdayjobs.com/Careers_US/job/Omaha-Nebraska/IT-Infrastructure-Internship---Summer-2027_Req-039788) |
| Conagra Brands ✓ | Software Development Internship - Summer 2027 | Software | Omaha, Nebraska | Aug 17, 2026 | [Apply](https://conagrabrands.wd1.myworkdayjobs.com/Careers_US/job/Omaha-Nebraska/Software-Development-Internship---Summer-2027_Req-039787) |
| The Voleon Group | Software Engineer Intern - (Summer 2027) | Software | Berkeley, CA | Aug 14, 2026 | [Apply](https://jobs.ashbyhq.com/voleon/57f1b666-2f4b-4bad-aac0-fa42a1c8fdf6) |
| GlobalFoundries ✓ | Advanced Manufacturing Process Engineering Intern (Summer 2027) | Hardware | USA - Vermont - Essex Junction | Aug 14, 2026 | [Apply](https://globalfoundries.wd1.myworkdayjobs.com/External/job/USA---Vermont---Essex-Junction/Advanced-Manufacturing-Process-Engineering-Intern--Summer-2027-_JR-2604657) |
| GlobalFoundries ✓ | US Advanced Manufacturing Equipment Engineering Intern, Junior (Summer 2027) | Hardware | USA - Vermont - Essex Junction | Aug 14, 2026 | [Apply](https://globalfoundries.wd1.myworkdayjobs.com/External/job/USA---Vermont---Essex-Junction/US-Advanced-Manufacturing-Equipment-Engineering-Intern--Junior--Summer-2027-_JR-2604666) |
| The Nuclear Company | Summer 2027 AI Applied Research Internship 🇺🇸 | Data & ML/AI | Washington, DC | Aug 14, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5391923008) |
| Notion ✓ | Software Engineer Intern (Summer 2027) | Software | San Francisco, California | Aug 14, 2026 | [Apply](https://jobs.ashbyhq.com/notion/3fba1c39-c5cb-47d7-9ad2-1cec4d7e9d0c) |
| Teledyne | NHRC Software Engineering Internship (Summer 2027) 🇺🇸 | Software | US - Huntsville, AL | Aug 13, 2026 | [Apply](https://flir.wd1.myworkdayjobs.com/flircareers/job/US---Huntsville-AL/NHRC-Software-Engineering-Internship--Summer-2027-_REQ36193) |
| Teledyne | NHRC Software Engineering Internship (Summer 2027) 🇺🇸 | Software | US - Huntsville, AL | Aug 13, 2026 | [Apply](https://flir.wd1.myworkdayjobs.com/flircareers/job/US---Huntsville-AL/NHRC-Software-Engineering-Internship--Summer-2027-_REQ36194-2) |
| Western Digital ✓ | Summer 2027 Intern - Software Engineering | Software | San Jose, CA, United States | Aug 12, 2026 | [Apply](https://jobs.smartrecruiters.com/WesternDigital/744000143171017) |
| RTX | Software Engineering Intern (Summer 2027) 🇺🇸 | Software | US-IA-CEDAR RAPIDS-137 ~ 855 35Th St NE… | Aug 12, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-137--855-35Th-St-NE--BLDG-137/Software-Engineering-Intern--Summer-2027-_01865875) |
| Chamberlain Group ✓ | Intern, Community Product Management (Summer 2027) | Software | Oak Brook, IL | Aug 10, 2026 | [Apply](https://chamberlain.wd1.myworkdayjobs.com/Chamberlain_Group/job/Oak-Brook-IL/Intern--Community-Product-Management--Summer-2026-_JR31309) |
| DV Trading | Software Engineer Intern - Summer 2027 (DV Commodities) | Software | New York | Aug 10, 2026 | [Apply](https://job-boards.greenhouse.io/dvtrading/jobs/4719119005) |
| ING | Summer 2027 Internship - Tech (Information Security) | Security | New York | Aug 10, 2026 | [Apply](https://ing.wd3.myworkdayjobs.com/icsgblcor/job/New-York/Summer-2027-Internship---Tech--Information-Security-_REQ-10119620) |
| ING | Summer 2027 Internship - Tech (Infrastructure) | Software | New York | Aug 10, 2026 | [Apply](https://ing.wd3.myworkdayjobs.com/icsgblcor/job/New-York/Summer-2027-Internship---Tech--Infrastructure-_REQ-10119621) |
| Axon ✓ | 2027 US Firmware Engineering Internship | Hardware | Seattle, Washington, United States | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/axontalentcommunity/jobs/7837246003) |
| The Nuclear Company | Summer 2027 AI/ML Engineering Intern 🇺🇸 | Data & ML/AI | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383231008) |
| The Nuclear Company | Summer 2027 Software Engineering Intern 🇺🇸 | Software | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383236008) |
| Roblox ✓ | [Summer 2027] Software Engineer Intern | Software | San Mateo, CA, United States | Aug 05, 2026 | [Apply](https://careers.roblox.com/jobs/8072713?gh_jid=8072713) |
| Belvedere Trading | Software Engineer Intern - Summer 2027 | Software | Chicago, Illinois | Aug 04, 2026 | [Apply](https://jobs.lever.co/belvederetrading/10746b3d-1760-4573-9b63-b93f5a5e4fc0) |
| Pentair | IT & Cybersecurity Leadership Development Internship Program -  Summer 2027 🛂 | Security | Golden Valley, MN | Aug 04, 2026 | [Apply](https://pentair.wd5.myworkdayjobs.com/pentair_careers/job/Golden-Valley-MN/IT---Cybersecurity-Leadership-Development-Internship-Program----Summer-2027_R23700) |
| Kraft Heinz ✓ | 2027 US Manufacturing Internship Program – Manufacturing Facility Garland, Texas | Hardware | Garland, TX | Aug 03, 2026 | [Apply](https://heinz.wd1.myworkdayjobs.com/KraftHeinz_Careers_UR/job/Garland-TX/XMLNAME-2027-US-Manufacturing-Internship-Program---Manufacturing-Facility-Garland--Texas_R-105352) |
| CNO Financial Group | Artificial Intelligence (AI) IT Intern 2027 - REMOTE 🏠 | Data & ML/AI | Carmel, IN | Aug 03, 2026 | [Apply](https://cnoinc.wd5.myworkdayjobs.com/Careers/job/Carmel-IN/Artificial-Intelligence--AI--IT-Intern-2027---REMOTE_JR170389) |
| Chicago Trading Company | Software Engineering Internship - Summer 2027 | Software | Chicago, Illinois, United States | Aug 03, 2026 | [Apply](https://job-boards.greenhouse.io/chicagotradingcampus/jobs/4716932005) |
| HPR (Hyannis Port Research) | Software Engineering Intern - Summer 2027 | Software | Needham, MA | Aug 01, 2026 | [Apply](https://job-boards.greenhouse.io/hyannisportresearch/jobs/7822989003) |
| Heliux | Software Engineer (Internship, Summer 2027) 🇺🇸 | Software | HQ (San Francisco, CA) | Jul 31, 2026 | [Apply](https://jobs.ashbyhq.com/heliux/ff2b6f4b-00d0-4afe-b4f5-2dbf443409ef) |
| Melius | Software Engineering Intern [Spring/Summer 2027] | Software | New York City | Jul 31, 2026 | [Apply](https://jobs.ashbyhq.com/melius/b61f063a-4f94-4e50-a4ef-05aaab552280) |
| Kraft Heinz ✓ | 2027 US Manufacturing Internship Program – Manufacturing Facility Fremont, Ohio | Hardware | Fremont, OH | Jul 31, 2026 | [Apply](https://heinz.wd1.myworkdayjobs.com/KraftHeinz_Careers_UR/job/Fremont-OH/XMLNAME-2027-US-Manufacturing-Internship-Program---Manufacturing-Facility-Fremont--Ohio_R-105282) |
| Kraft Heinz ✓ | 2027 US Manufacturing Internship Program – Manufacturing Facility Kirksville, Missouri | Hardware | Kirksville, MO | Jul 31, 2026 | [Apply](https://heinz.wd1.myworkdayjobs.com/KraftHeinz_Careers_UR/job/Kirksville-MO/XMLNAME-2027-US-Manufacturing-Internship-Program---Manufacturing-Facility-Kirksville--Missouri_R-105273) |
| Virtu Financial ✓ | 2027 Internship - Frontend Engineer (UI) | Software | New York | Jul 29, 2026 | [Apply](https://job-boards.greenhouse.io/virtu/jobs/8657500002) |
| Appian ✓ | Information Security Engineer Intern 🛂 | Security | McLean, Virginia | Jul 27, 2026 | [Apply](https://job-boards.greenhouse.io/appian/jobs/8088496) |
| PDT Partners | Summer 2027 Software Engineering Intern | Software | New York, NY | Jul 24, 2026 | [Apply](https://job-boards.greenhouse.io/pdtpartners/jobs/8077685) |
| Quadrillion | Software Engineering Intern (Summer 2027) | Software | New York City | Jul 24, 2026 | [Apply](https://jobs.ashbyhq.com/quadrillion-labs/a4acc44c-31ce-41a0-ab44-2500487b4d05) |
| Kairos Power | Mechanical and Manufacturing Engineering Internship - Summer 2027 | Hardware | Alameda +5 more | Jul 23, 2026 | [Apply](https://job-boards.greenhouse.io/kairospower/jobs/6123676004) |
| Anthelion Capital | Quant Developer / Quant Research Intern - 2026/2027 | Quant | New York City | Jul 23, 2026 | [Apply](https://jobs.ashbyhq.com/anthelioncap/5e2ea37b-2369-474e-b717-c24c60976e96) |
| Appian ✓ | Software Engineering Intern 🛂 | Software | McLean, Virginia | Jul 23, 2026 | [Apply](https://job-boards.greenhouse.io/appian/jobs/8041237) |
| Mosaic | Structural Engineer Co-Op/Intern - Summer 2027 | Hardware | US - Tampa, FL (Lithia area) | Jul 22, 2026 | [Apply](https://mosaic.wd5.myworkdayjobs.com/mosaic/job/US---Tampa-FL-Lithia-area/Structural-Engineer-Co-Op-Intern---Summer-2027_64448) |
| Virtu Financial ✓ | 2027 Internship - Software Engineer | Software | Austin, TX; New York | Jul 21, 2026 | [Apply](https://job-boards.greenhouse.io/virtu/jobs/8624410002) |
| Chicago Trading Company | Software Engineering Internship - Summer 2027 | Software | Chicago, Illinois, United States | Jul 20, 2026 | [Apply](https://job-boards.greenhouse.io/ctccampusboard/jobs/4708230005) |
| Chevron Corporation ✓ | 2026-2027 Information Technology - Software Engineer - Intern 🛂 | Software | Houston, Texas, United States of America | Jul 16, 2026 | [Apply](https://chevron.wd5.myworkdayjobs.com/University/job/Houston-Texas-United-States-of-America/XMLNAME-2026-2027-Information-Technology---Software-Engineer---Intern_R000072398-1) |
| The Trade Desk ✓ | 2027 North America Software Engineering Internship | Software | Bellevue +5 more | Jul 15, 2026 | [Apply](https://job-boards.greenhouse.io/thetradedesk/jobs/5187605007) |
| Five Rings | Summer Intern 2027 - Software Developer | Software | New York | Jul 14, 2026 | [Apply](https://job-boards.greenhouse.io/fiveringsllc/jobs/5349707008) |
| Akuna Capital ✓ | Software Engineer Intern - C++, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018847/?gh_jid=8018847) |
| Akuna Capital ✓ | Software Engineer Intern - Python, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018853/?gh_jid=8018853) |
| Akuna Capital ✓ | Platform Engineer Intern, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018856/?gh_jid=8018856) |
| Hudson River Trading ✓ | Software Engineering Internship (C++ or Python) – Summer 2027 | Software | Austin +11 more | Jul 13, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=8052083) |
| Tower Research Capital ✓ | Quantitative Developer Intern - Summer 2027 | Quant | New York, Chicago | Jul 05, 2026 | [Apply](https://www.tower-research.com/open-positions/?gh_jid=8044334) |
| IMC Trading | Software Engineer Intern - Summer 2027 | Software | Chicago, United States | Jul 01, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4823924101) |
| IMC Trading | Machine Learning Research Intern - Summer 2027 - Chicago | Data & ML/AI | Chicago, United States | Jul 01, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4907430101) |
| Anduril | 2027 Mechanical Engineer Intern 🇺🇸 | Hardware | Atlanta +26 more | Jun 11, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5153187007?gh_jid=5153187007) |
| Anduril | 2027 Manufacturing Engineer Intern 🇺🇸 | Hardware | Atlanta +23 more | Jun 11, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5153218007?gh_jid=5153218007) |
| Voloridge | Quantitative Developer Intern 2027 | Quant | Jupiter, FL | Jun 11, 2026 | [Apply](https://job-boards.greenhouse.io/voloridgeinvestmentmanagement/jobs/4224862009) |
| Anduril | 2027 Software Engineer Intern 🇺🇸 | Software | Atlanta +26 more | Jun 10, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5148079007?gh_jid=5148079007) |
| Walleye Capital | Quantic – Quantitative Developer Intern (Summer 2027) | Quant | Boston, MA | Jun 01, 2026 | [Apply](https://job-boards.greenhouse.io/walleyecapital-external-students/jobs/4679168006) |
| Ellipsis Labs | Software Engineer - 2027 Interns | Software | New York, New York | Mar 26, 2026 | [Apply](https://jobs.ashbyhq.com/ellipsislabs/02136b22-35b1-4b3d-8bef-567c3380a849) |
| Databricks ✓ | Product Management Intern (Summer 2027) | Software | Bellevue +5 more | Aug 17, 2023 | [Apply](https://databricks.com/company/careers/open-positions/job?gh_jid=6883068002) |

## Fall 2026  (36 employer-stated)

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Stantec ✓ | Roadway Design Co-op Student - Infrastructure (Fall 2026) 🆕 | Software | Raleigh, NC, United States | Sep 02, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1007497) |
| Philips | Co-op - Software Development Engineer (Automation) – Cambridge, MA – Fall 2026 🆕 | Software | Cambridge (US) +2 more | Sep 02, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Cambridge-US-Massachusetts-United-States/Co-op---Software-Development-Engineer--Automation----Cambridge--MA---Fall-2026_590708) |
| Northrop Grumman | 2026 Part-Time Cyber Security Engineering Intern - Aurora CO 🇺🇸 | Security | United States-Colorado-Aurora | Aug 31, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Colorado-Aurora/XMLNAME-2026-Part-Time-Cyber-Security-Engineering-Intern---Aurora-CO_R10248520) |
| Xcel Energy | IT Infrastructure Intern - CO | Software | Denver, CO, 80205 | Aug 31, 2026 | [Apply](https://xcelenergy.wd1.myworkdayjobs.com/External/job/Denver-CO-80205/IT-Infrastructure-Intern---CO_JR115917) |
| Amazon ✓ | Robotics - Software Development Engineer Fall Intern/Co-op - 2026 | Hardware | Westboro, Massachusetts, USA | Aug 27, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10517149/robotics-software-development-engineer-fall-intern-co-op-2026) |
| ABB ✓ | AI Robotics UI/UX Intern- Fall 2026 | Data & ML/AI | Milpitas, California, USA | Aug 27, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Milpitas-California-USA/AI-Robotics-UI-UX-Intern--Fall-2026_JR00044847-1) |
| ABB ✓ | Physical AI Robotics Simulation Intern- Fall 2026 | Data & ML/AI | Milpitas, California, USA | Aug 27, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Milpitas-California-USA/Physical-AI-Robotics-Simulation-Intern--Fall-2026_JR00044848-1) |
| Northrop Grumman | 2026 Part-Time Mechanical Engineering Intern - Chandler AZ 🇺🇸 | Hardware | United States-Arizona-Chandler | Aug 26, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Arizona-Chandler/XMLNAME-2026-Part-Time-Mechanical-Engineering-Intern---Chandler-AZ_R10247965) |
| Rivet Industries | Software Engineer Intern, XR Team (Fall 2026) 🇺🇸 | Software | Bellevue, WA | Aug 24, 2026 | [Apply](https://jobs.ashbyhq.com/rivet/4e02461a-9f6c-4d3c-a511-6d54f31999bc) |
| Moog | Intern, IT Computer Science | Software | Buffalo, NY | Aug 19, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--IT-Computer-Science_R-26-19378) |
| ABB ✓ | Manufacturing Engineering/Documentation Intern - Fall 2026 🛂 | Hardware | USA, AR, Jonesboro | Aug 19, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/USA-AR-Jonesboro/Manufacturing-Engineering-Documentation-Intern---Fall-2026_JR00042298) |
| Conagra Brands ✓ | Manufacturing Co-Op | Hardware | Waterloo, Iowa | Aug 18, 2026 | [Apply](https://conagrabrands.wd1.myworkdayjobs.com/Careers_US/job/Waterloo-Iowa/Manufacturing-Co-Op_Req-039806) |
| Flextronics International ✓ | Mechanical Engineering Co-op - Fall 2026 | Hardware | USA, SC, Orangeburg | Aug 07, 2026 | [Apply](https://flextronics.wd1.myworkdayjobs.com/Careers/job/USA-SC-Orangeburg/Mechanical-Engineering-Co-op---Fall-2026_WD227049) |
| The Nuclear Company | Fall 2026 AI/ML Engineering Intern 🇺🇸 | Data & ML/AI | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383163008) |
| Johnson & Johnson | Software Engineer Coop | Software | Cincinnati +2 more | Aug 07, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cincinnati-Ohio-United-States-of-America/Software-Engineer-Coop_R-092820) |
| NVIDIA ✓ | Software Engineering Intern, Dynamo - Fall 2026 | Software | US, CA, Santa Clara | Aug 05, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/US-CA-Santa-Clara/Software-Engineering-Intern--Dynamo---Fall-2026_JR2022295) |
| Phoenix Contact | Manufacturing Co-Op - High School Students | Hardware | Middletown, Pennsylvania | Aug 04, 2026 | [Apply](https://job-boards.greenhouse.io/phoenixcontact/jobs/7817228003) |
| Merck | 2026 Future Talent Program – Manufacturing and Reliability Engineering Co-Op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Manufacturing-and-Reliability-Engineering-Co-Op_R395901) |
| Merck | 2026 Future Talent Program - Vaccine Manufacturing Co-op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Vaccine-Manufacturing-Co-op_R395900) |
| Northrop Grumman | 2026 Fall Co-op Manufacturing Engineering - Baltimore MD 🇺🇸 | Hardware | United States-Maryland-Linthicum | Aug 03, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Maryland-Linthicum/XMLNAME-2026-Fall-Co-op-Manufacturing-Engineering---Baltimore-MD_R10243390-1) |
| Melius | Software Engineering Intern [Fall/Winter 2026] | Software | New York City | Jul 30, 2026 | [Apply](https://jobs.ashbyhq.com/melius/6a944911-dbbf-44c7-ba52-7866f7b433cf) |
| Moog | Intern, IT Computer Science - Data Analytics | Data & ML/AI | Buffalo, NY | Jul 16, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--IT-Computer-Science---Data-Analytics_R-26-17145) |
| NVIDIA ✓ | Applied Research Intern, NLP - Fall 2026 | Data & ML/AI | US, CA, Santa Clara | Jul 01, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/US-CA-Santa-Clara/Applied-Research-Intern--NLP---Fall-2026_JR2010488) |
| Junior | Software Engineering Intern — Fall 2026 🇺🇸 | Software | New York City | Jun 30, 2026 | [Apply](https://jobs.ashbyhq.com/junior/23ee686b-d305-4ac9-860d-16c99ddb4891) |
| Figure | Firmware Intern [Fall 2026] | Hardware | San Jose, CA | Jun 22, 2026 | [Apply](https://job-boards.greenhouse.io/figureai/jobs/4691070006) |
| SoloPulse | Software Engineer Intern/Co-Op - Fall 2026 | Software | Peachtree Corners, GA | Jun 16, 2026 | [Apply](https://jobs.lever.co/solopulseco/00fbde18-a387-4c9f-97d4-77059aec7b56) |
| Beacon Software | Software Engineering Intern | Software | San Francisco, CA | Jun 02, 2026 | [Apply](https://jobs.ashbyhq.com/beaconsoftware/2452d342-a069-4eda-adbe-9df296808ca1) |
| Amazon ✓ | Software Development Engineer Intern, AWS Data Services - Fall 2026 (US) | Data & ML/AI | Seattle, Washington, USA | May 06, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10412530/software-development-engineer-intern-aws-data-services-fall-2026-us) |
| Applied Materials ✓ | 2026 Fall Materials Engineering Co-op (TCAD Modeling) - Doctorate (Gloucester, MA) | Hardware | Gloucester,MA | Apr 01, 2026 | [Apply](https://amat.wd1.myworkdayjobs.com/External/job/GloucesterMA/XMLNAME-2026-Fall-Materials-Engineering-Co-op---Doctorate--Gloucester--MA-_R2611503) |
| Hermeus | Software Engineering Intern (Command & Control) - Fall 2026 🇺🇸 | Software | Atlanta, GA | Apr 01, 2026 | [Apply](https://jobs.lever.co/hermeus/a3a1f0ea-6a4f-42e5-81c8-3b34dac22a67) |
| Motorola ✓ | Intern - Embedded Software, System, and Test Engineer - 2026 🇺🇸 | Software | Irvine, CA | Mar 30, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Irvine-CA/Intern---Embedded-Software--System--and-Test-Engineer---2026_R62372) |
| Alloy Enterprises | Co-Op, Thermal Test Engineer, Fall 2026 (July-December) 🇺🇸 | Hardware | Burlington, MA | Mar 25, 2026 | [Apply](https://jobs.ashbyhq.com/alloyenterprises/946e7ae1-d2ac-4889-a72a-268b0aeda9bd) |
| Hermeus | Mechanical Engineering Intern  - Fall 2026 🇺🇸 | Hardware | Los Angeles, CA | Mar 09, 2026 | [Apply](https://jobs.lever.co/hermeus/6b6afa4a-b37d-4033-ac3b-e6501a951b98) |
| Hermeus | Flight Software Engineering Intern - Fall 2026 🇺🇸 | Software | Atlanta, GA | Mar 04, 2026 | [Apply](https://jobs.lever.co/hermeus/51378fa0-0327-45fd-9420-b6e7d8b56440) |
| SharkNinja ✓ | Fall 2026: Mechanical Engineering Co-op,  Wearable & Biomedical Devices (September to December) | Hardware | Needham, MA, United States | Feb 05, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4651641006) |
| Amazon ✓ | Robotics - Hardware Development Engineer Intern/Co-op - 2026 (Robotics, Mechanical, Electrical, Hardware Test, Reliability, Failure Analysis, Operations, and more) | Hardware | Westboro, Massachusetts, USA | Dec 17, 2025 | [Apply](https://www.amazon.jobs/en/jobs/3145033/robotics-hardware-development-engineer-intern-co-op-2026-robotics-mechanical-electrical-hardware-test-reliability-failure-analysis-operations-and-more) |

## Recently posted — cycle not stated  (169 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Hadrian | Software Engineer Intern 🇺🇸 🆕 | Software | Los Angeles, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/hadrian-automation/2b0423c6-947d-4226-8d23-90743bd5e63e) |
| Hadrian | Robotics Engineer Intern 🇺🇸 🆕 | Hardware | Los Angeles, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/hadrian-automation/02e33109-08c5-4db7-8881-67294c172584) |
| Hadrian | Data Science/ Data Engineer Intern 🇺🇸 🆕 | Data & ML/AI | Los Angeles, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/hadrian-automation/f718bcfe-3f5b-4682-a294-697499caf813) |
| Hewlett Packard (HP) | Personal Systems Product Management Intern 🆕 | Software | Austin, Texas, United States of America | Sep 02, 2026 | [Apply](https://hp.wd5.myworkdayjobs.com/ExternalCareerSite/job/Austin-Texas-United-States-of-America/Personal-Systems-Product-Management-Intern_UNI4755-1) |
| Intuitive Surgical ✓ | Mechanical Engineering Intern 🆕 | Hardware | Sunnyvale, CA, United States | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/Intuitive/744000147091674) |
| Lawrence Livermore National Laboratory (LLNL) | Protocol and Special Events Undergraduate AI and Digital Solutions Intern 🇺🇸 🏠 🆕 | Data & ML/AI | Livermore, CA, United States (Remote) | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/LLNL/3743990015035697) |
| Niagara Bottling ✓ | Manufacturing Intern - Atlanta 🆕 | Hardware | Atlanta - Newnan, GA | Sep 02, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Atlanta---Newnan-GA/Manufacturing-Intern---Atlanta_R56049) |
| Niagara Bottling ✓ | Manufacturing Intern - Atlanta 🆕 | Hardware | Atlanta - Newnan, GA | Sep 02, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Atlanta---Newnan-GA/Manufacturing-Intern---Atlanta_R56048) |
| Niagara Bottling ✓ | Manufacturing Intern - Allentown 🆕 | Hardware | Allentown - Allentown, PA | Sep 02, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Allentown---Allentown-PA/Manufacturing-Intern---Allentown_R56046) |
| Reflect Orbital | Embedded Firmware Engineering Intern 🆕 | Hardware | Hawthorne, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/d5ade048-5555-4a77-b002-d117254b6e6b) |
| Reflect Orbital | Flight Software Engineering Intern 🆕 | Software | Hawthorne, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/d2ad1427-89aa-404d-8678-7b8e6dace5e2) |
| Reflect Orbital | Mechanical Engineering Intern 🆕 | Hardware | Hawthorne, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/ed0c926a-9a52-4c84-8488-2552b1f0cca6) |
| Stryker ✓ | Manufacturing Engineering Intern 🆕 | Hardware | San Jose, California | Sep 02, 2026 | [Apply](https://stryker.wd1.myworkdayjobs.com/StrykerCareers/job/San-Jose-California/Manufacturing-Engineering-Intern_R572749-1) |
| Allegion | Mechanical Engineering Intern, Access Technologies – Farmington, Connecticut 🆕 | Hardware | Farmington, CT | Sep 02, 2026 | [Apply](https://allegion.wd5.myworkdayjobs.com/careers/job/Farmington-CT/Mechanical-Engineering-Intern--Access-Technologies---Farmington--Connecticut_JR37466-1) |
| Axcelis Technologies, Inc. ✓ | Manufacturing Engineer Co-op Production Support 🆕 | Hardware | Beverly, MA | Sep 02, 2026 | [Apply](https://axcelis.wd1.myworkdayjobs.com/axcelis/job/Beverly-MA/Manufacturing-Engineer-Co-op-Production-Support_12001) |
| Axcelis Technologies, Inc. ✓ | Manufacturing Test Development Co-op 🆕 | Hardware | Beverly, MA | Sep 02, 2026 | [Apply](https://axcelis.wd1.myworkdayjobs.com/axcelis/job/Beverly-MA/Manufacturing-Test-Development-Co-op_12009) |
| Axcelis Technologies, Inc. ✓ | Manufacturing Test Development Engineer Co-op 🆕 | Hardware | Beverly, MA | Sep 02, 2026 | [Apply](https://axcelis.wd1.myworkdayjobs.com/axcelis/job/Beverly-MA/Manufacturing-Test-Development-Engineer-Co-op_12010) |
| Copart ✓ | Software Engineering Intern 🆕 | Software | Dallas, TX - Headquarters | Sep 02, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR111173) |
| Hewlett Packard (HP) | Software Product Security Engineer Intern 🆕 | Security | Spring, Texas, United States of America | Sep 02, 2026 | [Apply](https://hp.wd5.myworkdayjobs.com/ExternalCareerSite/job/Spring-Texas-United-States-of-America/Software-Product-Security-Engineer-Intern_UNI4744-1) |
| Flagship Pioneering | Pioneering Intelligence: Agentic AI Co-Op 🆕 | Data & ML/AI | Cambridge, MA USA | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/fspco-op012325/jobs/8769080002) |
| National Information Solutions Cooperative (NISC) | Intern - Software Development 🆕 | Software | Cedar Rapids +3 more | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/nisc/jobs/8092699) |
| National Information Solutions Cooperative (NISC) | Intern - Data Engineer 🆕 | Data & ML/AI | Cedar Rapids +3 more | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/nisc/jobs/8167858) |
| Re:Build Manufacturing | Manufacturing Engineer Intern 🆕 | Hardware | Merrimack, NH | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/rebuildmanufacturing/jobs/4729848005) |
| National Information Solutions Cooperative (NISC) | Intern - Data Engineer 🆕 | Data & ML/AI | Cedar Rapids, IA | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/testnisc/jobs/8167883) |
| Sherwin-Williams ✓ | Year-Round IT Co-op, Cybersecurity 🆕 | Security | Cleveland, OH, United States | Sep 02, 2026 | [Apply](https://ejhp.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/2622615) |
| AECOM ✓ | Structural Intern- Hiring Event with AECOM - New York City 🆕 | Hardware | Piscataway, NJ, United States | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000147036623) |
| AECOM ✓ | Structural Intern- Hiring Event with AECOM - New York City 🆕 | Hardware | New York, NY, United States | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000147037399) |
| Winsupply ✓ | Software Developer Intern 🆕 | Software | Moraine, OH, United States | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/Winsupply1/3743990015014717) |
| Magna International | Intern - Engineering Software 🆕 | Software | Southfield, Michigan, US | Sep 02, 2026 | [Apply](https://magna.wd3.myworkdayjobs.com/Magna/job/Southfield-Michigan-US/Intern---Engineering-Software_R00258617) |
| Stryker ✓ | Commercial Operations Software Engineering Intern - Flower Mound, TX 🆕 | Software | Flower Mound, Texas | Sep 02, 2026 | [Apply](https://stryker.wd1.myworkdayjobs.com/StrykerCareers/job/Flower-Mound-Texas/Commercial-Operations-Software-Engineering-Intern---Flower-Mound--TX_R572941) |
| Valmont ✓ | Civil/Structural Engineering Intern 🆕 | Hardware | Tuscaloosa AL | Sep 02, 2026 | [Apply](https://valmont.wd1.myworkdayjobs.com/ValmontCareers/job/Tuscaloosa-AL/Civil-Structural-Engineering-Intern_R28717) |
| Genuine Parts Company ✓ | Software Engineer - QA Analyst Intern 🆕 | Software | Birmingham, AL, USA | Sep 02, 2026 | [Apply](https://genpt.wd1.myworkdayjobs.com/Careers/job/Birmingham-AL-USA/Software-Engineer---QA-Analyst-Intern_R26_0000029235) |
| Genuine Parts Company ✓ | Software Engineer - QA Analyst Intern 🆕 | Software | Birmingham, AL, USA | Sep 02, 2026 | [Apply](https://genpt.wd1.myworkdayjobs.com/Careers/job/Birmingham-AL-USA/Software-Engineer---QA-Analyst-Intern_R26_0000029236) |
| Genuine Parts Company ✓ | Web Developer Intern 🆕 | Software | Birmingham, AL, USA | Sep 02, 2026 | [Apply](https://genpt.wd1.myworkdayjobs.com/Careers/job/Birmingham-AL-USA/Web-Developer-Intern_R26_0000029238) |
| Ingredion | AI & Data Scientist Intern 🆕 | Data & ML/AI | Westchester, IL | Sep 01, 2026 | [Apply](https://ingredion.wd1.myworkdayjobs.com/IngredionCareers/job/Westchester-IL/AI---Data-Scientist-Intern_Req-40007-1) |
| US Foods ✓ | Intern – Data Analyst (Hybrid: Onsite & Remote) 🛂 🏠 🆕 | Data & ML/AI | Rosemont IL | Sep 01, 2026 | [Apply](https://usfoods.wd1.myworkdayjobs.com/usfoodscareersExternal/job/Rosemont-IL/Intern---Data-Analyst--Hybrid--Onsite---Remote-_R282121) |
| US Foods ✓ | Intern – Data Engineer (Hybrid: Onsite & Remote) 🛂 🏠 🆕 | Data & ML/AI | Rosemont IL | Sep 01, 2026 | [Apply](https://usfoods.wd1.myworkdayjobs.com/usfoodscareersExternal/job/Rosemont-IL/Intern---Data-Engineer--Hybrid--Onsite---Remote-_R282116) |
| US Foods ✓ | Intern – Software Engineer, Digital Commerce (Hybrid: Onsite & Remote) 🛂 🏠 🆕 | Software | Rosemont IL | Sep 01, 2026 | [Apply](https://usfoods.wd1.myworkdayjobs.com/usfoodscareersExternal/job/Rosemont-IL/Intern---Software-Engineer--Digital-Commerce--Hybrid--Onsite---Remote-_R282111) |
| Altera Corporation ✓ | Graduate Intern - Engineering Infrastructure 🆕 | Software | San Jose, California, United States | Sep 01, 2026 | [Apply](https://altera.wd1.myworkdayjobs.com/altera/job/San-Jose-California-United-States/Graduate-Intern---Engineering-Infrastructure_R03066) |
| Rockwell Automation ✓ | Intern, Content IDE Software Development (LCS) 🛂 🆕 | Software | Mayfield Heights, Ohio, United States | Sep 01, 2026 | [Apply](https://rockwellautomation.wd1.myworkdayjobs.com/External_Rockwell_Automation/job/Mayfield-Heights-Ohio-United-States/Intern--Content-IDE-Software-Development--LCS-_R26-5010-2) |
| Rockwell Automation ✓ | Intern, Cyber Professional Services (LCS) 🛂 🆕 | Security | Mayfield Heights, Ohio, United States | Sep 01, 2026 | [Apply](https://rockwellautomation.wd1.myworkdayjobs.com/External_Rockwell_Automation/job/Mayfield-Heights-Ohio-United-States/Intern--Cyber-Professional-Services--LCS-_R26-5042-2) |
| Valon | Software Engineer Intern 🆕 | Software | New York | Sep 01, 2026 | [Apply](https://jobs.ashbyhq.com/valon/b5a62c0c-823c-42dd-8cb5-e4b1455bcc64) |
| Eulerity | Backend Developer Intern 🆕 | Software | New York, New York | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/eulerity/jobs/4709040006) |
| Brunswick ✓ | Mercury Marine: Mechatronics Intern 🆕 | Hardware | Fond du Lac, WI | Sep 01, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Fond-du-Lac-WI/Mercury-Marine--Mechatronics-Intern_JR-051269) |
| CWAN | Product Management Intern 🆕 | Software | Office - New York | Sep 01, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Product-Management-Intern_R12200) |
| CWAN | Quant Developer Intern 🆕 | Quant | Office - New York | Sep 01, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Quant-Developer-Intern_R12182) |
| CWAN | Quant Developer Intern 🆕 | Quant | Office - New York | Sep 01, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Quant-Developer-Intern_R12183) |
| Stryker ✓ | Mechanical Engineering Intern 🆕 | Hardware | Redmond, Washington | Sep 01, 2026 | [Apply](https://stryker.wd1.myworkdayjobs.com/StrykerCareers/job/Redmond-Washington/Mechanical-Engineering-Intern_R572728) |
| Valmont ✓ | Civil/Structural Engineering Intern 🆕 | Hardware | Bellville TX | Sep 01, 2026 | [Apply](https://valmont.wd1.myworkdayjobs.com/ValmontCareers/job/Bellville-TX/Civil-Structural-Engineering-Intern_R28720) |
| Avav | Software Engineering Intern 🇺🇸 🆕 | Software | Sunrise, FL | Sep 01, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Sunrise-FL/Software-Engineering-Intern_8589) |
| Greenheck Group | Manufacturing Operations Co-op (WI) 🆕 | Hardware | Schofield, WI | Sep 01, 2026 | [Apply](https://greenheckgroup.wd5.myworkdayjobs.com/external/job/Schofield-WI/Manufacturing-Operations-Co-op--WI-_JR104525) |
| Northern Trust ✓ | Technology Intern – Data Science and Analytics 🛂 🆕 | Data & ML/AI | Chicago, IL | Sep 01, 2026 | [Apply](https://ntrs.wd1.myworkdayjobs.com/northerntrust/job/Chicago-IL/Technology-Intern---Data-Science-and-Analytics_R160865-1) |
| Northern Trust ✓ | Technology Intern – Information Security 🛂 🆕 | Security | Chicago, IL | Sep 01, 2026 | [Apply](https://ntrs.wd1.myworkdayjobs.com/northerntrust/job/Chicago-IL/Technology-Intern---Information-Security_R160869-1) |
| Northern Trust ✓ | Technology Intern – Infrastructure and IT Management 🛂 🆕 | Software | Chicago, IL | Sep 01, 2026 | [Apply](https://ntrs.wd1.myworkdayjobs.com/northerntrust/job/Chicago-IL/Technology-Intern---Infrastructure-and-IT-Management_R160872-1) |
| Intuitive Surgical ✓ | Mechanical Engineering Intern 🆕 | Hardware | Sunnyvale, CA, United States | Sep 01, 2026 | [Apply](https://jobs.smartrecruiters.com/Intuitive/744000146769559) |
| Mondelez International | Manufacturing Intern– Process Engineering 🆕 | Hardware | East Hanover, New Jersey, United States | Sep 01, 2026 | [Apply](https://wd3.myworkdaysite.com/recruiting/mdlz/External/job/East-Hanover-New-Jersey-United-States/Manufacturing-Intern--Process-Engineering_R-175409) |
| Tencent ✓ | Tencent Cloud CPaaS Product Management Intern 🆕 | Software | US-California-Los Angeles | Sep 01, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Los-Angeles/Tencent-Cloud-CPaaS-Product-Management-Intern_R108020) |
| Tencent ✓ | AI Business Analyst Intern 🆕 | Data & ML/AI | US-California-Palo Alto | Sep 01, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/AI-Business-Analyst-Intern_R108039-1) |
| Tencent ✓ | Tencent Cloud CPaaS Product Management Intern 🆕 | Software | US-California-Palo Alto | Sep 01, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/Tencent-Cloud-CPaaS-Product-Management-Intern_R108019) |
| TRUMPF | CNC Programming Intern 🆕 | Software | Farmington, CT | Sep 01, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Farmington-CT/CNC-Programming-Intern_R00042595) |
| TRUMPF | Industrial Engineering Internship 🆕 | Hardware | Farmington, CT | Sep 01, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Farmington-CT/Industrial-Engineering-Internship_R00042497) |
| TRUMPF | Manufacturing Intern 🆕 | Hardware | Farmington, CT | Sep 01, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Farmington-CT/Manufacturing-Intern_R00042282) |
| Olsson | Structural Engineering Internship - Facilities 🆕 | Hardware | Omaha, NE | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5394118008) |
| Olsson | Mechanical Engineering Internship - Healthcare Facilities 🆕 | Hardware | Dallas, TX; Fort Worth, TX | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5394239008) |
| Olsson | Mechanical Engineering Internship - Healthcare Facilities 🆕 | Hardware | Omaha, NE | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5394243008) |
| Brunswick ✓ | Mercury Marine: Materials Engineering Co-op 🆕 | Hardware | Fond du Lac, WI | Sep 01, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Fond-du-Lac-WI/Mercury-Marine--Materials-Engineering-Co-op_JR-051139) |
| CAE | Mechanical Engineering Intern 🇺🇸 🆕 | Hardware | Arlington, TX | Sep 01, 2026 | [Apply](https://cae.wd3.myworkdayjobs.com/career/job/Arlington-TX/Mechanical-Engineering-Intern_123480) |
| AECOM ✓ | Structural Engineering Intern - Hiring Event with AECOM - Philadelphia 🇺🇸 🆕 | Hardware | Conshohocken, PA, United States | Sep 01, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000146596391) |
| The Travelers Companies | Product Management Development Program (PMDP) Intern 🛂 🆕 | Software | CT - Hartford | Sep 01, 2026 | [Apply](https://travelers.wd5.myworkdayjobs.com/External/job/CT---Hartford/Product-Management-Development-Program--PMDP--Intern_R-52317) |
| Emerson Electric | AI Engineering Co-Op 🆕 | Data & ML/AI | Marshalltown, IA, United States | Sep 01, 2026 | [Apply](https://hdjq.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26007510) |
| Emerson Electric | Software Engineering Co-Op 🆕 | Software | Marshalltown, IA, United States | Sep 01, 2026 | [Apply](https://hdjq.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26008442) |
| Emerson Electric | Embedded Software Co-Op 🆕 | Software | Marshalltown, IA, United States | Sep 01, 2026 | [Apply](https://hdjq.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26008443) |
| Pluralis Research | Research Scientist Intern 🆕 | Data & ML/AI | USA or Australia | Aug 31, 2026 | [Apply](https://jobs.ashbyhq.com/pluralis-research/c8f78978-a693-4863-bcc0-66af5c3fd0be) |
| Katalyst Space Technologies | Engineering Intern (Electrical / Mechanical / GNC / Software) 🇺🇸 🆕 | Hardware | Broomfield, Colorado, United States | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/katalyst/jobs/6176711004) |
| Stripe ✓ | Software Engineer, Intern (Summer or Winter) 🆕 | Software | San Francisco, Seattle, New York City | Aug 31, 2026 | [Apply](https://stripe.com/jobs/search?gh_jid=8128745) |
| Integra FEC | (SPRING) Data Analyst Intern 🛂 | Data & ML/AI | Austin, Texas | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/integra/jobs/5406100008) |
| Integra FEC | (SUMMER) Data Analyst Intern 🛂 | Data & ML/AI | Austin, Texas | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/integra/jobs/5406109008) |
| Integra FEC | (SPRING) Data Analyst Intern 🛂 | Data & ML/AI | Austin, Texas | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/integrainterns/jobs/5406101008) |
| Bosch | Calibration Process Data Science Intern (8 months/40 hours per week) | Data & ML/AI | Farmington Hills, MI, United States | Aug 31, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000146546699) |
| Bosch | Software Engineering Intern (8 months/40hrs per week) | Software | Farmington Hills, MI, United States | Aug 31, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000146546849) |
| Bosch | AI Application Intern (8 months/40 hours per week) | Data & ML/AI | Farmington Hills, MI, United States | Aug 31, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000146547599) |
| Brunswick ✓ | Mercury Marine: Software Controls Engineering Intern | Software | Fond du Lac, WI | Aug 31, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Fond-du-Lac-WI/Mercury-Marine--Software-Controls-Engineering-Intern_JR-051436) |
| Dairyland Power Cooperative | Intern, Energy Data Analyst | Data & ML/AI | La Crosse, Wisconsin | Aug 31, 2026 | [Apply](https://dairynet.wd1.myworkdayjobs.com/DPCcareers/job/La-Crosse-Wisconsin/Intern--Energy-Data-Analyst_JR101052) |
| Dairyland Power Cooperative | Intern, Energy Data Science | Data & ML/AI | La Crosse, Wisconsin | Aug 31, 2026 | [Apply](https://dairynet.wd1.myworkdayjobs.com/DPCcareers/job/La-Crosse-Wisconsin/Intern--Energy-Data-Science_JR101053) |
| Leidos ✓ | Manufacturing/Quality Intern 🇺🇸 | Hardware | Huntsville, AL | Aug 31, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Huntsville-AL/Manufacturing-Quality-Intern_R-00190547) |
| Marmon Holdings | AI Intern | Data & ML/AI | Sauget, IL | Aug 31, 2026 | [Apply](https://marmon.wd501.myworkdayjobs.com/Marmon_Careers/job/Sauget-IL/AI-Intern_JR0000045510) |
| Micron Technology ✓ | Intern - AI Systems and Infrastructure Engineering | Data & ML/AI | Austin, TX | Aug 31, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Austin-TX/Intern---AI-Systems-and-Infrastructure-Engineering_JR109990) |
| Nike ✓ | NIKE, Inc. Software Engineering Undergraduate Internship | Software | Beaverton, Oregon | Aug 31, 2026 | [Apply](https://nike.wd1.myworkdayjobs.com/nke/job/Beaverton-Oregon/NIKE--Inc-Software-Engineering-Undergraduate-Internship_R-91111) |
| IGS Energy | Software Engineer Intern 🛂 🏠 | Software | Ohio Remote | Aug 31, 2026 | [Apply](https://igsenergy.wd1.myworkdayjobs.com/IGS/job/Ohio-Remote/Software-Engineer-Intern_R6263) |
| Nike ✓ | NIKE, Inc. Artificial Intelligence, Data, & Machine Learning Engineering Undergraduate Internship | Data & ML/AI | Beaverton, Oregon | Aug 31, 2026 | [Apply](https://nike.wd1.myworkdayjobs.com/nke/job/Beaverton-Oregon/NIKE--Inc-Artificial-Intelligence--Data----Machine-Learning-Engineering-Undergraduate-Internship_R-91110) |
| Booz Allen ✓ | University – Summer 27, Cybersecurity Analyst Intern 🇺🇸 | Security | McLean, VA | Aug 28, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/McLean-VA/University---Summer-27--Cybersecurity-Analyst-Intern_R0248214) |
| Booz Allen ✓ | AI Software Developer Intern 🇺🇸 | Data & ML/AI | San Diego, CA | Aug 28, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/San-Diego-CA/AI-Software-Developer-Intern_R0248115) |
| Xaira Therapeutics | AI Scientist Intern, Computational Protein Design | Data & ML/AI | Seattle +5 more | Aug 28, 2026 | [Apply](https://job-boards.greenhouse.io/xairatherapeutics/jobs/5225658007) |
| Re:Build Manufacturing | Process & Mechanical Engineer Co-op/Intern | Hardware | Rochester, NY | Aug 28, 2026 | [Apply](https://job-boards.greenhouse.io/rebuildmanufacturing/jobs/4728423005) |
| Ambarella ✓ | Software Architecture Engineer Intern | Software | US Headquarters | Aug 27, 2026 | [Apply](https://ambarella.wd108.myworkdayjobs.com/ambarella/job/US-Headquarters/Software-Architecture-Engineer-Intern_JR100365) |
| Ambarella ✓ | Software Development Engineer Intern | Software | US Headquarters | Aug 27, 2026 | [Apply](https://ambarella.wd108.myworkdayjobs.com/ambarella/job/US-Headquarters/Software-Development-Engineer-Intern_JR100366-1) |
| Ambarella ✓ | Software Engineer Intern | Software | US Headquarters | Aug 27, 2026 | [Apply](https://ambarella.wd108.myworkdayjobs.com/ambarella/job/US-Headquarters/Software-Engineer-Intern_JR100363) |
| Micron Technology ✓ | Intern - Technical Customer Management, AI | Data & ML/AI | Longmont-MAX- Office, CO | Aug 27, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Longmont-MAX--Office-CO/Intern---Technical-Customer-Management--AI_JR109454) |
| PSECU | Data Analyst Intern | Data & ML/AI | Harrisburg, PA | Aug 27, 2026 | [Apply](https://psecu.wd12.myworkdayjobs.com/PSECU/job/Harrisburg-PA/Data-Analyst-Intern_JR100964) |
| ROCKWOOL Group | Product Management - Intern | Software | Chicago, Illinois | Aug 27, 2026 | [Apply](https://rockwoolgroup.wd3.myworkdayjobs.com/ROCKWOOL/job/Chicago-Illinois/Product-Management---Intern_R0035795) |
| Customers Bank | AI Innovation Risk Co-Op 🛂 | Data & ML/AI | Malvern, PA | Aug 26, 2026 | [Apply](https://customersbank.wd1.myworkdayjobs.com/customersbankcareers/job/Malvern-PA/AI-Innovation-Risk-Co-Op_REQ-2026-978) |
| Ancestry ✓ | Software Engineer – Observability, Co-op | Software | Draper, Utah | Aug 26, 2026 | [Apply](https://ancestry.wd501.myworkdayjobs.com/Careers/job/Draper-Utah/Software-Engineer---Observability--Co-op_R003434) |
| Chemours | AI & Data Science Intern 🏠 | Data & ML/AI | US - Remote | Aug 26, 2026 | [Apply](https://chemours.wd103.myworkdayjobs.com/Chemours/job/US---Remote/AI---Data-Science-Intern_JR15013) |
| Maximor AI | Software engineering Intern | Software | New York City | Aug 25, 2026 | [Apply](https://jobs.ashbyhq.com/maximor/3ff6e57d-5430-4836-b6f0-19044d8ee6d8) |
| Nokia ✓ | Deepfield Software Engineer Co-op | Software | United States | Aug 25, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/39908) |
| Meridian Partners | Embedded Software Engineer Graduate Co-op 🇺🇸 | Software | Cambridge, MA | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/morsecorpcoop/jobs/7968523003) |
| Meridian Partners | Embedded Software Engineer Co-op 🇺🇸 | Software | Cambridge, MA | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/morsecorpcoop/jobs/7968605003) |
| Meridian Partners | Front End Software Engineer Co-op 🇺🇸 | Software | Cambridge, MA | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/morsecorpcoop/jobs/7967961003) |
| Canadian Solar | Data Analyst, Quality Intern | Data & ML/AI | Mesquite, TX | Aug 24, 2026 | [Apply](https://canadiansolar.wd5.myworkdayjobs.com/CanadianSolar/job/Mesquite-TX/Data-Analyst--Quality-Intern_10001414) |
| Monolithic Power Systems ✓ | AI Developer Intern | Data & ML/AI | San Jose - California | Aug 24, 2026 | [Apply](https://monolithicpower.wd12.myworkdayjobs.com/MPS_Careers/job/San-Jose---California/AI-Developer-Intern_R-1756) |
| Audax Group | Data Engineer Co-Op | Data & ML/AI | Boston, Massachusetts | Aug 24, 2026 | [Apply](https://job-boards.greenhouse.io/audaxgroup/jobs/4722770005) |
| Micron Technology ✓ | Intern - TD Site Industrial Engineer | Hardware | Boise, ID - Main Site | Aug 23, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Boise-ID---Main-Site/Intern---TD-Site-Industrial-Engineer_JR108729) |
| Atoms | Robotics Software Engineer Intern | Hardware | Pittsburgh, PA | Aug 21, 2026 | [Apply](https://job-boards.greenhouse.io/cssmerge/jobs/8695475002) |
| Atoms | Mechanical Design Engineering Intern‬ | Hardware | Pittsburgh, PA | Aug 21, 2026 | [Apply](https://job-boards.greenhouse.io/cssmerge/jobs/8695490002) |
| Ambrook | Software Engineering Intern | Software | New York | Aug 21, 2026 | [Apply](https://jobs.ashbyhq.com/ambrook/e458b046-aa7f-4022-bca5-63cdfd495456) |
| Weave | Data Engineer Intern | Data & ML/AI | Weave - Headquarters (Lehi, UT) | Aug 21, 2026 | [Apply](https://jobs.ashbyhq.com/weave/1318e017-3ea6-4a1f-aac7-1c11a46cda8d) |
| Syska Hennessy Group | Innovations Intern (Full Stack/Front End Engineering) | Software | New York | Aug 21, 2026 | [Apply](https://job-boards.greenhouse.io/syskahennessy/jobs/8147733) |
| H3X Technologies | Embedded Controls Intern (Spring) | Software | Louisville, Colorado | Aug 21, 2026 | [Apply](https://jobs.ashbyhq.com/h3x-technologies/d406e4b4-9b48-438c-a2af-b7feb8563a40) |
| Heidelberg Materials | Mechanical Engineering Intern | Hardware | Nazareth, PA | Aug 21, 2026 | [Apply](https://heidelbergmaterials.wd3.myworkdayjobs.com/global_hm_career_site/job/Nazareth-PA/Mechanical-Engineering-Intern_JR10018120) |
| Magna International | Intern - Engineering Mechanical Optics | Hardware | Auburn Hills, Michigan, US | Aug 21, 2026 | [Apply](https://magna.wd3.myworkdayjobs.com/Magna/job/Auburn-Hills-Michigan-US/Student---Engineering-Mechanical-Optics_R00256153) |
| Phoebe | Software Engineering Intern | Software | New York City | Aug 20, 2026 | [Apply](https://jobs.ashbyhq.com/phoebe-work/1ffe3e63-2163-447e-a8b0-1fff8b87e0ca) |
| Scotts Miracle-Gro | EHS Manufacturing Intern | Hardware | Marysville, OH | Aug 20, 2026 | [Apply](https://scottsmiraclegro.wd5.myworkdayjobs.com/smgexternal/job/Marysville-OH/EHS-Manufacturing-Intern_R26379-1) |
| Western Magnetics | Software Engineering Intern | Software | South San Francisco +2 more | Aug 20, 2026 | [Apply](https://apply.workable.com/western-magnetics/j/E366930F3F/) |
| Copart ✓ | Site Reliability Engineer Intern | Software | Dallas, TX - Headquarters | Aug 19, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Site-Reliability-Engineer-Intern_JR110631) |
| N1 | Software Engineer Intern (Backend, Rust) | Software | New York City | Aug 19, 2026 | [Apply](https://jobs.ashbyhq.com/n1/afe7deb5-9cfd-4926-bcb4-058d418592a6) |
| North Wind Group | Structural Engineering Intern 04206 LBYD | Hardware | HUNTSVILLE, AL | Aug 19, 2026 | [Apply](https://north-wind-group.breezy.hr/p/206627bdd565-structural-engineering-intern-04206-lbyd) |
| Johnson & Johnson | Automation & Robotics Engineering Spring Co-op | Hardware | Santa Clara +2 more | Aug 19, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Santa-Clara-California-United-States-of-America/Automation---Robotics-Engineering-Spring-Co-op_R-093526) |
| Garda Capital Partners | Software Engineer Intern | Software | New York, New York, United States | Aug 18, 2026 | [Apply](https://job-boards.greenhouse.io/gardacp/jobs/6146213004) |
| H3X Technologies | Mechanical Design Engineer Intern (Spring) | Hardware | Louisville, Colorado | Aug 18, 2026 | [Apply](https://jobs.ashbyhq.com/h3x-technologies/7add5fe2-8e3e-4817-b88a-34d803ba86f9) |
| Amcor | Intern - AI Innovation Engineer | Data & ML/AI | ASC Atlanta HQ GA | Aug 18, 2026 | [Apply](https://amcor.wd5.myworkdayjobs.com/amcor_external_career_site/job/ASC-Atlanta-HQ-GA/AI-Innovation-Engineer_REQ_93190) |
| American Fidelity | Cyber Security Intern (OKC Local Only) | Security | Oklahoma City, Oklahoma | Aug 17, 2026 | [Apply](https://americanfidelity.wd5.myworkdayjobs.com/External/job/Oklahoma-City-Oklahoma/Cyber-Security-Intern--OKC-Local-Only-_JR1023) |
| Intel ✓ | Software Development Graduate Intern | Software | US, California, Folsom | Aug 17, 2026 | [Apply](https://intel.wd1.myworkdayjobs.com/external/job/US-California-Folsom/Software-Development-Graduate-Intern_JR0285451-1) |
| ACDS | Align AI Software Development Intern | Data & ML/AI | Bentonville, AR | Aug 17, 2026 | [Apply](https://jobs.lever.co/acds/5a872bb7-8d9f-46e3-9e72-f5c69445e787) |
| Toyota Research Institute ✓ | Robotics Research Intern - Post-Training | Hardware | Los Altos, CA | Aug 17, 2026 | [Apply](https://jobs.lever.co/tri/186808f9-464c-4f22-9d7d-4372ef272ff0) |
| Datadog ✓ | Product Management Intern | Software | New York, New York, USA | Aug 17, 2026 | [Apply](https://careers.datadoghq.com/detail/8108241/?gh_jid=8108241) |
| Crowe ✓ | Data Analytics Developer Intern | Data & ML/AI | Chicago IL USA | Aug 14, 2026 | [Apply](https://crowe.wd12.myworkdayjobs.com/external_careers/job/Chicago-IL-USA/Data-Analytics-Developer-Intern_R-71041) |
| Crowe ✓ | AI Project Coordinator Intern | Data & ML/AI | Chicago IL USA | Aug 14, 2026 | [Apply](https://crowe.wd12.myworkdayjobs.com/external_careers/job/Chicago-IL-USA/AI-Project-Coordinator-Intern_R-71007) |
| TransMarket Group | Software Engineering Intern | Software | Chicago, Illinois, United States | Aug 14, 2026 | [Apply](https://job-boards.greenhouse.io/transmarketgroup/jobs/5212335007?gh_jid=5212335007) |
| Interco | Paid Internship -- Software Development -- React 🛂 | Software | St. Louis, MO, United States | Aug 13, 2026 | [Apply](https://jobs.smartrecruiters.com/Interco/744000143346169) |
| Crowe ✓ | AI Engineering Intern | Data & ML/AI | Chicago IL USA | Aug 13, 2026 | [Apply](https://crowe.wd12.myworkdayjobs.com/external_careers/job/Chicago-IL-USA/AI-Engineering-Intern_R-51782) |
| Exa Labs | Software Engineer, Intern | Software | San Francisco, California | Aug 13, 2026 | [Apply](https://jobs.ashbyhq.com/exa/a9e01521-66f1-481b-89da-ec01d4620f16) |
| ConnectPrep | Data Analyst Internship 🇺🇸 🏠 | Data & ML/AI | Washington +2 more | Aug 13, 2026 | [Apply](https://apply.workable.com/connectprep/j/D1C67258C0/) |
| American Fidelity | Software Dev Internship (OKC local only) | Software | Oklahoma City, Oklahoma | Aug 12, 2026 | [Apply](https://americanfidelity.wd5.myworkdayjobs.com/External/job/Oklahoma-City-Oklahoma/Software-Dev-Internship_JR1005) |
| Booz Allen ✓ | AI RAN Telecommunications Engineer Intern 🇺🇸 | Data & ML/AI | McLean, VA | Aug 11, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/McLean-VA/AI-RAN-Telecommunications-Engineer-Intern_R0246869) |
| Odys Aviation | Mechanical Engineering Intern/Co-Op [Propulsion] | Hardware | Long Beach CA | Aug 11, 2026 | [Apply](https://jobs.ashbyhq.com/odys-aviation/8f5e460a-98a4-4fd8-b880-d22071faa29f) |
| Ameren ✓ | Mechanical Engineering Fall Co-Op | Hardware | St. Louis, MO | Aug 11, 2026 | [Apply](https://ameren.wd1.myworkdayjobs.com/External/job/St-Louis-MO/Mechanical-Engineering-Fall-Co-Op_034018-1) |
| Ameren ✓ | Mechanical Engineering Spring Co-Op | Hardware | St. Louis, MO | Aug 11, 2026 | [Apply](https://ameren.wd1.myworkdayjobs.com/External/job/St-Louis-MO/Mechanical-Engineering-Spring-Co-Op_034022-1) |
| 1X | Internship - Manufacturing Engineering (Fall) | Hardware | San Carlos, CA | Aug 10, 2026 | [Apply](https://jobs.ashbyhq.com/1x/7d93444c-01f5-485c-89ef-24164f30441d) |
| Canadian Solar | Intern, IT Infrastructure Support | Software | Walnut Creek, CA | Aug 10, 2026 | [Apply](https://canadiansolar.wd5.myworkdayjobs.com/CanadianSolar/job/Walnut-Creek-CA/Intern--IT-Infrastructure-Support_10001383) |
| Teledyne | Mechanical Engineering Intern 🇺🇸 | Hardware | US - Miamisburg, OH | Aug 10, 2026 | [Apply](https://flir.wd1.myworkdayjobs.com/flircareers/job/US---Miamisburg-OH/Mechanical-Engineering-Intern_REQ35562) |
| Field AI | Mechanical Engineer, Robotics Hardware - Part-Time Internship | Hardware | Irvine, CA | Aug 10, 2026 | [Apply](https://jobs.lever.co/field-ai/88f05d6e-ee93-4fc5-80cd-efe6854e22bc) |
| Copart ✓ | Software Engineering Intern | Software | Dallas, TX - Headquarters | Aug 07, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR101510) |
| Moog | Intern, Industrial Engineering | Hardware | Buffalo, NY | Aug 07, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Industrial-Engineering_R-26-19319) |
| Centerfield ✓ | Frontend Engineer Intern (6 month internship) | Software | Los Angeles, California | Aug 06, 2026 | [Apply](https://jobs.ashbyhq.com/centerfield/1d7eacc1-37f7-478c-9b0a-fa7974f1a9e4) |
| Draper | Embedded Quality & Fielded Systems Intern | Software | Cambridge, MA | Aug 05, 2026 | [Apply](https://draper.wd5.myworkdayjobs.com/Draper_Careers/job/Cambridge-MA/Embedded-Quality---Fielded-Systems-Intern_JR002718) |
| Diversified Automation | Software Engineering Co-op | Software | Louisville, KY | Aug 04, 2026 | [Apply](https://jobs.lever.co/diversified-automation/827a092d-b8a3-4ca9-a84a-e8c236d1aabc) |
| TSC | Robotics Intern 🇺🇸 | Hardware | Washington +1 more | Aug 04, 2026 | [Apply](https://tsc.wd12.myworkdayjobs.com/TSC-Careers/job/Washington-DC---Naval-Research-Laboratory/Robotics-Intern_JR2713) |
| IDEXX ✓ | Security Operations (Cybersecurity) internship | Security | Westbrook, ME | Aug 03, 2026 | [Apply](https://idexx.wd1.myworkdayjobs.com/IDEXX/job/Westbrook-ME/Security-Operations--Cybersecurity--internship_J-053268) |
| IMEG ✓ | Structural Engineering Intern / Raleigh, NC | Hardware | Raleigh, NC | Aug 03, 2026 | [Apply](https://wd1.myworkdaysite.com/recruiting/imeg/Imeg_Careers/job/Raleigh-NC/Structural-Engineering-Intern---Raleigh--NC_R-16319-1) |
| Yotta Labs | Research Engineer Intern - AI Systems | Data & ML/AI | United States | Aug 02, 2026 | [Apply](https://jobs.ashbyhq.com/yotta/09821a51-fbe6-42a7-a566-0d2b5d40fae3) |
| Skydio ✓ | Hardware Product Management Intern | Hardware | San Mateo, California, United States | Jul 31, 2026 | [Apply](https://jobs.ashbyhq.com/skydio/1ec2fe3c-3fb2-4485-870d-764a3e5f5baf) |
| Modal | ML Research Intern | Data & ML/AI | New York | Jul 28, 2026 | [Apply](https://jobs.ashbyhq.com/modal/38888294-6bc7-4dab-b072-6d0f0c2ed79a) |
| CCC Intelligent Solutions ✓ | Applied AI Engineering Intern | Data & ML/AI | Chicago (Green St), IL | Jul 27, 2026 | [Apply](https://cccis.wd1.myworkdayjobs.com/broadbean_external/job/Chicago-Green-St-IL/Applied-AI-Engineering-Intern_0014827) |
| Core & Main | Intern - AI/ML Data Engineering  -  Onsite - St. Louis | Data & ML/AI | Saint Louis, MO 63146 | Jul 24, 2026 | [Apply](https://coreandmain.wd1.myworkdayjobs.com/coreandmain/job/Saint-Louis-MO-63146/Intern---Data-Engineering----Corp_45804) |
| Tenstorrent ✓ | Software Engineering Intern, Power Modeling & AI Tools | Data & ML/AI | Santa Clara, California, United States | Jul 23, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5186916007) |
| Pony.ai ✓ | Research Intern - Deep Learning | Data & ML/AI | Fremont, California, United States | Jul 22, 2026 | [Apply](https://apply.workable.com/pony-dot-ai/j/4C1F53EF5D/) |
| Pony.ai ✓ | Software Engineer Intern - Generalist | Software | Fremont, California, United States | Jul 22, 2026 | [Apply](https://apply.workable.com/pony-dot-ai/j/BA5FFDBC71/) |
| Moog | Intern, Software Engineering | Software | Buffalo, NY | Jul 22, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Software-Engineering_R-26-18885-1) |
| ACDS | AI Operations Intern-Caddell Reynolds | Data & ML/AI | Fort Smith, AR | Jul 20, 2026 | [Apply](https://jobs.lever.co/acds/01fdf41b-a835-4e00-8d01-0275677a8f08) |

<a id="drop-radar"></a>

## 📅 Drop Radar — when companies usually post for Summer 2027

Stop refreshing career pages. 🎯 = the employer's **own posted date**, read from their careers API. (We may have discovered the role after it went live — the date is the employer's, not our discovery time.) The rest are typical opening **months**, hand-checked against each company's careers page and public recruiting guides. ✅ = already live in the list above.

> **Heads up:** companies trend *earlier* every cycle, and "~Aug" is a month, not a day. Treat "expected" as when to **start watching**, and "rolling" companies as worth checking year-round.

| Company | Typical opening | Expected this cycle | Status |
|---|---|---|---|
| Citadel | ~Aug | ~Aug · any day now | ⏳ waiting |
| Citadel Securities | ~Aug | ~Aug · any day now | ⏳ waiting |
| DoorDash | ~Aug | ~Aug · any day now | ⏳ waiting |
| DRW | ~Aug | ~Aug · any day now | ⏳ waiting |
| Google | ~Aug | ~Aug · any day now | ⏳ waiting |
| Jane Street | ~Aug | ~Aug · any day now | ⏳ waiting |
| Meta | ~Aug | ~Aug · any day now | ⏳ waiting |
| Optiver | ~Aug | ~Aug · any day now | ⏳ waiting |
| Pinterest | ~Aug | ~Aug · any day now | ⏳ waiting |
| Salesforce | ~Aug | ~Aug · any day now | ⏳ waiting |
| SIG | ~Aug | ~Aug · any day now | ⏳ waiting |
| Snowflake | ~Aug | ~Aug · any day now | ⏳ waiting |
| Uber | ~Aug | ~Aug · any day now | ⏳ waiting |
| Adobe | ~Sep | ~Sep · any day now | ⏳ waiting |
| Airbnb | ~Sep | ~Sep · any day now | ⏳ waiting |
| Bloomberg | ~Sep | ~Sep · any day now | ⏳ waiting |
| Dropbox | ~Sep | ~Sep · any day now | ⏳ waiting |
| Plaid | ~Sep | ~Sep · any day now | ⏳ waiting |
| Point72 | ~Sep | ~Sep · any day now | ⏳ waiting |
| Robinhood | ~Sep | ~Sep · any day now | ⏳ waiting |
| Stripe | ~Sep | ~Sep · any day now | ⏳ waiting |
| D.E. Shaw | ~Oct | ~Oct · in ~29d | ⏳ waiting |
| Coinbase | ~Dec | ~Dec | ⏳ waiting |
| Ramp | ~Dec | ~Dec | ⏳ waiting |
| Two Sigma | ~Dec | ~Dec | ⏳ waiting |
| Apple | rolling | year-round | ⏳ waiting |
| Datadog | rolling | year-round | ⏳ waiting |
| Jump Trading | rolling | year-round | ⏳ waiting |
| Microsoft | rolling | year-round | ⏳ waiting |
| Millennium | rolling | year-round | ⏳ waiting |

_168 companies on the [full radar](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/#radar). **135** dated from our own live observations 🎯 (this grows every cycle). "~Aug" = hand-verified typical month, not a promise of the day; "rolling" = posts year-round; "waiting" = not seen in our tracked feeds yet, not a guarantee it isn't out somewhere else._

<details>
<summary><strong>Recently closed</strong> — 40 roles that left the list in the last 14 days</summary>

_Why each one left is in the last column, because the two reasons carry different evidence. **Gone from feed** = two consecutive complete reads of the employer's board no longer returned it (strong, but not the employer telling us directly). **Out of scope** = still posted, but it no longer passes our filters — our call, not theirs. **Not recorded** = closed before we started tracking the reason._

| Company | Role | Cycle | Closed | Why |
|---|---|---|---|---|
| DraftKings | Data Science Intern (Summer 2027) | Summer 2027 | 2026-09-02 | gone from feed |
| First National Bank | Summer 2027 AI and Innovation Intern - Pittsburgh, PA | Summer 2027 | 2026-09-02 | gone from feed |
| Motorola | Mission Critical Networks Software Engineer - 2027 Co-op | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Undergraduate Summer Internship Program - 2027 Digital Product Management, Enterprise Technology Services- New York, NY | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Undergraduate Summer Internship Program - 2027 Digital Product Management, Enterprise Technology Services- Sunrise, FL | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Digital Product Management, Enterprise Technology Services- New York, NY | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Digital Product Management, Enterprise Technology Services- Sunrise, FL | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Product Management, Global Merchant & Network Services - New York, NY | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Product Management, Global Merchant & Network Services - Phoenix, AZ | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Undergraduate Summer Internship Program - 2027 Digital Product Management, Enterprise Technology Services- Phoenix, AZ | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Digital Product Management, Enterprise Technology Services- Phoenix, AZ | Summer 2027 | 2026-09-02 | gone from feed |
| Leidos | Cybersecurity Analyst Intern | Summer 2027 | 2026-09-02 | gone from feed |
| Westlake | 2026 Intern - Mechanical Engineer | Fall 2026 | 2026-09-02 | gone from feed |
| American Express | Campus Graduate I Summer Internship Program - 2027 Data Science, Finance - New York, NY | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Graduate II Summer Internship Program - 2027 Data Science, Finance - New York, NY | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Undergraduate Summer Internship Program - 2027 Data Engineer, Enterprise Technology Services- Charlotte, NC | Summer 2027 | 2026-09-02 | gone from feed |
| Grant Thornton | Cybersecurity and Privacy Intern - Summer 2027 | Summer 2027 | 2026-09-02 | gone from feed |
| Stryker | Summer 2027 Internship - Software Engineering - Florida | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Undergraduate Summer Internship Program - 2027 Data Engineer, Enterprise Technology Services- Sunrise, FL | Summer 2027 | 2026-09-02 | gone from feed |
| Stryker | Summer 2027 Internship - Software Engineering - Indiana | Summer 2027 | 2026-09-02 | gone from feed |
| Stryker | Summer 2027 Internship - Software Engineering - Michigan | Summer 2027 | 2026-09-02 | gone from feed |
| American Express | Campus Undergraduate Summer Internship Program - 2027 Data Engineer, Enterprise Technology Services- Phoenix, AZ | Summer 2027 | 2026-09-01 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Data Engineer, Enterprise Technology Services- Phoenix, AZ | Summer 2027 | 2026-09-01 | gone from feed |
| Grant Thornton | AI, Data & Technology Intern - Summer 2027 | Summer 2027 | 2026-09-01 | gone from feed |
| Grant Thornton | AI, Data & Technology Intern - Summer 2027 | Summer 2027 | 2026-09-01 | gone from feed |
| Stantec | Roadway Design Intern - Infrastructure (Summer 2027) | Summer 2027 | 2026-09-01 | gone from feed |
| First National Bank | Summer 2027 Data Science Intern - Pittsburgh, PA | Summer 2027 | 2026-09-01 | gone from feed |
| United Parcel Service (UPS) | UPS Information Security Summer 2027 Internship - NJ | Summer 2027 | 2026-09-01 | gone from feed |
| Grant Thornton | AI, Data & Technology Intern - Summer 2027 | Summer 2027 | 2026-09-01 | gone from feed |
| WSP | Civil/Structural Engineering (Substation) Intern - Summer 2027 | Summer 2027 | 2026-09-01 | gone from feed |
| WSP | Mechanical Engineering Intern - Summer 2027 | Summer 2027 | 2026-09-01 | gone from feed |
| Oshkosh | Engineer Intern - Mechanical (Summer 2027) | Summer 2027 | 2026-09-01 | gone from feed |
| Oshkosh | Engineer Intern - Software (Summer 2027) | Summer 2027 | 2026-09-01 | gone from feed |
| Oshkosh | Engineer Intern - Manufacturing (Summer 2027) | Summer 2027 | 2026-09-01 | gone from feed |
| Stryker | Summer 2027 Internship - Mechanical Engineering - Illinois | Summer 2027 | 2026-09-01 | gone from feed |
| Stryker | Summer 2027 Internship - Mechanical Engineering - Michigan | Summer 2027 | 2026-09-01 | gone from feed |
| Stryker | Summer 2027 Internship - Mechanical Engineering - Arizona | Summer 2027 | 2026-09-01 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Data Engineer, Enterprise Technology Services- Charlotte, NC | Summer 2027 | 2026-09-01 | gone from feed |
| American Express | Campus Graduate Masters Summer Internship Program - 2027 Data Engineer, Enterprise Technology Services- Sunrise, FL | Summer 2027 | 2026-09-01 | gone from feed |
| Auto-Owners Insurance | Software Developer Internship - Summer 2027 | Summer 2027 | 2026-09-01 | gone from feed |

</details>

---

## Hiring timeline

Internships posted per week, from each role's real published date - redrawn automatically on every run. When this line takes off, recruiting season is open:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/trends-dark.svg">
  <img alt="Internships posted per week, drawn from real published dates" src="docs/trends-light.svg">
</picture>

## How it stays current

A small Python engine reads public company hiring feeds directly, keeps the roles that match the scope above, de-duplicates across sources, records each role's published date once (so it never shifts), and regenerates this page through GitHub Actions. It polls every company concurrently (async) with retry/backoff and per-host rate limits. The full source is in this repo.

_Engine (last run): 4,045 of 4,382 registered boards returned successfully across 12 ATS platforms (98% of boards attempted, 92% of the full registry) · completed in 443.9s · 112 board(s) returned a capped result set, so their roles were not eligible to be closed this run · employer or source-derived date on 100% of open roles._

## How this list is built

[METHODOLOGY.md](METHODOLOGY.md) documents exactly what every label claims — what separates a stated cycle from an inferred one, what the ✓ H-1B badge does and doesn't mean, how a role gets closed, and which limitations are known. Anything on this page that doesn't match the code is a bug worth reporting.

## Contributing

Adding a company takes one line, see [CONTRIBUTING.md](CONTRIBUTING.md), or just [open a request](../../issues/new?template=add-company.yml) with the board URL. **Spotted something wrong?** [Report the exact field](../../issues/new?template=wrong-data.yml) — wrong country, wrong cycle, closed role, bad sponsorship flag. Those reports usually fix a rule, which fixes every other role too.

Also here: [PRIVACY.md](PRIVACY.md) (what the email list stores — an address and nothing else) · [SECURITY.md](SECURITY.md) · [ARCHITECTURE.md](ARCHITECTURE.md) · [MIT licensed](LICENSE).

Built by one student with AI assistance, in the open. The part that matters isn't who typed it — it's that the rules, the tests, and every run's output are all public and checkable.

## Note on dates

The **Posted** column shows when a role was published, with the newest at the top. I pull the posting date straight from each job portal, but a lot of them don't expose one publicly, so those rows show a dash (—) for now instead of a guessed date. The ones that do publish a date are dated. Know the real date for a dashed role? Open a PR and I'll merge it.

Roles can close at any time, so always confirm on the company's own site before applying.
