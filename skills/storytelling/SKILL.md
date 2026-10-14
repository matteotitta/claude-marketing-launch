---
name: storytelling
description: Builds a narrative-driven B2B campaign from your positioning: the tension, the story arc, before-and-after archetypes, and a multi-week content plan with briefs per piece. Use for "storytelling", "brand narrative", "story arc", "founder story", "narrative campaign", "hero's journey campaign" or "multi-week campaign". Not for a single post or blog article.
version: '1.0.0'
license: MIT
---

# Storytelling

Turn your positioning into a story that runs across several weeks and channels. The story gives every piece of content one shared arc, so a buyer who sees three posts and an email feels one argument building, not four unrelated messages.

## When to use it

- A launch, a new category claim or a brand refresh that needs more than one announcement.
- A founder-led campaign where the founder's view is the hook.
- A multi-week content plan that should build to something.

Don't use it for a single blog post, a single social post, landing page copy or an email sequence with no arc. Write those directly.

## Inputs

Agency users swap `context/` for `clients/<client>/context/`.

- `context/positioning/`: category, alternatives, differentiators.
- `context/messaging/`: capabilities and proof points.
- `context/icp/`: the champion persona and their pains, in their own words if possible.
- `context/brand/`: tone of voice.
- `context/expert-pov/` if you have it: the founder's or expert's beliefs and stories.
- `context/competitors/` if you have it: the stories competitors tell.

If positioning or ICP is missing, ask the user for the core claim and the buyer's main pain before starting. Say which files were missing in the output.

## Steps

### 1. Find the tension

Answer four questions:
- What is the status quo the buyer lives with?
- Why does it need to change now?
- Why do the current ways of fixing it fail?
- What does the world look like after?

Quantify the tension where your inputs allow ("teams lose a day a week to this"). If you don't have a number, don't invent one.

Produces: a one-paragraph tension statement.

### 2. Map the emotions

For each main pain, name the feeling underneath it (frustration, fear of looking bad, boredom, being stuck) and the story beat that speaks to it.

Produces: a pain, emotion, story beat table.

### 3. Find the gap in competitors' stories

For each main alternative: the story they tell, what it leaves out, and your angle. Position against the status quo or the category, not against a named competitor.

Produces: one line per alternative, plus your angle.

### 4. Pick the arc

Match the goal to a shape:
- **Hero's journey:** the buyer is the hero, you are the guide. Good for transformation and launches.
- **Rags to riches / before and after:** a clear change in state. Good for customer stories.
- **Overcoming the monster:** a named enemy, usually a bad old way of working. Good for category claims.
- **Rebirth:** a team or market that reinvents itself. Good for brand refreshes.

For a founder-fronted campaign, pick an arc the founder can tell honestly. A founder whose story is a problem they lived should not be asked to narrate a grand vision, and the reverse.

Produces: the chosen arc, one line on why, and its stages mapped to content beats.

### 5. Name the before and after

Write two archetypes: who the buyer is before and after. For each, give an evocative name (a noun, not an adjective), what they do, what they use, what they feel, and one belief in their own voice ("I'll just do it myself, it's faster").

Produces: two short archetype profiles.

### 6. Build the campaign

- **Timeline:** usually four to six weeks. Each week carries one stage of the arc.
- **Anchor pieces:** one per week (a long post, an article, a video, a webinar). For each: title, the one idea, the story beat, key messages, proof, call to action.
- **Supporting pieces:** short posts, emails, clips cut from each anchor.
- **Distribution:** channel, format, frequency and what each channel is for.
- **Metrics:** awareness, engagement, conversion, pipeline. Use targets from `context/goals/` or mark them "Suggested: X".

Produces: a week-by-week table and a brief per anchor piece.

## Output

Save to `outputs/content/<campaign-slug>-story-campaign.md` with these sections: tension, emotional map, competitor gap, arc, archetypes, timeline, anchor briefs, supporting pieces, distribution, metrics, open questions.

If the campaign supports a launch, link it from the `/product-launch` plan. If it needs customer proof, run `/case-study`. If a week's anchor is a live session, run `/webinar`.

## What good looks like

- The change is shown as a shift in who the buyer is, not a generic outcome.
- The tension is specific and, where possible, has a number.
- Archetype names are concrete nouns you could picture.
- Every proof point and metric traces to a context file or is marked as a placeholder.
- Each week's anchor moves the arc forward; nothing repeats the week before.

## Mistakes to avoid

- A story about the product instead of the buyer.
- Attacking a named competitor instead of the old way of working.
- Inventing customer quotes or numbers to make a beat land. Use `[PLACEHOLDER: ...]`.
- Metaphors the audience won't recognise. Check them against who the buyer actually is.
- Six weeks of content with no build: every piece saying the same thing.
