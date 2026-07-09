---
title: "Cost Management"
sidebar_position: 2
sidebar_custom_props:
  icon: currency-dollar
description: "Track resource costs, manage contractor spend, and monitor project margins in real time."
---

Cost management in Successpro connects resource costs to project profitability. Every dollar spent on resources flows into project margins automatically, so you see margin as it forms, not after it slips.

## Employee costs

Employee costs are the foundation of margin calculation. You define how much each employee costs, and Successpro rolls that cost into every project they're allocated to.

### Set up employee costs

1. Go to **Resource Management** and click **Team Members**.
2. Select a team member and click **Edit**.
3. Enter their **cost** in the **Compensation** section.
4. Choose the **cost type**: Hourly, Daily, Weekly, Monthly, or Annual.
5. Set the **currency**.
6. Click **Save**.

For example:
- Senior Developer: $150/hour
- Project Manager: $120/hour
- Designer: $100/hour

Or:
- Senior Developer: $300,000/year
- Project Manager: $250,000/year

### Cost calculation

When a team member is allocated to a project, Successpro calculates their cost based on:
- Their hourly or annual cost
- Their allocation percentage or hours per week
- The duration of the allocation

This cost is subtracted from project revenue to calculate gross margin. As allocations change, costs update automatically.

:::note
If you use annual salaries, Successpro divides the annual cost by the number of billable hours per year (typically 1,800-2,000 hours) to calculate an effective hourly cost.
:::

## Contractor and supplier costs

You can also track costs for contractors and external suppliers. This is useful if you outsource work or use specialized vendors.

1. Go to **Resource Management** and click **Contractors**.
2. Click **New Contractor**.
3. Enter the contractor's **name** and **company**.
4. Set their **cost** (hourly, daily, or project-based).
5. Link them to **approved contracts** to prevent assignments outside contract terms.
6. Click **Save**.

When you allocate a contractor to a project, their cost is included in project margin calculations just like employees.

## AI and other variable costs

Some costs are variable and tied to usage rather than headcount. For example, if you use AI services, you might pay per API call or per token.

1. Go to **Resource Management** and click **Cost Categories**.
2. Click **New Category** and select **Variable Cost**.
3. Enter the **cost name** (e.g., "OpenAI API").
4. Set the **unit cost** (e.g., $0.01 per 1,000 tokens).
5. Link it to **projects** where this cost applies.

As your team uses the service, costs are tracked and rolled into project margins.

## Project margin tracking

Project margins update in real time as costs change. You can see:

- **Gross margin**: Revenue minus direct resource costs
- **Operating margin**: Gross margin minus overhead and indirect costs
- **Margin %**: Margin as a percentage of revenue

1. Go to **Financial Management** and click **Projects**.
2. Select a project to see its **margin dashboard**.
3. View margin by **time period**, **resource**, or **cost category**.

If margin is trending down, you can drill in to see why: Are hours running higher than planned? Are costs higher than expected? Is the rate lower than planned?

:::warning
Margin drift happens gradually. By the time you notice it at month-end, it's too late to course-correct. Monitor project margins weekly to catch issues early.
:::

## Overhead and indirect costs

In addition to direct resource costs, you have overhead: office space, software licenses, management, etc. You can allocate overhead to projects to calculate true operating margin.

1. Go to **Resource Management** and click **Overhead**.
2. Enter your **total overhead** for the period.
3. Choose how to **allocate** it: by revenue, by headcount, or by billable hours.
4. Click **Apply**.

Overhead is now included in project margin calculations.

## See also

- [Resource Planning](/docs/resource-management/planning), Allocate resources and track utilization.
- [Global Teams](/docs/resource-management/global), Manage costs across regions and currencies.
- [Services Analytics](/docs/analytics/dashboards), Monitor margins and profitability in dashboards.
