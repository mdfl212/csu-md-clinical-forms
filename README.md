# CSU SOM · Clinical Digital Forms

**MD201 / MD202** — Problem-oriented medical record tools for Caraga State University School of Medicine.

Self-contained HTML apps (no backend). Open in Chrome or Edge. Data stays in the browser (`localStorage`).

## Repository

**https://github.com/mdfl212/csu-md-clinical-forms**

## Forms (full sources)

The complete single-file apps live under `forms/`:

| File | Description |
|------|-------------|
| `forms/Dynamic_HnP.html` | **Dynamic History & Physical** — context-aware H&P simulator. Demographics drive Pediatric / Gyn / Obstetric modules. Speech-to-text, debounced autosave with Saved/Saving pill, CSV + DOCX export. CSU medical red theme. |
| `forms/Community_Health_Questionnaire.html` | Brgy. Abilan Health Center community assessment (CHQ). Guided + Classic + Dictation UIs, voice commands, CSV/DOCX. |
| `forms/OBGYN_HxPE.html` | Obstetric History & Physical — stepped form, LMP→AOG/EDC, ICD-10/11 search, DOCX. |
| `forms/Pediatric_HxPE.html` | Pediatric History & Physical structure. |

## Quick start

```bash
git clone https://github.com/mdfl212/csu-md-clinical-forms.git
cd csu-md-clinical-forms
# Open forms/Dynamic_HnP.html in Chrome or Edge
```

Or download individual HTML files from the `forms/` folder on GitHub and open them locally.

## Dynamic H&P features

1. Demographics first → auto Pediatric (age < 18), Gyn (female 12–55), Obstetric (G-P / LMP / keywords)
2. Natural language dictation → structured fields
3. Shared patient state + debounced autosave
4. History vs PE separation; incomplete-items list
5. CSV and Word export

## License

Educational use — CSU SOM Batch / MD201–MD202 clinical skills.
