# Promotion Point System

This page documents the **default** point values COMPASS ships with. Every value here is a starting point — a chapter can override most of them, and some chapters turn point tracking off entirely.

!!! note "Your chapter's numbers may differ"
    COMPASS is supplemental and voluntary. Promotion policy belongs to your Commanding Officer, not to COMPASS. If your chapter has published its own promotion point policy, that policy wins. This page tells you what COMPASS does when nobody has changed anything.

---

## The Two Point Pools

COMPASS tracks promotion points in two pools that behave differently.

| Pool | Made up of | Behaviour |
|---|---|---|
| **Event + Academy** | Event participation, event point adjustments, academy completions | **Spent** on promotions. Approving a promotion deducts its point cost from this pool. |
| **Awards + Permanent** | Award point values, permanent point awards | **Standing balance.** Counts toward every eligibility check and is never consumed. |

Eligibility compares `(Event + Academy − already spent) + (Awards + Permanent)` against the target rank's point cost.

!!! tip "Why the pools differ"
    Many chapters describe regular points as "resetting at each new rank." COMPASS implements the same idea by *spending* points rather than zeroing them, which keeps the full earning history intact for reports and audits. The available balance behaves the same way either way.

Event points are summed **across a member's whole career**, not per ship. A member who transfers carries both their earned points and their spent points to the new chapter, so the two sides stay coherent.

---

## Event Points

Each event type has a **base value** and a **uniform multiplier** applied when the member is recorded as having worn uniform.

| Event Type | Base | Uniform Multiplier | In Uniform | Counts for Attendance |
|---|---|---|---|---|
| Meeting or Event | 2 | ×2 | 4 | Yes |
| Games with Crewmates | 2 | ×2 | 4 | Yes |
| Fleet Challenges | 2 | ×1 | 2 | No |
| Plan or Host an Event | 3 | ×1 | 3 | No |
| Away Mission (individual or small group) | 1 | ×2 | 2 | No |
| Write an Article | 2 | ×1 | 2 | No |
| Attend a Convention | 3 | ×2 | 6 | Yes |
| Participating in a Charity Event | 2 | ×2 | 4 | Yes |
| Renewing Membership on Time | 5 | ×1 | 5 | No |
| Recruiting a Member | 5 | ×1 | 5 | No |
| Running the Chapter Table at a Convention | 5 | ×1 | 5 | Yes |
| Running a Convention Panel | 5 | ×1 | 5 | No |
| Participating in Community Service | 2 | ×2 | 4 | Yes |

**The uniform bonus is a multiplier, not an addition.** A multiplier of ×2 doubles the event's value when the member is recorded in uniform. A multiplier of ×1 means uniform wear makes no difference — that is how COMPASS marks the event types where being in uniform isn't applicable, such as renewing a membership or writing an article.

Each event type also has a **uniform bonus enabled** switch. Turning it off suppresses the multiplier entirely, so the event is worth its base value whether or not uniform was worn.

**Counts for Attendance** controls whether the event feeds the crew activity report. It has no effect on points.

Members can also receive **host credit** separately from attendance credit for the same event, so a member who plans, hosts, and attends is credited for both.

Chapters that joined COMPASS partway through their history can set an opening balance with **Event Point Adjustments** instead of back-entering years of events. Adjustments are folded into the member's event point total rather than shown separately.

---

## Academy Points

| Completion Grade | Default |
|---|---|
| Distinction | 2 |
| Honors | 1 |
| Pass | 1 |
| Beta Tester | 2 |
| Course Created | 2 |

Beta Tester and Course Created always match whatever Distinction is set to, including after an override.

---

## Award Points

Award point values are set per award, not per category. The defaults break down roughly as follows.

| Award Group | Typical Default |
|---|---|
| SFI Individual Awards | 1 to 5, most commonly 1 or 3 |
| SFA (Academy) Awards | 1 |
| Annual Awards | 2 to 3 |
| SFMC | 1, with achievement-tier awards at 2, 3, or 5 |
| SF Medical, Sciences, Special Operations, Tactical, Petfleet | 1 |

Repeatable awards are worth their point value **each time earned**.

When COMPASS looks up an award's value for a ship, it resolves in this order and stops at the first match:

