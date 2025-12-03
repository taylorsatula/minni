# Minni

*Old Norse: memory, mind*

A constructed writing system for MIRA. Every character fits a 7x9 pixel grid.

---

## Design Philosophy

Minni is not a cipher—it's a writing system where shapes encode meaning. The visual structure of each glyph reflects its phonetic or functional properties, the same way MIRA's memory system encodes relationships between ideas.

---

## Letters

### Core Principle: Vowels vs Consonants

**Vowels are open.** They use negative space, breathe, and don't fully enclose. Air passes freely when you speak them, and the glyphs reflect that.

**Consonants are closed.** They contain, obstruct, or redirect. The mouth closes or constricts when you speak them, and the shapes show it.

### Vowel System

Vowels are positioned based on where they're produced in the mouth:

| Vowel | Position | Description |
|-------|----------|-------------|
| i | front high | Minimal, left-leaning, highest point |
| e | front mid | Left-anchored aperture |
| a | central low | Wide, stable base, most open |
| o | back mid | Right-anchored aperture |
| u | back high | Right-leaning, cupped |

Front vowels (i, e) lean left. Back vowels (o, u) lean right. The low vowel (a) spreads wide at the base.

### Consonant System

Consonants are grouped by how they're produced:

**Stops** (p, t, k, b, d, g) — Complete closure, then release. These use enclosed shapes.
- Unvoiced stops (p, t, k) float
- Voiced stops (b, d, g) have "feet" — grounding elements that anchor them to the baseline

**Fricatives** (f, s, h, v, z) — Partial obstruction, turbulent airflow. These use angular, directional shapes.
- Unvoiced fricatives (f, s, h) float
- Voiced fricatives (v, z) are grounded

**Nasals** (m, n) — Air escapes through the nose. These have vent or chimney-like elements.

**Liquids** (l, r) — Continuous, flowing sounds. Smooth, descending strokes.

**Glides** (w, y) — Transitional sounds between vowels and consonants. Branching or bridging shapes.

**Affricates & Others** (c, j, q, x) — Complex sounds with unique constructions.

### Case: The Crown System

**Uppercase letters are crowned.** A single dot appears at the top-left corner (position 0,0), marking formality or emphasis—like a status indicator.

**Lowercase letters are bare.** The same base shape without the crown.

This mirrors how some writing systems use diacritics for register, rather than entirely different letterforms. In MIRA's terms: the crown is a memory that earns its place through importance.

---

## Numbers: Base-5 Tally System

The number system is countable at a glance. Built on a base-5 structure—one "hand."

| Digit | Representation |
|-------|----------------|
| 0 | Small diamond (void/null) |
| 1 | Single vertical tick |
| 2 | Two vertical ticks |
| 3 | Three vertical ticks |
| 4 | Three ticks above, two below |
| 5 | Horizontal bar (one "hand") |
| 6 | Bar + one tick below |
| 7 | Bar + two ticks below |
| 8 | Bar + three ticks below |
| 9 | Bar + four ticks below |

A reader can see "7" and immediately parse it as "one hand plus two." Like MIRA's scoring system, value is visible in structure.

---

## Punctuation

Punctuation marks encode their function visually:

| Symbol | Name | Logic |
|--------|------|-------|
| . | Period | Sealed square at baseline. Complete, grounded, final. |
| , | Comma | Similar to period but trails downward. Incomplete, continues. |
| ? | Question | Reaches upward, open at top. Seeking what's above. |
| ! | Exclamation | Stacked, dense, weighted. Force pressing down. |
| " | Open quote | Left-anchored, descends into speech. Entering another's words. |
| ' | Close quote | Right-anchored, rises and grounds. Exiting speech. |
| ( | Open paren | Light left curve. Soft aside. |
| ) | Close paren | Light right curve. Aside complete. |
| - | Hyphen | Short horizontal bridge. Connection. |
| — | Dash | Long horizontal bridge. Stronger separation. |

---

## Technical Specifications

- **Grid:** 9 × 9 pixels per glyph (square)
- **Monospaced:** All characters have identical advance width
- **Character set:** 72 glyphs
  - 26 lowercase
  - 26 uppercase (crowned)
  - 10 digits
  - 10 punctuation marks

---

## Files

- `Minni.ttf` — TrueType font
- `Minni.woff2` — Web font
- `Minni_reference.png` — Visual reference sheet
- `font_test.html` — Browser test page

---

## License

Public domain. Use freely.

---

*Part of the MIRA project — a conversational AI that remembers.*
