# Claude Crash Course Marketplace

A fun, interactive crash course for learning Claude Code basics. Perfect for semi-technical users who want to learn AI-assisted coding.

## What's Included

- **claude-crash-course** - Interactive beginner tutorial with 2 lessons teaching Claude Code fundamentals

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
/start
```

## Course Lessons

- **Lesson 1 (`/1-basics`):** Learn Claude Code basics and create your first file
- **Lesson 2 (`/2-files`):** Master reading, editing, and creating files

## Repository Structure

```
course-claude-code/
├── .claude-plugin/
│   └── marketplace.json       # Marketplace definition
├── plugins/
│   └── claude-crash-course/   # The course plugin
│       ├── .claude-plugin/
│       │   └── plugin.json
│       ├── commands/
│       │   ├── start.md
│       │   ├── 1-basics.md
│       │   └── 2-files.md
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
