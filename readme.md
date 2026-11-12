# Hemp Beverage Company — Design System ("Join the Revolution")

Source: https://hempbevco.com (Shopify storefront) — scraped Nov 2026. Content in `site-content.md`, `data/products.json`, `data/pages-raw.md`. Images in `assets/`.

Visual showcase: **Design System.dc.html**. Header/footer: **Header Footer.dc.html**.

## Brand context
Fast-acting, federally legal hemp-derived Delta-9 THC drinks: Mocktail Creator (liquid THC you add to any drink), THC-infused & plain non-alcoholic wines (Rosé, Chardonnay), wellness (re:LEAF, SwāeZ). Phoenix, AZ. 21+ only.

## Content fundamentals
- Voice: upbeat, social, reassuring. "Sip Smarter. Feel Better." "Cheers to good vibes." "Crafted for good vibes only."
- Address the reader as **you**; brand as **we**.
- Headlines short, punchy, Bebas (all caps rendering). Body sentence case, plain language.
- Always clear on dose (mg), onset (~15 min), legality (2018 Farm Bill, ≤0.3% Δ9), 21+, lab tested.
- No emoji. Unicode ★ for ratings, → for links are fine.

## Visual foundations
- **Color**: from the crest — copper #C8935A, hemp olive #6F7D2B, sage #CDD7B1, cream #FAF6EE canvas, olive-ink #23261A instead of black. Ratio ≈ 60 cream / 22 ink / 10 olive / 6 copper / 2 sage. Copper-500 is never used for text on cream (low contrast) — use copper-600 or put ink on copper.
- **Type**: Bebas Neue display (headlines, prices, big numbers, buttons); Manrope body/UI (400–800); JetBrains Mono for specs/batch numbers.
- **Shape**: soft, generous radii — cards 22px, inner image wells 16px, buttons/chips pill. Double-frame motif from logo border.
- **Depth**: mostly flat with 1px #E6DDC9 lines; soft long shadows for floating UI (header on scroll, menus, modals); copper glow for promos.
- **Backgrounds**: cream page; dark olive (#262B17) for footer & night moments; gradient meshes, sunburst, topo rings, paper grain (see tokens/gradients.css).
- **Patterns**: crest dots, label stripes, grid, crest rings, checker, chevron, arches — CSS only.
- **Imagery**: warm, social, golden-hour lifestyle; product renders on white/cream wells. Duotone olive→copper to unify stock.
- **Effects**: frosted glass (blur 16, cream 16%) over photography; protection gradient for type on photos; copper foil animated text (sparingly); outline-echo type.
- **Motion**: "pour" easing cubic-bezier(.22,1,.36,1). Fast 150 / base 250 / slow 450 / reveal 800ms, 80ms stagger. Hover: buttons lift 3px, cards 6px; press scale .96. Marquee 40s linear. Respect reduced motion.
- **Layout**: floating rounded sticky header (20px inset), rounded hero and footer panels, 1360px max content width.

## Iconography
The current site uses no custom icon set. Use simple Unicode glyphs (→ ↗ + − ✓ ★) or a thin-stroke CDN set (e.g. Lucide, 1.75px stroke) — flagged as a substitution. No emoji.

## Index
- styles.css → tokens/{typography,colors,gradients,spacing,motion}.css
- Design System.dc.html — full visual showcase
- Header Footer.dc.html — site header (mega menu) + footer
- Style Options.dc.html — earlier exploration (T4 / logo colors / H3 / F1 chosen)
- assets/ — logo, products, recipes, press, pages
