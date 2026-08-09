<div align="center">

# 🎓 Summer 2027 Tech Internships

**A self-updating engine that tracks tech internships so you don't have to.**

[![CI](https://img.shields.io/github/actions/workflow/status/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/ci.yml?branch=main&label=tests&style=flat-square&color=3fb950)](https://github.com/HeyIniHere/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/actions/workflows/ci.yml)&nbsp;[![Open roles](https://img.shields.io/badge/dynamic/json?label=open%20roles&query=open_total&url=https%3A%2F%2Fheyinihere.github.io%2FAutomated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships%2Fapi%2Fstats.json&color=2f81f7&style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/)&nbsp;![Updates](https://img.shields.io/badge/updates-every%20hour-3fb950?style=flat-square)&nbsp;[![RSS](https://img.shields.io/badge/RSS-subscribe-e67e22?style=flat-square)](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/feed.xml)

### 175 open roles (156 listed below) · 87 new this week

4,003 employers tracked · updated Aug 09, 2026 at 22:42 UTC

_110 have a cycle the employer stated · 65 are recent postings whose cycle isn't stated (listed separately, never mixed in)._

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
- **An engine, not a spreadsheet** - 4,100 job-board endpoints (4,003 distinct employers; some run more than one board) polled every hour across 12 ATS platforms, full source and tests in this repo.

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

## Summer 2027  (49 employer-stated)

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Axon ✓ | US Software Engineering Internship 🆕 | Software | Seattle, Washington, United States | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/axontalentcommunity/jobs/7837133003) |
| Northrop Grumman | 2027 Operations Manufacturing Engineering Intern 🇺🇸 🆕 | Hardware | United States-California-Palmdale | Aug 07, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-California-Palmdale/XMLNAME-2027-Operations-Manufacturing-Engineering-Intern_R10244597) |
| The Nuclear Company | Summer 2027 AI/ML Engineering Intern 🇺🇸 | Data & ML/AI | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383231008) |
| The Nuclear Company | Summer 2027 Software Engineering Intern 🇺🇸 | Software | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383236008) |
| The Nuclear Company | Summer 2027 Data Science Intern 🇺🇸 | Data & ML/AI | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383244008) |
| Northrop Grumman | 2027 Intern Software Engineer 🇺🇸 | Software | United States-Florida-Melbourne | Aug 06, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Florida-Melbourne/XMLNAME-2027-Intern-Software-Engineer_R10242395) |
| Northrop Grumman | 2027 Intern Software Engineer 🇺🇸 | Software | United States-Florida-Melbourne | Aug 06, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Florida-Melbourne/XMLNAME-2027-Intern-Software-Engineer_R10243573) |
| Roblox ✓ | [Summer 2027] Software Engineer Intern | Software | San Mateo, CA, United States | Aug 05, 2026 | [Apply](https://careers.roblox.com/jobs/8072713?gh_jid=8072713) |
| Regions Bank ✓ | 2027 ETP Intern – Corporate Banking Group, Commercial Credit Products, Mobile, AL 🛂 | Software | Mobile, AL - RSA Tower | Aug 05, 2026 | [Apply](https://regions.wd5.myworkdayjobs.com/regions_careers/job/Mobile-AL---RSA-Tower/XMLNAME-2027-ETP-Intern---Corporate-Banking-Group--Commercial-Credit-Products--Mobile--AL_R104975) |
| Belvedere Trading | Software Engineer Intern - Summer 2027 | Software | Chicago, Illinois | Aug 04, 2026 | [Apply](https://jobs.lever.co/belvederetrading/10746b3d-1760-4573-9b63-b93f5a5e4fc0) |
| Pentair | IT & Cybersecurity Leadership Development Internship Program -  Summer 2027 🛂 | Security | Golden Valley, MN | Aug 04, 2026 | [Apply](https://pentair.wd5.myworkdayjobs.com/pentair_careers/job/Golden-Valley-MN/IT---Cybersecurity-Leadership-Development-Internship-Program----Summer-2027_R23700) |
| Kraft Heinz ✓ | 2027 US Manufacturing Internship Program – Manufacturing Facility Garland, Texas 🆕 | Hardware | Garland, TX | Aug 03, 2026 | [Apply](https://heinz.wd1.myworkdayjobs.com/KraftHeinz_Careers_UR/job/Garland-TX/XMLNAME-2027-US-Manufacturing-Internship-Program---Manufacturing-Facility-Garland--Texas_R-105352) |
| CNO Financial Group | Artificial Intelligence (AI) IT Intern 2027 - REMOTE 🏠 | Data & ML/AI | Carmel, IN | Aug 03, 2026 | [Apply](https://cnoinc.wd5.myworkdayjobs.com/Careers/job/Carmel-IN/Artificial-Intelligence--AI--IT-Intern-2027---REMOTE_JR170389) |
| Chicago Trading Company | Software Engineering Internship - Summer 2027 | Software | Chicago, Illinois, United States | Aug 03, 2026 | [Apply](https://job-boards.greenhouse.io/chicagotradingcampus/jobs/4716932005) |
| JPMorganChase ✓ | 2027 Data & AI Program - Summer Internship - Analyst - United States | Data & ML/AI | Chicago, IL, United States | Aug 03, 2026 | [Apply](https://jpmc.fa.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/210773869) |
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
| Western Digital ✓ | Summer 2027 - Software Engineering Internship | Software | San Jose, CA, United States | Jul 20, 2026 | [Apply](https://jobs.smartrecruiters.com/WesternDigital/744000138727213) |
| Chicago Trading Company | Software Engineering Internship - Summer 2027 | Software | Chicago, Illinois, United States | Jul 20, 2026 | [Apply](https://job-boards.greenhouse.io/ctccampusboard/jobs/4708230005) |
| Deepgram | Software Engineering- Internship (Fall 2026/Summer 2027) 🏠 _(also open for Fall 2026)_ | Software | USA / Remote | Jul 17, 2026 | [Apply](https://jobs.ashbyhq.com/deepgram/dc8693b5-72ce-4ca3-ab15-9c8434d35da1) |
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
| Anduril | 2027 Mechanical Engineer Intern 🇺🇸 | Hardware | Atlanta +17 more | Jun 11, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5153187007?gh_jid=5153187007) |
| Anduril | 2027 Manufacturing Engineer Intern 🇺🇸 | Hardware | Atlanta +14 more | Jun 11, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5153218007?gh_jid=5153218007) |
| Voloridge | Quantitative Developer Intern 2027 | Quant | Jupiter, FL | Jun 11, 2026 | [Apply](https://job-boards.greenhouse.io/voloridgeinvestmentmanagement/jobs/4224862009) |
| Anduril | 2027 Software Engineer Intern 🇺🇸 | Software | Atlanta +17 more | Jun 10, 2026 | [Apply](https://boards.greenhouse.io/andurilindustries/jobs/5148079007?gh_jid=5148079007) |
| Walleye Capital | Quantic – Quantitative Developer Intern (Summer 2027) | Quant | Boston, MA | Jun 01, 2026 | [Apply](https://job-boards.greenhouse.io/walleyecapital-external-students/jobs/4679168006) |
| Ellipsis Labs | Software Engineer - 2027 Interns | Software | New York, New York | Mar 26, 2026 | [Apply](https://jobs.ashbyhq.com/ellipsislabs/02136b22-35b1-4b3d-8bef-567c3380a849) |
| Databricks ✓ | Product Management Intern (Summer 2027) | Software | Bellevue +5 more | Aug 17, 2023 | [Apply](https://databricks.com/company/careers/open-positions/job?gh_jid=6883068002) |

## Fall 2026  (54 employer-stated)

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| Flextronics International ✓ | Mechanical Engineering Co-op - Fall 2026 🆕 | Hardware | USA, SC, Orangeburg | Aug 07, 2026 | [Apply](https://flextronics.wd1.myworkdayjobs.com/Careers/job/USA-SC-Orangeburg/Mechanical-Engineering-Co-op---Fall-2026_WD227049) |
| The Nuclear Company | Fall 2026 AI/ML Engineering Intern 🇺🇸 | Data & ML/AI | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383163008) |
| The Nuclear Company | Fall 2026 AI Software Engineering Intern 🇺🇸 | Data & ML/AI | Washington, DC | Aug 07, 2026 | [Apply](https://job-boards.greenhouse.io/thenuclearcompany/jobs/5383113008) |
| Sony Pictures Entertainment ✓ | Intern, Insights, Strategy & Analytics, Product Management – Data Science – Fall 2026 | Data & ML/AI | Culver City, California | Aug 07, 2026 | [Apply](https://spe.wd1.myworkdayjobs.com/SonyPicturesEntertainment/job/Culver-City-California/Intern--Insights--Strategy---Analytics--Product-Management---Data-Science---Fall-2026_JR113988) |
| Johnson & Johnson | Software Engineer Coop | Software | Cincinnati +2 more | Aug 07, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Cincinnati-Ohio-United-States-of-America/Software-Engineer-Coop_R-092820) |
| Warner Bros. ✓ | Bleacher Report Social Programming Intern: LA - Fall 2026 | Software | CA Burbank Bldg. 700 +2 more | Aug 06, 2026 | [Apply](https://warnerbros.wd5.myworkdayjobs.com/global/job/CA-Burbank-Bldg-700-Second-Century-Tower-1/Bleacher-Report-Social-Programming-Intern--LA---Fall-2026_R000107469) |
| NVIDIA ✓ | Software Engineering Intern, Dynamo - Fall 2026 | Software | US, CA, Santa Clara | Aug 05, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/US-CA-Santa-Clara/Software-Engineering-Intern--Dynamo---Fall-2026_JR2022295) |
| Phoenix Contact | Manufacturing Co-Op - High School Students | Hardware | Middletown, Pennsylvania | Aug 04, 2026 | [Apply](https://job-boards.greenhouse.io/phoenixcontact/jobs/7817228003) |
| Merck | 2026 Future Talent Program – Manufacturing and Reliability Engineering Co-Op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Manufacturing-and-Reliability-Engineering-Co-Op_R395901) |
| Merck | 2026 Future Talent Program - Vaccine Manufacturing Co-op | Hardware | USA - Pennsylvania - West Point | Aug 04, 2026 | [Apply](https://msd.wd5.myworkdayjobs.com/searchjobs/job/USA---Pennsylvania---West-Point/XMLNAME-2026-Future-Talent-Program---Vaccine-Manufacturing-Co-op_R395900) |
| Densityai | Technical Intern- Software  (Fall 2026) 🇺🇸 | Software | Mountain View, CA | Aug 03, 2026 | [Apply](https://job-boards.greenhouse.io/densityai/jobs/4336452009) |
| Northrop Grumman | 2026 Fall Co-op Manufacturing Engineering - Baltimore MD 🇺🇸 | Hardware | United States-Maryland-Linthicum | Aug 03, 2026 | [Apply](https://ngc.wd1.myworkdayjobs.com/Northrop_Grumman_External_Site/job/United-States-Maryland-Linthicum/XMLNAME-2026-Fall-Co-op-Manufacturing-Engineering---Baltimore-MD_R10243390-1) |
| Melius | Software Engineering Intern [Fall/Winter 2026] | Software | New York City | Jul 30, 2026 | [Apply](https://jobs.ashbyhq.com/melius/6a944911-dbbf-44c7-ba52-7866f7b433cf) |
| Flextronics International ✓ | Industrial Engineering Co-Op - Fall 2026 | Hardware | USA, SC, Orangeburg | Jul 30, 2026 | [Apply](https://flextronics.wd1.myworkdayjobs.com/Careers/job/USA-SC-Orangeburg/Industrial-Engineering-Co-Op---Fall-2026_WD226357) |
| Redwood Materials | Embedded Software Engineer Intern - Fall 2026 | Software | San Francisco, California, United States | Jul 29, 2026 | [Apply](https://boards.greenhouse.io/redwoodmaterials/jobs/6126784004?gh_jid=6126784004) |
| Rendezvous Robotics | Manufacturing and Test Engineering Intern (Fall 2026) 🇺🇸 | Hardware | Golden, CO | Jul 27, 2026 | [Apply](https://job-boards.greenhouse.io/rendezvousrobotics/jobs/4332076009) |
| Toshiba Global Commerce ✓ | Mechanical Engineering Intern 🛂 | Hardware | Durham, NC | Jul 26, 2026 | [Apply](https://job-boards.greenhouse.io/toshibaglobalcommercesolutions/jobs/5187159007) |
| QuEra Computing | Mechanical Engineering Co-Op - Fall 2026 | Hardware | Boston, MA, USA | Jul 24, 2026 | [Apply](https://job-boards.greenhouse.io/queracomputinginc/jobs/5370312008) |
| Applied Materials ✓ | 2026 Fall Mechanical Engineer Co-op - BS/MS (Gloucester, MA) | Hardware | Gloucester,MA | Jul 23, 2026 | [Apply](https://amat.wd1.myworkdayjobs.com/External/job/GloucesterMA/XMLNAME-2026-Fall-Mechanical-Engineer-Co-op---BS-MS--Gloucester--MA-_R2611501) |
| Astranis | Software Engineer Intern - Enterprise Systems (Fall 2026) 🇺🇸 | Software | San Francisco, CA | Jul 23, 2026 | [Apply](https://job-boards.greenhouse.io/astranis/jobs/4699071006) |
| Rendezvous Robotics | Mechanical Engineering Intern (Fall 2026) 🇺🇸 | Hardware | Golden, CO | Jul 22, 2026 | [Apply](https://job-boards.greenhouse.io/rendezvousrobotics/jobs/4329113009) |
| Rendezvous Robotics | Software Engineering Intern (Fall 2026) 🇺🇸 | Software | Golden, CO | Jul 22, 2026 | [Apply](https://job-boards.greenhouse.io/rendezvousrobotics/jobs/4328555009) |
| Axon ✓ | RenderATL 2026 US Software Engineering Internship | Software | Seattle, Washington, United States | Jul 20, 2026 | [Apply](https://job-boards.greenhouse.io/axontalentcommunity/jobs/7800617003) |
| Axon ✓ | RenderATL 2026 US Firmware Engineering Internship | Hardware | Seattle, Washington, United States | Jul 20, 2026 | [Apply](https://job-boards.greenhouse.io/axontalentcommunity/jobs/7800628003) |
| Deepgram | Software Engineering- Internship (Fall 2026/Summer 2027) 🏠 _(also open for Summer 2027)_ | Software | USA / Remote | Jul 17, 2026 | [Apply](https://jobs.ashbyhq.com/deepgram/dc8693b5-72ce-4ca3-ab15-9c8434d35da1) |
| Moog | Intern, IT Computer Science - Data Analytics | Data & ML/AI | Buffalo, NY | Jul 16, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--IT-Computer-Science---Data-Analytics_R-26-17145) |
| SharkNinja ✓ | Fall 2026: Code/Sharks DTC Commerce Product Management Co-op (August through December 2026) | Software | Needham, MA, United States | Jul 08, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4695627006) |
| Sunday Robotics | Manufacturing Engineering Intern (Fall 2026) | Hardware | Redwood City, CA | Jul 07, 2026 | [Apply](https://jobs.ashbyhq.com/sunday/08feb65a-08b0-462d-aebf-4f0239a16ed8) |
| VAST | 2026 Fall Internship - Manufacturing 🇺🇸 | Hardware | Long Beach, California, United States | Jul 07, 2026 | [Apply](https://boards.greenhouse.io/vast/jobs/4694238006?gh_jid=4694238006) |
| VAST | 2026 Fall Internship - Mechanical / Aerospace 🇺🇸 | Hardware | Long Beach, California, United States | Jul 07, 2026 | [Apply](https://boards.greenhouse.io/vast/jobs/4694905006?gh_jid=4694905006) |
| NVIDIA ✓ | Applied Research Intern, NLP - Fall 2026 | Data & ML/AI | US, CA, Santa Clara | Jul 01, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/US-CA-Santa-Clara/Applied-Research-Intern--NLP---Fall-2026_JR2010488) |
| Junior | Software Engineering Intern — Fall 2026 🇺🇸 | Software | New York City | Jun 30, 2026 | [Apply](https://jobs.ashbyhq.com/junior/23ee686b-d305-4ac9-860d-16c99ddb4891) |
| Figure | Firmware Intern [Fall 2026] | Hardware | San Jose, CA | Jun 22, 2026 | [Apply](https://job-boards.greenhouse.io/figureai/jobs/4691070006) |
| Intuitive Surgical ✓ | Computer Vision Engineering Intern - Fall 2026 | Data & ML/AI | Sunnyvale, CA, United States | Jun 22, 2026 | [Apply](https://jobs.smartrecruiters.com/Intuitive/744000133458290) |
| Stantec ✓ | Structural Engineering Intern/Co-op - Transportation (Fall 2026) | Hardware | New York, NY, United States | Jun 18, 2026 | [Apply](https://hdhl.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/1006349) |
| SoloPulse | Software Engineer Intern/Co-Op - Fall 2026 | Software | Peachtree Corners, GA | Jun 16, 2026 | [Apply](https://jobs.lever.co/solopulseco/00fbde18-a387-4c9f-97d4-77059aec7b56) |
| Beacon Software | Software Engineering Intern | Software | San Francisco, CA | Jun 02, 2026 | [Apply](https://jobs.ashbyhq.com/beaconsoftware/2452d342-a069-4eda-adbe-9df296808ca1) |
| Rocket Lab | Manufacturing Engineering Intern Fall 2026 🇺🇸 | Hardware | Long Beach, CA | May 21, 2026 | [Apply](https://job-boards.greenhouse.io/rocketlab/jobs/7733900003) |
| Saronic | Software Engineer Intern (Fall 2026) 🇺🇸 | Software | Austin, TX | May 18, 2026 | [Apply](https://jobs.ashbyhq.com/saronic/1c74957f-0895-415b-9324-08b0994747d7) |
| Astranis | Software Engineer- Backend Intern (Fall 2026) 🇺🇸 | Software | San Francisco, CA | May 13, 2026 | [Apply](https://job-boards.greenhouse.io/astranis/jobs/4681183006) |
| Amazon ✓ | Software Development Engineer Intern, AWS Data Services - Fall 2026 (US) | Data & ML/AI | Seattle, Washington, USA | May 06, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10412530/software-development-engineer-intern-aws-data-services-fall-2026-us) |
| TMEIC ✓ | Intern - Applications, AI and Machine Learning (Fall 2026) (ET26021) 🛂 | Data & ML/AI | Roanoke, Virginia, United States | Apr 24, 2026 | [Apply](https://apply.workable.com/tmeic-corporation-americas/j/FD4C9770FF/) |
| Westlake | 2026 Intern - Mechanical Engineer 🛂 | Hardware | US - Houston, TX | Apr 22, 2026 | [Apply](https://westlake.wd1.myworkdayjobs.com/westlake/job/US---Houston-TX/XMLNAME-2026-Intern---Mechanical-Engineer_R30240) |
| SharkNinja ✓ | Fall 2026: AI/Sharks Applied AI & Analytics Co-op (August to December) | Data & ML/AI | Miami +8 more | Apr 02, 2026 | [Apply](https://job-boards.greenhouse.io/sharkninjaoperatingllc/jobs/4669676006) |
| Applied Materials ✓ | 2026 Fall Materials Engineering Co-op (TCAD Modeling) - Doctorate (Gloucester, MA) | Hardware | Gloucester,MA | Apr 01, 2026 | [Apply](https://amat.wd1.myworkdayjobs.com/External/job/GloucesterMA/XMLNAME-2026-Fall-Materials-Engineering-Co-op---Doctorate--Gloucester--MA-_R2611503) |
| Hermeus | Software Engineering Intern (Command & Control) - Fall 2026 🇺🇸 | Software | Atlanta, GA | Apr 01, 2026 | [Apply](https://jobs.lever.co/hermeus/a3a1f0ea-6a4f-42e5-81c8-3b34dac22a67) |
| Alloy Enterprises | Co-Op, Thermal Test Engineer, Fall 2026 (July-December) 🇺🇸 | Hardware | Burlington, MA | Mar 25, 2026 | [Apply](https://jobs.ashbyhq.com/alloyenterprises/946e7ae1-d2ac-4889-a72a-268b0aeda9bd) |
| Varda Space | Mechanical Engineering Internship - Fall 2026 🇺🇸 | Hardware | El Segundo, California, United States | Mar 24, 2026 | [Apply](https://job-boards.greenhouse.io/vardaspace/jobs/7670782003) |
| Hermeus | Mechanical Engineering Intern  - Fall 2026 🇺🇸 | Hardware | Los Angeles, CA | Mar 09, 2026 | [Apply](https://jobs.lever.co/hermeus/6b6afa4a-b37d-4033-ac3b-e6501a951b98) |
| Hermeus | Flight Software Engineering Intern - Fall 2026 🇺🇸 | Software | Atlanta, GA | Mar 04, 2026 | [Apply](https://jobs.lever.co/hermeus/51378fa0-0327-45fd-9420-b6e7d8b56440) |
| Field AI | Robotics Research Internship-Locomotion & Planning (Fall 2026) | Hardware | Irvine, CA | Feb 17, 2026 | [Apply](https://jobs.lever.co/field-ai/ce04c5b3-17c3-49aa-b833-a6bebbf9d23f) |
| Amazon ✓ | Robotics - Hardware Development Engineer Intern/Co-op - 2026 (Robotics, Mechanical, Electrical, Hardware Test, Reliability, Failure Analysis, Operations, and more) | Hardware | Westboro, Massachusetts, USA | Dec 17, 2025 | [Apply](https://www.amazon.jobs/en/jobs/3145033/robotics-hardware-development-engineer-intern-co-op-2026-robotics-mechanical-electrical-hardware-test-reliability-failure-analysis-operations-and-more) |
| Amazon ✓ | Robotics - Software Development Engineer Intern/Co-op - 2026 | Hardware | Westboro, Massachusetts, USA | Dec 03, 2025 | [Apply](https://www.amazon.jobs/en/jobs/3136266/robotics-software-development-engineer-intern-co-op-2026) |
| Figure | Mechanical Engineer Intern [Fall 2026] | Hardware | San Jose, CA | Nov 09, 2023 | [Apply](https://job-boards.greenhouse.io/figureai/jobs/4303098006) |

## Recently posted — cycle not stated  (54 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Posted | Apply |
|---|---|---|---|---|---|
| ACDS | AI Operations Engineer Intern | Data & ML/AI | Lowell, AR | Aug 07, 2026 | [Apply](https://jobs.lever.co/acds/e468d15b-69c3-4534-8072-7ff3f85fbf83) |
| Copart ✓ | Software Engineering Intern | Software | Dallas, TX - Headquarters | Aug 07, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR101510) |
| Bosch | Internship Vehicle Thermal Systems Engineering | Hardware | Farmington Hills, MI, United States | Aug 07, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000142173185) |
| Moog | Intern, Industrial Engineering | Hardware | Buffalo, NY | Aug 07, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Industrial-Engineering_R-26-19319) |
| Centerfield ✓ | Frontend Engineer Intern (6 month internship) | Software | Los Angeles, California | Aug 06, 2026 | [Apply](https://jobs.ashbyhq.com/centerfield/1d7eacc1-37f7-478c-9b0a-fa7974f1a9e4) |
| impact.com | Associate Software Engineer intern | Software | Santa Barbara, CA | Aug 06, 2026 | [Apply](https://job-boards.greenhouse.io/impact/jobs/8645964002) |
| Solid Power | Materials Engineering Intern 🛂 | Hardware | 486 S. Pierce Ave +3 more | Aug 06, 2026 | [Apply](https://job-boards.greenhouse.io/solidpower/jobs/6138210004) |
| Rainmaker | Mechanical Engineering Intern - Fall | Hardware | El Segundo, CA | Aug 06, 2026 | [Apply](https://jobs.lever.co/make-rain/87613e64-cc8f-47ab-a053-0b2c3ee93ebd) |
| Nokia ✓ | AI R&D Engineer Co-op | Data & ML/AI | United States | Aug 06, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/39284) |
| Nokia ✓ | AI R&D Engineer Co-op | Data & ML/AI | United States | Aug 06, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/39285) |
| Nokia ✓ | AI R&D Engineer Co-op | Data & ML/AI | United States | Aug 06, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/39286) |
| KBR ✓ | Software Intern | Software | Houston, Texas | Aug 06, 2026 | [Apply](https://kbr.wd5.myworkdayjobs.com/KBR_Careers/job/Houston-Texas/Software-Intern_R2127863) |
| CAE | Mechanical Engineering Intern 🇺🇸 | Hardware | Arlington, TX | Aug 05, 2026 | [Apply](https://cae.wd3.myworkdayjobs.com/career/job/Arlington-TX/Mechanical-Engineering-Intern_122210) |
| Draper | Embedded Quality & Fielded Systems Intern | Software | Cambridge, MA | Aug 05, 2026 | [Apply](https://draper.wd5.myworkdayjobs.com/Draper_Careers/job/Cambridge-MA/Embedded-Quality---Fielded-Systems-Intern_JR002718) |
| Diversified Automation | Software Engineering Co-op | Software | Louisville, KY | Aug 04, 2026 | [Apply](https://jobs.lever.co/diversified-automation/827a092d-b8a3-4ca9-a84a-e8c236d1aabc) |
| PlusAI ✓ | Deep Learning Research Intern — Multimodal BEV Perception | Data & ML/AI | Santa Clara, CA | Aug 04, 2026 | [Apply](https://jobs.lever.co/plus-2/2ee24f85-bfa1-47fc-bfe3-fd07521a7b62) |
| Intel ✓ | AI Software Engineer Graduate Intern | Data & ML/AI | Virtual US | Aug 04, 2026 | [Apply](https://intel.wd1.myworkdayjobs.com/external/job/Virtual-US/AI-Software-Engineer-Graduate-Intern_JR0285989) |
| Thales | AppSec Product Support Intern | Security | Texas | Aug 04, 2026 | [Apply](https://thales.wd3.myworkdayjobs.com/careers/job/Texas/AppSec-Product-Support-Intern_R0328978-1) |
| TSC | Robotics Intern 🇺🇸 | Hardware | Washington +1 more | Aug 04, 2026 | [Apply](https://tsc.wd12.myworkdayjobs.com/TSC-Careers/job/Washington-DC---Naval-Research-Laboratory/Robotics-Intern_JR2713) |
| IDEXX ✓ | Security Operations (Cybersecurity) internship | Security | Westbrook, ME | Aug 03, 2026 | [Apply](https://idexx.wd1.myworkdayjobs.com/IDEXX/job/Westbrook-ME/Security-Operations--Cybersecurity--internship_J-053268) |
| Bosch | AI and SW Development Engineering Intern | Data & ML/AI | Plymouth, MI, United States | Aug 03, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000141302469) |
| Yotta Labs | Research Engineer Intern - AI Systems | Data & ML/AI | United States | Aug 02, 2026 | [Apply](https://jobs.ashbyhq.com/yotta/09821a51-fbe6-42a7-a566-0d2b5d40fae3) |
| Copart ✓ | Software Engineering Intern | Software | Dallas, TX - Headquarters | Aug 02, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR110353) |
| Skydio ✓ | Product Management Intern | Software | San Mateo, California, United States | Jul 31, 2026 | [Apply](https://jobs.ashbyhq.com/skydio/1ec2fe3c-3fb2-4485-870d-764a3e5f5baf) |
| Copart ✓ | Software Engineering Intern | Software | Dallas, TX - Headquarters | Jul 30, 2026 | [Apply](https://copart.wd12.myworkdayjobs.com/copart/job/Dallas-TX---Headquarters/Software-Engineering-Intern_JR109964) |
| Bosch | Product Management Internship (6-month) | Software | Farmington Hills, MI, United States | Jul 29, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000140457960) |
| Modal | ML Research Intern | Data & ML/AI | New York | Jul 28, 2026 | [Apply](https://jobs.ashbyhq.com/modal/38888294-6bc7-4dab-b072-6d0f0c2ed79a) |
| Nelnet ✓ | Intern Program - Agentic AI | Data & ML/AI | Lincoln, NE | Jul 27, 2026 | [Apply](https://nelnet.wd1.myworkdayjobs.com/MyNelnet/job/Lincoln-NE/Intern-Program---Agentic-AI_R22904) |
| Kulicke & Soffa ✓ | Intern, AS Mechanical | Hardware | Fort Washington, PA, United States | Jul 24, 2026 | [Apply](https://etyy.fa.ap2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/11568) |
| Core & Main | Intern - AI/ML Data Engineering  -  Onsite - St. Louis | Data & ML/AI | Saint Louis, MO 63146 | Jul 24, 2026 | [Apply](https://coreandmain.wd1.myworkdayjobs.com/coreandmain/job/Saint-Louis-MO-63146/Intern---Data-Engineering----Corp_45804) |
| Magna International | R&D- Computer Vision Engineering Intern | Data & ML/AI | Troy, Michigan, US | Jul 24, 2026 | [Apply](https://magna.wd3.myworkdayjobs.com/Magna/job/Troy-Michigan-US/R-D--Computer-Vision-Engineering-Intern_R00253444-1) |
| Tenstorrent ✓ | Software Engineering Intern, Power Modeling & AI Tools | Data & ML/AI | Santa Clara, California, United States | Jul 23, 2026 | [Apply](https://job-boards.greenhouse.io/tenstorrentuniversity/jobs/5186916007) |
| Pony.ai ✓ | Research Intern - Deep Learning | Data & ML/AI | Fremont, California, United States | Jul 22, 2026 | [Apply](https://apply.workable.com/pony-dot-ai/j/4C1F53EF5D/) |
| Pony.ai ✓ | Software Engineer Intern - Generalist | Software | Fremont, California, United States | Jul 22, 2026 | [Apply](https://apply.workable.com/pony-dot-ai/j/BA5FFDBC71/) |
| Moog | Intern, Software Engineering | Software | Buffalo, NY | Jul 22, 2026 | [Apply](https://moog.wd5.myworkdayjobs.com/moog_external_career_site/job/Buffalo-NY/Intern--Software-Engineering_R-26-18885-1) |
| ACDS | AI Operations Intern-Caddell Reynolds | Data & ML/AI | Fort Smith, AR | Jul 20, 2026 | [Apply](https://jobs.lever.co/acds/01fdf41b-a835-4e00-8d01-0275677a8f08) |
| Neuralink | R&D Materials Engineer Intern | Hardware | South San Francisco +2 more | Jul 17, 2026 | [Apply](https://boards.greenhouse.io/neuralink/jobs/7808233003?gh_jid=7808233003) |
| Intel ✓ | AI Software Engineering Intern | Data & ML/AI | US, Arizona, Phoenix | Jul 17, 2026 | [Apply](https://intel.wd1.myworkdayjobs.com/external/job/US-Arizona-Phoenix/AI-Software-Engineering-Intern_JR0282641) |
| Huntsman | Mechanical Engineering Intern 🛂 | Hardware | USA - Texas - Houston - The Woodlands -… | Jul 16, 2026 | [Apply](https://huntsman.wd1.myworkdayjobs.com/Huntsman/job/USA---Texas---Houston---The-Woodlands---Corporate-Office/Mechanical-Engineering-Intern_J-020026) |
| Tencent ✓ | Research Intern – Video World Models (Research & ML Systems) | Data & ML/AI | US-California-Palo Alto | Jul 15, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/US-California-Palo-Alto/Research-Intern---Video-World-Models--Research---ML-Systems-_R107752-1) |
| MetOx International | Mechanical Engineering Intern | Hardware | Houston, TX | Jul 14, 2026 | [Apply](https://job-boards.greenhouse.io/metoxinternationalinc/jobs/5349699008) |
| ACDS | AI Operations Intern - Naukr AI | Data & ML/AI | Bentonville, AR | Jul 13, 2026 | [Apply](https://jobs.lever.co/acds/41bee5e2-6477-428f-b359-34b4071d545f) |
| TSC | Aerospace/Mechanical Engineering Intern 🇺🇸 | Hardware | Washington +1 more | Jul 12, 2026 | [Apply](https://tsc.wd12.myworkdayjobs.com/TSC-Careers/job/Washington-DC---Naval-Research-Laboratory/Aerospace-Mechanical-Engineering-Intern_JR2683) |
| Xsolla | AI-First Engineering Intern | Data & ML/AI | Raleigh, United States | Jul 10, 2026 | [Apply](https://jobs.lever.co/xsolla/5d5fd6b3-d82f-437a-b251-abf4674ac874) |
| Xsolla | AI-First Engineering Intern | Data & ML/AI | Los Angeles, United States | Jul 10, 2026 | [Apply](https://jobs.lever.co/xsolla/1c0e5375-2352-4a2c-a816-48ddebbdd3d6) |
| Jump Trading | Campus AI Research Engineer (Intern) | Data & ML/AI | Chicago; New York | Jul 08, 2026 | [Apply](https://www.jumptrading.com/hr/job?gh_jid=8052281) |
| Jump Trading | Campus AI Research Engineer - Deep Learning (Intern) | Data & ML/AI | Chicago; New York | Jul 08, 2026 | [Apply](https://www.jumptrading.com/hr/job?gh_jid=8052338) |
| Jump Trading | Campus AI Research Engineer – Research Automation (Intern) | Data & ML/AI | Chicago; New York | Jul 08, 2026 | [Apply](https://www.jumptrading.com/hr/job?gh_jid=8052351) |
| Bot Auto | Intern, Deep Learning Engineer | Data & ML/AI | Houston, TX | Jul 02, 2026 | [Apply](https://job-boards.greenhouse.io/botauto/jobs/5289440008) |
| ConnectPrep | Data Analyst Internship 🇺🇸 🏠 | Data & ML/AI | Washington +2 more | Jul 02, 2026 | [Apply](https://apply.workable.com/connectprep/j/C0CA13664F/) |
| Palantir ✓ | Forward Deployed Software Engineer, Internship - Intel | Software | Washington, D.C. | Jul 01, 2026 | [Apply](https://jobs.lever.co/palantir/9e40d77f-b07c-437b-98e7-def9b0184d89) |
| Palantir ✓ | Forward Deployed Software Engineer, Internship - Commercial | Software | Chicago, IL | Jun 30, 2026 | [Apply](https://jobs.lever.co/palantir/d5486403-c050-4920-b2e0-91b69b61ebb2) |
| Veeda AI | Internship - Veeda AI Scientist | Data & ML/AI | California | Jun 29, 2026 | [Apply](https://jobs.ashbyhq.com/veeda-labs/58cc42fb-1d6f-4e5f-860d-3b97bdccc6f4) |
| Lila Sciences | Co-Op, ML Scientist for Protein Engineering | Data & ML/AI | San Francisco, CA USA | Jun 29, 2026 | [Apply](https://job-boards.greenhouse.io/lilasciences/jobs/4289387009) |

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
| Adobe | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| Airbnb | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| Bloomberg | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| Dropbox | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| Plaid | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| Point72 | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| Robinhood | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| Stripe | ~Sep | ~Sep · in ~23d | ⏳ waiting |
| D.E. Shaw | ~Oct | ~Oct | ⏳ waiting |
| Coinbase | ~Dec | ~Dec | ⏳ waiting |
| Ramp | ~Dec | ~Dec | ⏳ waiting |
| Two Sigma | ~Dec | ~Dec | ⏳ waiting |
| Apple | rolling | year-round | ⏳ waiting |
| Datadog | rolling | year-round | ⏳ waiting |
| Jump Trading | rolling | year-round | ⏳ waiting |
| Microsoft | rolling | year-round | ⏳ waiting |
| Millennium | rolling | year-round | ⏳ waiting |

_74 companies on the [full radar](https://heyinihere.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-MechEng-Internships/#radar). **41** dated from our own live observations 🎯 (this grows every cycle). "~Aug" = hand-verified typical month, not a promise of the day; "rolling" = posts year-round; "waiting" = not seen in our tracked feeds yet, not a guarantee it isn't out somewhere else._

<details>
<summary><strong>Recently closed</strong> — 40 roles that left the list in the last 14 days</summary>

_Why each one left is in the last column, because the two reasons carry different evidence. **Gone from feed** = two consecutive complete reads of the employer's board no longer returned it (strong, but not the employer telling us directly). **Out of scope** = still posted, but it no longer passes our filters — our call, not theirs. **Not recorded** = closed before we started tracking the reason._

| Company | Role | Cycle | Closed | Why |
|---|---|---|---|---|
| JPMorganChase | 2027 Data for Good Hackathon - Data & AI Program - Summer Internship | Summer 2027 | 2026-08-09 | gone from feed |
| Duke Energy | Asc Cybersecurity Gov&Risk Analyst - Intern/Co-op Conversion 2027 (Souza) | Summer 2027 | 2026-08-08 | gone from feed |
| Netsmart | Software Engineer Intern (Summer 2027 Internship) | Summer 2027 | 2026-08-08 | gone from feed |
| Lego | Firmware Engineering Co-Op - Fall 2026 | Fall 2026 | 2026-08-08 | gone from feed |
| Atoms | Software Engineer Intern - Summer 2027 | Summer 2027 | 2026-08-07 | out of scope |
| CNO Financial Group | Cyber Security IT Intern - REMOTE | Summer 2027 | 2026-08-07 | gone from feed |
| Sony Pictures Entertainment | Current Programming Intern, Sony Pictures Television – Fall 2026 | Fall 2026 | 2026-08-07 | gone from feed |
| Saronic | Enterprise Technology Intern - AI and Automation (Fall 2026) | Fall 2026 | 2026-08-07 | gone from feed |
| Gemini | Software Engineering Intern (Fall 2026) | Fall 2026 | 2026-08-07 | gone from feed |
| Gemini | Product Management Intern (Fall 2026) | Fall 2026 | 2026-08-07 | gone from feed |
| Rocket Lab | Mechanical Engineering Intern Fall 2026 | Fall 2026 | 2026-08-07 | gone from feed |
| Samsung Research America | 2026 Fall Intern, ML/NLP Research | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - Enterprise Risk Management | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - Solutions | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - Federal | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - Threat | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - Payments | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - International Organization for Standardization (ISO) | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - Healthcare | Fall 2026 | 2026-08-07 | gone from feed |
| Tevora | Cybersecurity Internship Fall 2026 - Systems and Organizations Controls (SOC) | Fall 2026 | 2026-08-07 | gone from feed |
| JPMorganChase | 2027 Code for Good Hackathon - Software Engineer Program - Summer Internship – United States | Summer 2027 | 2026-08-07 | gone from feed |
| Motorola | Intern - Embedded Software, System, and Test Engineer - 2026 | Fall 2026 | 2026-08-07 | gone from feed |
| Toshiba Global Commerce | AI Product Management Intern | Fall 2026 | 2026-08-07 | gone from feed |
| NVIDIA | Performance Engineer Intern, Systems Software-  Fall 2026 | Fall 2026 | 2026-08-07 | gone from feed |
| Toshiba Global Commerce | Agentic Software Engineering intern | Fall 2026 | 2026-08-03 | gone from feed |
| Toshiba Global Commerce | Project Management & AI Automation Intern | Fall 2026 | 2026-08-03 | gone from feed |
| Toshiba Global Commerce | AI Engineering Intern | Fall 2026 | 2026-08-03 | gone from feed |
| Walleye Capital | Investment Data Science Intern (Summer 2027) | Summer 2027 | 2026-08-03 | gone from feed |
| Walleye Capital | Volatility Trading Developer Intern (Summer 2027) | Summer 2027 | 2026-08-03 | gone from feed |
| Hermeus | Software Engineering Intern (HIL) - Fall 2026 | Fall 2026 | 2026-08-03 | gone from feed |
| Draper | Electronics & Embedded Systems Intern (Summer 2027) | Summer 2027 | 2026-08-03 | gone from feed |
| Leidos | Software Developer Intern | Summer 2027 | 2026-08-03 | gone from feed |
| Mosaic | Informational Technology Cybersecurity Co-Op/Intern - Fall 2026 | Fall 2026 | 2026-08-03 | gone from feed |
| Sentara Health | Data & AI Finance Strategy Intern - Fall 2026 Internship Remote | Fall 2026 | 2026-08-03 | gone from feed |
| Sentara Health | Enterprise Data & AI Intern- Fall 2026 Internship | Fall 2026 | 2026-08-03 | gone from feed |
| Varda Space | Flight Software Internship - Fall 2026 | Fall 2026 | 2026-07-30 | gone from feed |
| Notion | Software Engineer Intern (Fall 2026) | Fall 2026 | 2026-07-30 | gone from feed |
| Hermeus | Software Engineering Intern (Modeling & Simulation) - Fall 2026 | Fall 2026 | 2026-07-29 | gone from feed |
| Charles River Analytics | Software QA Tester Intern/Co-op | Fall 2026 | 2026-07-29 | gone from feed |
| Four Hands | Cybersecurity Intern | Fall 2026 | 2026-07-28 | gone from feed |

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

_Engine (last run): 3,830 of 4,100 registered boards returned successfully across 12 ATS platforms (100% of boards attempted, 93% of the full registry) · completed in 327.3s · 93 board(s) returned a capped result set, so their roles were not eligible to be closed this run · employer or source-derived date on 100% of open roles._

## How this list is built

[METHODOLOGY.md](METHODOLOGY.md) documents exactly what every label claims — what separates a stated cycle from an inferred one, what the ✓ H-1B badge does and doesn't mean, how a role gets closed, and which limitations are known. Anything on this page that doesn't match the code is a bug worth reporting.

## Contributing

Adding a company takes one line, see [CONTRIBUTING.md](CONTRIBUTING.md), or just [open a request](../../issues/new?template=add-company.yml) with the board URL. **Spotted something wrong?** [Report the exact field](../../issues/new?template=wrong-data.yml) — wrong country, wrong cycle, closed role, bad sponsorship flag. Those reports usually fix a rule, which fixes every other role too.

Also here: [PRIVACY.md](PRIVACY.md) (what the email list stores — an address and nothing else) · [SECURITY.md](SECURITY.md) · [ARCHITECTURE.md](ARCHITECTURE.md) · [MIT licensed](LICENSE).

Built by one student with AI assistance, in the open. The part that matters isn't who typed it — it's that the rules, the tests, and every run's output are all public and checkable.

## Note on dates

The **Posted** column shows when a role was published, with the newest at the top. I pull the posting date straight from each job portal, but a lot of them don't expose one publicly, so those rows show a dash (—) for now instead of a guessed date. The ones that do publish a date are dated. Know the real date for a dashed role? Open a PR and I'll merge it.

Roles can close at any time, so always confirm on the company's own site before applying.
