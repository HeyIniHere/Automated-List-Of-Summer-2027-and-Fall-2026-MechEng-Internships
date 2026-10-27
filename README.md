<div align="center">

# 🎓 Summer 2027 Tech Internships

**A self-updating engine that tracks tech internships so you don't have to.**

[![CI](https://img.shields.io/github/actions/workflow/status/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/ci.yml?branch=main&label=tests&style=flat-square&color=3fb950)](https://github.com/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/actions/workflows/ci.yml)&nbsp;[![Open roles](https://img.shields.io/badge/dynamic/json?label=open%20roles&query=open_total&url=https%3A%2F%2Fheyinihere.github.io%2FAutomated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships%2Fapi%2Fstats.json&color=2f81f7&style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/)&nbsp;![Updates](https://img.shields.io/badge/updates-every%20hour-3fb950?style=flat-square)&nbsp;[![RSS](https://img.shields.io/badge/RSS-subscribe-e67e22?style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/feed.xml)

### 1432 open roles (608 listed below) · 184 new this week

4,744 employers tracked · updated Oct 27, 2026 at 07:46 UTC

_1016 have a cycle the employer stated · 416 are recent postings whose cycle isn't stated (listed separately, never mixed in)._

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
- **An engine, not a spreadsheet** - 4,884 job-board endpoints (4,744 distinct employers; some run more than one board) polled every hour across 12 ATS platforms, full source and tests in this repo.

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
| Visa ✓ | Business Strategy Intern, Data and AI Team - Summer 2027 🛂 🆕 | Data & ML/AI | US - Foster City, CA | Oct 27, 2026 | [Apply](https://visa.wd5.myworkdayjobs.com/Visa/job/US---Foster-City-CA/Business-Strategy-Intern--Data-and-AI-Team---Summer-2027_REF089884W-2) |
| Visa ✓ | Data Science Intern, Data and AI Team – Summer 2027 🆕 | Data & ML/AI | US - Foster City, CA | Oct 27, 2026 | [Apply](https://visa.wd5.myworkdayjobs.com/Visa/job/US---Foster-City-CA/Data-Science-Intern--Data-and-AI-Team---Summer-2027_REF089883W-1) |
| Visa ✓ | Product Management Intern, Data and AI Team - Summer 2027 🛂 🆕 | Data & ML/AI | US - Foster City, CA | Oct 27, 2026 | [Apply](https://visa.wd5.myworkdayjobs.com/Visa/job/US---Foster-City-CA/Product-Management-Intern--Data-and-AI-Team---Summer-2027_REF089881W-1) |
| Skydio ✓ | Manufacturing Intern - Summer 2027 🆕 | Hardware | Hayward, California, United States | Oct 26, 2026 | [Apply](https://jobs.ashbyhq.com/skydio/8f4f62b0-a2ea-498d-b78f-6f661b724a3c) |
| Skydio ✓ | Autonomy Engineer Intern, Simulation & Robotics, 2027 (HQ) 🆕 | Hardware | San Mateo, California, United States | Oct 26, 2026 | [Apply](https://jobs.ashbyhq.com/skydio/6f5caf41-fa1d-4208-9bdc-82c72e5d3f17) |
| Skydio ✓ | Autonomy Engineer Intern, Autonomy Infrastructure, Systems and Tools, 2027 (HQ) 🆕 | Software | San Mateo, California, United States | Oct 26, 2026 | [Apply](https://jobs.ashbyhq.com/skydio/ec82eb16-a5b4-46e7-827a-326b33d7d2cb) |
| Niantic Spatial | Software Engineering Intern (Summer 2027) - Native SDK & Mobile Platforms 🆕 | Software | San Francisco, CA | Oct 26, 2026 | [Apply](https://jobs.ashbyhq.com/niantic-spatial/ed68b062-4dcb-4deb-9cc0-ed38030f6e43) |
| Glean ✓ | Software Engineer, Intern (Summer 2027) 🆕 | Software | Mountain View, CA | Oct 26, 2026 | [Apply](https://job-boards.greenhouse.io/gleanwork/jobs/4747670005) |
| GIPathfinder | Manufacturing Engineering Co-op Jan - June 2027 🆕 | Hardware | Burlingame, California, United States | Oct 26, 2026 | [Apply](https://job-boards.greenhouse.io/gipathfinder/jobs/4747868005) |
| Global Infrastructure | Intern, Mechanical Designer 🆕 | Hardware | CA / AB / Calgary - 685 Centre Street S… | Oct 26, 2026 | [Apply](https://gi.wd1.myworkdayjobs.com/Global_Infrastructure/job/CA--AB--Calgary---685-Centre-Street-Southwest/Intern--Mechanical-Designer_6605) |
| Global Infrastructure | Intern, Mechanical Designer 🆕 | Hardware | CA / BC / Vancouver - 200 Granville Str… | Oct 26, 2026 | [Apply](https://gi.wd1.myworkdayjobs.com/Global_Infrastructure/job/CA--BC--Vancouver---200-Granville-Street/Intern--Mechanical-Designer_6607) |
| Global Infrastructure | Intern, Mechanical Designer 🆕 | Hardware | CA / BC / Victoria - 1515 Douglas Street | Oct 26, 2026 | [Apply](https://gi.wd1.myworkdayjobs.com/Global_Infrastructure/job/CA--BC--Victoria---1515-Douglas-Street/Intern--Mechanical-Designer_6602) |
| Sierra Nevada Corporation | Mechanical Engineer Intern - Summer 2027 (For SNC Summer 2026 Interns Only) 🇺🇸 🆕 | Hardware | Lone Tree, CO | Oct 26, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Lone-Tree-CO/Mechanical-Engineer-Intern---Summer-2027--For-SNC-Summer-2026-Interns-Only-_R0031083) |
| Parallel Systems | Hardware Engineering Intern (Mechanical & Electrical) 🆕 | Hardware | Los Angeles, CA | Oct 26, 2026 | [Apply](https://boards.greenhouse.io/parallel/jobs/5275660007?gh_jid=5275660007) |
| Toyota Research Institute ✓ | Robotics Intern, World Foundation Models 🆕 | Hardware | Los Altos, CA | Oct 26, 2026 | [Apply](https://jobs.lever.co/tri/016bbb58-857a-4367-b1aa-0cdc9f818478) |
| Toyota Research Institute ✓ | Robotics Intern, Trustworthy Learning under Uncertainty 🆕 | Hardware | Los Altos, CA | Oct 26, 2026 | [Apply](https://jobs.lever.co/tri/6f60ff79-c902-466a-912c-7ab849ce6424) |
| WSP | Structural Engineering Intern- Summer 2027 🆕 | Hardware | Lakewood, CO, United States | Oct 26, 2026 | [Apply](https://emit.fa.ca3.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2001/job/98294) |
| ADT ✓ | Cybersecurity & Risk Intern 🛂 🆕 | Security | Boca Raton, FL, United States | Oct 26, 2026 | [Apply](https://fa-erqb-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/3022588) |
| onsemi | Summer 2027 - AI & Data Science Intern 🆕 | Data & ML/AI | San Jose, CA, United States | Oct 26, 2026 | [Apply](https://hctz.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2506468) |
| AbbVie ✓ | 2027 Business Technology Solutions Intern - Cybersecurity (Undergraduate) 🆕 | Security | North Chicago, IL, United States | Oct 26, 2026 | [Apply](https://jobs.smartrecruiters.com/AbbVie/3743990016414086) |
| Cohesity ✓ | Software Engineering Intern (Summer 2027) 🆕 | Software | Santa Clara, CA - USA (Office) | Oct 26, 2026 | [Apply](https://cohesity.wd5.myworkdayjobs.com/Cohesity_Careers/job/Santa-Clara-CA---USA-Office/Software-Engineering-Intern--Summer-2027-_R04791-2) |
| Highmark Health ✓ | Summer 2027 Software Engineer enGen Undergraduate Intern 🛂 🆕 | Software | PA, Working at Home - Pennsylvania | Oct 26, 2026 | [Apply](https://highmarkhealth.wd1.myworkdayjobs.com/highmark/job/PA-Working-at-Home---Pennsylvania/Summer-2027-Software-Engineer-enGen-Undergraduate-Intern_J289812) |
| Jabil ✓ | Mechanical System Architect Intern 🆕 | Hardware | Austin, TX | Oct 26, 2026 | [Apply](https://jabil.wd5.myworkdayjobs.com/Jabil_Careers/job/Austin-TX/Mechanical-System-Architect-Intern_J2469350) |
| Northrop Grumman | 2027 Software Engineering Intern - Beavercreek OH 🇺🇸 🆕 | Software | United States-Ohio-Beavercreek | Oct 26, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Ohio-Beavercreek/XMLNAME-2027-Software-Engineering-Intern---Beavercreek-OH_R10257656) |
| Zebra Technologies ✓ | 2027 Summer Internship (US) - Product Management 🛂 🆕 | Software | Lincolnshire, Illinois | Oct 26, 2026 | [Apply](https://zebra.wd501.myworkdayjobs.com/Zebra_careers/job/Lincolnshire-Illinois/XMLNAME-2027-Summer-Internship--US----Product-Management_JR103652) |
| Hive Financial Systems | Software Internship-2027 🆕 | Software | Atlanta, Georgia | Oct 26, 2026 | [Apply](https://job-boards.greenhouse.io/hivefinancialsystems/jobs/5274887007) |
| S&C Electric Company ✓ | Mechanical Engineer (Facilities) Intern 🆕 | Hardware | Chicago, IL, United States | Oct 26, 2026 | [Apply](https://ejia.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/107465) |
| WSP | Mechanical Engineering Intern - Summer 2027 🆕 | Hardware | Boise, ID, United States | Oct 26, 2026 | [Apply](https://emit.fa.ca3.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2001/job/98213) |
| JM Family | Advance Manufacturing Engineering Intern 🆕 | Hardware | Florida - Jacksonville | Oct 26, 2026 | [Apply](https://jmfamily.wd1.myworkdayjobs.com/jmfamily_external/job/Florida---Jacksonville/Advance-Manufacturing-Engineering-Intern_JR105079) |
| Northrop Grumman | 2027 Mechanical Engineering Intern - Clearfield UT 🇺🇸 🆕 | Hardware | United States-Utah-Clearfield | Oct 26, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Utah-Clearfield/XMLNAME-2027-Mechanical-Engineering-Intern---Clearfield-UT_R10257639-1) |
| PTC ✓ | Software Engineer Intern (Summer 2027) 🆕 | Software | Boston, MA, USA | Oct 26, 2026 | [Apply](https://ptc.wd1.myworkdayjobs.com/ptc/job/Boston-MA-USA/Software-Engineer-Intern--Summer-2027-_JR112943) |
| AECOM ✓ | Structural Engineering Intern - Hiring Event with AECOM - Arlington, VA | Hardware | Hunt Valley, MD, United States | Oct 24, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000157611879) |
| AECOM ✓ | Structural Engineering Intern - Hiring Event with AECOM - Arlington, VA | Hardware | Virginia Beach, VA, United States | Oct 24, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000157611929) |
| Amazon ✓ | Software Development Engineer Intern, Amazon Leo - Summer 2027 (USA) 🇺🇸 | Software | Redmond, Washington, USA | Oct 23, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10587999/software-development-engineer-intern-amazon-leo-summer-2027-usa) |
| MongoDB ✓ | 2027 - Software Engineering Intern, AMER | Software | Austin; New York City; San Francisco | Oct 23, 2026 | [Apply](https://www.mongodb.com/careers/job/?gh_jid=8209134) |
| Scout AI | AI Engineer Intern - Fury Team (Summer 2027) | Data & ML/AI | Sunnyvale, CA | Oct 23, 2026 | [Apply](https://jobs.ashbyhq.com/scout-ai/3b639e39-abd7-4a0c-9bea-e1cd0a72db99) |
| ID.me | Summer Intern 2027 - Analytics Engineer Intern | Data & ML/AI | Mountain View, CA | Oct 23, 2026 | [Apply](https://job-boards.greenhouse.io/idmeuniversityrecruiting/jobs/8041991003) |
| Sun Life ✓ | Data Science Intern - Summer 2027 Intern | Data & ML/AI | Wellesley Hills, Massachusetts | Oct 23, 2026 | [Apply](https://sunlife.wd3.myworkdayjobs.com/Campus/job/Wellesley-Hills-Massachusetts/Data-Science-Intern---Summer-2027-Intern_JR00127666-1) |
| TREK ✓ | Mechanical Engineering Intern | Hardware | Waterloo, Wisconsin | Oct 23, 2026 | [Apply](https://trekbikes.wd1.myworkdayjobs.com/TREK/job/Waterloo-Wisconsin/Mechanical-Engineering-Intern_Trek115843) |
| Auto-Owners Insurance | Business Intelligence Developer Internship - Summer 2027 | Software | Lansing, MI | Oct 23, 2026 | [Apply](https://aoins.wd5.myworkdayjobs.com/AutoOwners/job/Lansing-MI/Business-Intelligence-Developer-Internship---Summer-2027_R_14772) |
| GlobalFoundries ✓ | Industrial Engineering Intern (Summer 2027) | Hardware | USA - Vermont - Essex Junction | Oct 23, 2026 | [Apply](https://globalfoundries.wd1.myworkdayjobs.com/External/job/USA---Vermont---Essex-Junction/Industrial-Engineering-Intern--Summer-2027-_JR-2604630) |
| Merck | 2027 Future Talent Program - AI/ML Biomedical Imaging and Computational Pathology - Intern | Data & ML/AI | USA - Massachusetts - Cambridge (320 Be… | Oct 23, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Massachusetts---Cambridge-320-Bent-Street/XMLNAME-2027-Future-Talent-Program---AI-ML-Biomedical-Imaging-and-Computational-Pathology---Intern_R423515) |
| Merck | 2027 Future Talent Program - Data, AI, and Genome Sciences - Intern | Data & ML/AI | USA - Massachusetts - Cambridge (320 Be… | Oct 23, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Massachusetts---Cambridge-320-Bent-Street/XMLNAME-2027-Future-Talent-Program---Data--AI--and-Genome-Sciences---Intern_R423333) |
| Merck | 2027 Future Talent Program - Data, AI, and Genome Sciences, Foundation Models - Intern | Data & ML/AI | USA - Massachusetts - Cambridge (320 Be… | Oct 23, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Massachusetts---Cambridge-320-Bent-Street/XMLNAME-2027-Future-Talent-Program---Data--AI--and-Genome-Sciences--Foundation-Models---Intern_R423438) |
| STV ✓ | Mechanical Engineering Intern - Summer 2027 🛂 | Hardware | Philadelphia, Pennsylvania | Oct 23, 2026 | [Apply](https://stvinc.wd5.myworkdayjobs.com/stv/job/Philadelphia-Pennsylvania/Mechanical-Engineering-Intern---Summer-2027_JR6097-1) |
| Gevernova | GE Vernova Manufacturing Process Engineer Intern - Summer 2027 🛂 | Hardware | Charleroi USA | Oct 23, 2026 | [Apply](https://gevernova.wd5.myworkdayjobs.com/only_confidential_executive_recruiting/job/Charleroi-USA/GE-Vernova-Manufacturing-Process-Engineer-Intern---Summer-2027_R5053285) |
| Verdantas | Mechanical Engineer Summer Intern | Hardware | Holden MA | Oct 23, 2026 | [Apply](https://verdantas.wd108.myworkdayjobs.com/Verdantas/job/Holden-MA/Mechanical-Engineer-Summer-Intern_R-101230) |
| Amazon ✓ | System Development Engineer Intern/Co-op, ROBOTICS -  2027 | Hardware | North Reading, Massachusetts, USA | Oct 22, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10587087/system-development-engineer-intern-co-op-robotics-2027) |
| DoorDash ✓ | Mechanical Engineering, Intern - Labs (Summer 2027) | Hardware | Oakland, CA | Oct 22, 2026 | [Apply](https://job-boards.greenhouse.io/doordashusa/jobs/8313401) |
| CVS Health | Innovation & Technology Internship - Data Science - Summer 2027 (Graduate) 🛂 | Data & ML/AI | NY - New York | Oct 22, 2026 | [Apply](https://cvshealth.wd1.myworkdayjobs.com/CVS_Health_Careers/job/NY---New-York/Innovation---Technology-Internship---Data-Science---Summer-2027--Graduate-_R1081038) |
| CVS Health | Innovation & Technology Internship - Data Science - Summer 2027 (Undergraduate) 🛂 | Data & ML/AI | NY - New York | Oct 22, 2026 | [Apply](https://cvshealth.wd1.myworkdayjobs.com/CVS_Health_Careers/job/NY---New-York/Innovation---Technology-Internship---Data-Science---Summer-2027--Undergraduate-_R1081067) |
| CVS Health | Innovation & Technology Internship - Software Engineering: Data & Intelligence Summer 2027 Graduate 🛂 | Data & ML/AI | NY - New York | Oct 22, 2026 | [Apply](https://cvshealth.wd1.myworkdayjobs.com/CVS_Health_Careers/job/NY---New-York/Innovation---Technology-Internship--Software-Engineering--Data---Intelligence-Summer-2027-Graduate_R1081128) |
| Allstate Insurance Company ✓ | Arity - Data Analytics Engineer Intern 🛂 🏠 | Data & ML/AI | USA - IL (Remote) | Oct 22, 2026 | [Apply](https://allstate.wd5.myworkdayjobs.com/sourcing_event/job/USA---IL-Remote/Arity---Data-Analytics-Engineer-Intern_R36286) |
| Allstate Insurance Company ✓ | Arity - Data Science Intern (Core Telematics) 🛂 🏠 | Data & ML/AI | USA - IL (Remote) | Oct 22, 2026 | [Apply](https://allstate.wd5.myworkdayjobs.com/sourcing_event/job/USA---IL-Remote/Arity---Data-Science-Intern--Core-Telematics-_R36285) |
| Amgen ✓ | Undergrad Intern - Manufacturing and Clinical Supply - Process Development (Summer 2027) | Hardware | US - California - Thousand Oaks | Oct 22, 2026 | [Apply](https://amgen.wd1.myworkdayjobs.com/careers/job/US---California---Thousand-Oaks/Undergrad-Intern---Manufacturing-and-Clinical-Supply---Process-Development--Summer-2027-_R-259434) |
| General Dynamics Information Technology ✓ | Financial Data Analyst Intern (Seasonal) 🇺🇸 | Data & ML/AI | USA VA Falls Church | Oct 22, 2026 | [Apply](https://gdit.wd5.myworkdayjobs.com/gdit_earlytalent/job/USA-VA-Falls-Church/Financial-Data-Analyst-Intern--Seasonal-_RQ230761) |
| Lowe's | Industrial Engineer Intern – Undergrad Internship – Summer 2027 - Field | Hardware | Mooresville, NC (SSC) 1999 | Oct 22, 2026 | [Apply](https://lowes.wd5.myworkdayjobs.com/LWS_External_CS/job/Mooresville-NC-SSC-1999/Industrial-Engineer-Intern---Undergrad-Internship---Summer-2027---Field_JR-02681866) |
| Motorola ✓ | Mechanical Engineering Intern - Summer 2027 | Hardware | Schaumburg, IL | Oct 22, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Schaumburg-IL/Mechanical-Engineering-Intern---Summer-2027_R69727) |
| Northrop Grumman | 2027 Systems Engineering Internship (AI Experience) - Dulles VA 🇺🇸 | Data & ML/AI | United States-Virginia-Dulles | Oct 22, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Virginia-Dulles/XMLNAME-2027-Systems-Engineering-Internship--AI-Experience----Dulles-VA_R10257423) |
| Sierra Nevada Corporation | Systems Security Engineer Intern - Summer 2027 (For SNC Summer 2026 Interns Only) 🇺🇸 | Security | Hagerstown, MD | Oct 22, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Hagerstown-MD/Systems-Security-Engineer-Intern---Summer-2027--For-SNC-Summer-2026-Interns-Only-_R0030540) |
| Sierra Nevada Corporation | Mechanical Engineer Intern (Summer 2027) 🇺🇸 | Hardware | Lone Tree, CO | Oct 22, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Lone-Tree-CO/Mechanical-Engineer-Intern--Summer-2027-_R0031177) |
| RESPEC | Student Engineering Intern (Structural) | Hardware | Anchorage, AK, United States | Oct 22, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000157189739) |
| Nissan ✓ | Cyber Security Intern - Summer 2027 - Smyrna, TN | Security | Smyrna +1 more | Oct 22, 2026 | [Apply](https://alliance.wd3.myworkdayjobs.com/nissanjobs/job/Smyrna-Tennessee---United-States-of-America/Cyber-Security-Intern---Summer-2027---Smyrna--TN_R00214879) |
| Allstate Insurance Company ✓ | Arity - Software Engineer Intern 🛂 🏠 | Software | USA - NC (Remote) | Oct 22, 2026 | [Apply](https://allstate.wd5.myworkdayjobs.com/sourcing_event/job/USA---NC-Remote/Arity---Software-Engineer-Intern_R36266) |
| Insulet Corporation ✓ | Co-op, Mechanical Engineer: January-June 2027 (Onsite) | Hardware | Acton, Massachusetts | Oct 22, 2026 | [Apply](https://insulet.wd5.myworkdayjobs.com/insuletcareers/job/Acton-Massachusetts/Co-op--Mechanical-Engineer--January-June-2027--Onsite-_REQ-2026-18798) |
| Leidos ✓ | AI/ML Intern 🇺🇸 | Data & ML/AI | Huntsville, AL | Oct 22, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Huntsville-AL/AI-ML-Intern_R-00195168) |
| Stryker ✓ | Summer 2027 Internship - Mechanical Engineer | Hardware | Massachusetts, Virtual Address | Oct 22, 2026 | [Apply](https://stryker.wd1.myworkdayjobs.com/StrykerCareers/job/Massachusetts-Virtual-Address/Summer-2027-Internship---Mechanical-Engineer_R573345) |
| GlobalFoundries ✓ | Industrial Engineering Intern (Summer 2027) | Hardware | USA - Vermont - Essex Junction | Oct 21, 2026 | [Apply](https://globalfoundries.wd1.myworkdayjobs.com/External/job/USA---Vermont---Essex-Junction/Industrial-Engineering-Intern--Summer-2027-_JR-2604569) |
| Moog | Intern, Manufacturing and Industrial Engineering | Hardware | Torrance, CA | Oct 21, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Torrance-CA/Intern--Manufacturing-and-Industrial-Engineering_R-26-19823) |
| Smith+Nephew ✓ | Intern Computer Vision Software Engineering | Data & ML/AI | Andover, MA | Oct 21, 2026 | [Apply](https://smithnephew.wd5.myworkdayjobs.com/External/job/Andover-MA/Intern-Computer-Vision-Software-Engineering_R92964) |
| Analytic Partners | Data Science Co-Op / January 2027 🛂 | Data & ML/AI | Miami, Florida, United States | Oct 21, 2026 | [Apply](https://jobs.lever.co/analyticpartners/006928a3-9a6d-49a3-be4f-46d77f0bb302) |
| Duke Energy | Nuclear Cybersecurity 2027 Summer Internship 🇺🇸 | Security | Hartsville, SC | Oct 21, 2026 | [Apply](https://dukeenergy.wd1.myworkdayjobs.com/search/job/Hartsville-SC/Nuclear-Cybersecurity-2027-Summer-Internship_R42099) |
| RTX | Software Engineering Co-op (Spring/Summer 2027) 🇺🇸 | Software | US-IA-CEDAR RAPIDS-130 ~ 5350 C Ave NE… | Oct 21, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-130--5350-C-Ave-NE--BLDG-130/Software-Engineering-Co-op--Spring-Summer-2027-_01882134) |
| RTX | Software Engineering Co-op (Summer/Fall 2027) 🇺🇸 | Software | US-IA-CEDAR RAPIDS-130 ~ 5350 C Ave NE… | Oct 21, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-130--5350-C-Ave-NE--BLDG-130/Software-Engineering-Co-op--Summer-Fall-2027-_01882137) |
| Smith+Nephew ✓ | Intern Agentic AI Software Engineering | Data & ML/AI | Andover, MA | Oct 21, 2026 | [Apply](https://smithnephew.wd5.myworkdayjobs.com/External/job/Andover-MA/Intern-Agentic-AI-Software-Engineering_R92953) |
| Smith+Nephew ✓ | Intern Embedded Software Engineering | Software | Andover, MA | Oct 21, 2026 | [Apply](https://smithnephew.wd5.myworkdayjobs.com/External/job/Andover-MA/Intern-Embedded-Software-Engineering_R92952) |
| Salesforce ✓ | Summer 2027 Intern - AI Research | Data & ML/AI | California - Palo Alto | Oct 20, 2026 | [Apply](https://salesforce.wd12.myworkdayjobs.com/Futureforce_Internships/job/California---Palo-Alto/Summer-2027-Intern---AI-Research_JR365111) |
| Anduril | 2027 Finance Data Analyst Intern | Data & ML/AI | Costa Mesa, California, United States | Oct 20, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5269977007?gh_jid=5269977007) |
| Integrate | Software Engineering Intern (Summer 2027) 🇺🇸 | Software | Seattle, WA | Oct 20, 2026 | [Apply](https://jobs.ashbyhq.com/integrate/7681f59b-70c0-414b-96d9-ae8925cc2ed3) |
| GoFundMe ✓ | MBA Product Management Internship, Summer 2027 | Software | San Francisco, CA | Oct 20, 2026 | [Apply](https://job-boards.greenhouse.io/gofundme/jobs/8304644) |
| Stantec ✓ | Mechanical Engineering Intern - Buildings (Summer 2027) | Hardware | Dallas, TX, United States | Oct 20, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1008413) |
| Stantec ✓ | Mechanical Engineering Intern - Buildings (Summer 2027) | Hardware | Houston, TX, United States | Oct 20, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1008415) |
| Uber ✓ | 2027 Software Engineering Intern, US | Software | San Francisco, CA, United States | Oct 20, 2026 | [Apply](https://iaziqy.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/303922) |
| LinkedIn ✓ | Software Engineer Intern, Undergraduate - Summer 2027 (Mountain View, CA) | Software | Mountain View, CA, United States | Oct 20, 2026 | [Apply](https://jobs.smartrecruiters.com/LinkedIn3/744000156616169) |
| Toyota | 2027 TFS Data Science Internship | Data & ML/AI | Plano, Texas | Oct 20, 2026 | [Apply](https://toyota.wd503.myworkdayjobs.com/tmna/job/Plano-Texas/XMLNAME-2027-TFS-Data-Science-Internship_10338545-1) |
| TruStage | Information Technology - Development and Infrastructure Internship (hybrid) 🏠 | Software | Wisconsin - Remote | Oct 20, 2026 | [Apply](https://trustage.wd1.myworkdayjobs.com/TruStage/job/Wisconsin---Remote/Enterprise-Information---Technology-Internship--Hybrid-_R-012155) |
| Stantec ✓ | Mechanical Engineering Intern - Buildings (Summer 2027) | Hardware | Austin, TX, United States | Oct 20, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1008370) |
| Philips | Intern – R&D Front-End Innovation Intern - Oral Healthcare – Bothell, WA – Summer 2027 | Other | Bothell, Washington, United States | Oct 20, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Bothell-Washington-United-States/Intern---R-D-Front-End-Innovation-Intern---Oral-Healthcare---Bothell--WA---Summer-2027_593146) |
| General Motors ✓ | 2027 Summer Intern - Manufacturing Excellence Industrial Engineering | Hardware | Warren +2 more | Oct 20, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Warren-Michigan-United-States-of-America/XMLNAME-2027-Summer-Intern---Manufacturing-Excellence-Industrial-Engineering_JR-202622634) |
| IMEG ✓ | Mechanical Engineering Co-op / Philadelphia, PA | Hardware | Philadelphia, PA | Oct 20, 2026 | [Apply](https://wd1.myworkdaysite.com/recruiting/imeg/Imeg_Careers/job/Philadelphia-PA/Mechanical-Engineering-Co-op---Philadelphia--PA_R-16908) |
| Watts Water | Manufacturing Engineer Co-Op, Jan-June 2027 | Hardware | Germantown, WI | Oct 20, 2026 | [Apply](https://wattswater.wd5.myworkdayjobs.com/Intern-External/job/Germantown-WI/Manufacturing-Engineer-Co-Op--Jan-June-2027_10017699) |
| Zebra Technologies ✓ | 2027 Summer Internship (US) - Mechanical Engineer 🛂 | Hardware | Holtsville, New York | Oct 20, 2026 | [Apply](https://zebra.wd501.myworkdayjobs.com/Zebra_careers/job/Holtsville-New-York/XMLNAME-2027-Summer-Internship--US----Mechanical-Engineer_JR103627) |
| Verizon Communications | Basking Ridge, NJ: VTeamer for a Day: Verizon Consumer Group: Data Science Summer 2027 Internship | Data & ML/AI | Basking Ridge, New Jersey | Oct 20, 2026 | [Apply](https://verizon.wd12.myworkdayjobs.com/verizon-careers/job/Basking-Ridge-New-Jersey/Basking-Ridge--NJ--VTeamer-for-a-Day--Verizon-Consumer-Group--Data-Science-Summer-2027-Internship_R-1102417) |
| Verizon Communications | Verizon Consumer Group: Data Science Summer 2027 Internship | Data & ML/AI | Basking Ridge, New Jersey | Oct 20, 2026 | [Apply](https://verizon.wd12.myworkdayjobs.com/verizon-careers/job/Basking-Ridge-New-Jersey/Verizon-Consumer-Group--Data-Science-Summer-2027-Internship_R-1102419) |
| Scale AI ✓ | Machine Learning Research Intern (Summer 2027) | Data & ML/AI | New York, NY; San Francisco, CA | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/scaleai/jobs/4735665005) |
| CACI | Mechanical Engineering Intern - Summer 2027 🇺🇸 | Hardware | Dulles, VA, US | Oct 19, 2026 | [Apply](https://caci.wd1.myworkdayjobs.com/external/job/Dulles-VA-US/Mechanical-Engineering-Intern---Summer-2027_333564) |
| Patreon ✓ | Software Engineering Intern - Summer 2027 | Software | New York | Oct 19, 2026 | [Apply](https://jobs.ashbyhq.com/patreon/cefe07ab-ba4f-48cc-86b9-a88b1859a95c) |
| Amplify ✓ | Summer 2027: Software Engineering Intern 🏠 | Software | Remote - United States | Oct 19, 2026 | [Apply](https://jobs.ashbyhq.com/amplify/855d22a3-f15e-49f6-854c-29e505653efa) |
| Amplify ✓ | Summer 2027: AI Scientist Intern 🏠 | Data & ML/AI | Remote - United States | Oct 19, 2026 | [Apply](https://jobs.ashbyhq.com/amplify/bb45b7f6-dd7e-40e5-84e6-52e21650a7b8) |
| Amplify ✓ | Summer 2027: Product Management Intern 🏠 | Software | Remote - United States | Oct 19, 2026 | [Apply](https://jobs.ashbyhq.com/amplify/c95f690f-28af-42b1-8847-5dcf14c1155e) |
| Inversion Space | AI & Internal Tools Software Engineer - Summer Internship 2027 🇺🇸 | Data & ML/AI | Playa Vista, California, United States | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/inversionspace/jobs/4745076005) |
| Inversion Space | Vehicle Software Engineer - Summer Internship 2027 🇺🇸 | Software | Playa Vista, California, United States | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/inversionspace/jobs/4745083005) |
| The Allen Institute for AI | Research Internship, Robotics | Hardware | Seattle, WA | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/thealleninstitute/jobs/8293641) |
| Clean Harbors ✓ | Mechanical Project Engineer Intern - Summer 2027 | Hardware | Dugway, UT, United States | Oct 19, 2026 | [Apply](https://epyc.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/167236) |
| RESPEC | Student Intern (Civil or Structural Engineering) | Hardware | Juneau, AK, United States | Oct 19, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000156379056) |
| Alcon ✓ | Spring/Summer 2027 Manufacturing Science & Technology Co-op | Hardware | Fort Worth, Texas | Oct 19, 2026 | [Apply](https://alcon.wd5.myworkdayjobs.com/careers_alcon/job/Fort-Worth-Texas/Spring-Summer-2027-Manufacturing-Science---Technology-Co-op_R-2026-50373) |
| Nissan ✓ | Industrial Engineering Intern - Summer 2027 - Smyrna, TN | Hardware | Smyrna +1 more | Oct 19, 2026 | [Apply](https://alliance.wd3.myworkdayjobs.com/nissanjobs/job/Smyrna-Tennessee---United-States-of-America/Industrial-Engineering-Intern---Summer-2027---Smyrna--TN_R00214284) |
| Nissan ✓ | Industrial Engineering Intern - Summer 2027 - Smyrna, TN | Hardware | Smyrna +1 more | Oct 19, 2026 | [Apply](https://alliance.wd3.myworkdayjobs.com/nissanjobs/job/Smyrna-Tennessee---United-States-of-America/Industrial-Engineering-Intern---Summer-2027---Smyrna--TN_R00214872) |
| Charter Manufacturing | Materials Engineer Intern (Summer 2027) | Hardware | Charter Aarrowcast - Shawano, WI | Oct 19, 2026 | [Apply](https://chartermfg.wd5.myworkdayjobs.com/Charter_Careers/job/Charter-Aarrowcast---Shawano-WI/Materials-Engineer-Intern--Summer-2027-_R08192) |
| Zurn Elkay Water Solutions | Product Management Intern - Summer 2027 | Software | Downers Grove, IL | Oct 19, 2026 | [Apply](https://elkay.wd1.myworkdayjobs.com/Elkay_External/job/Downers-Grove-IL/Product-Management-Intern---Summer-2027_REQ-020065) |
| General Dynamics Information Technology ✓ | GDIT Summer Internship Program-Summer 2027 Software Development Internship -Egg Harbor Township New Jersey 🇺🇸 | Software | USA NJ Egg Harbor Township | Oct 19, 2026 | [Apply](https://gdit.wd5.myworkdayjobs.com/gdit_earlytalent/job/USA-NJ-Egg-Harbor-Township/GDIT-Summer-Internship-Program---Summer-2027-Software-Development-Internship--_RQ230643) |
| RTX | Software Engineering Co-op (Summer / Fall 2027) 🇺🇸 | Software | US-IA-CEDAR RAPIDS-130 ~ 5350 C Ave NE… | Oct 19, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-130--5350-C-Ave-NE--BLDG-130/Software-Engineering-Co-op--Summer---Fall-2027-_01881368) |
| Highmark Health ✓ | Summer 2027 Data Analyst Undergraduate Intern 🛂 | Data & ML/AI | Pittsburgh PA +3 more | Oct 19, 2026 | [Apply](https://highmarkhealth.wd1.myworkdayjobs.com/highmark/job/Pittsburgh-PA-15222-FAP-5th-Avenue-Place/Summer-2027-Data-Analyst-Undergraduate-Intern_J288017) |
| Philips | Intern/Co-op - STET Mechanical Engineer – Latham, NY – Spring/Summer 2027 | Hardware | Latham, New York, United States | Oct 19, 2026 | [Apply](https://philips.wd3.myworkdayjobs.com/jobs-and-careers/job/Latham-New-York-United-States/Intern-Co-op---STET-Mechanical-Engineer---Latham--NY---Spring-Summer-2027_591053) |
| The Toro Company | Cloud Software Development Intern - The Toro Company 🛂 | Software | Frederick, CO | Oct 19, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Frederick-CO/Cloud-Software-Development-Intern---The-Toro-Company_JR17498) |
| Marvell ✓ | AI Data Science Intern, MS - Summer 2027 | Data & ML/AI | Santa Clara, CA | Oct 19, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/marvellcareers2/job/Santa-Clara-CA/AI-Data-Science-Intern--MS---Summer-2027_2603846) |
| Johnson & Johnson | Quality Data Science Co-Op , Summer 2027 | Data & ML/AI | Cincinnati +2 more | Oct 19, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cincinnati-Ohio-United-States-of-America/Quality-Data-Science-Co-Op---Summer-2027_R-103629) |
| GlobalFoundries ✓ | Industrial Engineering Intern (Summer 2027) | Hardware | USA - New York - Malta | Oct 16, 2026 | [Apply](https://globalfoundries.wd1.myworkdayjobs.com/External/job/USA---New-York---Malta/Industrial-Engineering-Intern--Summer-2027-_JR-2604575) |
| Ryan | Summer 2027 Intern, Software Development | Software | Plano TX | Oct 16, 2026 | [Apply](https://ryan.wd1.myworkdayjobs.com/RyanCareers/job/Plano/Summer-2027-Intern--Software-Development_R0020822-1) |
| Ryan | Summer 2027 Intern, Software Engineering | Software | Plano TX | Oct 16, 2026 | [Apply](https://ryan.wd1.myworkdayjobs.com/RyanCareers/job/Plano/Summer-2027-Intern--Software-Engineering_R0020843-1) |
| General Dynamics Information Technology ✓ | Summer 2027 AI and Estimation Intern 🇺🇸 | Data & ML/AI | USA VA Falls Church | Oct 16, 2026 | [Apply](https://gdit.wd5.myworkdayjobs.com/gdit_earlytalent/job/USA-VA-Falls-Church/Technical-Intern---AI-and-Estimation_RQ230646) |
| CACI | Aerospace Engineer Intern - Summer 2027 🇺🇸 | Hardware | Aberdeen Proving Ground, MD, US | Oct 16, 2026 | [Apply](https://caci.wd1.myworkdayjobs.com/external/job/Aberdeen-Proving-Ground-MD-US/Aerospace-Engineer-Intern---Summer-2027_333570) |
| CACI | Aerospace Engineer Intern - Summer 2027 🇺🇸 | Hardware | Aberdeen Proving Ground, MD, US | Oct 16, 2026 | [Apply](https://caci.wd1.myworkdayjobs.com/external/job/Aberdeen-Proving-Ground-MD-US/Aerospace-Engineer-Intern---Summer-2027_333648) |
| OATEY | Materials Intern - Cleveland Manufacturing | Hardware | Cleveland, OH (Manufacturing) | Oct 15, 2026 | [Apply](https://wd5.myworkdaysite.com/recruiting/oatey/Oatey_External_/job/Cleveland-OH-Manufacturing/Materials-Intern---Cleveland-Manufacturing_R7196) |
| LLNL | Critical Infrastructure Analysis Graduate Intern - Cyber and Critical Infrastructure Summer Institute - Summer 2027 🇺🇸 | Security | Livermore, CA, United States | Oct 15, 2026 | [Apply](https://jobs.smartrecruiters.com/llnl/3743990016164366) |
| LLNL | Power Systems Undergraduate Intern - Cyber and Critical Infrastructure Summer Institute - Summer 2027 🇺🇸 | Security | Livermore, CA, United States | Oct 15, 2026 | [Apply](https://jobs.smartrecruiters.com/llnl/3743990016164416) |
| LLNL | Critical Infrastructure Analysis Undergraduate Intern - Cyber and Critical Infrastructure Summer Institute - Summer 2027 🇺🇸 | Security | Livermore, CA, United States | Oct 15, 2026 | [Apply](https://jobs.smartrecruiters.com/llnl/3743990016165496) |
| Commonwealth Fusion Systems | Intern - Mechanical Engineer - Summer 2027 | Hardware | Milpitas, CA | Oct 15, 2026 | [Apply](https://jobs.lever.co/cfsenergy/9690a768-362f-4df8-86a1-554b896cbc76) |
| Inversion Space | Avionics Mechanical Engineer - Summer Internship 2027 🇺🇸 | Hardware | Playa Vista, California, United States | Oct 15, 2026 | [Apply](https://job-boards.greenhouse.io/inversionspace/jobs/4744390005) |
| General Matter | Summer 2027 Internship - Information Security Engineer | Security | Los Angeles, CA | Oct 15, 2026 | [Apply](https://job-boards.greenhouse.io/generalmatter/jobs/5448019008) |
| Clean Harbors ✓ | Mechanical Engineering Project Management Intern - Summer 2027 | Hardware | Norwell, MA, United States | Oct 15, 2026 | [Apply](https://epyc.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/167238) |
| Lawrence Livermore National Laboratory (LLNL) | Critical Infrastructure Analysis Graduate Intern - Cyber and Critical Infrastructure Summer Institute - Summer 2027 🇺🇸 | Security | Livermore, CA, United States | Oct 15, 2026 | [Apply](https://jobs.smartrecruiters.com/LLNL/3743990016164366) |
| Lawrence Livermore National Laboratory (LLNL) | Power Systems Undergraduate Intern - Cyber and Critical Infrastructure Summer Institute - Summer 2027 🇺🇸 | Security | Livermore, CA, United States | Oct 15, 2026 | [Apply](https://jobs.smartrecruiters.com/LLNL/3743990016164416) |
| Lawrence Livermore National Laboratory (LLNL) | Critical Infrastructure Analysis Undergraduate Intern - Cyber and Critical Infrastructure Summer Institute - Summer 2027 🇺🇸 | Security | Livermore, CA, United States | Oct 15, 2026 | [Apply](https://jobs.smartrecruiters.com/LLNL/3743990016165496) |
| Adient ✓ | Lean Manufacturing Intern | Hardware | Plymouth, MI | Oct 15, 2026 | [Apply](https://adient.wd3.myworkdayjobs.com/External/job/Plymouth-MI/Lean-Manufacturing-Intern_R-29531) |
| Ardian | Data Scientist Intern - February 2027 / NYC | Data & ML/AI | New York | Oct 15, 2026 | [Apply](https://ardian.wd103.myworkdayjobs.com/ArdianCareers/job/New-York/Data-Scientist-Intern---February-2027---NYC_JR1002271) |
| General Motors ✓ | 2027 Summer Intern, AI Research, Embodied AI (Masters) | Data & ML/AI | Sunnyvale +2 more | Oct 15, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Sunnyvale-California-United-States-of-America/XMLNAME-2027-Summer-Intern--AI-Research--Embodied-AI--Masters-_JR-202622535) |
| General Motors ✓ | 2027 Summer Intern, Onboard Autonomy, Embodied AI (Masters) | Data & ML/AI | Sunnyvale +2 more | Oct 15, 2026 | [Apply](https://generalmotors.wd5.myworkdayjobs.com/Careers_GM/job/Sunnyvale-California-United-States-of-America/XMLNAME-2027-Summer-Intern--Onboard-Autonomy--Embodied-AI--Masters-_JR-202622543) |
| The Toro Company | Manufacturing Engineering Intern - HammerHead 🛂 | Hardware | Lake Mills, WI | Oct 15, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Lake-Mills-WI/Manufacturing-Engineering-Intern---HammerHead_JR17635) |
| Muon Space | Ground Software Engineering Intern (Summer 2027) 🇺🇸 | Software | San Jose, CA | Oct 15, 2026 | [Apply](https://job-boards.greenhouse.io/muonspace/jobs/5266679007) |
| Hitachi Energy ✓ | Mechanical Engineering Intern/Co-Op | Hardware | Ogden, Utah, United States | Oct 15, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Ogden-Utah-United-States/Mechanical-Engineering-Intern-Co-Op_R0146513) |
| AECOM ✓ | Structural Engineering Intern | Hardware | Raleigh, NC, United States | Oct 14, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000155592720) |
| Charter Manufacturing | Mechanical Engineer Intern (Summer 2027) | Hardware | Charter Wire - Menomonee Valley - Milwaukee +1 more | Oct 14, 2026 | [Apply](https://chartermfg.wd5.myworkdayjobs.com/Charter_Careers/job/Charter-Wire---Menomonee-Valley---Milwaukee-WI/Mechanical-Engineer-Intern--Summer-2027-_R08115) |
| Howden | Underwriting Intern, Cyber | Security | New York – 1350 Avenue Of The Americas | Oct 14, 2026 | [Apply](https://hyperiongrp.wd3.myworkdayjobs.com/Hyperion_External/job/New-York--1350-Avenue-Of-The-Americas/Underwriting-Intern_R0019772-1) |
| ICF ✓ | 2027 Summer Intern, AI Engineer (Reston, VA) 🇺🇸 | Data & ML/AI | Reston, VA | Oct 14, 2026 | [Apply](https://icf.wd5.myworkdayjobs.com/ICFExternal_Career_Site/job/Reston-VA/XMLNAME-2027-Summer-Intern--AI-Engineer--Reston--VA-_R2603518) |
| ICF ✓ | 2027 Summer Intern, AI Engineer (Reston, VA) 🛂 | Data & ML/AI | Reston, VA | Oct 14, 2026 | [Apply](https://icf.wd5.myworkdayjobs.com/ICFExternal_Career_Site/job/Reston-VA/XMLNAME-2027-Summer-Intern--AI-Engineer--Reston--VA-_R2603521) |
| ICF ✓ | 2027 Summer Intern, Software Engineer (Reston, VA) 🇺🇸 | Software | Reston, VA | Oct 14, 2026 | [Apply](https://icf.wd5.myworkdayjobs.com/ICFExternal_Career_Site/job/Reston-VA/XMLNAME-2027-Summer-Intern--Software-Engineer--Reston--VA-_R2603522) |
| Plastipak | Manufacturing Operations (Engineering) Intern – Summer 2027 | Hardware | Plastipak - Pineville, LA | Oct 14, 2026 | [Apply](https://plastipak.wd1.myworkdayjobs.com/Plastipak/job/Plastipak---Pineville-LA/Manufacturing-Operations--Engineering--Intern---Summer-2027_REQ24668) |
| National Life ✓ | Data Science Intern – Summer 2027 🛂 | Data & ML/AI | Addison, TX; Montpelier, VT | Oct 14, 2026 | [Apply](https://job-boards.greenhouse.io/nationallifeinsurancecompany/jobs/4449670009) |
| Point7 | 2027 Summer Internship – Software Engineer | Software | New York, NY | Oct 14, 2026 | [Apply](https://boards.greenhouse.io/point72/jobs/8885733002?gh_jid=8885733002) |
| Plastipak | Manufacturing Operations (Engineering) Intern – Summer 2027 | Hardware | Plastipak - Plant City, FL | Oct 14, 2026 | [Apply](https://plastipak.wd1.myworkdayjobs.com/Plastipak/job/Plastipak---Plant-City-FL/Manufacturing-Operations--Engineering--Intern---Summer-2027_REQ24669) |
| QTS | Summer 2027 Internship: Information Security Operations Analyst 🇺🇸 | Security | US GA Atlanta Suwanee 1 DC1 | Oct 14, 2026 | [Apply](https://qtsdatacenters.wd5.myworkdayjobs.com/qts/job/US-GA-Atlanta-Suwanee-1-DC1/Summer-2027-Internship--Information-Security-Operations-Analyst_R2026-2273) |
| Anduril | 2027 Firmware Engineer Intern | Hardware | Costa Mesa, California, United States | Oct 13, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5265158007?gh_jid=5265158007) |
| Netflix ✓ | Software Engineer Intern - Summer 2027 | Software | Los Gatos +2 more | Oct 13, 2026 | [Apply](https://explore.jobs.netflix.net/careers/job/790318904468) |
| Field AI | Robotics Research, Robot Learning & Manipulation Intern (Spring, Summer, & Fall 2027) | Hardware | Irvine, CA | Oct 13, 2026 | [Apply](https://jobs.lever.co/field-ai/b37569c3-d07f-4968-82dc-44020f34e54e) |
| Field AI | Robotics Research, Embodied AI Intern (Spring & Summer 2027) | Data & ML/AI | Irvine, CA | Oct 13, 2026 | [Apply](https://jobs.lever.co/field-ai/ef35c537-b864-479f-9dbe-b30429ac7704) |
| Allison Transmission ✓ | Manufacturing Engineering Internship - Summer 2027 🇺🇸 | Hardware | Indianapolis, IN | Oct 13, 2026 | [Apply](https://allisontransmission.wd1.myworkdayjobs.com/ATI-External/job/Indianapolis-IN/Manufacturing-Engineering-Internship---Summer-2026_R008288) |
| Allison Transmission ✓ | Manufacturing Engineering Internship - Summer 2027 🇺🇸 | Hardware | Indianapolis, IN | Oct 13, 2026 | [Apply](https://allisontransmission.wd1.myworkdayjobs.com/ATI-External/job/Indianapolis-IN/Manufacturing-Engineering-Internship---Summer-2026_R008289) |
| Motorola ✓ | Mechanical Engineering Intern - Summer 2027 | Hardware | Plantation, FL | Oct 13, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Plantation-FL/Mechanical-Engineering-Intern---Summer-2027_R69030) |
| Watts Water | End User & Infrastructure Support Intern, Summer 2027 | Software | Andover, MA Federal Street | Oct 13, 2026 | [Apply](https://wattswater.wd5.myworkdayjobs.com/Intern-External/job/Andover-MA-Federal-Street/IT-Network-Intern--Summer-2027_10017567) |
| ADT ✓ | Data, Analytics & AI Internship 🛂 | Data & ML/AI | Boca Raton, FL, United States | Oct 13, 2026 | [Apply](https://fa-erqb-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/3022387) |
| Draper | Classified Cybersecurity/IT Internship (Summer 2027) 🇺🇸 | Security | Cambridge, MA | Oct 13, 2026 | [Apply](https://draper.wd5.myworkdayjobs.com/Draper_Careers/job/Cambridge-MA/Classified-Cybersecurity-IT-Internship--Summer-2027-_JR003021) |
| OATEY | Engineering Intern, Manufacturing & Automation | Hardware | Shakopee, MN (Manufacturing) | Oct 12, 2026 | [Apply](https://wd5.myworkdaysite.com/recruiting/oatey/Oatey_External_/job/Shakopee-MN-Manufacturing/Engineering-Intern--Manufacturing---Automation_R7258) |
| ABB ✓ | Manufacturing Engineering Intern - Summer 2027 🛂 | Hardware | USA, NC, Hickory | Oct 12, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/USA-NC-Hickory/Manufacturing-Engineering-Intern---Summer-2027_JR00047568) |
| ADT ✓ | Product Management & Product Operations Internship 🛂 | Software | Boca Raton, FL, United States | Oct 12, 2026 | [Apply](https://fa-erqb-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/3022393) |
| Bosch | Manufacturing Engineer Intern - Summer 2027 | Hardware | Lincolnshire, IL, United States | Oct 12, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000155100809) |
| Allison Transmission ✓ | Internship - Manufacturing Engineer 🇺🇸 | Hardware | Indianapolis, IN | Oct 12, 2026 | [Apply](https://allisontransmission.wd1.myworkdayjobs.com/ATI-External/job/Indianapolis-IN/Internship---Manufacturing-Engineer_R008319) |
| American Family Insurance Group | Summer 2027 Data Analyst Intern - Agency Performance, Insights and Operations | Data & ML/AI | WI Madison | Oct 12, 2026 | [Apply](https://amfam.wd1.myworkdayjobs.com/AmFamGroupInternCareers/job/WI-Madison/Summer-2027-Data-Analyst-Intern---Agency-Performance--Insights-and-Operations_R39513) |
| Verizon Communications | Verizon Consumer Group: Home & Mobile Value Prop Summer 2027 Internship | Software | Basking Ridge, New Jersey | Oct 12, 2026 | [Apply](https://verizon.wd12.myworkdayjobs.com/verizon-careers/job/Basking-Ridge-New-Jersey/Verizon-Consumer-Group--Home---Mobile-Value-Prop-Summer-2027-Internship_R-1102103) |
| Watts Water | Product Management Co-op, Jan-June 2027 | Software | Menomonee Falls, WI | Oct 12, 2026 | [Apply](https://wattswater.wd5.myworkdayjobs.com/Intern-External/job/Menomonee-Falls-WI/Product-Management-Co-op--Jan-June-2027_10017702) |
| CapTech Consulting | Consulting Internship: Software Engineering (Summer 2027) 🛂 | Software | Richmond, VA, United States | Oct 12, 2026 | [Apply](https://jobs.smartrecruiters.com/CapTechConsulting/744000155019115) |
| Commonwealth Fusion Systems | Intern - Manufacturing Engineer - Spring or Summer 2027 | Hardware | Devens, MA | Oct 09, 2026 | [Apply](https://jobs.lever.co/cfsenergy/01ec2ee8-b8c9-4f32-9b66-3a2ce1ff704f) |
| Commonwealth Fusion Systems | Intern - Industrial Engineer - Spring or Summer 2027 | Hardware | Devens, MA | Oct 09, 2026 | [Apply](https://jobs.lever.co/cfsenergy/7ed4bf93-2b32-4096-9af3-2eb79e620039) |
| Workday ✓ | Cybersecurity Engineer Intern 🛂 | Security | USA, CA, Pleasanton | Oct 09, 2026 | [Apply](https://workday.wd5.myworkdayjobs.com/Workday_Early_Career/job/USA-CA-Pleasanton/Cybersecurity-Engineer-Intern_JR-0110809) |
| Workday ✓ | Machine Learning Engineer Intern 🛂 | Data & ML/AI | USA, CA, Pleasanton | Oct 09, 2026 | [Apply](https://workday.wd5.myworkdayjobs.com/Workday_Early_Career/job/USA-CA-Pleasanton/Machine-Learning-Engineer-Intern_JR-0110812) |
| Workday ✓ | Software Application Development Engineer Intern 🛂 | Software | USA, CA, Pleasanton | Oct 09, 2026 | [Apply](https://workday.wd5.myworkdayjobs.com/Workday_Early_Career/job/USA-CA-Pleasanton/Software-Application-Development-Engineer-Intern_JR-0110811) |
| GCM Grosvenor | 2027 Software Engineering Summer Intern | Software | Chicago, Illinois, United States | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/gcmgrosvenor/jobs/8015792003) |
| DoorDash ✓ | Software Engineer, Intern - Labs (Summer 2027) | Software | San Francisco, CA; Sunnyvale, CA | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/doordashusa/jobs/8263774) |
| IMC Trading | Machine Learning Engineer Intern - Summer 2027 | Data & ML/AI | New York, United States | Oct 08, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4962456101) |
| SharkNinja ✓ | Summer 2027: Mechanical Engineering Intern, Shark (May to August) | Hardware | Needham, MA, United States | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4718812006) |
| Viget | Software Developer Intern (2027) 🛂 | Software | Boulder, CO | Oct 08, 2026 | [Apply](https://jobs.lever.co/viget/b18cc87d-fca2-485a-a0f2-ad6197db63f2) |
| Moog | Intern, Computer Science | Software | Torrance, CA | Oct 08, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Torrance-CA/Intern--Computer-Science_R-26-19819) |
| Plastipak | Manufacturing Operations (Engineering) Intern – Summer 2027 | Hardware | Plastipak - Havre de Grace, MD | Oct 08, 2026 | [Apply](https://plastipak.wd1.myworkdayjobs.com/Plastipak/job/Plastipak---Havre-de-Grace-MD/Manufacturing-Operations--Engineering--Intern---Summer-2027_REQ24670) |
| The Toro Company | Manufacturing Engineering Intern - The Toro Company 🛂 | Hardware | Shakopee, MN | Oct 08, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Shakopee-MN/Manufacturing-Engineering-Intern---The-Toro-Company_JR17581) |
| Rugged Robotics | Mechanical Engineering Intern/Co-op (Spring or Summer 2027) | Hardware | Houston, TX | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/ruggedrobotics/jobs/4730900005) |
| Rugged Robotics | Robotic Software Intern/Co-op (Spring or Summer 2027) | Software | Houston, TX | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/ruggedrobotics/jobs/4730908005) |
| Modernizing Medicine | Software Engineering Intern | Software | Boca Raton, FL | Oct 08, 2026 | [Apply](https://modmed.wd501.myworkdayjobs.com/ModMed12/job/Boca-Raton-FL/Software-Engineering-Intern_R5148) |
| Moog | Intern, Software Engineering | Software | Mineral Wells, TX | Oct 08, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Mineral-Wells-TX/Intern--Software-Engineering_R-26-19965) |
| Amazon ✓ | Software Development Engineer (Embedded Systems) Intern, Amazon Leo - Summer 2027 (USA) 🇺🇸 | Software | Redmond, Washington, USA | Oct 07, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10571374/software-development-engineer-embedded-systems-intern-amazon-leo-summer-2027-usa) |
| Apple Bank | 2027 Summer Intern- Information Security 🛂 | Security | New York, NY | Oct 07, 2026 | [Apply](https://applebank.wd5.myworkdayjobs.com/applebankcareers/job/New-York-NY/XMLNAME-2027-Summer-Intern--Information-Security_2026-1416) |
| Arc | Mechanical Engineering Intern - Recreational | Hardware | Torrance, CA | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/arcboatcompany/jobs/5445312008) |
| State Affairs | Software Engineer Intern (Summer 2027) | Software | Washington, DC | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/stateaffairs/jobs/4437430009) |
| Elanco | Manufacturing Associate Intern – Winslow, Maine (Summer 2027) | Hardware | Winslow, ME | Oct 07, 2026 | [Apply](https://elanco.wd5.myworkdayjobs.com/External_Career/job/Winslow-ME/Manufacturing-Associate-Intern---Winslow--Maine--Summer-2027-_R0027460) |
| Johnson & Johnson | GTO Manufacturing Engineering Co-op, Summer 2027 | Hardware | Cornelia +2 more | Oct 07, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cornelia-Georgia-United-States-of-America/GTO-Manufacturing-Engineering-Co-op--Summer-2027_R-103371) |
| Sigma Computing ✓ | Software Engineering Intern (Summer 2027) 🛂 | Software | San Francisco, CA | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/sigmacomputing/jobs/7850795003) |
| Sigma Computing ✓ | Software Engineering Intern (Summer 2027) 🛂 | Software | New York, NY | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/sigmacomputing/jobs/8001295003) |
| Highmark Health ✓ | Summer 2027 Artificial Intelligence (Operations) Undergraduate Intern 🛂 | Data & ML/AI | Pittsburgh PA +3 more | Oct 06, 2026 | [Apply](https://highmarkhealth.wd1.myworkdayjobs.com/highmark/job/Pittsburgh-PA-15222-FAP-5th-Avenue-Place/Summer-2027-Artificial-Intelligence--Operations--Undergraduate-Intern_J287476) |
| ABB ✓ | Manufacturing Quality Intern - Summer 2027 🛂 | Hardware | USA, NM, Albuquerque | Oct 06, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/USA-NM-Albuquerque/Manufacturing-Quality-Intern---Summer-2027_JR00048446) |
| Dmainc | Cybersecurity Intern - Summer 2027 | Security | Fort Wayne, IN | Oct 06, 2026 | [Apply](https://dmainc.wd5.myworkdayjobs.com/dma/job/Fort-Wayne-IN/Cybersecurity-Intern---Summer-2027_REQ742) |
| Courier Health | Software Engineering Intern (Summer 2027) | Software | New York, New York, United States | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/courierhealth/jobs/5258913007) |
| MEMX | Information Security Intern, Summer 2027 (Hybrid, NYC) | Security | United States | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/memx/jobs/5445236008) |
| Pure Storage ✓ | Software Engineer Intern (Summer 2027) | Software | Santa Clara, California | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/purestorage/jobs/8249749) |
| Carpenter Technology | Maintenance Intern - Mechanical | Hardware | Reading, PA | Oct 06, 2026 | [Apply](https://cartech.wd5.myworkdayjobs.com/CTCExternal/job/Reading-PA/Maintenance-Intern---Mechanical_26885) |
| Hudson River Trading ✓ | Data Scientist Intern - 2027 | Data & ML/AI | London +4 more | Oct 05, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=8257369) |
| Midland States Bank | Intern - IT Infrastructure | Software | Effingham, IL | Oct 05, 2026 | [Apply](https://midlandsb.wd1.myworkdayjobs.com/msbcareers/job/Effingham-IL/Intern---IT-Infrastructure_JR1471) |
| Arc | Mechanical Engineering Intern - Powertrain | Hardware | Torrance, CA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/arcboatcompany/jobs/5442958008) |
| WSP | Mechanical Engineering Co-op - Spring/Summer 2027 | Hardware | Philadelphia, PA, United States | Oct 05, 2026 | [Apply](https://emit.fa.ca3.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2001/job/95758) |
| ABB ✓ | Manufacturing Intern - Summer 2027 🛂 | Hardware | USA, NM, Albuquerque | Oct 05, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/USA-NM-Albuquerque/Manufacturing-Intern---Summer-2027_JR00047889) |
| Hitachi Energy ✓ | Mechanical Engineering Internship/Co-op | Hardware | Liberty, South Carolina, United States | Oct 05, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Liberty-South-Carolina-United-States/Mechanical-Engineering-Internship-Co-op_R0144979) |
| Jain Global | Data Engineer Intern | Data & ML/AI | New York, New York | Oct 05, 2026 | [Apply](https://jainglobal.wd5.myworkdayjobs.com/ExternalSite/job/New-York-New-York/Data-Engineer-Intern_JR100605-1) |
| LexisNexis Risk Solutions ✓ | Data Science Intern | Data & ML/AI | Alpharetta, GA (Alderman) | Oct 05, 2026 | [Apply](https://relx.wd3.myworkdayjobs.com/RiskSolutions/job/Alpharetta-GA-Alderman/Data-Science-Intern_R118955) |
| Hitachi Energy ✓ | Mechanical Engineering Internship/Co-op | Hardware | Auburn Hills, Michigan, United States | Oct 05, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Auburn-Hills-Michigan-United-States/Mechanical-Engineering-Internship-Co-op_R0143857) |
| Anduril | 2027 Industrial Engineer Intern | Hardware | Ashville +5 more | Oct 02, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5255593007?gh_jid=5255593007) |
| Affirm ✓ | Software Engineer (Machine Learning) Intern (Summer 2027) | Data & ML/AI | San Francisco, California, United States | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/affirm/jobs/8008645003) |
| Affirm ✓ | Software Engineer Intern (Summer 2027) | Software | San Francisco, California, United States | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/affirm/jobs/8011590003) |
| Harvey ✓ | Software Engineering Intern (Summer 2027) | Software | New York | Oct 02, 2026 | [Apply](https://jobs.ashbyhq.com/harvey/06d64648-b84b-48ae-94a2-d9c06dfdcb5d) |
| Cox | Cybersecurity Intern - Summer 2027 | Security | Atlanta GA | Oct 02, 2026 | [Apply](https://cox.wd1.myworkdayjobs.com/Cox_External_Career_Site_1/job/Atlanta-GA/Cybersecurity-Intern---Summer-2027_R202683372) |
| Arc | Software Engineering Intern | Software | Torrance, CA | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/arcboatcompany/jobs/5442881008) |
| Muon Space | Industrial Engineering Intern (Summer 2027) 🇺🇸 | Hardware | San Jose, CA | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/muonspace/jobs/5256284007) |
| Bedrock Robotics | 2027 Internship Behavior ML Engineer, Learned Manipulation Policies | Data & ML/AI | San Francisco, CA | Oct 02, 2026 | [Apply](https://jobs.ashbyhq.com/bedrock-robotics/96a6423e-7439-4cb4-9109-117b14e47f7c) |
| xAI | Summer 2027 Software Engineering Internship/Co-op | Software | Palo Alto, CA | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/xai/jobs/5255111007) |
| The Aerospace Corporation | 2027 Flight Loads Structural Dynamics Graduate Intern 🇺🇸 | Hardware | El Segundo, CA | Oct 02, 2026 | [Apply](https://aero.wd5.myworkdayjobs.com/external/job/El-Segundo-CA/XMLNAME-2027-Flight-Loads-Structural-Dynamics-Graduate-Intern_R016755) |
| Charter Manufacturing | Smart Manufacturing Engineer Intern (Summer 2027) | Hardware | Charter Steel - Saukville, WI | Oct 02, 2026 | [Apply](https://chartermfg.wd5.myworkdayjobs.com/Charter_Careers/job/Charter-Steel---Saukville-WI/Smart-Manufacturing-Engineer-Intern--Summer-2027-_R08133) |
| Nelnet ✓ | Intern - IT Software Engineer .NET (Summer 2027) | Software | Lincoln, NE | Oct 02, 2026 | [Apply](https://nelnet.wd1.myworkdayjobs.com/MyNelnet/job/Lincoln-NE/Intern---IT-Software-Engineer-NET--Summer-2027-_R23198) |
| Major League Baseball | Intern, Data Science | Data & ML/AI | Citi Field – Queens, New York | Oct 02, 2026 | [Apply](https://sterlingmets.wd5.myworkdayjobs.com/Mets/job/Citi-Field--Queens-New-York/Intern--Data-Science_R1508) |
| Pinterest ✓ | Software Engineer Intern 2027 (USA) 🏠 | Software | San Francisco, CA, US; Remote, US | Oct 01, 2026 | [Apply](https://www.pinterestcareers.com/jobs/?gh_jid=7838577) |
| Pinterest ✓ | Software Engineering Intern 2027 (Toronto) | Software | Toronto, ON, CA | Oct 01, 2026 | [Apply](https://www.pinterestcareers.com/jobs/?gh_jid=8138039) |
| Pinterest ✓ | Machine Learning Intern 2027 (Toronto) | Data & ML/AI | Toronto, ON, CA | Oct 01, 2026 | [Apply](https://www.pinterestcareers.com/jobs/?gh_jid=8138080) |
| The Federal Reserve System | Summer 2027 Intern-Data Science and Business Analytics 🛂 | Data & ML/AI | Chicago, IL | Oct 01, 2026 | [Apply](https://rb.wd5.myworkdayjobs.com/FRS/job/Chicago-IL/Summer-2027-Intern-Data-Science-and-Business-Analytics_R-0000033609) |
| The Federal Reserve System | Summer 2027 Intern-Cybersecurity and Information Security 🛂 | Security | Chicago, IL | Oct 01, 2026 | [Apply](https://rb.wd5.myworkdayjobs.com/FRS/job/Chicago-IL/Summer-2027-Intern-Cybersecurity-and-Information-Security_R-0000033612-1) |
| Mach Industries | Summer 2027 Engineering Internship, Manufacturing 🇺🇸 | Hardware | Huntington Beach +5 more | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/machindustries/jobs/4429928009) |
| Walleye Capital | Special Projects Developer Intern (Summer 2027) | Software | New York, New York | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/walleyecapital-external-students/jobs/4716166006) |
| Datacor | Summer 2027 AI Engineer Intern 🏠 | Data & ML/AI | Remote, US | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/datacor/jobs/5242412007) |
| ATC | Intern - Cyber Security Summer 2027 | Security | Pewaukee, WI | Oct 01, 2026 | [Apply](https://atcllc.wd5.myworkdayjobs.com/atcllc/job/Pewaukee-WI/Intern---Cyber-Security-Summer-2027_R0003307) |
| CoStar Group | Embedded Software Engineering Intern 🛂 | Software | Sunnyvale (US) | Oct 01, 2026 | [Apply](https://costar.wd1.myworkdayjobs.com/Costar_Campus/job/Sunnyvale-US/Embedded-Software-Engineering-Intern_R39950) |
| CoStar Group | Mechanical Engineering Intern 🛂 | Hardware | Sunnyvale (US) | Oct 01, 2026 | [Apply](https://costar.wd1.myworkdayjobs.com/Costar_Campus/job/Sunnyvale-US/Mechanical-Engineering-Intern_R39952) |
| Marvell ✓ | Firmware Engineer Intern, MS - Summer 2027 | Hardware | Santa Clara, CA | Oct 01, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/marvellcareers2/job/Santa-Clara-CA/Firmware-Engineer-Intern--MS---Summer-2027_2604513-1) |
| The Federal Reserve System | TS - Application Security Intern - 2027 🇺🇸 | Security | Cleveland, OH | Oct 01, 2026 | [Apply](https://rb.wd5.myworkdayjobs.com/FRS/job/Cleveland-OH/TS---Application-Security-Intern---2027_R-0000033625) |
| Zekelman Industries | Intern, Manufacturing Engineer | Hardware | Niles, OH | Oct 01, 2026 | [Apply](https://zekelman.wd12.myworkdayjobs.com/Careers/job/Niles-OH/Intern--Manufacturing-Engineer_JR002843) |
| Varda Space | Cybersecurity Internship - Summer 2027 🇺🇸 | Security | El Segundo, California, United States | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/vardaspace/jobs/8005821003) |
| Varda Space | Flight Software Internship - Summer 2027 🇺🇸 | Software | El Segundo, California, United States | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/vardaspace/jobs/8010159003) |
| Varda Space | Manufacturing Engineering Internship - Summer 2027 🇺🇸 | Hardware | El Segundo, California, United States | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/vardaspace/jobs/8010166003) |
| Generac ✓ | 2027 Summer Intern Digital Manufacturing Engineering | Hardware | Waukesha, WI - USA | Oct 01, 2026 | [Apply](https://generac.wd5.myworkdayjobs.com/external/job/Waukesha-WI---USA/XMLNAME-2027-Summer-Intern-Digital-Manufacturing-Engineering_JR16255) |
| Muon Space | Thermal Engineering Intern (Summer 2027) 🇺🇸 | Hardware | San Jose, CA | Sep 30, 2026 | [Apply](https://job-boards.greenhouse.io/muonspace/jobs/5253474007) |
| Allen Control Systems | Android Developer Intern, 2027 | Software | Austin, TX | Sep 30, 2026 | [Apply](https://jobs.ashbyhq.com/allen-control-systems/1cd2b432-9a01-4ae0-8eb2-6ebd9c278b94) |
| Dandy | Summer 2027 Internship - Software Engineering Intern | Software | USA - New York NY | Sep 30, 2026 | [Apply](https://jobs.ashbyhq.com/dandy/d43558e9-8e51-4980-b00d-39275063f099) |
| STV ✓ | Structural Engineering Intern - Summer 2027 🛂 | Hardware | Oklahoma City, Oklahoma | Sep 30, 2026 | [Apply](https://stvinc.wd5.myworkdayjobs.com/stv/job/Oklahoma-City-Oklahoma/Structural-Engineering-Intern---Summer-2027_JR6315) |
| Zekelman Industries | Intern, Manufacturing Engineer | Hardware | Rochelle, IL | Sep 30, 2026 | [Apply](https://zekelman.wd12.myworkdayjobs.com/Careers/job/Rochelle-IL/Intern--Manufacturing-Engineer_JR002824) |
| Helion Energy | Materials Engineering Summer 2027 Intern | Hardware | Everett, WA | Sep 29, 2026 | [Apply](https://jobs.ashbyhq.com/helion/56636c72-2c72-4f4f-8334-3b233a235c8d) |
| AMCA | Software Engineering Internship (Summer 2027) 🇺🇸 | Software | El Segundo, CA | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/amca/jobs/4425120009) |
| Freeform | Manufacturing Engineering Intern, CNC Machining (Summer 2027) | Hardware | Los Angeles, CA (On-site) | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/freeformfuturecorp/jobs/8004101003) |
| Itron ✓ | Intern - Data Science, Distributed Intelligence | Data & ML/AI | United States of America +2 more | Sep 29, 2026 | [Apply](https://itron.wd5.myworkdayjobs.com/Early_Careers/job/United-States-of-America-Washington-Liberty-Lake/Intern---Data-Science--Distributed-Intelligence_JR102942-2) |
| Insulet Corporation ✓ | Co-op, Software Development Engineer in Test: January - June 2027 (Hybrid) | Software | Acton, Massachusetts | Sep 29, 2026 | [Apply](https://insulet.wd5.myworkdayjobs.com/insuletcareers/job/Acton-Massachusetts/Co-op--Software-Development-Engineer-in-Test--January---June-2027--Hybrid-_REQ-2026-18026) |
| Insulet Corporation ✓ | Co-op, Manufacturing: January - June 2027 (Onsite) | Hardware | Irvine, California | Sep 29, 2026 | [Apply](https://insulet.wd5.myworkdayjobs.com/insuletcareers/job/Irvine-California/Co-op--Manufacturing--January---June-2027--Onsite-_REQ-2026-18119) |
| Enova ✓ | Software Engineer Internship Summer 2027 (Hybrid) 🛂 | Software | Chicago, IL | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/enova/jobs/8239619) |
| National Life ✓ | Digital & AI Experience Intern – Summer 2027 🛂 | Data & ML/AI | Addison, TX; Montpelier, VT | Sep 29, 2026 | [Apply](https://job-boards.greenhouse.io/nationallifeinsurancecompany/jobs/4403876009) |
| Marvell ✓ | AI-Native Development Platform Engineer Intern, MS - Summer 2027 | Data & ML/AI | Santa Clara, CA | Sep 29, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/marvellcareers2/job/Santa-Clara-CA/AI-Native-Development-Platform-Engineer-Intern--MS---Summer-2027_2603848) |
| nVent | Manufacturing Automaton Intern (June - August 2027) 🛂 | Hardware | Anoka, MN, US | Sep 29, 2026 | [Apply](https://nvent.wd5.myworkdayjobs.com/nVent/job/Anoka-MN-US/Manufacturing-Automaton-Intern--June---August-2027-_R23865) |
| Q2 | 2027 Summer Internship - Data Science 🛂 | Data & ML/AI | Cary, North Carolina | Sep 29, 2026 | [Apply](https://q2ebanking.wd5.myworkdayjobs.com/Q2/job/Cary-North-Carolina/XMLNAME-2027-Summer-Internship---Data-Science_REQ-12799) |
| Q2 | 2027 Summer Internship - Machine Learning Engineer 🛂 | Data & ML/AI | Cary, North Carolina | Sep 29, 2026 | [Apply](https://q2ebanking.wd5.myworkdayjobs.com/Q2/job/Cary-North-Carolina/XMLNAME-2027-Summer-Internship---Machine-Learning-Engineer_REQ-12800) |
| Q2 | 2027 Summer Internship - Software Engineer 🛂 | Software | Cary, North Carolina | Sep 29, 2026 | [Apply](https://q2ebanking.wd5.myworkdayjobs.com/Q2/job/Cary-North-Carolina/XMLNAME-2027-Summer-Internship---Software-Engineer_REQ-12798) |
| Hermeus | Flight Software Engineering Intern (Simulation/Hardware-In-The-Loop) - Spring & Summer 2027 🇺🇸 | Hardware | Los Angeles, CA | Sep 29, 2026 | [Apply](https://jobs.lever.co/hermeus/78008094-ca81-4a0c-9a18-93b30f932acd) |
| The Aerospace Corporation | 2027 Software Tools and Assurance Engineering Grad Intern 🇺🇸 | Software | El Segundo, CA | Sep 28, 2026 | [Apply](https://aero.wd5.myworkdayjobs.com/external/job/El-Segundo-CA/XMLNAME-2027-Software-Tools-and-Assurance-Engineering-Grad-Intern_R016753) |
| Zurn Elkay Water Solutions | Industrial Engineering Intern (Summer 2027) | Hardware | Freeport, IL | Sep 28, 2026 | [Apply](https://elkay.wd1.myworkdayjobs.com/Elkay_External/job/Freeport-IL/Industrial-Engineering-Intern--Summer-2027-_REQ-020072) |
| AtkinsRéalis | Structural Engineering Intern – Summer 2027 | Hardware | US.CO.Denver | Sep 28, 2026 | [Apply](https://slihrms.wd3.myworkdayjobs.com/careers/job/USCODenver/Structural-Engineering-Intern---Summer-2027_R-161182-1) |
| AtkinsRéalis | Structural Engineering Intern – Summer 2027 | Hardware | US.WA.Bothell | Sep 28, 2026 | [Apply](https://slihrms.wd3.myworkdayjobs.com/careers/job/USWABothell/Structural-Engineering-Intern---Summer-2027_R-162449-1) |
| Formlabsinternships | Desktop Software Intern (Summer 2027) | Software | Somerville, MA | Sep 28, 2026 | [Apply](https://job-boards.greenhouse.io/formlabsinternships/jobs/8223362) |
| Mars | Summer 2027 Mars Petcare Manufacturing Internship | Hardware | USA-Arkansas-Ft. Smith | Sep 28, 2026 | [Apply](https://mars.wd3.myworkdayjobs.com/external/job/USA-Arkansas-Ft-Smith/Summer-2027-Mars-Petcare-Manufacturing-Internship_R168212-1) |
| Cencora | AI Intern | Data & ML/AI | Conshohocken, PA | Sep 28, 2026 | [Apply](https://myhrabc.wd5.myworkdayjobs.com/Global/job/Conshohocken-PA/AI-Intern_R2613670) |
| Veterans United ✓ | Intern - Software Engineer - Summer 2027 🏠 | Software | Remote MO | Sep 28, 2026 | [Apply](https://veteransunited.wd1.myworkdayjobs.com/VUHL/job/Remote-MO/Intern---Software-Engineer---Summer-2027_R6249) |
| Aurora Innovation ✓ | Core Autonomy Software (C++) Intern 🆕 | Software | Mountain View, CA | Sep 25, 2026 | [Apply](https://jobs.ashbyhq.com/aurora-operations-inc/c823b343-ba1f-4ff3-84ce-965ee9952c12) |
| Mach Industries | Summer 2027 Engineering Internship, Mechanical 🇺🇸 | Hardware | Huntington Beach +11 more | Sep 25, 2026 | [Apply](https://job-boards.greenhouse.io/machindustries/jobs/4420611009) |
| Mach Industries | Summer 2027 Engineering Internship, Software/GNC 🇺🇸 | Software | Huntington Beach +5 more | Sep 25, 2026 | [Apply](https://job-boards.greenhouse.io/machindustries/jobs/4420626009) |
| Figma ✓ | Data Engineer Intern (2027) | Data & ML/AI | San Francisco, CA • New York, NY | Sep 23, 2026 | [Apply](https://boards.greenhouse.io/figma/jobs/6178851004?gh_jid=6178851004) |
| DoorDash ✓ | Machine Learning Intern (Masters) - Summer 2027 | Data & ML/AI | San Francisco +7 more | Sep 23, 2026 | [Apply](https://job-boards.greenhouse.io/doordashusa/jobs/8204111) |
| Figma ✓ | Software Engineer Intern (Summer 2027) | Software | San Francisco, CA • New York, NY | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/figma/jobs/6143238004?gh_jid=6143238004) |
| Figma ✓ | Data Science Intern (2027) | Data & ML/AI | San Francisco, CA • New York, NY | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/figma/jobs/6178857004?gh_jid=6178857004) |
| Lyft ✓ | Data Science Intern, Algorithms (Summer 2027 - SF/NYC) | Data & ML/AI | San Francisco, CA | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8767723002?gh_jid=8767723002) |
| Lyft ✓ | Software Engineer Intern, Backend (Summer 2027 - SF) | Software | San Francisco, CA | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8767726002?gh_jid=8767726002) |
| Lyft ✓ | Data Science Intern, Algorithms (Summer 2027 - SF/NYC) | Data & ML/AI | New York, NY | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8796124002?gh_jid=8796124002) |
| Coinbase ✓ | Software Engineer Intern | Software | Hybrid - San Francisco, CA | Sep 08, 2026 | [Apply](https://www.coinbase.com/careers/positions/8168315?gh_jid=8168315) |
| Coinbase ✓ | Machine Learning Engineer Intern | Data & ML/AI | Hybrid - San Francisco, CA | Sep 08, 2026 | [Apply](https://www.coinbase.com/careers/positions/8175441?gh_jid=8175441) |
| Coinbase ✓ | Data Engineer Intern | Data & ML/AI | Hybrid - San Francisco, CA | Sep 08, 2026 | [Apply](https://www.coinbase.com/careers/positions/8175459?gh_jid=8175459) |
| Datadog ✓ | Software Engineering Intern (Summer) | Software | Boston +5 more | Sep 08, 2026 | [Apply](https://careers.datadoghq.com/detail/8052118/?gh_jid=8052118) |
| Scale AI ✓ | Software Engineering Intern (Summer 2027) | Software | San Francisco, CA | Sep 04, 2026 | [Apply](https://job-boards.greenhouse.io/scaleai/jobs/4730845005) |
| Roblox ✓ | [Summer 2027] Product Management Intern | Software | San Mateo, CA, United States | Sep 02, 2026 | [Apply](https://careers.roblox.com/jobs/8143981?gh_jid=8143981) |
| Notion ✓ | Software Engineer Intern (Summer 2027) | Software | San Francisco, California | Aug 14, 2026 | [Apply](https://jobs.ashbyhq.com/notion/3fba1c39-c5cb-47d7-9ad2-1cec4d7e9d0c) |
| Roblox ✓ | [Summer 2027] Software Engineer Intern | Software | San Mateo, CA, United States | Aug 05, 2026 | [Apply](https://careers.roblox.com/jobs/8072713?gh_jid=8072713) |
| Hudson River Trading ✓ | Software Engineering Internship (C++ or Python) – Summer 2027 | Software | Austin +11 more | Jul 13, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=8052083) |
| Akuna Capital ✓ | Software Engineer Intern - C++, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018847/?gh_jid=8018847) |
| Akuna Capital ✓ | Platform Engineer Intern, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018856/?gh_jid=8018856) |
| Akuna Capital ✓ | Software Engineer Intern - C# .NET Desktop, Summer 2027 | Software | Chicago, IL | Jul 13, 2026 | [Apply](https://www.akunacapital.com/careers/job/8018886/?gh_jid=8018886) |
| IMC Trading | Software Engineer Intern - Summer 2027 | Software | Chicago, United States | Jul 01, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4823924101) |
| IMC Trading | Deep Learning Research Intern - Summer 2027 - New York | Data & ML/AI | New York, United States | Jul 01, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4907430101) |
| Databricks ✓ | Data Science Intern (2027 Start) | Data & ML/AI | Mountain View +3 more | Aug 17, 2023 | [Apply](https://databricks.com/company/careers/open-positions/job?gh_jid=6866538002) |
| Databricks ✓ | Product Management Intern (Summer 2027) | Software | Bellevue +5 more | Aug 17, 2023 | [Apply](https://databricks.com/company/careers/open-positions/job?gh_jid=6883068002) |
| Databricks ✓ | Software Engineering Intern (2027) | Software | Bellevue +7 more | Aug 04, 2023 | [Apply](https://databricks.com/company/careers/open-positions/job?gh_jid=6865687002) |
| Rippling | Software Engineer Intern - Backend Focused - Summer 2027 | Software | Seattle, WA | — | [Apply](https://ats.rippling.com/rippling/jobs/a07e4e46-3721-4934-b57b-0d58412e22ba) |
| Rippling | Data Science Intern - Summer 2027 | Data & ML/AI | San Francisco, CA | — | [Apply](https://ats.rippling.com/rippling/jobs/f255bf03-9173-4c0a-8a18-7cc43c27ded8) |
| Rippling | Full Stack Software Engineer Intern - Summer 2027 | Software | New York, NY | — | [Apply](https://ats.rippling.com/rippling/jobs/f64b6158-9534-4bab-9457-45556166b262) |

## Fall 2026  (33 employer-stated)

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Sierra Nevada Corporation | Mechanical Engineer II (For 2026 Interns Only) 🇺🇸 | Hardware | Plano, TX | Oct 22, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Plano-TX/Mechanical-Engineer-II--For-2026-Interns-Only-_R0031204) |
| The Allen Institute for AI | Research Internship, AI for Science | Data & ML/AI | Seattle, WA | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/thealleninstitute/jobs/8293615) |
| Sierra Nevada Corporation | Aerospace Engineer I (For 2026 Interns Only) 🇺🇸 | Hardware | Lone Tree, CO | Oct 06, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Lone-Tree-CO/Aerospace-Engineer-I--For-2026-Interns-Only-_R0030592) |
| Sierra Nevada Corporation | Software Engineer I (For 2026 Interns Only) 🇺🇸 | Software | Dayton, OH | Oct 06, 2026 | [Apply](https://snc.wd1.myworkdayjobs.com/snc_external_career_site/job/Dayton-OH/Software-Engineer-I--For-2026-Interns-Only-_R0030889) |
| RoboForce | Robotics Mechanical Engineering Intern (Fall/Winter 2026) | Hardware | Milpitas, CA | Oct 01, 2026 | [Apply](https://job-boards.greenhouse.io/roboforce/jobs/5441463008) |
| Moog | Intern, Artificial Intelligence | Data & ML/AI | Buffalo, NY | Sep 29, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Artificial-Intelligence_R-26-20288) |
| GITAI | Field-Deployed Software Engineering Intern – Fall 2026 / Spring 2027 🇺🇸 | Software | Los Angeles, California, United States | Sep 28, 2026 | [Apply](https://job-boards.greenhouse.io/gitai/jobs/5437128008) |
| QuEra Computing | Internship - Scientific Software and Compilation | Software | Boston, MA, USA | Sep 27, 2026 | [Apply](https://job-boards.greenhouse.io/queracomputinginc/jobs/5435902008) |
| American Century Investments | Infrastructure Automation Engineer Intern 🛂 | Software | Kansas City, Missouri | Sep 25, 2026 | [Apply](https://americancentury.wd5.myworkdayjobs.com/AmericanCenturyInvestments/job/Kansas-City-Missouri/Infrastructure-Automation-Engineer-Intern_R0005750) |
| American Century Investments | Software Developer Intern 🛂 | Software | Kansas City, Missouri | Sep 25, 2026 | [Apply](https://americancentury.wd5.myworkdayjobs.com/AmericanCenturyInvestments/job/Kansas-City-Missouri/Software-Developer-Intern_R0005749-1) |
| Mill | Computer Vision Intern, Fall/Winter 2026 🛂 | Data & ML/AI | San Bruno, California | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/mill/jobs/4737741005) |
| Eurofins | 6-month paid internship - AI & Automation | Data & ML/AI | Barcelona, CT, ES | Sep 22, 2026 | [Apply](https://jobs.smartrecruiters.com/Eurofins/744000150986035) |
| G2 | Intern, AI Agent Evaluations | Data & ML/AI | San Francisco, CA | Sep 21, 2026 | [Apply](https://jobs.ashbyhq.com/g2/64dcc04a-a0e7-493b-b899-dd4c56e561fd) |
| Bot Auto | Intern, Software Engineer AI Agents (Fall/Winter 2026) | Data & ML/AI | Houston, TX | Sep 18, 2026 | [Apply](https://job-boards.greenhouse.io/botauto/jobs/5429357008) |
| American Century Investments | Cybersecurity Intern 🛂 | Security | Kansas City, Missouri | Sep 16, 2026 | [Apply](https://americancentury.wd5.myworkdayjobs.com/AmericanCenturyInvestments/job/Kansas-City-Missouri/Cybersecurity-Intern_R0005729) |
| Contoro | Robotics Engineer Intern - Test & Validation (Fall 2026) | Hardware | Austin, TX | Sep 16, 2026 | [Apply](https://jobs.ashbyhq.com/contoro/cf7c8043-8fbe-4c7e-b91f-ee6db2a616c5) |
| Moog | Intern, Mechanical Engineering | Hardware | Torrance, CA | Sep 15, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Torrance-CA/Intern--Mechanical-Engineering_R-26-19918-1) |
| Axon ✓ | AfroTech 2026 Software Engineering Internship | Software | Seattle, Washington, United States | Sep 11, 2026 | [Apply](https://job-boards.greenhouse.io/axontalentcommunity/jobs/7993376003) |
| Moog | Intern, Embedded Design Engineering | Software | Blacksburg, VA | Sep 11, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Blacksburg-VA/Intern--Embedded-Design-Engineering_R-26-20053) |
| Eurofins | 6-month paid internship - AI & Automation | Data & ML/AI | Barcelona, CT, ES | Sep 10, 2026 | [Apply](https://jobs.smartrecruiters.com/Eurofins/744000148712379) |
| Eurofins | AI & Automation Intern | Data & ML/AI | Barcelona, CT, ES | Sep 09, 2026 | [Apply](https://jobs.smartrecruiters.com/Eurofins/744000148531473) |
| Re:Build Manufacturing | Manufacturing Engineer Intern Fall 2026 | Hardware | Merrimack, NH | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/rebuildmanufacturing/jobs/4729848005) |
| Northrop Grumman | 2026 Part-Time Cyber Security Engineering Intern - Aurora CO 🇺🇸 | Security | United States-Colorado-Aurora | Aug 31, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Colorado-Aurora/XMLNAME-2026-Part-Time-Cyber-Security-Engineering-Intern---Aurora-CO_R10248520) |
| Northrop Grumman | 2026 Part-Time Mechanical Engineering Intern - Chandler AZ 🇺🇸 | Hardware | United States-Arizona-Chandler | Aug 26, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Arizona-Chandler/XMLNAME-2026-Part-Time-Mechanical-Engineering-Intern---Chandler-AZ_R10247965) |
| Johnson & Johnson | Software Engineer Coop | Software | Cincinnati +2 more | Aug 07, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cincinnati-Ohio-United-States-of-America/Software-Engineer-Coop_R-092820) |
| Phoenix Contact | Manufacturing Co-Op - High School Students | Hardware | Middletown, Pennsylvania | Aug 04, 2026 | [Apply](https://job-boards.greenhouse.io/phoenixcontact/jobs/7817228003) |
| Merck | 2026 Future Talent Program – Manufacturing and Reliability Engineering Co-Op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Manufacturing-and-Reliability-Engineering-Co-Op_R395901) |
| Merck | 2026 Future Talent Program - Vaccine Manufacturing Co-op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Vaccine-Manufacturing-Co-op_R395900) |
| Northrop Grumman | 2026 Fall Co-op Manufacturing Engineering - Baltimore MD 🇺🇸 | Hardware | United States-Maryland-Linthicum | Aug 03, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Maryland-Linthicum/XMLNAME-2026-Fall-Co-op-Manufacturing-Engineering---Baltimore-MD_R10243390-1) |
| RoboForce | Robotics Electrical Engineering Intern (Fall/Winter 2026) | Hardware | Milpitas, CA | Apr 14, 2026 | [Apply](https://job-boards.greenhouse.io/roboforce/jobs/5181214008) |
| Applied Materials ✓ | 2026 Fall Materials Engineering Co-op (TCAD Modeling) - Doctorate (Gloucester, MA) | Hardware | Gloucester,MA | Apr 01, 2026 | [Apply](https://amat.wd1.myworkdayjobs.com/External/job/GloucesterMA/XMLNAME-2026-Fall-Materials-Engineering-Co-op---Doctorate--Gloucester--MA-_R2611503) |
| Alloy Enterprises | Co-Op, Thermal Test Engineer, Fall 2026 (July-December) 🇺🇸 | Hardware | Burlington, MA | Mar 25, 2026 | [Apply](https://jobs.ashbyhq.com/alloyenterprises/946e7ae1-d2ac-4889-a72a-268b0aeda9bd) |
| Amazon ✓ | Robotics - Hardware Development Engineer Intern/Co-op - 2026 (Robotics, Mechanical, Electrical, Hardware Test, Reliability, Failure Analysis, Operations, and more) | Hardware | Westboro, Massachusetts, USA | Dec 17, 2025 | [Apply](https://www.amazon.jobs/en/jobs/3145033/robotics-hardware-development-engineer-intern-co-op-2026-robotics-mechanical-electrical-hardware-test-reliability-failure-analysis-operations-and-more) |

## Recently posted — cycle not stated  (275 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Generac ✓ | Intern AI Engineering 🆕 | Data & ML/AI | Waukesha, WI - USA | Oct 26, 2026 | [Apply](https://generac.wd5.myworkdayjobs.com/external/job/Waukesha-WI---USA/Intern-AI-Engineering_JR17736) |
| Lila Sciences | Co-op, Mechatronics Engineer 🆕 | Hardware | Cambridge, MA USA | Oct 26, 2026 | [Apply](https://job-boards.greenhouse.io/lilasciences/jobs/4465068009) |
| Parallel Systems | Software Engineering Intern (Embedded, Backend, Fullstack) 🆕 | Software | Los Angeles, CA | Oct 26, 2026 | [Apply](https://boards.greenhouse.io/parallel/jobs/5275690007?gh_jid=5275690007) |
| Parallel Systems | Product Management Intern 🆕 | Software | Los Angeles, CA | Oct 26, 2026 | [Apply](https://boards.greenhouse.io/parallel/jobs/5275719007?gh_jid=5275719007) |
| Toyota Research Institute ✓ | Robotics Intern, Post-Training and Continual Learning 🆕 | Hardware | Los Altos, CA | Oct 26, 2026 | [Apply](https://jobs.lever.co/tri/f6541d1f-b72f-456f-829f-bf118ac10c43) |
| Daimler Truck ✓ | Mechatronics Engineering Intern – Vehicle Architecture and Controls 🆕 | Hardware | Gaffney, SC US | Oct 26, 2026 | [Apply](https://dtna.wd5.myworkdayjobs.com/DTNA_external/job/Gaffney-SC-US/Mechatronics-Engineering-Intern---Vehicle-Architecture-and-Controls_DT-20389) |
| Standard Aero | HR AI & Process Innovation Intern 🆕 | Data & ML/AI | Scottsdale, AZ, United States | Oct 26, 2026 | [Apply](https://cva.fa.us1.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_3/job/10369) |
| Analog Devices ✓ | DevOps Co-Op 🆕 | Software | US, MA, Boston | Oct 26, 2026 | [Apply](https://analogdevices.wd1.myworkdayjobs.com/External/job/US-MA-Boston/DevOps-Co-Op_R267690) |
| Analog Devices ✓ | Embedded Systems Co-Op 🆕 | Software | US, MA, Boston | Oct 26, 2026 | [Apply](https://analogdevices.wd1.myworkdayjobs.com/External/job/US-MA-Boston/Embedded-Systems-Co-Op_R267689) |
| Axos Bank | Data Analyst Intern 🆕 | Data & ML/AI | Omaha, NE | Oct 26, 2026 | [Apply](https://axos.wd5.myworkdayjobs.com/Axos/job/Omaha-NE/Data-Intern_JR5642) |
| Dematic ✓ | Mechanical Engineer - Co-Op 🛂 🆕 | Hardware | Grand Rapids, MI, United States | Oct 26, 2026 | [Apply](https://kiongroup.wd3.myworkdayjobs.com/kion_scs/job/Grand-Rapids-MI-United-States/Mechanical-Engineer---Co-Op_JR-0098269-1) |
| Prologis | AI and Automation (IT) Intern 🆕 | Data & ML/AI | Denver, Colorado | Oct 26, 2026 | [Apply](https://prologis.wd5.myworkdayjobs.com/Prologis_External_Careers/job/Denver-Colorado/AI-and-Automation--IT--Intern_R6883) |
| Valmont ✓ | Operations Data Analyst Intern 🆕 | Data & ML/AI | Valley NE | Oct 26, 2026 | [Apply](https://valmont.wd1.myworkdayjobs.com/ValmontCareers/job/Valley-NE/Operations-Data-Analyst-Intern_R29224) |
| ConnectPrep | Data Analyst Internship 🇺🇸 🏠 🆕 | Data & ML/AI | Washington +2 more | Oct 25, 2026 | [Apply](https://apply.workable.com/connectprep/j/1AF4F8C65F/) |
| ASML ✓ | Platform Software Engineer In Test ( Internship) | Software | San Jose, CA, USA | Oct 23, 2026 | [Apply](https://asml.wd3.myworkdayjobs.com/asmlext1/job/San-Jose-CA-USA/Platform-Software-Engineer-In-Test---Internship-_J-00354558) |
| Flagship Pioneering | ProFound Therapeutics: AI/ML Engineering - SAGE Platform Co-Op | Data & ML/AI | Cambridge, MA USA | Oct 23, 2026 | [Apply](https://job-boards.greenhouse.io/fspco-op012325/jobs/8911276002) |
| Path Robotics ✓ | Manufacturing Design Engineering Internship | Hardware | Columbus, Ohio | Oct 23, 2026 | [Apply](https://boards.greenhouse.io/pathrobotics/jobs/8911570002?gh_jid=8911570002) |
| Arcadis ✓ | Structural Engineer Intern | Hardware | Toledo, OH, United States | Oct 23, 2026 | [Apply](https://ebcs.fa.em2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/45422) |
| Zachry Group | Civil/Structural Engineering -Intern | Hardware | Charlotte, NC, United States | Oct 23, 2026 | [Apply](https://fa-evfm-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1029/job/16176) |
| Bertelsmann | Data Science Intern | Data & ML/AI | New York, New York (NY), United States | Oct 23, 2026 | [Apply](https://jobs.smartrecruiters.com/Bertelsmann-Jobs/744000157546634) |
| ASML ✓ | Internship - Application Software QA Engineer | Software | San Jose, CA, USA | Oct 23, 2026 | [Apply](https://asml.wd3.myworkdayjobs.com/asmlext1/job/San-Jose-CA-USA/Internship---Application-Software-QA-Engineer_J-00354565) |
| ASML ✓ | Internship - Software Engineer In Test (MOD) | Software | San Jose, CA, USA | Oct 23, 2026 | [Apply](https://asml.wd3.myworkdayjobs.com/asmlext1/job/San-Jose-CA-USA/Internship---Software-Engineer-In-Test--MOD-_J-00354568) |
| Copart ✓ | Software Engineering Intern | Software | Dallas, TX - Headquarters | Oct 23, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR111861) |
| Gorbel | Manufacturing Engineer Co-Op | Hardware | USA, New York, Victor | Oct 23, 2026 | [Apply](https://gorbel.wd501.myworkdayjobs.com/gorbelcareers/job/USA-New-York-Victor/Manufacturing-Engineer-Co-Op_REQ-2026-2330-1) |
| KLA ✓ | Software Engineering Intern | Software | Milpitas, CA | Oct 23, 2026 | [Apply](https://kla.wd1.myworkdayjobs.com/Search/job/Milpitas-CA/Software-Engineering-Intern_2642189-1) |
| Koppers | Financial Data Analyst Intern | Data & ML/AI | Peachtree City, GA | Oct 23, 2026 | [Apply](https://koppers.wd5.myworkdayjobs.com/Koppers/job/Peachtree-City-GA/Financial-Data-Analyst-Intern_REQ03221) |
| Nike ✓ | Converse AI Enablement Graduate Internship | Data & ML/AI | Boston, Massachusetts | Oct 23, 2026 | [Apply](https://nike.wd1.myworkdayjobs.com/nke/job/Boston-Massachusetts/Converse-AI-Enablement-Graduate-Internship_R-96256) |
| ZOLL Medical Corporation | Manufacturing Engineering Intern | Hardware | US CA San Jose | Oct 23, 2026 | [Apply](https://zoll.wd5.myworkdayjobs.com/ZOLLMedicalCorp/job/US-CA-San-Jose/Manufacturing-Engineering-Intern_R20619) |
| Olsson | Student Internship - Network and Server Infrastructure | Software | Lincoln, NE | Oct 23, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5462183008) |
| Bosch | Agentic AI R&D Intern | Data & ML/AI | Sunnyvale, CA, United States | Oct 23, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000157483412) |
| Astera Labs ✓ | Mechanical Solutions Architect Intern | Hardware | San Jose, CA | Oct 22, 2026 | [Apply](https://job-boards.greenhouse.io/asteraearlycareer2027/jobs/4746898005) |
| Palantir ✓ | Forward Deployed Software Engineer, Internship - Warp Speed 🇺🇸 | Software | New York, NY | Oct 22, 2026 | [Apply](https://jobs.lever.co/palantir/b3d81928-6c26-432f-8a0a-36602c2eefcb) |
| RESPEC | Student Engineering Intern (Mechanical or Electrical) | Hardware | Anchorage, AK, United States | Oct 22, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000157237049) |
| Dematic ✓ | Software Analytics Co-op | Data & ML/AI | Grand Rapids, MI, United States | Oct 22, 2026 | [Apply](https://kiongroup.wd3.myworkdayjobs.com/kion_scs/job/Grand-Rapids-MI-United-States/Software-Analytics-Co-op_JR-0096723) |
| Insperity ✓ | Rotational AI Intern | Data & ML/AI | Kingwood, TX | Oct 22, 2026 | [Apply](https://insperity.wd12.myworkdayjobs.com/NSP/job/Kingwood-TX/Rotational-AI-Intern_JR103460) |
| M&T Bank ✓ | Technology Intern - Software Engineering (Enterprise API Services Development Team) 🛂 | Software | Buffalo, NY | Oct 22, 2026 | [Apply](https://mtb.wd5.myworkdayjobs.com/Campus/job/Buffalo-NY/Technology-Intern---Software-Engineering--Enterprise-API-Services-Development-Team-_R90812) |
| Trimble ✓ | People Development AI & Digital Learning Intern | Data & ML/AI | US - CO, Westminster | Oct 22, 2026 | [Apply](https://trimble.wd1.myworkdayjobs.com/TrimbleCareers/job/US---CO-Westminster/People-Development-AI---Digital-Learning-Intern_R57819) |
| ZOLL Medical Corporation | Manufacturing Engineering Intern | Hardware | US CA San Jose | Oct 22, 2026 | [Apply](https://zoll.wd5.myworkdayjobs.com/ZOLLMedicalCorp/job/US-CA-San-Jose/Manufacturing-Engineering-Intern_R20618) |
| OpenArt AI | Early Adopter & Product Builder Intern, Creative AI | Data & ML/AI | San Carlos, California, USA | Oct 22, 2026 | [Apply](https://jobs.ashbyhq.com/openart/8dd52ba6-a5b6-40b1-95fe-50de352fa254) |
| Cummins ✓ | Manufacturing Co-Op Positions | Hardware | Columbus, IN, United States | Oct 22, 2026 | [Apply](https://fa-espx-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2439835) |
| Teledyne | Mechanical Engineering Intern - CW | Hardware | US - Wilsonville, OR | Oct 22, 2026 | [Apply](https://flir.wd1.myworkdayjobs.com/flircareers/job/US---Wilsonville-OR/Mechanical-Engineering-Intern---CW_REQ37514) |
| Metalenz | Camera Software Intern | Software | Boston, MA | Oct 21, 2026 | [Apply](https://jobs.ashbyhq.com/metalenz/979c12dd-e71a-41b5-9c5f-a0d7204a22f6) |
| Walrus | Full Stack Developer Intern 🛂 | Software | New York City (Hybrid) | Oct 21, 2026 | [Apply](https://jobs.ashbyhq.com/walrusfi/7dd09f17-cfff-48d8-8e4e-c3e016fe8cf5) |
| AECOM ✓ | Digital Infrastructure / Telecommunications Engineering Intern | Software | Philadelphia, PA, United States | Oct 21, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000156887619) |
| BorgWarner | Mechanical Design Engineer Summer Intern 🛂 | Hardware | Kokomo Technical Center - Indiana - USA | Oct 21, 2026 | [Apply](https://borgwarner.wd5.myworkdayjobs.com/BorgWarner_Careers/job/Kokomo-Technical-Center---Indiana---USA/Mechanical-Design-Engineer-Summer-Intern_R2026-4198) |
| Daimler Truck ✓ | BEV Systems Engineering Intern — Energy, Thermal & Analytics Intern | Data & ML/AI | Portland, OR US | Oct 21, 2026 | [Apply](https://dtna.wd5.myworkdayjobs.com/DTNA_external/job/Portland-OR-US/BEV-Systems-Engineering-Intern---Energy--Thermal---Analytics-Intern_DT-20328) |
| Daimler Truck ✓ | Vehicle Electronics Programming Station Intern | Software | Portland, OR US | Oct 21, 2026 | [Apply](https://dtna.wd5.myworkdayjobs.com/DTNA_external/job/Portland-OR-US/Vehicle-Electronics-Programming-Station-Intern_DT-20337) |
| Hitachi Energy ✓ | Software Engineering Co-op | Software | Liberty, South Carolina, United States | Oct 21, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Liberty-South-Carolina-United-States/Software-Engineering-Co-op_R0148733) |
| Whataburger | Data Scientist Intern | Data & ML/AI | 300 Concord Plaza Dr San Antonio TX 782… | Oct 21, 2026 | [Apply](https://whataburger.wd5.myworkdayjobs.com/WAB_CAREERS/job/300-Concord-Plaza-Dr-San-Antonio-TX-78216-6903/Data-Scientist-Intern_JR10014201) |
| Avav | Machine Learning Engineering Intern 🇺🇸 | Data & ML/AI | Centreville, VA | Oct 20, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Centreville-VA/Machine-Learning-Engineering-Intern_8941) |
| Avav | Software Engineering Intern 🇺🇸 | Software | Minneapolis, MN | Oct 20, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/Minneapolis-MN/Software-Engineering-Intern_8940) |
| Avav | Software Engineering Intern 🇺🇸 | Software | San Diego, CA | Oct 20, 2026 | [Apply](https://avav.wd1.myworkdayjobs.com/avav/job/San-Diego-CA/Software-Engineering-Intern_8828) |
| Micron Technology ✓ | Intern - Machine Learning Engineering | Data & ML/AI | Richardson, TX | Oct 20, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Richardson-TX/Intern---Machine-Learning-Engineering_JR114750) |
| Tranetechnologies | Industrial Engineering & Manufacturing Execution Systems Co-op | Hardware | La Crosse, Wisconsin | Oct 20, 2026 | [Apply](https://tranetechnologies.wd12.myworkdayjobs.com/trane_technologies_careers/job/La-Crosse-Wisconsin/Industrial-Engineering---Manufacturing-Execution-Systems-Co-op_JR-10172) |
| RESPEC | Student Engineering Intern (Structural) | Hardware | Morgantown, WV, United States | Oct 20, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000156644855) |
| American Electric Power ✓ | Data Scientist Intern | Data & ML/AI | Columbus, OH | Oct 20, 2026 | [Apply](https://aep.wd1.myworkdayjobs.com/AEPCareerSite/job/Columbus-OH/Data-Scientist-Intern---Columbus--OH_R20499) |
| Micron Technology ✓ | Intern - SMAI Probe AI Engineer | Data & ML/AI | Boise, ID - Main Site | Oct 20, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Boise-ID---Main-Site/Intern---SMAI-Probe-AI-Engineer_JR114094) |
| Insomniac Games | Engine and Tools Programming Intern – Undergraduate | Software | United States, Burbank, CA | Oct 20, 2026 | [Apply](https://job-boards.greenhouse.io/insomniac/jobs/6227080004) |
| BorgWarner | Application Mechanical Co-Op | Hardware | Auburn Hills - Michigan - USA | Oct 20, 2026 | [Apply](https://borgwarner.wd5.myworkdayjobs.com/BorgWarner_Careers/job/Auburn-Hills---Michigan---USA/Application-Mechanical-Co-Op_R2026-4100) |
| Constellation Brands | Intern, AI Enablement | Data & ML/AI | Rochester, New York | Oct 20, 2026 | [Apply](https://cbrands.wd5.myworkdayjobs.com/CBI_External_Careers/job/Rochester-New-York/Intern--AI-Enablement_R-41526) |
| FOX | Manufacturing Engineering Intern | Hardware | US, MI, Coldwater | Oct 20, 2026 | [Apply](https://foxfactory.wd1.myworkdayjobs.com/FOX/job/US-MI-Coldwater/Manufacturing-Engineering-Intern_JR113146) |
| Werner ✓ | Information Security Intern | Security | Omaha, NE | Oct 19, 2026 | [Apply](https://werner.wd501.myworkdayjobs.com/werner/job/Omaha-NE/Information-Security-Intern_JR23746) |
| Braze ✓ | Intern, Software Engineering | Software | New York City | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/braze/jobs/8301086) |
| Palantir ✓ | Software Engineer, Internship - Query Engines | Software | New York, NY | Oct 19, 2026 | [Apply](https://jobs.lever.co/palantir/da774f81-c98c-4dcf-9b9c-949fd7d90a13) |
| Emerson Electric | Mechanical Engineer Co-op July-December 🛂 | Hardware | Mansfield, MA, United States | Oct 19, 2026 | [Apply](https://hdjq.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26012073) |
| Lumentum ✓ | Internship - Mechanical Engineer | Hardware | USA - CA - San Jose (Ridder) | Oct 19, 2026 | [Apply](https://lumentum.wd5.myworkdayjobs.com/LITE/job/USA---CA---San-Jose-Ridder/Internship---Mechanical-Engineer_20261465) |
| National Information Solutions Cooperative (NISC) | Intern - Application Analyst (Financials Software) | Software | Mandan, ND | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/nisc/jobs/8301304) |
| American Fidelity | Software Developer Innovation Internship (OKC Local) | Software | Oklahoma City, Oklahoma | Oct 19, 2026 | [Apply](https://americanfidelity.wd5.myworkdayjobs.com/External/job/Oklahoma-City-Oklahoma/Software-Developer-Innovation-Internship_JR1118) |
| Badger Meter | Industrial Engineering Intern | Hardware | US - WI - Milwaukee HQ | Oct 19, 2026 | [Apply](https://badgermeter.wd5.myworkdayjobs.com/US_CareerSite/job/US---WI---Milwaukee-HQ/Continuous-Improvement-Intern_4634) |
| Cognex ✓ | Software Engineering Intern | Software | Wauwatosa, Wisconsin | Oct 19, 2026 | [Apply](https://cognex.wd1.myworkdayjobs.com/External_Career_Site/job/Wauwatosa-Wisconsin/Software-Engineering-Intern_R0012549) |
| Manhattan Associates ✓ | A.I. Developer Co-Op (Boston, MA) | Software | US - Home Office | Oct 19, 2026 | [Apply](https://manh.wd5.myworkdayjobs.com/campus/job/US---Home-Office/AI-Developer-Co-Op--Boston--MA-_17046) |
| Bracebridge Capital | Northeastern University Software Engineer - Application Development Co-op | Software | Boston, MA | Oct 19, 2026 | [Apply](https://job-boards.greenhouse.io/bracebridgecapital/jobs/4745001005) |
| Bosch | AI Research Intern: Wireless Foundation Models | Data & ML/AI | Pittsburgh, PA, United States | Oct 19, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000156323136) |
| Allegion | Summer Intern - Manufacturing Quality | Hardware | Greenfield, IN - West 350N | Oct 19, 2026 | [Apply](https://allegion.wd5.myworkdayjobs.com/careers/job/Greenfield-IN---West-350N/Summer-Intern---Manufacturing-Quality_JR37499-1) |
| AgZen | Software Engineering Co-op | Software | Somerville, MA | Oct 16, 2026 | [Apply](https://jobs.ashbyhq.com/agzen/4cff4edd-3e9a-4ea1-8138-80c7241a2d3a) |
| Gilead Sciences ✓ | Intern - Research - Clinical Virology - AI | Data & ML/AI | United States - California - Foster City | Oct 16, 2026 | [Apply](https://gilead.wd1.myworkdayjobs.com/gileadcareers/job/United-States---California---Foster-City/Intern---Research---Clinical-Virology---AI_R0055526) |
| Rockwell Automation ✓ | Intern, Firmware Engineering 🛂 | Hardware | Milwaukee, Wisconsin, United States | Oct 16, 2026 | [Apply](https://rockwellautomation.wd1.myworkdayjobs.com/External_Rockwell_Automation/job/Milwaukee-Wisconsin-United-States/Intern--Firmware-Engineering_R26-7922-1) |
| Nokia ✓ | Mechanical Packaging Engineer Co-op | Hardware | United States | Oct 16, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/40850) |
| Booz Allen ✓ | University, Software Engineer Intern 🇺🇸 | Software | Fayetteville, NC | Oct 16, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/Fayetteville-NC/University--Software-Engineer-Intern_R0251802) |
| Entrust | Mechanical CAD Designer  Internship | Hardware | United States - Shakopee, MN (GHQ) | Oct 16, 2026 | [Apply](https://entrust.wd1.myworkdayjobs.com/entrustcareers/job/United-States---Shakopee-MN-GHQ/Mechanical-CAD-Designer--Internship_R004435) |
| Entrust | Mechanical Engineering Co-Op | Hardware | United States - Shakopee, MN (GHQ) | Oct 16, 2026 | [Apply](https://entrust.wd1.myworkdayjobs.com/entrustcareers/job/United-States---Shakopee-MN-GHQ/Mechanical-Engineering-Co-Op_R004415) |
| Entrust | Software Engineering Co-op | Software | United States - Shakopee, MN (GHQ) | Oct 16, 2026 | [Apply](https://entrust.wd1.myworkdayjobs.com/entrustcareers/job/United-States---Shakopee-MN-GHQ/Software-Engineering-Co-op_R004425) |
| Wellmark ✓ | Software Engineer Internship – Technology Health Plan | Software | Des Moines, IA, United States | Oct 16, 2026 | [Apply](https://jobs.smartrecruiters.com/WellmarkInc/744000156043218) |
| KLA ✓ | Opto-Mechanical Intern | Hardware | Ann Arbor, MI | Oct 16, 2026 | [Apply](https://kla.wd1.myworkdayjobs.com/Search/job/Ann-Arbor-MI/Opto-Mechanical-Intern_2641704) |
| Aidashinc | Software Engineering Intern, Backend | Software | Palo Alto, California, United States | Oct 15, 2026 | [Apply](https://job-boards.greenhouse.io/aidashinc/jobs/4436057009) |
| Duolingo ✓ | Data Scientist, Intern | Data & ML/AI | New York, NY; Pittsburgh, PA | Oct 15, 2026 | [Apply](https://careers.duolingo.com/jobs/8888721002?gh_jid=8888721002) |
| Duolingo ✓ | Data Scientist, Intern | Data & ML/AI | Pittsburgh, PA; New York, NY | Oct 15, 2026 | [Apply](https://job-boards.greenhouse.io/duolingounirecruitment/jobs/8888785002) |
| Leidos ✓ | Performance Enablement AI/ML Intern 🇺🇸 🏠 | Data & ML/AI | 6314 Remote/Teleworker US | Oct 15, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/6314-RemoteTeleworker-US/Performance-Enablement-AI-ML-Intern_R-00194656) |
| ROCKWOOL Group | Associate Product Management Intern | Software | Chicago, Illinois | Oct 15, 2026 | [Apply](https://rockwoolgroup.wd3.myworkdayjobs.com/ROCKWOOL/job/Chicago-Illinois/Associate-Product-Management-Intern_R0036805-2) |
| EMC Insurance | Cybersecurity Intern | Security | Iowa | Oct 15, 2026 | [Apply](https://emcins.wd5.myworkdayjobs.com/EMC_Careers/job/Iowa/Cybersecurity-Intern_R6590) |
| Nordson | Manufacturing Engineer Intern | Hardware | USA - South Carolina - Clinton | Oct 15, 2026 | [Apply](https://nordsonhcm.wd501.myworkdayjobs.com/nordsoncareers/job/USA---South-Carolina---Clinton/Manufacturing-Engineer-Intern_REQ53354) |
| Astreya | AI Infrastructure DC Design Intern 🏠 | Data & ML/AI | Remote, CA | Oct 14, 2026 | [Apply](https://astreya.wd5.myworkdayjobs.com/life-at-astreya-opportunities/job/Remote-CA/AI-Infrastructure-DC-Design-Intern_R0017927) |
| Astreya | AI Infrastructure DC Design Intern 🏠 | Data & ML/AI | Remote, CA | Oct 14, 2026 | [Apply](https://astreya.wd5.myworkdayjobs.com/life-at-astreya-opportunities/job/Remote-CA/AI-Infrastructure-DC-Design-Intern_R0017929) |
| Astreya | AI Infrastructure DC Design Intern 🏠 | Data & ML/AI | Remote, CA | Oct 14, 2026 | [Apply](https://astreya.wd5.myworkdayjobs.com/life-at-astreya-opportunities/job/Remote-CA/AI-Infrastructure-DC-Design-Intern_R0017931) |
| Weld County | Community Health Intern - Mobile Unit Evaluation | Software | Greeley, CO | Oct 14, 2026 | [Apply](https://weldgov.wd5.myworkdayjobs.com/WeldCountyCareers/job/Greeley-CO/Community-Health-Intern---Mobile-Unit-Evaluation_JR102729) |
| RESPEC | Student Engineering Intern (Structural) | Hardware | Anchorage, AK, United States | Oct 14, 2026 | [Apply](https://jobs.smartrecruiters.com/RESPECInc/744000155538719) |
| Tenstorrent ✓ | Systems Intern - Validation, Software, Design, Architecture & Packaging (USA) | Software | Austin +5 more | Oct 14, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5264424007) |
| Syska Hennessy Group | Mechanical Engineer Summer Intern | Hardware | Tampa, FL | Oct 13, 2026 | [Apply](https://job-boards.greenhouse.io/syskahennessy/jobs/8267624) |
| KLA ✓ | Computer Vision/Machine Learning Intern | Data & ML/AI | Milpitas, CA | Oct 13, 2026 | [Apply](https://kla.wd1.myworkdayjobs.com/Search/job/Milpitas-CA/Computer-Vision-Machine-Learning-Intern_2641921-1) |
| Bose ✓ | Audio Machine Learning Co-op | Data & ML/AI | US, MA - Framingham | Oct 13, 2026 | [Apply](https://boseallaboutme.wd503.myworkdayjobs.com/Bose_Careers/job/US-MA---Framingham/Audio-Machine-Learning-Co-op_R29274) |
| Bose ✓ | Embedded Audio ML Engineer Co-op | Data & ML/AI | US, MA - Framingham | Oct 13, 2026 | [Apply](https://boseallaboutme.wd503.myworkdayjobs.com/Bose_Careers/job/US-MA---Framingham/Audio-Machine-Learning-Engineer-Co-op_R28719) |
| Cboe ✓ | Software Engineer Intern (C++) 🛂 | Software | Kansas City, MO | Oct 12, 2026 | [Apply](https://cboe.wd1.myworkdayjobs.com/External_Career_CBOE/job/Kansas-City-MO/Software-Engineer-Intern--C---_R-4726) |
| Azul Systems | IT Intern, AI and Operations | Data & ML/AI | Sunnyvale, CA | Oct 12, 2026 | [Apply](https://jobs.lever.co/azul/8f41ceaf-8835-4fc7-ba57-9384487d59db) |
| Arcesium ✓ | Product Management Intern | Software | New York | Oct 12, 2026 | [Apply](https://job-boards.greenhouse.io/arcesiumllc/jobs/5257266007) |
| Astera Labs ✓ | CyberSecurity Engineer Intern | Security | San Jose, CA | Oct 12, 2026 | [Apply](https://job-boards.greenhouse.io/asteraearlycareer2027/jobs/4743021005) |
| Bosch | Information Security and Privacy Intern | Security | Farmington Hills, MI, United States | Oct 12, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000155120934) |
| Life Fitness ✓ | Product Management Intern | Software | Rosemont, IL | Oct 12, 2026 | [Apply](https://lifefitness.wd1.myworkdayjobs.com/searchLFN/job/Rosemont-IL/Product-Management-Intern_JR-025280) |
| Life Fitness ✓ | Android Software Intern | Software | Schaumburg, IL 60173 | Oct 12, 2026 | [Apply](https://lifefitness.wd1.myworkdayjobs.com/searchLFN/job/Schaumburg-IL-60173/Android-Software-Intern_JR-025277) |
| Life Fitness ✓ | Embedded Software Intern | Software | Schaumburg, IL 60173 | Oct 12, 2026 | [Apply](https://lifefitness.wd1.myworkdayjobs.com/searchLFN/job/Schaumburg-IL-60173/Embedded-Software-Intern_JR-025276) |
| Niagara Bottling ✓ | Manufacturing Intern - Las Vegas | Hardware | Las Vegas - North Las Vegas, NV | Oct 12, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Las-Vegas---North-Las-Vegas-NV/Manufacturing-Intern---Las-Vegas_R56789) |
| Tencent ✓ | Data Science Intern | Data & ML/AI | US-California-Palo Alto | Oct 11, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/Data-Science-Intern_R108213) |
| C&S Wholesale Grocers ✓ | IS Internship - Data Analytics & Data Science | Data & ML/AI | Edison, NJ | Oct 11, 2026 | [Apply](https://cswg.wd1.myworkdayjobs.com/cs_careers/job/Edison-NJ/IS-Internship---Data-Analytics---Data-Science_R-268963) |
| Micron Technology ✓ | Intern - IT Software Engineer | Software | Boise, ID - Main Site | Oct 09, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Boise-ID---Main-Site/Intern---IT-Software-Engineer_JR113941) |
| Arcesium ✓ | Software Engineer Intern | Software | New York | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/arcesiumllc/jobs/5257176007) |
| Olsson | Structural Engineering Internship - Facilities | Hardware | Dallas, TX; Fort Worth, TX | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/olsson/jobs/5441485008) |
| Alcon ✓ | Clinical Data Science Intern 🛂 | Data & ML/AI | Fort Worth, Texas | Oct 09, 2026 | [Apply](https://alcon.wd5.myworkdayjobs.com/careers_alcon/job/Fort-Worth-Texas/Clinical-Data-Science-Intern_R-2026-50204) |
| Arcesium ✓ | Infrastructure Engineer Intern | Software | New York | Oct 09, 2026 | [Apply](https://job-boards.greenhouse.io/arcesiumllc/jobs/5257199007) |
| Aptiv ✓ | Embedded Software - Engineering Intern 🇺🇸 | Software | USA Walnut Creek, CA - WR | Oct 09, 2026 | [Apply](https://aptiv.wd5.myworkdayjobs.com/aptiv_careers/job/USA-Walnut-Creek-CA---WR/Embedded-Software---Engineering-Intern_J000704386) |
| Aptiv ✓ | Intern - Compiler Team | Software | USA Walnut Creek, CA - WR | Oct 09, 2026 | [Apply](https://aptiv.wd5.myworkdayjobs.com/aptiv_careers/job/USA-Walnut-Creek-CA---WR/Intern---Compiler-Team_J000704385) |
| Aurora Innovation ✓ | AI Engineer Intern 🆕 | Data & ML/AI | Mountain View, CA | Oct 08, 2026 | [Apply](https://jobs.ashbyhq.com/aurora-operations-inc/475a24d7-a058-4f86-be8f-fd6be679af9c) |
| Perpay | Super Day - Data Science Internship | Data & ML/AI | Philadelphia +2 more | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/perpay/jobs/5260960007) |
| Wabtec ✓ | Mechanical Engineer Intern - Production Operations | Hardware | Oak Creek, WI, United States | Oct 08, 2026 | [Apply](https://jobs.smartrecruiters.com/Wabtec/3743990016001786) |
| Wabtec ✓ | Mechanical Engineer Intern - New Product Development | Hardware | Oak Creek, WI, United States | Oct 08, 2026 | [Apply](https://jobs.smartrecruiters.com/Wabtec/3743990016001927) |
| Booz Allen ✓ | University, Applied AI Software Development Intern 🇺🇸 | Data & ML/AI | McLean, VA | Oct 08, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/McLean-VA/University--Applied-AI-Software-Development-Intern_R0251314) |
| Johnson & Johnson | AI Excellence, Decision Enablement Intern | Data & ML/AI | Spring House +2 more | Oct 08, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Spring-House-Pennsylvania-United-States-of-America/AI-Excellence--Decision-Enablement-Intern_R-102881) |
| Syska Hennessy Group | Mechanical Engineering Summer Intern | Hardware | Hamilton, NJ | Oct 08, 2026 | [Apply](https://job-boards.greenhouse.io/syskahennessy/jobs/8177728) |
| GenBio AI | Research Scientist Intern, AI Molecular Design | Data & ML/AI | Palo Alto, CA | Oct 08, 2026 | [Apply](https://jobs.lever.co/genbio/7d0b5764-48ce-4d06-93d2-431742d35604) |
| Cox | Data Scientist Co-op | Data & ML/AI | Atlanta GA | Oct 08, 2026 | [Apply](https://cox.wd1.myworkdayjobs.com/Cox_External_Career_Site_1/job/Atlanta-GA/Data-Scientist-Co-op_R202683033) |
| Gordon Food Service ✓ | Software Engineer Intern (Transportation Routing ) | Software | Wyoming, Michigan | Oct 08, 2026 | [Apply](https://gfs.wd5.myworkdayjobs.com/usjobs-gen-gfs/job/Wyoming-Michigan/Software-Engineer-Intern--Transportation-Routing--_R-58374) |
| Leidos ✓ | Systems, Integration and Software Engineer Intern 🇺🇸 | Software | Atlantic City, NJ | Oct 08, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Atlantic-City-NJ/Systems--Integration-and-Software-Engineer-Intern_R-00194152) |
| Tranetechnologies | Mechanical Engineering Co-op | Hardware | Grand Rapids, Michigan | Oct 07, 2026 | [Apply](https://tranetechnologies.wd12.myworkdayjobs.com/trane_technologies_careers/job/Grand-Rapids-Michigan/Mechanical-Engineering-Co-op_JR-8957) |
| Axos Bank | AI Engineer Intern | Data & ML/AI | HQ - San Diego, CA | Oct 07, 2026 | [Apply](https://axos.wd5.myworkdayjobs.com/Axos/job/HQ---San-Diego-CA/AI-Engineer-Intern_JR5658) |
| Axos Bank | Software Development Intern | Software | HQ - San Diego, CA | Oct 07, 2026 | [Apply](https://axos.wd5.myworkdayjobs.com/Axos/job/HQ---San-Diego-CA/Software-Development-Intern_JR5647) |
| Northrop Grumman | San Diego Manufacturing Technician Intern - Fall 🇺🇸 | Hardware | United States-California-San Diego | Oct 07, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-California-San-Diego/San-Diego-Manufacturing-Technician-Intern---Fall_R10255107) |
| IMEG ✓ | Mechanical Co-op | Hardware | Raleigh, NC | Oct 07, 2026 | [Apply](https://wd1.myworkdaysite.com/recruiting/imeg/Imeg_Careers/job/Raleigh-NC/Mechanical-Co-op_R-16838) |
| Northrop Grumman | Chandler Manufacturing Technician Intern - Fall 🇺🇸 | Hardware | United States-Arizona-Chandler | Oct 07, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Arizona-Chandler/Chandler-Manufacturing-Technician-Intern---Fall_R10250966) |
| Northrop Grumman | Chandler Manufacturing Technician Intern (2nd Shift) - Fall 🇺🇸 | Hardware | United States-Arizona-Chandler | Oct 07, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Arizona-Chandler/Chandler-Manufacturing-Technician-Intern--2nd-Shift----Fall_R10254794) |
| Leidos ✓ | Business Systems AI Intern 🇺🇸 🏠 | Data & ML/AI | 6314 Remote/Teleworker US | Oct 07, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/6314-RemoteTeleworker-US/Business-Systems-AI-Intern_R-00193769) |
| Moss & Associates ✓ | Mechanical Administrator Internship | Hardware | FORT LAUDERDALE, FL | Oct 07, 2026 | [Apply](https://mosscm.wd1.myworkdayjobs.com/moss_careers/job/FORT-LAUDERDALE-FL/Mechanical-Administrator-Internship_R-3031) |
| Tenstorrent ✓ | AI Software Intern - Cloud, Infrastructure & Data Centre Deployment (USA) | Data & ML/AI | Austin +5 more | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5256686007) |
| Tenstorrent ✓ | Hardware Intern - Architecture, AI HW & SoC (USA) | Data & ML/AI | Austin +11 more | Oct 07, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5256691007) |
| Tranetechnologies | Manufacturing Engineering Intern | Hardware | Grand Rapids, Michigan | Oct 06, 2026 | [Apply](https://tranetechnologies.wd12.myworkdayjobs.com/trane_technologies_careers/job/Grand-Rapids-Michigan/Manufacturing-Engineering-Intern_JR-11703) |
| Nokia ✓ | AI Engineering Co-op | Data & ML/AI | United States | Oct 06, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/40566) |
| Badger Meter | Mechanical Engineering NPD Intern | Hardware | US - WI - Milwaukee HQ | Oct 06, 2026 | [Apply](https://badgermeter.wd5.myworkdayjobs.com/US_CareerSite/job/US---WI---Milwaukee-HQ/Mechanical-Engineering-NPD-Intern_4642) |
| Vantor | Summer Internship: Aerospace Modeling & Simulation 🇺🇸 | Hardware | Herndon, VA | Oct 06, 2026 | [Apply](https://maxar.wd1.myworkdayjobs.com/Vantor/job/Herndon-VA/Summer-Internship--Aerospace-Modeling---Simulation_R24758) |
| Axis Automation | GVSU Mechanical Engineering Intern Co-op | Hardware | Walker, Michigan, United States | Oct 06, 2026 | [Apply](https://job-boards.greenhouse.io/axiscompany/jobs/8871027002) |
| Allegion | Summer Intern - Product Management | Software | Carmel, IN | Oct 06, 2026 | [Apply](https://allegion.wd5.myworkdayjobs.com/careers/job/Carmel-IN/Summer-Intern---Product-Management_JR37369-1) |
| Field AI | Mechanical Engineer, Robotics Hardware Intern | Hardware | Boston, MA | Oct 06, 2026 | [Apply](https://jobs.lever.co/field-ai/5ae428f8-ac13-49b2-a244-fb97d31bfc79) |
| Atoms | Manufacturing Intern | Hardware | San Francisco, CA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/atoms/jobs/8868917002) |
| Hewlett Packard Enterprise ✓ | Cloud Developer Intern | Software | San Jose +2 more | Oct 05, 2026 | [Apply](https://hpe.wd5.myworkdayjobs.com/Jobsathpe/job/San-Jose-California-United-States-of-America/Cloud-Developer-Intern_1214950) |
| TensorWave | Developer Community Engagement Intern | Software | Las Vegas, Nevada | Oct 05, 2026 | [Apply](https://jobs.ashbyhq.com/tensorwave/34dd183d-4423-40e3-bb6d-790b5dafc731) |
| TensorWave | Software Engineering Intern | Software | Las Vegas, Nevada | Oct 05, 2026 | [Apply](https://jobs.ashbyhq.com/tensorwave/39091eeb-13fc-46a7-b7e5-0d4584ac53ab) |
| TensorWave | Security Engineer Intern | Security | Las Vegas, Nevada | Oct 05, 2026 | [Apply](https://jobs.ashbyhq.com/tensorwave/8ec8b715-f9ad-48a7-869e-ed9d455119a5) |
| Atoms | Manufacturing Intern | Hardware | San Francisco, CA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/cssmerge/jobs/8868918002) |
| Found Energy | Data Engineer Co-op | Data & ML/AI | Cambridge, MA | Oct 05, 2026 | [Apply](https://job-boards.greenhouse.io/foundenergy/jobs/4719227006) |
| Graco | Cybersecurity Intern 🛂 | Security | Dayton, Minnesota, USA (French Lake) | Oct 05, 2026 | [Apply](https://graco.wd501.myworkdayjobs.com/Graco_Careers/job/Dayton-Minnesota-USA-French-Lake/Cybersecurity-Intern_R0023516) |
| BorgWarner | Manufacturing Process Engineering Intern 🛂 | Hardware | Kokomo Technical Center - Indiana - USA | Oct 05, 2026 | [Apply](https://borgwarner.wd5.myworkdayjobs.com/BorgWarner_Careers/job/Kokomo-Technical-Center---Indiana---USA/Manufacturing-Process-Engineering-Intern_R2026-3943-1) |
| RTX | Co-Op - AI DSP Applied Research 🇺🇸 | Data & ML/AI | US-IA-CEDAR RAPIDS-108 ~ 400 Collins Rd… | Oct 03, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-108--400-Collins-Rd-NE--BLDG-108/Co-Op---AI-DSP-Applied-Research_01873016) |
| Wabtec ✓ | Transducer Manufacturing Engineering Co-Op | Hardware | Waltham, MA, United States | Oct 02, 2026 | [Apply](https://jobs.smartrecruiters.com/Wabtec/3743990015874986) |
| AECOM ✓ | Structural Engineering Co-Op - Buildings | Hardware | Boston, MA, United States | Oct 02, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000153254989) |
| Trimble ✓ | Agriculture Product Management Intern 🛂 | Software | US - CO, Westminster | Oct 02, 2026 | [Apply](https://trimble.wd1.myworkdayjobs.com/TrimbleCareers/job/US---CO-Westminster/Product-Management-Intern_R57893) |
| ShopBack | Software Engineer Intern | Software | San Francisco, California | Oct 02, 2026 | [Apply](https://jobs.lever.co/shopback-2/640ac3fb-dae5-4738-95b9-9cb80cc7ad15) |
| ShopBack | Software Engineer Intern | Software | New York City, New York | Oct 02, 2026 | [Apply](https://jobs.lever.co/shopback-2/e5f5e276-e7f7-43e0-a224-5259d242fe98) |
| The Toro Company | Mechatronics Engineering Co-Op | Hardware | Bloomington, MN | Oct 02, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Bloomington-MN/Mechatronics-Engineering-Co-Op_JR17153) |
| ZOLL Medical Corporation | Manufacturing Engineering Co-op | Hardware | Pawtucket, RI | Oct 02, 2026 | [Apply](https://zoll.wd5.myworkdayjobs.com/ZOLLMedicalCorp/job/Pawtucket-RI/Manufacturing-Engineering-Co-op_R20367) |
| Profluent | Intern, Software Engineering | Software | Emeryville, California, United States | Oct 02, 2026 | [Apply](https://job-boards.greenhouse.io/profluent/jobs/5441955008) |
| American Bankers Association | Intern, Cybersecurity Policy Analyst | Security | US DC Main Office | Oct 01, 2026 | [Apply](https://aba.wd1.myworkdayjobs.com/aba/job/US-DC-Main-Office/Intern--Cybersecurity-Policy-Analyst_R611) |
| Range | Software Engineering Intern | Software | McLean, VA | Oct 01, 2026 | [Apply](https://jobs.ashbyhq.com/range/5fe3697d-b5b3-4772-9de4-1551cb726718) |
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
| Wellmark ✓ | Software Engineer Internship – Metadata Enablement Team | Software | Des Moines, IA, United States | Sep 30, 2026 | [Apply](https://jobs.smartrecruiters.com/WellmarkInc/744000152679699) |
| RTX | Manufacturing Engineer Intern - 1st shift - On site - Aeroestructuras | Hardware | MX-BCN-MEXICALI-238 ~ Blvd Venustiano Carranza #238 ~ BLDG 238 +1 more | Sep 30, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/MX-BCN-MEXICALI-238--Blvd-Venustiano-Carranza-238--BLDG-238-Desarrollo-Industrial-Colorado/Manufacturing-Engineer-Intern---1st-shift---On-site---Aeroestructuras_01872645) |
| Gilead Sciences ✓ | Intern - Research - Oncology Biomarker - AI | Data & ML/AI | United States - California - Foster City | Sep 29, 2026 | [Apply](https://gilead.wd1.myworkdayjobs.com/gileadcareers/job/United-States---California---Foster-City/Intern---Research---Oncology-Biomarker_R0054812) |
| Gilead Sciences ✓ | Intern - Research - Protein Therapeutics, Computational Biologics Engineering - AI | Data & ML/AI | United States - California - Foster City | Sep 29, 2026 | [Apply](https://gilead.wd1.myworkdayjobs.com/gileadcareers/job/United-States---California---Foster-City/Intern---Research---Protein-Therapeutics--Computational-Biologics-Engineering_R0054739) |
| Clay | Software Engineering Intern | Software | New York | Sep 29, 2026 | [Apply](https://jobs.ashbyhq.com/claylabs/5b7eced2-36bd-4265-a2a8-da0f786e47aa) |
| Plot Technologies | Co-op -- Applied AI | Data & ML/AI | New York City | Sep 29, 2026 | [Apply](https://jobs.ashbyhq.com/plot/5f8cfeaa-c368-480f-aaa5-de52452a63d0) |
| Johnson & Johnson | Manufacturing Execution Systems Co-op | Hardware | Raritan +2 more | Sep 29, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Raritan-New-Jersey-United-States-of-America/Manufacturing-Execution-Systems-Co-op_R-099373) |
| Moog | Intern, Software Engineering | Software | Torrance, CA | Sep 29, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Torrance-CA/Intern--Software-Engineering_R-26-19948) |
| Nike ✓ | NIKE, Inc. AI & Machine Learning, Innovation Graduate Internship | Data & ML/AI | Beaverton, Oregon | Sep 29, 2026 | [Apply](https://nike.wd1.myworkdayjobs.com/nke/job/Beaverton-Oregon/NIKE--Inc-AI---Machine-Learning--Innovation-Graduate-Internship_R-94412) |
| The Toro Company | Mechanical Design Engineer Co Op - BOSS Snowplow | Hardware | Iron Mountain, MI | Sep 29, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Iron-Mountain-MI/Mechanical-Design-Engineer-Co-Op---BOSS-Snowplow_JR17092) |
| Keenfinity | Software Engineering Intern | Software | Lincoln, NE, United States | Sep 28, 2026 | [Apply](https://jobs.smartrecruiters.com/Keenfinity/744000152241469) |
| Cummins ✓ | Structural, Dynamic and Acoustic Systems - Summer Internship Positions | Hardware | Columbus, IN, United States | Sep 28, 2026 | [Apply](https://fa-espx-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2437307) |
| Cummins ✓ | Structural, Dynamic and Acoustic Systems - Co-Op Positions | Hardware | Columbus, IN, United States | Sep 28, 2026 | [Apply](https://fa-espx-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2437754) |
| The Toro Company | Electrical/software Co-Op - BOSS Snowplow | Hardware | Iron Mountain, MI | Sep 28, 2026 | [Apply](https://ttc.wd1.myworkdayjobs.com/Toro_External_Careers/job/Iron-Mountain-MI/Electrical-software-Coop_JR17089) |
| Veolia | SAP & ServiceNow AI Automation Intern 🛂 | Data & ML/AI | Trevose, PA, United States | Sep 25, 2026 | [Apply](https://jobs.smartrecruiters.com/VeoliaEnvironnementSA/744000151947749) |
| Michael Baker International ✓ | Mechanical Engineering Intern | Hardware | Baltimore, MD, United States | Sep 25, 2026 | [Apply](https://ebxs.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/309935) |
| Cencora | EDI IT Software Developer Intern | Software | Conshohocken, PA | Sep 25, 2026 | [Apply](https://myhrabc.wd5.myworkdayjobs.com/Global/job/Conshohocken-PA/EDI-IT-Software-Developer-Intern_R2612376) |
| Heven AeroTech | Manufacturing Intern 🇺🇸 | Hardware | Winchester, Virginia | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/hevenaerotech/jobs/4410446009) |
| Aevex Aerospace | Robotics Engineering Co-op 🇺🇸 | Hardware | Tampa, Florida, United States | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/aevexaerospace/jobs/5415815008) |
| Reflect Orbital | Ground Software Engineering Intern | Software | Hawthorne, CA | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/c394615d-26c6-4435-ad84-3ca3269c2952) |
| Johnson & Johnson | Software Engineering Co-Op | Software | Danvers +2 more | Sep 24, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Danvers-Massachusetts-United-States-of-America/Software-Engineering-Co-Op_R-098277) |
| EQT Corporation | Water Infrastructure Engineering Intern | Software | Canonsburg, PA | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/eqtcorporation/jobs/5424757008) |
| Michael Baker International ✓ | Mechanical Engineering Intern | Hardware | Salt Lake City, UT, United States | Sep 24, 2026 | [Apply](https://ebxs.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/309936) |
| Wurl | Data Science Intern 🏠 | Data & ML/AI | Remote - United States | Sep 24, 2026 | [Apply](https://job-boards.greenhouse.io/wurljobs/jobs/4716249006) |
| Ramp ✓ | Software Engineering Intern, Frontend | Software | New York, NY (HQ) | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/ramp/a13ae586-f4cb-4385-8822-c42b9b54ed74) |
| Ramp ✓ | Software Engineering Intern, iOS | Software | New York, NY (HQ) | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/ramp/b66be397-240b-41a6-9b05-493299b270a9) |
| Ramp ✓ | Software Engineering Intern, Android | Software | New York, NY (HQ) | Sep 24, 2026 | [Apply](https://jobs.ashbyhq.com/ramp/fcf118cc-521a-4a62-9d13-945e5b6e3cb8) |
| ZipRecruiter ✓ | Software Engineer - Intern | Software | Santa Monica, CA | Sep 23, 2026 | [Apply](https://job-boards.greenhouse.io/ziprecruiter/jobs/8180455) |
| AECOM ✓ | Structural Engineering Intern - Hiring Event with AECOM - Philadelphia | Hardware | Philadelphia, PA, United States | Sep 23, 2026 | [Apply](https://jobs.smartrecruiters.com/AECOM2/744000151439229) |
| Keenfinity | Software Test Automation Co-Op | Software | Fairport, NY, United States | Sep 23, 2026 | [Apply](https://jobs.smartrecruiters.com/Keenfinity/744000151395769) |
| SWBC | Application Security Intern | Security | San Antonio, TX | Sep 23, 2026 | [Apply](https://swbc.wd1.myworkdayjobs.com/swbccareers/job/San-Antonio-TX/Application-Security-Intern_R0015572-2) |
| Vantor | AI Engineer Intern 🇺🇸 🏠 | Data & ML/AI | Remote (United States) | Sep 22, 2026 | [Apply](https://maxar.wd1.myworkdayjobs.com/Vantor/job/Remote-United-States/AI-Engineer-Intern_R24605) |
| Moog | Intern, Mechanical Analysis Engineering | Hardware | Buffalo, NY | Sep 22, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Mechanical-Analysis-Engineering_R-26-20226) |
| Cambridge Investment Research | IT Operations Intern - Service Desk, Infrastructure, Prod Support | Software | Fairfield, IA | Sep 21, 2026 | [Apply](https://cir.wd108.myworkdayjobs.com/CIR_External_Career_Site/job/Fairfield-IA/IT-Operations-Intern---Service-Desk--Infrastructure--Prod-Support_R-2025-235) |
| Collinear AI | MTS - Research Scientist Internship | Data & ML/AI | Sunnyvale, California | Sep 21, 2026 | [Apply](https://jobs.ashbyhq.com/collinear-ai/ae85fd08-dfd8-42e5-9b3b-9921ba24742b) |
| Acron Aviation | Software Engineer Intern - St. Pete Site | Software | St Petersburg, FL | Sep 18, 2026 | [Apply](https://jobs.lever.co/acronaviation/19dbac7d-b4fb-4d21-9247-dc610bf55fed) |
| Cambridge Investment Research | Consulting Services AI & Automation Intern | Data & ML/AI | Fairfield, IA | Sep 18, 2026 | [Apply](https://cir.wd108.myworkdayjobs.com/CIR_External_Career_Site/job/Fairfield-IA/Consulting-Services-AI---Automation-Intern_R-2025-223) |
| Gordon Food Service ✓ | Industrial / Mechanical / Electrical Engineer Internship | Hardware | Wyoming, Michigan | Sep 18, 2026 | [Apply](https://gfs.wd5.myworkdayjobs.com/usjobs-gen-gfs/job/Wyoming-Michigan/Industrial---Mechanical---Electrical-Engineer-Internship_R-57373) |
| Niagara Bottling ✓ | Manufacturing Intern - Milesburg | Hardware | Milesburg - Milesburg, PA | Sep 18, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Milesburg---Milesburg-PA/Manufacturing-Intern---Milesburg_R56065) |
| Astera Labs ✓ | Firmware Engineer Intern (Leo) | Hardware | San Jose, CA | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/asteraearlycareer2027/jobs/4731584005) |
| Ninjaholdings | Data Science Intern | Data & ML/AI | Chicago, IL | Sep 17, 2026 | [Apply](https://ninjaholdings.breezy.hr/p/85be8c78a2ba-data-science-intern) |
| XPENG Motors | AI Research Intern – Predictive World Model | Data & ML/AI | Santa Clara, CA | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/xpengmotors/jobs/8819001002) |
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
| Clockwork Systems | Software Engineer Intern | Software | Palo Alto, CA | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/clockworksystems/jobs/6174230004) |
| Thermo Fisher Scientific ✓ | Manufacturing Engineering Co-op | Hardware | Marietta, Ohio, USA | Sep 16, 2026 | [Apply](https://thermofisher.wd5.myworkdayjobs.com/ThermoFisherCareers/job/Marietta-Ohio-USA/Manufacturing-Engineering-Co-op_R-01366628) |
| Internrecruiting | Software Engineer Co-op | Software | Boston, MA | Sep 15, 2026 | [Apply](https://job-boards.greenhouse.io/internrecruiting/jobs/8204511) |
| Brevium | Software Engineer Intern | Software | American Fork, UT | Sep 15, 2026 | [Apply](https://job-boards.greenhouse.io/brevium/jobs/4713683006) |
| PerkinElmer | Data Science Intern, Asset Intelligence 🏠 | Data & ML/AI | US Remote - NY | Sep 15, 2026 | [Apply](https://newperkinelmer.wd1.myworkdayjobs.com/External/job/US-Remote---NY/Data-Science-Intern--Asset-Intelligence_REQ-058421) |
| Oshkosh | Manufacturing Simulation Intern | Hardware | McConnellsburg +2 more | Sep 15, 2026 | [Apply](https://oshkoshcorporation.wd5.myworkdayjobs.com/Oshkosh/job/McConnellsburg-Pennsylvania-United-States/Advanced-Manufacturing-Intern_R49618) |
| Interco | Paid Internship -- Software Development -- React 🛂 | Software | St. Louis, MO, United States | Sep 15, 2026 | [Apply](https://jobs.smartrecruiters.com/Interco/744000149591449) |
| LabCorp | Intern - Mechanical Engineer 🛂 | Hardware | Bloomfield CT | Sep 14, 2026 | [Apply](https://labcorp.wd1.myworkdayjobs.com/external/job/Bloomfield-CT/Intern---Mechanical-Engineer_2632739-1) |
| LabCorp | Intern - Software Developer 🛂 | Software | Durham NC | Sep 14, 2026 | [Apply](https://labcorp.wd1.myworkdayjobs.com/external/job/Durham-NC/Intern---Software-Developer_2632330) |
| Base Power | Quantitative Developer Intern | Quant | Austin, TX | Sep 14, 2026 | [Apply](https://jobs.ashbyhq.com/base-power/b6b2332e-1226-4575-b2c9-9e5258f2540e) |
| Base Power | Software Engineering Intern | Software | Austin, TX | Sep 14, 2026 | [Apply](https://jobs.ashbyhq.com/base-power/5353ea33-57d4-46fa-9a96-e392a3f841bc) |
| Flagship Pioneering | Flagship Pioneering: AI Automation Engineering Co-Op | Data & ML/AI | Cambridge, MA USA | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/fspco-op012325/jobs/8796996002) |
| Lexington Medical | Mechanical Engineering Co-Op | Hardware | Bedford, MA | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/lexingtonmedical/jobs/5423105008) |
| Thermo Fisher Scientific ✓ | Industrial Engineering Co-op | Hardware | Rochester, New York, USA | Sep 11, 2026 | [Apply](https://thermofisher.wd5.myworkdayjobs.com/ThermoFisherCareers/job/Rochester-New-York-USA/Industrial-Engineering-Co-op_R-01366625) |
| Thermo Fisher Scientific ✓ | Mechanical Engineering Co-op | Hardware | Rochester, New York, USA | Sep 11, 2026 | [Apply](https://thermofisher.wd5.myworkdayjobs.com/ThermoFisherCareers/job/Rochester-New-York-USA/Mechanical-Engineering-Co-op_R-01366623) |
| Crowe ✓ | MSFT AI Business Solutions Technical Intern | Data & ML/AI | Chicago IL USA | Sep 11, 2026 | [Apply](https://crowe.wd12.myworkdayjobs.com/external_careers/job/Chicago-IL-USA/D365-ERP-Technical-Intern_R-71039) |
| Direct Supply ✓ | AI Engineer Intern | Data & ML/AI | Milwaukee, WI | Sep 11, 2026 | [Apply](https://directsupply.wd501.myworkdayjobs.com/direct-supply-careers/job/Milwaukee-WI/AI-Engineer-Intern_REQ-2026-2553) |
| Moog | Intern, Mechanical Manufacturing Engineering | Hardware | Blacksburg, VA | Sep 11, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Blacksburg-VA/Intern--Mechanical-Manufacturing-Engineering_R-26-19925) |
| Niagara Bottling ✓ | Manufacturing Internship - Plainfield | Hardware | Plainfield - Plainfield, IN | Sep 10, 2026 | [Apply](https://niagarawater.wd5.myworkdayjobs.com/niagara/job/Plainfield---Plainfield-IN/Manufacturing-Internship---Plainfield_R56553) |
| RTX | Co-Op, Software Engineer- Onsite 🇺🇸 | Software | US-IA-CEDAR RAPIDS-109 ~ 400 Collins Rd… | Sep 10, 2026 | [Apply](https://globalhr.wd5.myworkdayjobs.com/rec_rtx_ext_gateway/job/US-IA-CEDAR-RAPIDS-109--400-Collins-Rd-NE--BLDG-109/Co-Op--Software-Engineer--Onsite_01871298) |
| IDEX | Mechanical Engineer-Intern | Hardware | Oklahoma City, Oklahoma | Sep 09, 2026 | [Apply](https://idexcorp.wd5.myworkdayjobs.com/idex_careers/job/Oklahoma-City-Oklahoma/Mechanical-Engineer-Intern_R-09824-1) |
| ConductorAI | Software Engineer Intern 🇺🇸 | Software | New York City | Sep 08, 2026 | [Apply](https://jobs.ashbyhq.com/conductorai/d6a1b110-10ad-4b5e-83a0-88c5fd7bc891) |
| TRUMPF | Smart Factory Robotics & Operations Intern | Hardware | Chicago, IL | Sep 08, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Chicago-IL/Smart-Factory-Robotics---Operations-Intern_R00042570) |
| Johnson Controls ✓ | Software/Controls Engineering Grad Intern (Fall Intern) | Software | Salem-Virginia-United States of America | Sep 04, 2026 | [Apply](https://jci.wd5.myworkdayjobs.com/JCI/job/Salem-Virginia-United-States-of-America/Software-Controls-Engineering-Grad-Intern_WD30278205-1) |
| Reflect Orbital | Mechanical Engineering Intern | Hardware | Hawthorne, CA | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/reflect-orbital/ed0c926a-9a52-4c84-8488-2552b1f0cca6) |
| Axcelis Technologies, Inc. ✓ | Manufacturing Test Development Engineer Co-op | Hardware | Beverly, MA | Sep 02, 2026 | [Apply](https://axcelis.wd1.myworkdayjobs.com/axcelis/job/Beverly-MA/Manufacturing-Test-Development-Engineer-Co-op_12010) |
| CWAN | Technical Product Management Intern | Software | Office - New York | Sep 01, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Technical-Product-Management-Intern_R12058) |
| CWAN | Technical Product Management Intern | Software | Office - New York | Sep 01, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---New-York/Technical-Product-Management-Intern_R12094) |
| Tencent ✓ | AI Business Analyst Intern | Data & ML/AI | US-California-Palo Alto | Sep 01, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/AI-Business-Analyst-Intern_R108039-1) |
| TRUMPF | CNC Programming Intern | Software | Farmington, CT | Sep 01, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Farmington-CT/CNC-Programming-Intern_R00042595) |
| TRUMPF | Industrial Engineering Internship | Hardware | Farmington, CT | Sep 01, 2026 | [Apply](https://trumpf.wd3.myworkdayjobs.com/TRUMPF_Students/job/Farmington-CT/Industrial-Engineering-Internship_R00042497) |
| The Travelers Companies | Product Management Development Program (PMDP) Intern 🛂 | Software | CT - Hartford | Sep 01, 2026 | [Apply](https://travelers.wd5.myworkdayjobs.com/External/job/CT---Hartford/Product-Management-Development-Program--PMDP--Intern_R-52317) |
| Emerson Electric | Software Engineering Co-Op | Software | Marshalltown, IA, United States | Sep 01, 2026 | [Apply](https://hdjq.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26008442) |
| Emerson Electric | Manufacturing Engineering Co-Op | Hardware | Marshalltown, IA, United States | Sep 01, 2026 | [Apply](https://hdjq.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26009034) |
| IGS Energy | Software Engineer Intern 🛂 🏠 | Software | Ohio Remote | Aug 31, 2026 | [Apply](https://igsenergy.wd1.myworkdayjobs.com/IGS/job/Ohio-Remote/Software-Engineer-Intern_R6263) |
| Brunswick ✓ | Mercury Marine: G3 Software Engineering Intern | Software | Oshkosh, WI | Aug 25, 2026 | [Apply](https://brunswick.wd1.myworkdayjobs.com/search/job/Oshkosh-WI/Mercury-Marine--Software-Validation-Intern_JR-051160) |
| Booz Allen ✓ | AI RAN Telecommunications Engineer Intern 🇺🇸 | Data & ML/AI | McLean, VA | Aug 11, 2026 | [Apply](https://bah.wd1.myworkdayjobs.com/bah_jobs/job/McLean-VA/AI-RAN-Telecommunications-Engineer-Intern_R0246869) |
| IDEXX ✓ | Security Operations (Cybersecurity) internship | Security | Westbrook, ME | Aug 03, 2026 | [Apply](https://idexx.wd1.myworkdayjobs.com/IDEXX/job/Westbrook-ME/Security-Operations--Cybersecurity--internship_J-053268) |
| Copart ✓ | Software Engineering Intern | Software | Dallas, TX - Headquarters | Jul 30, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR109964) |
| Core & Main | Intern - AI Intern - Copilot-  Onsite - St. Louis | Data & ML/AI | Saint Louis, MO 63146 | Jul 24, 2026 | [Apply](https://coreandmain.wd1.myworkdayjobs.com/coreandmain/job/Saint-Louis-MO-63146/Intern---Data-Engineering----Corp_45804) |
| Pony.ai ✓ | Research Intern - Deep Learning | Data & ML/AI | Fremont, California, United States | Jul 22, 2026 | [Apply](https://apply.workable.com/pony-dot-ai/j/4C1F53EF5D/) |
| Tencent ✓ | Research Intern – Video World Models (Research & ML Systems) | Data & ML/AI | US-California-Palo Alto | Jul 15, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/Research-Intern---Video-World-Models--Research---ML-Systems-_R107752-1) |

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
| SIG | ~Aug | ~Aug · any day now | ⏳ waiting |
| Snowflake | ~Aug | ~Aug · any day now | ⏳ waiting |
| Adobe | ~Sep | ~Sep · any day now | ⏳ waiting |
| Airbnb | ~Sep | ~Sep · any day now | ⏳ waiting |
| Bloomberg | ~Sep | ~Sep · any day now | ⏳ waiting |
| Plaid | ~Sep | ~Sep · any day now | ⏳ waiting |
| Point72 | ~Sep | ~Sep · any day now | ⏳ waiting |
| Stripe | ~Sep | ~Sep · any day now | ⏳ waiting |
| D.E. Shaw | ~Oct | ~Oct · any day now | ⏳ waiting |
| Ramp | ~Dec | ~Dec · in ~35d | ⏳ waiting |
| Two Sigma | ~Dec | ~Dec · in ~35d | ⏳ waiting |
| Apple | rolling | year-round | ⏳ waiting |
| Jump Trading | rolling | year-round | ⏳ waiting |
| Microsoft | rolling | year-round | ⏳ waiting |
| Millennium | rolling | year-round | ⏳ waiting |
| NVIDIA | rolling | year-round | ⏳ waiting |
| Palantir | rolling | year-round | ⏳ waiting |
| 🎯 Databricks | Aug 04 | dropped Aug 04 | ✅ [open now](https://databricks.com/company/careers/open-positions/job?gh_jid=6865687002) |
| 🎯 Perpay | Sep 12 | dropped Sep 12 | ✅ [open now](https://job-boards.greenhouse.io/perpay/jobs/4076978007) |
| 🎯 Glean | Sep 03 | dropped Sep 03 | ✅ [open now](https://job-boards.greenhouse.io/gleanwork/jobs/4747670005) |
| 🎯 Field AI | Feb 17 | dropped Feb 17 | ✅ [open now](https://jobs.lever.co/field-ai/b37569c3-d07f-4968-82dc-44020f34e54e) |
| 🎯 Ellipsis Labs | Mar 26 | dropped Mar 26 | ✅ [open now](https://jobs.ashbyhq.com/ellipsislabs/02136b22-35b1-4b3d-8bef-567c3380a849) |
| 🎯 Amazon | May 13 | dropped May 13 | ✅ [open now](https://www.amazon.jobs/en/jobs/10517567/software-development-engineer-intern-annapurna-labs-2027) |
| 🎯 Walleye Capital | Jun 01 | dropped Jun 01 | ✅ [open now](https://job-boards.greenhouse.io/walleyecapital-external-students/jobs/4716166006) |

_421 companies on the [full radar](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/#radar). **398** dated from our own live observations 🎯 (this grows every cycle). "~Aug" = hand-verified typical month, not a promise of the day; "rolling" = posts year-round; "waiting" = not seen in our tracked feeds yet, not a guarantee it isn't out somewhere else._

<details>
<summary><strong>Recently closed</strong> — 40 roles that left the list in the last 14 days</summary>

_Why each one left is in the last column, because the two reasons carry different evidence. **Gone from feed** = two consecutive complete reads of the employer's board no longer returned it (strong, but not the employer telling us directly). **Out of scope** = still posted, but it no longer passes our filters — our call, not theirs. **Not recorded** = closed before we started tracking the reason._

| Company | Role | Cycle | Closed | Why |
|---|---|---|---|---|
| S&C Electric Company | Manufacturing Engineer Intern | Summer 2027 | 2026-10-27 | gone from feed |
| Highmark Health | Summer 2027 Data Analyst enGen Undergraduate Intern | Summer 2027 | 2026-10-27 | gone from feed |
| Glean | Software Engineer, Intern (Summer 2027) | Summer 2027 | 2026-10-27 | gone from feed |
| K2 Space | Mechanical  Engineering Intern – Summer 2027 | Summer 2027 | 2026-10-27 | gone from feed |
| Rocket Lab | Thermal Engineering Intern Summer 2027 | Summer 2027 | 2026-10-27 | gone from feed |
| Walleye Capital | Quantic – Quantitative Developer Intern (Summer 2027) | Summer 2027 | 2026-10-27 | gone from feed |
| Neighbor | Software Engineer Intern 2027 | Summer 2027 | 2026-10-27 | gone from feed |
| WSP | Mechanical Engineering Intern - Summer 2027 | Summer 2027 | 2026-10-27 | gone from feed |
| ABB | AI Engineering, ERP Intern- Summer 2027 | Summer 2027 | 2026-10-27 | gone from feed |
| Booz Allen | University - 2027 Summer Games Software Developer Intern - Charleston, SC | Summer 2027 | 2026-10-27 | gone from feed |
| Centene | Cybersecurity Summer 2027 Intern (Undergraduate) | Summer 2027 | 2026-10-27 | gone from feed |
| General Motors | 2027 Summer Intern, AI/ML Engineer, Mapping | Summer 2027 | 2026-10-27 | gone from feed |
| Itron | Intern - HR AI Data Science (Summer 2027) | Summer 2027 | 2026-10-27 | gone from feed |
| Motorola | Android Applications Developer Intern - Summer 2027 | Summer 2027 | 2026-10-27 | gone from feed |
| Sierra Nevada Corporation | Mechanical Engineer Intern - Summer 2027 (For SNC Summer 2026 Interns Only) | Summer 2027 | 2026-10-27 | out of scope |
| STR | Data Analyst Intern - Summer 2027 | Summer 2027 | 2026-10-26 | gone from feed |
| Pattern | AI Automation Engineer Intern | Summer 2027 | 2026-10-26 | gone from feed |
| Allison Transmission | Manufacturing Engineering Intern - Summer 2027 | Summer 2027 | 2026-10-26 | gone from feed |
| Insulet Corporation | Co-op, Mechanical Lifecycle: January - June 2027 (Onsite) | Summer 2027 | 2026-10-26 | gone from feed |
| Jain Global | Quantitative Developer Intern (Summer 2027 - New York) | Summer 2027 | 2026-10-26 | gone from feed |
| LSEG | Intern - Software Engineer | Summer 2027 | 2026-10-26 | gone from feed |
| The Federal Reserve System | Summer 2027 Intern-Computer Science and Software Engineering | Summer 2027 | 2026-10-26 | gone from feed |
| Sierra Space | Summer 2027 Flight Software Engineer Intern | Summer 2027 | 2026-10-26 | gone from feed |
| The Toro Company | Embedded Software Engineering Intern - The Toro Company | Summer 2027 | 2026-10-26 | gone from feed |
| The Toro Company | Robotics System Test Intern - The Toro Company | Summer 2027 | 2026-10-26 | gone from feed |
| Zebra Technologies | 2027 Summer Internship (US) - Software Engineer | Summer 2027 | 2026-10-26 | gone from feed |
| General Motors | 2027 Summer Intern – Software Verification Engineer, AV/AI Platform | Summer 2027 | 2026-10-24 | gone from feed |
| Amazon | Software Development Engineer Intern, Amazon Leo - Summer 2027 (USA) | Summer 2027 | 2026-10-24 | gone from feed |
| Rhombus | Software Engineering Intern - Summer 2027 | Summer 2027 | 2026-10-24 | gone from feed |
| Stantec | Structural Engineering Intern - Buildings (Summer 2027) | Summer 2027 | 2026-10-24 | gone from feed |
| Stantec | Structural Engineering Intern - Buildings (Summer 2027) | Summer 2027 | 2026-10-24 | gone from feed |
| Skydio | Embedded Software Engineer Intern - Summer 2027 | Summer 2027 | 2026-10-24 | gone from feed |
| Stantec | Structural Engineering Intern - Buildings (Summer 2027) | Summer 2027 | 2026-10-24 | gone from feed |
| The Federal Reserve System | 2027 Intern - Mac/Mobile | Summer 2027 | 2026-10-24 | gone from feed |
| Amazon | Robotics - Applied Scientist II Intern / Co-op - 2026 (Robotics, Manipulation, Perception, Motion Planning, Autonomous Mobile Robots, Computer Vision, Machine Learning, Controls, and more) | Fall 2026 | 2026-10-23 | gone from feed |
| Belvedere Trading | Software Engineer Intern - Summer 2027 | Summer 2027 | 2026-10-23 | gone from feed |
| Pattern | AI Infrastructure Engineer Intern | Summer 2027 | 2026-10-23 | gone from feed |
| DP World | Information Security Intern | Summer 2027 | 2026-10-23 | gone from feed |
| WSP | Transportation Data Analyst Intern - Summer 2027 | Summer 2027 | 2026-10-23 | gone from feed |
| WSP | Structural Engineering Intern - Summer 2027 | Summer 2027 | 2026-10-23 | gone from feed |

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

_Engine (last run): 4,384 of 4,884 registered boards returned successfully across 12 ATS platforms (96% of boards attempted, 89% of the full registry) · completed in 570.0s · 108 board(s) returned a capped result set, so their roles were not eligible to be closed this run · employer or source-derived date on 99% of open roles._

## How this list is built

[METHODOLOGY.md](METHODOLOGY.md) documents exactly what every label claims — what separates a stated cycle from an inferred one, what the ✓ H-1B badge does and doesn't mean, how a role gets closed, and which limitations are known. Anything on this page that doesn't match the code is a bug worth reporting.

## Contributing

Adding a company takes one line, see [CONTRIBUTING.md](CONTRIBUTING.md), or just [open a request](../../issues/new?template=add-company.yml) with the board URL. **Spotted something wrong?** [Report the exact field](../../issues/new?template=wrong-data.yml) — wrong country, wrong cycle, closed role, bad sponsorship flag. Those reports usually fix a rule, which fixes every other role too.

Also here: [PRIVACY.md](PRIVACY.md) (what the email list stores — an address and nothing else) · [SECURITY.md](SECURITY.md) · [ARCHITECTURE.md](ARCHITECTURE.md) · [MIT licensed](LICENSE).

Built by one student with AI assistance, in the open. The part that matters isn't who typed it — it's that the rules, the tests, and every run's output are all public and checkable.

## Note on dates

The **Posted** column shows when a role was published, with the newest at the top. I pull the posting date straight from each job portal, but a lot of them don't expose one publicly, so those rows show a dash (—) for now instead of a guessed date. The ones that do publish a date are dated. Know the real date for a dashed role? Open a PR and I'll merge it.

Roles can close at any time, so always confirm on the company's own site before applying.
