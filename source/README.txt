Bethe 1928 rev22 source package

This package reproduces the 91-page rev22 document while preserving the audited
mathematical layer exactly.

Files:
- Bethe_1928_rev22_English_only_math_preserved_source.tex
  LaTeX assembly source.
- Bethe_1928_Final_Audited_Translation_rev20.pdf
  Immutable audited base document.
- Bethe_1928_rev22_changed_pages.pdf
  The 11 corrected English-prose pages, in the order 4, 7, 13, 14, 16, 18,
  36, 48, 49, 50, 76.

Compile with pdflatex. The source deliberately does NOT re-typeset any inline or
displayed mathematics, Miller indices, tables, figures, or page geometry.

- Bethe_1928_rev22_English_sentence_patch.tex
  Human-editable record of the prose-only changes. It intentionally does not
  reproduce mathematical notation; mathematics remains inherited from rev20.
