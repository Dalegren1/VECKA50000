# Pannkakor — Receptsida

En receptsida byggd med vanilla HTML och CSS.

## Tekniker
- Semantisk HTML5
- BEM-namngivning
- CSS custom properties (tokens)
- Flexbox & CSS Grid
- clamp() för fluid typografi och bilder
- Responsiv design utan media queries (flex-wrap, auto-fit)

## Filstruktur
styles/
  reset.css       — reset
  tokens.css      — CSS-variabler
  global.css      — typografi och container
  header.css      — header, nav, social
  hero.css        — hero-sektion
  recipes.css     — receptgrid och kort
  contact.css     — kontaktformulär
  footer.css      — footer


## Struktur & tanke
Sidan är byggd som en one-page layout där varje sektion 
behandlas som en egen komponent med separata CSS-filer. 
Strukturen är medvetet förberedd för React, där samma 
uppdelning används fast som JSX-komponenter.