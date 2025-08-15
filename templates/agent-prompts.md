Agent-ready prompts:
- For each actionable issue in the diff, output two blocks:
  1) A GitHub Suggestion diff patch for direct apply.
  2) An agent prompt with exact file paths and patches. Prefer a general format; if the repo indicates Cursor/Claude Code/Cline, add their specific format hints.
- No commentary outside these blocks.

