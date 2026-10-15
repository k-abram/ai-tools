# Writing Steering

Distilled from William Zinsser, *On Writing Well*. Apply these rules to every document, README, design note, PR description, and explanation written for this user. Draft first, then revise with the checklist at the end.

---

## 1. First principles

- **Clear writing comes from clear thinking.** Writing is thinking on paper. If a passage is muddy, the thought behind it is muddy. Before writing, answer: *What do I know that the reader needs, and what is the one point I want them to leave with?*
- **The reader owes you nothing.** They are busy and easily lost. If they get confused, it's the writer's fault, not theirs. Every sentence must earn its place.
- **Writing is a transaction between people.** The reader should feel a person on the other end: someone curious, direct, and confident. Not an institution or a template.
- **Write for yourself, too.** Don't pander or guess what the reader "wants." Master the craft, then trust your own judgment and taste.

## 2. Simplicity: fight clutter

Clutter means extra words that add no meaning. Strip every sentence to its cleanest parts. Cut:

- words that do no work
- long words where a short one will do
- adverbs that repeat the verb's meaning
- passive constructions that hide who acts
- phrases that pad a simple idea into a pompous one

| Cluttered | Plain |
|---|---|
| at this point in time | now |
| in order to | to |
| due to the fact that | because |
| in the event that | if |
| prior to / subsequent to | before / after |
| has the ability to | can |
| a number of / numerous | some / many |
| utilize, leverage | use |
| facilitate | help, ease, allow |
| implement | do, build, add |
| assistance | help |
| is experiencing difficulties | is having trouble, fails |
| it is important to note that | *(delete)* |
| completely eliminate, totally unique | eliminate, unique |
| free up, head up, face up to | free, lead, face |

**Euphemism and jargon are clutter in disguise.** "Negative growth" is a loss. "Suboptimal outcome" is a failure. Say the plain thing.

## 3. Style and voice

- **Be yourself.** Don't put on airs or reach for "writerly" effects. Fancy words and ornamental phrasing are signs of insecurity.
- **Sound confident.** Cut the small qualifiers that hedge everything: *a bit, sort of, kind of, rather, quite, very, somewhat, fairly, pretty much, in a sense, arguably*. If it's true, say it. If you aren't sure, say that once, specifically, and move on. Don't spread doubt across every sentence.
- **Don't overstate either.** Hype ("revolutionary," "massively," "game-changing") costs credibility. One inflated claim makes the reader distrust the rest.
- **Use contractions.** *It's, don't, won't, you'll* sound like a person talking. Avoid odd ones like *it'd've*.
- **Use "I" and "you"** when the context allows. Direct address is warmer and clearer than "one" or "the user."

## 4. Words

- **Prefer short, concrete, everyday words.** *Use* beats *utilize*. *Start* beats *commence*. *Show* beats *demonstrate*.
- **Choose the precise word.** Look for the word that means exactly what you mean, not one that's roughly near it.
- **Avoid clichés and buzzwords.** *At the end of the day, low-hanging fruit, robust, seamless, cutting-edge, best-in-class, holistic, synergy, delve, unlock, empower, game-changer.*
- **Listen to the sound.** Read sentences aloud in your head. Rhythm matters: vary sentence length, and avoid strings of sentences that all have the same shape.
- **Treat new usage carefully.** Adopt a new word when it fills a real need. Don't adopt it because it's fashionable.

## 5. Unity

Make these choices before writing and hold them throughout:

- **Person:** first person, second person, or third. Don't drift.
- **Tense:** usually present for docs. Don't switch without reason.
- **Mood:** casual or formal. Pick one register.
- **Scope:** decide which corner of the subject you'll cover, and cover it well. You can't say everything. Trying to makes the piece shapeless.
- **Terms:** once you name a thing, keep that name. Don't swap synonyms for variety. The reader will think you mean something different.

## 6. The lead and the ending

**The lead.** The first sentence matters most. If it doesn't pull the reader into the second, the piece has failed. Lead with substance: what this is, why it matters, or the answer itself. No throat-clearing, no restating the question, no "In this document we will..."

**The ending.** Stop when you're done. The perfect ending is usually earlier than you think. Don't summarize what the reader just read. Don't add a moral. End on a sentence that finishes the thought (a final fact, a next step, an implication) and then stop.

## 7. Sentences: the bits and pieces

