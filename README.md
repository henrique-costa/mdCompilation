# mdCompilation

# COMO FAZER UM BOM CLAUDE.md

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
claude --dangerously-skip-permissions
claude plugin add anthropic/frontend-design
claude plugin add nextlevelbuilder/ui-ux-pro-max-skill

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
