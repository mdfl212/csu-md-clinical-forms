# Push full form sources

The complete HTML apps are ready in the project workspace. To upload them to this repo from a machine with GitHub access:

```bash
git clone https://github.com/mdfl212/csu-md-clinical-forms.git
cd csu-md-clinical-forms
mkdir -p forms

# Copy from the Grok project artifacts / attachments (or download the files):
# - Dynamic_HnP.html
# - Community Health Questionnaire (index.html)
# - OBGYN_HxPE.html
# - Pediatric History & PE form

# Then:
git add forms/
git commit -m "Add full clinical form HTML apps"
git push origin main
```

Or drag-and-drop the four HTML files into a `forms/` folder on GitHub’s web UI.
