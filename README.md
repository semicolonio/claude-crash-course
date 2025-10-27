# Claude Crash Course Marketplace

A fun, interactive crash course for learning Claude Code basics. Perfect for semi-technical users who want to learn AI-assisted coding.

## What's Included

- **claude-crash-course** - Interactive beginner tutorial with 13 lessons teaching Claude Code fundamentals (~70 minutes)

## Installation

### Step 1: Add the Marketplace

From any directory where you want to take the course, add this marketplace:

```bash
/plugin marketplace add /Users/nasir/apps/course-claude-code
```

Or if using from a GitHub repo:
```bash
/plugin marketplace add owner/repo-name
```

### Step 2: Install the Course Plugin

```bash
/plugin install claude-crash-course
```

### Step 3: Start Learning

```bash
/claude-crash-course:lesson-1-start
```

## Course Overview (13 Lessons)

### Phase 1: Foundation (Lessons 1-3)
- Welcome, Context Management, Images

### Phase 2: Content & Data (Lessons 4-7)
- Web Fetching, Data Analysis, Interactive Apps, Media Processing

### Phase 3: Developer Workflows (Lessons 8-10)
- Codebase Exploration, Debugging, Prototypes

### Phase 4: Extensibility (Lessons 11-13)
- Custom Commands, Skills & Subagents, MCP Integrations

**Status:** 12/13 lessons complete (92%) - Lesson 10 needs content

## Repository Structure

```
claude-crash-course/
├── .claude-plugin/
│   └── marketplace.json       # Marketplace definition
├── plugins/
│   └── claude-crash-course/   # The course plugin
│       ├── .claude-plugin/
│       │   └── plugin.json
│       ├── commands/
│       │   ├── lesson-1-start.md      (13 lesson files)
│       │   ├── lesson-2-basics.md
│       │   └── ...
│       ├── CURRICULUM.md      # Detailed curriculum
│       └── README.md
└── README.md                  # This file
```

## For Course Developers

To add more lessons or create new course plugins:

1. Create a new plugin folder under `plugins/`
2. Add its structure: `.claude-plugin/plugin.json` and `commands/`
3. Register it in `.claude-plugin/marketplace.json`

## Contributing

Want to add more lessons or improve the course? PRs welcome!

## License

MIT
