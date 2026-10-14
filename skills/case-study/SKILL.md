---
name: case-study
description: Turns a customer interview or win into a B2B case study with a before-and-after story, sourced metrics and verbatim quotes, ready for a web page or PDF. Never invents numbers. Use for "case study", "customer story", "success story", "write up this win", "customer proof point" or "case study from this interview".
version: '1.0.0'
license: MIT
---

# Case study

Turn what a customer said and measured into a story a buyer believes. The case study is only as strong as its evidence: every number has a source and every quote is the customer's own words.

## When to use it

- You have a customer win and want a page, a PDF or a sales asset from it.
- You have an interview transcript or call notes and need the story pulled out.
- A launch needs customer proof (this is the proof step for `/product-launch`).

Don't use it for a single testimonial quote (pull the quote directly) or a full multi-week campaign (use `/storytelling`).

## Inputs

Agency users swap `context/` for `clients/<client>/context/`.

- An interview transcript, call notes, or the customer's answers in writing. The best input by far.
- Results data the customer shared: before and after numbers, with where each came from.
- `context/icp/`: so the story speaks to the buyer who reads it.
- `context/messaging/`: so the solution section uses your own product language.
- `context/win-loss/` if you have it: why they chose you.

Minimum to start: customer name and industry, the problem in their words, how they use the product, and at least one result. If there's no interview yet, give the user the questions below and stop until the answers come back.

## Interview questions

Ask these, in this order, and record the answers word for word:

1. What was your role and team when this started?
2. What were you doing before, and what was it costing you? (time, money, risk, missed targets)
3. What made you look for something new at that moment?
4. What else did you consider, and why did you pick this?
5. How did the first month go? What surprised you?
6. What has changed since? What can you measure?
7. Where do those numbers come from? (dashboard, report, estimate)
8. What would you tell a peer who's in the position you were in?

Also ask for permission: may we use your name, title, company name and logo, and these quotes?

## Steps

### 1. Pull out the evidence

From the transcript, list:
- the before state, as specific as possible
- the trigger that made them act
- every result, with its source and timeframe
- 3 to 5 quotes worth using, copied exactly, with name, title and company

Produces: an evidence sheet. Anything without a source goes in a separate "unconfirmed" list.

### 2. Find the story arc

Before, turning point, after. Pick the one outcome that matters most to the reader as the headline. It must be an outcome (revenue, time saved, risk removed), not an activity ("rolled out to 40 users").

Find one signature moment: the specific thing that shows the change better than a number can. It must come from the customer, not from you.

Produces: one-sentence hero statement (under 25 words) and the arc in three lines.

### 3. Build the metrics

Pick up to three numbers for the metrics bar. For each, write the number, what it measures, the timeframe and the source.

If a number is missing, write `[METRIC NEEDED: what to ask for]`. Never round up, estimate on the customer's behalf, or borrow a number from a different customer or a different context.

Produces: a metrics table with sources.

### 4. Draft the sections

- **Hero statement:** one sentence, the outcome.
- **Metrics bar:** up to three sourced numbers.
- **About the customer:** two or three sentences.
- **The challenge:** the before state in their words. Specific pain, not "they were struggling to grow".
- **Why they chose you:** the trigger and the decision.
- **The solution:** how they actually use the product, tied to named features.
- **The results:** the after state, metrics in context, one or two quotes.
- **Call to action:** one next step for a reader in the same position.

### 5. Check before it ships

Run the checks under "What good looks like". Send the draft to the customer for approval of every quote and number.

## Output

Save to `outputs/product-marketing/<customer-slug>-case-study.md`. Add a short source list at the bottom: each metric and quote, and where it came from. Remove that list before publishing.

## What good looks like

- The headline is an outcome the customer stated, not an activity count.
- Every number has a source and a timeframe. Every quote is verbatim and attributed.
- The before state is specific enough that a reader recognises their own situation.
- The customer approved the final text.
- Mark anything still open with `[CONFIRM: detail]`.

## Mistakes to avoid

- Inventing or rounding metrics. Mark the gap instead.
- Paraphrasing a quote into something "better". Use their words or no quote.
- A generic opening like "Company X was struggling with growth".
- Jumping to the solution with no clear before state.
- Writing the whole thing in third person with no customer voice.
- Publishing before the customer has signed off on names, quotes and numbers.

Check back with the customer at three and six months. Stronger results usually arrive later; update the study when they do.
