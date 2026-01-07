# MMErroR Project Page

This repository hosts the project page for **MMErroR: A Benchmark for Erroneous Reasoning in Vision-Language Models**. The page summarizes the paper, highlights the benchmark design, and provides quick access to the PDF and citation.

## Highlights
- **Benchmark scope:** 2,013 multimodal samples spanning 24 subdomains across six domains, each containing exactly one reasoning error.
- **Tasks:** Error Type Classification (ETC) and Error Presence Detection (EPD) to evaluate process-level reasoning.
- **Taxonomy:** Visual Perception, Knowledge Deployment, Question Comprehension, and Reasoning errors.
- **Results:** 20 VLMs evaluated; Gemini-3.0-Pro achieves 66.47% error-type accuracy.

## Editing the page
- Main content lives in `index.html`.
- Paper PDF: `static/pdfs/mmerror.pdf` (copied from the provided ACL paper).
- Images and videos live under `static/images/` and `static/videos/` and can be swapped with MMErroR-specific assets.
- Styles are in `static/css/index.css`; behavior in `static/js/index.js`.

## Viewing locally
Open `index.html` in a browser or serve the folder with any static server, e.g.:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.
