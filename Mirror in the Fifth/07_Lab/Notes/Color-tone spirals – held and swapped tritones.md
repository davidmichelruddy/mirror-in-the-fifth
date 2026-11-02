---
type: working-note
date: 2026-10-30
author: ai
ai-assisted: true
source: Claude Code session
tags:
  - lab/working-note
  - theory/diminished
  - theory/axis
---

# Color-tone spirals: held and swapped tritones

> [!ai] Skeleton: fragments, tables, arithmetic only. Extends two working notes in [[Restructured argument (tab)]]: "the unit, the poles and the three diminished sevenths" and "inside and outside diminished, from the anchors". The import itself stays untouched.

## Status

- Mirror structure (held / swapped, which sets): *Derived*, any pole, ET
- Voice leading of the resolutions: *Derived*
- Choice of resolution direction (vs. tritone-sub direction): open → §8
- Functional hearing (S / D / home pull): *Hypothesis*

## 1. Starting point

- Anchor window F–C · C–G · G–D → lower poles F, C, G
- Color tones (thirds of each lower pole):
  - S, F–C → A (bright) / A♭ (dark)
  - T, C–G → E (bright) / E♭ (dark)
  - D, G–D → B (bright) / B♭ (dark)
- Each pair = one half-step axis of its anchor's pair-based spiral (sums 5, 7, 9); the other axis of each (D–E♭, A–B♭, E–F) = not a color pair
- First pass (pairs → three dim7s): any two pairs cover all 12; all three cover each dim7 twice, one bright + one dark → coverage only, no direction → superseded by single-tone spirals below
- Single tone → tone-based mirror I*n*, *n* = 2 × tone (mod 12)

## 2. The six spirals

| Function | Tone   | Index | Pairs (fixed points first and last)           |     |
| -------- | ------ | ----- | --------------------------------------------- | --- |
| T bright | E (4)  | I8    | E–E · E♭–F · D–F♯ · D♭–G · C–G♯ · B–A · B♭–B♭ |     |
| T dark   | E♭ (3) | I6    | E♭–E♭ · D–E · D♭–F · C–F♯ · B–G · B♭–A♭ · A–A |     |
| D bright | B (11)  | I10    | B–B · B♭–C · A–D♭ · A♭–D · G–E♭ · F♯–E · F–F  |     |
| D dark   | B♭ (10) | I8    | B♭–B♭ · A–B · A♭–C · G–C♯ · F♯–D · F–E♭ · E–E |     |
| S bright | A (9)  | I6    | A–A · A♭–B♭ · G–B · G♭–C · F–D♭ · E–D · E♭–E♭ |     |
| S dark   | A♭ (8) | I4    | A♭–A♭ · G–A · G♭–B♭ · F–B · E–C · E♭–D♭ · D–D |     |

