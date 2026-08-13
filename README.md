# Resume — Prince Ralambomanarivo

LaTeX resume source and compiled PDF.

## Files

- `Prince_Ralambomanarivo_Resume.tex` — LaTeX source
- `Prince_Ralambomanarivo_Resume.pdf` — Compiled PDF

## How to Compile

### Overleaf (no install)

1. Go to [overleaf.com](https://www.overleaf.com)
2. New Project → Upload Project → upload the `.tex` file
3. It compiles automatically

### Linux

```bash
sudo apt install texlive-latex-base texlive-latex-recommended texlive-latex-extra texlive-fonts-recommended
pdflatex Prince_Ralambomanarivo_Resume.tex
```

### macOS

```bash
brew install --cask mactex
pdflatex Prince_Ralambomanarivo_Resume.tex
```

### Windows

1. Install [MiKTeX](https://miktex.org/download)
2. Open a terminal and run:

```bash
pdflatex Prince_Ralambomanarivo_Resume.tex
```

### Docker (any platform)

```bash
docker run --rm -v $(pwd):/work -w /work texlive/texlive pdflatex Prince_Ralambomanarivo_Resume.tex
```
