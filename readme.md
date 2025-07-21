# UI LaTeX templates

This repository contains templates for creating slides and posters that are consistent with the University of Iowa [brand manual colors](https://brand.uiowa.edu/color).

## Slides

This folder provides a [Beamer](https://www.overleaf.com/learn/latex/Beamer) template. It can be used to write slides directly in LaTeX, or using markdown through Pandoc (thereby also supporting `.rmd`/`.qmd` workflows).

Some custom shortcuts are included in `custom.tex`, but none of these are essential. They can be included, modified, or deleted according to your preferences.

Compiling `ui-beamer.tex` will produce `ui-beamer.pdf`.

If you prefer to compose in markdown (include R/Quarto variants), you can also render the `.qmd` file using

``` bash
quarto render beamer-ui.qmd
```

This works exactly the same in R markdown.

NOTE: This needs a little bit of work, should use a template.

## Poster

This folder currently includes the poster theme (`beamerthemegemini.sty`), color theme (`beamercolorthemeuiowa.sty`) and an example poster (`poster.tex`) that uses them. However, it is not yet a minimal, reproducible template -- `poster.tex` is a real poster example from ENAR 2025 rather than a clean starting point, and it references figures not included in the repository. As a result, compiling it directly will fail because you don't have the missing figures. However, it should illustrate what you need to do in order to get this working.

The final poster looks like this:

[![Poster Thumbnail](https://raw.githubusercontent.com/IowaBiostat/ui_latex/refs/heads/master/poster/thumb.webp)](poster/poster.pdf)

The poster is based on the [Gemini poster theme](https://github.com/anishathalye/gemini).

A proper, fully reproducible poster template is planned but still in development.

