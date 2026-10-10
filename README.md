<div align="center">

# 🎓 Summer 2027 Tech Internships

**A self-updating engine that tracks tech internships so you don't have to.**

[![CI](https://img.shields.io/github/actions/workflow/status/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/ci.yml?branch=main&label=tests&style=flat-square&color=3fb950)](https://github.com/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/actions/workflows/ci.yml)&nbsp;[![Open roles](https://img.shields.io/badge/dynamic/json?label=open%20roles&query=open_total&url=https%3A%2F%2Fheyinihere.github.io%2FAutomated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships%2Fapi%2Fstats.json&color=2f81f7&style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/)&nbsp;![Updates](https://img.shields.io/badge/updates-every%20hour-3fb950?style=flat-square)&nbsp;[![RSS](https://img.shields.io/badge/RSS-subscribe-e67e22?style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/feed.xml)

### 1382 open roles (668 listed below) · 203 new this week

4,640 employers tracked · updated Oct 10, 2026 at 06:58 UTC

_902 have a cycle the employer stated · 480 are recent postings whose cycle isn't stated (listed separately, never mixed in)._

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
- **An engine, not a spreadsheet** - 4,772 job-board endpoints (4,640 distinct employers; some run more than one board) polled every hour across 12 ATS platforms, full source and tests in this repo.

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

## Summer 2027  (300 employer-stated)

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Itron ✓ | Intern - HR AI Data Science (Summer 2027) 🆕 | Data & ML/AI | United States of America, Texas, Austin | Oct 09, 2026 | [Apply](https://itron.wd5.myworkdayjobs.com/Early_Careers/job/United-States-of-America-Texas-Austin/Intern---HR-AI-Data-Science--Summer-2027-_JR103034) |
| Workday ✓ | Cybersecurity Engineer Intern 🛂 🆕 | Security | USA, CA, Pleasanton | Oct 09, 2026 | [Apply](https://workday.wd5.myworkdayjobs.com/Workday_Early_Career/job/USA-CA-Pleasanton/Cybersecurity-Engineer-Intern_JR-0110809) |
| Workday ✓ | Machine Learning Engineer Intern 🛂 🆕 | Data & ML/AI | USA, CA, Pleasanton | Oct 09, 2026 | [Apply](https://workday.wd5.myworkdayjobs.com/Workday_Early_Career/job/USA-CA-Pleasanton/Machine-Learning-Engineer-Intern_JR-0110812) |
| Workday ✓ | Software Application Development Engineer Intern 🛂 🆕 | Software | USA, CA, Pleasanton | Oct 09, 2026 | [Apply](https://workday.wd5.myworkdayjobs.com/Workday_Early_Career/job/USA-CA-Pleasanton/Software-Application-Development-Engineer-Intern_JR-0110811) |
| American Family Insurance Group | Summer 2027 Intern - Data Analyst 🆕 | Data & ML/AI | WI Madison | Oct 09, 2026 | [Apply](https://amfam.wd1.myworkdayjobs.com/AmFamGroupInternCareers/job/WI-Madison/Summer-2027-Intern---Data-Analyst_R39404) |
| General Motors ✓ | 2027 Summer Intern, AI Research, Embodied AI 🆕 | Data & ML/AI | Sunnyvale +2 more | Oct 09, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Sunnyvale-California-United-States-of-America/XMLNAME-2027-Summer-Intern--AI-Research--Embodied-AI_JR-202622146) |
| General Motors ✓ | 2027 Summer Intern, Onboard Autonomy, Embodied AI 🆕 | Data & ML/AI | Sunnyvale +2 more | Oct 09, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Sunnyvale-California-United-States-of-America/XMLNAME-2027-Summer-Intern--Onboard-Autonomy--Embodied-AI_JR-202622135) |
| General Motors ✓ | 2027 Summer Intern, SEAM, Embodied AI 🆕 | Data & ML/AI | Sunnyvale +2 more | Oct 09, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Sunnyvale-California-United-States-of-America/XMLNAME-2027-Summer-Intern--SEAM--Embodied-AI_JR-202622143) |
| Northrop Grumman | 2027 Operations Manufacturing Engineering Intern 🇺🇸 🆕 | Hardware | United States-Florida-Melbourne | Oct 09, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Florida-Melbourne/XMLNAME-2027-Operations-Manufacturing-Engineering-Intern_R10253688) |
| GCM Grosvenor | 2027 Software Engineering Summer Intern 🆕 | Software | Chicago, Illinois, United States | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/gcmgrosvenor/jobs/8015792003) |
| Schonfeld ✓ | 2027 Quantitative Developer Intern 🆕 | Quant | Austin, Texas, United States | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/schonfeld/jobs/8267092) |
| DoorDash ✓ | Software Engineer, Intern - Labs (Summer 2027) 🆕 | Software | San Francisco, CA; Sunnyvale, CA | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/doordashusa/jobs/8263774) |
| IMC Trading | Machine Learning Engineer Intern - Summer 2027 🆕 | Data & ML/AI | New York, United States | Oct 08, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4962456101) |
| SharkNinja ✓ | Summer 2027: Mechanical Engineering Intern, Shark (May to August) 🆕 | Hardware | Needham, MA, United States | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4718812006) |
| Viget | Software Developer Intern (2027) 🛂 🆕 | Software | Boulder, CO | Oct 08, 2026 | [Apply](https://jobs.lever.co/viget/b18cc87d-fca2-485a-a0f2-ad6197db63f2) |
| Alcon ✓ | 2027 Spring/Summer Manufacturing Engineering Co-op 🆕 | Hardware | Houston, Texas | Oct 08, 2026 | [Apply](https://alcon.wd5.myworkdayjobs.com/careers_alcon/job/Houston-Texas/XMLNAME-2027-Spring-Summer-Manufacturing-Engineering-Co-op_R-2026-50147) |
| RTX | Software Engineering Co-op (Spring/Summer 2027) 🇺🇸 🆕 | Software | US-IA-CEDAR RAPIDS-131 ~ 5450 C Ave NE… | Oct 08, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-131--5450-C-Ave-NE--BLDG-131/Software-Engineering-Co-op--Spring-Summer-2027-_01878369) |
| Moog | Intern, Computer Science 🆕 | Software | Torrance, CA | Oct 08, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Torrance-CA/Intern--Computer-Science_R-26-19819) |
| Plastipak | Manufacturing Operations (Engineering) Intern – Summer 2027 🆕 | Hardware | Plastipak - Havre de Grace, MD | Oct 08, 2026 | [Apply](https://plastipak.wd1.myworkdayjobs.com/Plastipak/job/Plastipak---Havre-de-Grace-MD/Manufacturing-Operations--Engineering--Intern---Summer-2027_REQ24670) |
| Sierra Space | Summer 2027 Manufacturing Engineer Intern 🇺🇸 🆕 | Hardware | Broomfield, CO | Oct 08, 2026 | [Apply](https://sierraspace.wd1.myworkdayjobs.com/Sierra_Space_External_Career_Site/job/Broomfield-CO/Summer-2027-Manufacturing-Engineer-Intern_R26389) |
| The Toro Company | Manufacturing Engineering Intern - The Toro Company 🛂 🆕 | Hardware | Shakopee, MN | Oct 08, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Shakopee-MN/Manufacturing-Engineering-Intern---The-Toro-Company_JR17581) |
| The Toro Company | Manufacturing Engineer Intern - The Toro Company 🛂 🆕 | Hardware | Windom, MN | Oct 08, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Windom-MN/Manufacturing-Engineer-Intern---The-Toro-Company_JR17578) |
| Rugged Robotics | Mechanical Engineering Intern/Co-op (Spring or Summer 2027) 🆕 | Hardware | Houston, TX | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/ruggedrobotics/jobs/4730900005) |
| Rugged Robotics | Robotic Software Intern/Co-op (Spring or Summer 2027) 🆕 | Software | Houston, TX | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/ruggedrobotics/jobs/4730908005) |
| Stantec ✓ | Civil/Transportation Engineering Intern - Infrastructure (Summer 2027) 🆕 | Software | Charleston, SC, United States | Oct 08, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1008210) |
| Nissan ✓ | Trim & Chassis Manufacturing Engineering Intern - Summer 2027 - Canton, MS 🆕 | Hardware | Canton +1 more | Oct 08, 2026 | [Apply](https://alliance.wd3.myworkdayjobs.com/nissanjobs/job/Canton-Mississippi---United-States-of-America/Trim---Chassis-Manufacturing-Engineering-Intern---Summer-2027---Canton--MS_R00214255) |
| Nissan ✓ | Manufacturing Digital Data Intern - Summer 2027 - Decherd, TN 🆕 | Data & ML/AI | Decherd +1 more | Oct 08, 2026 | [Apply](https://alliance.wd3.myworkdayjobs.com/nissanjobs/job/Decherd-Tennessee---United-States-of-America/Manufacturing-Digital-Data-Intern---Summer-2027---Decherd--TN_R00214881) |
| Modernizing Medicine | Software Engineering Intern 🆕 | Software | Boca Raton, FL | Oct 08, 2026 | [Apply](https://modmed.wd501.myworkdayjobs.com/ModMed12/job/Boca-Raton-FL/Software-Engineering-Intern_R5148) |
| Moog | Intern, Software Engineering 🆕 | Software | Mineral Wells, TX | Oct 08, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Mineral-Wells-TX/Intern--Software-Engineering_R-26-19965) |
| Northrop Grumman | 2027 - Mechanical Engineer Intern -McClellan CA 🇺🇸 🆕 | Hardware | United States-California-McClellan | Oct 08, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-California-McClellan/XMLNAME-2027---Mechanical-Engineer-Intern--McClellan-CA_R10255111) |
| Northrop Grumman | 2027 Software Engineer Intern – McClellan CA 🇺🇸 🆕 | Software | United States-California-McClellan | Oct 08, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-California-McClellan/XMLNAME-2027-Software-Engineer-Intern---McClellan-CA_R10255207) |
| Amazon ✓ | Software Development Engineer (Embedded Systems) Intern, Amazon Leo - Summer 2027 (USA) 🇺🇸 | Software | Redmond, Washington, USA | Oct 07, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10571374/software-development-engineer-embedded-systems-intern-amazon-leo-summer-2027-usa) |
| Apple Bank | 2027 Summer Intern- Information Security 🛂 🆕 | Security | New York, NY | Oct 07, 2026 | [Apply](https://applebank.wd5.myworkdayjobs.com/applebankcareers/job/New-York-NY/XMLNAME-2027-Summer-Intern--Information-Security_2026-1416) |
| onsemi | Summer 2027 - Manufacturing Engineering Intern | Hardware | Hopewell Junction, NY, United States | Oct 07, 2026 | [Apply](https://hctz.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2506639) |
| Nissan ✓ | Digital Products & AI Strategy Intern - Summer 2027 - Franklin, TN | Data & ML/AI | Franklin +1 more | Oct 07, 2026 | [Apply](https://alliance.wd3.myworkdayjobs.com/nissanjobs/job/Franklin-Tennessee---United-States-of-America/Digital-Products---AI-Strategy-Intern---Summer-2027---Franklin--TN_R00214215) |
| Arc | Mechanical Engineering Intern - Recreational | Hardware | Torrance, CA | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/arcboatcompany/jobs/5445312008) |
| AECOM ✓ | Mechanical Engineering Intern – Hiring Event with AECOM – Atlanta, GA | Hardware | Atlanta, GA, United States | Oct 07, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000154178117) |
| Elanco | Manufacturing Associate Intern – Winslow, Maine (Summer 2027) | Hardware | Winslow, ME | Oct 07, 2026 | [Apply](https://elanco.wd5.myworkdayjobs.com/External_Career/job/Winslow-ME/Manufacturing-Associate-Intern---Winslow--Maine--Summer-2027-_R0027460) |
| RTX | Manufacturing Project Specialist Intern (Summer 2027) 🇺🇸 | Hardware | US-IA-CEDAR RAPIDS-119 ~ 400 Collins Rd… | Oct 07, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-119--400-Collins-Rd-NE--BLDG-119/Manufacturing-Project-Specialist-Intern--Summer-2027-_01879288) |
| RTX | Software Engineering Co-op (Spring/Summer 2027) 🇺🇸 | Software | US-IA-CEDAR RAPIDS-130 ~ 5350 C Ave NE… | Oct 07, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-130--5350-C-Ave-NE--BLDG-130/Software-Engineering-Co-op--Spring-Summer-2027-_01879726) |
| Ingredion | Mechanical Engineer Co-op 2027 (January - August) | Hardware | North Kansas City, MO | Oct 07, 2026 | [Apply](https://ingredion.wd1.myworkdayjobs.com/IngredionCareers/job/North-Kansas-City-MO/Mechanical-Engineer-Co-op-2027--January---August-_Req-40189-1) |
| Philips | Intern – Digital Healthtech Product Management – Bothell, WA – Summer 2027 | Software | Bothell, Washington, United States | Oct 07, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Bothell-Washington-United-States/Intern---Digital-Healthtech-Product-Management---Bothell--WA---Summer-2027_585564) |
| S&C Electric Company ✓ | Mechanical Engineer Intern - Franklin,WI | Hardware | Franklin, WI, United States | Oct 07, 2026 | [Apply](https://ejia.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/107361) |
| S&C Electric Company ✓ | Manufacturing Engineer Intern | Hardware | Chicago, IL, United States | Oct 07, 2026 | [Apply](https://ejia.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/107366) |
| S&C Electric Company ✓ | Mechanical Engineer Intern- Palatine,IL | Hardware | Palatine, IL, United States | Oct 07, 2026 | [Apply](https://ejia.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/107367) |
| Johnson & Johnson | GTO Manufacturing Engineering Co-op, Summer 2027 | Hardware | Cornelia +2 more | Oct 07, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cornelia-Georgia-United-States-of-America/GTO-Manufacturing-Engineering-Co-op--Summer-2027_R-103371) |
| Amazon ✓ | Software Development Engineer Intern - Mobile(iOS/Android) - Summer 2027 (USA) | Software | Seattle, Washington, USA | Oct 06, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10571004/software-development-engineer-intern-mobile-ios-android-summer-2027-usa) |
| Niantic Spatial | Software Engineering Intern (Summer 2027) | Software | San Francisco, CA | Oct 06, 2026 | [Apply](https://jobs.ashbyhq.com/niantic-spatial/898b2da7-03cd-486e-96e3-3430a148c8fd) |
| Sigma Computing ✓ | Software Engineering Intern (Summer 2027) 🛂 | Software | San Francisco, CA | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/sigmacomputing/jobs/7850795003) |
| Sigma Computing ✓ | Software Engineering Intern (Summer 2027) 🛂 | Software | New York, NY | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/sigmacomputing/jobs/8001295003) |
| Highmark Health ✓ | Summer 2027 Artificial Intelligence (Operations) Undergraduate Intern 🛂 | Data & ML/AI | Pittsburgh PA +3 more | Oct 06, 2026 | [Apply](https://highmarkhealth.wd1.myworkdayjobs.com/highmark/job/Pittsburgh-PA-15222-FAP-5th-Avenue-Place/Summer-2027-Artificial-Intelligence--Operations--Undergraduate-Intern_J287476) |
| Rivet Industries | Intern, Software Engineering (Summer 2027) 🇺🇸 | Software | San Jose, CA | Oct 06, 2026 | [Apply](https://jobs.ashbyhq.com/rivet/03fcb078-7371-4cfd-89a9-368e5b60d914) |
| Waymo ✓ | 2027 Summer Intern, BS, Waymo ML Ops & Automation | Data & ML/AI | Mountain View, CA, USA | Oct 06, 2026 | [Apply](https://careers.withwaymo.com/jobs?gh_jid=8257237) |
| Waymo ✓ | 2027 Summer Intern, BS, Software Engineer, Model Eval | Software | Mountain View, CA, USA | Oct 06, 2026 | [Apply](https://careers.withwaymo.com/jobs?gh_jid=8257660) |
| Clean Harbors ✓ | Mechanical Engineer Intern - Summer 2027 | Hardware | La Porte, TX, United States | Oct 06, 2026 | [Apply](https://epyc.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/166786) |
| ABB ✓ | Manufacturing Quality Intern - Summer 2027 🛂 | Hardware | USA, NM, Albuquerque | Oct 06, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/USA-NM-Albuquerque/Manufacturing-Quality-Intern---Summer-2027_JR00048446) |
| Dmainc | Cybersecurity Intern - Summer 2027 | Security | Fort Wayne, IN | Oct 06, 2026 | [Apply](https://dmainc.wd5.myworkdayjobs.com/dma/job/Fort-Wayne-IN/Cybersecurity-Intern---Summer-2027_REQ742) |
| Courier Health | Software Engineering Intern (Summer 2027) | Software | New York, New York, United States | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/courierhealth/jobs/5258913007) |
| MEMX | Information Security Intern, Summer 2027 (Hybrid, NYC) | Security | United States | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/memx/jobs/5445236008) |
| Pure Storage ✓ | Software Engineer Intern (Summer 2027) | Software | Santa Clara, California | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/purestorage/jobs/8249749) |
| Carpenter Technology | Maintenance Intern - Mechanical | Hardware | Reading, PA | Oct 06, 2026 | [Apply](https://cartech.wd5.myworkdayjobs.com/CTCExternal/job/Reading-PA/Maintenance-Intern---Mechanical_26885) |
| Marvell ✓ | Machine Learning Engineer Intern, BS/MS - Summer 2027 | Data & ML/AI | Santa Clara, CA | Oct 06, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/marvellcareers2/job/Santa-Clara-CA/Machine-Learning-Engineer-Intern--BS-MS---Summer-2027_2604989) |
| Hudson River Trading ✓ | Data Scientist Intern - 2027 | Data & ML/AI | London +4 more | Oct 05, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=8257369) |
| Motorola ✓ | Android Applications Developer Intern - Summer 2027 🇺🇸 🆕 | Software | Chicago, IL | Oct 05, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Chicago-IL/Android-Applications-Developer-Intern---Summer-2027_R69313) |
| Midland States Bank | Intern - IT Infrastructure | Software | Effingham, IL | Oct 05, 2026 | [Apply](https://midlandsb.wd1.myworkdayjobs.com/msbcareers/job/Effingham-IL/Intern---IT-Infrastructure_JR1471) |
| Arc | Mechanical Engineering Intern - Powertrain | Hardware | Torrance, CA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/arcboatcompany/jobs/5442958008) |
| WSP | Mechanical Engineering Co-op - Spring/Summer 2027 | Hardware | Philadelphia, PA, United States | Oct 05, 2026 | [Apply](https://emit.fa.ca3.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2001/job/95758) |
| ABB ✓ | Manufacturing Intern - Summer 2027 🛂 | Hardware | USA, NM, Albuquerque | Oct 05, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/USA-NM-Albuquerque/Manufacturing-Intern---Summer-2027_JR00047889) |
| American Family Insurance Group | Summer 2027 Intern - Data Analyst | Data & ML/AI | WI Madison | Oct 05, 2026 | [Apply](https://amfam.wd1.myworkdayjobs.com/AmFamGroupInternCareers/job/WI-Madison/Summer-2027-Intern---Data-Analyst_R39615) |
| Hitachi Energy ✓ | Mechanical Engineering Internship/Co-op | Hardware | Liberty, South Carolina, United States | Oct 05, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Liberty-South-Carolina-United-States/Mechanical-Engineering-Internship-Co-op_R0144979) |
| Jain Global | Data Engineer Intern | Data & ML/AI | New York, New York | Oct 05, 2026 | [Apply](https://jainglobal.wd5.myworkdayjobs.com/ExternalSite/job/New-York-New-York/Data-Engineer-Intern_JR100605-1) |
| LexisNexis Risk Solutions ✓ | Data Science Intern | Data & ML/AI | Alpharetta, GA (Alderman) | Oct 05, 2026 | [Apply](https://relx.wd3.myworkdayjobs.com/RiskSolutions/job/Alpharetta-GA-Alderman/Data-Science-Intern_R118955) |
| Hitachi Energy ✓ | Mechanical Engineering Internship/Co-op | Hardware | Auburn Hills, Michigan, United States | Oct 05, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Auburn-Hills-Michigan-United-States/Mechanical-Engineering-Internship-Co-op_R0143857) |
| Hitachi Energy ✓ | Mechanical Engineering Internship/Co-op | Hardware | Holland, Michigan, United States | Oct 05, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Holland-Michigan-United-States/Mechanical-Engineering-Internship-Co-op_R0144975) |
| Primient | AI Analyst Intern - Summer 2027 | Data & ML/AI | Schaumburg, IL | Oct 04, 2026 | [Apply](https://primient.wd1.myworkdayjobs.com/External_Careers/job/Schaumburg-IL/AI-Analyst-Intern---Summer-2027_JREQ7056) |
| Amazon ✓ | Software Development Engineer Intern (Embedded Systems) - Summer 2027 (USA) | Software | Seattle, Washington, USA | Oct 02, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10567914/software-development-engineer-intern-embedded-systems-summer-2027-usa) |
| Anduril | 2027 Industrial Engineer Intern | Hardware | Ashville +5 more | Oct 02, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5255593007?gh_jid=5255593007) |
| Affirm ✓ | Software Engineer (Machine Learning) Intern (Summer 2027) | Data & ML/AI | San Francisco, California, United States | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/affirm/jobs/8008645003) |
| Affirm ✓ | Software Engineer Intern (Summer 2027) | Software | San Francisco, California, United States | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/affirm/jobs/8011590003) |
| Harvey ✓ | Software Engineering Intern (Summer 2027) | Software | New York | Oct 02, 2026 | [Apply](https://jobs.ashbyhq.com/harvey/06d64648-b84b-48ae-94a2-d9c06dfdcb5d) |
| ispace ✓ | 2027 Summer Internship - Mechanical Test Engineer 🇺🇸 | Hardware | Englewood, Colorado | Oct 02, 2026 | [Apply](https://jobs.lever.co/ispace-inc/fa34bd91-bd23-460b-af53-4a7f2066d9f3) |
| Cox | Cybersecurity Intern - Summer 2027 | Security | Atlanta GA | Oct 02, 2026 | [Apply](https://cox.wd1.myworkdayjobs.com/Cox_External_Career_Site_1/job/Atlanta-GA/Cybersecurity-Intern---Summer-2027_R202683372) |
| Arc | Software Engineering Intern | Software | Torrance, CA | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/arcboatcompany/jobs/5442881008) |
| Muon Space | Industrial Engineering Intern (Summer 2027) 🇺🇸 | Hardware | San Jose, CA | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/muonspace/jobs/5256284007) |
| Bedrock Robotics | 2027 Internship Behavior ML Engineer, Learned Manipulation Policies | Data & ML/AI | San Francisco, CA | Oct 02, 2026 | [Apply](https://jobs.ashbyhq.com/bedrock-robotics/96a6423e-7439-4cb4-9109-117b14e47f7c) |
| xAI | Summer 2027 Software Engineering Internship/Co-op | Software | Palo Alto, CA | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/xai/jobs/5255111007) |
| Stantec ✓ | Structural Engineering Intern/Co-op – Transportation (Summer 2027) | Hardware | New York, NY, United States | Oct 02, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1008131) |
| The Aerospace Corporation | 2027 Flight Loads Structural Dynamics Graduate Intern 🇺🇸 | Hardware | El Segundo, CA | Oct 02, 2026 | [Apply](https://aero.wd5.myworkdayjobs.com/external/job/El-Segundo-CA/XMLNAME-2027-Flight-Loads-Structural-Dynamics-Graduate-Intern_R016755) |
| Charter Manufacturing | Smart Manufacturing Engineer Intern (Summer 2027) | Hardware | Charter Steel - Saukville, WI | Oct 02, 2026 | [Apply](https://chartermfg.wd5.myworkdayjobs.com/Charter_Careers/job/Charter-Steel---Saukville-WI/Smart-Manufacturing-Engineer-Intern--Summer-2027-_R08133) |
| Nelnet ✓ | Intern - IT Software Engineer .NET (Summer 2027) | Software | Lincoln, NE | Oct 02, 2026 | [Apply](https://nelnet.wd1.myworkdayjobs.com/MyNelnet/job/Lincoln-NE/Intern---IT-Software-Engineer-NET--Summer-2027-_R23198) |
| Major League Baseball | Intern, Data Science | Data & ML/AI | Citi Field – Queens, New York | Oct 02, 2026 | [Apply](https://sterlingmets.wd5.myworkdayjobs.com/Mets/job/Citi-Field--Queens-New-York/Intern--Data-Science_R1508) |
| Pinterest ✓ | Software Engineer Intern 2027 (USA) 🏠 | Software | San Francisco, CA, US; Remote, US | Oct 01, 2026 | [Apply](https://www.pinterestcareers.com/jobs/?gh_jid=7838577) |
| Pinterest ✓ | Software Engineering Intern 2027 (Toronto) | Software | Toronto, ON, CA | Oct 01, 2026 | [Apply](https://www.pinterestcareers.com/jobs/?gh_jid=8138039) |
| Pinterest ✓ | Machine Learning Intern 2027 (Toronto) | Data & ML/AI | Toronto, ON, CA | Oct 01, 2026 | [Apply](https://www.pinterestcareers.com/jobs/?gh_jid=8138080) |
| Mach Industries | Summer 2027 Engineering Internship, Manufacturing 🇺🇸 | Hardware | Huntington Beach +5 more | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/machindustries/jobs/4429928009) |
| The Federal Reserve System | Summer 2027 Intern-Computer Science and Software Engineering 🛂 | Software | Chicago, IL | Oct 01, 2026 | [Apply](https://rb.wd5.myworkdayjobs.com/FRS/job/Chicago-IL/Summer-2027-Intern-Computer-Science-and-Software-Engineering_R-0000033637) |
| Walleye Capital | Special Projects Developer Intern (Summer 2027) | Software | New York, New York | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/walleyecapital-external-students/jobs/4716166006) |
| Datacor | Summer 2027 AI Engineer Intern 🏠 | Data & ML/AI | Remote, US | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/datacor/jobs/5242412007) |
| Stantec ✓ | Transportation Engineering Intern - Infrastructure (Summer 2027) | Software | Atlanta, GA, United States | Oct 01, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1008089) |
| ATC | Intern - Cyber Security Summer 2027 | Security | Pewaukee, WI | Oct 01, 2026 | [Apply](https://atcllc.wd5.myworkdayjobs.com/atcllc/job/Pewaukee-WI/Intern---Cyber-Security-Summer-2027_R0003307) |
| CoStar Group | Embedded Software Engineering Intern 🛂 | Software | Sunnyvale (US) | Oct 01, 2026 | [Apply](https://costar.wd1.myworkdayjobs.com/Costar_Campus/job/Sunnyvale-US/Embedded-Software-Engineering-Intern_R39950) |
| CoStar Group | Mechanical Engineering Intern 🛂 | Hardware | Sunnyvale (US) | Oct 01, 2026 | [Apply](https://costar.wd1.myworkdayjobs.com/Costar_Campus/job/Sunnyvale-US/Mechanical-Engineering-Intern_R39952) |
| Marvell ✓ | Firmware Engineer Intern, MS - Summer 2027 | Hardware | Santa Clara, CA | Oct 01, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/marvellcareers2/job/Santa-Clara-CA/Firmware-Engineer-Intern--MS---Summer-2027_2604513-1) |
| The Federal Reserve System | TS - Application Security Intern - 2027 🇺🇸 | Security | Cleveland, OH | Oct 01, 2026 | [Apply](https://rb.wd5.myworkdayjobs.com/FRS/job/Cleveland-OH/TS---Application-Security-Intern---2027_R-0000033625) |
| Zekelman Industries | Intern, Manufacturing Engineer | Hardware | Niles, OH | Oct 01, 2026 | [Apply](https://zekelman.wd12.myworkdayjobs.com/Careers/job/Niles-OH/Intern--Manufacturing-Engineer_JR002843) |
| AECOM ✓ | Structural Engineering Intern – Hiring Event with AECOM – Atlanta, GA | Hardware | Atlanta, GA, United States | Oct 01, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000152952229) |
| Allison Transmission ✓ | Manufacturing Engineering Intern - Summer 2027 | Hardware | Indianapolis, IN | Oct 01, 2026 | [Apply](https://allisontransmission.wd1.myworkdayjobs.com/ATI-External/job/Indianapolis-IN/Manufacturing-Engineering-Intern---Summer-2027_R008126) |
| Varda Space | Cybersecurity Internship - Summer 2027 🇺🇸 | Security | El Segundo, California, United States | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/vardaspace/jobs/8005821003) |
| Varda Space | Flight Software Internship - Summer 2027 🇺🇸 | Software | El Segundo, California, United States | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/vardaspace/jobs/8010159003) |
| Varda Space | Manufacturing Engineering Internship - Summer 2027 🇺🇸 | Hardware | El Segundo, California, United States | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/vardaspace/jobs/8010166003) |
| Generac ✓ | 2027 Summer Intern Digital Manufacturing Engineering | Hardware | Waukesha, WI - USA | Oct 01, 2026 | [Apply](https://generac.wd5.myworkdayjobs.com/external/job/Waukesha-WI---USA/XMLNAME-2027-Summer-Intern-Digital-Manufacturing-Engineering_JR16255) |
| Muon Space | Thermal Engineering Intern (Summer 2027) 🇺🇸 | Hardware | San Jose, CA | Sep 30, 2026 | [Apply](https://job-boards.greenhouse.io/muonspace/jobs/5253474007) |
| Helion Energy | Mechanical Engineering Summer 2027 Intern | Hardware | Everett, WA | Sep 30, 2026 | [Apply](https://jobs.ashbyhq.com/helion/b73602bd-b644-4a46-9188-fded4b2db606) |
| Allen Control Systems | Android Developer Intern, 2027 | Software | Austin, TX | Sep 30, 2026 | [Apply](https://jobs.ashbyhq.com/allen-control-systems/1cd2b432-9a01-4ae0-8eb2-6ebd9c278b94) |
| Muon Space | Flight Software Engineering Intern (Summer 2027) 🇺🇸 | Software | San Jose, CA | Sep 30, 2026 | [Apply](https://job-boards.greenhouse.io/muonspace/jobs/5247725007) |
| Dandy | Summer 2027 Internship - Software Engineering Intern | Software | USA - New York NY | Sep 30, 2026 | [Apply](https://jobs.ashbyhq.com/dandy/d43558e9-8e51-4980-b00d-39275063f099) |
| Waymo ✓ | 2027 Summer Intern, BS, Software Engineering, Labeling | Software | Mountain View, CA, USA | Sep 30, 2026 | [Apply](https://careers.withwaymo.com/jobs?gh_jid=8238525) |
| Allison Transmission ✓ | Manufacturing Engineer Intern - Summer 2027-1 🇺🇸 | Hardware | Indianapolis, IN | Sep 30, 2026 | [Apply](https://allisontransmission.wd1.myworkdayjobs.com/ATI-External/job/Indianapolis-IN/Manufacturing-Engineer-Intern---Summer-2027-1_R008267) |
| Allison Transmission ✓ | Manufacturing Engineer Intern - Summer 2027-2 🇺🇸 | Hardware | Indianapolis, IN | Sep 30, 2026 | [Apply](https://allisontransmission.wd1.myworkdayjobs.com/ATI-External/job/Indianapolis-IN/Manufacturing-Engineer-Intern---Summer-2027-2_R008266) |
| STV ✓ | Structural Engineering Intern - Summer 2027 🛂 | Hardware | Oklahoma City, Oklahoma | Sep 30, 2026 | [Apply](https://stvinc.wd5.myworkdayjobs.com/stv/job/Oklahoma-City-Oklahoma/Structural-Engineering-Intern---Summer-2027_JR6315) |
| Zekelman Industries | Intern, Manufacturing Engineer | Hardware | Rochelle, IL | Sep 30, 2026 | [Apply](https://zekelman.wd12.myworkdayjobs.com/Careers/job/Rochelle-IL/Intern--Manufacturing-Engineer_JR002824) |
| Robinhood ✓ | Data Science Intern (Summer 2027) | Data & ML/AI | Menlo Park, CA | Sep 29, 2026 | [Apply](https://boards.greenhouse.io/robinhood/jobs/8241738?t=gh_src=&gh_jid=8241738) |
| Helion Energy | Materials Engineering Summer 2027 Intern | Hardware | Everett, WA | Sep 29, 2026 | [Apply](https://jobs.ashbyhq.com/helion/56636c72-2c72-4f4f-8334-3b233a235c8d) |
| AMCA | Software Engineering Internship (Summer 2027) 🇺🇸 | Software | El Segundo, CA | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/amca/jobs/4425120009) |
| Freeform | Manufacturing Engineering Intern, CNC Machining (Summer 2027) | Hardware | Los Angeles, CA (On-site) | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/freeformfuturecorp/jobs/8004101003) |
| Itron ✓ | Intern - Data Science, Distributed Intelligence | Data & ML/AI | United States of America +2 more | Sep 29, 2026 | [Apply](https://itron.wd5.myworkdayjobs.com/Early_Careers/job/United-States-of-America-Washington-Liberty-Lake/Intern---Data-Science--Distributed-Intelligence_JR102942-2) |
| ICF ✓ | 2027 Summer Intern, AI Engineer (Reston, VA) 🇺🇸 | Data & ML/AI | Reston, VA | Sep 29, 2026 | [Apply](https://icf.wd5.myworkdayjobs.com/ICFExternal_Career_Site/job/Reston-VA/XMLNAME-2027-Summer-Intern--AI-Engineer--Reston--VA-_R2603312-1) |
| Insulet Corporation ✓ | Co-op, Software Development Engineer in Test: January - June 2027 (Hybrid) | Software | Acton, Massachusetts | Sep 29, 2026 | [Apply](https://insulet.wd5.myworkdayjobs.com/insuletcareers/job/Acton-Massachusetts/Co-op--Software-Development-Engineer-in-Test--January---June-2027--Hybrid-_REQ-2026-18026) |
| Insulet Corporation ✓ | Co-op, Manufacturing: January - June 2027 (Onsite) | Hardware | Irvine, California | Sep 29, 2026 | [Apply](https://insulet.wd5.myworkdayjobs.com/insuletcareers/job/Irvine-California/Co-op--Manufacturing--January---June-2027--Onsite-_REQ-2026-18119) |
| The Toro Company | Manufacturing Engineer Intern - Ditch Witch 🛂 | Hardware | Perry, OK | Sep 29, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Perry-OK/Manufacturing-Engineer-Intern---Ditch-Witch_JR17449) |
| Perchwell | Software Engineering Intern | Software | New York Office | Sep 29, 2026 | [Apply](https://jobs.ashbyhq.com/perchwell/194eec78-26db-4d8e-850f-a99ea2733e9f) |
| Enova ✓ | Software Engineer Internship Summer 2027 (Hybrid) 🛂 | Software | Chicago, IL | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/enova/jobs/8239619) |
| National Life ✓ | Digital & AI Experience Intern – Summer 2027 🛂 | Data & ML/AI | Addison, TX; Montpelier, VT | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/nationallifeinsurancecompany/jobs/4403876009) |
| Ralliant | Manufacturing Engineering Intern - Summer 2027 | Hardware | Boxborough, MA, United States | Sep 29, 2026 | [Apply](https://ibwujb.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/10680) |
| Ralliant | Manufacturing Engineering Intern - Summer 2027 | Hardware | Plainville, CT, United States | Sep 29, 2026 | [Apply](https://ibwujb.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/10681) |
| Marvell ✓ | AI-Native Development Platform Engineer Intern, MS - Summer 2027 | Data & ML/AI | Santa Clara, CA | Sep 29, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/marvellcareers2/job/Santa-Clara-CA/AI-Native-Development-Platform-Engineer-Intern--MS---Summer-2027_2603848) |
| nVent | Manufacturing Automaton Intern (June - August 2027) 🛂 | Hardware | Anoka, MN, US | Sep 29, 2026 | [Apply](https://nvent.wd5.myworkdayjobs.com/nVent/job/Anoka-MN-US/Manufacturing-Automaton-Intern--June---August-2027-_R23865) |
| Q2 | 2027 Summer Internship - Data Science 🛂 | Data & ML/AI | Cary, North Carolina | Sep 29, 2026 | [Apply](https://q2ebanking.wd5.myworkdayjobs.com/Q2/job/Cary-North-Carolina/XMLNAME-2027-Summer-Internship---Data-Science_REQ-12799) |
| Q2 | 2027 Summer Internship - Machine Learning Engineer 🛂 | Data & ML/AI | Cary, North Carolina | Sep 29, 2026 | [Apply](https://q2ebanking.wd5.myworkdayjobs.com/Q2/job/Cary-North-Carolina/XMLNAME-2027-Summer-Internship---Machine-Learning-Engineer_REQ-12800) |
| Q2 | 2027 Summer Internship - Software Engineer 🛂 | Software | Cary, North Carolina | Sep 29, 2026 | [Apply](https://q2ebanking.wd5.myworkdayjobs.com/Q2/job/Cary-North-Carolina/XMLNAME-2027-Summer-Internship---Software-Engineer_REQ-12798) |
| Hermeus | Flight Software Engineering Intern (Simulation/Hardware-In-The-Loop) - Spring & Summer 2027 🇺🇸 | Hardware | Los Angeles, CA | Sep 29, 2026 | [Apply](https://jobs.lever.co/hermeus/78008094-ca81-4a0c-9a18-93b30f932acd) |
| Verizon Communications | Irving V Teamer for a Day: Verizon Data Science Summer 2027 Internship | Data & ML/AI | Irving, Texas | Sep 29, 2026 | [Apply](https://verizon.wd12.myworkdayjobs.com/verizon-careers/job/Irving-Texas/Irving-V-Teamer-for-a-Day--Verizon-Data-Science-Summer-2027-Internship_R-1101386) |
| Verizon Communications | Verizon Network and Technology: Data Science Summer 2027 Internship | Data & ML/AI | Irving, Texas | Sep 29, 2026 | [Apply](https://verizon.wd12.myworkdayjobs.com/verizon-careers/job/Irving-Texas/Verizon-Network-and-Technology--Data-Science-Summer-2027-Internship_R-1101384) |
| The Aerospace Corporation | 2027 Software Tools and Assurance Engineering Grad Intern 🇺🇸 | Software | El Segundo, CA | Sep 28, 2026 | [Apply](https://aero.wd5.myworkdayjobs.com/external/job/El-Segundo-CA/XMLNAME-2027-Software-Tools-and-Assurance-Engineering-Grad-Intern_R016753) |
| Zurn Elkay Water Solutions | Industrial Engineering Intern (Summer 2027) | Hardware | Freeport, IL | Sep 28, 2026 | [Apply](https://elkay.wd1.myworkdayjobs.com/Elkay_External/job/Freeport-IL/Industrial-Engineering-Intern--Summer-2027-_REQ-020072) |
| AtkinsRéalis | Structural Engineering Intern – Summer 2027 | Hardware | US.CO.Denver | Sep 28, 2026 | [Apply](https://slihrms.wd3.myworkdayjobs.com/careers/job/USCODenver/Structural-Engineering-Intern---Summer-2027_R-161182-1) |
| AtkinsRéalis | Structural Engineering Intern – Summer 2027 | Hardware | US.WA.Bothell | Sep 28, 2026 | [Apply](https://slihrms.wd3.myworkdayjobs.com/careers/job/USWABothell/Structural-Engineering-Intern---Summer-2027_R-162449-1) |
| Formlabsinternships | Desktop Software Intern (Summer 2027) | Software | Somerville, MA | Sep 28, 2026 | [Apply](https://job-boards.greenhouse.io/formlabsinternships/jobs/8223362) |
| Lawrence Livermore National Laboratory (LLNL) | Data Science Institute Graduate Student Intern - Summer 2027 🇺🇸 | Data & ML/AI | Livermore, CA, United States | Sep 28, 2026 | [Apply](https://jobs.smartrecruiters.com/LLNL/3743990015737586) |
| Mars | Summer 2027 Mars Petcare Manufacturing Internship | Hardware | USA-Arkansas-Ft. Smith | Sep 28, 2026 | [Apply](https://mars.wd3.myworkdayjobs.com/external/job/USA-Arkansas-Ft-Smith/Summer-2027-Mars-Petcare-Manufacturing-Internship_R168212-1) |
| Veterans United ✓ | Intern - Software Engineer - Summer 2027 🏠 | Software | Remote MO | Sep 28, 2026 | [Apply](https://veteransunited.wd1.myworkdayjobs.com/VUHL/job/Remote-MO/Intern---Software-Engineer---Summer-2027_R6249) |
| Blue Cross Blue Shield of Michigan ✓ | Summer 2027 Intern - Data Science / Biostatistician | Data & ML/AI | Detroit, MI, United States | Sep 28, 2026 | [Apply](https://ejko.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_3/job/14837) |
| GM financial | Intern - Cybersecurity 🛂 | Security | Irving, TX, United States | Sep 28, 2026 | [Apply](https://fa-exvu-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/260805) |
| GM financial | Intern - Cybersecurity | Security | Arlington, TX, United States | Sep 28, 2026 | [Apply](https://fa-exvu-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/260836) |
| AECOM ✓ | Mechanical Engineering Intern - Hiring Event with AECOM - Arlington, VA | Hardware | Arlington, VA, United States | Sep 28, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000152172269) |
| General Dynamics Information Technology ✓ | GDIT Summer Internship Program – Summer 2027 AI/ML Data Science and Engineering Internship 🇺🇸 | Data & ML/AI | USA LA Bossier City | Sep 26, 2026 | [Apply](https://gdit.wd5.myworkdayjobs.com/gdit_earlytalent/job/USA-LA-Bossier-City/GDIT-Summer-Internship-Program---Summer-2027-AI-ML-Data-Science-and-Engineering-Internship_RQ228936) |
| General Dynamics Information Technology ✓ | GDIT Summer Internship Program – Summer 2027 AI/ML Software Development and Engineering Internship 🇺🇸 | Data & ML/AI | USA LA Bossier City | Sep 26, 2026 | [Apply](https://gdit.wd5.myworkdayjobs.com/gdit_earlytalent/job/USA-LA-Bossier-City/GDIT-Summer-Internship-Program---Summer-2027-AI-ML-Software-Development-and-Engineering-Internship_RQ228939) |
| General Dynamics Information Technology ✓ | GDIT Summer Internship Program – Summer 2027 AI/ML Software Development and Engineering Internship 🇺🇸 | Data & ML/AI | USA LA Bossier City | Sep 26, 2026 | [Apply](https://gdit.wd5.myworkdayjobs.com/gdit_earlytalent/job/USA-LA-Bossier-City/GDIT-Summer-Internship-Program---Summer-2027-AI-ML-Software-Development-and-Engineering-Internship_RQ228940) |
| Mach Industries | Summer 2027 Engineering Internship, Mechanical 🇺🇸 | Hardware | Huntington Beach +11 more | Sep 25, 2026 | [Apply](https://job-boards.greenhouse.io/machindustries/jobs/4420611009) |
| Mach Industries | Summer 2027 Engineering Internship, Software/GNC 🇺🇸 | Software | Huntington Beach +5 more | Sep 25, 2026 | [Apply](https://job-boards.greenhouse.io/machindustries/jobs/4420626009) |
| Zurn Elkay Water Solutions | Embedded Firmware Intern (Summer 2027) | Hardware | Milwaukee, WI | Sep 25, 2026 | [Apply](https://elkay.wd1.myworkdayjobs.com/Elkay_External/job/Milwaukee-WI/Embedded-Firmware-Intern--Summer-2027-_REQ-020150-1) |
| Zurn Elkay Water Solutions | Embedded Hardware Intern (Summer 2027) | Hardware | Milwaukee, WI | Sep 25, 2026 | [Apply](https://elkay.wd1.myworkdayjobs.com/Elkay_External/job/Milwaukee-WI/Embedded-Hardware-Intern--Summer-2027-_REQ-020151) |
| Life Fitness ✓ | Manufacturing Quality Engineering Intern - Owatonna, MN | Hardware | Owatonna, MN | Sep 25, 2026 | [Apply](https://lifefitness.wd1.myworkdayjobs.com/searchLFN/job/Owatonna-MN/Manufacturing-Quality-Engineering-Intern---Owatonna--MN_JR-025245) |
| AbbVie ✓ | 2027 Business Technology Solutions Intern - Cybersecurity (Undergraduate) | Security | North Chicago, IL, United States | Sep 25, 2026 | [Apply](https://jobs.smartrecruiters.com/AbbVie/3743990015679246) |
| AbbVie ✓ | 2027 Business Technology Solutions Intern - Data & Software Engineering (Undergraduate) | Data & ML/AI | North Chicago, IL, United States | Sep 25, 2026 | [Apply](https://jobs.smartrecruiters.com/AbbVie/3743990015679386) |
| AbbVie ✓ | 2027 Business Technology Solutions Intern - Data & Software Engineering (Undergraduate) | Data & ML/AI | Irvine, CA, United States | Sep 25, 2026 | [Apply](https://jobs.smartrecruiters.com/AbbVie/3743990015684476) |
| iRhythm Technologies ✓ | Embedded SDET Co-Op Full Time Intern January-June 2027 | Software | San Francisco, CA | Sep 24, 2026 | [Apply](https://irhythmtech.wd5.myworkdayjobs.com/irhythm/job/San-Francisco-CA/Embedded-SDET-Co-Op-Full-Time-Intern-January-June-2027_JR1758) |
| ABB ✓ | Product Management Intern - Summer 2027 🛂 | Software | New Berlin +2 more | Sep 24, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/New-Berlin-Wisconsin-United-States-of-America/Product-Management-Intern---Summer-2027_JR00047280) |
| iRhythm Technologies ✓ | Mechanical Engineering Co-op Full Time Intern Jan - June 2027 | Hardware | San Francisco, CA | Sep 24, 2026 | [Apply](https://irhythmtech.wd5.myworkdayjobs.com/irhythm/job/San-Francisco-CA/Mechanical-Engineering-Co-op-Full-Time-Intern-Jan---June-2027_JR1766) |
| Motorola ✓ | Software Engineering Intern - Summer 2027 🇺🇸 | Software | Plantation, FL | Sep 24, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Plantation-FL/Software-Engineering-Intern---Summer-2027_R69136) |
| Merck | 2027 Future Talent Program - Data Science - Intern | Data & ML/AI | USA - Pennsylvania - West Point | Sep 24, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2027-Future-Talent-Program---Data-Science---Intern_R413312) |
| ZOLL Medical Corporation | Mechanical Engineering Intern | Hardware | Chelmsford, MA | Sep 24, 2026 | [Apply](https://zoll.wd5.myworkdayjobs.com/ZOLLMedicalCorp/job/Chelmsford-MA/Mechanical-Engineering-Intern_R20310) |
| Figma ✓ | Data Engineer Intern (2027) | Data & ML/AI | San Francisco, CA • New York, NY | Sep 23, 2026 | [Apply](https://boards.greenhouse.io/figma/jobs/6178851004?gh_jid=6178851004) |
| DoorDash ✓ | Machine Learning Intern (Masters) - Summer 2027 | Data & ML/AI | San Francisco +7 more | Sep 23, 2026 | [Apply](https://job-boards.greenhouse.io/doordashusa/jobs/8204111) |
| Zekelman Industries | Industrial Engineer - Intern | Hardware | Killeen, TX | Sep 23, 2026 | [Apply](https://zekelman.wd12.myworkdayjobs.com/Careers/job/Killeen-TX/Industrial-Engineer---Intern_JR002772) |
| Klaviyo ✓ | AI Engineer Intern (Summer 2027) | Data & ML/AI | Boston, MA | Sep 23, 2026 | [Apply](https://job-boards.greenhouse.io/klaviyocampus/jobs/8003260003) |
| The Aerospace Corporation | 2027 Structural Dynamics Undergraduate Intern 🇺🇸 | Hardware | El Segundo, CA | Sep 23, 2026 | [Apply](https://aero.wd5.myworkdayjobs.com/external/job/El-Segundo-CA/XMLNAME-2027-Structural-Dynamics-Undergraduate-Intern_R016668) |
| Continental | 2027 Internship - Manufacturing Engineer (Hoosier Racing Tire) | Hardware | Plymouth, IN, United States | Sep 23, 2026 | [Apply](https://jobs.smartrecruiters.com/Continental/744000151462939) |
| Insulet Corporation ✓ | Intern, DevOps Engineer: June-August 2027 (Onsite) | Software | San Diego, California | Sep 23, 2026 | [Apply](https://insulet.wd5.myworkdayjobs.com/insuletcareers/job/San-Diego-California/Intern--DevOps-Engineer--June-August-2027--Onsite-_REQ-2026-18202) |
| Klaviyo ✓ | Machine Learning Engineer Internship-Summer 2027 | Data & ML/AI | Palo Alto, CA | Sep 23, 2026 | [Apply](https://job-boards.greenhouse.io/klaviyocampus/jobs/7999274003) |
| Generac ✓ | Mechanical Engineering Intern - Transfer Switch - Summer 2027 | Hardware | Waukesha, WI - USA | Sep 23, 2026 | [Apply](https://generac.wd5.myworkdayjobs.com/external/job/Waukesha-WI---USA/Mechanical-Engineering-Intern---Transfer-Switch---Summer-2027_JR17048) |
| Grow Therapy | Software Engineering Intern (Summer 2027) | Software | New York City | Sep 22, 2026 | [Apply](https://jobs.ashbyhq.com/grow-therapy/92bfe88a-4c23-48c8-8f7b-4959ab6cd8d8) |
| Astranis | Software Engineer Backend Intern (Summer 2027) 🇺🇸 | Software | San Francisco, CA | Sep 22, 2026 | [Apply](https://job-boards.greenhouse.io/astranis/jobs/4705214006) |
| Astranis | Software Engineer - Enterprise Systems Intern (Summer 2027) 🇺🇸 | Software | San Francisco, CA | Sep 22, 2026 | [Apply](https://job-boards.greenhouse.io/astranis/jobs/4705610006) |
| Life Fitness ✓ | Manufacturing Engineering Intern - Ramsey, MN | Hardware | Ramsey, MN | Sep 22, 2026 | [Apply](https://lifefitness.wd1.myworkdayjobs.com/searchLFN/job/Ramsey-MN/Manufacturing-Engineering-Intern---Ramsey--MN_JR-025239) |
| Verizon Communications | Verizon Network and Technology: AI Science 2027 Internship: Rutgers, NJIT, NYU, UT Dallas, UT Arlington, Texas A&M | Data & ML/AI | Basking Ridge, New Jersey | Sep 22, 2026 | [Apply](https://verizon.wd12.myworkdayjobs.com/verizon-careers/job/Basking-Ridge-New-Jersey/Verizon-Network-and-Technology--AI-Science-2027-Internship--Rutgers--NJIT--NYU--UT-Dallas--UT-Arlington--Texas-A-M_R-1101169) |
| Rentvision | Software Engineering Intern | Software | Lincoln, Nebraska, United States | Sep 21, 2026 | [Apply](https://apply.workable.com/rentvision/j/0F1C7992BF/) |
| Formlabsinternships | Mechanical Engineering Intern (Summer 2027) | Hardware | Somerville, MA | Sep 21, 2026 | [Apply](https://job-boards.greenhouse.io/formlabsinternships/jobs/8199928) |
| Formlabsinternships | Embedded Software Intern (Summer 2027) | Software | Somerville, MA | Sep 21, 2026 | [Apply](https://job-boards.greenhouse.io/formlabsinternships/jobs/8222268) |
| Cowboy Space | Intern, Software Engineering, 2027 🇺🇸 | Software | San Carlos, California | Sep 21, 2026 | [Apply](https://jobs.ashbyhq.com/cowboyspace/56d1d7e4-fa7e-4c25-aa8b-6828447fc64a) |
| Shield AI | Summer 2027 - Mechanical Engineering Intern | Hardware | Seattle, Washington | Sep 21, 2026 | [Apply](https://jobs.lever.co/shieldai/da54c482-fe62-4f60-98b1-55ac0b82b3bc) |
| Avav | Summer 2027 Autonomy & Robotics Engineering Intern 🇺🇸 | Hardware | Moorpark, CA | Sep 21, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Moorpark-CA/Summer-2027-Autonomy---Robotics-Engineering-Intern_8551) |
| Bracco | Quality Analyst Intern (Software) | Software | USA, Eden Prairie, Minnesota, 55344 | Sep 21, 2026 | [Apply](https://bracco.wd103.myworkdayjobs.com/braccocareers/job/USA-Eden-Prairie-Minnesota-55344/Quality-Analyst-Intern--Software-_JR100314) |
| Charter Manufacturing | Mechanical Engineer Intern (Summer 2027) | Hardware | Charter Steel - Saukville, WI | Sep 21, 2026 | [Apply](https://chartermfg.wd5.myworkdayjobs.com/Charter_Careers/job/Charter-Steel---Saukville-WI/Mechanical-Engineering-Intern--Year-Round-_R08122) |
| Life Fitness ✓ | Mechanical Engineering Intern - Ramsey, MN | Hardware | Ramsey, MN | Sep 21, 2026 | [Apply](https://lifefitness.wd1.myworkdayjobs.com/searchLFN/job/Ramsey-MN/Mechanical-Engineering-Intern---Ramsey--MN_JR-025235) |
| Rocket Lab | Thermal Engineering Intern Summer 2027 🇺🇸 | Hardware | Long Beach, CA | Sep 21, 2026 | [Apply](https://job-boards.greenhouse.io/rocketlab/jobs/8000958003) |
| Brunswick ✓ | Mercury Marine: Intern Design Analysis Group-Fluid & Thermal | Hardware | Fond du Lac, WI | Sep 21, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Fond-du-Lac-WI/Mercury-Marine--Intern-Design-Analysis-Group-Fluid---Thermal_JR-050977) |
| Commerce Bank | Intern - Data Analyst (Summer 2027) 🛂 | Data & ML/AI | MO - Kansas City Downtown/Plaza - Kansa… | Sep 21, 2026 | [Apply](https://commercebank.wd1.myworkdayjobs.com/CommerceJobs/job/MO---Kansas-City-DowntownPlaza---Kansas-City---KC-Downtown-Trust-Building-922-Walnut-64106/Intern-EABI---Data-Analyst-Summer-2027_38484) |
| Commerce Bank | Intern - Data Science (Summer 2027) 🛂 | Data & ML/AI | MO - Kansas City Downtown/Plaza - Kansa… | Sep 21, 2026 | [Apply](https://commercebank.wd1.myworkdayjobs.com/CommerceJobs/job/MO---Kansas-City-DowntownPlaza---Kansas-City---KC-Downtown-Trust-Building-922-Walnut-64106/Intern-EABI---Data-Science-Summer-2027_38483) |
| Draper | Mechanical Engineering & System Packaging Intern (Summer 2027) 🇺🇸 | Hardware | Cambridge, MA | Sep 21, 2026 | [Apply](https://draper.wd5.myworkdayjobs.com/Draper_Careers/job/Cambridge-MA/Mechanical-Engineering---System-Packaging-Intern--Summer-2027-_JR002943) |
| Thrivent ✓ | Associate Software Engineer - Junior Intern Summer 2027 🛂 🏠 | Software | Remote-Minnesota | Sep 18, 2026 | [Apply](https://thrivent.wd5.myworkdayjobs.com/external/job/Remote-Minnesota/Associate-Software-Engineer---Junior-Intern-Summer-2027_REQ-48334) |
| Lawrence Livermore National Laboratory (LLNL) | Computing Undergraduate Student Intern: DevOps Internship Program - Summer 2027 🇺🇸 | Software | Livermore, CA, United States | Sep 18, 2026 | [Apply](https://jobs.smartrecruiters.com/LLNL/3743990015408206) |
| Veolia | SAP & ServiceNow AI Automation Intern 🛂 | Data & ML/AI | Trevose, PA, United States | Sep 18, 2026 | [Apply](https://jobs.smartrecruiters.com/VeoliaEnvironnementSA/744000150460339) |
| Alcon ✓ | 2027 Spring/Summer Co-Op - Manufacturing Engineer 🛂 | Hardware | Fort Worth, Texas | Sep 18, 2026 | [Apply](https://alcon.wd5.myworkdayjobs.com/careers_alcon/job/Fort-Worth-Texas/XMLNAME-2027-Spring-Summer-Co-Op---Manufacturing-Engineer_R-2026-49587) |
| Charter Manufacturing | Mechanical Engineer Intern (Year-Round) | Hardware | Charter Steel - Saukville, WI | Sep 18, 2026 | [Apply](https://chartermfg.wd5.myworkdayjobs.com/Charter_Careers/job/Charter-Steel---Saukville-WI/Mechanical-Engineer-Intern--Year-Round-_R08102) |
| Philips | Co-op - Manufacturing Engineering - Latham, NY - January-August 2027 | Hardware | Latham, New York, United States | Sep 18, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Latham-New-York-United-States/Co-op---Manufacturing-Engineering---Latham--NY---January-August-2027_590906) |
| Watts Water | Manufacturing Quality Intern, Summer 2027 | Hardware | Fort Myers, FL | Sep 18, 2026 | [Apply](https://wattswater.wd5.myworkdayjobs.com/Intern-External/job/Fort-Myers-FL/Manufacturing-Quality-Intern--Summer-2027_10017584) |
| Rocket Lab | Manufacturing Engineering Intern Summer 2027 🇺🇸 | Hardware | Wallops Island, VA | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/rocketlab/jobs/7996623003) |
| Honeywell ✓ | Software Engineer Co-Op - Spring/Summer 2027 🇺🇸 | Software | Pittsford, NY, United States | Sep 17, 2026 | [Apply](https://ibqbjb.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/158088) |
| Bosch | AI Engineering Intern (October 2026 - August 2027) | Data & ML/AI | Plymouth, MI, United States | Sep 17, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000150217869) |
| Lowe's | Store Operations Industrial Engineering – Undergrad Internship – Summer 2027 | Hardware | Mooresville, NC (SSC) 1999 | Sep 17, 2026 | [Apply](https://lowes.wd5.myworkdayjobs.com/LWS_External_CS/job/Mooresville-NC-SSC-1999/Store-Operations-Industrial-Engineering---Undergrad-Internship---Summer-2027_JR-02651868-1) |
| X-energy | Mechanical Engineering Internship - Summer 2027 | Hardware | Rockville, MD | Sep 17, 2026 | [Apply](https://xenergy.wd5.myworkdayjobs.com/X-energyUS/job/Rockville-MD/Mechanical-Engineering-Internship---Summer-2027_R101319-1) |
| CACI | Software Test Engineer Intern - Summer 2027 🇺🇸 | Software | Colorado Springs, CO, US | Sep 16, 2026 | [Apply](https://caci.wd1.myworkdayjobs.com/external/job/Colorado-Springs-CO-US/Software-Test-Engineer-Intern---Summer-2027_332003) |
| CoVar | Machine Learning Internship Summer 2027 | Data & ML/AI | Durham, NC | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/covar/jobs/5240360007) |
| Nanopath | Software Development Co-op (Jan '27 Start) | Software | Cambridge, MA | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/nanopathinc/jobs/4732881005) |
| Rocket Lab | Manufacturing Engineering Intern Summer 2027 🇺🇸 | Hardware | Long Beach, CA | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/rocketlab/jobs/7984564003) |
| Bass Pro Shops | Advanced Manufacturing Intern Summer 2027 | Hardware | Springfield +1 more | Sep 16, 2026 | [Apply](https://basspro.wd1.myworkdayjobs.com/careers/job/Springfield-MO-Bass-Pro-Shops-Base-Camp/Advanced-Manufacturing-Intern-Summer-2027_R267458) |
| Sensata ✓ | Mechanical Engineer Intern (Aerospace) - Summer 2027 🇺🇸 | Hardware | Thousand Oaks, CA | Sep 16, 2026 | [Apply](https://sensata.wd1.myworkdayjobs.com/Sensata-Careers/job/Thousand-Oaks-CA/Mechanical-Engineer-Intern--Aerospace----Summer-2027_IRC98482) |
| Sensata ✓ | Mechanical Engineer Intern (Aerospace) - Summer 2027 🇺🇸 | Hardware | Vista, CA | Sep 16, 2026 | [Apply](https://sensata.wd1.myworkdayjobs.com/Sensata-Careers/job/Vista-CA/Mechanical-Engineer-Intern--Aerospace----Summer-2027_IRC98483) |
| Cartesian | IAP Software Engineering Intern 2027 | Software | Cambridge, MA | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/cartesiansystems/jobs/4408204009) |
| Relay | Software Engineering Intern (AI/ML) - Summer 2027 | Data & ML/AI | Raleigh, NC | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/relaypro/jobs/8176774) |
| Relay | Software Engineering Intern (Device Team) - Summer 2027 | Software | Raleigh, NC | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/relaypro/jobs/8180836) |
| Rendezvous Robotics | Software Engineering Intern (Summer 2027) 🇺🇸 | Software | Golden, CO | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/rendezvousrobotics/jobs/4408590009) |
| Rendezvous Robotics | Mechanical Engineering Intern (Summer 2027) 🇺🇸 | Hardware | Golden, CO | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/rendezvousrobotics/jobs/4408601009) |
| Duracell | PS Manufacturing - Engineering Intern Spring/Summer 2027 | Hardware | Cleveland, TN, United States | Sep 16, 2026 | [Apply](https://fa-ewub-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_26/job/1399) |
| Duracell | PS Manufacturing -Engineering Co-Op-2027 | Hardware | Cleveland, TN, United States | Sep 16, 2026 | [Apply](https://fa-ewub-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_26/job/1400) |
| AspenTech | Software Development Intern - Digital Grid Management - Summer 2027 | Software | Medina, Minnesota | Sep 16, 2026 | [Apply](https://aspentech.wd5.myworkdayjobs.com/aspentech/job/Medina-Minnesota/Software-Development-Intern---Digital-Grid-Management---Summer-2027_R9456) |
| Avav | Summer 2027 Software Engineering Intern 🇺🇸 | Software | Melbourne, FL | Sep 16, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Melbourne-FL/Summer-2027-Software-Engineering-Intern_8550) |
| Johnson & Johnson | Systems & Simulation Engineering Intern - Robotics R&D | Hardware | Santa Clara +2 more | Sep 16, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Santa-Clara-California-United-States-of-America/Systems---Simulation-Engineering-Intern---Robotics-R-D_R-100027) |
| Lonza ✓ | Summer 2027 Manufacturing, Science & Technology Internship | Hardware | US - Portsmouth, NH | Sep 16, 2026 | [Apply](https://lonza.wd3.myworkdayjobs.com/lonza_careers/job/US---Portsmouth-NH/Summer-2026-Manufacturing--Science---Technology-Internship_R79570) |
| Bedrock Robotics | 2027 Internship Software Engineer, Fleet Platform | Software | New York, NY | Sep 16, 2026 | [Apply](https://jobs.ashbyhq.com/bedrock-robotics/8927dd7e-a48d-49a2-92eb-09ec059432f4) |
| Gecko Robotics | Full Stack Software Engineering Intern | Software | New York City | Sep 16, 2026 | [Apply](https://jobs.ashbyhq.com/gecko-robotics/01138338-ff3c-4982-8ba3-5401386bf082) |
| Gecko Robotics | AI/Machine Learning Engineering Intern | Data & ML/AI | New York City | Sep 16, 2026 | [Apply](https://jobs.ashbyhq.com/gecko-robotics/c097505b-0a28-4a33-a917-268f463641e8) |
| Bass Pro Shops | Cybersecurity Intern Summer 2027 | Security | Springfield +1 more | Sep 16, 2026 | [Apply](https://basspro.wd1.myworkdayjobs.com/careers/job/Springfield-MO-Bass-Pro-Shops-Base-Camp/Cybersecurity-Intern-Summer-2027_R267444) |
| Bass Pro Shops | IT Developer Intern Summer 2027 | Software | Springfield +1 more | Sep 16, 2026 | [Apply](https://basspro.wd1.myworkdayjobs.com/careers/job/Springfield-MO-Bass-Pro-Shops-Base-Camp/IT-Developer-Intern-Summer-2027_R267441-1) |
| Lawrence Livermore National Laboratory (LLNL) | Data Science Institute Undergraduate Student Intern - Summer 2027 🇺🇸 | Data & ML/AI | Livermore, CA, United States | Sep 16, 2026 | [Apply](https://jobs.smartrecruiters.com/LLNL/3743990015289136) |
| Anduril | 2027 Flight Software Engineer Intern | Software | Costa Mesa, California, United States | Sep 15, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5239083007?gh_jid=5239083007) |
| RAVE Aerospace | Intern - Software Engineering (Summer 2027) | Software | Laramie, Wyoming, United States | Sep 15, 2026 | [Apply](https://apply.workable.com/raveaerospace/j/739753C003/) |
| Philips | Co-op - Mechanical Engineering Technician - Latham, NY - January-June 2027 | Hardware | Latham, New York, United States | Sep 15, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Latham-New-York-United-States/Co-op---Mechanical-Engineering-Technician---Latham--NY---January-June-2027_590339) |
| SingleStore ✓ | Software Engineer Intern- Helios- 2027 | Software | United States | Sep 15, 2026 | [Apply](https://job-boards.greenhouse.io/singlestore/jobs/8205514) |
| Johnson & Johnson | Clinical Engineering & Human Factors Intern - Robotics R&D 🛂 | Hardware | Santa Clara +2 more | Sep 15, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Santa-Clara-California-United-States-of-America/Clinical-Engineering---Human-Factors-Intern---Robotics-R-D_R-099931) |
| AspenTech | Data Science Intern - Summer 2027 - Bedford, MA | Data & ML/AI | Bedford, Massachusetts | Sep 15, 2026 | [Apply](https://aspentech.wd5.myworkdayjobs.com/aspentech/job/Bedford-Massachusetts/Data-Science-Intern---Summer-2027---Bedford--MA_R9459) |
| Bracco | Firmware Engineering Co-op | Hardware | USA, Eden Prairie, Minnesota, 55344 | Sep 15, 2026 | [Apply](https://bracco.wd103.myworkdayjobs.com/braccocareers/job/USA-Eden-Prairie-Minnesota-55344/Firmware-Engineering-Co-op_JR100324) |
| Brunswick ✓ | Mercury Marine: Industrial Engineer Intern | Hardware | Brownsburg, IN | Sep 15, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Brownsburg-IN/Mercury-Marine--Industrial-Engineer-Intern_JR-051584) |
| Woodward Governor | Engineering Co-op - Manufacturing Engineering / Zeeland, MI (Summer 2027) | Hardware | Zeeland, MI, US | Sep 15, 2026 | [Apply](https://woodward.wd5.myworkdayjobs.com/woodward/job/Zeeland-MI-US/Engineering-Co-op---Manufacturing-Engineering---Zeeland--MI--Summer-2027-_JR112088) |
| CAI | Cybersecurity Analyst Intern | Security | California | Sep 15, 2026 | [Apply](https://cai.wd5.myworkdayjobs.com/computer_aid/job/California/Cybersecurity-Analyst-Intern_R8488) |
| Robinhood ✓ | Software Engineering Intern, Backend (Summer 2027) | Software | Bellevue +5 more | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/robinhood/jobs/8123225?t=gh_src=&gh_jid=8123225) |
| Robinhood ✓ | Software Engineering Intern, iOS (Summer 2027) | Software | Menlo Park, CA; New York, NY | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/robinhood/jobs/8142959?t=gh_src=&gh_jid=8142959) |
| Figma ✓ | Software Engineer Intern (Summer 2027) | Software | San Francisco, CA • New York, NY | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/figma/jobs/6143238004?gh_jid=6143238004) |
| Figma ✓ | Data Science Intern (2027) | Data & ML/AI | San Francisco, CA • New York, NY | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/figma/jobs/6178857004?gh_jid=6178857004) |
| DoorDash ✓ | Software Engineer, Intern (Summer 2027) - US | Software | New York +9 more | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/doordashusa/jobs/8171041) |
| Workshop | Software Engineer Intern (Summer 2027) | Software | Omaha, Nebraska, United States | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/workshop/jobs/5237900007) |
| SingleStore ✓ | Software Engineer Intern- Engine-2027 | Software | United States | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/singlestore/jobs/8154399) |
| Brevan Howard ✓ | 2027 Summer Internship Program – AI & Quantitative Analyst, New York | Quant | New York | Sep 14, 2026 | [Apply](https://wd3.myworkdaysite.com/recruiting/brevanhoward/BH_ExternalCareers/job/New-York/XMLNAME-2027-Summer-Internship-Program---AI---Quantitative-Analyst--New-York_JR101602) |
| AI Intern to the CEO | Software Engineering Intern - SWE/ML (Summer 2027) | Data & ML/AI | Boston, Massachusetts | Sep 14, 2026 | [Apply](https://jobs.ashbyhq.com/cyvl/8bfc4116-b0bb-47f8-bca1-7069a37db328) |
| Amgen ✓ | Grad Intern – Digital Product – Technology, AI & Data (Summer 2027) 🏠 | Data & ML/AI | United States - Remote | Sep 14, 2026 | [Apply](https://amgen.wd1.myworkdayjobs.com/careers/job/United-States---Remote/Grad-Intern---Digital-Product---Amgen-s-Technology---Medical-Organizations--Summer-2027-_R-255744) |
| Amgen ✓ | Undergrad Intern – Digital Product – Technology, AI & Data (Summer 2027) 🏠 | Data & ML/AI | United States - Remote | Sep 14, 2026 | [Apply](https://amgen.wd1.myworkdayjobs.com/careers/job/United-States---Remote/Undergrad-Intern---Digital-Product---Amgen-s-Technology---Medical-Organizations--Summer-2027-_R-255711) |
| CoStar Group | Security Engineer Intern - Richmond, VA 🛂 | Security | US-VA Richmond | Sep 14, 2026 | [Apply](https://costar.wd1.myworkdayjobs.com/Costar_Campus/job/US-VA-Richmond/Security-Engineer-Intern---Richmond--VA_R39726) |
| nVent | Manufacturing Engineering Co-op (January - June 2027) | Hardware | Anoka, MN, US | Sep 14, 2026 | [Apply](https://nvent.wd5.myworkdayjobs.com/nVent/job/Anoka-MN-US/Manufacturing-Engineering-Co-op--January---June-2027-_R23576) |
| nVent | Manufacturing Engineering Co-op (June - December 2027) | Hardware | Anoka, MN, US | Sep 14, 2026 | [Apply](https://nvent.wd5.myworkdayjobs.com/nVent/job/Anoka-MN-US/Manufacturing-Engineering-Co-op--June---December-2027-_R23578) |
| The Walt Disney Company | Disneyland Resort Industrial Engineering Intern, Summer 2027 | Hardware | Anaheim, CA, USA | Sep 14, 2026 | [Apply](https://disney.wd5.myworkdayjobs.com/disneycareer/job/Anaheim-CA-USA/Disneyland-Resort-Industrial-Engineering-Intern--Summer-2027_10159978-1) |
| The Walt Disney Company | Walt Disney World Industrial Engineering Intern, Summer/Fall 2027 | Hardware | Lake Buena Vista, FL, USA | Sep 14, 2026 | [Apply](https://disney.wd5.myworkdayjobs.com/disneycareer/job/Lake-Buena-Vista-FL-USA/Walt-Disney-World-Industrial-Engineering-Intern--Summer-Fall-2027_10159994-1) |
| TD Bank ✓ | 2027 Summer Internship Program - Global Technology & Solutions - Cloud/DevOps | Software | Mount Laurel, New Jersey | Sep 13, 2026 | [Apply](https://td.wd3.myworkdayjobs.com/TD_Bank_Careers/job/Mount-Laurel-New-Jersey/XMLNAME-2027-Summer-Internship-Program---Global-Technology---Solutions---Cloud-DevOps_R_1510799) |
| TD Bank ✓ | 2027 Summer Internship Program - Global Technology & Solutions - Cyber Security | Security | Mount Laurel, New Jersey | Sep 13, 2026 | [Apply](https://td.wd3.myworkdayjobs.com/TD_Bank_Careers/job/Mount-Laurel-New-Jersey/XMLNAME-2027-Summer-Internship-Program---Global-Technology---Solutions---Cyber-Security_R_1510795) |
| TD Bank ✓ | 2027 Summer Internship Program - Global Technology & Solutions - Data Engineer | Data & ML/AI | Mount Laurel, New Jersey | Sep 13, 2026 | [Apply](https://td.wd3.myworkdayjobs.com/TD_Bank_Careers/job/Mount-Laurel-New-Jersey/XMLNAME-2027-Summer-Internship-Program---Global-Technology---Solutions---Data-Engineer_R_1510797) |
| AnaVation | Computer Science Internship Summer 2027 🇺🇸 | Software | Chantilly, VA | Sep 12, 2026 | [Apply](https://jobs.lever.co/anavationllc/4a82ae00-30f0-410c-bf3c-f1cdd18739e7) |
| Lyft ✓ | Data Analyst Intern (Summer 2027) | Data & ML/AI | New York, NY | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8802198002?gh_jid=8802198002) |
| Lyft ✓ | Data Science Intern, Algorithms (Summer 2027 - SF/NYC) | Data & ML/AI | San Francisco, CA | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8767723002?gh_jid=8767723002) |
| Lyft ✓ | Software Engineer Intern, Backend (Summer 2027 - SF) | Software | San Francisco, CA | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8767726002?gh_jid=8767726002) |
| CACI | Software Engineering Intern – Summer 2027 🇺🇸 | Software | Lisle, IL, US | Sep 11, 2026 | [Apply](https://caci.wd1.myworkdayjobs.com/external/job/Lisle-IL-US/Software-Engineering-Intern---Summer-2027_331742) |
| CACI | Software Engineer Intern - Summer 2027 🇺🇸 | Software | Ypsilanti, MI, US | Sep 11, 2026 | [Apply](https://caci.wd1.myworkdayjobs.com/external/job/Ypsilanti-MI-US/Software-Engineer-Intern---Summer-2027_331648) |
| MegazoneCloud | Software Engineer Co-op 2027 🛂 | Software | Rochester, NY | Sep 11, 2026 | [Apply](https://jobs.ashbyhq.com/megazone/e2889469-cf20-4227-bf24-2a6e885f8dca) |
| MegazoneCloud | Data Engineer Co-op 2027 🛂 | Data & ML/AI | Rochester, NY | Sep 11, 2026 | [Apply](https://jobs.ashbyhq.com/megazone/fde09888-986f-4207-88fe-3ff5b921a1fa) |
| Klaviyo ✓ | Software Engineer Intern (Summer 2027) 🛂 | Software | Boston, MA | Sep 11, 2026 | [Apply](https://job-boards.greenhouse.io/klaviyocampus/jobs/7989364003) |
| Xcimer Energy | Summer 2027 Internship - Mechanical Engineering 🇺🇸 | Hardware | Denver, CO | Sep 11, 2026 | [Apply](https://jobs.lever.co/xcimer/c672a37e-007d-45ee-a4f9-b5d4dd25a2e3) |
| Xcimer Energy | Summer 2027 Internship - Computational and Software Engineering 🇺🇸 | Software | Denver, CO | Sep 11, 2026 | [Apply](https://jobs.lever.co/xcimer/fee9965c-8040-4614-8fd1-10bddfe3b911) |
| ibotta ✓ | Software Engineer Intern | Software | Denver, CO | Sep 11, 2026 | [Apply](https://jobs.ashbyhq.com/ibotta/3130669e-16aa-4f63-834d-b83571c8d269) |
| Amgen ✓ | Grad Intern – Machine Learning Engineer – Technology, AI & Data (Summer 2027) 🏠 | Data & ML/AI | United States - Remote | Sep 11, 2026 | [Apply](https://amgen.wd1.myworkdayjobs.com/careers/job/United-States---Remote/Grad-Intern---Machine-Learning-Engineer---Amgen-s-Technology---Medical-Organizations--Summer-2027-_R-255743) |
| Booz Allen ✓ | University - Summer 2027, Software Engineer Intern 🇺🇸 | Software | Fayetteville, NC | Sep 11, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/Fayetteville-NC/University---Summer-2027--Software-Engineer-Intern_R0249225) |
| Coinbase ✓ | Software Engineer Intern | Software | Hybrid - San Francisco, CA | Sep 08, 2026 | [Apply](https://www.coinbase.com/careers/positions/8168315?gh_jid=8168315) |
| Coinbase ✓ | Machine Learning Engineer Intern | Data & ML/AI | Hybrid - San Francisco, CA | Sep 08, 2026 | [Apply](https://www.coinbase.com/careers/positions/8175441?gh_jid=8175441) |
| Coinbase ✓ | Data Engineer Intern | Data & ML/AI | Hybrid - San Francisco, CA | Sep 08, 2026 | [Apply](https://www.coinbase.com/careers/positions/8175459?gh_jid=8175459) |
| Datadog ✓ | Software Engineering Intern (Summer) | Software | Boston +5 more | Sep 08, 2026 | [Apply](https://careers.datadoghq.com/detail/8052118/?gh_jid=8052118) |
| Scale AI ✓ | Software Engineering Intern (Summer 2027) | Software | San Francisco, CA | Sep 04, 2026 | [Apply](https://job-boards.greenhouse.io/scaleai/jobs/4730845005) |
| Skydio ✓ | Autonomy Engineer Intern, Computer Vision / Deep Learning, Summer 2027 | Data & ML/AI | San Mateo, California, United States | Sep 03, 2026 | [Apply](https://jobs.ashbyhq.com/skydio/ae4a6f7d-a240-4fa2-8c8e-04cc906e4ef9) |
| Roblox ✓ | [Summer 2027] Product Management Intern | Software | San Mateo, CA, United States | Sep 02, 2026 | [Apply](https://careers.roblox.com/jobs/8143981?gh_jid=8143981) |
| Notion ✓ | Software Engineer Intern (Summer 2027) | Software | San Francisco, California | Aug 14, 2026 | [Apply](https://jobs.ashbyhq.com/notion/3fba1c39-c5cb-47d7-9ad2-1cec4d7e9d0c) |
| Roblox ✓ | [Summer 2027] Software Engineer Intern | Software | San Mateo, CA, United States | Aug 05, 2026 | [Apply](https://careers.roblox.com/jobs/8072713?gh_jid=8072713) |
| Hudson River Trading ✓ | Software Engineering Internship (C++ or Python) – Summer 2027 | Software | Austin +11 more | Jul 13, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=8052083) |
| Akuna Capital ✓ | Software Engineer Intern - C++, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018847/?gh_jid=8018847) |
| Akuna Capital ✓ | Software Engineer Intern - Python, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018853/?gh_jid=8018853) |
| Akuna Capital ✓ | Platform Engineer Intern, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018856/?gh_jid=8018856) |
| IMC Trading | Software Engineer Intern - Summer 2027 | Software | Chicago, United States | Jul 01, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4823924101) |
| IMC Trading | Deep Learning Research Intern - Summer 2027 - Chicago, New York | Data & ML/AI | Chicago +3 more | Jul 01, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4907430101) |
| Anduril | 2027 Mechanical Engineer Intern 🇺🇸 | Hardware | Atlanta +26 more | Jun 11, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5153187007?gh_jid=5153187007) |
| Glean ✓ | Software Engineer, Intern (Summer 2027) | Software | Mountain View, CA | Sep 03, 2025 | [Apply](https://job-boards.greenhouse.io/gleanwork/jobs/4595665005) |
| Databricks ✓ | Product Management Intern (Summer 2027) | Software | Bellevue +5 more | Aug 17, 2023 | [Apply](https://databricks.com/company/careers/open-positions/job?gh_jid=6883068002) |
| Rippling | Software Engineer Intern - Backend Focused - Summer 2027 | Software | New York, NY | — | [Apply](https://ats.rippling.com/rippling/jobs/a07e4e46-3721-4934-b57b-0d58412e22ba) |
| Rippling | Data Science Intern - Summer 2027 | Data & ML/AI | San Francisco, CA | — | [Apply](https://ats.rippling.com/rippling/jobs/f255bf03-9173-4c0a-8a18-7cc43c27ded8) |
| Rippling | Full Stack Software Engineer Intern - Summer 2027 | Software | New York, NY | — | [Apply](https://ats.rippling.com/rippling/jobs/f64b6158-9534-4bab-9457-45556166b262) |

## Fall 2026  (38 employer-stated)

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Sierra Nevada Corporation | Aerospace Engineer I (For 2026 Interns Only) 🇺🇸 | Hardware | Lone Tree, CO | Oct 06, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Lone-Tree-CO/Aerospace-Engineer-I--For-2026-Interns-Only-_R0030592) |
| Sierra Nevada Corporation | Software Engineer I (For 2026 Interns Only) 🇺🇸 | Software | Dayton, OH | Oct 06, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Dayton-OH/Software-Engineer-I--For-2026-Interns-Only-_R0030889) |
| Amgen ✓ | Undergrad Co-op – Interactive Developer / Immersive Course Programmer for Manufacturing | Hardware | US - Puerto Rico - Juncos | Oct 06, 2026 | [Apply](https://amgen.wd1.myworkdayjobs.com/careers/job/US---Puerto-Rico---Juncos/Undergrad-Co-op---Interactive-Developer---Immersive-Course-Programmer-for-Manufacturing_R-256886) |
| Sierra Nevada Corporation | Mechanical Engineer I (For 2026 Interns Only) 🇺🇸 | Hardware | Colorado Springs, CO | Oct 05, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Colorado-Springs-CO/Mechanical-Engineer-I--For-2026-Interns-Only-_R0030590) |
| RoboForce | Robotics Mechanical Engineering Intern (Fall/Winter 2026) | Hardware | Milpitas, CA | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/roboforce/jobs/5441463008) |
| S&C Electric Company ✓ | Mechanical Engineer Co-Op | Hardware | Chicago, IL, United States | Sep 29, 2026 | [Apply](https://ejia.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/107299) |
| Moog | Intern, Artificial Intelligence | Data & ML/AI | Buffalo, NY | Sep 29, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Artificial-Intelligence_R-26-20288) |
| GITAI | Field-Deployed Software Engineering Intern – Fall 2026 / Spring 2027 🇺🇸 | Software | Los Angeles, California, United States | Sep 28, 2026 | [Apply](https://job-boards.greenhouse.io/gitai/jobs/5437128008) |
| QuEra Computing | Internship - Scientific Software and Compilation | Software | Boston, MA, USA | Sep 27, 2026 | [Apply](https://job-boards.greenhouse.io/queracomputinginc/jobs/5435902008) |
| American Century Investments | Infrastructure Automation Engineer Intern 🛂 | Software | Kansas City, Missouri | Sep 25, 2026 | [Apply](https://americancentury.wd5.myworkdayjobs.com/AmericanCenturyInvestments/job/Kansas-City-Missouri/Infrastructure-Automation-Engineer-Intern_R0005750) |
| Mill | Computer Vision Intern, Fall/Winter 2026 🛂 | Data & ML/AI | San Bruno, California | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/mill/jobs/4737741005) |
| Eurofins | 6-month paid internship - AI & Automation | Data & ML/AI | Barcelona, CT, ES | Sep 22, 2026 | [Apply](https://jobs.smartrecruiters.com/Eurofins/744000150986035) |
| G2 | Intern, AI Agent Evaluations | Data & ML/AI | San Francisco, CA | Sep 21, 2026 | [Apply](https://jobs.ashbyhq.com/g2/64dcc04a-a0e7-493b-b899-dd4c56e561fd) |
| Bot Auto | Intern, Software Engineer AI Agents (Fall/Winter 2026) | Data & ML/AI | Houston, TX | Sep 18, 2026 | [Apply](https://job-boards.greenhouse.io/botauto/jobs/5429357008) |
| Hunt Oil Company | AI Business Strategy & Transformation Intern - Fall 2026 | Data & ML/AI | Dallas, TX, United States | Sep 17, 2026 | [Apply](https://fa-eqcd-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1067) |
| American Century Investments | Cybersecurity Intern 🛂 | Security | Kansas City, Missouri | Sep 16, 2026 | [Apply](https://americancentury.wd5.myworkdayjobs.com/AmericanCenturyInvestments/job/Kansas-City-Missouri/Cybersecurity-Intern_R0005729) |
| Contoro | Robotics Engineer Intern - Test & Validation (Fall 2026) | Hardware | Austin, TX | Sep 16, 2026 | [Apply](https://jobs.ashbyhq.com/contoro/cf7c8043-8fbe-4c7e-b91f-ee6db2a616c5) |
| Moog | Intern, Mechanical Engineering | Hardware | Torrance, CA | Sep 15, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Torrance-CA/Intern--Mechanical-Engineering_R-26-19918-1) |
| Moog | Intern, Embedded Design Engineering | Software | Blacksburg, VA | Sep 11, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Blacksburg-VA/Intern--Embedded-Design-Engineering_R-26-20053) |
| Eurofins | 6-month paid internship - AI & Automation | Data & ML/AI | Barcelona, CT, ES | Sep 10, 2026 | [Apply](https://jobs.smartrecruiters.com/Eurofins/744000148712379) |
| Eurofins | AI & Automation Intern | Data & ML/AI | Barcelona, CT, ES | Sep 09, 2026 | [Apply](https://jobs.smartrecruiters.com/Eurofins/744000148531473) |
| Re:Build Manufacturing | Manufacturing Engineer Intern Fall 2026 | Hardware | Merrimack, NH | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/rebuildmanufacturing/jobs/4729848005) |
| Northrop Grumman | 2026 Part-Time Cyber Security Engineering Intern - Aurora CO 🇺🇸 | Security | United States-Colorado-Aurora | Aug 31, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Colorado-Aurora/XMLNAME-2026-Part-Time-Cyber-Security-Engineering-Intern---Aurora-CO_R10248520) |
| Amazon ✓ | Robotics - Software Development Engineer Fall Intern/Co-op - 2026 | Hardware | Westboro, Massachusetts, USA | Aug 27, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10517149/robotics-software-development-engineer-fall-intern-co-op-2026) |
| Northrop Grumman | 2026 Part-Time Mechanical Engineering Intern - Chandler AZ 🇺🇸 | Hardware | United States-Arizona-Chandler | Aug 26, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Arizona-Chandler/XMLNAME-2026-Part-Time-Mechanical-Engineering-Intern---Chandler-AZ_R10247965) |
| Johnson & Johnson | Software Engineer Coop | Software | Cincinnati +2 more | Aug 07, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cincinnati-Ohio-United-States-of-America/Software-Engineer-Coop_R-092820) |
| Phoenix Contact | Manufacturing Co-Op - High School Students | Hardware | Middletown, Pennsylvania | Aug 04, 2026 | [Apply](https://job-boards.greenhouse.io/phoenixcontact/jobs/7817228003) |
| Merck | 2026 Future Talent Program – Manufacturing and Reliability Engineering Co-Op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Manufacturing-and-Reliability-Engineering-Co-Op_R395901) |
| Merck | 2026 Future Talent Program - Vaccine Manufacturing Co-op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Vaccine-Manufacturing-Co-op_R395900) |
| Northrop Grumman | 2026 Fall Co-op Manufacturing Engineering - Baltimore MD 🇺🇸 | Hardware | United States-Maryland-Linthicum | Aug 03, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Maryland-Linthicum/XMLNAME-2026-Fall-Co-op-Manufacturing-Engineering---Baltimore-MD_R10243390-1) |
| Skydio ✓ | Hardware Product Management Intern - Fall 2026/Winter 2027 | Hardware | San Mateo, California, United States | Jul 31, 2026 | [Apply](https://jobs.ashbyhq.com/skydio/1ec2fe3c-3fb2-4485-870d-764a3e5f5baf) |
| NVIDIA ✓ | Applied Research Intern, NLP - Fall 2026 | Data & ML/AI | US, CA, Santa Clara | Jul 01, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/US-CA-Santa-Clara/Applied-Research-Intern--NLP---Fall-2026_JR2010488) |
| Beacon Software | Software Engineering Intern | Software | San Francisco, CA | Jun 02, 2026 | [Apply](https://jobs.ashbyhq.com/beaconsoftware/2452d342-a069-4eda-adbe-9df296808ca1) |
| RoboForce | Robotics Electrical Engineering Intern (Fall/Winter 2026) | Hardware | Milpitas, CA | Apr 14, 2026 | [Apply](https://job-boards.greenhouse.io/roboforce/jobs/5181214008) |
| Applied Materials ✓ | 2026 Fall Materials Engineering Co-op (TCAD Modeling) - Doctorate (Gloucester, MA) | Hardware | Gloucester,MA | Apr 01, 2026 | [Apply](https://amat.wd1.myworkdayjobs.com/External/job/GloucesterMA/XMLNAME-2026-Fall-Materials-Engineering-Co-op---Doctorate--Gloucester--MA-_R2611503) |
| Alloy Enterprises | Co-Op, Thermal Test Engineer, Fall 2026 (July-December) 🇺🇸 | Hardware | Burlington, MA | Mar 25, 2026 | [Apply](https://jobs.ashbyhq.com/alloyenterprises/946e7ae1-d2ac-4889-a72a-268b0aeda9bd) |
| Amazon ✓ | Robotics - Hardware Development Engineer Intern/Co-op - 2026 (Robotics, Mechanical, Electrical, Hardware Test, Reliability, Failure Analysis, Operations, and more) | Hardware | Westboro, Massachusetts, USA | Dec 17, 2025 | [Apply](https://www.amazon.jobs/en/jobs/3145033/robotics-hardware-development-engineer-intern-co-op-2026-robotics-mechanical-electrical-hardware-test-reliability-failure-analysis-operations-and-more) |
| Amazon ✓ | Robotics - Applied Scientist II Intern / Co-op - 2026 (Robotics, Manipulation, Perception, Motion Planning, Autonomous Mobile Robots, Computer Vision, Machine Learning, Controls, and more) | Data & ML/AI | North Reading, Massachusetts, USA | Oct 08, 2025 | [Apply](https://www.amazon.jobs/en/jobs/3104589/robotics-applied-scientist-ii-intern-co-op-2026-robotics-manipulation-perception-motion-planning-autonomous-mobile-robots-computer-vision-machine-learning-controls-and-more) |

## Recently posted — cycle not stated  (330 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Micron Technology ✓ | Intern - IT Software Engineer 🆕 | Software | Boise, ID - Main Site | Oct 09, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Boise-ID---Main-Site/Intern---IT-Software-Engineer_JR113941) |
| Arcesium ✓ | Software Engineer Intern 🆕 | Software | New York | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/arcesiumllc/jobs/5257176007) |
| Olsson | Structural Engineering Internship - Facilities 🆕 | Hardware | Dallas, TX; Fort Worth, TX | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5441485008) |
| Syska Hennessy Group | Mechanical Engineer Summer Intern 🆕 | Hardware | Tampa, FL | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/syskahennessy/jobs/8267628) |
| Bosch | Information Security and Privacy Intern 🆕 | Security | Farmington Hills, MI, United States | Oct 09, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000154757409) |
| Bosch | Artificial Intelligence / Machine Learning: Foundation Models - Intern 🆕 | Data & ML/AI | Sunnyvale, CA, United States | Oct 09, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000154759734) |
| Bosch | Manufacturing Engineering Intern 🆕 | Hardware | Grand Rapids, MI, United States | Oct 09, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000154762134) |
| Loram | Machine Learning / Artificial Intelligence (AI) Intern 🆕 | Data & ML/AI | Hamel, MN, United States | Oct 09, 2026 | [Apply](https://jobs.smartrecruiters.com/Loram1/3743990016031492) |
| Alcon ✓ | Clinical Data Science Intern 🛂 🆕 | Data & ML/AI | Fort Worth, Texas | Oct 09, 2026 | [Apply](https://alcon.wd5.myworkdayjobs.com/careers_alcon/job/Fort-Worth-Texas/Clinical-Data-Science-Intern_R-2026-50204) |
| Daimler Truck ✓ | Data Science Intern 🆕 | Data & ML/AI | Portland, OR US | Oct 09, 2026 | [Apply](https://dtna.wd5.myworkdayjobs.com/DTNA_external/job/Portland-OR-US/Data-Science-Intern_DT-20166) |
| Micron Technology ✓ | Intern - SSD Firmware - CICD 🆕 | Hardware | Longmont-MAX- Office, CO | Oct 09, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Longmont-MAX--Office-CO/Intern---SSD-Firmware---CICD_JR114542) |
| Arcesium ✓ | Infrastructure Engineer Intern 🆕 | Software | New York | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/arcesiumllc/jobs/5257199007) |
| Texas Instruments ✓ | Software Engineering Intern (Longmont, CO) 🛂 🆕 | Software | Longmont, CO, United States | Oct 09, 2026 | [Apply](https://edbz.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/25012948) |
| Gorbel | Manufacturing Engineer Co-Op 🆕 | Hardware | USA, New York, Victor | Oct 09, 2026 | [Apply](https://gorbel.wd501.myworkdayjobs.com/gorbelcareers/job/USA-New-York-Victor/Manufacturing-Engineer-Co-Op_REQ-2026-2326-1) |
| KLA ✓ | Mechanical Engineering Intern 🆕 | Hardware | Ann Arbor, MI | Oct 09, 2026 | [Apply](https://kla.wd1.myworkdayjobs.com/Search/job/Ann-Arbor-MI/Mechanical-Engineering-Intern_2640653-2) |
| Aptiv ✓ | Linux Software Development Intern 🆕 | Software | USA Home Office - WR | Oct 09, 2026 | [Apply](https://aptiv.wd5.myworkdayjobs.com/aptiv_careers/job/USA-Home-Office---WR/Linux-Software-Development-Intern_J000704398) |
| Aptiv ✓ | Linux Software Development Intern 🆕 | Software | USA Home Office - WR | Oct 09, 2026 | [Apply](https://aptiv.wd5.myworkdayjobs.com/aptiv_careers/job/USA-Home-Office---WR/Linux-Software-Development-Intern_J000704399) |
| Aptiv ✓ | Embedded Software - Engineering Intern 🇺🇸 🆕 | Software | USA Walnut Creek, CA - WR | Oct 09, 2026 | [Apply](https://aptiv.wd5.myworkdayjobs.com/aptiv_careers/job/USA-Walnut-Creek-CA---WR/Embedded-Software---Engineering-Intern_J000704386) |
| Crane Co. ✓ | Manufacturing Intern-1 🆕 | Hardware | Montgomery, Texas | Oct 08, 2026 | [Apply](https://cranecompany.wd5.myworkdayjobs.com/Careers/job/Montgomery-Texas/Manufacturing-Intern-1_JR102723) |
| Centific | AI Research Intern -  Physical AI 🏠 🆕 | Data & ML/AI | Remote Work( USA) | Oct 08, 2026 | [Apply](https://centific.wd1.myworkdayjobs.com/Centific_Global/job/Remote-Work-USA/AI-Research-Intern----Physical-AI_JR108131-1) |
| Hewlett Packard Enterprise ✓ | Thermal Engineering Intern 🆕 | Hardware | Sunnyvale +2 more | Oct 08, 2026 | [Apply](https://hpe.wd5.myworkdayjobs.com/Jobsathpe/job/Sunnyvale-California-United-States-of-America/Thermal-Engineering-Intern_1214190) |
| Perpay | Super Day - Data Science Internship 🆕 | Data & ML/AI | Philadelphia +2 more | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/perpay/jobs/5260960007) |
| Wabtec ✓ | Mechanical Engineer Intern - Production Operations 🆕 | Hardware | Oak Creek, WI, United States | Oct 08, 2026 | [Apply](https://jobs.smartrecruiters.com/Wabtec/3743990016001786) |
| Wabtec ✓ | Mechanical Engineer Intern - New Product Development 🆕 | Hardware | Oak Creek, WI, United States | Oct 08, 2026 | [Apply](https://jobs.smartrecruiters.com/Wabtec/3743990016001927) |
| Booz Allen ✓ | University, Applied AI Software Development Intern 🇺🇸 🆕 | Data & ML/AI | McLean, VA | Oct 08, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/McLean-VA/University--Applied-AI-Software-Development-Intern_R0251314) |
| Johnson & Johnson | AI Excellence, Decision Enablement Intern 🆕 | Data & ML/AI | Spring House +2 more | Oct 08, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Spring-House-Pennsylvania-United-States-of-America/AI-Excellence--Decision-Enablement-Intern_R-102881) |
| Syska Hennessy Group | Mechanical Engineering Summer Intern 🆕 | Hardware | Hamilton, NJ | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/syskahennessy/jobs/8177728) |
| GenBio AI | Research Scientist Intern, AI Molecular Design 🆕 | Data & ML/AI | Palo Alto, CA | Oct 08, 2026 | [Apply](https://jobs.lever.co/genbio/7d0b5764-48ce-4d06-93d2-431742d35604) |
| American Electric Power ✓ | Data Scientist Intern - Columbus, OH 🆕 | Data & ML/AI | Columbus, OH | Oct 08, 2026 | [Apply](https://aep.wd1.myworkdayjobs.com/AEPCareerSite/job/Columbus-OH/Data-Scientist-Intern---Columbus--OH_R19884) |
| Badger Meter | Software Engineering Intern 🆕 | Software | US  - CA - Escondido Facility | Oct 08, 2026 | [Apply](https://badgermeter.wd5.myworkdayjobs.com/US_CareerSite/job/US----CA---Escondido-Facility/Software-Engineering-Intern_4645) |
| Cox | Data Scientist Co-op 🆕 | Data & ML/AI | Atlanta GA | Oct 08, 2026 | [Apply](https://cox.wd1.myworkdayjobs.com/Cox_External_Career_Site_1/job/Atlanta-GA/Data-Scientist-Co-op_R202683033) |
| Gordon Food Service ✓ | Software Engineer Intern (Transportation Routing ) 🆕 | Software | Wyoming, Michigan | Oct 08, 2026 | [Apply](https://gfs.wd5.myworkdayjobs.com/usjobs-gen-gfs/job/Wyoming-Michigan/Software-Engineer-Intern--Transportation-Routing--_R-58374) |
| Leidos ✓ | Systems, Integration and Software Engineer Intern 🇺🇸 🆕 | Software | Atlantic City, NJ | Oct 08, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Atlantic-City-NJ/Systems--Integration-and-Software-Engineer-Intern_R-00194152) |
| Axos Bank | AI Engineer Intern 🆕 | Data & ML/AI | HQ - San Diego, CA | Oct 07, 2026 | [Apply](https://axos.wd5.myworkdayjobs.com/Axos/job/HQ---San-Diego-CA/AI-Engineer-Intern_JR5658) |
| Axos Bank | Software Development Intern 🆕 | Software | HQ - San Diego, CA | Oct 07, 2026 | [Apply](https://axos.wd5.myworkdayjobs.com/Axos/job/HQ---San-Diego-CA/Software-Development-Intern_JR5647) |
| Avav | Mechanical Engineering Intern 🇺🇸 | Hardware | Petaluma, CA | Oct 07, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Petaluma-CA/Mechanical-Engineering-Intern_9038) |
| Northrop Grumman | San Diego Manufacturing Technician Intern - Fall 🇺🇸 | Hardware | United States-California-San Diego | Oct 07, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-California-San-Diego/San-Diego-Manufacturing-Technician-Intern---Fall_R10255107) |
| IMEG ✓ | Mechanical Co-op | Hardware | Raleigh, NC | Oct 07, 2026 | [Apply](https://wd1.myworkdaysite.com/recruiting/imeg/Imeg_Careers/job/Raleigh-NC/Mechanical-Co-op_R-16838) |
| Northrop Grumman | Chandler Manufacturing Technician Intern - Fall 🇺🇸 | Hardware | United States-Arizona-Chandler | Oct 07, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Arizona-Chandler/Chandler-Manufacturing-Technician-Intern---Fall_R10250966) |
| Northrop Grumman | Chandler Manufacturing Technician Intern (2nd Shift) - Fall 🇺🇸 | Hardware | United States-Arizona-Chandler | Oct 07, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Arizona-Chandler/Chandler-Manufacturing-Technician-Intern--2nd-Shift----Fall_R10254794) |
| Entrust | Firmware Engineering Co-op | Hardware | United States - Shakopee, MN (GHQ) | Oct 07, 2026 | [Apply](https://entrust.wd1.myworkdayjobs.com/entrustcareers/job/United-States---Shakopee-MN-GHQ/Firmware-Engineering-Co-op_R004419) |
| Intel ✓ | AI Solution Architect - Undergraduate Intern | Data & ML/AI | US, Oregon, Hillsboro | Oct 07, 2026 | [Apply](https://intel.wd1.myworkdayjobs.com/external/job/US-Oregon-Hillsboro/AI-Solution-Architect---Undergraduate-Intern_JR0287931) |
| Leidos ✓ | Business Systems AI Intern 🇺🇸 🏠 | Data & ML/AI | 6314 Remote/Teleworker US | Oct 07, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/6314-RemoteTeleworker-US/Business-Systems-AI-Intern_R-00193769) |
| Moss & Associates ✓ | Mechanical Administrator Internship | Hardware | FORT LAUDERDALE, FL | Oct 07, 2026 | [Apply](https://mosscm.wd1.myworkdayjobs.com/moss_careers/job/FORT-LAUDERDALE-FL/Mechanical-Administrator-Internship_R-3031) |
| Tenstorrent ✓ | AI Software Intern - Cloud, Infrastructure & Data Centre Deployment (USA) | Data & ML/AI | Austin +5 more | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5256686007) |
| Tenstorrent ✓ | Hardware Intern - Architecture, AI HW & SoC (USA) | Data & ML/AI | Austin +11 more | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5256691007) |
| Tenstorrent ✓ | AI Software Intern (USA) | Data & ML/AI | Austin +5 more | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5258901007) |
| Nokia ✓ | AI Engineering Co-op | Data & ML/AI | United States | Oct 06, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/40566) |
| Badger Meter | Mechanical Engineering NPD Intern | Hardware | US - WI - Milwaukee HQ | Oct 06, 2026 | [Apply](https://badgermeter.wd5.myworkdayjobs.com/US_CareerSite/job/US---WI---Milwaukee-HQ/Mechanical-Engineering-NPD-Intern_4642) |
| Leidos ✓ | Business Systems AI Intern 🇺🇸 🏠 | Data & ML/AI | 6314 Remote/Teleworker US | Oct 06, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/6314-RemoteTeleworker-US/Business-Systems-AI-Intern_R-00193327) |
| Vantor | Summer Internship: Aerospace Modeling & Simulation 🇺🇸 | Hardware | Herndon, VA | Oct 06, 2026 | [Apply](https://maxar.wd1.myworkdayjobs.com/Vantor/job/Herndon-VA/Summer-Internship--Aerospace-Modeling---Simulation_R24758) |
| Axis Automation | GVSU Mechanical Engineering Intern Co-op | Hardware | Walker, Michigan, United States | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/axiscompany/jobs/8871027002) |
| Allegion | Summer Intern - Product Management | Software | Carmel, IN | Oct 06, 2026 | [Apply](https://allegion.wd5.myworkdayjobs.com/careers/job/Carmel-IN/Summer-Intern---Product-Management_JR37369-1) |
| Avav | Hypersonic RF Software Engineering Intern 🇺🇸 | Software | Germantown, MD | Oct 06, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Germantown-MD/Hypersonic-RF-Software-Engineering-Intern_8993) |
| Kenco Management Services ✓ | Industrial Engineering Intern | Hardware | Wilmer, TX | Oct 06, 2026 | [Apply](https://kencogroup.wd12.myworkdayjobs.com/kenco/job/Wilmer-TX/SCS-Intern_JR106615) |
| Field AI | Mechanical Engineer Internship, Robotics Hardware | Hardware | Boston, MA | Oct 06, 2026 | [Apply](https://jobs.lever.co/field-ai/5ae428f8-ac13-49b2-a244-fb97d31bfc79) |
| Atoms | Manufacturing Intern | Hardware | San Francisco, CA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/atoms/jobs/8868917002) |
| Atoms | Machine Learning Engineer Intern | Data & ML/AI | San Francisco, CA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/atoms/jobs/8869105002) |
| Hewlett Packard Enterprise ✓ | Cloud Developer Intern | Software | San Jose +2 more | Oct 05, 2026 | [Apply](https://hpe.wd5.myworkdayjobs.com/Jobsathpe/job/San-Jose-California-United-States-of-America/Cloud-Developer-Intern_1214950) |
| TensorWave | Developer Community Engagement Intern | Software | Las Vegas, Nevada | Oct 05, 2026 | [Apply](https://jobs.ashbyhq.com/tensorwave/34dd183d-4423-40e3-bb6d-790b5dafc731) |
| TensorWave | Software Engineering Intern | Software | Las Vegas, Nevada | Oct 05, 2026 | [Apply](https://jobs.ashbyhq.com/tensorwave/39091eeb-13fc-46a7-b7e5-0d4584ac53ab) |
| TensorWave | Security Engineer Intern | Security | Las Vegas, Nevada | Oct 05, 2026 | [Apply](https://jobs.ashbyhq.com/tensorwave/8ec8b715-f9ad-48a7-869e-ed9d455119a5) |
| Atoms | Manufacturing Intern | Hardware | San Francisco, CA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/cssmerge/jobs/8868918002) |
| Found Energy | Data Engineer Co-op | Data & ML/AI | Cambridge, MA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/foundenergy/jobs/4719227006) |
| Graco | Cybersecurity Intern 🛂 | Security | Dayton, Minnesota, USA (French Lake) | Oct 05, 2026 | [Apply](https://graco.wd501.myworkdayjobs.com/Graco_Careers/job/Dayton-Minnesota-USA-French-Lake/Cybersecurity-Intern_R0023516) |
| Intel ✓ | AI Solution Architect - Graduate Intern | Data & ML/AI | US, California, Santa Clara | Oct 05, 2026 | [Apply](https://intel.wd1.myworkdayjobs.com/external/job/US-California-Santa-Clara/AI-Solution-Architect---Graduate-Intern_JR0287524) |
| Intel ✓ | AI Solution Architect Graduate Intern | Data & ML/AI | US, California, Santa Clara | Oct 05, 2026 | [Apply](https://intel.wd1.myworkdayjobs.com/external/job/US-California-Santa-Clara/AI-Solution-Architect-Graduate-Intern_JR0287530) |
| Micron Technology ✓ | Intern - SMAI TD AI Engineering Team | Data & ML/AI | Boise, ID - Main Site | Oct 05, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Boise-ID---Main-Site/Intern---SMAI-TD-AI-Engineering-Team_JR112991) |
| BorgWarner | Manufacturing Process Engineering Intern 🛂 | Hardware | Kokomo Technical Center - Indiana - USA | Oct 05, 2026 | [Apply](https://borgwarner.wd5.myworkdayjobs.com/BorgWarner_Careers/job/Kokomo-Technical-Center---Indiana---USA/Manufacturing-Process-Engineering-Intern_R2026-3943-1) |
| RTX | Co-Op - AI DSP Applied Research 🇺🇸 | Data & ML/AI | US-IA-CEDAR RAPIDS-108 ~ 400 Collins Rd… | Oct 03, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-108--400-Collins-Rd-NE--BLDG-108/Co-Op---AI-DSP-Applied-Research_01873016) |
| DISA Technologies | Data Engineering & ML Intern | Data & ML/AI | Casper, Wyoming, United States | Oct 02, 2026 | [Apply](https://apply.workable.com/disa-technologies/j/73E7609B99/) |
| Wabtec ✓ | Transducer Manufacturing Engineering Co-Op | Hardware | Waltham, MA, United States | Oct 02, 2026 | [Apply](https://jobs.smartrecruiters.com/Wabtec/3743990015874986) |
| AECOM ✓ | Structural Engineering Co-Op - Buildings | Hardware | Boston, MA, United States | Oct 02, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000153254989) |
| Magna International | Humanoid Robotics Intern | Hardware | Troy, Michigan, US | Oct 02, 2026 | [Apply](https://magna.wd3.myworkdayjobs.com/Magna/job/Troy-Michigan-US/Humanoid-Robotics-Intern_R00264476) |
| Trimble ✓ | Product Management Intern 🛂 | Software | US - CO, Westminster | Oct 02, 2026 | [Apply](https://trimble.wd1.myworkdayjobs.com/TrimbleCareers/job/US---CO-Westminster/Product-Management-Intern_R57893) |
| ShopBack | Software Engineer Intern | Software | San Francisco, California | Oct 02, 2026 | [Apply](https://jobs.lever.co/shopback-2/640ac3fb-dae5-4738-95b9-9cb80cc7ad15) |
| ShopBack | Software Engineer Intern | Software | New York City, New York | Oct 02, 2026 | [Apply](https://jobs.lever.co/shopback-2/e5f5e276-e7f7-43e0-a224-5259d242fe98) |
| The Toro Company | Mechatronics Engineering Co-Op | Hardware | Bloomington, MN | Oct 02, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Bloomington-MN/Mechatronics-Engineering-Co-Op_JR17153) |
| ZOLL Medical Corporation | Manufacturing Engineering Co-op | Hardware | Pawtucket, RI | Oct 02, 2026 | [Apply](https://zoll.wd5.myworkdayjobs.com/ZOLLMedicalCorp/job/Pawtucket-RI/Manufacturing-Engineering-Co-op_R20367) |
| Profluent | Intern, Software Engineering | Software | Emeryville, California, United States | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/profluent/jobs/5441955008) |
| American Bankers Association | Intern, Cybersecurity Policy Analyst | Security | US DC Main Office | Oct 01, 2026 | [Apply](https://aba.wd1.myworkdayjobs.com/aba/job/US-DC-Main-Office/Intern--Cybersecurity-Policy-Analyst_R611) |
| Range | Software Engineering Intern | Software | McLean, VA | Oct 01, 2026 | [Apply](https://jobs.ashbyhq.com/range/5fe3697d-b5b3-4772-9de4-1551cb726718) |
| Attentive ✓ | Product Management Intern, Agentic Integrations | Software | United States | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/attentive/jobs/4429880009) |
| Gas South | Software Engineering Intern | Software | Atlanta, Georgia | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/gassouth/jobs/8247622) |
| Nordson | Software Intern | Software | USA - Minnesota - Minneapolis - 5900 Go… | Oct 01, 2026 | [Apply](https://nordsonhcm.wd501.myworkdayjobs.com/nordsoncareers/job/USA---Minnesota---Minneapolis---5900-Golden-Hills-Drive/Software-Intern_REQ52945) |
| Nordson | Intern (Software Engineering) | Software | USA - Rhode Island - East Providence | Oct 01, 2026 | [Apply](https://nordsonhcm.wd501.myworkdayjobs.com/nordsoncareers/job/USA---Rhode-Island---East-Providence/Intern--Software-Engineering-_REQ53006) |
| Stripe ✓ | Data Analyst, Intern | Data & ML/AI | New York +2 more | Oct 01, 2026 | [Apply](https://stripe.com/jobs/search?gh_jid=8194291) |
| Nokia ✓ | AI R&D Engineer Co-op | Data & ML/AI | United States | Oct 01, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/40702) |
| Cisco ✓ | Software Engineer I (Co-op) - United States | Software | Maynard, Massachusetts, US | Oct 01, 2026 | [Apply](https://cisco.wd5.myworkdayjobs.com/cisco_careers/job/Maynard-Massachusetts-US/Software-Engineer-I--Co-op----United-States_2026920) |
| Cisco ✓ | Software Engineer II (Co-op) - United States | Software | Maynard, Massachusetts, US | Oct 01, 2026 | [Apply](https://cisco.wd5.myworkdayjobs.com/cisco_careers/job/Maynard-Massachusetts-US/Software-Engineer-II--Co-op----United-States_2026923) |
| Cisco ✓ | Mechanical Engineer I (Intern) - United States | Hardware | San Jose, California, US | Oct 01, 2026 | [Apply](https://cisco.wd5.myworkdayjobs.com/cisco_careers/job/San-Jose-California-US/Mechanical-Engineer-I--Intern----United-States_2026028) |
| Hitachi Energy ✓ | Intern - Industrial Engineering | Hardware | Batesburg-Leesville +2 more | Oct 01, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Batesburg-Leesville-South-Carolina-United-States-of-America/Intern---Industrial-Engineering_R0144157) |
| Hitachi Energy ✓ | Intern - Manufacturing Planner | Hardware | Batesburg-Leesville +2 more | Oct 01, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Batesburg-Leesville-South-Carolina-United-States-of-America/Intern---Manufacturing-Planner_R0144125) |
| Polaris ✓ | Materials Engineering Intern 🛂 | Hardware | Wyoming, MN, USA | Oct 01, 2026 | [Apply](https://polaris.wd5.myworkdayjobs.com/PolarisJobs/job/Wyoming-MN-USA/Materials-Engineering-Intern_R31381) |
| Base Power | Mechanical Engineering Intern | Hardware | Austin, TX | Sep 30, 2026 | [Apply](https://jobs.ashbyhq.com/base-power/717274d7-09dc-4176-b307-07301074b87f) |
| GenScript ✓ | AI Intern, Enterprise Agent Development | Data & ML/AI | Piscataway, New Jersey, United States | Sep 30, 2026 | [Apply](https://job-boards.greenhouse.io/genscript/jobs/5253581007) |
| Allegion | Summer Intern - Software Engineering - Quality Assurance | Software | Golden, CO | Sep 30, 2026 | [Apply](https://allegion.wd5.myworkdayjobs.com/careers/job/Golden-CO/Summer-Intern---Summer-Intern---Software-Engineering---Quality-Assurance_JR37856-1) |
| KLA ✓ | Mechatronics Engineering Internship | Hardware | Milpitas, CA | Sep 30, 2026 | [Apply](https://kla.wd1.myworkdayjobs.com/Search/job/Milpitas-CA/Mechatronics-Engineering-Internship_2641518-1) |
| KLA ✓ | Mechatronics/Systems Engineering Internship | Hardware | Milpitas, CA | Sep 30, 2026 | [Apply](https://kla.wd1.myworkdayjobs.com/Search/job/Milpitas-CA/Mechatronics-Systems-Engineering-Internship_2641532-1) |
| Wellmark ✓ | Software Engineer Internship – Metadata Enablement Team | Software | Des Moines, IA, United States | Sep 30, 2026 | [Apply](https://jobs.smartrecruiters.com/WellmarkInc/744000152679699) |
| RTX | Manufacturing Engineer Intern - 1st shift - On site - Aeroestructuras | Hardware | MX-BCN-MEXICALI-238 ~ Blvd Venustiano Carranza #238 ~ BLDG 238 +1 more | Sep 30, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/MX-BCN-MEXICALI-238--Blvd-Venustiano-Carranza-238--BLDG-238-Desarrollo-Industrial-Colorado/Manufacturing-Engineer-Intern---1st-shift---On-site---Aeroestructuras_01872645) |
| Clay | Software Engineering Intern | Software | New York | Sep 29, 2026 | [Apply](https://jobs.ashbyhq.com/claylabs/5b7eced2-36bd-4265-a2a8-da0f786e47aa) |
| Plot Technologies | Co-op -- Applied AI | Data & ML/AI | New York City | Sep 29, 2026 | [Apply](https://jobs.ashbyhq.com/plot/5f8cfeaa-c368-480f-aaa5-de52452a63d0) |
| Avav | Titan-SV Software Engineer Intern 🇺🇸 | Software | Leesburg, VA | Sep 29, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Leesburg-VA/Titan-SV-Software-Engineer-Intern_8901) |
| Johnson & Johnson | Manufacturing Execution Systems Co-op | Hardware | Raritan +2 more | Sep 29, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Raritan-New-Jersey-United-States-of-America/Manufacturing-Execution-Systems-Co-op_R-099373) |
| Moog | Intern, Software Engineering | Software | Torrance, CA | Sep 29, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Torrance-CA/Intern--Software-Engineering_R-26-19948) |
| Nike ✓ | NIKE, Inc. AI & Machine Learning, Innovation Graduate Internship | Data & ML/AI | Beaverton, Oregon | Sep 29, 2026 | [Apply](https://nike.wd1.myworkdayjobs.com/nke/job/Beaverton-Oregon/NIKE--Inc-AI---Machine-Learning--Innovation-Graduate-Internship_R-94412) |
| ABB ✓ | R&D Mechanical Engineering Co-op 🛂 | Hardware | Greenville +2 more | Sep 29, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Greenville-South-Carolina-United-States-of-America/R-D-Mechanical-Engineering-Co-op_JR00048185) |
| ABB ✓ | R&D Mechanical Engineering Co-op 🛂 | Hardware | Greenville +2 more | Sep 29, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Greenville-South-Carolina-United-States-of-America/R-D-Mechanical-Engineering-Co-op_JR00048188-1) |
| The Toro Company | Manufacturing Engineer Co-Op - BOSS Snowplow | Hardware | Iron Mountain, MI | Sep 29, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Iron-Mountain-MI/Manufacturing-Engineer-Co-Op_JR17469) |
| The Toro Company | Mechanical Design Engineer Co Op - BOSS Snowplow | Hardware | Iron Mountain, MI | Sep 29, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Iron-Mountain-MI/Mechanical-Design-Engineer-Co-Op---BOSS-Snowplow_JR17092) |
| Gilead Sciences ✓ | Intern - Research - Inflammation - AI | Data & ML/AI | United States - California - Foster City | Sep 28, 2026 | [Apply](https://gilead.wd1.myworkdayjobs.com/gileadcareers/job/United-States---California---Foster-City/Intern---Research---Inflammation_R0054741) |
| Keenfinity | Software Engineering Intern | Software | Lincoln, NE, United States | Sep 28, 2026 | [Apply](https://jobs.smartrecruiters.com/Keenfinity/744000152241469) |
| BorgWarner | Mechanical Engineering Intern (Year Round) | Hardware | Auburn Hills - Michigan - USA | Sep 28, 2026 | [Apply](https://borgwarner.wd5.myworkdayjobs.com/BorgWarner_Careers/job/Auburn-Hills---Michigan---USA/Mechanical-Engineering-Intern--Year-Round-_R2026-3788) |
| Cummins ✓ | Structural, Dynamic and Acoustic Systems - Summer Internship Positions | Hardware | Columbus, IN, United States | Sep 28, 2026 | [Apply](https://fa-espx-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2437307) |
| Cummins ✓ | Structural, Dynamic and Acoustic Systems - Co-Op Positions | Hardware | Columbus, IN, United States | Sep 28, 2026 | [Apply](https://fa-espx-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2437754) |
| Nordson | Intern (Mechanical Engineering) | Hardware | USA - Rhode Island - East Providence | Sep 28, 2026 | [Apply](https://nordsonhcm.wd501.myworkdayjobs.com/nordsoncareers/job/USA---Rhode-Island---East-Providence/Intern--Mechanical-Engineering-_REQ52997) |
| Veolia | SAP & ServiceNow AI Automation Intern 🛂 | Data & ML/AI | Trevose, PA, United States | Sep 25, 2026 | [Apply](https://jobs.smartrecruiters.com/VeoliaEnvironnementSA/744000151947749) |
| American Family Insurance Group | Intern - Application Billing Center Developer | Software | WI Madison | Sep 25, 2026 | [Apply](https://amfam.wd1.myworkdayjobs.com/AmFamGroupInternCareers/job/WI-Madison/Intern---Application-Billing-Center-Developer_R39407) |
| American Family Insurance Group | ML Ops Intern | Data & ML/AI | WI Madison | Sep 25, 2026 | [Apply](https://amfam.wd1.myworkdayjobs.com/AmFamGroupInternCareers/job/WI-Madison/ML-Ops-Intern_R39493) |
| Zurn Elkay Water Solutions | Manufacturing Engineer Intern | Hardware | Sanford, NC | Sep 25, 2026 | [Apply](https://elkay.wd1.myworkdayjobs.com/Elkay_External/job/Sanford-NC/Manufacturing-Engineer-Intern_REQ-020175) |
| Michael Baker International ✓ | Mechanical Engineering Intern | Hardware | Moon Township, PA, United States | Sep 25, 2026 | [Apply](https://ebxs.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/309934) |
| Michael Baker International ✓ | Mechanical Engineering Intern | Hardware | Baltimore, MD, United States | Sep 25, 2026 | [Apply](https://ebxs.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/309935) |
| Allegion | Summer Intern - Software Engineering | Software | Golden, CO | Sep 25, 2026 | [Apply](https://allegion.wd5.myworkdayjobs.com/careers/job/Golden-CO/Summer-Intern---Software-Engineering_JR37795-1) |
| Analog Devices ✓ | Healthcare Mechanical Engineering Co-op (Spring) | Hardware | US, MA, Wilmington | Sep 25, 2026 | [Apply](https://analogdevices.wd1.myworkdayjobs.com/External/job/US-MA-Wilmington/Healthcare-Mechanical-Engineering-Co-op--Spring-_R266691) |
| Copart ✓ | Data & AI Intern | Data & ML/AI | Dallas, TX - Headquarters | Sep 25, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Data---AI-Intern_JR111596) |
| Gilead Sciences ✓ | Intern - Research - Pathobiology - AI | Data & ML/AI | United States - California - Foster City | Sep 25, 2026 | [Apply](https://gilead.wd1.myworkdayjobs.com/gileadcareers/job/United-States---California---Foster-City/Intern---Research---Pathobiology_R0054579) |
| Heven AeroTech | Manufacturing Intern 🇺🇸 | Hardware | Winchester, Virginia | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/hevenaerotech/jobs/4410446009) |
| Aevex Aerospace | Robotics Engineering Co-op 🇺🇸 | Hardware | Tampa, Florida, United States | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/aevexaerospace/jobs/5415815008) |
| Reflect Orbital | Ground Software Engineering Intern | Software | Hawthorne, CA | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/c394615d-26c6-4435-ad84-3ca3269c2952) |
| Johnson & Johnson | Software Engineering Co-Op | Software | Danvers +2 more | Sep 24, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Danvers-Massachusetts-United-States-of-America/Software-Engineering-Co-Op_R-098277) |
| Wex ✓ | Software Engineering Intern - Enterprise Data & Systems (Salesforce & Snowflake) (Graduate/Master's) 🏠 | Data & ML/AI | US - Remote | Sep 24, 2026 | [Apply](https://wexinc.wd5.myworkdayjobs.com/WEXInc/job/US---Remote/Software-Engineering-Intern---Enterprise-Data---Systems--Salesforce---Snowflake---Graduate-Master-s-_R22543) |
| EQT Corporation | Water Infrastructure Engineering Intern | Software | Canonsburg, PA | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/eqtcorporation/jobs/5424757008) |
| Michael Baker International ✓ | Mechanical Engineering Intern | Hardware | Salt Lake City, UT, United States | Sep 24, 2026 | [Apply](https://ebxs.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/309936) |
| Cummins ✓ | Thermal and Fluid Sciences Engineering Co-Op Positions | Hardware | Columbus, IN, United States | Sep 24, 2026 | [Apply](https://fa-espx-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2437752) |
| GM financial | Intern - Data Engineer | Data & ML/AI | Arlington, TX, United States | Sep 24, 2026 | [Apply](https://fa-exvu-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/260821) |
| ZOLL Medical Corporation | Manufacturing Engineering Co-op | Hardware | Pawtucket, RI | Sep 24, 2026 | [Apply](https://zoll.wd5.myworkdayjobs.com/ZOLLMedicalCorp/job/Pawtucket-RI/Manufacturing-Engineering-Co-op_R20084) |
| Wurl | Data Science Intern 🏠 | Data & ML/AI | Remote - United States | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/wurljobs/jobs/4716249006) |
| Ramp ✓ | Software Engineer Internship, Frontend | Software | New York, NY (HQ) | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/ramp/a13ae586-f4cb-4385-8822-c42b9b54ed74) |
| Ramp ✓ | Software Engineering Intern, iOS | Software | New York, NY (HQ) | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/ramp/b66be397-240b-41a6-9b05-493299b270a9) |
| Ramp ✓ | Software Engineering Intern, Android | Software | New York, NY (HQ) | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/ramp/fcf118cc-521a-4a62-9d13-945e5b6e3cb8) |
| ZipRecruiter ✓ | Software Engineer - Intern | Software | Santa Monica, CA | Sep 23, 2026 | [Apply](https://job-boards.greenhouse.io/ziprecruiter/jobs/8180455) |
| Hypertherm | Firmware Developer - Internship | Hardware | Hanover, NH | Sep 23, 2026 | [Apply](https://hypertherm.wd503.myworkdayjobs.com/hypertherm-careers/job/Hanover-NH/Intern_R4100) |
| AECOM ✓ | Structural Engineering Intern - Hiring Event with AECOM - Philadelphia | Hardware | Philadelphia, PA, United States | Sep 23, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000151439229) |
| ZOLL Medical Corporation | Manufacturing Engineering Co-Op | Hardware | Chelmsford, MA | Sep 23, 2026 | [Apply](https://zoll.wd5.myworkdayjobs.com/ZOLLMedicalCorp/job/Chelmsford-MA/Manufacturing-Engineering-Co-Op_R20300) |
| Keenfinity | Software Test Automation Co-Op | Software | Fairport, NY, United States | Sep 23, 2026 | [Apply](https://jobs.smartrecruiters.com/Keenfinity/744000151395769) |
| Amgen ✓ | Undergrad Co-op – MCS Manufacturing Associate | Hardware | US - California - Thousand Oaks | Sep 23, 2026 | [Apply](https://amgen.wd1.myworkdayjobs.com/careers/job/US---California---Thousand-Oaks/Undergrad-Co-op---MCS-Manufacturing-Associate_R-256774) |
| SWBC | Application Security Intern | Security | San Antonio, TX | Sep 23, 2026 | [Apply](https://swbc.wd1.myworkdayjobs.com/swbccareers/job/San-Antonio-TX/Application-Security-Intern_R0015572-2) |
| Haigroup | Software Development Intern | Software | Cheshire, CT | Sep 22, 2026 | [Apply](https://job-boards.greenhouse.io/haigroup/jobs/4409386009) |
| Vantor | AI Engineer Intern 🇺🇸 🏠 | Data & ML/AI | Remote (United States) | Sep 22, 2026 | [Apply](https://maxar.wd1.myworkdayjobs.com/Vantor/job/Remote-United-States/AI-Engineer-Intern_R24605) |
| EMC Insurance | Intern - Software Engineering | Software | Iowa | Sep 22, 2026 | [Apply](https://emcins.wd5.myworkdayjobs.com/EMC_Careers/job/Iowa/Intern---Software-Engineering_R6557-1) |
| Moog | Intern, Mechanical Analysis Engineering | Hardware | Buffalo, NY | Sep 22, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Mechanical-Analysis-Engineering_R-26-20226) |
| Nightwing Intelligence Solutions | Mechanical Engineer Intern 🇺🇸 | Hardware | Springfield, VA | Sep 22, 2026 | [Apply](https://nwis.wd12.myworkdayjobs.com/NW/job/Springfield-VA/Mechanical-Engineer-Intern_JR102089-1) |
| Tencent ✓ | Site Reliability Engineer (SRE) Intern — AI Infrastructure | Data & ML/AI | US-California-Palo Alto | Sep 22, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/Site-Reliability-Engineer--SRE--Intern---AI-Infrastructure_R108158-1) |
| GuideStone | Summer Intern - Software Developer 🛂 | Software | Dallas, TX | Sep 22, 2026 | [Apply](https://guidestone.wd1.myworkdayjobs.com/guidestone/job/Dallas-TX/Summer-Intern---Software-Developer_R2129) |
| Gorbel | Mechanical Engineering Co-Op | Hardware | USA, New York, Henrietta | Sep 21, 2026 | [Apply](https://gorbel.wd501.myworkdayjobs.com/gorbelcareers/job/USA-New-York-Henrietta/Mechanical-Engineering-Co-Op_REQ-2026-2283-1) |
| Gorbel | Mechanical Engineering Co-Op | Hardware | USA, New York, Victor | Sep 21, 2026 | [Apply](https://gorbel.wd501.myworkdayjobs.com/gorbelcareers/job/USA-New-York-Victor/Mechanical-Engineering-Co-Op_REQ-2026-2284-1) |
| SingleStore ✓ | MIT- Software Engineer Intern / Engine | Software | United States | Sep 21, 2026 | [Apply](https://job-boards.greenhouse.io/singlestore/jobs/8220919) |
| SingleStore ✓ | MIT- Software Engineer Intern / Helios | Software | United States | Sep 21, 2026 | [Apply](https://job-boards.greenhouse.io/singlestore/jobs/8220941) |
| Viking Global ✓ | Data Science Intern | Data & ML/AI | New York, NY | Sep 21, 2026 | [Apply](https://job-boards.greenhouse.io/vikingglobalinvestors/jobs/6202755004) |
| Cambridge Investment Research | IT Operations Intern - Service Desk, Infrastructure, Prod Support | Software | Fairfield, IA | Sep 21, 2026 | [Apply](https://cir.wd108.myworkdayjobs.com/CIR_External_Career_Site/job/Fairfield-IA/IT-Operations-Intern---Service-Desk--Infrastructure--Prod-Support_R-2025-235) |
| LivaNova ✓ | Manufacturing Engineer Intern | Hardware | Arvada, Colorado, US | Sep 21, 2026 | [Apply](https://livanova.wd5.myworkdayjobs.com/search/job/Arvada-Colorado-US/Manufacturing-Engineer-Intern_JR-14827) |
| Collinear AI | MTS - Research Scientist Internship | Data & ML/AI | Sunnyvale, California | Sep 21, 2026 | [Apply](https://jobs.ashbyhq.com/collinear-ai/ae85fd08-dfd8-42e5-9b3b-9921ba24742b) |
| Flagship Pioneering | Metaphore: Data Science Co-Op | Data & ML/AI | Cambridge, MA USA | Sep 21, 2026 | [Apply](https://job-boards.greenhouse.io/fspco-op012325/jobs/8796563002) |
| Gordon Food Service ✓ | Imports & Commodities - Data Analyst Internship | Data & ML/AI | Wyoming, Michigan | Sep 21, 2026 | [Apply](https://gfs.wd5.myworkdayjobs.com/usjobs-gen-gfs/job/Wyoming-Michigan/Imports---Commodities---Data-Analyst-Internship_R-57384) |
| CWAN | Product Management Intern | Software | Office - New York | Sep 19, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Product-Management-Intern_R12287) |
| CWAN | Product Management Intern | Software | Office - New York | Sep 19, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Product-Management-Intern_R12288) |
| CWAN | Product Management Intern | Software | Office - New York | Sep 18, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Product-Management-Intern_R12285) |
| Acron Aviation | Software Engineer Intern - St. Pete Site | Software | St Petersburg, FL | Sep 18, 2026 | [Apply](https://jobs.lever.co/acronaviation/19dbac7d-b4fb-4d21-9247-dc610bf55fed) |
| Cambridge Investment Research | Consulting Services AI & Automation Intern | Data & ML/AI | Fairfield, IA | Sep 18, 2026 | [Apply](https://cir.wd108.myworkdayjobs.com/CIR_External_Career_Site/job/Fairfield-IA/Consulting-Services-AI---Automation-Intern_R-2025-223) |
| Gordon Food Service ✓ | Industrial / Mechanical / Electrical Engineer Internship | Hardware | Wyoming, Michigan | Sep 18, 2026 | [Apply](https://gfs.wd5.myworkdayjobs.com/usjobs-gen-gfs/job/Wyoming-Michigan/Industrial---Mechanical---Electrical-Engineer-Internship_R-57373) |
| Niagara Bottling ✓ | Manufacturing Intern - Milesburg | Hardware | Milesburg - Milesburg, PA | Sep 18, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Milesburg---Milesburg-PA/Manufacturing-Intern---Milesburg_R56065) |
| Nokia ✓ | AI Assisted Software Development Co-op | Data & ML/AI | United States | Sep 18, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/40535) |
| Analytical Mechanics Associates | Mechanical Engineering Intern 🇺🇸 | Hardware | Hampton, VA | Sep 18, 2026 | [Apply](https://amainc.wd12.myworkdayjobs.com/ama_careers/job/Hampton-VA/Mechanical-Engineering-Intern_R-100764) |
| GreatAmerica Financial Services | Platform Engineering Intern | Software | Cedar Rapids, IA | Sep 18, 2026 | [Apply](https://greatamerica.wd12.myworkdayjobs.com/greatamericacareers/job/Cedar-Rapids-IA/Platform-Engineering-Intern_JR1240-1) |
| Astera Labs ✓ | Firmware Engineer Intern (Leo) | Hardware | San Jose, CA | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/asteraearlycareer2027/jobs/4731584005) |
| IEX | Data Engineer Intern | Data & ML/AI | New York | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/iex-interns/jobs/8210998) |
| Ninjaholdings | Data Science Intern | Data & ML/AI | Chicago, IL | Sep 17, 2026 | [Apply](https://ninjaholdings.breezy.hr/p/85be8c78a2ba-data-science-intern) |
| Church & Dwight | AI Developer Co-op - Graduate Program (9 Months) 🇺🇸 | Data & ML/AI | USA, Ewing, NJ | Sep 17, 2026 | [Apply](https://churchdwight.wd1.myworkdayjobs.com/chdcareers/job/USA-Ewing-NJ/AI-Developer-Co-op---Graduate-Program--9-Months-_R2026-15686) |
| XPENG Motors | AI Research Intern – Predictive World Model | Data & ML/AI | Santa Clara, CA | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/xpengmotors/jobs/8819001002) |
| IDEX | Manufacturing Engineering Co-Op | Hardware | Cedar Falls, Iowa | Sep 17, 2026 | [Apply](https://idexcorp.wd5.myworkdayjobs.com/idex_careers/job/Cedar-Falls-Iowa/Manufacturing-Engineering-Co-Op_R-09910) |
| LabCorp | Intern – Network Infrastructure & Automation Engineering 🛂 | Software | Durham NC | Sep 17, 2026 | [Apply](https://labcorp.wd1.myworkdayjobs.com/external/job/Durham-NC/Intern---Network-Infrastructure---Automation-Engineering_2632795) |
| SharkNinja ✓ | Mechanical Engineering Co-op Opportunities | Hardware | Needham, MA, United States | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4713783006) |
| SharkNinja ✓ | Applied AI & Analytics Co-op Opportunities | Data & ML/AI | Miami +8 more | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4713793006) |
| SharkNinja ✓ | Applied AI & Analytics Intern Opportunities | Data & ML/AI | Miami +5 more | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4713808006) |
| American Electric Power ✓ | Civil/Structural Designer Intern - New Albany, OH | Hardware | New Albany, OH | Sep 17, 2026 | [Apply](https://aep.wd1.myworkdayjobs.com/AEPCareerSite/job/New-Albany-OH/Civil-Structural-Designer-Intern---New-Albany--OH_R19383) |
| American Electric Power ✓ | Civil/Structural Designer Intern - Roanoke, VA | Hardware | Roanoke, VA | Sep 17, 2026 | [Apply](https://aep.wd1.myworkdayjobs.com/AEPCareerSite/job/Roanoke-VA/Civil-Structural-Designer-Intern---Roanoke--VA_R19382) |
| Amperesand | Software Intern, Factory & Ops | Software | Reno, Nevada, United States | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/amperesand/jobs/4409254009) |
| Legrand | Mechanical Engineering Co-op | Hardware | West Hartford, CT, United States | Sep 16, 2026 | [Apply](https://iadugs.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/841) |
| Acron Aviation | Manufacturing Engineer Intern - Grand Rapids Site | Hardware | Grand Rapids, MI | Sep 16, 2026 | [Apply](https://jobs.lever.co/acronaviation/2893b51b-c93c-4875-9912-1292ab0f4926) |
| Kitware | AI Research Internship 🇺🇸 | Data & ML/AI | Clifton Park, New York | Sep 16, 2026 | [Apply](https://jobs.lever.co/kitware/ff25a349-a362-45d2-b1e4-2487c1df4f75) |
| Graco | Software Engineer Intern 🛂 | Software | Dayton, Minnesota, USA (French Lake) | Sep 16, 2026 | [Apply](https://graco.wd501.myworkdayjobs.com/Graco_Careers/job/Dayton-Minnesota-USA-French-Lake/Software-Engineer-Intern_R0023556) |
| KBR ✓ | Image Processing Software Engineer Intern | Software | Sioux Falls, South Dakota | Sep 16, 2026 | [Apply](https://kbr.wd5.myworkdayjobs.com/KBR_Careers/job/Sioux-Falls-South-Dakota/Image-Processing-Software-Engineer-Intern_R2130067) |
| Rockwell Automation ✓ | Intern, Product Management 🛂 | Software | Mequon, Wisconsin, United States | Sep 16, 2026 | [Apply](https://rockwellautomation.wd1.myworkdayjobs.com/External_Rockwell_Automation/job/Mequon-Wisconsin-United-States/Intern--Product-Management_R26-6971-1) |
| Terex | Manufacturing Engineer Intern | Hardware | US-SD Watertown | Sep 16, 2026 | [Apply](https://terex.wd1.myworkdayjobs.com/terexcareers/job/US-SD-Watertown/Manufacturing-Engineer-Intern_REQ-14323) |
| Clockwork Systems | Software Engineer Intern | Software | Palo Alto, CA | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/clockworksystems/jobs/6174230004) |
| Thermo Fisher Scientific ✓ | Manufacturing Engineering Co-op | Hardware | Marietta, Ohio, USA | Sep 16, 2026 | [Apply](https://thermofisher.wd5.myworkdayjobs.com/ThermoFisherCareers/job/Marietta-Ohio-USA/Manufacturing-Engineering-Co-op_R-01366628) |
| Vermeer | IT Data Engineer Intern | Data & ML/AI | Pella, Iowa, USA - Corporate Office | Sep 16, 2026 | [Apply](https://vermeer.wd5.myworkdayjobs.com/externalcareersite/job/Pella-Iowa-USA---Corporate-Office/IT-Data-Engineer-Intern_REQ-22171) |
| Sonoco | Manufacturing Internship | Hardware | Hartselle, AL, USA | Sep 16, 2026 | [Apply](https://sonoco.wd1.myworkdayjobs.com/CorporateCareers/job/Hartselle-AL-USA/Manufacturing-Internship_JR-159794) |
| Sonoco | Mechanical Internship | Hardware | Hartselle, AL, USA | Sep 16, 2026 | [Apply](https://sonoco.wd1.myworkdayjobs.com/CorporateCareers/job/Hartselle-AL-USA/Mechanical-Internship_JR-159771) |
| Sonoco | Manufacturing Internship | Hardware | Jefferson, TX, USA | Sep 16, 2026 | [Apply](https://sonoco.wd1.myworkdayjobs.com/CorporateCareers/job/Jefferson-TX-USA/Manufacturing-Internship_JR-159774) |
| Internrecruiting | Software Engineer Co-op | Software | Boston, MA | Sep 15, 2026 | [Apply](https://job-boards.greenhouse.io/internrecruiting/jobs/8204511) |
| Brevium | Software Engineer Intern | Software | American Fork, UT | Sep 15, 2026 | [Apply](https://job-boards.greenhouse.io/brevium/jobs/4713683006) |
| PerkinElmer | Data Science Intern, Asset Intelligence 🏠 | Data & ML/AI | US Remote - NY | Sep 15, 2026 | [Apply](https://newperkinelmer.wd1.myworkdayjobs.com/External/job/US-Remote---NY/Data-Science-Intern--Asset-Intelligence_REQ-058421) |
| Ensign-Bickford Aerospace & Defense Company | Electronics Manufacturing Engineer Intern | Hardware | Simsbury, CT | Sep 15, 2026 | [Apply](https://ebi.wd5.myworkdayjobs.com/ebadcareers/job/Simsbury-CT/Electronics-Manufacturing-Engineer-Intern_REQ107696-1) |
| Interco | Paid Internship -- Software Development -- React 🛂 | Software | St. Louis, MO, United States | Sep 15, 2026 | [Apply](https://jobs.smartrecruiters.com/Interco/744000149591449) |
| BorgWarner | Mechanical Engineering Co-op – Engine Solenoids | Hardware | Auburn Hills - Michigan - USA | Sep 15, 2026 | [Apply](https://borgwarner.wd5.myworkdayjobs.com/BorgWarner_Careers/job/Auburn-Hills---Michigan---USA/Mechanical-Engineering-Co-op---Engine-Solenoids_R2026-3583) |
| DigiKey | Industrial Engineering Intern 🛂 | Hardware | Thief River Falls, MN | Sep 15, 2026 | [Apply](https://digikey.wd5.myworkdayjobs.com/digi-key/job/Thief-River-Falls-MN/Industrial-Engineering-Intern_R5775) |
| CSC Generation | Software Engineer - Legacy Applications & Modernization - Intern/Part Time | Software | Houston, TX | Sep 14, 2026 | [Apply](https://jobs.lever.co/cscgeneration-2/3a04b45f-a2eb-438a-a8ac-b07324223813) |
| Tihinsurance | Internship - Software Engineering | Software | Dallas TX - 12377 Merit Dr. | Sep 14, 2026 | [Apply](https://tihinsurance.wd1.myworkdayjobs.com/crc_careers/job/Dallas-TX---12377-Merit-Dr/Internship---Software-Engineering_R0000003172) |
| Tencent ✓ | Machine Learning Intern | Data & ML/AI | US-California-Palo Alto | Sep 14, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/Machine-Learning-Intern_R108140-1) |
| LabCorp | Intern - Mechanical Engineer 🛂 | Hardware | Bloomfield CT | Sep 14, 2026 | [Apply](https://labcorp.wd1.myworkdayjobs.com/external/job/Bloomfield-CT/Intern---Mechanical-Engineer_2632739-1) |
| RESPEC | Student Engineering Intern (Structural) | Hardware | Sioux Falls, SD, United States | Sep 14, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000149447560) |
| LabCorp | Intern - Software Developer 🛂 | Software | Durham NC | Sep 14, 2026 | [Apply](https://labcorp.wd1.myworkdayjobs.com/external/job/Durham-NC/Intern---Software-Developer_2632330) |
| Wex ✓ | AI & Data Platform Engineering Intern (Undergraduate) 🏠 | Data & ML/AI | US - Remote | Sep 14, 2026 | [Apply](https://wexinc.wd5.myworkdayjobs.com/WEXInc/job/US---Remote/AI---Data-Platform-Engineering-Intern--Undergraduate-_R23055) |
| Wex ✓ | Data & AI Intern (Graduate/Master’s) 🏠 | Data & ML/AI | US - Remote | Sep 14, 2026 | [Apply](https://wexinc.wd5.myworkdayjobs.com/WEXInc/job/US---Remote/Data---AI-Intern--Graduate-Master-s-_R22551) |
| Base Power | Quantitative Developer Intern | Quant | Austin, TX | Sep 14, 2026 | [Apply](https://jobs.ashbyhq.com/base-power/b6b2332e-1226-4575-b2c9-9e5258f2540e) |
| RESPEC | Student Structural BIM Technician Intern (Rapid City) | Hardware | Rapid City, SD, United States | Sep 14, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000149419399) |
| RESPEC | Student Structural BIM Technician Intern (Denver, Loveland, & Sioux Falls) | Hardware | Denver, CO, United States | Sep 14, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000149420667) |
| Tencent ✓ | Cyber Security Engineer Intern | Security | US-California-Palo Alto | Sep 14, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/Cyber-Security-Engineer-Intern_R108141-2) |
| Base Power | Software Engineering Intern | Software | Austin, TX | Sep 14, 2026 | [Apply](https://jobs.ashbyhq.com/base-power/5353ea33-57d4-46fa-9a96-e392a3f841bc) |
| Flagship Pioneering | Flagship Pioneering: AI Automation Engineering Co-Op | Data & ML/AI | Cambridge, MA USA | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/fspco-op012325/jobs/8796996002) |
| Lexington Medical | Mechanical Engineering Co-Op | Hardware | Bedford, MA | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/lexingtonmedical/jobs/5423105008) |
| Viavi Solutions ✓ | Software Engineering Co-Op | Software | Germantown, MD USA | Sep 14, 2026 | [Apply](https://viavisolutions.wd1.myworkdayjobs.com/careers/job/Germantown-MD-USA/Software-Engineering-Co-Op_260005140-1) |
| Autostore | Co-Op/Intern - Mechanical Engineer | Hardware | Atlanta, GA, USA | Sep 13, 2026 | [Apply](https://autostore.wd3.myworkdayjobs.com/autostore/job/Atlanta-GA-USA/Co-Op---Mechanical-Engineer_JR102694) |
| Autostore | Co-Op/Intern - Software Engineering | Software | Atlanta, GA, USA | Sep 13, 2026 | [Apply](https://autostore.wd3.myworkdayjobs.com/autostore/job/Atlanta-GA-USA/Co-Op---Software-Engineering_JR102692) |
| Fortune Brands | Product Management Intern, B2B Security | Security | Deerfield, ILLINOIS, United States | Sep 11, 2026 | [Apply](https://jobs.smartrecruiters.com/FortuneBrands/744000149058098) |
| NewsBreak | Nearby AI Internship Program - Engineering Track | Data & ML/AI | Mountain View, California, United States | Sep 11, 2026 | [Apply](https://job-boards.greenhouse.io/newsbreak/jobs/4712896006) |
| Businessolver | Business Intelligence Analyst Internship (Innovation & Data Science) | Data & ML/AI | United States | Sep 11, 2026 | [Apply](https://job-boards.greenhouse.io/businessolverinvitationonly/jobs/8189738) |
| Corteva ✓ | Agentic AI Engineer Intern | Data & ML/AI | Indianapolis, Indiana, United States | Sep 11, 2026 | [Apply](https://corteva.wd5.myworkdayjobs.com/corteva/job/Indianapolis-Indiana-United-States/Agentic-AI-Engineer-Intern_248210W) |
| Corteva ✓ | Data Science Summer Intern | Data & ML/AI | Indianapolis, Indiana, United States | Sep 11, 2026 | [Apply](https://corteva.wd5.myworkdayjobs.com/corteva/job/Indianapolis-Indiana-United-States/Data-Science-Summer-Intern_248208W) |
| Graco | Manufacturing Engineering Intern 🛂 | Hardware | Erie, Pennsylvania, USA | Sep 11, 2026 | [Apply](https://graco.wd501.myworkdayjobs.com/Graco_Careers/job/Erie-Pennsylvania-USA/Manufacturing-Engineering-Intern_R0023592) |
| Thermo Fisher Scientific ✓ | Industrial Engineering Co-op | Hardware | Rochester, New York, USA | Sep 11, 2026 | [Apply](https://thermofisher.wd5.myworkdayjobs.com/ThermoFisherCareers/job/Rochester-New-York-USA/Industrial-Engineering-Co-op_R-01366625) |
| Thermo Fisher Scientific ✓ | Mechanical Engineering Co-op | Hardware | Rochester, New York, USA | Sep 11, 2026 | [Apply](https://thermofisher.wd5.myworkdayjobs.com/ThermoFisherCareers/job/Rochester-New-York-USA/Mechanical-Engineering-Co-op_R-01366623) |
| Crowe ✓ | MSFT AI Business Solutions Technical Intern | Data & ML/AI | Chicago IL USA | Sep 11, 2026 | [Apply](https://crowe.wd12.myworkdayjobs.com/external_careers/job/Chicago-IL-USA/D365-ERP-Technical-Intern_R-71039) |
| DigiKey | Product Management & Supplier Development Intern 🛂 | Software | Thief River Falls, MN | Sep 11, 2026 | [Apply](https://digikey.wd5.myworkdayjobs.com/digi-key/job/Thief-River-Falls-MN/Product-Management---Supplier-Development-Intern_R5829) |
| Direct Supply ✓ | AI Engineer Intern | Data & ML/AI | Milwaukee, WI | Sep 11, 2026 | [Apply](https://directsupply.wd501.myworkdayjobs.com/direct-supply-careers/job/Milwaukee-WI/AI-Engineer-Intern_REQ-2026-2553) |
| Moog | Intern, Mechanical Manufacturing Engineering | Hardware | Blacksburg, VA | Sep 11, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Blacksburg-VA/Intern--Mechanical-Manufacturing-Engineering_R-26-19925) |
| Bracco | Software Engineering Intern | Software | USA, Eden Prairie, Minnesota, 55344 | Sep 10, 2026 | [Apply](https://bracco.wd103.myworkdayjobs.com/braccocareers/job/USA-Eden-Prairie-Minnesota-55344/Software-Engineering-Intern_JR100328) |
| VAST | Emerging Talent - Mechanical/Aerospace Engineering Internship 🇺🇸 | Hardware | Long Beach, California, United States | Sep 10, 2026 | [Apply](https://boards.greenhouse.io/vast/jobs/4711400006?gh_jid=4711400006) |
| VAST | Emerging Talent - Manufacturing Engineering Internship 🇺🇸 | Hardware | Long Beach, California, United States | Sep 10, 2026 | [Apply](https://boards.greenhouse.io/vast/jobs/4711403006?gh_jid=4711403006) |
| Magna International | Intern - Engineering Software | Software | Southfield, Michigan, US | Sep 10, 2026 | [Apply](https://magna.wd3.myworkdayjobs.com/Magna/job/Southfield-Michigan-US/Intern---Engineering-Software_R00260232) |
| Niagara Bottling ✓ | Manufacturing Internship - Plainfield | Hardware | Plainfield - Plainfield, IN | Sep 10, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Plainfield---Plainfield-IN/Manufacturing-Internship---Plainfield_R56553) |
| Booz Allen ✓ | Enterprise Cybersecurity Data Loss Prevention Intern 🇺🇸 | Data & ML/AI | McLean, VA | Sep 10, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/McLean-VA/Enterprise-Cybersecurity-Data-Loss-Prevention-Intern_R0249131-1) |
| RTX | Co-Op, Software Engineer- Onsite 🇺🇸 | Software | US-IA-CEDAR RAPIDS-109 ~ 400 Collins Rd… | Sep 10, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-109--400-Collins-Rd-NE--BLDG-109/Co-Op--Software-Engineer--Onsite_01871298) |
| Polar Semiconductor | Industrial Engineering Intern | Hardware | Bloomington, MN, USA | Sep 10, 2026 | [Apply](https://polarsemi.wd501.myworkdayjobs.com/Polar/job/Bloomington-MN-USA/Industrial-Engineering-Intern_R3772) |
| Polar Semiconductor | Manufacturing Planning Intern | Hardware | Bloomington, MN, USA | Sep 10, 2026 | [Apply](https://polarsemi.wd501.myworkdayjobs.com/Polar/job/Bloomington-MN-USA/Manufacturing-Planning-Intern_R3785) |
| Cleveland-Cliffs ✓ | Manufacturing Planning Intern | Hardware | Indiana Harbor | Sep 10, 2026 | [Apply](https://aksteel.wd1.myworkdayjobs.com/careers/job/Indiana-Harbor/Manufacturing-Planning-Intern_R13519) |
| Astera Labs ✓ | Data Analyst Intern | Data & ML/AI | San Jose, CA | Sep 09, 2026 | [Apply](https://job-boards.greenhouse.io/asteraearlycareer2027/jobs/4731996005) |
| Ninjaholdings | Data Engineer Intern | Data & ML/AI | Chicago, IL | Sep 09, 2026 | [Apply](https://ninjaholdings.breezy.hr/p/12b3ed96c30c-data-engineer-intern) |
| Ninjaholdings | Software Engineer Intern | Software | Chicago, IL | Sep 09, 2026 | [Apply](https://ninjaholdings.breezy.hr/p/23a015fea536-software-engineer-intern) |
| Hypertherm | Mechanical Engineering Winter/Spring Co-Op - Central Engineering (NH) | Hardware | Hanover, NH | Sep 09, 2026 | [Apply](https://hypertherm.wd503.myworkdayjobs.com/hypertherm-careers/job/Hanover-NH/Mechanical-Engineering-Winter-Spring-Internship-or-Co-Op---Central-Engineering--NH-_R4060) |
| Hypertherm | Mechanical Engineering Winter/Spring Co-Op - Central Engineering (WA) | Hardware | Kent, WA | Sep 09, 2026 | [Apply](https://hypertherm.wd503.myworkdayjobs.com/hypertherm-careers/job/Kent-WA/Mechanical-Engineering-Winter-Spring-Internship-or-Co-Op---Central-Engineering--WA-_R4061) |
| Sequence Holdings | Software Engineer (Intern) | Software | New York City | Sep 09, 2026 | [Apply](https://jobs.ashbyhq.com/seqholdings/9dc9a7f3-198a-43c0-be75-a3aba228bf2c) |
| Amperesand | Product Software Intern | Software | Reno +5 more | Sep 09, 2026 | [Apply](https://job-boards.greenhouse.io/amperesand/jobs/4381214009) |
| AECOM ✓ | Structural Engineering Intern 🇺🇸 | Hardware | Pittsburgh, PA, United States | Sep 09, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000148614879) |
| Booz Allen ✓ | Enterprise Cybersecurity Education and Execution Intern 🇺🇸 | Security | McLean, VA | Sep 09, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/McLean-VA/Enterprise-Cybersecurity-Education-and-Execution-Intern_R0249071) |
| Internship | AI Labs Intern | Data & ML/AI | New York | Sep 09, 2026 | [Apply](https://jobs.ashbyhq.com/interplay/bdf67758-1f20-4a01-8bb3-ccebfa79e9ac) |
| Crest Industries | Developer Intern | Software | Pineville, Louisiana | Sep 09, 2026 | [Apply](https://jobs.lever.co/crestoperations/e012721c-e731-483d-a4e3-1a240c48bfbd) |
| IDEX | Mechanical Engineer-Intern | Hardware | Oklahoma City, Oklahoma | Sep 09, 2026 | [Apply](https://idexcorp.wd5.myworkdayjobs.com/idex_careers/job/Oklahoma-City-Oklahoma/Mechanical-Engineer-Intern_R-09824-1) |
| Astera Labs ✓ | Firmware Engineer Intern (SCO1) | Hardware | San Jose, CA | Sep 08, 2026 | [Apply](https://job-boards.greenhouse.io/asteraearlycareer2027/jobs/4731585005) |
| Syntiant | Machine Learning Intern - KWS/AED | Data & ML/AI | Redwood City, California, United States | Sep 08, 2026 | [Apply](https://apply.workable.com/syntiant/j/113F994B7B/) |
| ConductorAI | Software Engineer Intern 🇺🇸 | Software | New York City | Sep 08, 2026 | [Apply](https://jobs.ashbyhq.com/conductorai/d6a1b110-10ad-4b5e-83a0-88c5fd7bc891) |
| Coretek Services | AI & Automation Development Intern | Data & ML/AI | Farmington Hills +2 more | Sep 08, 2026 | [Apply](https://apply.workable.com/coretek-services/j/8D69C6C871/) |
| Buildertrend | Software Engineering Intern | Software | Omaha, NE | Sep 08, 2026 | [Apply](https://buildertrend.wd108.myworkdayjobs.com/External_Careers/job/Omaha-NE/Software-Engineering-Inter_JR-000467) |
| Eudia | AI Engineer Intern | Data & ML/AI | Palo Alto, CA | Sep 08, 2026 | [Apply](https://job-boards.greenhouse.io/eudia/jobs/4020078009) |
| Syska Hennessy Group | Mechanical Engineer Summer Intern | Hardware | Jacksonville, FL | Sep 08, 2026 | [Apply](https://job-boards.greenhouse.io/syskahennessy/jobs/8178051) |
| The Boeing Company ✓ | Boeing Engineering & Technology Innovation Graduate Researcher Program, Computational Fluid Dynamics (CFD) Intern 🇺🇸 | Hardware | USA - Hazelwood, MO | Sep 08, 2026 | [Apply](https://boeing.wd1.myworkdayjobs.com/EXTERNAL_CAREERS/job/USA---Hazelwood-MO/Boeing-Engineering---Technology-Innovation-Graduate-Researcher-Program--Computational-Fluid-Dynamics--CFD--Intern_JR2026523768) |
| The Boeing Company ✓ | Boeing Engineering & Technology Innovation, Graduate Researcher Program –  Computational Fluid Dynamics Intern 🇺🇸 | Hardware | USA - Huntington Beach, CA | Sep 08, 2026 | [Apply](https://boeing.wd1.myworkdayjobs.com/EXTERNAL_CAREERS/job/USA---Huntington-Beach-CA/Boeing-Engineering---Technology-Innovation--Graduate-Researcher-Program----Computational-Fluid-Dynamics-Intern_JR2026523774) |
| The Boeing Company ✓ | Boeing Engineering & Technology Innovation Graduate Researcher Program, Software Engineering Artificial Intelligence Intern 🇺🇸 | Data & ML/AI | USA - Tukwila, WA | Sep 08, 2026 | [Apply](https://boeing.wd1.myworkdayjobs.com/EXTERNAL_CAREERS/job/USA---Tukwila-WA/Boeing-Engineering---Technology-Innovation-Graduate-Researcher-Program--Software-Engineering-Artificial-Intelligence-Intern_JR2026523687) |
| TRUMPF | Smart Factory Robotics & Operations Intern | Hardware | Chicago, IL | Sep 08, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Chicago-IL/Smart-Factory-Robotics---Operations-Intern_R00042570) |
| Flagship Pioneering | Pioneering Intelligence: Data Science Co-Op (Embedded Science Team) | Data & ML/AI | Cambridge, MA USA | Sep 08, 2026 | [Apply](https://job-boards.greenhouse.io/fspco-op012325/jobs/8783960002) |
| M3USA | AI Engineering Intern (Remote) 🏠 | Data & ML/AI | Fort Washington +2 more | Sep 08, 2026 | [Apply](https://jobs.smartrecruiters.com/M3USA/744000148244649) |
| Matic | Robotics Customer Success Intern | Hardware | Menlo Park, CA | Sep 08, 2026 | [Apply](https://jobs.ashbyhq.com/maticrobots/a0d77cc5-555f-46d8-89b1-e1df201a77dc) |
| Gilead Sciences ✓ | Intern - PDM - Manufacturing (Biologics) | Hardware | United States - California - Foster City | Sep 08, 2026 | [Apply](https://gilead.wd1.myworkdayjobs.com/gileadcareers/job/United-States---California---Foster-City/Intern---PDM---Manufacturing--Biologics-_R0054750) |
| Harbinger Motors | Intern, Powertrain Manufacturing | Hardware | Garden Grove, CA | Sep 05, 2026 | [Apply](https://job-boards.greenhouse.io/harbingermotors/jobs/5231838007) |
| Harbinger Motors | Intern, Cybersecurity | Security | Garden Grove, CA | Sep 05, 2026 | [Apply](https://job-boards.greenhouse.io/harbingermotors/jobs/5231842007) |
| CNA Insurance | Technology Internship Program (Software Engineering) 🛂 | Software | Chicago, IL, USA | Sep 04, 2026 | [Apply](https://cna.wd1.myworkdayjobs.com/CNA_Careers/job/Chicago-IL-USA/Technology-Internship-Program--Software-Engineering-_R-8107) |
| Garner Health | Software Engineering Intern 🛂 | Software | New York City, New York | Sep 04, 2026 | [Apply](https://job-boards.greenhouse.io/garnerhealth/jobs/6164698004) |
| GenScript ✓ | mRNA Manufacturing Intern (Full Time) | Hardware | Redmond, Washington, United States | Sep 04, 2026 | [Apply](https://job-boards.greenhouse.io/genscript/jobs/5231601007) |
| Ingredion | AI & Data Scientist Intern | Data & ML/AI | Westchester, IL | Sep 04, 2026 | [Apply](https://ingredion.wd1.myworkdayjobs.com/IngredionCareers/job/Westchester-IL/AI---Data-Scientist-Intern_Req-40220) |
| Loram | Mechanical Engineering Intern | Hardware | Hamel, MN, United States | Sep 04, 2026 | [Apply](https://jobs.smartrecruiters.com/Loram1/3743990015079155) |
| Johnson Controls ✓ | Software/Controls Engineering Grad Intern (Fall Intern) | Software | Salem-Virginia-United States of America | Sep 04, 2026 | [Apply](https://jci.wd5.myworkdayjobs.com/JCI/job/Salem-Virginia-United-States-of-America/Software-Controls-Engineering-Grad-Intern_WD30278205-1) |
| NewsBreak | New Market Launch Intern (MBA), Nearby AI 🏠 | Data & ML/AI | Bellevue +9 more | Sep 03, 2026 | [Apply](https://job-boards.greenhouse.io/newsbreak/jobs/4711146006) |
| Premier ✓ | Data Science Intern | Data & ML/AI | Charlotte, NC | Sep 03, 2026 | [Apply](https://premierinc.wd1.myworkdayjobs.com/External_Professional/job/Charlotte-NC/Data-Science-Intern_R0008481) |
| Premier ✓ | Software Engineer Intern | Software | Charlotte, NC | Sep 03, 2026 | [Apply](https://premierinc.wd1.myworkdayjobs.com/External_Professional/job/Charlotte-NC/Software-Engineer-Intern_R0008480) |
| Winsupply ✓ | Data Analyst Intern | Data & ML/AI | Moraine, OH, United States | Sep 03, 2026 | [Apply](https://jobs.smartrecruiters.com/Winsupply1/3743990015046116) |
| IEX | Cyber Security Analyst Intern | Security | New York | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/iex-interns/jobs/8173713) |
| Dynamic Catholic | Internship - Front-End UX Intern 🛂 | Other | Erlanger, Kentucky | Sep 02, 2026 | [Apply](https://jobs.lever.co/dynamiccatholic/603f082e-07c8-4b1c-ac09-8963c51229ad) |
| Dynamic Catholic | Internship - Software Developer - Commerce Cloud | Software | Erlanger, Kentucky | Sep 02, 2026 | [Apply](https://jobs.lever.co/dynamiccatholic/e94fa581-892c-4958-9515-0221f862ce57) |
| Hadrian | Robotics Engineer Intern 🇺🇸 | Hardware | Los Angeles, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/hadrian-automation/02e33109-08c5-4db7-8881-67294c172584) |
| Hadrian | Software Engineer Intern 🇺🇸 | Software | Los Angeles, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/hadrian-automation/2b0423c6-947d-4226-8d23-90743bd5e63e) |
| Hadrian | Data Science/ Data Engineer Intern 🇺🇸 | Data & ML/AI | Los Angeles, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/hadrian-automation/f718bcfe-3f5b-4682-a294-697499caf813) |
| Reflect Orbital | Flight Software Engineering Intern | Software | Hawthorne, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/d2ad1427-89aa-404d-8678-7b8e6dace5e2) |
| Reflect Orbital | Embedded Firmware Engineering Intern | Hardware | Hawthorne, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/d5ade048-5555-4a77-b002-d117254b6e6b) |
| Intuitive Surgical ✓ | Mechanical Engineering Intern | Hardware | Sunnyvale, CA, United States | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/Intuitive/744000147091674) |
| Axcelis Technologies, Inc. ✓ | Manufacturing Test Development Engineer Co-op | Hardware | Beverly, MA | Sep 02, 2026 | [Apply](https://axcelis.wd1.myworkdayjobs.com/axcelis/job/Beverly-MA/Manufacturing-Test-Development-Engineer-Co-op_12010) |
| National Information Solutions Cooperative (NISC) | Intern - Software Development | Software | Cedar Rapids +3 more | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/nisc/jobs/8092699) |
| National Information Solutions Cooperative (NISC) | Intern - Software Development | Software | Cedar Rapids, IA | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/testnisc/jobs/8174088) |
| National Information Solutions Cooperative (NISC) | Intern - Software Development | Software | Lake Saint Louis, MO | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/testnisc/jobs/8174090) |
| Winsupply ✓ | Software Developer Intern | Software | Moraine, OH, United States | Sep 02, 2026 | [Apply](https://jobs.smartrecruiters.com/Winsupply1/3743990015014717) |
| IEX | Platform Engineer Intern | Software | New York | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/iex-interns/jobs/8171127) |
| Ingredion | AI & Data Scientist Intern | Data & ML/AI | Westchester, IL | Sep 01, 2026 | [Apply](https://ingredion.wd1.myworkdayjobs.com/IngredionCareers/job/Westchester-IL/AI---Data-Scientist-Intern_Req-40007-1) |
| Valon | Software Engineer Intern | Software | New York | Sep 01, 2026 | [Apply](https://jobs.ashbyhq.com/valon/b5a62c0c-823c-42dd-8cb5-e4b1455bcc64) |
| Eulerity | Backend Developer Intern | Software | New York, New York | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/eulerity/jobs/4709040006) |
| TRUMPF | CNC Programming Intern | Software | Farmington, CT | Sep 01, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Farmington-CT/CNC-Programming-Intern_R00042595) |
| TRUMPF | Industrial Engineering Internship | Hardware | Farmington, CT | Sep 01, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Farmington-CT/Industrial-Engineering-Internship_R00042497) |
| Olsson | Mechanical Engineering Internship - Healthcare Facilities | Hardware | Dallas, TX; Fort Worth, TX | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5394239008) |
| Olsson | Mechanical Engineering Internship - Healthcare Facilities | Hardware | Omaha, NE | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5394243008) |
| Niagara Bottling ✓ | Manufacturing Intern - Temple | Hardware | Temple - Temple, TX | Sep 01, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Temple---Temple-TX/Manufacturing-Intern---Temple_R56074) |
| Katalyst Space Technologies | Engineering Intern (Electrical / Mechanical / GNC / Software) 🇺🇸 | Hardware | Broomfield, Colorado, United States | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/katalyst/jobs/6176711004) |
| Stripe ✓ | Software Engineer, Intern (Summer or Winter) | Software | San Francisco, Seattle, New York City | Aug 31, 2026 | [Apply](https://stripe.com/jobs/search?gh_jid=8128745) |
| Integra FEC | (SPRING) Data Analyst Intern 🛂 | Data & ML/AI | Austin, Texas | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/integra/jobs/5406100008) |
| Integra FEC | (SUMMER) Data Analyst Intern 🛂 | Data & ML/AI | Austin, Texas | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/integra/jobs/5406109008) |
| Integra FEC | (SPRING) Data Analyst Intern 🛂 | Data & ML/AI | Austin, Texas | Aug 31, 2026 | [Apply](https://job-boards.greenhouse.io/integrainterns/jobs/5406101008) |
| Dairyland Power Cooperative | Intern, Energy Data Analyst | Data & ML/AI | La Crosse, Wisconsin | Aug 31, 2026 | [Apply](https://dairynet.wd1.myworkdayjobs.com/DPCcareers/job/La-Crosse-Wisconsin/Intern--Energy-Data-Analyst_JR101052) |
| IGS Energy | Software Engineer Intern 🛂 🏠 | Software | Ohio Remote | Aug 31, 2026 | [Apply](https://igsenergy.wd1.myworkdayjobs.com/IGS/job/Ohio-Remote/Software-Engineer-Intern_R6263) |
| Nike ✓ | NIKE, Inc. Artificial Intelligence, Data, & Machine Learning Engineering Undergraduate Internship | Data & ML/AI | Beaverton, Oregon | Aug 31, 2026 | [Apply](https://nike.wd1.myworkdayjobs.com/nke/job/Beaverton-Oregon/NIKE--Inc-Artificial-Intelligence--Data----Machine-Learning-Engineering-Undergraduate-Internship_R-91110) |
| Xaira Therapeutics | AI Scientist Intern, Computational Protein Design | Data & ML/AI | Seattle +5 more | Aug 28, 2026 | [Apply](https://job-boards.greenhouse.io/xairatherapeutics/jobs/5225658007) |
| Re:Build Manufacturing | Process & Mechanical Engineer Co-op/Intern | Hardware | Rochester, NY | Aug 28, 2026 | [Apply](https://job-boards.greenhouse.io/rebuildmanufacturing/jobs/4728423005) |
| Ambarella ✓ | Software Architecture Engineer Intern | Software | US Headquarters | Aug 27, 2026 | [Apply](https://ambarella.wd108.myworkdayjobs.com/ambarella/job/US-Headquarters/Software-Architecture-Engineer-Intern_JR100365) |
| Chemours | AI & Data Science Intern 🏠 | Data & ML/AI | US - Remote | Aug 26, 2026 | [Apply](https://chemours.wd103.myworkdayjobs.com/Chemours/job/US---Remote/AI---Data-Science-Intern_JR15013) |
| Monolithic Power Systems ✓ | AI Developer Intern | Data & ML/AI | San Jose - California | Aug 24, 2026 | [Apply](https://monolithicpower.wd12.myworkdayjobs.com/MPS_Careers/job/San-Jose---California/AI-Developer-Intern_R-1756) |
| Exa Labs | Software Engineer, Intern | Software | San Francisco, California | Aug 13, 2026 | [Apply](https://jobs.ashbyhq.com/exa/a9e01521-66f1-481b-89da-ec01d4620f16) |
| IDEXX ✓ | Security Operations (Cybersecurity) internship | Security | Westbrook, ME | Aug 03, 2026 | [Apply](https://idexx.wd1.myworkdayjobs.com/IDEXX/job/Westbrook-ME/Security-Operations--Cybersecurity--internship_J-053268) |
| Core & Main | Intern - AI Intern - Copilot-  Onsite - St. Louis | Data & ML/AI | Saint Louis, MO 63146 | Jul 24, 2026 | [Apply](https://coreandmain.wd1.myworkdayjobs.com/coreandmain/job/Saint-Louis-MO-63146/Intern---Data-Engineering----Corp_45804) |
| Pony.ai ✓ | Research Intern - Deep Learning | Data & ML/AI | Fremont, California, United States | Jul 22, 2026 | [Apply](https://apply.workable.com/pony-dot-ai/j/4C1F53EF5D/) |
| Pony.ai ✓ | Software Engineer Intern - Generalist | Software | Fremont, California, United States | Jul 22, 2026 | [Apply](https://apply.workable.com/pony-dot-ai/j/BA5FFDBC71/) |
| Copart ✓ | Software Engineering Intern | Software | Dallas, TX - Headquarters | Jul 15, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR109673) |
| Manhattan Associates ✓ | A.I. Developer Co-Op (Boston, MA) | Software | US - Home Office | Jul 10, 2026 | [Apply](https://manh.wd5.myworkdayjobs.com/campus/job/US---Home-Office/AI-Developer-Co-Op--Boston--MA-_16931) |

<a id="drop-radar"></a>

## 📅 Drop Radar — when companies usually post for Summer 2027

Stop refreshing career pages. 🎯 = the employer's **own posted date**, read from their careers API. (We may have discovered the role after it went live — the date is the employer's, not our discovery time.) The rest are typical opening **months**, hand-checked against each company's careers page and public recruiting guides. ✅ = already live in the list above.

> **Heads up:** companies trend *earlier* every cycle, and "~Aug" is a month, not a day. Treat "expected" as when to **start watching**, and "rolling" companies as worth checking year-round.

| Company | Typical opening | Expected this cycle | Status |
|---|---|---|---|
| Citadel | ~Aug | ~Aug · any day now | ⏳ waiting |
| Citadel Securities | ~Aug | ~Aug · any day now | ⏳ waiting |
| DRW | ~Aug | ~Aug · any day now | ⏳ waiting |
| Google | ~Aug | ~Aug · any day now | ⏳ waiting |
| Jane Street | ~Aug | ~Aug · any day now | ⏳ waiting |
| Meta | ~Aug | ~Aug · any day now | ⏳ waiting |
| Salesforce | ~Aug | ~Aug · any day now | ⏳ waiting |
| SIG | ~Aug | ~Aug · any day now | ⏳ waiting |
| Snowflake | ~Aug | ~Aug · any day now | ⏳ waiting |
| Uber | ~Aug | ~Aug · any day now | ⏳ waiting |
| Adobe | ~Sep | ~Sep · any day now | ⏳ waiting |
| Airbnb | ~Sep | ~Sep · any day now | ⏳ waiting |
| Bloomberg | ~Sep | ~Sep · any day now | ⏳ waiting |
| Plaid | ~Sep | ~Sep · any day now | ⏳ waiting |
| Point72 | ~Sep | ~Sep · any day now | ⏳ waiting |
| Stripe | ~Sep | ~Sep · any day now | ⏳ waiting |
| D.E. Shaw | ~Oct | ~Oct · any day now | ⏳ waiting |
| Ramp | ~Dec | ~Dec | ⏳ waiting |
| Two Sigma | ~Dec | ~Dec | ⏳ waiting |
| Apple | rolling | year-round | ⏳ waiting |
| Jump Trading | rolling | year-round | ⏳ waiting |
| Microsoft | rolling | year-round | ⏳ waiting |
| Millennium | rolling | year-round | ⏳ waiting |
| NVIDIA | rolling | year-round | ⏳ waiting |
| Palantir | rolling | year-round | ⏳ waiting |
| 🎯 Databricks | Aug 17 | dropped Aug 17 | ✅ [open now](https://databricks.com/company/careers/open-positions/job?gh_jid=6883068002) |
| 🎯 Perpay | Sep 12 | dropped Sep 12 | ✅ [open now](https://job-boards.greenhouse.io/perpay/jobs/4076978007) |
| 🎯 Glean | Sep 03 | dropped Sep 03 | ✅ [open now](https://job-boards.greenhouse.io/gleanwork/jobs/4595665005) |
| 🎯 Field AI | Feb 17 | dropped Feb 17 | ✅ [open now](https://jobs.lever.co/field-ai/ce04c5b3-17c3-49aa-b833-a6bebbf9d23f) |
| 🎯 Ellipsis Labs | Mar 26 | dropped Mar 26 | ✅ [open now](https://jobs.ashbyhq.com/ellipsislabs/02136b22-35b1-4b3d-8bef-567c3380a849) |

_370 companies on the [full radar](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/#radar). **345** dated from our own live observations 🎯 (this grows every cycle). "~Aug" = hand-verified typical month, not a promise of the day; "rolling" = posts year-round; "waiting" = not seen in our tracked feeds yet, not a guarantee it isn't out somewhere else._

<details>
<summary><strong>Recently closed</strong> — 40 roles that left the list in the last 14 days</summary>

_Why each one left is in the last column, because the two reasons carry different evidence. **Gone from feed** = two consecutive complete reads of the employer's board no longer returned it (strong, but not the employer telling us directly). **Out of scope** = still posted, but it no longer passes our filters — our call, not theirs. **Not recorded** = closed before we started tracking the reason._

| Company | Role | Cycle | Closed | Why |
|---|---|---|---|---|
| Graco | Manufacturing Engineering Intern - Summer 2027 | Summer 2027 | 2026-10-10 | gone from feed |
| Motorola | Software Engineer - Summer 2027 Internship | Summer 2027 | 2026-10-10 | gone from feed |
| Dev Technology Group | AI/ML Intern (Summer 2027) | Summer 2027 | 2026-10-09 | gone from feed |
| Dev Technology Group | React/Node Developer Intern (Summer 2027) | Summer 2027 | 2026-10-09 | gone from feed |
| Dev Technology Group | Microsoft Power Platform & AI Intern (Summer 2027) | Summer 2027 | 2026-10-09 | gone from feed |
| Dev Technology Group | AI/Agentic Solution Engineer Intern (Summer 2027) | Summer 2027 | 2026-10-09 | gone from feed |
| REV Robotics | Mechanical Engineering INTERN 2027 | Summer 2027 | 2026-10-09 | gone from feed |
| REV Robotics | Software Engineering INTERN 2027 | Summer 2027 | 2026-10-09 | gone from feed |
| HMH | AI & Automation Development Intern | Summer 2027 | 2026-10-09 | gone from feed |
| The Aerospace Corporation | 2027 Flight Loads Structural Dynamics Undergraduate Intern | Summer 2027 | 2026-10-09 | gone from feed |
| Leidos | Data Science Intern | Summer 2027 | 2026-10-09 | gone from feed |
| Leidos | Software Engineer Intern | Summer 2027 | 2026-10-09 | gone from feed |
| Jones Lang LaSalle (JLL) | AI Intern Summer 2027 Internship - Los Angeles, CA | Summer 2027 | 2026-10-09 | gone from feed |
| Riot Games | Software Engineering Intern - Summer 2027 (Remote) | Summer 2027 | 2026-10-09 | gone from feed |
| Booz Allen | University, 2027 Summer Games Software Developer Intern - Rome, NY | Summer 2027 | 2026-10-09 | gone from feed |
| Brunswick | Manufacturing Engineering Intern Summer '27 | Summer 2027 | 2026-10-09 | gone from feed |
| Fannie Mae | Campus – Data Science Intern (Analytics & Modeling Program) | Summer 2027 | 2026-10-09 | gone from feed |
| Mosaic | Structural Engineer Co-Op/Intern - Summer 2027 | Summer 2027 | 2026-10-09 | gone from feed |
| POET | Software Developer Intern - Summer 2027 | Summer 2027 | 2026-10-09 | gone from feed |
| SoloPulse | Software Engineer Intern/Co-Op - Fall 2026 | Fall 2026 | 2026-10-08 | gone from feed |
| WSP | Structural Engineering Intern - Summer 2027 | Summer 2027 | 2026-10-08 | gone from feed |
| Booz Allen | University, 2027 Summer Games Cyber Security Intern - Rome, NY | Summer 2027 | 2026-10-08 | gone from feed |
| Fifth Third Bank | Software Engineer Co-Op - Enterprise Finance Applications - Summer 2027 | Summer 2027 | 2026-10-08 | gone from feed |
| Oshkosh | Engineer Intern - Mechanical (Summer 2027) | Summer 2027 | 2026-10-08 | gone from feed |
| Saab | Software Engineer Co-Op (Summer 2027) | Summer 2027 | 2026-10-08 | gone from feed |
| Saab | Software Engineering Co-Op (Spring - Summer 2027) | Summer 2027 | 2026-10-08 | gone from feed |
| Saab | Software Engineering Co-Op (Summer 2027) | Summer 2027 | 2026-10-08 | gone from feed |
| IMEG | Structural Engineering Intern / Dallas, TX | Summer 2027 | 2026-10-08 | gone from feed |
| U.S. Bank | 2027 Product Management Summer Intern | Summer 2027 | 2026-10-08 | gone from feed |
| State Affairs | Software Engineer Intern (Summer 2027) | Summer 2027 | 2026-10-08 | gone from feed |
| The Aerospace Corporation | 2027 Structural Mechanics Undergraduate Intern | Summer 2027 | 2026-10-08 | gone from feed |
| Anduril | 2027 Manufacturing Optimization Engineer Intern | Summer 2027 | 2026-10-08 | gone from feed |
| Olsson | Mechanical Engineering Internship - Substation and Power Generation | Summer 2027 | 2026-10-08 | gone from feed |
| RF-SMART | Product Engineering Software Developer Internship - Spring & Summer 2027 | Summer 2027 | 2026-10-08 | gone from feed |
| Voyager Technologies | Fall 2026 Mechanical Engineering Internship | Fall 2026 | 2026-10-08 | gone from feed |
| S&C Electric Company | Software Engineer Intern | Summer 2027 | 2026-10-08 | gone from feed |
| GM financial | Intern - Software Development Engineer | Summer 2027 | 2026-10-08 | gone from feed |
| Stantec | Civil Engineering Internship - Infrastructure (Summer 2027) | Summer 2027 | 2026-10-08 | gone from feed |
| Honeywell | Data Science Co-Op - Spring/Summer 2027 | Summer 2027 | 2026-10-08 | gone from feed |
| Marvell | Machine Learning Engineer Intern, BS/MS - Summer 2027 | Summer 2027 | 2026-10-08 | gone from feed |

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

_Engine (last run): 3,092 of 4,772 registered boards returned successfully across 12 ATS platforms (69% of boards attempted, 64% of the full registry) · completed in 343.9s · 30 board(s) returned a capped result set, so their roles were not eligible to be closed this run · employer or source-derived date on 99% of open roles._

## How this list is built

[METHODOLOGY.md](METHODOLOGY.md) documents exactly what every label claims — what separates a stated cycle from an inferred one, what the ✓ H-1B badge does and doesn't mean, how a role gets closed, and which limitations are known. Anything on this page that doesn't match the code is a bug worth reporting.

## Contributing

Adding a company takes one line, see [CONTRIBUTING.md](CONTRIBUTING.md), or just [open a request](../../issues/new?template=add-company.yml) with the board URL. **Spotted something wrong?** [Report the exact field](../../issues/new?template=wrong-data.yml) — wrong country, wrong cycle, closed role, bad sponsorship flag. Those reports usually fix a rule, which fixes every other role too.

Also here: [PRIVACY.md](PRIVACY.md) (what the email list stores — an address and nothing else) · [SECURITY.md](SECURITY.md) · [ARCHITECTURE.md](ARCHITECTURE.md) · [MIT licensed](LICENSE).

Built by one student with AI assistance, in the open. The part that matters isn't who typed it — it's that the rules, the tests, and every run's output are all public and checkable.

## Note on dates

The **Posted** column shows when a role was published, with the newest at the top. I pull the posting date straight from each job portal, but a lot of them don't expose one publicly, so those rows show a dash (—) for now instead of a guessed date. The ones that do publish a date are dated. Know the real date for a dashed role? Open a PR and I'll merge it.

Roles can close at any time, so always confirm on the company's own site before applying.
