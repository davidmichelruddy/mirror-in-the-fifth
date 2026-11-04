---
type: research
author: ai
verified: false
created: 2026-11-04
tags:
  - research
  - theory/axis
  - theory/means
  - source/zarlino
  - source/archytas
---

# Dividing the fifth – research

Why 5/4 × 6/5 = 3/2, what the three means have to do with it, and what Zarlino actually said. Prompted by [[2026-11-04]] (E/E♭ as reflection point). Related: [[Book outline]] Part III "Two triads" and "The mirror"; [[Payoff inventory]] row "Zarlino's two divisions of the fifth"; [[Symmetric Questions]] (Coleman on the means).

## Q: Why do the two thirds multiply to the fifth?

Stacking intervals multiplies frequencies. Going up a major third multiplies by 5/4; going up a minor third multiplies by 6/5. Do both and you've multiplied by 5/4 × 6/5 = 30/20 = 3/2.

Worked in hertz, with C = 200:

| | Hz | step from previous | from C |
|---|---|---|---|
| C | 200 | – | 1 |
| E | 250 | ×5/4 | 5/4 |
| G | 300 | ×6/5 | 3/2 |

| | Hz | step from previous | from C |
|---|---|---|---|
| C | 200 | – | 1 |
| E♭ | 240 | ×6/5 | 6/5 |
| G | 300 | ×5/4 | 3/2 |

- The same two steps in opposite orders.
- E and E♭ are 10 Hz apart: 250/240 = 25/24.

The same thing three other ways:

- **Partials:** the major triad is partials 4 : 5 : 6. (5/4)(6/5): the 5 cancels, leaving 6/4 = 3/2. Counting 4 → 5 → 6.
- **Cents:** 386 + 316 = 702. Cents are logarithms, which turn multiplying into adding. Semitones (4 + 3 = 7) are the ET version of the same sum.
- **Lattice:** E (0,1) + E♭ (1,−1) = (1,0) = G. Multiplying ratios is adding coordinates.

## Q: Where is the centre of the fifth, and why isn't it at 250 Hz?

There are three ways to average 200 and 300, and each one lands somewhere different:

| mean | formula | 200 & 300 | note |
|---|---|---|---|
| arithmetic | (a + b) / 2 | 250 | E |
| harmonic | 2ab / (a + b) | 240 | E♭ |
| geometric | √(ab) | ≈ 244.9 | no note: ≈ 351¢ above C, the axis |

- The ear hears ratios, not differences, so the centre of an interval is its geometric mean. The geometric centre of C–G is √(3/2) above C, which is the lattice point (½, 0).
- A pitfall: a reader who averages hertz will land on E.
- Check: arithmetic × harmonic = geometric². That's 250 × 240 = 60,000 = 200 × 300. This is 5/4 × 6/5 = 3/2 written as means. The two thirds sit either side of the axis, equally far from it in ratio (each is √(25/24) away, about 35¢).

## Q: Did I have Zarlino's labels the wrong way round?

Yes. In chat I said "major = arithmetic, minor = harmonic." That's true **for frequencies**. Zarlino worked with **string lengths**, and lengths are the reciprocals of frequencies. Taking reciprocals swaps the arithmetic and harmonic means, so his labels are the reverse:

| | string lengths (Zarlino) | his name | frequencies | mean, in frequency |
|---|---|---|---|---|
| major (M3 below) | 15 : 12 : 10 | harmonic division | 4 : 5 : 6 | arithmetic |
| minor (m3 below) | 6 : 5 : 4 (as A–C–E) | arithmetic division | 10 : 12 : 15 | harmonic |

- 15 : 12 : 10: the harmonic mean of 15 and 10 is 2·150/25 = 12. ✓
- 6 : 5 : 4 as lengths: 6→5 is a minor third (the longer string is lower), then 5→4 is a major third. ✓
- The same numbers 4 : 5 : 6 read as frequencies are the major triad. Whether a number set "is" major or minor depends on whether you read it as lengths or as frequencies. The dualists' use of this ambiguity (von Oettingen, Riemann) is *citation needed*; I haven't checked it.
- The geometric mean doesn't move under the swap (√(15·10) and √(4·6) both give the same ≈351¢ point). The arithmetic and harmonic means trade places, but the axis stays fixed.
- [[Symmetric Questions]] uses Zarlino's convention ("E … the Harmonic Mean … from the perspective of string proportions"). That's consistent with this table.

**For the book:** if the Hz version leads, the means come out in frequency terms (E arithmetic). Citing Zarlino then needs the length/frequency flip, or it will look like a contradiction.

## Q: What exactly does Zarlino say?

