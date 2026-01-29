# Algebraic-Geometry-2026s1

Repository for sharing and working with algebraic geometry notes at University of Melbourne (Semester 1, 2026).

## Templates

This repository includes LaTeX templates for creating notes and presentations:

- `templates/note-template/note-template.tex` - Template for lecture notes
- `templates/beamer-template/beamer-template.tex` - Template for presentations (Beamer)

Each chapter folder already contains both templates with appropriate titles:
- `note.tex` - Notes template
- `slides.tex` - Beamer presentation template

## Usage

Each chapter folder contains pre-configured templates with the appropriate chapter titles. Simply edit the content directly in the chapter folder.

### Compile LaTeX files

```bash
pdflatex filename.tex
bibtex filename.aux  # if using bibliography
pdflatex filename.tex
pdflatex filename.tex
```

## Structure

```
.
├── README.md
├── templates/
│   ├── note-template/
│   └── beamer-template/
└── chapters/
    ├── ch0-polynomial-rings/
    ├── ch1-varieties-ideals/
    ├── ch2-irreducibility/
    ├── ch3-coordinate-rings/
    ├── ch4-polynomial-maps/
    ├── ch5-nullstellensatz/
    ├── ch6-dimension/
    ├── ch7-smoothness/
    ├── ch8-products/
    ├── ch9-projective-varieties/
    ├── ch10-maps-projective/
    ├── ch11-quasiprojective/
    └── ch12-culminating/
```

## Chapters
- Ch.0. Polynomial Rings (Prereading)
- Ch.1. Varieties and Ideals (week 1)
- Ch.2. Irreducibility of Affine Varieties (week 2)
- Ch.3. Coordinate Rings (week 3)
- Ch.4. Polynomial Maps  (week 4)
- Ch.5. Proof of the Nullstellensatz (week 5)
- Ch.6. Dimension (week 6)
- Ch.7. Smoothness  (week 7)
- Ch.8. Products (week 8)
- Ch.9. Projective Varieties  (week 9)
- Ch.10. Maps of Projective Varieties (week 10)
- Ch.11. Quasiprojective Varieties  (week 11)
- Ch.12. Culminating Topics  (week 12)



## Contributing

Feel free to add your notes, exercises, and solutions to this repository.