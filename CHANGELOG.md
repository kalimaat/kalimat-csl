# Changelog

## 1.0.4 (2026-10-01)

- **Manuscripts end with a full stop** even when the record has a URL (manuscript URLs are not printed).
- **Edition and volumes as in Chicago** (Latin script): `Title. 2nd ed. Place…` instead of `Title, 2nd ed.`; `Vol. 3`; and the number of volumes when no single volume is cited: `The Arabian Nights Encyclopedia. 2 vols. Santa Barbara…`. Arabic entries are unchanged.
- **Forthcoming in Arabic:** with Extra `status: قيد النشر` and no date, the date position reads `(قيد النشر)`.
- The style's `self` link now points to its published address on GitHub.

## 1.0.3 (2026-10-01)

- **First editions.** A book cited in a later edition gives its first edition in one entry: enter Extra `original-date:` (and, if different, `original-publisher-place:` and `original-publisher:`). Arabic: `(الطبعة الأولى: بغداد: دار الرشيد، ١٩٧٩).` Latin script: `First published Baghdad: Dār al-Rashīd, 1979.` A translated book keeps `(تاريخ النشر في اللغة الأصل: …)` in Arabic.

## 1.0.2 (2026-10-01)

- **Forthcoming works.** Enter Extra `status: forthcoming` and leave the date empty. Without a publisher or journal the status follows in parentheses (`In Title, ed. Neguin Yavari (forthcoming).`; `“Title.” (forthcoming).`), after a journal it replaces the year (`Journal (forthcoming).`), and after a publisher it takes the year's place (`Leiden: Brill, forthcoming.`).

## 1.0.1 (2026-10-01)

- **Serial comma in name lists, as in Chicago.** Bibliography: a comma after the inverted first name (`Gruendler, Beatrice, and Isabel Toral`) and before "and" in lists of three or more (`Conybeare, F. C., J. R. Harris, and A. S. Lewis`). Notes and editor/translator lists: a comma before "and" from three names up (`Conybeare, Harris, and Lewis`; two names stay `Gruendler and Toral`). Arabic lists are unchanged.

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
