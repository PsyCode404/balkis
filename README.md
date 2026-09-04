# Internship Report LaTeX Project

This repository contains a clean LaTeX scaffold for the internship report titled:

**PCAP Preprocessing AI Agent for Automotive Ethernet Testing**

## Structure

- `main.tex` is the main compilation file.
- Front matter, introduction, chapters, and references are split into separate files.
- `figures/` is reserved for images.

## Build

Use a standard LaTeX toolchain from the project root:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

A BibTeX file is already in place at `references/references.bib`.

## Notes

- The project currently contains only the LaTeX structure and placeholder text.
- Replace the placeholder content file by file when the report is ready.
