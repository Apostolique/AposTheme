# Change Log

All notable changes to the "apostheme" extension are documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/).

## [Unreleased]

- Nothing yet!

## [1.2.0] - 2026-07-26

### Added
- Syntax highlighting for `.diff` / `.patch` files: headers, hunk ranges, index lines,
  and inserted / deleted / changed lines.
- Syntax highlighting for git commit messages, interactive rebase todo files, and `.gitignore`.
- Semantic highlighting (`semanticHighlighting: true`) with a full `semanticTokenColors` map.
- Bracket pair colorization (`editorBracketHighlight.foreground1`-`6`) and matching
  bracket pair guides.
- Scopes for regular expressions, decorators / annotations, preprocessor directives,
  labels, and `invalid` / deprecated code.
- Scopes for CSS color literals, pseudo-classes, pseudo-elements and at-rules.
- Scopes for YAML anchors and block scalars, TOML keys and tables, XML namespaces,
  CDATA and declarations, and JSX components.
- Markdown scopes for strikethrough, link URLs, code fence languages, tables,
  horizontal rules and front matter.
- Language scopes for shell, Makefile, Dockerfile, SQL, Python, Rust and Go.
- Workbench colors for the minimap, breadcrumbs, notifications, menus, quick input,
  keybinding labels, settings editor, inlay hints, ghost text, sticky scroll,
  command center, banner, testing, charts, symbol icons, the debug UI, merge
  conflicts and the terminal.
- Overview ruler and gutter decorations for errors, warnings, matches and git state.

### Changed
- The four variants now inherit every shared color from `AposTheme-color-base.json`
  and only declare the ~23 surface colors that carry their hue.
- Diff editor now distinguishes word-level changes from line-level ones
  (`diffEditor.insertedTextBackground` vs `diffEditor.insertedLineBackground`).
- Markdown heading markers (`#`) are dimmed against the heading text.
- Minimum supported VS Code raised to 1.85.

### Fixed
- The green and red variants were both named `AposTheme` internally, the same as the
  blue variant.
- The green and red variants used the blue `peekViewTitle.background`.

## [1.1.3] - 2024-01-29
- `enum` added to the keyword scopes.

## [1.1.2] - 2023-12-13
- `struct` added to the keyword scopes.

## [1.1.1] - 2023-12-13
- Keyword color applied to property `get` / `set` accessors.

## [1.1.0] - 2023-12-09
- Release scripts reworked to version from the git tag.

## [0.8.0] - 2023-12-09
- Punctuation coloring for interpolated strings.
- Open VSX release workflow.
- Color fixes across the themes.

## [0.7.4] - 2021-02-04
- Earlier releases predate this changelog; see the
  [commit history](https://github.com/Apostolique/AposTheme/commits/main) for details.

[Unreleased]: https://github.com/Apostolique/AposTheme/compare/v1.2.0...HEAD
[1.2.0]: https://github.com/Apostolique/AposTheme/compare/v1.1.3...v1.2.0
[1.1.3]: https://github.com/Apostolique/AposTheme/compare/v1.1.2...v1.1.3
[1.1.2]: https://github.com/Apostolique/AposTheme/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/Apostolique/AposTheme/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/Apostolique/AposTheme/compare/v0.8.0...v1.1.0
[0.8.0]: https://github.com/Apostolique/AposTheme/compare/v0.7.4...v0.8.0
[0.7.4]: https://github.com/Apostolique/AposTheme/releases/tag/v0.7.4
