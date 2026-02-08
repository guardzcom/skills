# Guardz Skills

> **Early development.** Skills may change significantly between versions. Feedback welcome via [issues](https://github.com/guardzcom/skills/issues).

Open-source agent skills for [Claude Code](https://claude.com/product/claude-code), built by [Guardz](https://guardz.com).

## Available Skills

### Session Checkpoint

Named save points for coding sessions — preserve progress across sessions.

```bash
npx skills add guardzcom/skills --skill session-checkpoint
```

- **Memory-native** — checkpoints persist in Claude's auto-memory directory, indexed in MEMORY.md
- **Named and parallel** — multiple checkpoints coexist without conflict
- **Structured state** — tracks accomplishments, failed approaches, modified files, branch, and plan progress
- **Zero dependencies** — single Markdown file, no runtime requirements

**Usage:**

```
save checkpoint my-feature   # save current progress
continue my-feature          # resume in a new session
clear checkpoint my-feature  # remove when done
```

## Contributing

Issues and pull requests are welcome.

## License

[MIT](LICENSE)
