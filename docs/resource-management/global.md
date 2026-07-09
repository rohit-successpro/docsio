---
title: "Global Teams"
sidebar_position: 3
sidebar_custom_props:
  icon: globe
description: "Manage resources across regions, currencies, and local work schedules without complexity."
---

If your team spans multiple countries or regions, Successpro handles the complexity of managing global resources. You can coordinate teams across legal entities, currencies, and regional calendars without losing operational control.

## Set up regions and legal entities

Successpro lets you define regions and legal entities to organize your global team.

1. Go to **Settings** and click **Regions**.
2. Click **New Region** and enter the **region name** (e.g., "North America", "Europe", "India").
3. Set the **default currency** for the region (USD, EUR, INR, etc.).
4. Define **local holidays** for the region (e.g., Diwali in India, Christmas in US).
5. Set the **standard work week** (e.g., 40 hours in US, 45 hours in some countries).
6. Click **Save**.

Repeat for each region where you have team members.

### Legal entities

If you have separate legal entities in different countries (e.g., a US entity and an India entity), you can set them up separately.

1. Go to **Settings** and click **Legal Entities**.
2. Click **New Entity** and enter the **entity name** (e.g., "Acme Corp US", "Acme Corp India").
3. Select the **region** where the entity is located.
4. Set the **currency** and **tax ID**.
5. Click **Save**.

When you hire team members, you assign them to a legal entity. This ensures payroll, taxes, and costs are calculated correctly for each jurisdiction.

## Assign team members to regions

When you create a team member, assign them to a **region** and **legal entity**.

1. Go to **Resource Management** and click **Team Members**.
2. Click **New Team Member**.
3. Enter their **name** and **email**.
4. Select their **region** (this determines their local holidays and work schedule).
5. Select their **legal entity** (this determines their payroll and tax treatment).
6. Enter their **cost** in the local currency.
7. Click **Save**.

Now when you allocate this team member to a project, Successpro knows their local work schedule, holidays, and cost in their local currency.

## Work schedules and holidays

Each region has a standard work schedule (e.g., 40 hours/week, Monday-Friday). Successpro uses this to calculate available capacity.

When you create a timesheet or allocation, the system automatically accounts for:
- Local holidays (e.g., Diwali, Christmas, Eid)
- Regional work weeks (e.g., some countries work 45 hours/week)
- Time off (vacation, sick leave, etc.)

This means timesheets are pre-filled correctly for each region, and capacity calculations are accurate.

:::note
If a team member works a non-standard schedule (e.g., 4-day work week), you can override the regional default for that individual.
:::

## Multi-currency billing

When you have team members in different regions, you need to bill in different currencies. Successpro handles this automatically.

1. Create a **rate card** for each region or currency.
2. When you allocate a team member to a project, select the appropriate rate card.
3. When you generate an invoice, choose the **billing currency**.

Successpro converts costs and rates using current exchange rates and shows everything in the billing currency.

### Exchange rates

Exchange rates are updated daily from a market data provider. You can also manually override exchange rates if you want to use a specific rate for a project.

1. Go to **Financial Management** and click **Exchange Rates**.
2. View current rates or click **Set Custom Rate** to override for a specific date range.

## Manage costs across regions

Resource costs vary by region. A senior developer in the US costs more than a senior developer in India. Successpro lets you set region-specific costs.

When you allocate a resource to a project, the system uses the cost for their region. This ensures margins are calculated correctly regardless of where the team member is located.

### Example

- Senior Developer in US: $200/hour
- Senior Developer in India: $80/hour
- Project revenue: $150/hour (same for both)

When you allocate the US developer, margin is $150 - $200 = -$50/hour (loss).
When you allocate the India developer, margin is $150 - $80 = $70/hour (profit).

Successpro shows this margin difference immediately, so you can make informed allocation decisions.

:::warning
Be careful with cross-region allocations. If you allocate a high-cost resource to a low-margin project, margins can go negative quickly.
:::

## See also

- [Resource Planning](/docs/resource-management/planning), Allocate resources and track utilization.
- [Cost Management](/docs/resource-management/costs), Track costs and monitor margins.
- [Services Analytics](/docs/analytics/dashboards), Monitor global team performance in dashboards.
