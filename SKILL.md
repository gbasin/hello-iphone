---
name: iphone-launch-presentation-analysis
description: Build a Slidev study deck in the style of this 2007 iPhone launch analysis: transcript-led, visual-evidence-based, and focused on explaining what a speaker is doing and why.
---

# iPhone Launch Presentation Analysis

Use this skill when the task is to turn a major keynote, product launch, or founder presentation into a Markdown-based study deck that merges transcript excerpts, original visuals, and practical rhetorical analysis.

## Goal

Create a deck that helps the audience understand the presentation mechanics, not just the content. The output should answer:

- What is the speaker trying to make the audience believe?
- What sequence of moves changes that belief?
- How do the visuals support or sharpen each move?
- What reusable presentation pattern can we learn from it?

## Source Workflow

1. Extract the transcript text and use it as the narrative spine.
2. Render the source slides or video frames into image assets.
3. Make a contact sheet of the visuals before selecting deck assets.
4. Identify the major belief-change moments: setup, enemy, contrast, mechanism, proof, emotional payoff, price or ask, close.
5. Select only the visuals that illustrate those moves cleanly.

## Deck Structure

Use Slidev Markdown. A strong deck usually has:

- A title slide that states the overall analytical thesis.
- A thesis slide explaining the presentation as a sequence of belief changes.
- A spine or outline slide showing the full arc.
- A series of paired evidence slides: short transcript quote, original visual, analysis.
- Chapter breaks before major mode changes, especially before live-demo analysis.
- A closing playbook slide that turns the case study into reusable rules.
- A source-notes slide.

## Slide Pattern

Most analysis slides should follow this pattern:

- Eyebrow: name the move, e.g. `Move 3: frame the enemy`.
- Claim headline: explain what the speaker is doing.
- Short excerpt or paraphrase from the transcript.
- Source visual in a stable frame.
- Analysis block: explain why the move works.

Avoid long transcript blocks. Use excerpts as evidence, then paraphrase the mechanics.

## Analytical Lens

Look for these moves:

- Historical permission: the speaker earns the right to claim a category shift.
- Enemy framing: the status quo is made to look structurally trapped.
- White-space positioning: the product occupies a gap the speaker just drew.
- Mechanism reveal: the core invention is presented as the obvious answer.
- Novelty/familiarity alternation: new behavior is balanced with familiar adoption paths.
- Demo by verbs: actions like touch, scroll, pinch, call, browse, and zoom carry the feature claims.
- Repetition: repeated language turns features into category-level claims.
- Humor after proof: jokes work best after the product has already demonstrated credibility.
- Price anchoring: the value argument is framed against the bundle of outcomes, not cost.
- Slogan compression: the close compresses the argument the audience has already accepted.

## Visual Direction

Use a restrained editorial visual system:

- Dark background with high-contrast white text.
- A small accent palette for analysis labels and emphasis.
- Large readable headlines.
- Source visuals framed as proof objects.
- No decorative filler.
- No dense quote walls.

The design should feel like a serious product-story teardown, not a generic keynote template.

## Verification

Before delivery:

- Run `npm run build`.
- Open the deck locally or verify with Playwright.
- Spot-check several slides for readable text, loaded images, and non-overlapping layout.
- Keep generated `dist/`, browser screenshots, and temporary contact sheets out of version control unless explicitly requested.
