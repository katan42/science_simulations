# 📚 Interactive Science Simulations

Small, self-contained browser activities for science. Each one is a single HTML file — no build step, no dependencies, no login. Built for my own classroom and left public so other teachers and students can use them.

**▶️ Live: [katan42.github.io/science_simulations](https://katan42.github.io/science_simulations/)**

---

## Activities at a glance

| Activity | Subject | Format | Focus |
| :-- | :-- | :-- | :-- |
| [**Reactivity Rumble**](https://katan42.github.io/science_simulations/ReactivityRumble-2.html) | Chemistry | Equation selection + vocabulary match | Metal reactivity series |
| [**Biology Revision**](https://katan42.github.io/science_simulations/bio_revision_bench.html) | Biology | Open-ended recall | Whole-syllabus recall |
| [**Chemical Formula Challenge**](https://katan42.github.io/science_simulations/chemistry-formula-game-3.html) | Chemistry | Timed formula writing | Ionic formulae |
| [**IonQuest**](https://katan42.github.io/science_simulations/chemistry-ion-quest.html) | Chemistry | Grid puzzle | Ionic formulae |

---

## ⚗️ Reactivity Rumble

Reactions of metals with water, steam and dilute acid, plus displacement — worked through the balanced equation rather than a description.

**Students should be able to:**

- Place the common metals in reactivity order (K, Na, Ca, Mg, Al, Zn, Fe, Pb, Cu, Ag, Au) and use that order to predict behaviour.
- Decide whether a given metal reacts with cold water, with steam, or with dilute acid — and whether it reacts at all.
- Select the correctly balanced equation for a reaction, with the right formulae and state symbols.
- Describe how vigorous a reaction is using syllabus vocabulary — *explosively*, *violently*, *readily*, *slowly*, *no reaction*.
- Apply the displacement rule: a more reactive metal displaces a less reactive one from its compound.

**How to play:**

1. A card names a metal and what it meets — cold water, steam, dilute hydrochloric acid, or the solution/oxide of another metal.
2. Choose the balanced equation that matches from the options given. State symbols count.
3. Match the observation to the correct vigour term in the vocabulary round.
4. You start with three hearts; a wrong answer costs one and triggers feedback explaining what the correct equation should have been. Consecutive correct answers build a streak multiplier.
5. Clear the round by reaching the target score before the hearts run out.

---

## 🔬 Biology Revision — Field Notebook

Broad multiple-choice sweep across the syllabus. Best used early in revision, to find the weak topics before drilling them.

**Students should be able to:**

- Recognise correct definitions, structures and processes across all examinable topics.
- Spot the common distractors — the near-miss answers that come up in exam options.
- Identify which topics need more work, using the per-topic progress display.

**How to play:**

1. Pick a topic, or work through all of them in order.
2. Answer each question by selecting one option; feedback is immediate, with a short explanation of why the correct answer is correct.
3. The progress bar fills as you go and shows your score per topic, so gaps are visible at a glance.
4. Retake any topic as many times as you like — question order changes each run.

## 🔬 Biology Revision — Specimen Bench

The recall counterpart to the Field Notebook. Nothing to choose from — students have to produce the answer themselves, which is much closer to what the paper actually asks.

**Students should be able to:**

- Recall and write key biological terms, definitions and processes without prompts.
- Use precise terminology rather than everyday paraphrase.
- Structure a short written answer that contains the marking points.

**How to play:**

1. Choose a topic from the syllabus list.
2. Read the question and type your answer in your own words.
3. The checker looks for the key terms a marker would expect, then shows the model answer alongside yours so you can see what was missing.
4. Questions you get wrong come back around before the topic is finished.

---

## 🧪 Chemical Formula Challenge

Writing the formula of an ionic compound from its name or from a pair of ions. Timed, with hints and a streak system.

**Students should be able to:**

- Recall the symbols and charges of common cations and anions, including polyatomic ions.
- Balance charges to work out the correct ion ratio in a compound.
- Apply the bracket rule correctly — brackets go around a polyatomic ion only when its subscript is greater than 1, never around a single-element ion.
- Distinguish a subscript from a coefficient: potassium sulfate is K₂SO₄, not 2KSO₄.

**How to play:**

1. Pick a difficulty. The easier level sticks to simple ions; the harder level brings in polyatomic ions and transition metals with variable charge.
2. A compound name or an ion pair appears. Build or type its formula before the countdown runs out.
3. Use a hint if you're stuck — it narrows things down without handing over the answer.
4. Correct answers extend your streak; wrong ones show the working and are put back in the queue to come up again later.

## 🧩 IonQuest

The same chemistry as the Formula Challenge, approached as a spatial puzzle instead of a writing task.

**Students should be able to:**

- Recognise ions from their symbols and charges at speed.
- Work out which combination of ions gives a named compound with charges balanced overall.
- Reason about ratio — knowing that two of one ion may be needed to cancel the charge of another.

**How to play:**

1. A target compound is named above a grid of ion tiles.
2. Select adjacent tiles that combine to make that compound with the charges balanced. The selection has to be a connected path — the ions you need aren't always next to each other.
3. Hints highlight part of the path if you're stuck.
4. Successful captures clear the tiles, the grid refills, and your streak carries over into the next target.

---

## Running locally

Clone and open `index.html` in a browser. That's it — everything is inline.

```bash
git clone https://github.com/katan42/science_simulations.git
cd science_simulations
open index.html      # macOS  (Linux: xdg-open index.html)
```

## Adding a new activity

1. Drop the single-file `.html` into the repository root.
2. Add a `<a class="card">` block to `index.html` pointing at it.
3. Add a row to the table above, and a section describing the learning outcomes and how to play.

`.nojekyll` is present so GitHub Pages serves these files exactly as written, without running them through Jekyll.

---

