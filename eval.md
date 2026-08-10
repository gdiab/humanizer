# Humanizer eval

Run this against your own output before returning it. Answer each check pass or fail. Any fail means fix the draft and run the checks again. Do not delegate this to a separate evaluator agent; check your own work.

For detect-mode responses, skip to the Detect mode section at the bottom.

## Preservation

1. Does the rewrite cover everything the original covered? Same number of sections, same claims, nothing quietly dropped.
2. Are all claims, stats, quotes, names, and examples from the original preserved, with nothing invented?
3. Did strong human sentences survive untouched instead of being rewritten for consistency?
4. Is the amount of cutting proportional to the actual slop, rather than a compression pass that strips character?
5. Would the original writer recognize this as their own voice? Vocabulary, cadence, bluntness, humor, uncertainty, and digressions intact?
6. Were DETECTION GUIDANCE false positives respected? Polish, correct-but-fancy vocabulary, and isolated hits are not slop.
7. Are the signs of human writing preserved: concrete hard-to-fabricate detail, mixed feelings, genuine asides, varied sentence length?

## Content patterns (1-6)

8. Significance inflation, notability puffery, superficial `-ing` analyses, promotional language, weasel attribution, and "challenges and future prospects" scaffolding all removed?
9. Is every vague attribution either sourced by name or cut? If the writer has no source, was it flagged rather than invented?

## Language and grammar (7-13)

10. Banned AI vocabulary gone?
11. Copula avoidance fixed: "is" and "has" used where they read better than "serves as" and "features"?
12. Negative parallelisms ("it's not X, it's Y") stated as direct positive claims?
13. Forced rule-of-three, synonym cycling, false ranges, and subjectless passive fragments fixed?

## Style (14-19)

14. Zero em dashes (`—`) and zero prose-break en dashes. Scan the literal characters, do not eyeball it. En dashes are acceptable only in numeric and date ranges and compound relationships if the host project's style allows them; never as a prose break.
15. Decorative boldface, inline-header lists, title-case headings, emoji, and curly quotes removed?
16. Do bullets earn their place, or should they be prose?

## Communication and filler (20-30)

17. Chatbot framing, sycophancy, knowledge-cutoff disclaimers, and speculative gap-filling removed?
18. Filler phrases, excessive hedging, hyphenated-pair overuse, and persuasive authority tropes cut?
19. Generic positive conclusions replaced with the last concrete point, takeaway, or next action?
20. Signposting and emphasis preambles cut, including the announcement form ("here's the thing", "the part I keep coming back to")?
21. Fragmented headers and diff-anchored phrasing fixed?

## Rhetorical posturing (31-33)

22. Colon reveals rewritten as plain sentences, with sentence case after any colon that remains?
23. Faux-insight setups deleted so the claim stands on its own?
24. Interpretive metadiscourse removed, both the trailing aside and the redundant gloss?

## Portability

25. Does every generic sentence pass the portability test? If a sentence could move unchanged to another person, company, country, or product, it is filler. Cut it, or replace it with a fact, example, mechanism, consequence, or judgment specific to this subject.

## Endings

26. Was any fake-profound kicker deleted rather than rewritten into a better metaphor? Do not preserve its rhythm. End on the clearest concrete sentence already in the draft.
27. Was any summary-recap ending cut? The reader was just there.

## Final read

28. Does the draft avoid robotic symmetry, repeated sentence shapes, and stacked punchy fragments?
29. Does it read naturally aloud, with varied sentence length?
30. Does the deliverable include what Process and Output specifies: the draft, the brief still-AI bullets, and the final rewrite?

## Detect mode

31. Is each finding named by its numbered pattern, with the offending line quoted and a fix given in a few words?
32. Were clusters reported rather than isolated hits?
33. Does the response avoid rewriting the draft, scoring it, and claiming AI authorship?
