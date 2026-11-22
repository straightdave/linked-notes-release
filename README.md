# Linked Notes

A fast, local-first, cross-platform spatial infinite canvas and distraction-free tabbed editor for taking atomic notes, linking ideas visually, and deriving smaller notes while learning.

## Download

Get the latest desktop installer from the **[Releases page](https://github.com/straightdave/linked-notes-release/releases/latest)**:

| Platform | Installer |
| :--- | :--- |
| **macOS (Apple Silicon — M1/M2/M3/M4)** | `Linked Notes_*_aarch64.dmg` |
| **macOS (Intel)** | `Linked Notes_*_x64.dmg` |
| **Windows (64-bit)** | `Linked Notes_*_x64-setup.exe` or `.msi` |
| **Linux (64-bit)** | `.AppImage` or `.deb` |

> **macOS first-launch note:** Because the app is not yet notarized with an Apple Developer certificate, macOS may warn that the app is from an unidentified developer. After dragging **Linked Notes.app** to Applications, run:
> ```bash
> xattr -cr "/Applications/Linked Notes.app"
> ```
> and then open it normally.

## Highlights

- **Infinite Spatial Canvas** — Pan, zoom, drag, resize, and organize atomic notes freely with a live minimap and fit-to-view.
- **Sublime-Style Focus Editor (`Cmd/Ctrl + E`)** — Multi-tab Markdown editor with Write / Split / Preview modes, syntax highlighting, and live word/line/link counts.
- **Derive Smaller Notes** — Highlight any text to spawn a linked child card with automatic lineage tracking and quote context.
- **Visual Connections & Wiki-Links** — Connect cards with labeled directional arrows and jump between notes with `[[Note Title]]`.
- **Lock / Unlock Notes** — Protect finished or reference notes from accidental edits, moves, or deletion.
- **Local-First & Portable** — Notes are saved automatically on local disk as plain Markdown files (`notes/<id>.md`) with one-click Markdown and JSON backup/import.
- **Themes & Languages** — 5 themes (Midnight, Daylight, Warm Paper, Nord, Forest), custom UI & Editor fonts, and English / 简体中文 / 日本語 support.

## Keyboard Shortcuts

- `Cmd/Ctrl + N` (or `N` on Canvas) — New note
- `Cmd/Ctrl + E` — Toggle Canvas / Focus Editor
- `Cmd/Ctrl + K` — Quick Search / Command Palette
- `Cmd/Ctrl + ,` — Preferences
- `Cmd/Ctrl + 1..9` — Switch tabs in Focus Editor
- `Cmd/Ctrl + W` — Close active tab
- `Cmd/Ctrl + Z` / `Cmd/Ctrl + Shift + Z` — Undo / Redo
- `L` — Lock / Unlock selected note(s) on Canvas
- `F` — Fit all notes in view
- `Delete` / `Backspace` — Delete selected note(s) or connection

## Feedback & Bug Reports

Please open an issue in the **[Issues tab](https://github.com/straightdave/linked-notes-release/issues)**.
