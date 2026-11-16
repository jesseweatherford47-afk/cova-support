# Cova — Ticket Priority Guide

How to categorize and format triage output for incoming Cova support tickets.

## Priority Definitions
<!-- Why: Not all issues are equal. Enterprise customers 
have a 1-hour SLA. Claude must know the difference. -->
- **Critical**: System down, data loss, login failure, 
  security/compliance issue, or complete business process 
  blocked for Enterprise customer
- **High**: Major feature broken with no workaround, significant 
  customer impact, time-sensitive business consequence or deadline
- **Medium**: Feature degraded, workaround available, 
  moderate customer impact
- **Low**: How-to question, feature request, 
  cosmetic issue, general inquiry

SLA targets come from the Plan Tiers + SLAs section in `CLAUDE.md`.

## Pattern Recognition
<!-- Why: Multiple similar tickets in one batch may 
mean a platform-wide incident, not individual problems. -->
- Two or more Critical/High tickets with the same symptom 
  → flag as possible incident, escalate to engineering
- Same customer appearing twice → consolidate into one ticket

## Summary reports
- Every time I ask you for a summary, write those files in the @reports folder as a .md

## Output Format

Make a .md in the @reports folder which will hold a report .md file for all the tickets you analyze

**Priority**: [Critical / High / Medium / Low]
**Issue type**: [Bug / Account / Billing / How-to / Feature request / Compliance]
**Plan tier**: [from ticket]
**SLA target**: [based on tier and priority]
**What's happening**: [1 sentence, plain English]
**Customer impact**: [what this is costing them right now]
**Immediate action**: [specific next step, assigned to a role]
**Draft first response**: [2-3 sentences to send to the customer]
