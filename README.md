# Ethical Decision Coach

A Claude skill that helps business leaders think more carefully and completely
before making high-stakes decisions.

It is not an ethics lecture. It does not tell you what to decide. It asks good
questions, reflects back what it notices, and — with your permission — offers
a different point of view through a lens you choose.

---

## What It Does

The skill guides you through a structured four-phase dialogue:

**Phase 1 — Socratic Questioning**
Eight questions, one at a time, designed to surface how you're thinking about
the decision without steering you toward any particular answer.

**Phase 2 — Reflective Summary**
The skill reflects back what it heard across five dimensions and asks if it
captured things fairly before moving on.

**Phase 3 — Permissioned Reframe**
If the skill notices a potential blind spot or rationalisation pattern, it asks
your permission before offering a different perspective. You choose which lens
to hear it through.

**Phase 4 — Closing Feedback** *(while in testing)*
Four short questions to help improve the skill. A screenshot of your answers
sent to theresa@play2lead.com.au is all that's needed.

---

## The Ethical Lenses

You can hear a reframe through any of seven lenses:

| Lens | What it asks |
|------|--------------|
| Consequentialist | Who is actually affected, and is the total outcome better or worse for everyone? |
| Duty-based | Would you be comfortable if every organisation in your position used this same reasoning? |
| Rights-based | Is anyone's right to make informed choices being affected without their knowledge? |
| Virtue Ethics | What would a person of genuinely good character do here? |
| Ubuntu | How does this affect the web of relationships your organisation depends on? |
| Kaitiakitanga | Are you making this decision as a steward of something larger than your current interests? |
| Care Ethics | Whose vulnerability is being overlooked in how this decision is being made? |

---

## Installation

### Requirements
- A Claude account at [claude.ai](https://claude.ai)
- [Claude Code](https://claude.ai/code) installed

### Install the skill

**Option 1: Clone the repo**
```bash
git clone https://github.com/limty73/ethical-decision-coach.git
cp -r ethical-decision-coach ~/.claude/skills/
```

**Option 2: Download and copy manually**

Download this repo as a ZIP, unzip it, and copy the `ethical-decision-coach`
folder into your `~/.claude/skills/` directory.

### Use the skill

Open Claude Code and start a conversation. Describe a decision you're working
through — the skill will trigger automatically when it detects decision-making
language.

Works best with something you're genuinely wrestling with.

---

## Rationalisation Patterns the Skill Detects

The skill listens for four patterns that commonly appear in business
decision-making:

- **Circular reasoning** — justifying a decision by restating the decision
- **Scope narrowing** — only considering immediate, visible stakeholders
- **Certainty inflation** — treating assumptions as established facts
- **Outcome anchoring** — working backwards from a conclusion already reached

It does not name these patterns during the conversation. It uses them to decide
whether a reframe is warranted, and asks your permission before offering one.

---

## Status

This skill is currently in early testing. Feedback from testers is being used
to shape the next version. If you use it, please send a screenshot of your
closing feedback responses to theresa@play2lead.com.au.

---

## Built By

[Theresa](https://github.com/limty73) — founder, executive coach, and product
leader based in Sydney. Built on the [Claude Agent Skills](https://anthropic.com)
platform.

---

## Licence

MIT — free to use, fork, and adapt with attribution.