1. A ship-level override for that specific award
2. A legacy ship-level override for that award
3. A ship-level override for the award's whole category
4. The award's own point value
5. The system-wide default for the award's category

This is why a CO can say "all Medical awards are worth 1 point on my ship" with a single category override, without touching 53 individual awards.

---

## Permanent Points

Permanent points never reset and are never spent. Each category has a cap on the total a member can hold from that category.

| Category | Cap |
|---|---|
| Academic Development Program | 100 |
| Auxiliary Special Award | 60 |
| Leadership Positions | 75 |
| Bridge Officer Certification | 20 |
| Officer Training | No cap |
| Other | No cap |

### Academic Development Program

| Award | Points |
|---|---|
| Associate Degree | 10 |
| Bachelor Degree | 15 |
| Masters Degree | 25 |
| Doctorate Degree | 40 |
| Additional Doctorate | 30 |

### Auxiliary Special Award

| Award | Points |
|---|---|
| Auxiliary Special Award | 30 |

Covers recognitions such as the Black Ops Specialty Pin, the Specialist Medical Training Program, and SFMC achievement awards at silver or higher.

### Leadership Positions

| Award | Points |
|---|---|
| Leadership Position (Chapter) | 50 |
| Leadership Position (Region) | 75 |
| Leadership Position (Fleet) | 75 |

The 75-point category cap means a member holding both a chapter and a regional position is credited 75, not 125.

### Bridge Officer Certification

| Award | Points |
|---|---|
| Bridge Officer Certification | 20 |

### Officer Training

| Award | Points |
|---|---|
| Officer Training School (OTS) | 5 |
| Officer Training School — Distinction | 10 |
| Officer Command Course (OCC) | 15 |
| Officer Command Course — Distinction | 30 |

---

## Rank Costs and Time in Grade

Point cost is what the promotion consumes; time in grade (TIG) is the minimum months a member must hold their current rank before becoming eligible.

### Navy Enlisted

| Grade | Rank | Points | TIG |
|---|---|---|---|
| E-1 | CRR / CRMN 3C | — | — |
| E-2 | CRA / CRMN 2C | 20 | 1 |
| E-3 | CRMN / CRMN 1C | 30 | 2 |
| E-4 | PO3 | 50 | 3 |
| E-5 | PO2 | 80 | 3 |
| E-6 | PO1 | 150 | 3 |
| E-7 | CPO | 200 | 4 |
| E-8 | SCPO | 250 | 5 |
| E-9 | MCPO | 300 | 6 |

E-1 through E-3 run as two parallel tracks. A member on the reserve track (CRR → CRA → CRMN) is never offered the regular track (CRMN 3C → CRMN 2C → CRMN 1C), or the reverse. The tracks converge at E-4.

### Navy Officer

| Grade | Rank | Points | TIG |
|---|---|---|---|
| O-1 | ENS | 50 | 2 |
| O-2 | LTJG | 100 | 3 |
| O-3 | LT | 150 | 6 |
| O-4 | LCDR | 250 | 7 |
| O-5 | CMDR | 300 | 8 |
| O-6 | CAPT | 0 | 18 |
| O-7 | FCAPT | 0 | 21 |
| O-8 | COMM | 0 | 24 |
| O-9 | RADM | 0 | 24 |
| O-10 | VADM | 0 | 30 |
| O-11 | ADM | 0 | 36 |

O-6 and above carry no point cost — they are earned through service and approval, not accumulation. TIG still applies.

### Marine Enlisted

| Grade | Rank | Points | TIG |
|---|---|---|---|
| E-1 | PVT | — | — |
| E-2 | PFC | 20 | 1 |
| E-3 | LCP | 30 | 2 |
| E-4 | CPL | 50 | 3 |
| E-5 | SGT | 80 | 3 |
| E-6 | SSGT | 150 | 3 |
| E-7 | GSMT | 200 | 4 |
| E-8 | MSGT / 1SGT | 250 | 5 |
| E-9 | MGSGT / SGM | 300 | 6 |

### Marine Officer

