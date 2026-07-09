---
title: "Invoicing & Revenue Recognition"
sidebar_position: 2
sidebar_custom_props:
  icon: file-check
description: "Generate invoices from approved work and recognize revenue accurately with built-in compliance."
---

Invoicing in Successpro is fast because it's automated. Revenue recognition is accurate because it's connected to actual project delivery. Both happen without manual effort.

## Generate an invoice

1. Navigate to **Financial Management** and click **Invoices**.
2. Select the **project** you want to invoice.
3. Choose the **billing period** (e.g., this month, last quarter).
4. Click **Generate Invoice**.

Successpro pulls all approved hours, expenses, milestones, and recurring fees from the project. It applies the correct rates from your rate card, calculates any discounts or adjustments defined in the contract, and formats everything into a professional invoice.

5. Review the invoice details. Check that all line items are correct and amounts match your expectations.
6. Add any final adjustments (e.g., a one-time discount) if needed.
7. Click **Send** to deliver the invoice to your customer.

The entire process takes minutes. No manual data entry. No hunting through spreadsheets for approved hours.

:::note
Invoices can only be generated from approved time entries and expenses. If your team's timesheet is still pending approval, those hours won't appear on the invoice yet.
:::

## Billing from different sources

Successpro can generate invoices from multiple sources, all in one document:

| Source | Description |
|---|---|
| Approved time entries | Hours logged by team members, approved by managers |
| Approved expenses | Receipts submitted and approved through the expense workflow |
| Project milestones | Deliverables marked complete in the project plan |
| Recurring fees | Retainers or subscription amounts defined in the contract |
| Usage metrics | Consumption-based charges (API calls, storage, etc.) |

All of these can appear on a single invoice, with each line item showing the source, quantity, rate, and amount.

## Revenue recognition

Revenue recognition happens automatically as work is delivered. Successpro supports two methods:

### Effort-based recognition

Revenue is recognized based on the percentage of effort completed. As your team logs approved hours, the system calculates what percentage of the total project effort has been completed and recognizes that percentage of the contract value as revenue.

This method works well for Time & Materials and fixed-fee projects where effort is the primary driver of progress.

### Milestone percent completion

Revenue is recognized when project milestones are marked complete. You define milestones upfront (e.g., "Design complete", "Development complete", "Testing complete") and assign a percentage of the contract value to each. As milestones are completed, that percentage is recognized as revenue.

This method works well for fixed-fee projects with clear deliverables.

## Accruals and deferrals

Successpro automatically generates accrual and deferral entries based on your revenue recognition method. These entries are formatted for your accounting system and ready to post to your general ledger.

You don't have to manually calculate accruals or deferrals. The system does it for you, ensuring compliance with ASC 606 and IFRS 15.

:::warning
Revenue recognition is tied to approved work. If a timesheet or expense is rejected, any revenue recognized from that entry is reversed automatically.
:::

## Spot margin drift early

As projects progress, Successpro compares planned baselines against real-time revenue, effort, and cost. If actual hours are running higher than planned, or if actual costs are higher than expected, you see it immediately.

This early warning system lets you course-correct before margin drift becomes a problem. You can adjust resource allocation, renegotiate scope, or take other action while there's still time.

## See also

- [Billing Overview](/docs/financial-management/overview), Understand billing models and how they work.
- [Rate Cards & Contracts](/docs/financial-management/contracts), Set up and manage rate cards and contracts.
- [Services Analytics](/docs/analytics/dashboards), Monitor revenue and margins in real time.
