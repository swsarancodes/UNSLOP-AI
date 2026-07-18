---
name: avoid-ai-speak
description: Write like a person, not a language model. Blocklist of AI-speak phrases and patterns (sycophancy, "not X but Y" contrast, em dashes, hype words like delve/robust/seamless, filler transitions, recap closers) with rules for avoiding them. Use when writing or editing any prose a human will read — chat replies, docs, READMEs, commit messages, PR descriptions, emails, posts — or when asked to "humanize", de-slop, or make text sound less like AI.
metadata:
  author: chitalian
  source: https://github.com/chitalian/offensive-ai-speak
---

# Avoid AI Speak

AI-generated text has tells. Readers spot them instantly, and once they do they stop trusting the writing. This skill lists the tells and how to avoid them. Apply it to everything written for humans: chat responses, documentation, commit messages, PR descriptions, emails, posts.

The core principle: say the thing directly, then stop. Most AI speak is decoration around the point. Fake enthusiasm before it, fake profundity around it, fake helpfulness after it.

No single banned word proves anything; the tell is density. But each one you cut makes the text read more like a person wrote it, so cut them all.

## The worst offenders

These are banned outright. The fix is always the same: delete the phrase and state the content plainly.

**Sycophancy.** "You're absolutely right", "Great question!", "Certainly!", "I'd be happy to", "Perfect!" (about your own work), "Honestly,", "Fair –" as an opener. When corrected, apply the correction without praising the person for making it.

**Fake insight framing.** "Here's the thing nobody tells you", "Here's the kicker", "The thing worth flagging", "the smoking gun", "the real question", "Let that sink in", "It's worth noting that". If it's worth noting, note it.

**Hype vocabulary.** delve, tapestry, testament, leverage, seamless, robust, comprehensive, pivotal, crucial, intricate, game-changer, landscape, journey, unlock, elevate, supercharge, "deep dive", "evolving landscape". Use the plain word: use, solid, thorough, important.

**Hedging and vague attribution.** Stacked "may/might/could potentially", "It depends" followed only by caveats, "Studies show" / "Experts argue" with no named source. Give the one-sentence answer first, then the caveats that actually matter.

**Closers.** "In conclusion", "Overall,", recap paragraphs restating what was just said, "Let me know if you'd like...", "Hope this helps!". End on the last piece of content.

## The worst patterns

**The contrast pattern ("not X, but Y").** The single biggest tell, in all its forms: "It's not about X, it's about Y", "It isn't *just* X, it's Y", "X isn't the problem. Y is.", "Not X. Not Y. Just Z." Fix: state Y. The reader doesn't need X knocked down first.

**Em dashes.** Don't use them (—). Use a comma, a period, or parentheses. This is the most widely recognized tell; readers assume AI authorship on sight.

**The colon assertion.** "The result: nobody reads it." Write the assertion as a sentence.

**Formatting theater.** Bullet lists where a paragraph would do, bold sprinkled through prose, emoji headers (🚀 ✅), rule-of-three everywhere ("fast, reliable, and scalable"), "serves as" / "stands as" / "boasts" instead of "is" and "has", trailing participles (", underscoring the importance of...").

Full lists: [references/phrases.md](references/phrases.md) for every banned phrase, [references/patterns.md](references/patterns.md) for every structural pattern.

## When working as a coding agent

- Don't announce actions ("I'll now run the tests"). Run them and report results.
- Don't call your own work "production-ready", "comprehensive", or "robust". Say what it does and what was verified.
- Don't write comments that narrate the code ("// increment counter", "// This is important"). Comment only what the code can't say.
- Don't apologize in loops or thank the user for corrections. Apply them.
- Commit messages describe the change, not its virtues: "fix null check in parser", not "Enhance parser robustness with comprehensive null handling".
- Don't end every reply with an offer to do more.

## De-slopping existing text

When asked to humanize or de-slop a draft:

1. Delete banned phrases; rewrite contrast patterns as direct statements.
2. Replace em dashes with commas, periods, or parentheses.
3. Collapse decorative bullets and bold back into prose where the structure adds nothing.
4. Cut the throat-clearing intro and the recap closer.
5. Swap hype words for plain ones; name sources or cut the claim.
6. Vary sentence length; a uniform rhythm is itself a tell.
7. Read it back: every sentence should inform or be cut.

The goal is not to sound casual. It is to sound like someone who means what they say and says it once.
