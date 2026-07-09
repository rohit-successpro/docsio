---
title: "Expense Management"
sidebar_position: 1
sidebar_custom_props:
  icon: receipt
description: "Capture expenses efficiently with AI-powered receipt processing and multi-level approval workflows."
---

Expense management in Successpro eliminates manual data entry. Upload a receipt and AI extracts the amount, category, and tax automatically. Your team submits expenses, managers approve them, and they flow directly into project costs and billing.

## Submit an expense

1. Go to **Expense Management** and click **My Expenses**.
2. Click **New Expense**.
3. Choose how to submit:
   - **Upload receipt**: Take a photo or upload a PDF of the receipt.
   - **Manual entry**: Type in the details if you don't have a receipt.

### Upload a receipt

1. Click **Upload Receipt** and select an image or PDF.
2. AI automatically extracts:
   - **Amount** (total cost)
   - **Currency**
   - **Category** (travel, meals, software, etc.)
   - **Tax** (if applicable)
   - **Vendor** (merchant name)
   - **Date**

3. Review the extracted data and correct anything if needed.
4. Select the **project** this expense belongs to.
5. Add any **notes** (e.g., "Client dinner for Acme Corp project").
6. Click **Submit for Approval**.

:::tip
Take clear photos of receipts with good lighting. AI extracts data more accurately from clear, legible receipts.
:::

### Manual entry

If you don't have a receipt or prefer to enter data manually:

1. Click **Manual Entry**.
2. Enter the **amount**, **currency**, **category**, **vendor**, and **date**.
3. Select the **project** this expense belongs to.
4. Add **notes** if needed.
5. Click **Submit for Approval**.

## Expense categories

Expenses are organized by category. Common categories include:

| Category | Examples |
|---|---|
| Travel | Flights, hotels, rental cars, parking |
| Meals | Client dinners, team lunches, meals while traveling |
| Software | SaaS subscriptions, tools, licenses |
| Hardware | Computers, monitors, equipment |
| Office | Supplies, furniture, rent |
| Professional Services | Consulting, contractors, freelancers |
| Other | Anything that doesn't fit above |

You can create custom categories for your business.

## Approval workflows

Expenses flow through approval workflows just like timesheets. You can configure who approves expenses and in what order.

### Set up approval workflows

1. Go to **Settings** and click **Approval Workflows**.
2. Click **New Workflow** and select **Expense**.
3. Define the **approval levels** and **sequential** or **parallel** approval.
4. Set **approval deadlines**.
5. Click **Save**.

### Approve an expense

1. Go to **Expense Management** and click **Approvals**.
2. View all expenses pending your approval.
3. Click an expense to review it.
4. Check that the amount, category, and project are correct.
5. Click **Approve** or **Reject**.

If you reject, the submitter gets feedback and can resubmit with corrections.

:::warning
Rejected expenses don't flow into billing. The submitter must correct and resubmit before the expense can be invoiced.
:::

## Compliance controls

Successpro includes built-in compliance controls to prevent fraud and ensure policy adherence:

- **Missing receipt controls**: Require receipts for expenses above a threshold (e.g., $25). For missing receipts, require an affidavit.
- **Category rules**: Enforce GL mapping so expenses are coded correctly for accounting.
- **Approval limits**: Require higher-level approval for expenses above a threshold.
- **Audit trails**: Every action is logged for compliance and dispute resolution.

## See also

- [Time Tracking](/docs/time-tracking/overview), Capture and approve time entries.
- [Invoicing](/docs/financial-management/invoicing), Generate invoices from approved expenses.
- [Services Analytics](/docs/analytics/dashboards), Monitor expenses and costs in dashboards.
