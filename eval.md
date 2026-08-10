# Humanizer eval

Run this against your own output before returning it. Answer each check pass or fail. Any fail means fix the draft and run the checks again. Do not delegate this to a separate evaluator agent; check your own work.

For detect-mode responses, skip to the Detect mode section at the bottom.

## Fabrication

1. Does the rewrite contain any fact, name, number, date, quote, or citation that is not in the source text? A single invented specific is a defect, even when it reads better than the vague original.
2. Where a vague claim became specific, did the specific come from the source or the user rather than from you?
3. Where a sentence needed real-world detail that does not exist in the source, was the plain version written or the detail asked for, rather than filled in?

## Preservation

4. Does every claim in the original survive into the rewrite? Depth may vary and paragraphs may merge or split, but no claim quietly disappears.
5. Did strong human sentences survive untouched instead of being rewritten for consistency?
6. Is the amount of cutting proportional to the actual slop, rather than a compression pass that strips character?
7. Would the original writer recognize this as their own voice? Vocabulary, cadence, bluntness, humor, uncertainty, and digressions intact?
8. If a voice sample was provided, were its habits matched, including its em dash frequency?
9. Were DETECTION GUIDANCE false positives respected? Polish, correct-but-fancy vocabulary, and isolated hits are not slop.
10. Are the signs of human writing preserved: concrete hard-to-fabricate detail, mixed feelings, genuine asides, varied sentence length?

## Content patterns (1-6)

11. Significance inflation, notability puffery, superficial `-ing` analyses, promotional language, weasel attribution, and "challenges and future prospects" scaffolding all removed?
12. Is every vague attribution either sourced by name from the source text or cut? An unsupported claim gets cut, not decorated.

## Language and grammar (7-13)

13. Banned AI vocabulary gone?
14. Copula avoidance fixed: "is" and "has" used where they read better than "serves as" and "features"?
15. Negative parallelisms ("it's not X, it's Y") stated as direct positive claims?
16. Forced rule-of-three, synonym cycling, false ranges, and subjectless passive fragments fixed?

## Style (14-19)

17. Zero em dashes (`—`) and zero prose-break en dashes, unless a voice sample overrides §14. Scan the literal characters, do not eyeball it.
18. Decorative boldface, inline-header lists, title-case headings, emoji, and curly quotes removed?
19. Do bullets earn their place, or should they be prose?

## Communication and filler (20-30)

20. Chatbot framing, sycophancy, offer-to-continue closers, knowledge-cutoff disclaimers, and speculative gap-filling removed?
21. Filler phrases, excessive hedging, hyphenated-pair overuse, and persuasive authority tropes cut?
22. Generic positive conclusions replaced with the last concrete point, takeaway, or next action?
23. Signposting cut, and fragmented headers and diff-anchored phrasing fixed?

## Cadence (31-33)

24. Manufactured punchlines and runs of staccato fragments broken up?
25. Aphorism formulas replaced with the concrete claim they were gesturing at? Delete the formula rather than rewriting it into a better one.
26. Conversational rhetorical openers cut, so the point arrives without the fake-candid pause?

## Rhetorical posturing (34-36)

27. Colon reveals rewritten as plain sentences, with sentence case after any colon that remains?
28. Faux-insight setups deleted so the claim stands on its own?
29. Interpretive metadiscourse removed in both positions: the preamble announcing importance and the trailing aside assigning weight?

## Portability

30. Does every generic sentence pass the portability test? If a sentence could move unchanged to another person, company, country, or product, it is filler. Cut it, or replace it with a fact, example, mechanism, consequence, or judgment specific to this subject and present in the source.

## Final read

31. Does the draft avoid robotic symmetry, repeated sentence shapes, and stacked punchy fragments?
32. Does it read naturally aloud, with varied sentence length?
33. Does the deliverable match the invocation mode? Pasted text gets the draft, audit bullets, and final rewrite; file mode rewrites in place and reports a summary; embedded mode returns only the final text.

## Detect mode

34. Is each finding named by its numbered pattern, with the offending line quoted and a fix given in a few words?
35. Were clusters reported rather than isolated hits?
36. Does the response avoid rewriting the draft, scoring it, and claiming AI authorship?
