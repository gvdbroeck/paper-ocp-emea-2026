# OCP EMEA 2026 DC Protection Paper

Paper on DC short-circuit protection methodology for the OCP EMEA Summit Future Technologies Symposium (April 2026).

## Conference Details

- **Event**: OCP EMEA Summit Future Technologies Symposium
- **Date**: April 29, 2026 | Barcelona, Spain
- **Digest Submission Deadline**: February 9, 2026 (11:59 PM PT)
- **Format**: 2-page IEEE two-column conference format
- **Prize**: $10,000 for best paper

### Judging Criteria

1. **Innovation** - Uniqueness vs. current state-of-the-art
2. **Impact to OCP Community** - Market coverage potential
3. **Timeline to Impact** - Years to market prevalence

### Requirements

- Must report on innovative engineering/scientific results
- Technology projected 2-5 years out
- **Must not be commercial** or contain confidential information
- Categories: AI/HPC, Data Center Sustainability, Future Tech

## Paper Title

**"A Systematic Methodology for DC Short-Circuit Protection Evaluation in High-Power Data Center Microgrids"**

Alternative titles considered:
- "A Practical Methodology for DC Short-Circuit Protection Evaluation in Megawatt-Scale DC Data Center Microgrids"
- "Democratization of short-circuit current calculations"

## Paper Topic

A systematic methodology for DC short-circuit protection evaluation in high-power data center microgrids, featuring:
- Transient simulation-based analysis
- Multi-source fault contribution evaluation
- Protection coordination strategies
- Laboratory validation with solid-state circuit breaker (SCCB) prototypes

### Guiding Principles

- Highlight that it can be easily done (software application exists, but not commercial)
- Focus on practical application, not just mathematical theory
- Show technical fundament without overwhelming with differential equations
- Enable others to run short-circuit current calculations

## Timeline

- **Jan 9**: Kick-off
- **Jan 16**: Get access to SCCB lab test results
- **Jan 23**: First draft
- **Jan 30**: Second draft
- **Feb 6**: Submission two-pager digest
- **Mar 23**: Draft presentation
- **Apr 29**: Final presentation at OCP EMEA Summit

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

- `digest.tex` - 2-page IEEE conference format digest (main paper)
- `references.bib` - BibTeX bibliography
- `planning.md` - Detailed paper outline and ABB meeting strategy
- `figures/` - Directory for figures and images

## Compilation

The paper compiles automatically on Overleaf. For local compilation:

```bash
pdflatex digest.tex
bibtex digest
pdflatex digest.tex
pdflatex digest.tex
```
