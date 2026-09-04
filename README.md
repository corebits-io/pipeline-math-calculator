# Pipeline Math Calculator for PE Firms

Most private equity firms set a deal target for the year.

Few work backwards to the amount of origination required to get there.

This is the spreadsheet that does it. Enter what you want to close and what your
team generates today, and it tells you how many qualified owner conversations you
actually need — and how far behind you are.

**[⬇ Download the calculator](./Pipeline-Math-Calculator-for-PE-Firms.xlsx)**

Excel, Google Sheets, or LibreOffice. No macros, no signups, nothing to install.

---

## What you enter

Five cells. They are the only editable ones in the workbook.

- Platforms you want to close in the next 12 months
- Add-ons you want to close in the next 12 months
- Qualified owner conversations your team generates today, per month
- Your qualified conversation → LOI rate
- Your LOI → close rate

## What it tells you

- Qualified owner conversations needed **per deal**
- Conversations needed **annually** and **monthly**
- LOIs needed at each stage
- Your current annual run-rate
- **How many conversations short of your target you are**
- How many of your targeted deals you actually close at the current run-rate

---

## The worked example it ships with

You want to close 3 platforms and 6 add-ons in the next twelve months. Nine
deals. Your qualified conversation → LOI rate is 20 percent, and your LOI → close
rate is 20 percent — so 4 percent of qualified owner conversations become closed
deals.

```
Qualified conversations needed per deal      1 / 0.04    =  25
Qualified conversations needed, annual       9 x 25      = 225
Qualified conversations needed, monthly      225 / 12    =  19

Your team generates today                                     7 / month
Annual run-rate                              7 x 12      =  84

CONVERSATIONS SHORT, ANNUAL                  225 - 84    = 141
You are 63% behind the volume your deal target requires
At the current run-rate you close 3 of the 9 deals you are targeting
```

The point is the last three lines.

The sourcing problem is no longer *"we need more deal flow."*

It is *"we are 225 qualified owner conversations short of our annual target."*

One of those can be managed. The other cannot.

---

## What is in the workbook

**Pipeline Calculator** — the model. Five inputs, everything else live formulas.

**Sensitivity** — conversations needed annually across a grid of conversion
rates, because your two percentages are estimates and the requirement swings
hard on them.

```
CONVERSATIONS NEEDED ANNUALLY, at a 9-deal target

                             LOI → close
  Qual → LOI      15%      20%      25%      30%      35%
       10%        603      450      360      306      261
       15%        405      306      243      207      180
       20%        306      225      180      153      135
       25%        243      180      144      126      108
       30%        207      153      126      108       90
```

Read it the other way round and it makes the real point: **improving conversion
is almost always cheaper than tripling origination volume.** Moving qualified
conversation → LOI from 20 to 25 percent takes 45 conversations a year off the
requirement. That improvement comes from a better-qualified target list and
better pre-call research — not from more outreach.

**Read me** — what counts as a qualified owner conversation, why the defaults are
what they are, and what this model deliberately does not tell you.

---

## Two things to be careful about

**1. What counts as a qualified owner conversation.**

A real, two-way conversation with somebody who can actually sell the business —
the owner or the controlling shareholder. Not a general manager. Not a
gatekeeper. An email you sent is not a conversation, and neither is a
five-minute call that ended at "send me something".

If you count loosely here, every number in the model flatters you.

**2. The default conversion rates are assumptions, not your numbers.**

20 percent and 20 percent are sector-typical for lower-middle-market
origination. Replace them with your own as soon as you have twenty or more
qualified conversations to measure from.

Below twenty, a rate calculated from your own history is noise. A 50 percent
close rate from two conversations has misled more than one investment committee.

---

## Using it in Google Sheets

**File → Import → Upload**, choose the `.xlsx`, and select *Replace spreadsheet*.
All the formulas carry over. The cell shading marking the five inputs carries
over too.

---

## Important

This is not investment, legal, or tax advice. It is arithmetic, and it is only as
good as the two conversion rates you put into it.

---

## License

[MIT](./LICENSE) — do whatever you want with it.

Built by [Corebits](https://corebits.io).
