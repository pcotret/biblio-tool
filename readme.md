# biblio-tool

A tool to make a quick cleaning of research publications and prepare them for notes.
- Put your papers in `articles/to_progress`.
- It will make a folder for each paper `Year_Author_Title` and create the BibTeX file as well as an empty Markdown file for future notes  (as long as the DOI exists).

## Kudos
- https://github.com/qducasse/lectern
- https://github.com/MicheleCotrufo/pdf-renamer

```bash
pip install -r requirements.txt
```

See https://github.com/qducasse/lectern for default commands. Basic usage is : `python lectern.py --process`
