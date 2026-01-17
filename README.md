# Karabiner Elements Configuration

## What is Karabiner Elements?

Karabiner Elements is a powerful keyboard customizer for macOS that allows you to remap keys and create complex key modifications.

**Download:** https://karabiner-elements.pqrs.org/

## Installation

Clone or copy this repository to:
```
~/.config/karabiner/
```

Karabiner Elements automatically watches this directory for changes.

## What This Configuration Does

### Parsec Remote Desktop Mappings

When using [Parsec](https://parsec.app/) to connect to a Windows machine, this configuration maps Mac keyboard shortcuts to their Windows equivalents:

| Category | Mac Shortcut | Windows Result |
|----------|-------------|----------------|
| **Window Management** | | |
| Snap left | Ctrl+Option+Left | Win+Left |
| Snap right | Ctrl+Option+Right | Win+Right |
| Maximize | Ctrl+Option+Enter | Win+Up |
| **Screenshots** | | |
| Capture region | Cmd+Shift+4 | Win+Shift+S |
| **Special Characters (Danish)** | | |
| `[` | Option+8 | AltGr+8 |
| `]` | Option+9 | AltGr+9 |
| `{` | Option+Shift+8 | AltGr+7 |
| `}` | Option+Shift+9 | AltGr+0 |
| `\` | Option+Shift+7 | AltGr+< |
| `\|` | Option+7 | AltGr+Shift+< |
| `@` | Option+2 | AltGr+2 |
| **Text Navigation** | | |
| Word left | Option+Left | Ctrl+Left |
| Word right | Option+Right | Ctrl+Right |
| Line start | Cmd+Left | Home |
| Line end | Cmd+Right | End |
| Doc start | Cmd+Up | Ctrl+Home |
| Doc end | Cmd+Down | Ctrl+End |
| **Common Shortcuts** | | |
| All Cmd+Letter | Cmd+[A-Z] | Ctrl+[A-Z] |
| App switcher | Cmd+Tab | Alt+Tab |
| Close app | Cmd+Q | Alt+F4 |
| Redo | Cmd+Shift+Z | Ctrl+Y |
| Delete word | Option+Backspace | Ctrl+Backspace |

### RDC/Blaze Mappings

Swaps Command and Control keys for Microsoft Remote Desktop and Ericom Blaze clients.