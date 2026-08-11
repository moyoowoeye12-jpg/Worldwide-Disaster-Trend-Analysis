# Worldwide-Disaster-Trend-Analysis
The objective is to analyse worldwide disaster occurrence and impact over time, with emphasis on disaster frequency, mortality, affected population and reported economic damage. The completed Power BI dashboard provides an interactive trend view with Country, Region, Disaster Type and Disaster Subtype filters.


<img width="1405" height="792" alt="Screenshot (547)" src="https://github.com/user-attachments/assets/510e9121-f1e9-4424-830e-28aa3bd77286" />


𝐎𝐮𝐭𝐥𝐢𝐧𝐞


This document follows a technical report structure for documenting the Worldwide Disaster Analysis project. It records the data source, data structure, preprocessing considerations, analytical methodology, dashboard outputs, technical validation, findings, limitations, recommendations and future analytical work.


𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧

𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞

The objective is to analyse worldwide disaster occurrence and impact over time, with emphasis on disaster frequency, mortality, affected population and reported economic damage. The completed Power BI dashboard provides an interactive trend view with Country, Region, Disaster Type and Disaster Subtype filters.


𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐏𝐫𝐨𝐛𝐥𝐞𝐦

The analysis converts a large historical disaster-event dataset into measurable indicators that identify peak disaster years, mortality peaks, population-impact peaks, economic-damage peaks and long-term event trends.


𝐒𝐜𝐨𝐩𝐞


The supplied raw workbook contains 16,858 records and 47 variables. Start Year ranges from 2000 through 2026. The technical analysis focuses on the measures represented in the supplied Worldwide Disaster Trend dashboard and validates those outputs against the raw workbook.


𝐃𝐚𝐬𝐡𝐛𝐨𝐚𝐫𝐝 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞


Inspection of the supplied Power BI package shows report sections including Pre Analysis, Dashboard, In-Analysis 1, In-Analysis 2, In-Analysis 3, Post-Analysis and Recommendations. The supplied screenshot represents the Worldwide Disaster Trend analytical view.


𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐐𝐮𝐞𝐬𝐭𝐢𝐨𝐧𝐬


Which year recorded the highest number of disaster events?

Which year recorded the highest total deaths?

Which year recorded the highest total affected population?

Which year recorded the highest reported total damage?

How did disaster deaths, events, affected population and damage change over time?

How can the dashboard be technically validated against the raw source data?


𝐒𝐭𝐨𝐫𝐲 𝐨𝐟 𝐃𝐚𝐭𝐚


𝐃𝐚𝐭𝐚 𝐒𝐩𝐥𝐢𝐭𝐭𝐢𝐧𝐠 𝐚𝐧𝐝 𝐏𝐫𝐞𝐩𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠


𝐏𝐫𝐞-𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬

𝐃𝐞𝐬𝐜𝐫𝐢𝐩𝐭𝐢𝐯𝐞 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰

Indicator: Highest event-count year Raw Data Result: 2000 (869 records)

Indicator: Highest mortality year Raw Data Result: 2010 (336,900 deaths)

Indicator: Highest affected-population year Raw Data Result: 2002 (659,481,311 affected)

Indicator: Highest reported damage year Raw Data Result: 2011 (364,128,969 thousand US$)


𝐓𝐨𝐩 𝐃𝐢𝐬𝐚𝐬𝐭𝐞𝐫 𝐓𝐲𝐩𝐞𝐬


Rank: 1 Disaster Type: Flood Records: 4,273

Rank: 2 Disaster Type: Storm Records: 2,877

Rank: 3 Disaster Type: Road Records: 2,254

Rank: 4 Disaster Type: Water Records: 1,187

Rank: 5 Disaster Type: Epidemic Records: 894

Rank: 6 Disaster Type: Earthquake Records: 698

Rank: 7 Disaster Type: Extreme temperature Records: 568

Rank: 8 Disaster Type: Mass movement (wet) Records: 500

Rank: 9 Disaster Type: Explosion (Industrial) Records: 477

Rank: 10 Disaster Type: Fire (Miscellaneous) Records: 461


𝐑𝐞𝐠𝐢𝐨𝐧𝐚𝐥 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧


Region: Asia Records: 6,799 Share: 40.33%

Region: Africa Records: 4,327 Share: 25.67%

Region: Americas Records: 3,354 Share: 19.90%

Region: Europe Records: 1,957 Share: 11.61%

Region: Oceania Records: 421 Share: 2.50%

5.4 Initial Analytical Expectations

