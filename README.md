# LogSeq Skills

[Agent Skills](https://agentskills.io/specification) for working with [LogSeq](https://logseq.com/) graphs. Provides Claude with comprehensive knowledge of LogSeq's block-based markdown, Datalog query language, template system, and whiteboard format.

## Skills

| Skill | Description |
|-------|-------------|
| [logseq-markdown](skills/logseq-markdown/SKILL.md) | Block-based markdown with properties, wikilinks, block references, embeds, tasks, and namespaces |
| [logseq-queries](skills/logseq-queries/SKILL.md) | Simple queries and advanced Datalog queries for filtering, searching, and aggregating graph data |
| [logseq-templates](skills/logseq-templates/SKILL.md) | Templates with dynamic variables for reusable block structures |
| [logseq-whiteboards](skills/logseq-whiteboards/SKILL.md) | Whiteboard .edn files with shapes, connectors, portals, and embeds on an infinite canvas |
| [logseq-cc-records](skills/logseq-cc-records/SKILL.md) | Log Claude Code conversations to today's LogSeq journal with time-stamped summaries |

## Installation

### Claude Code (via marketplace)

```
/plugin marketplace add logseq-skills
/plugin install logseq@logseq-skills
```

### Claude Code (manual)

Copy the `skills/` directory and `.claude-plugin/` to your project's `.claude/` folder, or to `~/.claude/` for global access.

## License

MIT
