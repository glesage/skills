---
name: unslop
description: Cut AI tells from any writing.
---

## Process

1. Scan for the patterns below.
2. Rewrite. Preserve meaning, match intended tone.

## Clarity for humans

1. Use mermaid diagrams, flow charts and ASCII diagrams to visually show information
2. Use tables and bullet lists when possible to list information instead of text
3. Prefer concrete examples instead of technical jargon explanations and details.
4. Add soul:
- **Have opinions.** React to facts instead of neutrally listing pros and cons.
- **Use "I" when it fits.** First person isn't unprofessional.
- **Be specific.** Not "this is concerning" but "there's something unsettling about agents churning away at 3am."

## Patterns to detect and fix

### Content

1. **Puffery.** "pivotal moment", "testament to", "evolving landscape", "setting the stage for", "indelible mark", "deeply rooted". Cut puffery, state what happened.
2. **Promotional language.** "nestled", "vibrant", "breathtaking", "groundbreaking", "renowned", "stunning", "must-visit". Use neutral descriptions.
3. **Vague attributions.** "Experts believe", "Industry reports suggest", "Some critics argue". Name the source or delete.
4. **Formulaic challenges.** "Despite challenges... continues to thrive." Replace with specific facts.

### Language

5. **AI vocabulary.** Additionally, crucial, delve, enduring, enhance, fostering, garner, interplay, intricate, landscape (abstract), pivotal, showcase, tapestry (abstract), testament, underscore, vibrant. Replace with plain words.
6. **Fancy ways to say "is".** "serves as", "stands as", "boasts", "features". Just say "is" or "has".
7. **"Not just X, but Y."** State the point directly instead.
8. **False ranges.** "from X to Y" where X and Y aren't on a meaningful scale. List topics directly.

### Style

9. **Em dash overuse.** Avoid em dashes entirely.
10. **Colon overuse.** Colons are fine before a list or example. Not as mid-sentence connectors.
11. **Boldface overuse.** Don't bold every proper noun or acronym.
12. **Inline-header lists.** The tell is a bold label and colon that restates the line
13. **Title case headings.** Use sentence case.
14. **Curly quotes.** Replace with straight quotes.

### Communication artifacts

15. **Chatbot phrases.** "I hope this helps!", "Let me know if...", "Of course!", "Certainly!", "Found the smoking gun!" Remove.
16. **Cutoff disclaimers.** "While specific details are limited..." Find sources or remove.
17. **Sycophantic tone.** "Great question! You're absolutely right!" Respond directly.

### Filler

18. **Filler phrases.** "In order to" becomes "To". "Due to the fact that" becomes "Because". "It is important to note that" gets deleted.
19. **Excessive hedging.** "could potentially possibly be argued that it might" becomes "may".
20. **Generic conclusions.** "The future looks bright." State specific plans or facts.

### Plain speech

21. **Say what it does, not how it feels.** "the database stays close at hand", "SQL you can read", "types that follow your schema" name a feeling. The fix names the mechanism or a number: "`.toSQL()` returns the exact string sent to the database", "a column rename fails the build". Ask what the sentence tells the reader to do or know, then write that. If you can't restate it as a concrete instruction, fact, or number, cut it. One more check: if the sentence could appear unchanged in another project's docs, it says nothing about this one. Cut it.
22. **Shorten or split dense sentences.** If the reader has to backtrack to parse a sentence, break it in two or drop clauses. One idea per sentence.
23. **Active voice.** Prefer it. Catch "is/are/was/were + past participle" and name the actor: "queries are validated" becomes "the compiler validates queries", "the file is parsed by the loader" becomes "the loader parses the file". Passive is fine only when the actor is unknown or genuinely doesn't matter.
24. **Cut adverbs, or use a stronger verb.** "runs quickly" becomes "is fast" or the number. "significantly improves" becomes the measured delta. An adverb propping up a weak verb means the verb is wrong.
25. **Prefer the plain word.** "utilize" becomes "use", "leverage" becomes "use", "facilitate" becomes "help", "numerous" becomes "many", "in the event that" becomes "if". The fancier synonym is rarely clearer.
