
## Table of contents

## About the coronavirus (COVID-19) in the UK dashboard

Testing Testing

The dashboard is an up-to-date and authoritative summary of key information about the COVID-19 pandemic. This includes levels of infections, the impact on health in the UK and on measures taken to respond.  We update it every Thursday at 6pm to present a dynamic contemporary picture. 

The dashboard meets a strong public need for timely updates at national and local level to ensure good understanding of the progress of the pandemic. We show how the pandemic is changing through: 
- interactive maps
- trends over time of key measures relating to testing capacity and activity, newly-confirmed cases, hospital admissions and deaths

The dashboard supports developers and analysts to reuse data through access to the results in machine-readable files and via an API.

To ensure high public value and quality, the statistics are presented in line with the Code of Practice for Statistics. We provide information on the strengths and weaknesses of the data to help users to interpret them correctly. 

## About the data

The coronavirus (COVID-19) in the UK dashboard provides information about the COVID-19 pandemic. The main topics covered are:
-	cases
-	deaths
-	healthcare
-	testing
-	vaccinations

All data are updated weekly on Thursdays at 6pm.

For cases by specimen date and for deaths by date of death, every Thursday we update the daily numbers of new and cumulative cases and deaths for all previous days for which data are available.

For cases and deaths by report date, we report the number of new cases or deaths as the total number newly reported since the previous week. Previous week’s figures by report date are not revised as they are a record of what was reported at the time.
Full definitions for the metrics presented in the dashboard are provided in the 

