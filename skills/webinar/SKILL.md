---
name: webinar
description: Plans a B2B webinar from topic to follow-up: positioning, format, content outline, run of show, promotion calendar, registration page and invite copy, attendee and no-show follow-up, and a repurposing plan. Use for "webinar", "plan a webinar", "webinar brief", "online event", "run of show", "launch webinar" or "partner webinar".
version: '1.0.0'
license: MIT
---

# Webinar brief

Plan a webinar as a full cycle: why anyone should come, what happens on the day, how you fill the room, and what happens after. Most of a webinar's value comes after it ends, so plan the follow-up and repurposing before you promote it.

## When to use it

- A launch moment, a thought leadership session, a demo session or a partner event.
- You need a brief the speakers, the marketer and the ops person can all work from.

Don't use it if you only need slides, only a demo script, or only a registration page. Do those directly.

## Inputs

Agency users swap `context/` for `clients/<client>/context/`.

Required from the user: topic, target audience, date and time, speakers, and whether there is a live demo.

From context:
- `context/messaging/`: so the topic lines up with what you sell.
- `context/icp/`: so the promise speaks to a real pain.
- `context/brand/`: tone for all copy.
- `context/goals/` if you have it: targets and past webinar numbers.

If required inputs are missing, ask for topic, date and speakers first. Mark any unconfirmed logistics `[CONFIRM: detail]`. If you have a web search tool (Exa, Firecrawl or plain web search), check what competitors have run on the same topic recently.

## Steps

1. **Position it.** Topic angle, the promise to attendees, why now, and what makes it different from the last ten webinars on this topic. Produces: a one-sentence positioning statement.
2. **Set goals.** Registrations, attendance rate, questions asked, demo requests, pipeline. Mark targets `[TARGET]` if you have no past numbers.
3. **Pick the format.** Solo talk, interview, panel, demo plus Q&A, or hands-on workshop. Match length to format: 30 minutes for a demo, 45 for a talk, 60 for a panel.
4. **Outline the content.** Default for 45 minutes: 5 intro, 10 context, 20 core, 5 how to apply it, 5 Q&A. Produces: a section list with timings and the one point each section makes.
5. **Write speaker prep.** Talking points per section, transitions, and the five questions you expect from the audience with draft answers.
6. **Build the run of show.** T-30 tech check, T-15 speakers online, T-5 green room, 0:00 live, section timings, close, stop recording. An owner on every row.
7. **Plan engagement.** Polls, prompts for questions, resource links dropped in chat, with the minute each one happens.
8. **Build the promotion calendar.** From three weeks out to one hour before. Three or four emails, social posts from speakers and the company, partner posts if co-hosted. An owner on every row.
9. **Write the copy.** Registration page (headline under 70 characters, subhead under 120, three to five bullets on what they'll learn, speaker bios, form fields), three or four invite emails, social posts, and a partner kit if co-hosted.
10. **Write the follow-up.** Attendees: day 0 recording, day 2 key takeaway, day 5 a next step such as a demo. No-shows: day 0 recording with what they missed.
11. **Plan repurposing.** A blog post in week one, quote cards and short clips in weeks one and two, an audio extract in week two.
12. **Set up the review.** Registrations against target, attendance rate, watch time, questions asked, demo requests, pipeline. Book the review date now.

## Output

Save to `outputs/product-marketing/<webinar-slug>-webinar-brief.md` with these sections: overview, positioning, goals, format and outline, speakers and prep, run of show, engagement plan, promotion calendar, copy (registration page, emails, social), follow-up sequences, repurposing plan, metrics review, open questions.

If the webinar is part of a launch, link it from the `/product-launch` plan. If it is one stage of a campaign, take the story beat from `/storytelling`.

## What good looks like

- The positioning gives a reason to attend that this audience can't get elsewhere.
- The outline fits the time slot with room for questions.
- Every run of show and promotion row has an owner and a time.
- All copy is written, not described.
- Both follow-up sequences exist: attendees and no-shows.
- No invented speakers, guests or numbers.

## Mistakes to avoid

- A topic that is really a product pitch with a webinar title.
- Too much content for the slot, so Q&A gets cut.
- Promotion that starts a week out. Most registrations need three weeks of build-up.
- No follow-up for no-shows, who are often half the registrants.
- Treating the recording as the only output and never cutting it into anything else.
