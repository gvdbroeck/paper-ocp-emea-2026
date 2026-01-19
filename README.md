# OCP EMEA 2026 DC Protection Paper

Paper on DC short-circuit protection methodology for the OCP EMEA Summit Future Technologies Symposium (April 2026).

## Conference Details

- **Event**: OCP EMEA Summit 2026 - Future Technologies Symposium
- **Digest Submission Deadline**: February 9, 2026 (11:59 PM PT)
- **Format**: 2-page IEEE two-column conference format

## Paper Topic

A systematic methodology for DC short-circuit protection evaluation in high-power data center microgrids, featuring:
- Transient simulation-based analysis
- Multi-source fault contribution evaluation
- Protection coordination strategies
- Laboratory validation with solid-state circuit breaker (SCCB) prototypes

## Workflow

This repository is synchronized with Overleaf for collaborative editing and compilation.

### Editing Workflow

1. **Local Editing**: Edit `.tex` and `.bib` files locally in your preferred editor
2. **Commit Changes**: `git commit -am "Description of changes"`
3. **Push to GitHub**: `git push origin main`
4. **Overleaf Sync**: Overleaf automatically pulls changes from GitHub
5. **Pull Collaborator Changes**: `git pull origin main` to get updates from Overleaf

### Overleaf Integration

This repository is linked to an Overleaf project for LaTeX compilation. Changes pushed to GitHub are automatically synced to Overleaf.

## Collaboration

- **Lead Author**: Giel Van den Broeck (DEP)
- **Co-Authors**: Pavel Purgat (ABB), Dusan Brhlik (DEP), Antonello Antoniazzi (ABB)

## Files

- `main.tex` - Main LaTeX document (IEEE conference format)
- `references.bib` - BibTeX bibliography
- `figures/` - Directory for figures and images

## Compilation

The paper compiles automatically on Overleaf. For local compilation:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```
