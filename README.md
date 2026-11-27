# Lebanese Official Gazette — 2024

Scanned pages of the 2024 Lebanese Official Gazette (الجريدة الرسمية, published on pcm.gov.lb),
with Arabic OCR text and metadata.

```
2024/
├── ocr_nuqta/        OCR text, UTF-8, one .txt per page (9,412 pages)
├── metadata/         issue index, per-issue tables of contents, page ranges, OCR status
└── original_scans/   original page scans, 516 px wide GIFs (9,412 pages)
```

File names match across folders, for example:

- `2024/original_scans/issue025/2024_issue025_part1_page01571.gif`
- `2024/ocr_nuqta/issue025/2024_issue025_part1_page01571.txt`

`part1` = laws, decrees and decisions; `part2` = judicial and commercial announcements.
Issues ending in `m` (e.g. `issue007m`) are supplements.

## OCR

Every page was read with **Nuqta Arabic OCR 4B** (`SalahALHaismawi/Nuqta-Arabic-OCR-4B-GGUF`, Q8_0, run
locally through Ollama in Markdown mode). OCR can contain mistakes, especially in numbers and names, so
check important details against the original scan.

## Note on paths inside metadata

The metadata files were written by the original pipeline, so their paths use the old folder names:
`2024/images/...` means `2024/original_scans/...`, and `2024/ocr_qwen/...` means `2024/ocr_nuqta/...`
(the file names are the same).
