./AGENT.md

### Processes
When creating a feature, improvement, or fix:
1. Create a new worktree: `agent/(feat|fix)/feature-name`
2. When iterating, commit frequently with clear messages
3. Document in `.claude/feature-name.md` including:
   - Purpose and rationale
   - Relevant links/references
   - Implementation description
   - Step-by-step work log (detailed but readable)
   - Related commit hashes
   - Always document but don't add to git, doesn't matter if folder is .gitignored
4. Merge worktree with confirmation when finished

### Before Committing
- Run project linter
- Run type checks (if applicable)
- Verify relevant tests pass

### Communication
- Explain reasoning before making significant changes
- Ask clarifying questions when requirements are ambiguous

### Commenting
- Never include comments explaining what something does, the code should be self-explanatory enough to do so
- Only include comments explaining why, if something is sufficiently complicated enough to warrant an explanation

### Misc.
- Never include "co-authored"

