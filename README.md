# ⚡ Immerse

A powerful task management and focus timer plugin for [Obsidian](https://obsidian.md), heavily inspired by [Blitzit](https://www.blitzit.app/).

![Immerse Banner](https://img.shields.io/badge/Obsidian-Plugin-7c3aed?style=for-the-badge&logo=obsidian&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.1.5-blue?style=for-the-badge)

## 🎯 Overview

Task management and focus timer for Obsidian. Plan your day, track time with Pomodoro technique, and manage tasks without leaving your vault.

## ✨ Key Features

**📋 Task Management**
- Create tasks with time estimates and organize into customizable lists
- Filter by list, status, or date
- Schedule tasks with reminders (5/10/15/30/60 min before due)
- Daily note integration with automatic task logging

**⏱️ Dual Timer Modes**
- **Pomodoro**: Configurable work sessions with automatic breaks
- **Stopwatch**: Free-form time tracking with estimate alerts

**📊 Analytics & Reports**
- View productivity metrics (tasks/day, hours/day, streaks)
- Pie charts and bar graphs showing activity breakdown
- Time tracking by list category
- Insights on most productive hours, days, and months

**🎨 Polish**
- Status bar timer, celebration messages, sound alerts
- Keyboard shortcuts, dark mode support
- Overdue task detection with visual indicators
- Works on desktop and mobile

## 🚀 Installation

### From Obsidian Community Plugins (Coming Soon)
1. Open Obsidian Settings
2. Go to Community Plugins
3. Search for "Immerse"
4. Click Install, then Enable

### Manual Installation
1. Download the latest release from the [releases page](https://github.com/sayuop/immerse/releases)
2. Extract the files to your vault's `.obsidian/plugins/immerse/` folder
3. **⚠️ IMPORTANT**: When updating, do NOT replace or delete the existing `data.json` file - this contains all your tasks, settings, and progress!
4. Reload Obsidian
5. Enable the plugin in Settings → Community Plugins

> **Note**: Only copy the three plugin files (`main.js`, `manifest.json`, `styles.css`) when updating. Your `data.json` file stores all your tasks and settings and should never be replaced.

### Building from Source
```bash
# Clone the repository
git clone https://github.com/sayuop/immerse.git
cd immerse

# Install dependencies
npm install

# Build the plugin
npm run build

# Copy to your vault
cp main.js manifest.json styles.css /path/to/your/vault/.obsidian/plugins/immerse/
```

## 📖 Quick Start

1. Click ⚡ icon in ribbon or use command palette (`Ctrl/Cmd + P` → "Open Immerse Panel")
2. Add a task with "+ Add Task" (description, time estimate, list)
3. Start timer: ▶ for Pomodoro or ⏱ for stopwatch
4. Complete and enjoy the celebration!

## ⚙️ Configuration

All settings available in Settings → Immerse:
- Pomodoro durations (work: 25min, short break: 5min, long break: 15min)
- Default time estimates, sounds, celebrations
- Daily note integration (auto-log completed tasks)
- Custom lists with names, emojis, and colors

## 🤝 Contributing

Contributions welcome! Fork, create a feature branch, and open a PR.

**Dev Setup:**
```bash
git clone https://github.com/sayuop/immerse.git
cd immerse
npm install
npm run dev
```

## 📜 License

MIT License - see [LICENSE](LICENSE) file.

---

**Links:** [Repository](https://github.com/sayuop/immerse) • [Issues](https://github.com/sayuop/immerse/issues) • [Blitzit](https://www.blitzit.app/)

<p align="center">
  Made with ❤️ for the Obsidian community
  <br><br>
  <em>✨ Coded with assistance from <a href="https://claude.ai">Claude.ai</a></em>
</p>
