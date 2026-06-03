# Managing Competitions

> Create, configure and publish competitions on Competition Engine.

## Creating a competition

{% stepper %}
{% step %}
### Go to Competitions

In the admin sidebar, click **Competitions**, then click **Create Competition** in the top right.
{% endstep %}

{% step %}
### Fill in the details

Enter the competition name, description, ticket price, total tickets, and draw date. You can also set a sale price, cash alternative value, and upload gallery images.
{% endstep %}

{% step %}
### Configure ticket settings

Set the maximum tickets per customer and optionally set a minimum tickets per order. You can also enable Pick Your Number mode, time locks, or time between orders restrictions.
{% endstep %}

{% step %}
### Add Instant Wins

Assign instant win categories to the competition. Each category defines a prize title, value, and how many tickets will trigger it. These are distributed randomly across the ticket pool when you publish.
{% endstep %}

{% step %}
### Set the status and publish

Set the status to **Active** (publicly visible) or **Private** (accessible only via direct link). Saving as **Draft** keeps it hidden until you're ready.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Instant win tickets are generated automatically when you publish a competition. You cannot add or edit instant wins after tickets have been sold.
{% endhint %}

---

## Competition statuses

| Status | What it means |
|--------|--------------|
| **Draft** | Hidden from customers. Editable, no tickets generated yet. |
| **Active** | Live and visible to all customers. |
| **Private** | Live but only accessible via direct link — not shown on the competitions listing page. |
| **Paused** | Temporarily hidden from customers. |
| **Ended** | Past the end date. No more entries accepted. |

---

## Ticket settings

| Setting | What it does |
|--------|--------------|
| **Total Tickets** | The total number of tickets available to purchase. |
| **Max Tickets Per Customer** | Limits how many tickets a single customer can buy in total. |
| **Max Tickets Per Order** | Limits how many tickets can be added in a single checkout. |
| **Min Tickets Per Order** | Requires a minimum quantity to be purchased at once. |
| **Pick Your Number** | Allows customers to choose specific ticket numbers rather than random assignment. |
| **Time Lock** | Blocks purchases during a set daily time window (e.g. 22:00–08:00). |
| **Time Between Orders** | Enforces a cooldown period between purchases from the same customer. |

---

## Templates & duplicating

You can save any competition as a **template** to reuse its settings, instant wins, and gallery for future competitions. Templates appear in a separate tab on the Competitions page.

To duplicate an existing competition, open it and click the **Duplicate** option from the menu. This opens the create form pre-filled with the existing competition's data — nothing is saved until you click publish.

---

## Preparing for the draw

Once a competition has ended or sold out, mark it as **Prepared for Draw** from the competition edit page. This sets the end and draw dates to now if they are still in the future, and makes it available in the Winner Reveal tool.

{% hint style="warning" %}
Once a competition has been prepared for draw and tickets have been sold, instant win settings can no longer be edited.
{% endhint %}

---

## Archiving competitions

Archiving hides a competition from all admin lists without deleting any data. Archived competitions can be restored at any time. This is different from deletion — archived competitions retain all their orders, tickets and winner records.