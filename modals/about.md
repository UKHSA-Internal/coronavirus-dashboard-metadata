> During the holiday period, the COVID-19 Dashboard will be updated every day, but the amount of data being updated will vary. The following information is provided to assist forward planning only and is subject to change. 
>
>UK cases and deaths will be updated every day throughout the holiday period, with the following service changes: 
>England - data updated daily
>Northern Ireland - no data on 24-28 December
>Scotland - no data on 25-28 December and 1-4 January
>Wales - no data on 25 December and 1 January
>
>UK totals for each day will reflect the sum of the nations which reported data. Cases and deaths that would have been reported during these periods are likely to instead be reported on the following days. As a result, any changes to published data should be interpreted with caution during this period, as they may be a result of changes to reporting schedules.
>
>Testing and capacity metrics will be updated on working days. This means they will not be updated 25-28 December 2020, and data for this period will instead be updated on 29 December 2020.
>
>Healthcare statistics will be published when data are provided by NHS England and NHS Improvement and health authorities in the Devolved Administrations, but may experience interruptions during this period.

> 20 October 2020: Read the Public Health Matters blog [The COVID-19 dashboard: a design and feature evolution](https://publichealthmatters.blog.gov.uk/2020/10/20/covid-19-dashboard-a-design-and-feature-evolution/)

## Table of contents

## Introduction

The dashboard presents progress of the coronavirus pandemic as an up to date and authoritative summary of key information. This includes levels of infections, the impact on health in the UK and on measures taken to respond.  It presents a dynamic contemporary picture and is updated daily. 

It meets a strongly expressed need from the public for timely updates at national and local level to ensure good understanding of the day to day progress of the pandemic. This is achieved through interactive maps and trends over time of key measures relating to testing capacity and activity, newly confirmed cases, hospital admissions and deaths.

The dashboard provides a tool for developers and analysts by supporting reuse of data through access to the results in machine readable files and via an API.
To ensure high public value and quality, the statistics are presented in line with the Code of Practice for Statistics. Information is provided on the strengths and weaknesses of the data to help users to interpret them correctly. 

Full definitions for the metrics presented in the dashboard are provided below.

## R number and growth rate

Estimated COVID-19 R number and growth rate on the reporting date, expressed as ranges.

{inc:base/rNumberRate.md|modals}

## Daily and cumulative numbers of tests

Number of positive, negative or void COVID-19 test results, across all types of testing, reported on or up to the reporting date.

{inc:base/tests_processed.md|modals}

## Testing capacity

Total number of lab-based tests capable of being performed by laboratories on the reporting date.

{inc:base/testingCapacity.md|modals}

## Weekly number of people receiving a PCR test and positivity

The number of people who received a PCR test in the previous 7 days, and the percentage of people who received a PCR test in the previous 7 days, who had at least one positive COVID-19 PCR test result.

{inc:base/PCRTestingPositivity.md|modals}

## Daily and cumulative numbers of cases 

Number of people with a positive COVID-19 virus test (either lab-reported or lateral flow device) on or up to the specimen date or reporting date (depending on availability).

{inc:base/cases.md|modals}

## Daily and cumulative numbers of patients admitted to hospital

Numbers of patients admitted to hospital with COVID-19 on or up to the reporting date. 

{inc:base/admissions.md|modals}

## Patients in hospital

Total number of confirmed COVID-19 patients in hospital on the reporting date.

{inc:base/patientsInHospital.md|modals}

## Patients in mechanical ventilation beds

Total number of mechanical ventilation beds that are occupied by COVID-19 patients on the reporting date.

{inc:base/covidPatientsInMVBeds.md|modals}

## Daily and cumulative deaths within 28 days of a positive test

Total number of people who had a positive test result for COVID-19 and died within 28 days of the first
positive test, reported on or up to the date of death or reporting date (depending on availability).

{inc:base/deaths28Days.md|modals}

## Methodologies

{inc:base/sevenDayMetrics.md|modals}

{inc:base/rates.md|modals}

{inc:base/rolling_averages.md|modals}

## Downloads

{inc:base/msoaCases.md|modals}


We are no longer publishing data at LSOA level following guidance from the Office for National Statistics published by the Department for Health and Social Care: [Office for National Statistics recommendation for publishing data at small geographies for NHS Test and Trace](https://www.gov.uk/government/publications/office-for-national-statistics-recommendation-for-publishing-data-at-small-geographies-for-nhs-test-and-trace)


{inc:base/ageCases.md|modals}
### Legacy CSV downloads

The CSV downloads provided from the previous version of the dashboard are available on the download data page. The legacy deaths download is no longer available as the data series has been discontinued.

These files will be updated alongside the main website on a daily basis for the foreseeable future.
However, users are strongly recommended to use the API instead, which give access to the full range of
data in the live site. See the [Developer's guide](https://coronavirus-staging.data.gov.uk/developers-guide)
for details.