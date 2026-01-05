Refactor report (stability-first)

Files before: 90 (including assets)
Files after:  89 (including assets)

Main changes
- CSS pruned: removed selectors that do not match any class/id present in index.html; dropped empty @media blocks.
- Kept all HTML content unchanged to avoid layout risk.
- No JavaScript introduced.

Sizes
- index.html: 193345 bytes (unchanged)
- styles.css:  668420 bytes -> 224081 bytes

Notes for beginners
- Edit page content in index.html.
- Edit styles in styles.css (organized by selectors already present in HTML).
