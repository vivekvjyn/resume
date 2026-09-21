# Vivek Vijayan's CV

Built with [Modern-Deedy](https://github.com/Aarif123456/modern-deedy) LaTeX template.

## Build locally

```bash
tectonic -X compile main.tex --outdir build
```

This produces `build/main.pdf`.

## Build prerequisites

[tectonic](https://tectonic-typesetting.org/) — a self-contained TeX engine that bundles packages automatically.

```bash
# macOS / Linux
curl --proto '=https' --tlsv1.2 -fsSL https://drop-sh.fullyjustified.net | sh
```

Or install via your package manager (e.g. `apt install tectonic` on Ubuntu).

## Project structure

```
.
├── main.tex     # Entry point; includes each section
├── sections/    # One file per CV section
├── styles/      # LaTeX class, style files and entry macros
├── assets/
│   └── fonts/   # Lato and Raleway font files
├── build/       # Generated PDF (gitignored)
└── .github/     # CI workflow that builds and releases the PDF
```
