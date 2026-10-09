# Steps 0–3 report: photo.jpg

Total time 37s; per step: exif 0.7s, variants 4.7s, edges 5.0s, ocr 37.2s

Next: record clues on board.py (`clue`), lookup clues with `apply`; list the candidates in full first (`children`), then rank.

## Metadata

No metadata (common for forwarded images, screenshots, rephotographed images). Raw output: `{"file": "/home/user/GEO/case1/photo.jpg", "size": [2576, 1224]}`

## OCR text (second reader; pass=up/tile was only read after zooming, treat it as an assumption)

No text read. Maybe there really is no text, or it's too small: zoom in by hand with imgprep.py zoom and look again

## Reverse image search

Not done (--no-rev). This is not "searched, nothing found".
## Output files

- Edge crops: `edges/` (8 images; look at the four edges and four corners one by one)
- Variants: `variants/` (3 images)
- OCR annotated image: `ocr.png`



## Status

- exif: ok
- variants: ok
- edges: ok
- ocr: ok