The pre-analysis indicates substantial variation by year, geography and disaster classification. Disaster frequency is expected to behave differently from severity measures because event count, mortality, population impact and economic damage represent different dimensions of disaster impact.


𝐈𝐧-𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬

𝐀𝐧𝐧𝐮𝐚𝐥 𝐃𝐢𝐬𝐚𝐬𝐭𝐞𝐫 𝐄𝐯𝐞𝐧𝐭 𝐓𝐫𝐞𝐧𝐝

Using DisNo. as the event identifier, the raw data records a maximum of 869 events in 2000. The annual series fluctuates over the study period, with higher event counts concentrated in the early 2000s and further variation in later years.


𝐀𝐧𝐧𝐮𝐚𝐥 𝐌𝐨𝐫𝐭𝐚𝐥𝐢𝐭𝐲 𝐓𝐫𝐞𝐧𝐝

Total deaths peak in 2010 at 336,900. Other high-mortality years include 2004, 2008 and 2023. This demonstrates that annual mortality can be driven by a limited number of high-severity events.


𝐀𝐧𝐧𝐮𝐚𝐥 𝐀𝐟𝐟𝐞𝐜𝐭𝐞𝐝-𝐏𝐨𝐩𝐮𝐥𝐚𝐭𝐢𝐨𝐧 𝐓𝐫𝐞𝐧𝐝


Total affected population peaks in 2002 at 659,481,311. The affected-population series is highly volatile, with major peaks in 2002 and 2015.


𝐀𝐧𝐧𝐮𝐚𝐥 𝐄𝐜𝐨𝐧𝐨𝐦𝐢𝐜 𝐃𝐚𝐦𝐚𝐠𝐞 𝐓𝐫𝐞𝐧𝐝


