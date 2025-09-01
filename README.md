# AFRO-ENTERTAINERS-ANALYTICS-REPORT-SQL-Power-BI

## Table of Content

[Project Overview](#ProjectOverview)

[Objectives](#Objectives)

[Data Source](#DataSource)

[Tools Used](#ToolsUsed)

[Skills_Demonstrated](#Skills_Demonstrated)

[Insights](#Insights)

[Recommendations](#Recommendations)

## Project Overview

We profiled 20 African entertainers to understand demographics, geography, career progression, popularity, and wealth. We built a small relational dataset, used SQL to clean/shape it into analysis-ready views, and used Power BI for modeling, DAX measures, and interactive dashboards.

## Data Source
Manually compiled tabular dataset (CSV/Excel) of 20 entertainers with fields including: name, gender, country, genre, years worked, experience level, awards, social media followers (M), marital status, age group, and estimated net worth (USD, millions).

## Tools
SQL (PostgreSQL / SQL Server compatible) for cleaning, joins, deduping, deriving columns, and creating views.

Power BI for data model, DAX, visuals, and slicers.
## Data Modelling
Import & Cleaning: standardized country and genre labels, consistent casing, removed duplicates, ensured numeric types for net worth, followers, and years worked.

Derived Columns:

Age Group: Young Adult, Early Midlife, Mature Adult, Legacy Stage.

Experience Level: Rising, Emerging, Established, Veteran.

Measures (DAX):

Avg Net Worth ($M), Avg Years Worked, Total Entertainers, Max Followers (M).

Modeling: single-table star-like setup with slicers for Gender, Age Group, Experience Level, Genre, and Marital Status.

Design: consistent palette, card KPIs, bar/column charts, donuts, map.

## Skills Demonstrated

Data transformation • SQL modeling & views • Power BI modeling • DAX • Visualization • Critical thinking • Problem-solving

## Objectives

Profile entertainers by demographics, geography, and experience.

Quantify career progression using years worked, popularity, and awards.

Examine wealth patterns and identify top/least earners.

Explore family/marital status links to wealth and preferences.

Produce actionable insights for talent scouts, labels, and marketers.

## Data Analysis & Visualization (Dashboard-by-Dashboard)

<img width="2770" height="1475" alt="SQL" src="https://github.com/user-attachments/assets/011eb17d-1a27-49a8-8bcd-38c0e82c7322" />

- Key KPIs: Avg Net Worth ≈ $9.98M, Average Age ≈ 36, Total = 20, Males = 12, Females = 8.
- Top Five Wealthy ($M): Davido (40), Burna Boy (35), Wizkid (32), Khaby Lame (18), Angélique Kidjo (15).
- Age Group Distribution: Young Adults dominate (12; 60%), followed by Early Midlife (6; 30%), small shares for Legacy and Mature Adults (1 each).
- Politics Involvement: Majority not involved (≈55%) vs ≈45% involved.
- Top Social Media Followers (M): Khaby Lame (80) leads by a wide margin; Davido (30), Tiwa Savage (19), Diamond Platnumz (19), Wizkid (18).
- Nationality Map: Nigeria leads (8), then South Africa (3). Ghana & Kenya (2 each). Benin, Egypt, Gambia,

<img width="2635" height="1490" alt="SQL2" src="https://github.com/user-attachments/assets/1c9cb4e7-4f7e-4341-9a21-4e28d27a3c07" />

- Years of Experience Distribution: Established (9) is the largest segment; Emerging (4) and Veteran (4) are tied; Rising (3) is smallest.
- Age Group Distribution (bars): confirms the youth skew—12 Young Adults, 6 Early Midlife.
- Country Distribution (bar funnel): mirrors the map—Nigeria dominant (8), South Africa (3), Ghana & Kenya (2 each), others at 1.
- Effect of Career Length on Net Worth (by individual):
- Longer careers often correlate with higher net worth (e.g., Davido’s 14 years with $40M; Burna Boy 15 years with $35M), but not perfectly—Khaby Lame shows high net worth traction with fewer years, driven by digital virality.

<img width="2637" height="1475" alt="SQL3" src="https://github.com/user-attachments/assets/320e3a24-0c68-4243-b504-e1eff6a3a60b" />

- Top 5 Wealthiest ($): Davido (40), Burna Boy (35), Wizkid (32), Khaby Lame (18), Angélique Kidjo (15) — consistent with overview.
- Top 5 by Followers (M): Khaby (80) >> Davido (30) >> Tiwa (19) ≈ Diamond Platnumz (19) ≈ Wizkid (18).
- Female Grammy Recipients Under 40: Tems (27), Tyla (21) — highlights young award-winning talent.
- Least 5 Earners ($M): Ayra Starr (1.50), John Dumelo (1.20), Sona Jobarteh (1.00), Pascal Tokodi (0.50), Menna Shalabi (0.29).
- Average Net Worth by Marital Status (donut): married group shows largest share of total net worth; singles moderate; divorced smallest.

- <img width="2630" height="1480" alt="SQL4" src="https://github.com/user-attachments/assets/a2cdb844-11bc-4ee6-a74f-81ba7de6631b" />

- Marital Status Distribution: Married (12; 60%), Single (6; 30%), Divorced (2; 10%).
- Net-Worth Share by Marital Status ($M): Married account for the largest proportion (≈43%); Singles (≈38%); Divorced (≈19%).
- Marital Status by Gender (horizontal bars): Female Single (6) and Male Single (6) highlight an even single pool; Male Married (5) notable; very small divorced counts per gender.
- Genre Preferences by Marital Status: small-n patterns show Afrobeats heavily represented across statuses; niche blends (Amapiano/Pop; Dancehall/Reggae) appear among singles.

## Insights 

- Nigeria as the powerhouse: supplies 40% of the sample and most of the top earners—critical for A&R and brand partnerships.

- Youthful engine: 60% Young Adults suggest a long runway for growth; early career support compounds returns.

- Experience still matters—unless you go viral: years worked correlate with wealth, but digital platforms can fast-track outliers.

- Popularity ≠ wealth (always): Social reach is necessary but insufficient; monetization (catalog, touring, endorsements) drives the gap.

- Family status is a proxy for tenure: married entertainers hold a bigger slice of total wealth, likely reflecting time in industry, stability, and compounding assets.

- Female excellence spotlight: Tems and Tyla underscore a rising cohort of globally recognized young women in Afrobeats/Afropop.

  A&R & Label Focus: Prioritize Nigeria & South Africa; cultivate Ghana/Kenya.

## Recommendations

- Prioritize Nigeria & South Africa; cultivate Ghana/Kenya.

- Optimize catalog streaming, sync, international routing.

- Monetization Playbook for High-Reach/Lower-Wealth: direct-to-fan drops, live sessions, tiered endorsements by audience geo.

- Tour Targeting: diaspora cities (London, NYC, Toronto, Paris) + regional circuits.

- Women-in-Music Initiatives: mentorship, PR, prime festival slots.




