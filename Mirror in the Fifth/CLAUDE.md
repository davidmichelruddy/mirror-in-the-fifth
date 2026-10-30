# Mirror in the Fifth

A music theory writing project on pitch-class symmetry, axes of inversion, interval cycles, dualism, and structures that bridge tonal and atonal practice. Outputs: book chapters, Substack essays, and SVG pitch/interval diagrams.

This folder is an Obsidian vault (Minimal theme), synced by iCloud and tracked in git.

## Vault layout

- `00_Inbox/`: raw captures and rough ideas. Daily notes go in `00_Inbox/Daily/`.
- `01_Meta/`: system files and prompts. Templates are in `01_Meta/Templates/` (Templater syntax: `<% tp.date.now("YYYY-MM-DD") %>`; daily notes are named `YYYY-MM-DD`).
- `02_Sources/`: notes on papers, references, and citations.
- `03_Substack/`: essays as they move through `01_Ideas/` → `02_Drafts/` → `03_Published/`.
- `04_Assets/`: images and exported SVGs that notes embed.
- `05_AppSync/`: data and diagram specs exchanged with the custom diagram web app.
- `06_Book/`: manuscript chapters and outlines.

## Rules

1. **Protected folders:** only edit files in `06_Book/` or `03_Substack/` when asked to work on that specific file. Anywhere else, creating new notes is fine.
2. **Critique before editing:** when reviewing a draft, give feedback on musical clarity, argument, pacing, and flow first. Wait for a go-ahead before rewriting.
3. **Don't move or rename notes** unless asked. Links depend on file names. If a rename is needed, update every `[[link]]` that points at the note.
4. **Leave `.obsidian/` alone** unless asked to change vault settings.
5. **Claims:** cite the theorist and work behind any historical or theoretical claim (Riemann, Lewin, Cohn, Straus, etc.). If you are unsure of a source, flag it instead of inventing one.

## Obsidian conventions

- Link between notes with `[[Note Name]]` wikilinks. Embed files with `![[file.svg]]`.
- New notes start with YAML frontmatter that includes at least `type` and `tags`. Use nested tags such as `log/daily`.
- Use callouts for asides: `> [!note]` for technical tangents, `> [!example]` for worked examples, `> [!info]` for proofs or derivations.

## Writing style

- **Audience:** advanced musicians. Be precise about theory without academic padding.
- **Voice:** authoritative, curious, clear. No filler ("in today's world", "delve into", "it's worth noting").
- **Structure:** use `##` and `###` headings to pace the argument. Bold each key concept the first time it appears.

## Notation

- **Pitch-class operations:** integers 0–11 with C = 0; use `t` and `e` for 10 and 11 in set listings. Write sets as `[0,1,4]`, prime forms as `(014)`, and operations as T*n*, T*n*I, or I*n*. Name the index or axis of every inversion explicitly.
- **Performance examples:** letter names with Unicode accidentals (C♯, D♭, B♮).
- **Intervals:** P5, M3, and so on for tonal contexts. Use interval classes (ic1–ic6) for set-theoretic contexts.
- **Staff notation:** the ABC Music Notation plugin renders ` ```abc ` code blocks as sheet music. Use them for short musical examples: chords, voicings, a mirrored pair side by side. Keep the header minimal (`X:1`, `L:`, `K:`) and remember that ABC has its own accidental syntax (`^C` sharp, `_D` flat, `=B` natural), separate from the Unicode accidentals used in prose. For example, C major and C minor as a chord pair:

  ```abc
  X:1
  L:1/1
  K:C
  [CEG] | [C_EG] |]
  ```

- **Diagrams:** when a concept would benefit from a figure, include a short SVG spec: what it shows, which pitch classes or axis, and the layout (clock face, Tonnetz, line). The spec is for the web app in `05_AppSync/`.
