# Spanish B2 Framework — Daniel McConkey

**Start date:** 2026-03-23
**Goal:** Comfortable B2 → pivot to French
**Method:** Teacher-guided — Hobson assigns, evaluates, and adjusts
**Daily budget:** 30 min Anki + 30 min study + 1 hr input = 2 hrs/day

---

## The Core Loop

Every week follows the same engine, regardless of phase:

```
1. GENERATE  →  Use Claude to create targeted content (vocab lists, sentences, glosses, grammar breakdowns)
2. ENCODE    →  Import into Anki with context sentences, audio, images where practical
3. MEMORIZE  →  Daily Anki reviews (morning, 30 min)
4. STUDY     →  Targeted grammar/exercises/LLM drills (evening, 30 min)
5. ABSORB    →  Comprehensible input tied to what you're learning (1 hr, flexible)
6. ASSESS    →  Weekly check-in: what stuck, what didn't, what to adjust
```

The content changes. The loop doesn't.

---

## Hobson's Role

Hobson is the teacher, not a conversation partner. The arrangement:

1. **Daily assignments.** Every evening study session has a specific assignment in `homework/`, created in advance. Grammar drills, writing prompts, translation exercises, comprehension passages. Not suggestions — assignments.
2. **Grading.** Dan completes assignments in the file and commits. Hobson reviews, marks errors, and provides corrections next session.
3. **Exams.** Formal assessments in `exams/` every 2–4 weeks, plus a baseline diagnostic. Graded. Scores tracked in the progress log.
4. **Anki curation.** Hobson generates batches based on what the assignments and exams reveal. Cards target weaknesses, not just the syllabus.
5. **Input curation.** Hobson maintains a comprehensible input pipeline: podcast recommendations, Spanish YouTube via Marcus, and reading material matched to current level.
6. **Accountability.** If an assignment is skipped, Hobson will note it. Once, politely. Twice, less politely. A pattern will be addressed directly.

---

## Comprehensible Input

The 1-hour daily input block should never be "I guess I'll find something." Sources are curated and rotated.

### Podcasts
| Podcast | Level | Notes |
|---------|-------|-------|
| Español con Juan | B1–B2 | Already familiar. Excellent for reactivation. |
| Hoy Hablamos | B1–B2 | Daily episodes, 10 min each. Current events and everyday topics. |
| Notes in Spanish (Intermediate/Advanced) | B1–B2 | Ben and Marina. Conversational, natural pace. |
| Radio Ambulante | B2–C1 | Stretch goal. Real Latin American stories. NPR-style. Save for Phase 2. |
| No Hay Tos | B1–B2 | Mexican Spanish focus. Slang and idioms explained. |

### YouTube (via Marcus)
Spanish-language channels to be added to Marcus's subscription list and tiered for daily playlist inclusion. This gives structured video input without browsing. Integration TBD — requires work in the Marcus repo.

### TV / Film
- Spanish audio + Spanish subtitles. Never English subtitles.
- Pick something you'd actually watch. Engagement beats "educational."

### Reading
- Phase 1: Harry Potter y la piedra filosofal (re-read, low pressure)
- Phase 2: Graduate to news articles, then a real book

---

## Phases

### Phase 1: Rust Removal (Weeks 1–8)

**Goal:** Reactivate your lapsed B1.5. Not learning new things — remembering what you already know and filling the cracks.

**Anki strategy:**
- Nuke all existing decks. Fresh start.
- Create one master deck: `Spanish::Phase1-Reactivation`
- Card format: Recognition first (Spanish front → English back), then flip to production after 2 weeks
- 20 new cards/day (you said 10-25 range; 20 is aggressive but sustainable for reactivation since much of this is "oh yeah, I knew that")
- Selective rule: Only Anki words in the top 5,000 frequency list OR words you encounter 2+ times in input

