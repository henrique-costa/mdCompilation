# CLAUDE.md

## QUICK CHECKLIST

Before shipping your CLAUDE.md:

- Can I read this in 60 seconds?
- Does every line tell Claude something it cannot guess?
- Am I under 30 instructions? (20 is ideal)
- Did I include specific examples instead of vague rules?
- Would a freelancer understand my project from this?

If not, cut it.

---
## Commands
### Skip Permissions Prompt

Starts Claude Code without the permission confirmation on every tool use. Useful for uninterrupted workflows but use with caution — Claude will execute commands without asking first. Run this from your regular terminal.

```bash
claude --dangerously-skip-permissions
```

---

### Install Frontend Design Skill (Anthropic Official)

Anthropic's own skill that forces Claude to pick a bold aesthetic direction before writing any code. Prevents the generic "AI slop" look (Inter font, purple gradients, rounded cards). The official marketplace is pre-loaded — just open the plugin menu inside a Claude Code session.

```
/plugin
```

Then go to the **Discover** tab and install `frontend-design`.

---

### Install UI/UX Pro Max Skill

Adds a full design intelligence engine with 50+ styles, 95 color palettes, 56 font pairings, and stack-specific guidelines (React, Next.js, Vue, Tailwind, etc.). Claude automatically searches its local design databases before generating UI code. Run these inside a Claude Code session.

**Add the marketplace:**

```
/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
```

**Install the plugin:**

```
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
```


---

## PRO TIPS

- If you already have a project, run `/init` in Claude Code. Let it draft. Then delete aggressively.

- If starting fresh, copy a minimal template and fill it as you build.

- Fix mistakes in real time. If Claude does something wrong, say:
  "Add to CLAUDE.md that we never do X."
  Next session, it already knows.

- Use `IMPORTANT:` only for critical rules. Use sparingly.

- Put 5–10 real examples in a reference folder and tell Claude to follow them.

- Build it over weeks, not in one sitting. Add rules from real mistakes. Remove rules that never matter.

- Separate shared from personal:
  CLAUDE.md (committed)
  CLAUDE.local.md (gitignored)

---

## RULES FOR WRITING RULES

- No generic advice.
- No philosophy.
- No documentation.
- No repetition.
- Short sentences.
- Specific constraints.
- Operational instructions only.

If it looks like a README, rewrite it.
If it looks like a behavior manual, it's correct.
