---
title: "Rate Cards & Contracts"
sidebar_position: 3
sidebar_custom_props:
  icon: handshake
description: "Set up rate cards and manage contracts to define how you price and bill your services."
---

Rate cards and contracts are the foundation of accurate billing and margin protection. Rate cards define your pricing. Contracts define the terms of each engagement.

## Rate cards

A rate card is a set of prices for your services. You can create company-wide rate cards that apply across all projects, or customer-specific rate cards that override the defaults for a particular client.

### Create a rate card

1. Go to **Financial Management** and click **Rate Cards**.
2. Click **New Rate Card**.
3. Enter a **name** for the rate card (e.g., "Standard Rates 2024" or "Acme Corp Rates").
4. Define rates by **role**, **skill**, **level**, **experience**, and **location**.

For example:
- Senior Developer in US: $200/hour
- Junior Developer in US: $120/hour
- Senior Developer in India: $80/hour

5. Set the **currency** (USD, EUR, GBP, etc.).
6. Click **Save**.

Once saved, the rate card is available when you create or update projects.

### Apply a rate card to a project

When you create a project, select which rate card to use. All time entries logged to that project will use the rates defined in that card.

If you need to override rates for a specific project, you can create a customer-specific rate card and apply it instead.

:::tip
Create rate cards for different regions, experience levels, and customer types. This gives you flexibility while maintaining pricing discipline.
:::

## Contracts

A contract defines the terms of an engagement: the billing model, rates, payment schedule, milestones, and any special terms.

### Create a contract

1. Go to **Financial Management** and click **Contracts**.
2. Click **New Contract**.
3. Enter the **contract name** (e.g., "Acme Corp - Website Redesign").
4. Select the **customer** from your customer list.
5. Choose the **billing model**: Time & Materials, Fixed Fee, Managed Service, Subscription, Usage-Based, or Hybrid.
6. Define the **contract terms**:
   - **Start date** and **end date**
   - **Total contract value** (for fixed-fee contracts)
   - **Recurring fee amount** (for managed service or subscription contracts)
   - **Payment schedule** (e.g., net 30, net 60)

7. Link the **rate card** that applies to this contract.
8. Upload or paste the contract document (MSA, SOW, PO, etc.).
9. Click **Save**.

### Contract-linked billing

Once a contract is created, link it to a project. All billing for that project will follow the contract terms automatically.

When you generate an invoice, Successpro applies:
- The correct billing model
- The correct rates from the linked rate card
- Any discounts or adjustments defined in the contract
- The correct payment schedule and terms

This ensures every invoice is accurate and compliant with the contract.

| Contract Element | Purpose |
|---|---|
| Billing model | Defines how you charge (hourly, fixed, recurring, usage-based) |
| Rate card | Defines the prices for different roles and skills |
| Payment schedule | Defines when invoices are due (net 30, net 60, etc.) |
| Milestones | Defines deliverables and their billing triggers |
| Special terms | Defines any custom terms (e.g., volume discounts, caps) |

### AI-assisted contract extraction

When you upload a contract document, Successpro uses AI to extract key terms automatically. It identifies:
- Billing model
- Contract value
- Payment terms
- Milestones and deliverables
- Rate information

You review the extracted data and confirm it's correct. This saves time and reduces errors compared to manual data entry.

:::warning
Always review AI-extracted contract terms carefully. If the extraction misses something or gets it wrong, edit the contract details manually to ensure accuracy.
:::

## Manage contracts over time

Contracts can be updated anytime. If you need to change the billing model, rates, or terms, edit the contract and the changes apply to future billing periods.

Historical invoices use the contract terms that were active when they were generated, so you maintain an accurate audit trail.

## See also

- [Billing Overview](/docs/financial-management/overview), Understand billing models and how they work.
- [Invoicing & Revenue Recognition](/docs/financial-management/invoicing), Generate invoices and recognize revenue.
- [Resource Management](/docs/resource-management/planning), Link resource costs to contracts for accurate margin tracking.