- Each spiral spelled from the tone's own anchor, centered on the tone
- Six spirals → four ET mirrors: I4, I6, I8, I10 (whole-tone ladder around home's I7)
- Merged pairs = the pole-centered tritones (formerly "neutral"): E/B♭ (I8), E♭/A (I6)
  - same pitch-class pairs, different center and spelling: D♭–G from E vs C♯–G from B♭; C–F♯ from E♭ vs G♭–C from A
  - → distinct spirals in the lattice (§7); ET index alone hides this
- Unmerged: B (I10), A♭ (I4), a minor third apart
- Every spiral covers all 12 → trivial; content = how it treats the three dim7s

## 3. Held and swapped

- **Held tritone:** the mirror's two fixed points = the tone + its tritone; each note maps to itself
  - exact in ET only; lattice: center exact, rim split (§7, center and rim)
  - → an oriented object, center → rim, not an unordered pair
- **Swapped tritone:** the other tritone of the same dim7; its two notes trade places
- Tone's own dim7: kept as a set, one tritone still, one flipped
- Other two dim7s: exchanged with each other, pair by pair

Sets: C°7 [0,3,6,9] · C♯°7 [1,4,7,10] · B°7 [2,5,8,11]

| Spiral | Holds set | Held tritone | Swapped tritone | Exchanged sets |
| --- | --- | --- | --- | --- |
| E (I8) | C♯°7 | E–B♭ | D♭–G | C°7 ↔ B°7 |
| E♭ (I6) | C°7 | E♭–A | C–F♯ | C♯°7 ↔ B°7 |
| B (I10) | B°7 | B–F | A♭–D | C°7 ↔ C♯°7 |
| B♭ (I8) | C♯°7 | B♭–E | C♯–G | C°7 ↔ B°7 |
| A (I6) | C°7 | A–E♭ | G♭–C | C♯°7 ↔ B°7 |
| A♭ (I4) | B°7 | A♭–D | F–B | C°7 ↔ C♯°7 |

- Held-set distribution: C♯°7 ← E, B♭ · C°7 ← E♭, A · B°7 ← B, A♭
- Home's B°7: held only by D and S spirals, never by T's
- B and A♭: each swaps the other's held tritone (B holds B–F, swaps A♭–D; A♭ holds A♭–D, swaps F–B)

## 4. Resolutions

Each voice by semitone; target read from the tone's own anchor.

| Anchor | Tone | Held → | Reads as | Swapped → | Reads as |
| --- | --- | --- | --- | --- | --- |
| C–G | E | E–B♭ → F–A | F major | D♭–G → C–A♭ | F minor |
| C–G | E♭ | E♭–A → D–B♭ | G minor | C–F♯ → B–G | G major |
| G–D | B | B–F → C–E | C major | A♭–D → G–E♭ | C minor |
| G–D | B♭ | B♭–E → A–F | D minor | C♯–G → D–F♯ | D major |
| F–C | A | A–E♭ → B♭–D | B♭ major | G♭–C → F–D♭ | B♭ minor |
| F–C | A♭ | A♭–D → G–E♭ | C minor | F–B → E–C | C major |

> [!example] Home's two spirals, held then swapped
> E: E–B♭ → F–A, D♭–G → C–A♭
>
> ```abc
> X:1
> L:1/2
> K:C
> [E_B] [FA] | [_DG] [C_A] |]
> ```
>
> E♭: E♭–A → D–B♭, C–F♯ → B–G
>
> ```abc
> X:1
> L:1/2
> K:C
> [_EA] [D_B] | [C^F] [B,G] |]
> ```

## 5. The rule

|  | Direction on the spine | Held tritone | Swapped tritone |
| --- | --- | --- | --- |
| Bright tone (E, B, A) | down a fifth | major | minor |
| Dark tone (E♭, B♭, A♭) | up a fifth | minor | major |

- Direction ← tone's color; held keeps the tone's color; swapped flips it (swap = color flip, P)
- Crossing: bright tone sits sharpward of its pole (+4 fifths) → pulls flatward; dark tone sits flatward (−3) → pulls sharpward
- Same crossing as "crossed resolution on every anchor", but reached from a single tone's spiral → independent second route

> [!info] General form, lower pole *p*
> - Bright tone *p*+4 → I(2*p*+8): holds (*p*+4, *p*+t), swaps (*p*+1, *p*+7)
>   - held → (*p*+5, *p*+9): root + M3 of *p*+5, major
>   - swapped → (*p*, *p*+8): 5 + ♭3 of *p*+5, minor
> - Dark tone *p*+3 → I(2*p*+6): holds (*p*+3, *p*+9), swaps (*p*, *p*+6)
>   - held → (*p*+2, *p*+t): 5 + ♭3 of *p*+7, minor
>   - swapped → (*p*+e, *p*+7): M3 + root of *p*+7, major
> - Check: *p* = 0 → E, E♭ · *p* = 7 → B, B♭ · *p* = 5 → A, A♭

- Major landing always root + M3; minor landing always 5 + ♭3 → the two landings of one spiral = twins under the target's own unit mirror (sum 2·target + 7)
  - e.g. F–A ↔ C–A♭ under F–C (sum 5): 5 + 0 = 5, 9 + 8 = 17 ≡ 5
  - → spiral's two tritones deliver one target's major/minor twin pair

## 6. Destination map

| Destination | From | Colors |
| --- | --- | --- |
| B♭ | A (S bright) | major, minor |
| F | E (T bright) | major, minor |
| C | B (D bright), A♭ (S dark) | both, twice |
| G | E♭ (T dark) | minor, major |
| D | B♭ (D dark) | minor, major |

- Five roots B♭ … D, symmetric around C
- Tonic's own tones → S and D only, never home
- Home ← flanking anchors only, inward-facing tones (D's bright, S's dark), both colors each
- Outer tones (S bright, D dark) → one fifth beyond the window: IV/IV, V/V
- Closes T/D/S on home; ties the twelve tones to function via spirals, not via set membership

**T6 partners and two families**

- B♭ = T6(E), A = T6(E♭); partner's spiral = same ET mirror, read from the other end (list reversed)
- T6 flips color and direction: E bright ↓ F · B♭ dark ↑ D; E♭ dark ↑ G · A bright ↓ B♭
- Held tritone: same landing dyad, opposite reading (F–A: F major / D minor; D–B♭: G minor / B♭ major)
- Swapped tritone: opposite resolution, landings T6 apart (C–A♭ vs D–F♯; B–G vs F–D♭)
- Family 1, E · E♭ · B♭ · A: closed under home's mirror (E↔E♭, B♭↔A) and T6 (E↔B♭, E♭↔A); outward-pointing spirals
- Family 2, B · A♭: twins under home's mirror, a minor third apart; T6 → F, D (outside the six); homeward spirals

## 7. Lattice readings

Addresses (fifths, thirds): E (0,1) · E♭ (1,−1) · B (1,1) · B♭ (2,−1) · A (−1,1) · A♭ (0,−1)

| Tone | Lattice sum S | ET index | Minor-third line held |
| --- | --- | --- | --- |
| E | (0, 2) | 8 | G's line |
| B♭ | (4, −2) | 8 | G's line |
| E♭ | (2, −2) | 6 | C's line |
| A | (−2, 2) | 6 | C's line |
| B | (2, 2) | 10 | D's line (D 9/8, B 15/8) |
| A♭ | (0, −2) | 4 | F's line (D 10/9, B 50/27) |

- Rows: bright tones on s5 = 2, dark on s5 = −2; each anchor's pair shifted by (2, 0) along the spine
- E / B♭ and E♭ / A: same line, different centers → ET merges two mirrors
- B / A♭: different lines, ET merges into one B°7
  - B → dominant-reading B°7 (V's D, true leading tone)
  - A♭ → predominant-reading B°7 (ii's D)
  - → function label predicts which of the "Two B°7s"
- Spelling as address:
  - D♭–G (from C, → F minor) vs C♯–G (from G, → D major)
  - C–F♯ (from C, → G major) vs G♭–C (from F, → B♭ minor)
- Same held dyad, two readings:
  - E–B♭ → F–A: F major from C / D minor from G
  - E♭–A → D–B♭: G minor from C / B♭ major from F
  - both pole-centered tritones; reading set by the anchor heard as home

**Center and rim: oriented tritones**

- ET index (I8) and sorted pair (E–B♭) flatten E → B♭ and B♭ → E into one object
- Lattice sum S keeps the spirals apart ((0, 2) vs (4, −2)) but drops orientation
- Spiral = center (exact) + rim (antipode, split): +2 m3 (dark arm) vs −2 m3 (bright arm), a diesis apart
- Notation: center → rim (arm), e.g. E → B♭ (dark), B♭ → E (bright)

| Spiral | Center | Rim, dark arm (+2 m3) | Rim, bright arm (−2 m3) |
| --- | --- | --- | --- |
| E | E 5/4 | **B♭ 9/5** = B♭'s center | A♯ 125/72 |
| B♭ | B♭ 9/5 | F♭ 162/125 | **E 5/4** = E's center |
| E♭ | E♭ 6/5 | B♭♭ 216/125 | **A 5/3** = A's center |
| A | A 5/3 | **E♭ 6/5** = E♭'s center | D♯ 125/108 |

- Reciprocal reach: each rim lands exactly on the partner's center, opposite arm, opposite direction
  - E → B♭: dark arm, up · B♭ → E: bright arm, down
  - E♭ → A: bright arm, down · A → E♭: dark arm, up
  - color/direction flip of the resolutions (F major vs D minor) already present in the reach
- Other tritones:

| Tritone | Ends that are spiral centers | Reciprocal exact reach |
| --- | --- | --- |
| E–B♭, E♭–A | both | yes |
| B–F, A♭–D | one (F, D = poles) | no; e.g. B's arms → F 27/20, E♯ 125/96, not F 4/3 |
| D♭–G, C–F♯ | none | no |

- → pole-centered tritones (E–B♭, E♭–A) = the only pairs generated from both ends, each end reaching the other exactly
- → candidate for prominence: the axes the outward-pointing spirals turn on (author's claim; *Derived* for the reach, *Hypothesis* for the weight)
- Antipode note ("the far point splits in two") → here: which half of the split is the partner's center

**Correction: no neutral tritones (author)**

- "Neutral" = sum of two addresses (E + B♭ = (2, 0)) → symmetric, unordered → same flattening as the ET index
- Oriented: tritone takes its center's color (held keeps the tone's color, §5)
  - E → B♭ bright (→ F major) · B♭ → E dark (→ D minor) · E♭ → A dark (→ G minor) · A → E♭ bright (→ B♭ major)
- Zero sum only with one spelling (each end = partner's center); other arm colored: E's rim A♯ → (−2, 4) · B♭'s rim F♭ → (6, −4)
- From home: E–B♭ in E's spiral (bright), E♭–A in E♭'s spiral (dark) → 3 bright, 3 dark

| Mode | Edge tritone | Color from home | Third |
| --- | --- | --- | --- |
| Lydian | C–F♯ | bright | E |
| Ionian | F–B | bright | E |
| Mixolydian | E–B♭ | bright (was neutral) | E |
| Dorian | E♭–A | dark (was neutral) | E♭ |
| Aeolian | A♭–D | dark | E♭ |
| Phrygian | D♭–G | dark | E♭ |

- Edge color = mode's third: major-third modes bright, minor-third modes dark
- Home's mirror: every mode pair swaps bright ↔ dark (Lydian ↔ Phrygian, Ionian ↔ Aeolian, Mixolydian ↔ Dorian); no neutral → neutral exception
- Kept from the old reading: E–B♭, E♭–A = pole-centered (E–G–B♭, A–C–E♭) + reciprocal (rim = partner's center); color still anchor-dependent (B♭ → E dark from G–D)
- Corrected 2026-10-30 in [[Restructured argument (tab)]] and [[The Mirror in the Fifth (tab)]] (see each file's Corrections log); 600¢ midpoint → "tempered tritone"
- Blues working note removed from the import (author: unsupported)
- To check: does the color-from-home reading match the hexagon addresses, or does it require switching to oriented addresses throughout?

## 8. Ties to existing notes

- Crossed resolution on every anchor → now per tone, plus the color split
- Two routes to the outside sets → color tones along the chromatic semitone; here made directional
- "Neutral tritones take color from a neighbor" → §7 same-dyad readings; "neutral" withdrawn (§7 correction)
- Two B°7s → §7, B vs A♭
- Blue notes on the axis → E–B♭ and E♭–A = I7 and IV7 tritones = the tonic spirals' held tritones
- Principle: swap = P move

## 9. Open / to check

- Other resolution direction (each voice the other way, toward the antipode)
  - first pass, E: E–B♭ → D♯–B (B major), D♭–G → D–F♯ (B minor) → rule survives at F's antipode?
  - check all six
- Held vs swapped by ear: does keeping the color feel more stable than flipping it?
- F–A after E–B♭ with C as home vs with G as home
- Minor-key homes: does the rule hold with A or C minor as home?
- Lattice: are each spiral's two landings exact twins, or a comma off?
- Tritone species from each tone's own anchor (bright / dark) vs from home
- Extending the window: D–A's tones F♯ (→ G) and F (→ A); does each new anchor add exactly one outer destination?
- Relation to the mode-edge table (edge tritones cycling through the dim7s)

## Diagram specs

- **E's spiral, clock face:** I8 axis through E and B♭; held tritone E–B♭ on the axis; swapped D♭–G with exchange arrow; C°7 / B°7 pairs in two colors across the axis; resolution arrows to F–A and C–A♭
- **Destination map, line of fifths B♭ … D:** six tones above the line, arrows to their target roots; bright arrows flatward, dark sharpward; major/minor marked at each landing
