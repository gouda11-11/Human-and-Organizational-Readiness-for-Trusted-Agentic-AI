# HORA-TAI development guide

This repository contains the working specification for Human and Organizational
Readiness for Trusted Agentic AI (HORA-TAI). The document is maintained in
reStructuredText (RST) and built with Sphinx.

## Source structure

- `src/doc/index.rst`: title, abstract, history, authors, keywords, foreword,
  status note, and table of contents.
- `src/doc/chapters/01_chapter1.rst`: introduction and scope.
- `src/doc/chapters/02_chapter2.rst`: problem statement and objectives.
- `src/doc/chapters/03_chapter3.rst`: terms and definitions.
- `src/doc/chapters/04_chapter4/index.rst`: HORA-TAI framework.
- `src/doc/chapters/05_annex/`: assessment method, delegation levels, and
  proposed requirements.
- `src/doc/chapters/06_appendix/index.rst`: readiness assessment worksheet.
- `src/doc/chapters/07_references.rst`: references and supporting sources.

## Build and preview

The GitHub Actions workflow builds the HTML documentation and PDF whenever
changes are pushed to the `main` branch.

To build the HTML documentation locally:

```shell
pip install -r requirements.txt
sphinx-build -b html src/doc target/html
```

To build the PDF locally, install a LaTeX distribution and run:

```shell
sphinx-build -b latex src/doc target/latex
make -C target/latex
```

PlantUML is configured for diagrams. If a source file uses a PlantUML
directive, install Java and PlantUML and make the `plantuml` command available
on the system path.

## Document maintenance

Keep the document version consistent across `README.md`, `src/doc/conf.py`,
and the History table in `src/doc/index.rst`. Preserve the distinction between
the working proposal and an approved ITU-T Recommendation. Changes to proposed
requirements should retain their identifiers unless a substantive revision
requires an explicit change record.

The DataTracker record for this work item is
https://tida-datatracker.org/doc/fg-tida-contribution-7/.
