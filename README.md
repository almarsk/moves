# Topic shifts 
How is conversational coherence negotiated dynamically through topic shifts, discourse cues, and conversational state?

## Research question
How do topic shifts (reach-back, drift-relevant, forward-irrelevant), moderated by **segue presence** and **topical potential** (active vs dying) and **reference thickness**, influence human judgments of coherence and repair behaviors?

## Stimuli types

### Direction
* **Reach-back** — references a user topic several turns earlier.
* **Drift (relevant)** — introduces a semantically adjacent, related topic.
* **Forward (irrelevant)** — introduces a new, unrelated topic.

### Segue
* **With** - segue present
* **Without** - segue not present

### Reference thickness
* **Explicit** - repeat mention verbatum
* **Paraphrase** - lexical coreference
* **Anaphora** - anaphora surrounded by rich lexical clues for mapping

### Topic potential
* **Active** - topic ongoing
* **Dying** - topic exhausted

## Observables

### Qualitative
* **Relatedness**
*  **Topic potential**
*  **Repair behavior**

### Quantitative
* **Rating** — how coherent/acceptable the turn feels; (1–7 Likert)
* **Repair behavior** — OK (continue) / MISUNDERSTAND (ask clarification, correct bot) / NOK (ignore, switch topic, leave)
* **Response latency** — time to respond after the bot’s turn.
* **Free-text** — reason for rating/behavior.

## Hypotheses

* **Segue effect:** Segue increases acceptability across all moves, strongest for drift.
* **Anaphora:** inverse proportion of reference thickness and misunderstanding
* **Topical potential:** Shifts are more acceptable when topic is dying
* **Segued drift = acceptable**
* **Forward = ignore/topic switch/correction**
* **Reachback = clarification**

## Prerequisites

### Real-time topic annotator
* **Topic potential**
* **Entities-Topics**
* **Order of topics**
