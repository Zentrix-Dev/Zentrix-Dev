# Assets

Hand-authored SVG assets used by the profile README. These are **not** auto-generated —
edit them by hand and commit changes directly.

| File | Purpose |
|------|---------|
| `terminal-banner.svg` | Top-of-page banner with terminal prompt + brand name |
| `terminal-card.svg`   | Larger "about me" terminal card shown in the About section |
| `divider.svg`         | Animated horizontal gradient divider between sections |
| `footer-wave.svg`     | Animated wave footer shown after the Connect section |
| `logo.svg`            | Hexagonal "Z" logo / avatar, shown at the top of the README |
| `background.svg`      | Cyber-grid background (available for use in custom pages) |
| `social-icons.svg`    | Reusable `<symbol>` library of social platform icons |

## Editing notes

- All SVGs use the same blue-cyber palette (`#0A0F1E`, `#38BDF8`, `#1E90FF`, `#3B82F6`, `#00BFFF`).
- Keep `font-family` stacks as `'JetBrains Mono','Fira Code','Courier New',monospace` for terminal text.
- Animations use SMIL (`<animate>` / `<animateTransform>`) so they render on GitHub without JS.
