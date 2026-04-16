<div align="center">

# Nongine

### The No-Code Visual Novel Engine

Build branching narratives visually, design every pixel, and publish with one click.

[Website](https://nongine.app) | [Editor](https://app.nongine.app) | [Documentation](https://docs.nongine.app) | [Download Desktop](https://nongine.app/download) | [Changelog](https://nongine.app/changelog)

</div>

---

## What is Nongine?

Nongine is a free, browser-based visual novel editor. No coding required. Create branching stories with a visual node graph, write dialogue in a writer-friendly editor, design your UI with a freeform canvas, preview in real-time, and export a playable game — all from your browser.

**Who it's for:** Writers, narrative designers, indie VN teams, and anyone who wants to make a visual novel without learning Ren'Py syntax or fighting game engines.

## Key Features

**Story Graph** — 21 node types for building branching narratives. Scenes, choices, conditions, variables, subgraphs, cutscene timelines, random branches, and more. Visual path analysis catches dead ends and unreachable nodes.

**Write Mode** — Write dialogue and narration with slash commands (`/dialog`, `/sfx`, `/bgm`, `/parallel`). Rich text with VN tags (`{shake}`, `{pause:500}`, `{speed:80}`). Copy/paste blocks, multi-select, keyboard shortcuts.

**Design Mode** — Customize textbox, choice buttons, name badge, character positions, and decorations on a freeform canvas. Bubble textbox with tail, image-based UI elements, per-character style overrides. Title screen and save/load screen designers.

**Runtime Player** — Full-featured VN player with save/load (complete scene restoration), auto/skip modes, backlog, keyboard controls, scene transitions, character Z-ordering, and achievement popups.

**Export** — ZIP export with standalone player bundle (100% feature parity). Works offline from `file://`. Save as `.nvl` project file for backup and sharing.

**Desktop App** — Native macOS and Windows app built with Tauri. Work offline, save locally, native menus. Under 15 MB.

## How It Compares

| Feature | Nongine | Ren'Py | Twine |
|---------|---------|--------|-------|
| Free to use | Yes | Yes | Yes |
| No coding required | Yes | No | Yes |
| Visual story graph | Yes | No | Partial |
| Visual design editor | Yes | No | No |
| Character animations | Yes | Yes | No |
| Cutscene timeline | Yes | No | No |
| Path analysis | Yes | No | No |
| One-click web publish | Yes | No | No |
| Script export (5 formats) | Yes | No | No |
| Browser-based editor | Yes | No | Yes |
| Desktop app | Yes | Yes | No |

## Getting Started

1. Open [app.nongine.app](https://app.nongine.app) in your browser
2. Create a free account
3. Click **New Project**
4. Build your story in the **Graph** tab
5. Write dialogue in the **Write** tab
6. Customize the look in the **Design** tab
7. Press **Play** to test
8. Click **Publish** to share or **Export** to download

No installation needed. Works in Chrome, Firefox, Edge, and Safari.

## Desktop App

Download the native app for offline editing:

- [macOS (Apple Silicon & Intel)](https://github.com/glebmatz/nongine-releases/releases/latest)
- [Windows 10+](https://github.com/glebmatz/nongine-releases/releases/latest)

Built with Tauri. Under 15 MB. Auto-updates included.

## Tech Stack

- **Editor:** React, TypeScript, Zustand, ReactFlow, TipTap, Tailwind CSS
- **Runtime:** Custom VN engine with event-driven architecture, layered renderer
- **Backend:** Supabase (auth, database, storage)
- **Desktop:** Tauri (Rust)
- **Web:** Next.js
- **Docs:** Docusaurus

## Links

- **Website:** [nongine.app](https://nongine.app)
- **Editor:** [app.nongine.app](https://app.nongine.app)
- **Documentation:** [docs.nongine.app](https://docs.nongine.app)
- **Desktop Downloads:** [nongine.app/download](https://nongine.app/download)
- **Changelog:** [nongine.app/changelog](https://nongine.app/changelog)
- **Blog:** [nongine.app/blog](https://nongine.app/blog)

## License

Nongine is a proprietary product with a free tier. See [Terms of Service](https://nongine.app/terms) for details.
