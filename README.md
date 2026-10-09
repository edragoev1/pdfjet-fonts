# pdfjet-fonts

The fonts of [PDFjet](https://github.com/edragoev1/pdfjet): the TrueType fonts
its examples and tests use, which PDFjet embeds as subsets of the glyphs a
document draws, and the metrics of the 14 standard PDF fonts in `Core`. IBM
Plex Sans is also here as `.otf`, a font with CFF outlines, which PDFjet
subsets as well; so are the Regular of IBM Plex Sans SC, TC, JP and KR, the
hinted `.otf` of the same IBM release as their `.ttf`, as a document of
Chinese, Japanese or Korean draws hundreds of glyphs, whose CFF outlines
are smaller (Examples 02 and 04: about a quarter smaller PDFs); and `Test` has Source Han Sans JP Regular, a CID-keyed font
with CFF outlines, for the tests. Since PDFjet 9.0.5 there are no `.stream`
files, and PDFjet reads `.ttf` and `.otf` fonts alone.

This repository is the `fonts` directory of
[edragoev1/pdfjet](https://github.com/edragoev1/pdfjet), at the commit that
`fonts-and-data.txt` of PDFjet pins. PDFjet's build, run and test scripts
fetch it there the first time they run, and `get-fonts-and-data.sh` does it
alone.

## Licenses

Every font keeps its own license, in the file next to it.

| Directory | License file | License |
|---|---|---|
| `Core` | `LICENSE.txt` | The license of the Adobe AFM files: free to use, copy and distribute, with the copyright notices kept |
| `IBMPlexMath` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexMono` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSans` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSansArabic` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSansHebrew` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSansJP` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSansKR` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSansSC` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSansTC` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSansThai` | `license.txt` | SIL Open Font License 1.1 |
| `IBMPlexSerif` | `license.txt` | SIL Open Font License 1.1 |
| `JetBrainsMono` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSans` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansArabic` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansHebrew` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansJP` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansKR` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansMono` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansSC` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansSymbols` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansTC` | `OFL.txt` | SIL Open Font License 1.1 |
| `NotoSansThai` | `OFL.txt` | SIL Open Font License 1.1 |
| `SourceSerif4` | `OFL.txt` | SIL Open Font License 1.1 |
| `Test` | `SourceHanSansJP-LICENSE.txt` | SIL Open Font License 1.1 |
