# Design Brief

## Direction

KUANDO — a premium China↔Angola marketplace with a dark-first, ember-and-ink identity that reads as technological, warm, African and trustworthy.

## Tone

Refined maximal warmth on a deep ink base — bold ember-orange accents over warm charcoal, engineered for confidence and premium feel without e-commerce clichés.

## Differentiation

A "Kwanza Noir" identity: warm charcoal ink, a fiery ember-orange primary and gold secondary that evoke African earth and the Kwanza, paired with Space Grotesk display type — unmistakably KUANDO, never Amazon/Alibaba/Temu.

## Color Palette

| Token      | OKLCH (dark)  | Role                        |
| ---------- | ------------- | --------------------------- |
| background | 0.14 0.02 30  | warm ink base               |
| foreground | 0.95 0.01 60  | primary text                |
| card       | 0.18 0.02 30  | elevated surfaces           |
| primary    | 0.68 0.19 40  | ember-orange CTA            |
| accent     | 0.82 0.14 85  | gold premium highlights     |
| muted      | 0.22 0.02 30  | secondary surfaces          |
| success    | 0.6 0.16 150  | trust / verified / in-stock |

## Typography

- Display: Space Grotesk — hero, headings, product titles, logo
- Body: DM Sans — paragraphs, UI, forms, navigation
- Mono: Geist Mono — prices, codes, quantities, tracking
- Scale: hero `text-4xl md:text-6xl font-bold tracking-tight`, h2 `text-2xl md:text-4xl font-bold tracking-tight`, label `text-xs font-semibold tracking-widest uppercase`, body `text-base`

## Elevation & Depth

Layered warm-charcoal surfaces with subtle-to-elevated shadows; cards lift on hover via `shadow-elevated` while the page stays grounded in the ink base.

## Structural Zones

| Zone    | Background     | Border     | Notes                                   |
| ------- | -------------- | ---------- | --------------------------------------- |
| Header  | card           | border-b   | sticky, elevated, contains search       |
| Content | background     | —          | alternate sections bg-muted/30          |
| Footer  | muted/40       | border-t   | trust links, payment/partner hints      |

## Spacing & Rhythm

Mobile-first generous spacing — section gaps `py-16 md:py-24`, tight card grids `gap-4 md:gap-6`, micro-spacing `gap-2`/`gap-3` for form and chip rhythm.

## Component Patterns

- Buttons: rounded-xl, primary ember-orange with gradient-primary hover, secondary outline
- Cards: rounded-2xl, bg-card, border-border, hover shadow-elevated + translate-y
- Badges: rounded-full pills, ember/gold for promo, success-green for in-stock/verified

## Motion

- Entrance: fade-up 0.5s staggered on hero and section reveals
- Hover: card lift + shadow-elevated 0.3s transition-smooth
- Decorative: subtle fade-in on category tiles, no bouncy loops

## Constraints

- Mobile-first; excellent on telemóvel and desktop
- Português de Angola throughout
- No real payments/transporters/notifications/reviews (MVP simulation only)
- Dark mode is primary; light mode supported via tokens

## Signature Detail

Ember-to-gold gradient text on hero headlines and a gold "verificado" trust badge — the warm premium mark that makes KUANDO feel African, modern and dependable.
