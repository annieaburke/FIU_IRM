# FIU_IRM

Two-axis field of workflow-modes. One CSV row = one dot.

- `index.html` — the editor, one file, opens offline from a local folder
- `data/field.csv` — the dataset, the single source of truth

## Opening

1. Double-click `index.html`. It opens via `file://`.
2. First open: choose `data/field.csv` from the folder, or drag it onto the window.
3. After that, work restores on its own, with a "restored unsaved work" notice showing the save time.

## Saving

- Working state autosaves to the browser (localStorage) as you edit.
- **Export CSV** downloads `field.csv` — identical columns, identical order.
- To the repo, in your signed-in browser: repo page → `data` folder → Upload files → drag the exported `field.csv` in → type a message → Commit. Every save is a commit.
- From the repo: download `field.csv` from the repo page, then drag it onto the editor.

## Keys

- select — click · deselect — Esc
- move — drag, or arrows 0.1 / shift-arrows 0.5
- undo / redo — Cmd-Z / Shift-Cmd-Z
- pan — space-drag or trackpad · zoom — pinch, or scroll toward the cursor
- add dot — double-click empty canvas · delete — button in the side panel
- search — type a tool name top left; Enter steps through matches
