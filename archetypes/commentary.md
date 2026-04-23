---
title: "{{ replace (replaceRE `^[0-9]{4}-[0-9]{2}-` "" .Name) "-" " " | title }}"
date: {{ .Date }}
draft: true
month_covered: "{{ dateFormat "January 2006" .Date }}"
tags:
  - commentary
  - monthly
summary: "Commentary for {{ dateFormat "January 2006" .Date }}."
---

## Market environment

{{/* Token: {{MARKET_ENVIRONMENT}} — replaced by Session-6 report generator.
     One to three sentences on regime. VIX level/structure in qualitative terms,
     rates backdrop, any macro event dominating the period. No dollar figures. */}}

_Placeholder for market-environment narrative._

## Strategy activity

{{/* Token: {{LAYER_SUMMARY}} — percentage contributions only.
     Absolute dollar amounts, contract counts, strike specifics, and notional
     values are excluded by policy. */}}

- **Layer 1 (capital base).** _Placeholder._
- **Layer 2 (systematic VRP).** _Placeholder._
- **Layer 3 (episodic/tactical).** _Placeholder._

Month-over-month return: **_XX.XX%_**.  
Year-to-date return: **_XX.XX%_**.

## Key observations

{{/* Token: {{OBSERVATIONS}} — bullet points or short prose.
     Anything notable from the trade log: a roll that worked, a thesis that
     did not, indicator signals that were respected or overridden. */}}

_Placeholder for observations._

## Forward stance

{{/* Token: {{FORWARD_STANCE}} — qualitative posture heading into next month.
     Risk-on / risk-off / neutral, specific catalysts flagged, layer weighting
     adjustments if any. */}}

_Placeholder for forward stance._

---

_The full performance record (NAV, TWR per GIPS sub-period methodology, trade log) is available on request. See [Contact](/contact/)._
