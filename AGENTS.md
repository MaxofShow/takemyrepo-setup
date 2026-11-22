# For the agent installing this repo

The person asked you to install Take My Repo setup. It connects you to Take My Repo and adds a rule to your global instructions.

1. Tell them in a few short lines what is coming:
   - you will run one script that adds the `takemyrepo` MCP server to the coding agents found on this computer (Claude Code, Codex, Cursor) and the "Take My Repo first" rule to their global instructions (`~/.claude/CLAUDE.md`, `~/.codex/AGENTS.md`);
   - their browser will then open Take My Repo, once per app: they sign in if it asks and press Allow. That is normal.
2. Run it from this folder, with `--yes` since you already told them: `sh install.sh --yes`
   If they have no Take My Repo account and do not want one: `sh install.sh --yes --no-account`
3. Tell them what the script printed: what was added, what was skipped, and that the new tools appear after a restart of the agent.

Do not change anything else on their computer. To undo: `sh install.sh --yes --uninstall`.
