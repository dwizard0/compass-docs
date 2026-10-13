# Reports

COMPASS includes a full suite of reports for monitoring your ship's health, tracking crew activity, and generating required SFI submissions.

Go to **Command Dashboard → Reports** to reach the Reports & Analytics page.

![Reports & Analytics — overview](../img/Command Dashboard - Reports.png)

---

## Available Reports

### Crew Activity Report

Shows event participation rates, attendance streaks, active crew tracking, and an **Inactive Crew Alert** highlighting members who haven't attended any events in the selected period.

![Crew Activity Report — most active crew and full crew activity table](../img/Command Dashboard - Reports - Crew Activity Report 1b.png)

Use this report monthly to identify members who may be slipping into inactivity before they actually leave.

---

### Event Statistics Report

Breaks down your events by type, attendance trends, and most-attended events over a selectable time period.

![Event Statistics Report](../img/Command Dashboard - Reports - Event Statistics Report 1a.png)

---

### Promotion Points Report

Shows a detailed points breakdown for all crew members — event points, academy points, permanent points, and total — to help determine promotion eligibility at a glance.

![Promotion Points Report](../img/Command Dashboard - Reports - Promotion Points Report.png)

---

### Points Accumulation Report

Tracks recognition and promotion point trends across your crew over time.

![Points Accumulation Report](../img/Command Dashboard - Reports - Points Accumulation Report 1a.png)

---

### Academy Completion Report

Shows OTS, OCC, and academy course completions by crew member. Useful for identifying who needs training to qualify for command roles.

![Academy Completion Report](../img/Command Dashboard - Reports - Academy Completion Report 1a.png)

---

### Membership Expiration Report

Tracks crew members with memberships expiring in the next 60, 45, 30, 21, 14, or 7 days, and those already expired. Run this monthly before submitting reports to avoid losing crew to lapsed memberships.

![Membership Expiration Report](../img/Command Dashboard - Reports - Membership Expiration Report 1a.png)

---

### Community Service Hours Report

Tracks volunteer hours from community service event types across your crew.

![Community Service Hours Report](../img/Command Dashboard - Reports - Community Service Hours Report 1a.png)

---

### Uniform Compliance Report

Tracks uniform wearing rates and bonus points earned for crew who wear their uniform to events.

![Uniform Compliance Report](../img/Command Dashboard - Reports - Uniform Compliance Report.png)

---

### Crew Platform Engagement

Shows which crew members are actively logging into COMPASS and identifies dormant accounts — useful for following up with members who may not know the platform exists.

![Crew Platform Engagement Report](../img/Command Dashboard - Reports - Crew Platform Engagement.png)

---

### Monthly Status Report (MSR)

Generates the MSR for SFI submission, listing current and previous month activity with participant counts.

![Monthly Status Report](../img/Command Dashboard - Reports - Monthly Status Report (MSR).png)

!!! tip
    Run the MSR report at the end of each month, review for accuracy, and submit to your RC. The RC manual requires monthly submission — COMPASS does the counting for you, but you still need to formally submit.

---

### Individual Crew Report

A complete profile report for a specific crew member. Access this from the crew roster by clicking a member's name rather than from the main Reports page.

---

## Exporting Data

The bottom of the Reports page has three export buttons:

| Export | Contents |
|---|---|
| **Export Crew Roster** | Full crew list with ranks, statuses, and SCCs |
| **Export Events** | All events with dates, types, and attendance counts |
| **Export Participation Data** | Per-member event attendance and points data |

Exports are CSV format, suitable for Excel or Google Sheets.

---

## Exporting One Member's Activity

To export a single crew member's activity for a date range — for a promotion packet, an award nomination, or a member who asks for their history:

1. Open the member's crew record (click their name on the roster).
2. Click **Export Activity** at the top right.

    ![Export Activity Report](../img/Ship - Export Activity.png)

3. Choose a **Start Date** and **End Date**. The window opens set to the last 30 days.
4. Click **Export CSV**.

The file starts with the member's name, SCC and the period, then one row per item with its date, type, description, details, points and uniform:

- **Event** participation, with the event type and whether they wore uniform
- **Awards** received, with their point value
- **Promotions**, shown as negative points (the points the promotion used)
- **Permanent points** awarded, with their category

Academy courses aren't included, because COMPASS records academy totals rather than a date for each course.

**Export Activity** is available to the CO, XO, OPS and SO.

!!! tip "Adjusting points"
    To give a member (or your whole roster) a starting balance of event points, or to correct a recording error, use event point adjustments. See [Opening Event Points](event-point-adjustments.md).
