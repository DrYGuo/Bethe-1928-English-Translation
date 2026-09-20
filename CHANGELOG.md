# Changelog

All notable revisions to the working translation are documented here.

## [rev22] — 2026-09-20

### Prose-only revision of the audited translation
- `Bethe_1928_Final_Audited_Translation_rev22_English_only_math_preserved.pdf` (91 pp) replaces `Bethe_1928_Final_Audited_Translation_rev20.pdf`
- English prose corrected on 11 pages (PDF pp. 4, 7, 13, 14, 16, 18, 36, 48, 49, 50, 76); no inline or displayed mathematics, Miller indices, tables, figures, or page geometry re-typeset — the mathematical layer is inherited unchanged from rev20
- `source/` replaced with the rev22 source package: LaTeX assembly source, human-editable English sentence patch record, changed-pages PDF, and the immutable rev20 base document

All notable revisions to the working translation are documented here.

## [Polished Reading Edition] — 2026-09-20

### Two-document release
- `Bethe_1928_Final_Audited_Translation_rev20.pdf` (91 pp) — the complete audited translation, now under its canonical filename; authoritative for exact equations (1)–(94), numerical tables, figures, footnotes, and documented source-print anomalies
- `Bethe_1928_Polished_English_Reading_Edition.pdf` (26 pp) added — polished English reading edition: all 665 sentence-aligned audit units re-reviewed with a second criterion (the English must read as coherent scientific prose); Germanic calques, page-break artifacts, duplicated wording, and logically opaque constructions revised against the German facsimile and fidelity audit as controls
- Nine fidelity issues identified by the previous audit incorporated, including the (46a)/(43) cross-reference and the p. 63 page-break/footnote repairs
- Displayed equations are not reconstructed from extracted text in the reading edition; gray "Audited mathematical material" notes mark where exact mathematics is preserved in the audited translation

### LaTeX source published
- `Bethe_1928_Polished_English_Reading_Edition.tex` — standalone LaTeX source of the reading edition now included in the repository
- `source/` — supporting audit material: prose review report, math notation audit checklist, audit appendix source

## [rev20] — 2026-09-18

### Pagination and front matter
- Translation paginated from p. 1 (cover + edition contents unnumbered front matter)
- Printed page numbers 1–89 on all content pages; PDF page labels match (Cover / Contents / 1–89)
- New cover page: title, translator credit ("Translated by Yueming Guo using Muse Spark 1.3 (Meta)"), contact email, motivation paragraph, September 2026, how-to-cite
- New "Contents of this edition" page
- Translation pp. 1–2 restructured: p. 1 = translator's note + Bethe's original contents; p. 2 = title block + article text (redundant "3." heading removed)

### Content fixes
- p. 60: Repaired corrupted paragraph (Helvetica overlay with lost math glyphs over partially erased LMRoman); restored from audited Rev. 4 with correct V₀, r², V(𝔯)
- p. 53: Converted two Helvetica paragraphs to serif for font consistency (wording unchanged)
- Cover motivation: "The translator does not read German" stated explicitly; paragraph set justified

### Tables
- Table 1 (p. 8): Rebuilt with thick separator between Observational/Theoretical groups; 24 rows + Mean verified
- Table 2 (dedicated p. 10): 551̄ overbar preserved (crystallographic −1); em dashes in Θ* column; 9 rows verified
- Table 3 (p. 68): Rebuilt; ρ_g header cleaned; lower continuation split into two blocks
- German original Tabellen 1–4 appended (pp. 85–88)

### Appendices
- Printing-errors appendix (pp. 75–76): Seven source-print anomalies documented
- Historical terminology appendix (p. 89): 20-term German → English → modern equivalent glossary
- German original figures (pp. 77–84)

## [rev19] — 2026-09-18
- Added cover page and edition contents (91 pp total)
- File-size fix: flattened stacked image layers (115 MB → 4 MB)

## [rev18] — 2026-09-18
- Added historical terminology appendix (p. 89)

## [rev17] — 2026-09-18
- Table 3 rebuilt; 6 Germanism fixes in English prose (§§2–3)

## [rev16] — 2026-09-18
- Fig. 5 cropped (removed German body text); p. 7 font unified to serif; attribution wording fixed

## [rev15] — 2026-09-18
- Table 1 rebuilt with thick separator; moved to dedicated p. 8

## [rev14] — 2026-09-18
- Table 2 moved to dedicated page

## [rev13] — 2026-09-18
- Table 2 fixed in place (551̄, em dashes); German original tables appended

## [rev12] — 2026-09-18
- (Superseded by rev13: English tables stay in place; German originals appended as reference)

## [rev11] — 2026-09-18
- Attribution: Muse Spark 1.3 and GPT-5.6 each credited with ~ten rounds of audit
- Read-only final QA passed (82 pp)

## [rev10] — 2026-09-18
- Attribution corrected: GPT-5.6 contributed ~ten rounds (not a single pass)

## [rev9] — 2026-09-18
- Appendix anomalies 5 → 7; figure caption line breaks aligned to German originals (Figs. 1, 2, 7, 8)

## [rev8] — 2026-09-18
- Surgical repair of rev7 layout regressions (pp. 10, 29, 73)

## [rev7] — 2026-09-18
- Footnote 1 repositioned (p. 63→64); (46a) and (43) text-layer fix; anomalies #6–#7 added

## [rev6] — 2026-09-18
- 6 editorial fixes: Summary Davisson–Germer clause restored; 2 German calques reworded; contents re-typeset

## [rev5] — 2026-09-18
- 665-entry prose audit closure: 0 REVISE, 0 unresolved alignment (A=0, B=0)

## [rev4] — 2026-09-17
- Math layer certified against German facsimile; 31 transcription corrections applied
