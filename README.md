# pb-cc-plugins

A Claude Code plugin marketplace distributing two workflow plugins: `discuss` and `orchestrate`.

## Add the marketplace

```
/plugin marketplace add mahito1594/pb-cc-plugins
```

## Install a plugin

```
/plugin install discuss@pb-cc-plugins
/plugin install orchestrate@pb-cc-plugins
```

## Plugins

- **discuss**: Design discussion mode that blocks file edits via a lock file and a bundled `PreToolUse` hook until you end the discussion.
- **orchestrate**: Orchestrator mode that keeps planning, verification, and commits in the main session and delegates implementation to a bundled subagent.

## License

MIT. See [LICENSE](./LICENSE).
