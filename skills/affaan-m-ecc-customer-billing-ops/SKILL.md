<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-customer-billing-ops
description: "Operate real customer billing workflows with Muse: identify the customer, classify the issue, apply..."
---

# Customer Billing Ops

Curated by Skill Harbor: use this skill for real customer operations, not generic payment API design. The goal is to help the operator answer four questions: who is this customer, what happened, what is the safest fix, and what follow-up should be sent. Workflow: identify the customer cleanly from the strongest identifier available (customer email, Stripe customer ID, subscription ID, invoice ID), returning a concise identity summary of active and canceled subscriptions, invoices, and obvious anomalies like duplicate active subscriptions; classify the issue before touching anything, distinguishing accidental duplicate purchases, deliberate multi-seat or team purchases, broken product or unmet value, failed or incomplete checkouts, and cancellations caused by missing self-serve controls; apply the safest fix, verifying the contract shape for annual plans, team plans and prorated states; then define the follow-up. Guardrails: prefer connected billing tools like Stripe first and hosted billing portals over custom account code; never expose secret keys, full card details or unnecessary customer PII in responses; do not refund blindly, classify first. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this needs connected billing tools to be useful; judgment stays human, the skill classifies and recommends but you approve the refund. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-customer-billing-ops
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-customer-billing-ops
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/customer-billing-ops/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
