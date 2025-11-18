# Curriculum Vitae - Vinod A. Thale

This repository contains the LaTeX source files for Vinod A. Thale's Curriculum Vitae.

## Description

A professional academic CV showcasing research experience, education, publications, and skills in computational fluid dynamics and multiphase flow simulations.

## Structure

- `cv-llt.tex` - Main CV document file
- `settings.sty` - Style definitions and formatting settings
- `Introduction.tex` - Professional profile/summary
- `education.tex` - Educational background
- `employment.tex` - Employment history
- `publications.tex` - Research publications structure
- `skills.tex` - Technical skills and competencies
- `misc.tex` - Awards and achievements
- `referee.tex` - References placeholder
- `referee-full.tex` - Detailed references
- `own-bib.bib` - Bibliography database
- `photo.jpg` - Profile photo
- `google-scholar.pdf` - Google Scholar profile

## Compilation

This CV is built using the `curve` document class and requires the following:

### Prerequisites

- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- XeLaTeX or LuaLaTeX (recommended) or pdfLaTeX
- Required packages: `academicons`, `fontawesome5`, `biblatex`, `cochineal`, `cabin`, `zi4`

### Building the CV

To compile the CV, run:

```bash
xelatex cv-llt.tex
biber cv-llt
xelatex cv-llt.tex
xelatex cv-llt.tex
```

Or with pdfLaTeX:

```bash
pdflatex cv-llt.tex
biber cv-llt
pdflatex cv-llt.tex
pdflatex cv-llt.tex
```

### Using a Build Tool

With latexmk:

```bash
latexmk -xelatex cv-llt.tex
```

## Customization

- **Colors**: Modify color definitions in `settings.sty` or uncomment color customization in `cv-llt.tex`
- **Fonts**: Change font packages in `cv-llt.tex` (lines 37-49)
- **Margins**: Uncomment and adjust geometry settings in `cv-llt.tex` (line 52)
- **Photo**: Toggle photo display by commenting/uncommenting lines 62-63 in `cv-llt.tex`

## Template Credit

This CV template is based on the work of LianTze Lim (liantze@gmail.com), October 2022.

## License

Personal CV document. Please contact the author for permission before using this template structure.
