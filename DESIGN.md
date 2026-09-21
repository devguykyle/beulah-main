---
version: reference-aligned
name: Beulah-and-Main-editorial-system
description: Beulah and Main should feel like the supplied generated mockup: a polished Christian editorial magazine with a light high-contrast serif masthead, cream paper, forest green identity, restrained gold actions, fine rules, image-led story modules, and a warm family/culture/literary atmosphere.

voice:
  editorial: "Christian, literary, grounded, hospitable, and culturally observant."
  posture: "Good Stories. Better Company. A Little Closer to Home."
  avoid:
    - "Heavy bold typography"
    - "Rustic heritage costume"
    - "Generic blog cards"
    - "Institutional ministry design"

colors:
  ink: "#14291f"
  text: "#1f211d"
  muted: "#606158"
  paper: "#fbfaf4"
  paper-soft: "#f3efe5"
  rule: "#d8d1c3"
  forest: "#153b2c"
  gold: "#9a7a36"

typography:
  masthead:
    fontFamily: Didot, "Bodoni 72", "Bodoni MT", Georgia, "Times New Roman", serif
    fontSize: 94px
    fontWeight: 400
    lineHeight: 0.9
    letterSpacing: -0.02em
  display:
    fontFamily: Didot, "Bodoni 72", "Bodoni MT", Georgia, "Times New Roman", serif
    fontWeight: 400
    letterSpacing: 0
  body:
    fontFamily: Georgia, "Times New Roman", serif
    fontWeight: 400
    lineHeight: 1.45
  metadata:
    fontFamily: Georgia, "Times New Roman", serif
    fontWeight: 700
    letterSpacing: 0.14em
    textTransform: uppercase

layout:
  max-width: 1220px
  homepage: "Reference-style editorial front page: masthead, nav, hero plus draught card, four story cards, quote image band, lower recent/archive/newsletter grid."
  rules: "Fine hairlines only."
  radius: "No rounded structural cards."
  imagery: "Warm editorial photography: family golf, books, coffee, city neighborhoods, meals, porch reading, open archives."

components:
  masthead:
    textColor: "{colors.forest}"
    ampersandColor: "{colors.gold}"
    typography: "{typography.masthead}"
  primary-action:
    backgroundColor: "{colors.gold}"
    textColor: "#ffffff"
  story-grid:
    backgroundColor: "{colors.paper}"
    borderColor: "{colors.rule}"
  draught-card:
    backgroundColor: "{colors.paper-soft}"
    textColor: "{colors.text}"
  quote-band:
    backgroundColor: "{colors.forest}"
    textColor: "#ffffff"

implementation_notes:
  - "The attached generated mockup is the visual source of truth."
  - "Use thin display serif, not bold newspaper slab energy."
  - "Keep forest green sophisticated and quiet; gold is for actions and small emphasis."
  - "Use image-led editorial modules with compact metadata and fine dividers."
---