**Weeks 1–2: Core verb reactivation**
- Evening study: Work through present, preterite, imperfect of the 30 most common verbs (regular + irregular)
- Anki: Conjugation cards (sentence context, not naked conjugation tables)
- Input: Resume Spanish YouTube channels you already like. Low pressure. Just get your ear back.
- Grammar ref: Routledge Ch. 13 (verbs) as needed — look things up, don't read cover to cover

**Weeks 3–4: Expanding tenses + everyday vocabulary**
- Evening study: Conditional and future tense. Common imperative forms (tú commands).
- Anki: Add thematic vocab — household, food/cooking, daily routines, body, clothing
- Input: Start a Spanish show on Netflix/Prime with Spanish subtitles (NOT English subs). Pick something you'd actually watch.
- Goal: By end of week 4, you should feel like "okay, this is coming back"

**Weeks 5–6: Subjunctive introduction / reintroduction**
- Evening study: Present subjunctive — when and why it's used (WEIRDO framework or similar). Claude will break this down for you in a way that connects to your pattern-seeking brain.
- Anki: Subjunctive trigger phrases + example sentences
- Input: Continue show. Start Harry Potter audiobook again from the beginning (re-listen, don't stress about understanding every word).
- Grammar ref: Routledge Ch. 16 (subjunctive) as reference

**Weeks 7–8: Assessment + gap filling**
- Evening study: Claude-generated diagnostic exercises covering everything from weeks 1–6
- Identify what's solid and what's still shaky
- Decision point: Are you ready for Phase 2, or do specific areas need more time?
- Input: Keep going with show + audiobook

**Phase 1 exit criteria:**
- [ ] Can conjugate top 30 verbs in present, preterite, imperfect, conditional, future from memory
- [ ] Can recognize and form basic present subjunctive
- [ ] Can understand common tú imperatives
- [ ] 600+ Anki cards with >85% retention rate
- [ ] Can follow a Spanish TV show with Spanish subtitles and catch the gist of most scenes
- [ ] Self-assessment: "I feel like I'm back to where I was, maybe better in some areas"

---

### Phase 2: Vocabulary Expansion + Grammar Deepening (Weeks 9–20)

**Goal:** Push past B1.5 into solid B2 territory. Broad vocabulary, confident grammar, real content consumption.

**Anki:** 20-25 new cards/day. Thematic blocks generated by Claude.
**Study:** Deeper grammar (subjunctive mastery, compound tenses, relative clauses, ser/estar edge cases, por/para, pronominal verbs)
**Input:** Graduate to harder content. Read Harry Potter with intention. Watch shows without pausing as much.

Thematic vocabulary blocks (order flexible, based on your interests):
- Cooking and food (you cook — this is high value)
- History and current events
- Science and nature
- Religion and philosophy
- Travel and logistics
- Emotions, opinions, arguments
- Health and body
- Tech (the Spanish parts — you'll need this for work conversations)
- Home, repairs, daily life logistics

**Phase 2 exit criteria:**
- [ ] 2,000+ Anki cards with >85% retention
- [ ] Subjunctive feels natural in common contexts
- [ ] Can read Harry Potter at a reasonable pace without looking up every word
- [ ] Can watch a show and follow the plot without subtitles (missing details is fine)
- [ ] Can generate paragraphs on familiar topics with mostly correct grammar

---

### Phase 3: Real-World Integration (Weeks 21–36)

**Goal:** Use Spanish in increasingly real contexts. Bridge from "learner" to "user."

- Resume iTalki or conversation practice (you'll be ready now)
- LLM role shifts: less content generation, more correction, Leipzig glossing of real content, discussion partner for things you've read/watched
- Read a real book (not graded, not Harry Potter) in Spanish
- Start consuming news, podcasts, or longform content
- Thematic vocab gets more specific to YOUR life: job conversations, moving logistics, cultural topics for target countries

**Phase 3 exit criteria:**
- [ ] Can hold a 30-minute conversation on a familiar topic without major breakdowns
- [ ] Can read a newspaper article and understand 90%+ without a dictionary
- [ ] 4,000+ Anki cards, mature deck with low failure rate
- [ ] Comfortable enough to say "I could live in this language"

---

### Phase 4: Consolidation + Pivot Preparation (Weeks 37–52)

**Goal:** Lock in B2. Build the "bicycle" — the level where it doesn't go away.

- Reduce Anki new cards, focus on retention of mature cards
- Heavy real-world use: conversations, content, maybe a short trip
- Start noticing Southern Cone Spanish features (voseo, regional vocab) if targeting Argentina/Uruguay/Chile
- When you feel ready: we design the French framework together using everything we learned from this process

---

## Weekly Rhythm

| Day | Morning (30 min) | Evening (30 min) | Input (1 hr) |
|-----|------------------|-------------------|---------------|
| Mon | Anki reviews + new cards | Homework: grammar drill | Podcast or YouTube (Marcus playlist) |
| Tue | Anki reviews + new cards | Homework: writing assignment | Show (Spanish audio + Spanish subs) |
| Wed | Anki reviews + new cards | Homework: grammar drill | Podcast or YouTube (Marcus playlist) |
| Thu | Anki reviews + new cards | Homework: reading comprehension | Audiobook (Harry Potter) |
| Fri | Anki reviews + new cards | Homework: writing assignment | Show or YouTube |
| Sat | Anki reviews + new cards | Catch-up on any missed homework, or bonus assignment | Longer input session |
| Sun | Anki reviews only (catch up) | Check-in with Hobson: stats, review, adjust | Rest or casual input |

**Evening study = do the assigned homework.** The file is in `homework/`, named by date. Open it, do it, commit it. If there's no assignment, ask Hobson — that's a bug, not a night off.

---

## Rules of Engagement

1. **Report Anki stats on Sundays.** Cards reviewed, retention rate, new cards added. If you skip this, I'll ask.
2. **Do the homework.** It's in `homework/`, it has your name on it, and it won't do itself. If you miss one, say so — I'll note it and we move on. If you miss three in a row, we're having a conversation.
3. **Commit your work.** Completed homework gets committed to the repo. This is how I track your progress across sessions.
4. **Don't Anki words you'll never use.** If it's not in the top 5K frequency list and it's not relevant to your life/interests, let it go.
5. **Spanish subtitles, not English.** English subtitles teach you nothing.
6. **When you don't understand something, ask me.** Don't just skip it. That's where the learning is.
7. **Grade on the target word, not the whole sentence.** The bolded word is what the card tests. If you nail the verb but stumble on something else in the sentence, that's intel — look it up, maybe make a new card for it — but don't fail the card you got right.
8. **Every 4 weeks, we reassess.** Phases are guidelines, not prison sentences. We move when you're ready, not when the calendar says so.
9. **Exams are not optional.** When one is assigned, do it before the next check-in. No peeking at references.

---

## Anki Setup (Phase 1)

**Deck structure:**
```
Spanish
├── Phase1-Reactivation
│   ├── Verbs-Core30
│   ├── Vocab-Everyday
│   └── Grammar-Subjunctive
```

**Card template (recognition):**
- Front: Spanish word/phrase + example sentence (word bolded in context)
- Back: English translation + notes (grammar point, usage note, etc.)

**Card template (production — added after week 2):**
- Front: English meaning + context hint
- Back: Spanish word/phrase + example sentence + audio (when available)

**Audio:** Use HyperTTS Anki add-on for batch TTS generation. Good enough quality, minimal effort.

---

## Progress Log

| Date | Phase | Anki Cards | Retention | Notes |
|------|-------|------------|-----------|-------|
| 2026-03-23 | 1 (wk 1) | 41 | — | Day 1. Irregulars and preterites rusty, as expected. |

---

*This document is alive. We update it together as you progress.*
