# sibirposten-preview

Public **preview** of the *Sibirposten* magazine (NO\*Tokleperlen / Siri Tokle),
served as static files via GitHub Pages at
**https://tokleperlen.github.io/sibirposten-preview/** (`noindex` draft for review).

Part of the **ToklePerlen** GitHub org (Siri's cattery + magazine family).

## Structure

| File | What it is |
|---|---|
| `index.html` | Landing page linking the magazine PDFs |
| `Sibirposten-Komplett-SiriStil.pdf` / `-Forbedret.pdf` | Complete issue (done articles), two styles |
| `Sibirposten-Utvidet-SiriStil.pdf` / `-Forbedret.pdf` | Extended/refined incl. KOMMER placeholder pages |
| `Sibirposten-Komplett-Canva.pptx` | Canva-importable editable version |
| `robots.txt` | `Disallow` — keeps the draft out of search |
| `.nojekyll` | Serve files as-is (no Jekyll processing) |

## Source

This repo holds only the **published preview artifacts**. They are generated from the
magazine working material in the family umbrella `ToklePerlen/Tokle` at
`sibirposten/` (the `.docx` sources, article markdown, and `build_issue.py`).
Regenerate there, then upload the refreshed PDFs/PPTX here.

This is a draft preview for review — not the final published magazine.