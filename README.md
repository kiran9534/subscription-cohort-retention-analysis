# Subscription Cohort & Retention Analysis

## Overview

This Excel project analyzes subscription activity over time. The main focus is understanding when customers sign up, when they cancel, how long subscriptions remain active, and how retention changes across signup cohorts.

## Business questions

- How many subscriptions were created?
- How many subscriptions were cancelled?
- How long do customers remain active?
- Do customers who pay behave differently from unpaid subscriptions?
- How does retention change across signup cohorts?
- Which cohorts show stronger or weaker retention?

## Dataset

The main dataset contains 3,069 subscription records with:
- customer ID
- created date
- canceled date
- subscription cost
- subscription interval
- paid/unpaid status

Additional calculated fields in the workbook include active months, a five-month retention flag, and a retained-month indicator.

## Tools

- Microsoft Excel
- Pivot Tables
- Cohort analysis
- Date-based calculations

## Key findings

- 2,004 of 3,069 subscriptions have a cancellation date, or about 65%.
- Average active duration in the workbook's calculated `Active_months` field is about 2.6 months.
- The median active duration is 2 months.
- The workbook includes cohort-level views for comparing retention across signup groups.

## Files

- `data/Subscription_Cohort_Analysis_Data.xlsx` — source and analysis workbook
- `images/subscription-cohort-dashboard.png` — project screenshot

## Portfolio takeaway

This project shows how I use Excel to analyze customer lifecycle behavior and turn subscription-level records into cohort and retention views that can help identify early churn patterns.
