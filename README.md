# Welcome to GovScan

## Important installation / version requirements
Python v3.9 is needed for the installation of the detectron package. Additionally, detectron is native to Linux, therefore if Windows users do not have a Windows Subsystem for Linux we recommend using Google Colab.

## Inital Problem Area
How can we take state plans for programs that are federally funded and state run (for example: Medicaid and child care subsidies) and make them digestible, easily searchable and actually useful to understand how 50 different states are implementing programs?

## Overview
GovScan is a vectorbase powered large language model (LLM) that simultaneously scans multiple large PDF documents and leverages generative artificial intellegence (AI) to return specific data requests. Unlike Chat GPT, GovScan maintains source disaggregation so that each return can be linked directly to the orignial document text in which it was found. This provides users with the abilty to search and compare large PDF documents with the click of a button almost like using the CTRL+F shortcut, but for an entire document library at once using natural language prompts like, "Hey GovScan, how does Pennsylvania determine Childcare Development Funding (CCDF) eligibility compared to Ohio?" GovScan has the potential to save users hours of time and millions of dollars in document research, all the while increasing the usability of large PDF documents.

**GovScan does not replace the human verification requirement**

## GovScan In Action: <a href="https://youtu.be/xSBFVVNNgTY" target="_blank">Prototype Demonstration</a>

## Background
With the advent of the Portable Document Format (PDF) in 1993 and then Adobe's decision to release the proprietary format as an open standard in 2008, the PDF has become widely adopted as the preferred method for securing digital documents. Private businesses and public agencies alike face the burden of managing extensive libraries of PDFs in a way that allows for easy retrieval when information is needed. The problem is, a single human seeking information from a PDF can only one review one document at a time. This limitation has resulted in costly hours spent reviewing documents one-by-one to find the desired information. 

## User Research Affinity Map
Our team interviewed numerous stakeholders to better understand how an AI document scanning tool might serve them best. A collaborative affinity map of user inputs organized by common trends can be found here: https://miro.com/app/board/uXjVNNbCIVc=/

## User Research Takeaways
After subsantial user research, here are the key takeaways that influenced our development of GovScan:
* Users look to large reports to help inform decisions making.
* Users tend to look for specific data points while reading reports.
* There is a mismatch in the existing mental models of two user groups - ones who create reports and ones who read them.
* At times the reports are generated at different points in time which makes recency of the report relative and hard to compare.
* Federal government is now focusing on data rather than reports.
* The laborious heavy lifting of using AI to find and parse data will leave the intellectual high-risk analysis in the hands of a human.
* Users rely on their internal network of stakeholders to ‘figure out’ what’s in reports and ask clarifying questions.
* There is a steep learning curve and significant friction in the comprehension of these reports.

## Suggested Use Cases 
#### Federal Goverment
* Use GovScan to navigate Federal Regulations, summarize public comments, and provide agencies the ability to efficiently compare data reporting across all 50 states.
#### State Goverment
* Use GovScan to improve federal program compliance and benchmark peer competitors. 
#### Local Government
* Use GovScan to reduce governoring costs and garner greater benefits from state and federal programs.
#### Nonprofit
* Use GovScan to reduce administrative costs and improve document organization. 
#### Consulting
* Use GovScan to retrieve data from in-house databases and improve market research for clients.  
#### Legal
* Use GovScan to improve document review and build a stronger case in court.
#### Military
* Use GovScan to draw strategic insight from open source adversary documents. 

## Sponsor's Guide to Adopting GovScan
1. You can find all GovScan files here: https://github.com/dcraig93/GovScan-Carnegie-Mellon-Policy-Innovation-Lab/tree/main
2. Review the "User Research" folder to explore user personas and other research documents that shaped GovScan's development.
3. Review the "App" folder to access the open source query engine and data pipeline code annotated with programming notes and directions.
4. Review the "LICENSE" file to ensure all future development efforts comply.

## Recommended Roadmap to Further Development
#### Product Refinement
* Convert the GovScan prototype into full fledge product and include new features to parse and summarize information in PDF reports.
#### User Testing
* Test prototype with policy analysts and other stakeholders to understand their thoughts about the product.
#### Scaling
* Expand the backend code to accommodate other program reports.

## Potential Challenges
* Exhaustive search capability
* Fabrications (“hallucinations”)
* Government adoption of Large Language Models
* Dependence on third party foundational models i.e. OpenAI, Meta, Anthropic
* Technological disruption

## Summary
Consider a federal policy analyst working for the U.S. Department of Health & Human Services, the Administration for Children and Families who is repsonsible for reviewing state Child Care Development Fund (CCDF) plans to ensure compliance with federal law. It will take the anyalyst weeks if not months to individually review all 50 state plans. Encumbered by the time-intensive task, the analyst is prone to error and potentially lacks the appropriate oversight necessary to enforce compliance. What if the analyst could search all 50 state plans simultaneously with the click of a button? GovScan is designed to perform this very function. With the power to search multiple documents at once and the ability to scan like a human, GovScan is positioned to reduce administrative costs and increase oranizational output for businesses, publicy entities, and academic institutions.
