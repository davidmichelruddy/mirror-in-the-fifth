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

# The diminished trinity

> [!ai] Skeleton: fragments, tables, arithmetic only. The complete theory, built on [[Color-tone spirals – held and swapped tritones]]. Jump-off: [[The Trinity of Symmetric Engines]]. Derivation trail and window checks: [[Trinity reconciled – three dim7s from the color tones]].

## Status

- Mirror law, interval sets, both parities, resolution law: *Derived*, ET, all twelve keys
- Center = odd sum, pole = even sum (author's framing): adopted throughout
- Latin square, center ↔ vii°7 bijection: *Derived*, ET
- Lattice: three versions per set, stitched version exact under its center, exact 16/15 resolution: *Derived*, checked for homes C, G, D
- Lendvai's branches = pole mirrors; membership vs action = parity shift: *Derived* arithmetic; reading of Lendvai *Hypothesis* (primary source to check)
- Functional hearing of held vs swapped, oriented vs reversible: *Hypothesis*
- Minor home: parallel minor = same center and square, mode picks which of home's tritones lands; relative minor = home set's other center (I1); harmonic scales = the only window scales containing home's set: *Derived* (§11)

## 1. The claim

- An axis earns its place by deriving a complete interval set (author)
  - odd sum: m2, m3, P4, P5, M6, M7 [1,3,5,7,9,e]
  - even sum: P1, M2, M3, Tri, m6, m7 [0,2,4,6,8,t]
- Odd sum = **center**: falls between two notes, no note sits on it, truly symmetric
- Even sum = **pole**: sits on a note (and its tritone); the note is held, not centered
- Diminished field = twelve tones as three dim7s: C°7 [0,3,6,9] · C♯°7 [1,4,7,t] · B°7 [2,5,8,e] = pitch class mod 3
- One center sorts the field: one set fixed (by m3s), two exchanged (by fifths and semitones)
- One pole sorts it too: one set held (by P1 and Tri), two exchanged (by whole tones and major thirds)
- Resolution = pole → center: tension held at a pole, released at a center
- Three anchors = one period of the field (fifth = 7 ≡ 1 mod 3) → the trinity

## 2. Interval sets and the mirror law

- Spiral outward from the center of I*n*: pair (*x*, *n*−*x*), directed interval *n* − 2*x*
  - odd *n*: every odd interval, each once per half → [m2, m3, P4, P5, M6, M7]
  - even *n*: every even interval → [P1, M2, M3, Tri, m6, m7]; P1 = the pole itself (fixed points *x*, *x*+6)
- Mirror law: set *r* → *n* − *r* (mod 3) → one set fixed (*r* ≡ 2*n*), two exchanged
- Which intervals do which job (one dim7 = ic3 and ic6 only):

|  | Inside the fixed set | Across the exchanged pair |
| --- | --- | --- |
| Center (odd) | ic3 ×2: m3 / M6 | ic5 ×2 (P5 / P4), ic1 ×2 (m2 / M7) |
| Pole (even) | P1 ×2 (held tritone), ic6 ×1 (swapped tritone) | ic2 ×2 (M2 / m7), ic4 ×2 (M3 / m6) |

- → the inside behavior follows from the interval set alone
  - pole: has P1 and Tri → holds one tritone pointwise, flips the other → **oriented**
  - center: has neither → no note fixed, no tritone kept → its fixed set's two tritones trade places → **reversible**
- Twelve mirrors, four per set:

| Set | Poles (even) | Centers (odd) |
| --- | --- | --- |
| C°7 | I0, I6 | I3, I9 |
| C♯°7 | I2, I8 | I5, Ie |
| B°7 | I4, It | I1, I7 |

- Pole pair *n*, *n*+6 = the set's two tritones; center pair *n*, *n*+6 = two anchors a tritone apart

## 3. Window

- Anchors S (F–C) · T (C–G) · D (G–D) = three centers, sums 5, 7, 9
- Poles F, C, G, D (lower poles F, C, G; outer poles F, D)
- Color tones = thirds of each lower pole *p*: bright *p*+4, dark *p*+3 → each a pole of its own spiral

| Center | Sum | Bright | Dark |
| --- | --- | --- | --- |
| S, F–C | 5 | A | A♭ |
| T, C–G | 7 | E | E♭ |
| D, G–D | 9 | B | B♭ |

- Color pair sums = anchor sums (A + A♭ = F + C = 5, etc.) → a color pair is a semitone pair of its anchor's center

## 4. Center view: one center, the whole trinity

- Each center's six pairs = its anchor's fifth, its color semitone, its vii°7's minor thirds, each doubled at the tritone

| Center | Fifths (anchor) | Semitones (color pair) | Minor thirds (fixed set) |
| --- | --- | --- | --- |
| T, C–G (I7) | C–G, C♯–F♯ | E♭–E, A–B♭ | D–F, A♭–B → B°7 |
| D, G–D (I9) | G–D, C♯–A♭ | B♭–B, E–F | C–A, E♭–F♯ → C°7 |
| S, F–C (I5) | F–C, F♯–B | A♭–A, D–E♭ | C♯–E, G–B♭ → C♯°7 |

- → odd interval set = anchor (P5) + color (m2) + diminished (m3): the three layers of the theory in one axis
- Fixed set = the set containing *q*−1 (anchor on *q*; *q*−1 → *q*+8, same set) → **each center fixes its own vii°7**
  - T: B°7 = vii°7 of C · D: C°7 = vii°7 of G · S: C♯°7 = vii°7 of F
- Exchanged pair = the sets of the center's own two color tones (the semitone pair swaps bright ↔ dark)
- Fixed set = the one set the center holds neither color tone of

## 5. Pole view: where a set is held

- Pole on *x*, I(2*x*): holds *x* and *x*+6, swaps the set's other tritone, exchanges the other two sets by M2 and M3
- Window's four poles + six color tones realize all six pole mirrors:

| Set | Pole mirror | Realized by | Holds (P1) | Swaps (Tri) |
| --- | --- | --- | --- | --- |
| C°7 | I0 | pole C | C–F♯ | E♭–A |
|  | I6 | E♭ (T dark), A (S bright) | E♭–A | C–F♯ |
| C♯°7 | I2 | pole G | C♯–G | E–B♭ |
|  | I8 | E (T bright), B♭ (D dark) | E–B♭ | C♯–G |
| B°7 | It | pole F, B (D bright) | F–B | A♭–D |
|  | I4 | pole D, A♭ (S dark) | A♭–D | F–B |

- Each set: two pole mirrors, each holding the tritone the other swaps
- Inner sets: one inner pole + two color tones sharing the other pole mirror
- Home's set (B°7): each outer pole paired with one color tone
- Sets as pole lines: C°7 = C's line · C♯°7 = G's line · B°7 = F's + D's lines

**Lendvai = the pole view**

- Lendvai's axes: tonic C–E♭–F♯–A, dominant G–B♭–C♯–E, subdominant F–A♭–B–D (*Béla Bartók: An Analysis of His Music*, 1971; page to verify)
- His pole / counterpole pairs (principal branch C–F♯, secondary E♭–A, etc.) = a pole mirror's held tritone (recalled; check terminology in the source)
- → each axis's two branches = the set's two pole mirrors (I0, I6 for C°7)
- No centers in Lendvai → no anchor fifth, no color semitone, no vii°7 action (§6)

**Color tones by set** (mod 3)

- Dark *p*+3 ≡ *p* → in its lower pole's set; bright *p*+4 ≡ *p*+1 → in its upper pole's set
- Bright of *p* and dark of *p*+7 a tritone apart → same pole mirror → links inside the window
  - A + E♭ → I6 (C°7) · E + B♭ → I8 (C♯°7)
- Loose ends B (G's bright), A♭ (F's dark) → share pole mirrors with the outer poles F, D → B°7, the window folded

## 6. Where the views meet

**Latin square** (center × set)

|  | C°7 | C♯°7 | B°7 |
| --- | --- | --- | --- |
| S, F–C | bright A | **fixed, I5** | dark A♭ |
| T, C–G | dark E♭ | bright E | **fixed, I7** |
| D, G–D | **fixed, I9** | dark B♭ | bright B |

- Every row, every column: one bright, one dark, one fixed
- Each center touches all three sets once: two through its color tones (poles), one through itself
- Each set: held by two centers' tones (one bright, one dark), fixed by the third center
- Bijection center ↔ own vii°7: S ↔ C♯°7 · T ↔ B°7 · D ↔ C°7

**Membership vs action = the parity shift**

- On the same root *q*: pole I(2*q*) → set ∋ *q* (membership) · center I(2*q*+7) → set ∋ *q*−1 (action)
- One class apart, always
  - C: pole I0 → C°7 (Lendvai tonic) · center I7 → B°7 (resolves to C)
  - B°7: subdominant by membership (poles F, D), dominant by action (vii°7 of C)
- → Lendvai labels by poles; function runs by centers

## 7. Resolution law: pole → center

- Color tone *t* (a pole) resolves, each voice by semitone, onto root *q*:
  - bright: *q* = *t*+1 (down a fifth from its anchor); dark: *q* = *t*+4 (up a fifth)
  - either way *q* ≡ *t*+1 (mod 3) → center on *q* fixes the set ∋ *q*−1 ≡ *t*
- → **the center a tone resolves into fixes the set the tone's pole holds**
- Pole mirror I(2*t*) × center mirror I(2*q*+7) = T3 or T9 (indices differ by 3 or 9) → fixes every dim7
- Other direction (each voice the other way) → root *q*+6, same center mirror
- Checked: all twelve keys, both colors, both directions

| Tone (pole) | Holds | Lands on | Center | Fixes |
| --- | --- | --- | --- | --- |
| E (T bright) | C♯°7, I8 | F | F–C, I5 | C♯°7 ✓ |
| E♭ (T dark) | C°7, I6 | G | G–D, I9 | C°7 ✓ |
| B (D bright) | B°7, It | C | C–G, I7 | B°7 ✓ |
| A♭ (S dark) | B°7, I4 | C | C–G, I7 | B°7 ✓ |
| A (S bright) | C°7, I6 | B♭ | B♭–F, I3 | C°7 ✓ |
| B♭ (D dark) | C♯°7, I8 | D | D–A, Ie | C♯°7 ✓ |

- Inner tones land inside the window; outer tones (A, B♭) on the next centers out (I3, Ie = the other two centers of their sets)
- Color rule (spirals note §5): bright → down a fifth, dark → up; held tritone keeps the tone's color, swapped flips it
- Each set held by two centers' tones resolves onto the third → home's set held by both flanks, lands home twice

## 8. Home and the 1 + 2 shape

- Home center: fixes home's vii°7, exchanges the other two → one self-mirrored set + a mirrored pair
- Home's set (B°7): reversible (center behavior)
  - both tritones held, each by one pole (F–B by F and B, A♭–D by D and A♭)
  - I7 pairs pole with pole (D ↔ F), color tone with color tone (B ↔ A♭), held tritone with held tritone
  - both land home: C major (B–F → C–E), C minor (A♭–D → G–E♭)
- The pair (C°7, C♯°7): oriented (pole behavior)
  - one tritone held by two color tones (E♭–A, E–B♭: pole-centered, reciprocal reach), the other held by the inner pole (C–F♯, C♯–G)
  - land outward: C°7 → G, B♭ · C♯°7 → F, D
- Recentering = T7: every set moves one class (C°7 → C♯°7 → B°7 → C°7)
  - home G → home's set C°7 (held by F♯, E♭) · home D → C♯°7 (held by C♯, B♭); both checked

**Mode edges**

| Set | Bright edge | Dark edge |
| --- | --- | --- |
| C°7 | Lydian C–F♯ | Dorian E♭–A |
| B°7 | Ionian F–B | Aeolian A♭–D |
| C♯°7 | Mixolydian E–B♭ | Phrygian D♭–G |

- Each set: one bright edge, one dark; home's center pairs the modes (Lydian ↔ Phrygian, Ionian ↔ Aeolian, Mixolydian ↔ Dorian)

## 9. Whole-tone layer

- Pole intervals all even → every pole mirror keeps each whole-tone collection [0,2,4,6,8,t] / [1,3,5,7,9,e]
- Center intervals all odd → every center swaps the two collections
- Held tritones: E–B♭, C–F♯, A♭–D even · E♭–A, C♯–G, F–B odd → each set has one tritone in each collection
- Home's center: swaps whole-tone collections and swaps C°7 ↔ C♯°7 → bright/dark exchange on both layers at once
- To check: does this give the jump-off note's "whole-tone highway" a real form, or is it just parity?

## 10. Lattice: poles give lines, centers give stitched sets

- Poles hold a minor-third line (s3 + s5 even); centers trade lines in pairs (import, "Diminished sevenths are minor-third lines")
- Each set, three versions; ET merges them:

| Set (center) | Flatward pole's spine | Stitched, center's vii°7 | Sharpward pole's spine |
| --- | --- | --- | --- |
| B°7 (C–G) | F's: B 50/27, D 10/9, **F 4/3, A♭ 8/5** | F, A♭ · D 9/8, B 15/8 | D's: **B 15/8, D 9/8**, F 27/20, A♭ 81/50 |
| C°7 (G–D) | C's: F♯ 25/18, A 5/3, **C 1/1, E♭ 6/5** | C, E♭ · F♯ 45/32, A 27/16 | A's: **F♯ 45/32, A 27/16**, C 81/80, E♭ 243/200 |
| C♯°7 (D–A) | G's: C♯ 25/24, E 5/4, **G 3/2, B♭ 9/5** | G, B♭ · C♯ 135/128, E 81/64 | E's: **C♯ 135/128, E 81/64**, G 243/160, B♭ 729/400 |

- Stitched = flatward pole's dark half (up a 6/5) + sharpward pole's bright half (down a 6/5); cycle 6/5 · 32/27 · 6/5 · 75/64 = 2/1, every time
- Each spine crosses into the other half 81/80 off at two notes (flatward low, sharpward high)
- Center maps its own window exactly (checked C–G, G–D, D–A) → fixes its stitched set exactly; neighbors' sets only a comma off
- Center maps one spine onto the other (I7: F's spine ↔ D's spine)

**Exact resolution** (B°7 into C, each voice 16/15)

| Version | B → C | D → E♭ | F → E 5/4 | A♭ → G 3/2 |
| --- | --- | --- | --- | --- |
| F's spine (from IV) | 81/80 low | 81/80 low | exact | exact |
| Stitched (C's vii°7) | exact | exact | exact | exact |
| D's spine (from V) | exact | exact | 81/80 high | 81/80 high |

- Each spine resolves exactly through its own half only; the stitched set, through both
- → lattice version of the resolution law: the pole's line is where a set is held, a comma from home; the center's stitched set is the one that lands
- Ties: Two B°7s (import) = F's spine vs stitched; Ch. 7 spine F: D's spine offers F 27/20 (G's 9/5), lands E 81/64 → only F 4/3 resolves onto 5/4 by the leading tone's 16/15

## 11. Minor home

**Parallel minor (C minor): same center, same square, same home set**

- Home center stays C–G (I7); the Latin square uses both colors of every anchor → mode-free
- Mode = one color per anchor → eight scales in the window (poles C, D, F, G fixed):

| S T D | Scale | Tones | Sets hit | Full dim7 |
| --- | --- | --- | --- | --- |
| b b b | Ionian | A, E, B | C°7, C♯°7, B°7 | none |
| d d d | Aeolian | A♭, E♭, B♭ | B°7, C°7, C♯°7 | none |
| b b d | Mixolydian | A, E, B♭ | C°7, C♯°7 ×2 | none |
| b d d | Dorian | A, E♭, B♭ | C°7 ×2, C♯°7 | none |
| b d b | melodic minor | A, E♭, B | C°7 ×2, B°7 | none |
| d b d | Mixolydian ♭6 | A♭, E, B♭ | B°7, C♯°7 ×2 | none |
| d b b | harmonic major | A♭, E, B | B°7 ×2, C♯°7 | **B°7** |
| d d b | harmonic minor | A♭, E♭, B | B°7 ×2, C°7 | **B°7** |

- All bright or all dark (Ionian, Aeolian) → one tone per set, a permutation of the square; mixed → one set doubled
- C°7, C♯°7 never complete inside the window (need F♯ or C♯) → home's set is the only dim7 a window scale can contain
- Home's set complete only with S dark + D bright = both inward tones (A♭ → C, B → C) → the harmonic scales
  - T's color then picks the mode: E → harmonic major, E♭ → harmonic minor
- Natural minor: A♭ only (one inward tone) → harmonic minor's raised 7th = D's bright B, completing home's set → the leading tone derived as the second inward holder
- Mode = which of home's tritones lands
  - major: F–B → C–E (Ionian edge, bright) · minor: A♭–D → G–E♭ (Aeolian edge, dark)
  - home's center exchanges the two (F–B ↔ A♭–D) → parallel major/minor = one reversible set, its two tritones swapped by home's center
  - lattice: both land exactly by 16/15 (§10 table: B → C, F → E 5/4; A♭ → G, D → E♭)

**Relative minor (A minor): the home set's other center**

- Center A–E, sum 13 ≡ 1 → I1 = B°7's second center (B°7: I1, I7) → same home set
- A ≡ C (mod 3) → same Latin square cell for cell; every tone T9 down (E♭ → C, E → C♯, A → F♯, A♭ → F, B → G♯, B♭ → G)
- Window D–A · A–E · E–B: poles D, A, E, B; natural A minor = all dark (F, C, G) = C major's notes
- Roles inside B°7 trade:

| Home | Outer poles | Holders | Major landing | Minor landing |
| --- | --- | --- | --- | --- |
| C | F, D | B, A♭ | F–B → C–E | A♭–D → G–E♭ |
| A | D, B | G♯, F | G♯–D → A–C♯ | F–B → E–C |

- F–B shared: C major and A minor, same landing dyad C–E, two readings (as in the spirals note §7)
- A♭–D vs G♯–D: C minor vs A major, opposite directions
- Lattice (A 5/3, E 5/4, D 10/9, B 15/8):
  - A–E maps its window exactly ✓
  - A's stitched B°7: D 10/9, F 4/3 (D's dark half) · B 15/8, G♯ 25/16 (B's bright half)
  - C's stitched B°7: F 4/3, A♭ 8/5 · D 9/8, B 15/8
  - share F, B; differ at D (10/9 vs 9/8, 81/80) and G♯/A♭ (25/16 vs 8/5, 128/125)
  - A's resolves exactly into A: G♯ → A 5/3, B → C, F → E 5/4, D → C♯ 25/24 (each 16/15)
  - A's D 10/9 = iv's D → the relative minor's vii°7 carries the predominant D; C's carries V's D
- → one ET set, two homes (C, A), two exact lattice sets, a comma and a diesis apart

## 12. Open

- Lendvai primary source: pole / counterpole = held tritone? any notion of a center between notes?
- Oriented vs reversible by ear: home's set vs the pair
- Other resolution direction (antipode roots) in the lattice: exact into which spelling of the far center?
- Pole view in the lattice: I6 realized by E♭ 6/5 (C's line) and by A 27/16 (A's line) → one ET pole mirror, two lattice poles; same for I8, I4, It
- Five-anchor window (B♭–F … D–A): anything new, or the Latin square shifted?
- Whole-tone layer (§9): structure or parity only?
- B°7's four homes (C, E♭, F♯, A = both centers × tritone): do E♭'s and F♯'s stitched sets give two more lattice versions?
- A's stitched B°7 (D 10/9) vs F's spine (D 10/9, B 50/27): related, or coincidence of the shared D?
- Melodic minor / Dorian double C°7 (A + E♭ → E♭–A in the scale): does the doubled set predict each mode's characteristic tritone pull?

## Diagram specs

- **One center, three layers:** clock face, I7 axis between E♭/E and A/B♭; six chords across the axis colored by layer: fifths (C–G, C♯–F♯), semitones (E♭–E, A–B♭), minor thirds (D–F, A♭–B); B°7 square highlighted
- **Latin square as a triangle:** vertices S, T, D (centers); each edge = the set its two centers' tones hold (bright and dark holder at the ends); each vertex labeled with the set it fixes, arrow from the opposite edge
- **Poles and centers on one clock face:** six even axes through tones (I0 … It) and six odd axes between tones (I1 … Ie), colored by the set each fixes; window's tones and three centers marked
- **Lattice strip, B°7:** F's spine and D's spine as two parallel minor-third lines, stitched set as the zigzag F–A♭ · D–B between them, comma gaps marked; C–G center shown
