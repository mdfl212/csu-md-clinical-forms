# CSU SOM · Clinical Digital Forms

**MD201 / MD202** — Problem-oriented medical record tools for Caraga State University School of Medicine.

Self-contained HTML apps (no backend). Open in Chrome or Edge. Data stays in the browser (`localStorage`).

## Forms

| File | Description |
|------|-------------|
| [`Dynamic_HnP.html`](Dynamic_HnP.html) | **Dynamic History & Physical** — context-aware H&P simulator. Demographics drive Pediatric / Gyn / Obstetric modules. Speech-to-text dictation, autosave, CSV + DOCX export. CSU medical red theme. |
| [`Community_Health_Questionnaire.html`](Community_Health_Questionnaire.html) | Brgy. Abilan Health Center community assessment (CHQ). Guided + Classic + Dictation UIs, voice commands, CSV/DOCX. |
| [`OBGYN_HxPE.html`](OBGYN_HxPE.html) | Obstetric History & Physical Examination — stepped form, LMP→AOG/EDC calc, ICD-10/11 search, DOCX export. |
| [`Pediatric_HxPE.html`](Pediatric_HxPE.html) | Pediatric History & Physical — birth/feeding/milestones/immunization structure (UI shell). |

## Dynamic H&P highlights

1. **Demographics first** → auto-detects Pediatric (age < 18), Gynecologic (female 12–55), Obstetric (G-P / LMP / keywords).
2. **Natural language input** — dictate or type; fields fill and flash.
3. **Shared patient state** across steps; debounced autosave with "Saved / Saving…" indicator.
4. **History vs PE** kept separate; incomplete items listed under Assessment.
5. **Export** CSV (flat row) and Word (.doc HTML).

## Usage

1. Download or clone this repo.
2. Open any `.html` file in a modern browser (Chrome/Edge recommended for speech recognition).
3. No install or server required.

## License

Educational use — CSU SOM Batch / MD201–MD202 clinical skills.
