# Support Triage Studio

A single-file web app that simulates support-queue triage policies and staffing/automation tradeoffs.

## Inspiration

Trend: "I've been waiting over a month for Anthropic to respond to my billing issue"

Source: https://nickvecchioni.github.io/thoughts/2026/04/08/anthropic-support-doesnt-exist/

## What you can do

- Inspect a live ticket queue with synthetic churn and SLA-breach scoring
- Switch triage policies (balanced, VIP-first, angry customers, churn risk, SLA-first)
- Tune operational inputs (agents online, handle time, automation coverage/reliability, after-hours coverage)
- Run a 7-day simulation and compare outcomes (median response time, trust index, revenue at risk)
- Export/import scenarios and download a JSON report
- Generate a short draft post for sharing results

## How to run

Open `index.html` in any modern browser.

## Notes

- This app is a sandbox: the scoring and simulation are intentionally simplified but consistent.
- No external services are called.
