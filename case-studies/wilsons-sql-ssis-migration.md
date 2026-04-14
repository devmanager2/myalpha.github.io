---
title: "SQL + SSIS Migration for Wilsons — CRM Event Load into Salesforce"
layout: single
---

# Challenge
Wilsons needed to migrate legacy CRM event data into Salesforce to support sell-side analysts publishing stock research, distributing Rapid Insights, and enabling communications for major capital raises such as Afterpay.

The legacy data model was inconsistent, incomplete, and required transformation before Salesforce could consume it.

# Approach
- Designed SQL transformations to normalise legacy CRM event data  
- Built SSIS packages to extract, cleanse, and load data into Salesforce  
- Implemented data quality rules to ensure analyst research events were accurate  
- Automated the load pipeline to support ongoing research distribution  
- Validated mappings with analysts, marketing, and compliance  

# Outcome
- Analysts could publish research faster with clean, reliable event data  
- Marketing gained accurate segmentation for Rapid Insights  
- Capital raise communications became consistent and compliant  
- Reduced manual intervention and operational risk  
