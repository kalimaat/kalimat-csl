# Changelog

## 1.0.0 (2026-09-24)

First published version of the kalimat citation style.

- **Two layouts.** Records with the Language `ar-Arab` use the Arabic layout; all other records, including transliterated Arabic (`ar-Latn`), use the Latin-script one.
- **Short notes throughout,** with no first-mention/subsequent distinction and no ibid.
- **Punctuation:** notes end without punctuation, so the author's own full stop, comma or semicolon follows the citation. Bibliography entries end with a full stop.
- **Historical texts** (Extra: `type: classic`) name their editor or translator in notes: `(ed. Kratchkovsky)`, `(تحقيق هارون)`. An Arabic historical text without an editor names its press instead: `(ط. دار الكتب العلمية)`.
- **Arabic note locators:** `ص` before pages and `ق` (ورقة) before folios; volumes and chapters as entered (`ج 2، ص 750–753`).
- **Manuscripts:** repository, `رقم الحفظ`/`MS` and shelf mark, laid out correctly next to Latin shelf marks in Arabic notes in Word.
- **Authors who share a surname** are given with their first names in notes.
- **Sorting:** an Extra line `kalimat-sort:` sets a name's place in the bibliography where ʿ, ʾ or an internal al- would misfile it.
- **Word-safe text direction:** Latin citations in Arabic text are marked with invisible left-to-right marks, which Word keeps and does not display.
