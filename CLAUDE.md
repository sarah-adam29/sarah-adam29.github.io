# CLAUDE.md

Portfolio site for Sarah Adam, served by GitHub Pages from `main` at https://sarah-adam29.github.io/.

Plain HTML and CSS: `index.html`, `styles.css`, `favicon.svg`. No framework, no build step, no JavaScript unless strictly needed. Preview by opening `index.html` in a browser. `design/mockup-reference.html` is the approved design; its inline styles are for reference only.

## Public data only

The repo is public. Nothing confidential goes in it: no client names, engagement data, employer materials, personal email or phone number.

## Site copy

Don't rewrite site copy unless asked.

## Design rules (do not break)

- White background. The plum accent (`--accent`) appears only on the eyebrow line, primary buttons, links, the ~3% figure and the thin lines above the How I work items.
- Buttons have a 6px corner radius. Never pill-shaped.
- No cream or off-white page backgrounds, no monospace labels, no emoji, no 01/02/03 numbering, no gradients, no left-border accent cards, no animations.
- Responsive: works at 375px wide with no horizontal scroll; nav wraps; cards stack.
- Accessibility: text contrast at least 4.5:1, visible focus styles in the accent colour, external links keep normal behaviour (no forced new tabs).
- Colours are CSS custom properties at the top of `styles.css`. Use them rather than hard-coded values.

## Git habit

One short-lived branch per change, cut from an up-to-date `main`. Open a PR, merge it, delete the branch.
