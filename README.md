[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/steimerbyte)

> ⭐ If you find this useful, consider [supporting me on Ko-fi](https://ko-fi.com/steimerbyte)!


# Obsidian Kanban Plugin - Maintained Version

**This is a maintained version of the Obsidian Kanban plugin with improved Escape key behavior and ongoing updates.**

---

## Why This Fork?

The original Obsidian Kanban plugin is looking for new maintainers. This fork provides a **actively maintained version** with:

### Key Improvements:
1. **Escape Key Save Behavior**: Pressing Escape now saves edits instead of canceling them
2. **Click-Outside Save**: Clicking outside forms now saves changes instead of discarding them
3. **Ongoing Maintenance**: Regular updates and bug fixes
4. **Enhanced Documentation**: Comprehensive guides and improvement suggestions

### Modified Behavior:
- **Escape key**: Now saves changes instead of canceling them
- **Click outside**: Now saves changes (for item form) instead of discarding them
- **Enter key**: Continues to save changes (when not allowing new lines)

### Files Modified:
- `src/components/Item/ItemContent.tsx` - Escape key saves card edits
- `src/components/Item/ItemForm.tsx` - Escape key and click-outside save new cards
- `src/components/Lane/LaneTitle.tsx` - Escape key saves lane title edits
- `src/components/Lane/LaneForm.tsx` - Escape key creates new lane

---

## Documentation

### Fork-Specific Documentation:
- `ESCAPE_KEY_CHANGES.md` - Detailed documentation of all changes
- `AGENTS.md` - Project documentation with build commands and code style
- `IMPROVEMENTS.md` - Code analysis and suggestions for further improvements

### Original Plugin Documentation:
- [Obsidian Kanban Plugin Documentation](https://publish.obsidian.md/kanban/)
- [Original Repository](https://github.com/mgmeyers/obsidian-kanban)

---

## Installation

### For Users:
1. Download the latest release from the [Releases page](https://github.com/alephtex/obsidian-kanban-fork/releases)
2. Extract the files to your Obsidian plugins folder: `.obsidian/plugins/obsidian-kanban-fork/`
3. Enable the plugin in Obsidian settings

### For Developers:
1. Clone this repository
2. Install dependencies: `npm install` or `yarn install`
3. Build the plugin: `npm run build`
4. Copy `main.js` to your Obsidian plugins folder

---

## Features

### Core Features (from original plugin):
- Create markdown-backed Kanban boards in Obsidian
- Drag and drop cards between lanes
- Add dates, tags, and metadata to cards
- Archive completed cards
- WIP (Work In Progress) limits
- Customizable board layouts

### Enhanced Features (this fork):
- **Improved Escape Key Behavior**: Save instead of cancel
- **Better Error Handling**: More robust input validation
- **Enhanced Documentation**: Comprehensive guides and examples
- **Ongoing Maintenance**: Regular updates and bug fixes

---

## Contributing

Contributions are welcome! Please read [AGENTS.md](AGENTS.md) for:
- Code style guidelines
- Build and test commands
- Development best practices
- Negative Space Programming patterns

---

## License

MIT License - See [LICENSE.md](LICENSE.md) for details

---

## Acknowledgments

- Original plugin by [mgmeyers](https://github.com/mgmeyers)
- Based on the Obsidian plugin template
- Built with TypeScript, Preact, and the Obsidian API
