# FinderLink: Keep your files. Link them naturally.

FinderLink is a macOS-only Obsidian plugin in development. It is designed to connect notes to files and folders already on your Mac using ordinary Markdown links, then help you locate those targets in Finder.

```markdown
[Project materials](file:///Users/yourname/Documents/project/)
[Reading list.numbers](file:///Users/yourname/Documents/Reading%20list.numbers)
```

## Planned experience

- Insert a link to one file or folder from Obsidian's ribbon, a configurable command, or the editor context menu.
- Keep the original item where it is. FinderLink does not copy files or build a directory catalog.
- Use Command-click in Obsidian's live preview to reveal a file in Finder or enter a folder.
- Track explicitly registered targets and update related links when a rename or move can be confirmed safely.
- Preserve normal Markdown links and Obsidian's native editing behavior.

## Project status

This project is in development. There is no installable plugin release yet. The features above describe the intended behavior; macOS and Obsidian integration still needs implementation and validation.

FinderLink is intended for macOS and the current user's home directory. The project will not embed a machine-specific username in its source code or public examples.
