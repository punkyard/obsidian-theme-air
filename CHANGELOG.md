# Changelog

## [Unreleased]

## [0.2.1] — 2026-08-18

### Fixed

- Obsidian theme-review checks now pass with zero errors and zero warnings; removed `!important`, `:has()`, CSS masks, named colors, and unsupported `text-indent` usage (#51)
- Fenced code blocks inside lists render consistently through six nesting levels, including aligned fences, backgrounds, bullets, copy controls, and language labels (#52, #58)
- Ordered, unordered, and task-list content aligns with in-list code-block edges (#53)
- Side-pane divider lines remain translucent instead of bright (#55)
- Balanced spacing around regular code blocks, paragraphs, and lists (#56, #57)
- Tags inherit the regular text font without changing tag colors (#59)
- Cancelled task boxes use a styled cross and strikethrough; completed tasks remain unstruck (#60)

## [0.2.0] — 2026-07-20

### Fixed

- Obsidian theme-review warnings: removed `!important`, `:has()`, `text-indent`, and `mask-image` from fenced code blocks inside lists — CSS-only gradient approach (#48, #50)

## [0.1.5] — 2026-07-19

### Fixed

- Fenced code blocks inside bullet lists — background, fence, and text aligned properly at every nesting depth (L1/L2/L3) (#45)
- List fenced code uses `::before` pseudo-element for rounded background corners
- Hidden opening-fence row no longer paints oversized top area
- List blockquote bottom padding balanced
- Checkbox dual-mark rendering, all states use window background color (#44)
- Light-mode border leaks and low-specificity border rules
- List marker color uses `--text-normal` instead of accent

## [0.1.1] — 2026-07-10

### Fixed

- Graph view lines invisible in light mode — hardcoded dark colors replaced with theme-aware vars (#25)
- `[x]` checkbox icon showing checkmark (v) instead of X in live preview (#25)
- Frontmatter tag pills had dark background — now transparent, accent text only (#25)

### Added

- `[x]` checkbox box background now gray (`--text-muted`) when checked (#25)
- `[v]` checkbox item text colored with accent (`--text-accent`) (#25)
- Unchecked checkboxes in live preview get accent border (#25)

## [0.1.0] — 2026-07-09

### Added

- Initial release
- Flat ultra-dark (and light) design
- Accent-driven heading system (H1–H6)
- Custom Syne heading font
- Zero border-radius, no pane borders
- Ribbon hides until hover
- mobile support
