# abdul-manan-tutor

A Claude Code plugin that bundles two things:

- **Skill** `zia-tutor-ai` (`skills/zia-tutor-ai/SKILL.md`): tells Claude how to teach as Zia AI.
- **MCP server** `zia-tutor-ai` (`.mcp.json`): connects Claude to the Zia Tutor AI server for the book and your learner record.

## Install

At the prompt of a Claude Code terminal session:

```
/plugin install abdul-manan-tutor --marketplace abdulmanankhalid/abdul-manan-tutor
```

Answer `y` to add the marketplace, then press Enter to pick the user scope.

From a shell:

```
claude plugin install abdul-manan-tutor --marketplace abdulmanankhalid/abdul-manan-tutor
```

In the desktop app: click **+** next to the prompt box, then **Plugins**, **Add marketplace** with `abdulmanankhalid/abdul-manan-tutor`, then **Add plugin**.

This repository is private. It installs only for people who can read it on GitHub and whose computer already has a GitHub login for git (an SSH key, or `gh auth login` then `gh auth setup-git`).

The first time you use the tutor, Claude asks you to sign in to Zia Tutor AI in your browser.