| Grade | Rank | Points | TIG |
|---|---|---|---|
| O-1 | 2LT | 50 | 2 |
| O-2 | 1LT | 100 | 3 |
| O-3 | MCPT | 150 | 6 |
| O-4 | MAJ | 250 | 7 |
| O-5 | LTC | 300 | 8 |
| O-6 | COL | 0 | 18 |
| O-7 | BDR | 0 | 21 |
| O-8 | BGN | 0 | 24 |
| O-9 | MGN | 0 | 24 |
| O-10 | LGN | 0 | 30 |
| O-11 | GEN | 0 | 36 |

### Warrant Officer

| Grade | Rank | Points | TIG |
|---|---|---|---|
| W-1 | WO1 | 100 | 0 |
| W-2 | CWO2 | 150 | 3 |
| W-3 | CWO3 | 200 | 6 |
| W-4 | CWO4 | 250 | 7 |
| W-5 | CWO5 | 300 | 8 |

Appointment to WO1 cannot be self-requested.

### Cadet

| Grade | Rank | Points | TIG |
|---|---|---|---|
| C-1 | CDT | — | — |
| C-2 | CDT4 | 10 | 6 |
| C-3 | CDT 3C | 15 | 8 |
| C-4 | CDT 2C | 25 | 10 |
| C-5 | CDT 1C | 50 | 12 |
| C-6 | CDT CRMN | 75 | 18 |

The Cadet starting rank is only offered to members under 18.

### Marine Cadet

| Grade | Rank | Points | TIG |
|---|---|---|---|
| MC-1 | CDT PVT | — | — |
| MC-2 | CDT PFC | 10 | 2 |
| MC-3 | CDT LCP | 15 | 3 |
| MC-4 | CDT CPL | 20 | 3 |
| MC-5 | CDT SGT | 25 | 4 |
| MC-6 | CDT SSGT | 30 | 4 |
| MC-7 | CDT GSMT | 40 | 6 |
| MC-8 | CDT 1SGT | 50 | 6 |
| MC-9 | CDT MSGT | 60 | 8 |
| MC-10 | CDT SGM | 70 | 10 |
| MC-11 | CDT MGSGT | 85 | 12 |
| MC-12 | CDT 2LT | 100 | 12 |
| MC-13 | CDT 1LT | 125 | 18 |

---

## Officer Prerequisites

Points and time in grade are not the only gate on officer ranks.

| Target | Requirement |
|---|---|
| O-1 through O-4 | Officer Training School (OTS or OTS Distinction) |
| O-5 and above | OTS **and** Officer Command Course (OCC or OCC Distinction) |

A member at E-1 through E-5 who holds OTS also sees O-1 (ENS or 2LT) as a commissioning option alongside their normal next enlisted rank.

Enlisted and Warrant Officer promotions have no course prerequisites.

---

## Time in Grade Waivers

A CO — or an officer they have delegated promotion authority to — can apply a **TIG waiver** at promotion time, which halves the time-in-grade requirement for that promotion. For Captain/Colonel and above, a waiver instead takes **6 months** off the requirement. Waivers are intended for exceptional performance and are recorded on the promotion.

---

## Turning Points Off

Some chapters do not use a point system at all. Ship Settings has toggles for this.

| Toggle | Effect |
|---|---|
| Promotion points disabled | Master switch. All point totals report as zero and every rank costs 0. |
| Event points disabled | Event participation and adjustments stop counting. |
| Academy points disabled | Academy completions stop counting. |
| Award points disabled | Award values stop counting. |
| Permanent points disabled | Permanent point awards stop counting. |
| TIG disabled | All time-in-grade requirements become 0 months. |

With points disabled, promotions become a pure Captain's Prerogative workflow — COMPASS still records the promotion, the rank change, and the notification.

---

## Where to Change These Values

Everything on this page is configured under **Ship Settings**:

- **Event Points** — base value, uniform multiplier, and uniform bonus toggle per event type
- **Academy Points** — Distinction, Honors, and Pass values
- **Award Points** — per-award and per-category overrides
- **Permanent Award Points** — permanent point values
- **Promotion Requirements** — point cost and TIG per rank
- **Event Point Adjustments** — opening balances and bulk corrections

See [Ship Settings](../co-guide/ship-settings.md) for the walkthrough.

!!! warning
    Changing promotion requirements takes effect immediately and recalculates eligibility for your whole crew. Check the Promotion Eligibility Report afterwards to see what moved.
