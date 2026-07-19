# Changelog

## [Unreleased]

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
