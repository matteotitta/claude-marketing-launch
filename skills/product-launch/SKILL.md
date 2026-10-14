---
name: product-launch
description: Plans a B2B SaaS product or feature launch from one brief. Sets the launch tier, the ship date and the announce date, the channel plan, the asset list, a T-minus timeline and a launch report read twice after launch. Use for "product launch", "feature launch", "launch plan", "launch strategy", "go-to-market launch", "release coordination", "launch checklist" or "launch timeline". Works best with positioning, messaging and ICP files in the context folder.
version: '1.0.0'
license: MIT
---

# Product launch

Plan a launch that earns attention for longer than one day. Start from one brief, decide how big the launch is, then pick channels and assets that fit that size. The channel checklist is not the strategy. Launch day is the middle of the plan, not the end.

## When to use it

- A new product, feature, integration, pricing change or anything else where you are asking the market to pay attention.
- You need a dated plan the product, marketing and sales teams can all work from.

Don't use it for landing page copy alone, a single social post or a single email. Write those directly.

## Inputs

Read these first. Agency users swap `context/` for `clients/<client>/context/`.

- `context/positioning/`: category, alternatives, differentiators.
- `context/messaging/`: capabilities, benefits, proof points.
- `context/icp/`: who buys, their pains, where they spend time.
- The launch brief from the user (see step 1).

If a context file is missing, say which one, ask the user for the key facts, and carry on. Mark anything you had to assume as `[ASSUMPTION: ...]`.

## Steps

### 1. Get one brief

Ask for, or fill in from context, a single brief with:
- what is launching, in one sentence, and who it is for
- the problem it solves and why now
- the proof you have today (beta users, usage, quotes)
- the ship date and the announce date (see below)
- one owner for the whole launch: the person you ask when it drifts
- the budget and the people available

Produces: a one-page launch brief. Everything else hangs off it.

**Two dates, not one.** The ship date is when customers can use it. The announce date (T-0) is when you tell the market. They can be the same day; often they shouldn't be. Ship early, learn, then announce with real usage as proof. If you hold the announcement, name what you are waiting for. "The right moment" with no named moment is drift. Every T-minus number below counts back from the announce date.

### 2. Set the tier

| Tier | When it fits | What it gets |
|------|--------------|--------------|
| 1 | New product, new category, platform shift, pricing overhaul | Full plan: pre-launch build-up, a live moment, paid support, sales enablement, 30-day follow-through |
| 2 | Major feature, important integration, new segment | Owned channels, founder and team posts, email to the base, sales briefing, one recap |
| 3 | Improvement, smaller feature, fix customers asked for | Release note, in-app message, one social post, help doc |

Ask: would a prospect change their buying decision because of this? If yes, tier 1 or 2. If only current users care, tier 3. Don't inflate the tier to please a stakeholder; a tier 1 plan on a tier 3 change trains the audience to ignore you.

Produces: the tier, with one line on why.

### 3. Write the narrative

One headline claim, three supporting points, one proof each, pulled from `context/messaging/`. Frame it as a problem the buyer already has, not "we're excited to announce". If the launch needs a story arc across several weeks, run `/storytelling` on the brief.

Produces: headline, three points with proof, one line of before-and-after.

### 4. Plan channels

Pick channels from where the ICP actually spends time, not from a default list. For each channel note the job it does (build-up, launch moment, follow-through), the owner and the date. Founder and team accounts usually beat the company page; ask each person to post their own take rather than shared copy.

Produces: a channel table with job, owner, date.

### 5. List the assets

Scope the list to the tier. A tier 1 list usually holds:
- launch page or updated product page
- announcement email to customers, and one to prospects
- founder post plus angle briefs for team posts
- short demo video (polished or plainly raw, never halfway)
- sales one-pager and a short internal briefing with FAQ and objections
- release note and help doc
- one customer proof piece (run `/case-study`)
- a live session if the launch needs a moment (run `/webinar`)

Tier 2 drops paid, the live session and usually the video. Tier 3 keeps the release note, in-app message, help doc and one post.

Produces: asset list with owner and due date per asset.

### 6. Build the timeline

- **T-14:** brief signed off, tier set, owner named. Start recording a baseline: two weeks of daily signups, site visits, branded search and demo requests.
- **T-10 to T-3:** assets drafted and reviewed. Sales briefed. Customer quotes cleared.
- **T-2 to T-1:** everything scheduled, links checked, people who will post have their angle briefs.
- **T-0:** announce. Founder posts first, team follows over the next day or two. Reply to every comment.
- **T+1 to T+14:** follow-through. Recap posts with new angles (customer reactions, usage, behind the scenes), not repeats.
- **T+30:** second report read (step 7).

Produces: a dated timeline table with owner per row.

### 7. Plan the launch report, read twice

Agree the report before launch. It answers one question: should we run this again, and what would we change?

- **First read, 48 to 72 hours after:** while the campaign can still be fixed.
- **Second read, day 30:** views peak in two days, but signups, branded search and pipeline don't.

Each read covers: every account that posted, sorted by reach; lift against the T-14 baseline; what underperformed and what you would not repeat; three to five changes you can check next time. If nobody recorded a baseline, say so and give raw numbers. Never invent one.

## Output

Save to `outputs/product-marketing/<launch-slug>-launch-plan.md` with these sections: brief, tier, narrative, channel table, asset list, timeline, launch report template, open questions.

## What good looks like

- The tier is justified in one line and the plan matches it.
- Every asset and timeline row has an owner and a date.
- The narrative leads with the buyer's problem and every claim traces to a context file.
- The baseline starts at T-14 and the report has two dates in the calendar.

## Mistakes to avoid

- Starting from a channel checklist instead of the brief and tier.
- Treating launch day as the finish line, with nothing planned after T+1.
- Inventing metrics or quotes. Use `[PLACEHOLDER: ...]` for anything unconfirmed.
- One shared post copied by the whole team. It reads as a pod and gets ignored.
- A report where everything worked. It was written for a stakeholder, not the next launch.