The raw Total Damage ('000 US$) field reaches its highest annual aggregate in 2011 at 364,128,969 thousand US$.

Technical unit interpretation: 364,128,969 in a field measured in thousands of US dollars equals US$364,128,969,000, approximately US$364.129 billion. The dashboard KPI should therefore explicitly state its unit or convert the value before presentation.


𝐑𝐞𝐥𝐚𝐭𝐢𝐨𝐧𝐬𝐡𝐢𝐩 𝐁𝐞𝐭𝐰𝐞𝐞𝐧 𝐌𝐞𝐭𝐫𝐢𝐜𝐬

Event count measures frequency, deaths measure mortality, Total Affected measures human impact, and Total Damage measures reported financial loss. A peak in one metric should not be assumed to imply a peak in another.


𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐓𝐞𝐜𝐡𝐧𝐢𝐪𝐮𝐞𝐬


Annual aggregation by Start Year

Count aggregation for event frequency

Sum aggregation for deaths, affected population and reported damage

Peak-year ranking

Geographic and categorical segmentation

Time-series line charts

KPI cards

Dashboard-to-source reconciliation


𝐏𝐨𝐬𝐭-𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐚𝐧𝐝 𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬


𝐊𝐞𝐲 𝐅𝐢𝐧𝐝𝐢𝐧𝐠𝐬


Disaster frequency is highest in 2000. The raw dataset records 869 disaster records.

Mortality is highest in 2010. 2010 records 336,900 deaths.

Population impact peaks independently of mortality. 2002 records 659,481,311 total affected.

Economic damage peaks in 2011. The raw unadjusted damage aggregate is 364,128,969 thousand US$.

Flood is the most frequent disaster type. Flood records total 4,273.

Asia has the largest regional event count. Asia records 6,799 events.

Reported damage is incomplete. 80.26% of records have no reported unadjusted damage value.


𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐕𝐚𝐥𝐢𝐝𝐚𝐭𝐢𝐨𝐧 𝐨𝐟 𝐃𝐚𝐬𝐡𝐛𝐨𝐚𝐫𝐝 𝐊𝐏𝐈𝐬


Dashboard KPI: Peak Disaster Year Dashboard Display: 2000; 869 events Raw Workbook Recalculation: 2000; 869 events Status: Validated

Dashboard KPI: Peak Mortality Year Dashboard Display: 2010; 336,900 deaths Raw Workbook Recalculation: 2010; 336,900 deaths Status: Validated

Dashboard KPI: Year of Highest Damages Dashboard Display: 2011; displayed as $364 Million Raw Workbook Recalculation: 2011; 364,128,969 thousand US$ = $364.129 billion Status: Unit interpretation requires correction

Dashboard KPI: Highest Affected Population Year Dashboard Display: 2002; displayed value 336,900 Raw Workbook Recalculation: 2002; 659,481,311 affected Status: KPI value mismatch

Technical control observation: the peak years for events, mortality, affected population and damage are supported by the raw workbook. The affected-population KPI displays 336,900 although the raw Total Affected aggregate for 2002 is 659,481,311. The damage KPI also requires explicit unit handling because the source field is denominated in thousands of US dollars.

𝐃𝐚𝐭𝐚-𝐭𝐨-𝐃𝐚𝐬𝐡𝐛𝐨𝐚𝐫𝐝 𝐂𝐨𝐧𝐬𝐢𝐬𝐭𝐞𝐧𝐜𝐲

The supplied trend charts contain annual values that correspond to the source aggregation at visible points. The principal control issues identified from the supplied materials are concentrated in KPI presentation, unit labeling and synchronization between dashboard measures and source definitions.


𝐃𝐚𝐭𝐚-𝐭𝐨-𝐃𝐚𝐬𝐡𝐛𝐨𝐚𝐫𝐝 𝐂𝐨𝐧𝐬𝐢𝐬𝐭𝐞𝐧𝐜𝐲


The dashboard uses four KPI cards and four time-series charts. The KPI cards summarize peak event frequency, mortality, damage and affected population. The trend charts show annual deaths, damage, disaster events and affected population. Country, Region, Disaster Type and Disaster Subtype are interactive filters.


𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧 𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐀𝐬𝐬𝐞𝐬𝐬𝐦𝐞𝐧𝐭

Visual: KPI cards Purpose: Highlight peak years and headline totals Technical Assessment: Effective for scanning; affected-population value and damage units require correction.

Visual: Yearly Death Trend Purpose: Show annual mortality volatility Technical Assessment: Appropriate time-series visualization.

Visual: Total Damage Trend Purpose: Show annual economic impact Technical Assessment: Appropriate if source unit is explicitly displayed.

Visual: Yearly Disaster Event Trend Purpose: Show annual event frequency Technical Assessment: Appropriate for temporal frequency analysis.

Visual: Total Affected Trend Purpose: Show annual population impact Technical Assessment: Appropriate, with a clear definition of Total Affected.

Visual: Slicers Purpose: Support geographic and disaster-category segmentation Technical Assessment: Appropriate for interactive exploration.


𝐃𝐚𝐬𝐡𝐛𝐨𝐚𝐫𝐝 𝐃𝐞𝐬𝐢𝐠𝐧 𝐎𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧

The visual hierarchy separates headline indicators from trend analysis and provides categorical filters on the left. For technical reporting, the dashboard should explicitly document measure definitions, source units, data freshness and completeness.


𝐑𝐞𝐜𝐨𝐦𝐦𝐞𝐧𝐝𝐚𝐭𝐢𝐨𝐧𝐬 𝐚𝐧𝐝 𝐎𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧𝐬

𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐑𝐞𝐜𝐨𝐦𝐦𝐞𝐧𝐝𝐚𝐭𝐢𝐨𝐧𝐬

Correct the affected-population KPI. Bind the KPI to the same Total Affected aggregation used by the trend measure so that 2002 displays 659,481,311 for the supplied workbook.

Correct damage units. Label the damage measure as thousand US$ or convert it to million/billion US$ before presentation.

Add data freshness context. State the EM-DAT version and extraction date, especially because 2026 is a partial year.

Document measure definitions. Define Event Count, Total Deaths, Total Affected and Total Damage in the dashboard.

Handle missing damage values explicitly. Do not interpret missing financial values as zero without a documented rule.

Add completeness indicators. Show the percentage of records with reported values for major impact metrics.

Add a partial-year warning. Prevent users from interpreting 2026 as a complete annual observation.



𝐀𝐧𝐚𝐥𝐲𝐭𝐢𝐜𝐚𝐥 𝐑𝐞𝐜𝐨𝐦𝐦𝐞𝐧𝐝𝐚𝐭𝐢𝐨𝐧𝐬


Add disaster-severity metrics such as deaths per event and affected population per event.

Add regional trend comparisons.

Separate Natural and Technological disaster groups.

Provide adjusted versus unadjusted damage views.

Add a data-completeness panel.

Introduce year-over-year percentage change for the core indicators.


𝐃𝐞𝐜𝐢𝐬𝐢𝐨𝐧-𝐌𝐚𝐤𝐢𝐧𝐠 𝐎𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧


The dashboard is suitable for descriptive disaster monitoring because it combines headline indicators, temporal trends and categorical filters. Before formal operational or policy use, data completeness, unit consistency and KPI reconciliation should be treated as mandatory controls.




