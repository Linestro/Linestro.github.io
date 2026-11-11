# Resume

Editable LaTeX source for the public resume served at `../assets/Resume_HaojieYe.pdf`.

The source preserves the original A4, 12-point TeX Gyre Heros template, centered contact header, ruled sections, and numbered publication format.

Compile from this directory with a current TeX Live installation that includes Font Awesome 5, Fira, and Contour:

```sh
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

After reviewing the generated PDF, copy `main.pdf` to `../assets/Resume_HaojieYe.pdf`.

Alternatively, compile with Tectonic, which resolves the required packages automatically:

```sh
tectonic main.tex
```
