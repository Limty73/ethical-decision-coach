# Ethical Decision Coach

A Claude skill that guides business leaders through high-stakes decisions by surfacing
blind spots, rationalisation patterns, and unconsidered perspectives before they commit.

It is not an ethics lecture. It is a structured thinking partner that asks good questions,
reflects back what it notices, and — with your permission — offers a different point of
view through a lens you choose.

---

## What It Does

The skill runs a three-phase dialogue:

**Phase 1 — Socratic questioning.** Eight questions, one at a time, designed so your
answers naturally reveal how you're thinking about the decision. No steering. No right
answers.

**Phase 2 — Reflective summary.** Claude reflects back what it heard: the decision,
your motivation, who you've considered, what assumptions are carrying weight. You
confirm or correct it.

**Phase 3 — Permissioned reframe.** If Claude has noticed a blind spot or rationalisation
pattern, it asks your permission before offering a different perspective. You choose which
lens to hear it through.

Available lenses include Consequentialist, Duty-based, Rights-based, Virtue Ethics,
Ubuntu, Kaitiakitanga, and Care Ethics.

---

## Who It's For

Founders, business leaders, and senior managers working through significant decisions —
product launches, strategic moves, people decisions, market entries, or technology
implementations.

It works best with a decision you're genuinely wrestling with, not a hypothetical.

---

## Installation

You'll need a Claude account and Claude Code installed.

**Option 1: Install via Claude Code (recommended)**

```bash
# Clone this repo
git clone https://github.com/limty73/ethical-decision-coach.git

# Copy the skill to your Claude skills directory
cp -r ethical-decision-coach ~/.claude/skills/
```

**Option 2: Manual install**

Download the folder and copy it to `~/.claude/skills/ethical-decision-coach/`

The folder structure should look like this:

```
~/.claude/skills/
└── ethical-decision-coach/
    ├── SKILL.md
    └── references/
        ├── ethical-lenses.md
        └── rationalisation-patterns.md
```

---

## Using the Skill

Once installed, open Claude Code and start a conversation. Describe a decision you're
working through — the skill will trigger automatically when it detects decision-making
language.

You don't need to say "use the ethical decision coach skill." Just start talking about
your decision.

---

## This Skill Is in Early Testing

If you use this skill, your feedback would be genuinely useful. At the end of the
conversation Claude will ask you four short questions. A screenshot of your answers
sent to theresa@play2lead.com.au helps shape the next version.

---

## Background

Built by [Theresa](https://www.linkedin.com/in/theresalewis/) at Play2Lead.

The skill draws on ethical frameworks from the Markkula Center for Applied Ethics
(Santa Clara University), Darden School of Business, and non-Western traditions
including Ubuntu philosophy and Māori concepts of kaitiakitanga.

---

## License

MIT — free to use, share, and adapt with attribution.
