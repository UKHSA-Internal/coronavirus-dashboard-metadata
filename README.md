# Coronavirus (COVID-19) in the UK - Metadata

This repository is used to manage the metric definitions and metric availability text used in the website.  The definitions are written using basic markdown syntax.  When the repository is published each markdown is created with its own url and these are called and surfaced as required within the website pages.  

These data definitions are surfaced in the following ways:  

* Tooltips/hover text - single sentence for each headline metric identifying it uniquely including the 
date of event or publishing represented
* Modals - windows that open by clicking on headline indicators providing more detailed scrollable definitions
* About tabs - provided in detail at card radio button level to specifically define the data within that card display
* About the data document - all detailed definitions appended into a single document.  Each header is an anchor 
point to support signposting from elsewhere within the site


The repository work closely with the [coronavirus-dashboard-layouts](https://github.com/publichealthengland/coronavirus-dashboard-layouts) repository which also includes the following additional way to surface metric definitions as well as identifying which metadata 
files to surface in each layout location within the site:  

* Card abstracts - one or two sentences introducing the metrics presented within each card - defined at card level 
via the layouts GitHub repository and not within this repo.




### Structure of the repository

* base markdown files - The main detailed definition for each metric theme is defined in a base file - this file is then re-used in many locations. Base files are not specific to an individual metric, rather a group of related metrics - so the event date and publish date, daily and cumulative versions of a metric would be defined in a single base file.  This makes the definitions more manageable and consistent by avoiding the need to duplicate text in multiple places.  Base files must be saved at the modals/base directory level.

* modal markdown files - these generally include just a title and a single sentence defining the specific metric being surfaced, followed by calling the inclusion of the relevant base markdown file(s).  The modal filename must match the headline metric name exactly and the files must be saved at the top modal directory level.

* card markdown files - these define the 'About tab' definitions and generally include just a title and a single sentence defining each specific metric being surfaced, followed by calling the inclusion of the relevant base markdown file(s).  These may define two or more metrics one after another if the card presents multiple metrics. The filenames are flexible but the files must be saved in the modal/cardMetadata/sub-directory for the relevant page.

* about markdown file - this is a single file saved at the top modal directory level using filename about.md and defines the overarching 'About the data' document.  All base files should be included here, each with its own header and, if appropriate, single sentence of introduction.  


## Other repositories

Different parts of the Coronavirus dashboard service are maintained in their respective 
repositories, itemised as follows:
 
- [API v.1](https://github.com/publichealthengland/coronavirus-dashboard-api-v1) - Main API service for the data, lookup tables, CMS, and metadata.
- [API v.2.0](https://github.com/publichealthengland/coronavirus-dashboard-api-v2) - Batch downloads service [DEPRECATED in favour of v2.1]
- [API v.2.1](https://github.com/publichealthengland/coronavirus-dashboard-api-v2-server) - Batch downloads service
- [Generic APIs](https://github.com/publichealthengland/coronavirus-dashboard-generic-apis) - APIs that power the map, navigation, hierarchy, and relations
- [Coronavirus Dashboard](https://github.com/publichealthengland/coronavirus-dashboard) - Details pages
- [Frontend Server](https://github.com/publichealthengland/coronavirus-dashboard-frontend-server) - Home and Postcode pages
- [Easy-Read Server](https://github.com/publichealthengland/coronavirus-dashboard-easy-read) - Easy-read pages and PDF generator
- [Layout CMS](https://github.com/publichealthengland/coronavirus-dashboard-layouts) - Definition of contents
- [ETL Service](https://github.com/publichealthengland/coronavirus-dashboard-pipeline-etl) - Post-pipeline data processing and deployment
- [Terraform](https://github.com/publichealthengland/coronavirus-dashboard-terraform) - Infrastructure as Code [DEPRECATED in favour of ARM templates]


## Credits
This service is developed and maintained by [Public Health England](https://www.gov.uk/government/organisations/public-health-england).
