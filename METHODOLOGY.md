# Forecasting Methodology

## Overview

This document describes how the PrehabGuys revenue forecasting model is constructed, what inputs it uses, and how to interpret the outputs.

## Forecast Tiers

| Tier | Description |
|------|-------------|
| **Floor** | Conservative case. Assumes no improvement in current conversion rates and baseline marketing spend. |
| **Target** | Base case. Reflects expected performance given current pipeline and planned campaigns. |
| **Stretch** | Optimistic case. Assumes successful execution of all growth initiatives. |

## Key Inputs

### Trial Conversions
- Source: Arash and George
- Metric: Trial-to-paid conversion rate by cohort
- Update frequency: Monthly

### Marketing IC Data
- Source: Marketing team
- Includes: Campaign projections, channel mix, expected impressions and CPAs

### Campaign Revenue Projections
- Built from IC data and historical campaign performance
- Segmented by channel and audience

## Model Logic

1. Start with current subscriber base and known churn rates
2. Layer in projected new trials from marketing campaigns
3. Apply conversion rates (Floor / Target / Stretch scenarios)
4. Add direct and partnership revenue channels
5. Produce monthly and quarterly totals per tier

## Update Cadence

- **Weekly:** Marketing IC data refreshed
- **Monthly:** Conversion rates updated from Arash / George
- **Quarterly:** Full model review and re-baseline

## Change Log

| Date | Version | Summary |
|------|---------|---------|
| 2026-04-02 | v2.0 | Updated IC data from marketing, campaign revenue projections, updated trial conversion rates from Arash and George |