Source: *Le istitutioni harmoniche*, Venice 1558, from the TMI reading edition (Utrecht), [tmiweb.science.uu.nl/text/reading-edition/zarins58.html](https://tmiweb.science.uu.nl/text/reading-edition/zarins58.html). The page numbers are the 1558 pages as marked in that edition. Chapter numbers differ in the revised 1573 edition, so check that before citing.

**Part III, ch. 15 "Del Ditono, ouer Terza maggiore" (p. 161)**: the two divisions as the same thirds in opposite order:

> "Questo è veramente marauiglioso, che la Natura habbia ordinato in tal maniera l'vna Consonanza dopo l'altra, che ritrouandosi tra le parti del Senario la forma della Diapente, diuisa Arithmeticamente in due parti, tra questi termini 6. 5. 4; il Musico ritroua queste parti, con uno ordine contrario, tra la istessa Diapente diuisa harmonicamente in due parti, tra questi termini. 15. 12. 10."

Rough gloss (for the author, not for quoting): *this is truly marvellous: in the senario the fifth divided arithmetically gives 6:5:4, and the musician finds the same parts in contrary order in the same fifth divided harmonically, 15:12:10.*

**Part III, ch. 10 "Della propietà, o natura delle consonanze Imperfette" (pp. 156–57)**: the affect, and his ranking:

> "alcune di loro sono viue & allegre … & alcune, quantunque siano dolci, & soaui, declinano alquanto al mesto, ouero languido. Le prime sono le Terze, & le Seste maggiori … & le altre sono le minori."

> "la Quinta tramezata, o diuisa harmonicamente in vna Terza maggiore, & in vna minore; il che molto diletta all'vdito."

> "la Quinta si pone al contrario, cioè mediata arithmeticamente da vna chorda mezana; di modo che molte uolte si odeno le consonanze, poste contra la natura del Numero sonoro."

- Major: the harmonic division, "according to the nature of the sonorous number."
- Minor: the arithmetic division, "contrary to" it.
- He ranks them. He doesn't treat them as equal mirror images.

**Part I, ch. 39 "Della Diuisione, ouero Proportionalità harmonica" (≈ p. 50)**: the method for dividing a fifth harmonically: divide 3:2 arithmetically to get 6:5:4, then convert it to get 30:24:20 (= 15:12:10). He also quotes Pietro d'Abano: "Il mezo è quello, che genera l'harmonia" (*the mean is what generates harmony*).

## Q: Was Zarlino a dualist?

No. Riemann (1880) claimed him as a forerunner of major–minor dualism. The Polish Music Library encyclopedia calls that "erroneous" ([polskabibliotekamuzyczna.pl](https://polskabibliotekamuzyczna.pl/encyklopedia/zarlino/?lang=en)). The ch. 10 passage shows why: for Zarlino, minor goes against nature. He saw the opposite order. He didn't see two equal and opposite fields.

**For the lineage:** Zarlino noticed the two thirds swap order inside one fifth. The dualists turned that into a mirror. That fits the [[Book outline]] historical thread between Euler and the dualists, or as background to it. Zarlino comes before Euler (1558 vs 1739).

## Q: Does it go back to Archytas?

**Only the means do, not the divided fifth.**

- The three means (arithmetic, geometric, harmonic) come from an Archytas fragment (Diels–Kranz 47 B2) quoted by Porphyry in his commentary on Ptolemy's *Harmonics*. The harmonic mean was earlier called "subcontrary," and the rename is credited to Archytas and Hippasus.
- In Greek theory the means divide the **octave** (12 : 9 : 8 → 9 is the arithmetic mean, 8 the harmonic, giving fifth and fourth), not the fifth into thirds. Thirds weren't consonances in that scheme.
- So the lineage is: Archytas names the means → Zarlino uses them to divide the fifth into two thirds.
- Sources: MacTutor's Archytas biography ([mathshistory.st-andrews.ac.uk](https://mathshistory.st-andrews.ac.uk/Biographies/Archytas/)). The standard scholarly edition is Huffman, *Archytas of Tarentum* (Cambridge, 2005), which has **not been checked**.

## To check before citing

- [ ] Zarlino page and chapter numbers against a facsimile (IMSLP / Internet Archive scan of 1558), and against 1573 if that edition is cited
- [ ] An English translation for any quoted lines: Part III is in Marco & Palisca, *The Art of Counterpoint* (Yale, 1968); Part I has partial translations
- [ ] Archytas fragment number and the Hippasus renaming, against Huffman (2005)
- [ ] Whether Zarlino is the first to frame the fifth's two divisions this way (Fogliano 1529 and Ramis 1482 are earlier just-intonation theorists)
