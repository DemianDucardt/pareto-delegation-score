---
title: Pipeline Workflows Blueprint
type: automation
date: 2026-10-06
sources: ["../01_SecondBrain/MOC.md"]
status: active
related: ["MOC.md", "optin_blueprint.json", "nurture_qualified_3.md"]
---

Title: Pipeline plus workflows blueprint. Owner Demian Ducardt. Date 2026-10-06.

Pipeline stages, 5:
Opt in. Qualified. Call via email. Client. Other.
Log file: pipeline_log.csv with columns email, revenue_band, route, date. No GHL access per owner, so log is manual plus form JS route.

Opt in workflow:
Trigger: form submit on 06_Funnel index.html.
Steps: tag by revenue band. Create opportunity row. Send resource email at once. Notify demian.ducardt@gmail.com.
Blueprint: 07_Workflows/optin_blueprint.json.

Qualified nurture: 3 emails. Day 0 delivery plus SOP. Day 2 agent map. Day 4 handoff list plus email CTA.
Other nurture: 1 email. Delivery only.

Booking: email CTA only per owner. Confirmation copy in booking_confirmation.md. No calendar embed.

All workflows OFF by default in live use. Test via form JS plus inbox.

Built by Demian Ducardt.
