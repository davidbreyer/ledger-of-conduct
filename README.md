# The Ledger of Conduct

A Markdown-based journaling system for disciplined reflection, accountability, and deliberate living.

## Philosophy

The Ledger of Conduct is built on the principle that **examined living leads to intentional living**. In a world of constant distraction and reactive behavior, this system provides a structured framework for:

- **Daily reflection** that transforms experience into wisdom
- **Consistent accountability** to yourself and your commitments
- **Pattern recognition** that reveals what's truly working (and what isn't)
- **Strategic planning** grounded in honest self-assessment

This is not a diary for recording events. It's a **ledger**—an accounting system for your time, energy, and integrity. Like a financial ledger tracks money, this tracks something far more valuable: how you're spending your life.

### Core Beliefs

1. **Writing clarifies thinking.** Until you write it down, you haven't really thought it through.
2. **What gets measured gets managed.** Tracking commitments reveals your true priorities.
3. **Honesty is non-negotiable.** Self-deception is the enemy of growth.
4. **Consistency compounds.** Small, regular reflections create dramatic long-term insight.
5. **You are what you repeatedly do.** Excellence is not an act, but a habit.

## How It Works

The Ledger of Conduct uses three levels of reflection:

### 📅 Daily Entries (10-15 minutes)
End each day by recording:
- What you actually did (not what you planned)
- What you observed and learned
- What worked and what didn't
- What you commit to tomorrow

### 📊 Weekly Reviews (30 minutes)
Every week, step back to see:
- Patterns across the week
- Progress on commitments
- Energy sources and drains
- Strategic adjustments for next week

### 🎯 Monthly Assessments (60 minutes)
Each month, conduct a comprehensive review:
- Goal progress and achievement
- Habit tracking and evaluation
- Long-term pattern recognition
- Strategic planning for the month ahead

## Getting Started

### 1. Read the Constitution
Start with [`constitution/journal_constitution.md`](constitution/journal_constitution.md) to understand the principles and practices.

### 2. Set Up Your Environment
This system is designed for **VS Code + GitHub Copilot**:
- The `.vscode` folder contains optimized settings for distraction-free writing
- Copilot can help you reflect more deeply using the custom prompts
- Markdown provides flexibility and future-proof portability

### 3. Use the Templates
Find templates in [`journal/templates/ledger_of_conduct_template.md`](journal/templates/ledger_of_conduct_template.md):
- Daily entry template
- Weekly review template
- Monthly assessment template
- Quarterly review template

**Quick Insert with IntelliSense**: In VS Code, type `/loc.daily`, `/loc.weekly`, `/loc.monthly`, or `/loc.quarterly` and the autocomplete menu will show template snippets you can insert instantly.

### 4. Start Writing
Open [`journal/2025-H2.md`](journal/2025-H2.md) and write today's entry. Don't overthink it—just start.

## Directory Structure

```
ledger-of-conduct/
├── constitution/
│   └── journal_constitution.md      # Governing principles and practices
├── journal/
│   ├── 2025-H2.md                   # Current journal (Jul-Dec 2025)
│   └── templates/
│       └── ledger_of_conduct_template.md  # Entry templates
├── .vscode/
│   ├── settings.json                # Optimized for Markdown + Copilot
│   ├── markdown.code-snippets       # IntelliSense snippets (/loc.daily, /loc.weekly, etc.)
│   └── prompts/
│       ├── daily-prompt.md          # Daily reflection prompts
│       ├── weekly-prompt.md         # Weekly review prompts
│       └── monthly-prompt.md        # Monthly assessment prompts
└── README.md                        # This file
```

## Using GitHub Copilot

This system is designed to work with GitHub Copilot as your reflection partner:

### Daily Reflections
1. Open `.vscode/prompts/daily-prompt.md`
2. Start Copilot Chat and reference this prompt
3. Let Copilot guide you through reflection questions
4. Write your entry in `journal/2025-H2.md`

### Weekly Reviews
1. Use `.vscode/prompts/weekly-prompt.md` with Copilot
2. Review your daily entries from the past week
3. Let Copilot help identify patterns and insights

### Monthly Assessments
1. Use `.vscode/prompts/monthly-prompt.md` with Copilot
2. Review weekly summaries and significant events
3. Get help creating strategic plans and setting goals

## Best Practices

### Do
- ✅ Write honestly, even when it's uncomfortable
- ✅ Be specific with examples and details
- ✅ Review past entries regularly
- ✅ Track commitments and follow through
- ✅ Adjust the system to fit your needs
- ✅ Miss a day if needed, but always resume

### Don't
- ❌ Write what you think you "should" write
- ❌ Use this as a venting mechanism only
- ❌ Skip reflection for action items
- ❌ Make commitments you won't keep
- ❌ Compare your practice to others
- ❌ Let perfection prevent consistency

## Organization Tips

### Tagging
Use hashtags to categorize entries:
- `#work` `#health` `#relationships` `#learning`
- `#win` `#challenge` `#insight` `#decision`

This makes it easy to search and find patterns later.

### File Organization
Create a new file for each half-year:
- `2025-H1.md` (January - June)
- `2025-H2.md` (July - December)
- `2026-H1.md` and so on...

This keeps files manageable while maintaining continuity.

### Archiving
At year's end, create an annual summary:
- Key achievements and learnings
- Major patterns observed
- Strategic direction for next year

## Why Markdown?

- **Plain text**: Future-proof, searchable, portable
- **Version control**: Track changes over time with Git
- **Flexible**: Easy to format, link, and organize
- **Tool-agnostic**: Works with any text editor
- **Private**: Your data, under your control

## Privacy & Security

This is **your personal journal**:
- Keep it private (add journal files to `.gitignore` if needed)
- Don't share sensitive information about others
- Consider encrypting if storing sensitive data
- Use a private GitHub repo if version controlling

## Frequently Asked Questions

**Q: What if I miss a day (or week)?**  
A: Don't stress. Acknowledge it in your next entry and resume. Consistency is the goal, but life happens.

**Q: How long should entries be?**  
A: Quality over quantity. A honest 5-minute entry beats a rambling 30-minute one.

**Q: Should I write in the morning or evening?**  
A: Evening works best for most—reflecting on the day just completed. Experiment to find what works for you.

**Q: What if I don't have anything to write about?**  
A: You always have something. Use the prompts to get started. Even "boring" days teach you something.

**Q: Can I customize the templates?**  
A: Absolutely! This system works best when adapted to your needs.

## Inspiration

> "Journal writing is a voyage to the interior." — Christina Baldwin

> "We write to taste life twice, in the moment and in retrospect." — Anaïs Nin

> "The unexamined life is not worth living." — Socrates

## License

This system is free to use and adapt for personal use. Share it, modify it, make it your own.

---

**Now start writing. Today's entry won't write itself.**
