# claude-workflow-plugins

A Claude Code plugin marketplace distributing two workflow plugins: `discuss` and `orchestrate`.

## Add the marketplace

```
/plugin marketplace add mahito1594/claude-workflow-plugins
```

## Install a plugin

```
/plugin install discuss@claude-workflow-plugins
/plugin install orchestrate@claude-workflow-plugins
```

## Plugins

- **discuss**: Design discussion mode that blocks file edits via a lock file and a bundled `PreToolUse` hook until you end the discussion.
- **orchestrate**: Orchestrator mode that keeps planning, verification, and commits in the main session and delegates implementation to a bundled subagent.

## License

MIT. See [LICENSE](./LICENSE).