Full definitions for the metrics presented in the dashboard are provided in the [Metrics documentation](https://coronavirus.data.gov.uk/metrics)

### Cases
A case is when someone is confirmed as having COVID-19 through a positive test. People can be counted as a case more than once if they test positive for COVID-19 again after a certain time period. The time period varies across the different UK nations.

We show cases by specimen date – the date the sample was taken from the person that identified the infection.

At the height of the pandemic, we showed cases by date reported – the date the case was first included in the published totals. Cases by report date are no longer shown on the dashboard but are still available to download via the API.

#### Case rates
To compare numbers of cases across different areas which have different numbers of people living in them, we also show case rates. We calculate these by dividing the total number of cases in the period by the number of people living in the area and multiplying by 100,000.

You can see case rates for the latest 7 days from the last update on the interactive map, for example.

#### Allocating cases to areas
Cases are allocated to where the person usually lives. This is normally the address they provide when they are tested.

#### Tests used to identify cases
Cases are identified by testing for the SARS CoV-2 virus. Tests can be either:
-	laboratory-based polymerase chain reaction (PCR) tests
-	rapid lateral flow tests – swab tests that don’t need to be sent to a laboratory.

The different UK nations vary in how they use these to count positive cases. For example, Wales does not count positive results from lateral flow tests as cases.
 
### Deaths
The dashboard shows 2 main types of death data:
-	deaths where COVID-19 is mentioned on the death certificate as one of the causes (deaths from COVID)
-	deaths within 28 days of a positive COVID-19 test (deaths with COVID)

Data are shown by the date someone died (date of death).

We previously also showed deaths by when the death was reported (date reported). Deaths by report date are no longer shown on the dashboard but are still available to download via the API.

The different UK nations vary in how they count COVID-19 deaths. Find out more information on this in the [Metrics documentation](https://coronavirus.data.gov.uk/metrics).

#### Deaths with COVID-19 on the death certificate
Deaths with COVID-19 on the death certificate (deaths from COVID-19) data are updated weekly by national statistics bodies in the 4 UK nations. The data represents represent people who have died from COVID-19, as decided by the clinician registering the death. There is a time delay of around 11 days between the occurrence, registration and reporting of a death.

#### Deaths within 28 days of a positive test 
Deaths within 28 days of a positive COVID-19 test are included whether or not COVID-19 was a cause of death shown on the death certificate.

People who died more than 28 days after a positive COVID-19 test are not included in these figures, whether or not COVID-19 was a cause of death on the death certificate.

#### Allocating deaths to areas
Deaths are allocated to the area the person usually lived in. If more than one address is identified, the address given in the death registration from the Office for National Statistics (ONS) is used.

### Healthcare
The healthcare section contains data about COVID-19 patients in hospital:
-	patients admitted to hospital with COVID-19
-	patients currently in hospital with COVID-19
-	COVID-19 patients in hospital beds with a mechanical ventilator to help them breathe.

The different UK nations vary in how they collect data about COVID-19 patients in hospitals. Find out more information on this in the [Metrics documentation](https://coronavirus.data.gov.uk/metrics).

### Tests
We report data on tests being carried out for COVID-19. These include:
-	tests for the SARS-CoV-2 virus – these test if a person currently has COVID-19 and include rapid lateral flow and polymerase chain reaction (PCR) tests
-	tests for COVID-19 antibodies – these test if a person has had COVID-19 in the past and now has antibodies against the virus (proteins the immune system makes to fight infection).

We show tests by either:
-	date reported – the date the test was included in the published totals
-	specimen date – the date the sample was taken from the person being tested.

We include data on positive, negative and inconclusive (void) COVID-19 virus test results.

The most common types of test are PCR and lateral flow tests.

#### Lateral flow tests 
Swab tests that give results in less than an hour, without needing to go to a laboratory.

#### PCR tests
PCR tests are sent to a laboratory to be analysed. They are sometimes used to confirm cases suspected after a positive lateral flow test.

### Vaccinations
We show data on the number of people who have been vaccinated against COVID-19 since the UK vaccination programme began in December 2020. Data are shown by either:
-	when someone was vaccinated (vaccination date)
-	when the vaccination was reported (date reported).

#### Vaccine doses
COVID-19 vaccines are given in several doses. We include data on:
-	first doses
-	second doses
-	third or booster doses.

Booster doses were offered from September 2021 to everyone aged 16 and over (and some children aged 12 to 15) who had been given a second dose of the vaccine at least 3 months ago. Extra booster doses were also offered to specific groups, such as people with severely weakened immune systems, called spring and autumn boosters. 

#### Percentage vaccinated
We include data on the percentage of people vaccinated for some areas.
For the UK, we divide the total number of vaccinations given to people of all ages by the mid-year 2020 population estimate for people aged 12 and over, published by the Office for National Statistics.

The different UK nations vary in how they calculate percentage vaccinated.

#### Allocating vaccinations to areas
The different UK nations vary in how they allocate vaccinations to areas.
At a national level, England, Northern Ireland and Wales include all vaccinations given in that country. Scotland includes all vaccinations given in Scotland, plus Scottish residents vaccinated elsewhere if recorded within the Vaccination Management Tool.

### Data availability by area

Different data is shown for different geographical areas.

#### Cases, testing and deaths data

These are shown for:
- the whole UK up to 19/05/2022 when Northern Ireland stopped reporting these data
- nations (England, Northern Ireland (up to 19/05/2022), Scotland and Wales)
- English regions
- local authorities in England, Northern Ireland (up to 19/05/2022), Scotland and Wales

#### Vaccinations data

These are shown for:
- the whole UK
- nations (England, Northern Ireland, Scotland and Wales)
- English regions
- local authorities in England, Northern Ireland, Scotland and Wales

#### Healthcare data

These are shown for:
- the whole UK
- nations (England, Northern Ireland, Scotland and Wales)
- English NHS regions
- English NHS trusts

The availability of data for different areas varies between metrics. Some metrics are not available for the whole UK because we do not have data from all nations, and so will only be shown when the area they are available for (for example, England) is selected. Healthcare data for the UK are updated to the latest date that we have data for all nations. More recent data may be available if an individual nation is selected. 

Cases by specimen date and vaccination uptake data are also available for middle layer super output areas (MSOA) in England. These areas are smaller than local authorities, so show data at the most local level. These data are shown on the interactive maps and when using the postcode search.

We are no longer publishing data at lower super output area (LSOA) level following guidance from the Office for National Statistics published by the Department for Health and Social Care: [Office for National Statistics recommendation for publishing data at small geographies for NHS Test and Trace](https://www.gov.uk/government/publications/office-for-national-statistics-recommendation-for-publishing-data-at-small-geographies-for-nhs-test-and-trace)

## Blogs about the COVID-19 dashboard

29 November 2022: [Changes to the COVID-19 dashboard and COVID-19 vaccination surveillance report](https://ukhsa.blog.gov.uk/2022/11/29/changes-to-the-covid-19-dashboard-and-covid-19-vaccination-surveillance-report/?_ga=2.240456003.1770260184.1669889785-595865933.1645545809)

September 2022: [Dashboard Confessional: Civil Service World interview with Clare Griffiths](https://www.civilserviceworld.com/in-depth/article/read-the-september-2022-issue-of-civil-service-world)

28 June 2022: [The COVID-19 Dashboard Moves to Weekly Updates](https://ukhsa.blog.gov.uk/2022/06/28/the-covid-19-dashboard-moves-to-weekly-updates/)

28 February 2022: [Voluntary Application: Demonstrating the value of the COVID-19 Dashboard through the Code of Practice for Statistics](https://code.statisticsauthority.gov.uk/case-studies/voluntary-application-demonstrating-the-value-of-the-covid-19-dashboard-through-the-code-of-practice-for-statistics/)

4 February 2022: [Changing the COVID-19 Case Definition](https://ukhsa.blog.gov.uk/2022/02/04/changing-the-covid-19-case-definition/)

20 January 2022: [Reporting the vital statistics - how data management has been central to the handling of the pandemic](https://ukhsa.blog.gov.uk/2022/01/20/reporting-the-vital-statistics-how-data-management-has-been-central-to-the-handling-of-the-pandemic/)

16 December 2021: [What Does COVID-19 look like in your area?](https://ukhsa.blog.gov.uk/2021/12/16/what-does-covid-19-look-like-in-your-area/)

15 December 2021: [Statistics are vital: An interview with Clare Griffiths](https://rss.org.uk/news-publication/news-publications/2021/general-news/statistics-are-vital-an-interview-with-clare-griff/)

11 December 2021: [UK COVID-19 dashboard built using Postgres and Citus for millions of users](https://techcommunity.microsoft.com/t5/azure-database-for-postgresql/uk-covid-19-dashboard-built-using-postgres-and-citus-for/ba-p/3036276)

22 March 2021: [Behind the scenes: Expanding the COVID-19 dashboard](https://publichealthmatters.blog.gov.uk/2021/03/22/behind-the-scenes-expanding-the-covid-19-dashboard/)

8 February 2021: [Counting deaths during the pandemic](https://publichealthmatters.blog.gov.uk/2021/02/08/counting-deaths-during-the-pandemic/)

9 December 2020: [Lateral flow testing – rapid tests to detect COVID-19](https://publichealthmatters.blog.gov.uk/2020/12/08/lateral-flow-testing-new-rapid-tests-to-detect-covid-19/)

20 October 2020: [The COVID-19 dashboard: a design and feature evolution](https://publichealthmatters.blog.gov.uk/2020/10/20/covid-19-dashboard-a-design-and-feature-evolution/)

4 September 2020: [The COVID-19 dashboard: bringing together data and statistics in one place](https://publichealthmatters.blog.gov.uk/2020/09/04/the-covid-19-dashboard-bringing-together-data-and-statistics-in-one-place/)

12 August 2020: [Behind the headlines: Counting COVID-19 deaths](https://publichealthmatters.blog.gov.uk/2020/08/12/behind-the-headlines-counting-covid-19-deaths/)

15 May 2020: [Coronavirus (COVID-19): Real-time tracking of the virus](https://publichealthmatters.blog.gov.uk/2020/05/15/coronavirus-covid-19-real-time-tracking-of-the-virus/)

23 April 2020: [Coronavirus (COVID-19): Using data to track the virus](https://publichealthmatters.blog.gov.uk/2020/04/23/coronavirus-covid-19-using-data-to-track-the-virus/)

## Compliance with the Code of Practice for Statistics

[Statement of voluntary application of the Code of Practice for Statistics](https://coronavirus.data.gov.uk/details/compliance)

## Other Government Statistics on COVID-19 

### COVID-19 Health Inequalities Monitoring in England tool (CHIME) 

[The national CHIME tool](https://www.gov.uk/government/statistics/covid-19-health-inequalities-monitoring-in-england-tool-chime) from the Office for Health Improvement and Disparities brings together data to monitor the direct impacts of COVID-19 on health inequalities. This includes data on mortality rates, hospital admissions, confirmed cases and vaccinations. 

The CHIME tool presents inequality breakdowns, including by: 

- age 
- sex 
- ethnic group 
- level of deprivation 
- geographical area 

The CHIME tool: 

- shows how inequalities have changed through the pandemic and what the current cumulative picture is 
- brings together data so that users can access and use the intelligence more easily 
- provides indicators with a consistent methodology across different data sets to help understanding 
- supports users to identify and address inequalities within their areas and identify priority areas for recovery 

### Coronavirus (COVID-19) latest insights

A live roundup of the latest data and trends about the pandemic from the Office for National Statistics and other sources.

[The COVID-19 latest insights tool](https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/conditionsanddiseases/articles/coronaviruscovid19/latestinsights) brings together the latest information from government sources including:

- the COVID-19 Infection Survey (CIS) –contains high-level estimates on infection for England, Wales, Northern Ireland and Scotland.
- the Opinions and Lifestyle Survey – aims to understand the impact of the pandemic on people, households and communities in Great Britain
- deaths registered weekly – provides provisional counts of deaths registered in England and Wales, including deaths involving COVID-19, in the latest weeks for which data are available. These figures lag behind the daily figures published on the dashboard by at least 11 days.

### Wider Impacts of COVID-19 on Health monitoring tool (WICH)

[The national WICH monitoring tool](https://www.gov.uk/government/statistics/wider-impacts-of-covid-19-on-health-monitoring-tool) from the Office for Health Improvement and Disparities brings together metrics to assess the wider impacts of COVID-19 on health. 

It collates metrics across a range of wider impacts to provide a single point of access. This will help people to:

- monitor changes over time or against an agreed point in time
- make timely, informed decisions
- intervene early to mitigate against poor outcomes
- understand the wider context on population health