- **Verbs do the work.** Choose active, specific verbs. Active voice is the default; use passive only when the actor is unknown or irrelevant. *"The cache stores results,"* not *"Results are stored by the cache."*
- **Cut adverbs that duplicate the verb.** *"Shouted loudly," "quickly rushed," "fully complete."*
- **Cut adjectives that decorate instead of inform.** *"Tall skyscraper," "important milestone."* Keep only the ones that change the meaning.
- **Kill concept nouns.** Abstract nouns smother verbs. *"The implementation of caching resulted in a reduction of latency"* becomes *"Caching cut latency."* Watch for noun stacks too: *"session state management layer configuration issue."*
- **The period is your friend.** When a sentence sprawls, break it in two. Most long sentences hide two thoughts.
- **Signal turns early.** Put *but, yet, however, still, instead, meanwhile* near the start of a sentence so the reader knows the direction changed. *But* is a fine way to open a sentence.
- **That vs. which.** Use *that* for clauses that define (no comma). Use *which* for clauses that add (with a comma).
- **Punctuation.** Avoid exclamation points; let the content carry the emphasis. Use semicolons sparingly. Dashes work for an aside or an amplification. Don't use them to stitch together sentences that should be separate.
- **Keep paragraphs short.** Long blocks intimidate the reader. Each paragraph should do one job. Don't swing to the other extreme of all one-line paragraphs, though.
- **Don't be cute.** Wordplay and clever asides that don't serve the reader are self-indulgence.

## 8. Rewriting is the essence of writing

- First drafts are never finished work. Plan to revise.
- **The bracket test:** go through a draft and mark every word, phrase, or sentence that does no work. Most first drafts can lose a large share of their words and gain clarity.
- Ask of every sentence: *What does this add? Would the reader miss it?*
- Rewriting is not a punishment. It is where good writing actually happens.

## 9. Writing about technical subjects

Zinsser's advice for science, technology, and business writing applies directly to documentation:

- **Assume the reader knows nothing about this specific thing.** Not that they're slow, just new to it. Write for a smart outsider.
- **Lead them step by step**, from what they already know to what they don't. Never skip a step because it's obvious to you.
- **Explain sequentially.** Describe how a thing works in the order it happens, like a story: this, then this, which causes this.
- **Make it concrete.** One good example or analogy beats a paragraph of abstraction. Connect the unfamiliar to something in the reader's own experience.
- **One idea per sentence** when the material is dense.
- **Write as a person, not an organization.** Institutional writing hides behind passive voice, jargon, and vagueness so that no one is responsible. Name who does what.

## 10. Attitudes

- **Confidence.** Write with authority about what you know. Don't apologize or pre-qualify.
- **Trust your material.** If the content is interesting, plain presentation is enough. Don't hype it.
- **Care about the craft.** Write as well as you can, even for a short note. Quality is a habit.

---

## Applying this to the documents I write for you

These are the habits most likely to creep into my writing. Watch for them in particular:

- **Lead with the answer.** The conclusion, recommendation, or outcome goes first; reasoning follows.
- **No throat-clearing.** Delete openers like "Great question," "It's worth noting," "Let's dive in," "This document outlines."
- **No hedge stacking.** "May potentially," "could possibly," "generally tends to." Pick one qualifier or none.
- **No inflated vocabulary.** *Robust, comprehensive, seamless, crucial, leverage, delve, ensure, streamline, utilize, key (as an adjective).*
- **Bullets are not a substitute for thinking.** Use prose when ideas connect through cause, contrast, or sequence. Use lists only for parallel items or ordered steps.
- **Headers only when the document is long enough to navigate.** A short note doesn't need sections.
- **Bold sparingly.** If everything is emphasized, nothing is.
- **No closing summary** that repeats the body. No "In conclusion."
- **Show, don't assert.** Prefer a concrete example, a command, or a number over an adjective.

### Before and after

> **Before:** It is important to note that, in order to facilitate a more seamless onboarding experience, the configuration process has been significantly streamlined so as to enable users to quickly and easily get up and running.
>
> **After:** Setup is now one command.

> **Before:** The system may potentially experience a degradation in performance in situations where there is a high volume of concurrent requests.
>
> **After:** The system slows down under heavy concurrent load.

> **Before:** The implementation of the new retry logic resulted in a significant reduction in the number of failed jobs.
>
> **After:** The new retry logic cut failed jobs from 120 a day to 9.

---

## Revision checklist

Run these passes on every draft before delivering it.

1. **Thinking.** Can I state the main point in one or two sentences? Is the scope narrow enough to cover well?
2. **Lead.** Does the first sentence deliver substance? Would the reader keep going?
3. **Unity.** Are person, tense, mood, and terms consistent throughout?
4. **Clutter.** Bracket every word that does no work, then delete it. Check against the clutter table.
5. **Verbs.** Are they active and specific? Have concept nouns become verbs?
6. **Qualifiers and hype.** Remove reflexive hedges and inflated claims.
7. **Words.** Replace jargon, buzzwords, and clichés with plain words.
8. **Sentences and paragraphs.** Break long sentences. Keep paragraphs short and single-purpose.
9. **Ending.** Does it stop when it's done, without a recap?
10. **Sound.** Read it aloud. Does it sound like a clear-headed person talking to a friend?
