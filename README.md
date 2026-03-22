# Ethical Decision Coach

A Claude skill that guides business leaders through high-stakes decisions by surfacing
blind spots, rationalisation patterns, and unconsidered perspectives before they commit.

It is not an ethics lecture. It is a structured thinking partner that asks good questions,
reflects back what it notices, and — with your permission — offers a different point of
view through a lens you choose.

---

## What It Does

The skill runs four phases:

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

**Phase 3b — Thinking Hats (optional, generative).** After the reflective dialogue closes,
Claude offers a separate generative session using De Bono's Five Thinking Hats. This helps
you think thoughts you haven't thought yet — not examine what you already have. You can do
it in the same sitting or come back when you have more mental space.

**Phase 4 — Feedback.** Four short multiple choice questions to help shape the next version.

---

## Who It's For

Founders, business leaders, senior managers, and product managers working through
significant decisions — product launches, strategic moves, people decisions, market
entries, or technology implementations.

It works best with a decision you're genuinely wrestling with, not a hypothetical.

---

## Installation

You'll need a Claude account. A free account works.

### Option 1: ZIP upload via Claude.ai (recommended)

1. Click the green **Code** button on this page, then **Download ZIP**
2. Do not unzip the file
3. In Claude, go to **Settings > Capabilities** and make sure **Code execution and file creation** is toggled on
4. Go to **Customize > Skills** and upload the ZIP file
5. Toggle the skill on once it appears in your list

### Option 2: Terminal install (Claude Code users)

```bash
# Clone this repo
git clone https://github.com/limty73/ethical-decision-coach.git

# Copy the skill to your Claude skills directory
cp -r ethical-decision-coach ~/.claude/skills/
```

On Windows: copy the folder to `%USERPROFILE%\.claude\skills\`

The folder structure should look like this:

```
~/.claude/skills/
└── ethical-decision-coach/
    ├── SKILL.md
    └── references/
        ├── ethical-lenses.md
        ├── rationalisation-patterns.md
        └── thinking-hats.md
```

---

## Using the Skill

Once installed, start a conversation in Claude and describe a decision you're working
through. You don't need to name the skill or ask for it specifically — it will trigger
automatically when it detects decision-making language.

---

## Feedback

This skill is in active testing. At the end of the conversation Claude will ask you four
short multiple choice questions. A screenshot of your answers sent to
theresa@play2lead.com.au helps shape the next version directly.

After this testing phase, the skill will be shared with product manager communities
globally and via LinkedIn. Your feedback at this stage carries real weight.

---

## Background

Built by [Theresa Lim](https://www.linkedin.com/in/theresalewis/) at Play2Lead.

The skill draws on ethical frameworks from the Markkula Center for Applied Ethics
(Santa Clara University), Darden School of Business, and non-Western traditions
including Ubuntu philosophy and Māori concepts of kaitiakitanga. The generative
session draws on Edward de Bono's Six Thinking Hats framework.

---

## License

MIT — free to use, share, and adapt with attribution.
