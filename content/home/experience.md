---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Data Engineer
    company: will bank
    company_url: 'https://www.willbank.com.br/'
    company_logo: will
    location: Brazil (Remote)
    date_start: '2022-08-01'
    date_end: ''
    description: |2-        
        * Refactored and expanded the bank's credit engine, workin with Python microservices, AWS stack, Terraform and DataDog for observability.
        * Developed of a new data pipeline to periodically ingest datasets of over 150M rows instead of making on demand requests using PySpark, AWS Glue and AWS EKS, lowering monthly costs by 7%.
        * Integrated pipelines with the data lake (AWS S3 + Athena), allowing data scientists to have access to new variables.
        * Aligned with business teams to deploy new credit models and policies.
        * Utilized SQL to extract performance metrics and generate samples for testing new features for business teams.

  - title: Data Analyst
    company: will bank
    company_url: 'https://www.willbank.com.br/'
    company_logo: will
    location: Brazil (Remote)
    date_start: '2021-06-01'
    date_end: '2022-08-31'
    description: |2-
      * Developed exploratory and in-depth analysis to give inputs for business decision making, such as selection of fraud
      * score suppliers and expansion of experiments using Python and Excel.
      * Participated in the credit engine Data Engineering team, using Python and AWS to develop a new project that increased monthly approval rate by 3%.
      * Created the acquisition funnel dashboard, modeling data with dbt and AWS Athena and visualization with Looker and Metabase.

  - title: Data Analyst
    company: TruckPad
    company_url: 'https://www.truckpad.com.br/'
    company_logo: truckpad_logo
    location: São Paulo, Brazil
    date_start: '2019-09-01'
    date_end: '2021-06-01'
    description: |2-
      * Built dashboards and analysis for different areas of the company (Product, Marketing and Operations), such as retention cohorts in Periscope (data viz tool).
      * Coordinated the migration of the business intelligence database from MySQL to Postgres.
      * Developed exploratory and in-depth analysis to give inputs for business decision making, such as A-ha moment framework analysis.

  - title: Finance Analyst
    company: Loggi
    company_url: 'https://www.loggi.com/'
    company_logo: loggi_logo
    location: São Paulo, Brazil
    date_start: '2018-04-01'
    date_end: '2019-08-01'
    description: |2-
      * Responsible for the Billing, Receiving, and Reimbursement processes, creating routines and reports for each process
      * Coordinated the team and trained two interns.
      * Consolidated reports for accounting (Revenue, Accounts Receivable, Provision for Bad Debts) using SQL for extracting
      data (Looker).

  - title: Finance Analyst
    company: Finenge
    company_url: 'https://www.finenge.com/'
    company_logo: finenge_logo
    location: São Paulo, Brazil
    date_start: '2017-06-01'
    date_end: '2018-04-01'
    description: |2-
      * Provided consulting for companies in search of long-term funding.
      * Complex financial modeling using accounting and financial statements, customers’ business and strategical planning and market research.
      * Produced investment thesis presentations and memorandums by working collaboratively with customers, including onsite visits.

  - title: Intern
    company: Aqua Capital
    company_url: 'https://aqua.capital/'
    company_logo: aqua_logo
    location: São Paulo, Brazil
    date_start: '2016-01-01'
    date_end: '2016-12-01'
    description: |2-
      * Provided consulting for companies in search of long-term funding.
      * Complex financial modeling using accounting and financial statements, customers’ business and strategical planning and market research.
      * Produced investment thesis presentations and memorandums by working collaboratively with customers, including onsite visits.

design:
  columns: '1'
---
