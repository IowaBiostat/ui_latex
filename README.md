# UI Beamer/LaTeX slides 

Here is a template for creating [Beamer slides](https://www.overleaf.com/learn/latex/Beamer) that are consistent with the University of Iowa [brand manual colors](https://brand.uiowa.edu/color). There is a version for Overleaf (or other LaTeX editor) in `main.tex`, and there is an R markdown version in `ui_beamer.Rmd` -- both of these create Beamer slides. 

My LaTeX shortcuts are included at the top of the `preamble.tex/md` files -- these shortcuts are specific to statistical notation. Of course, you could modify these however you'd like. 

Special thanks to my advisor [Patrick Breheny](https://github.com/pbreheny/pb-latex) and [Javi Flores](https://scholar.google.com/citations?user=KWz0HccAAAAJ&hl=en) for sharing their templates with me in years past. My template has taken some elements from both of theirs. 

The PDFs contain minimal examples of the 'final products' of these templates. 

## Details for Overleaf users
What you need to upload to your project for the UI slides to work are: 

(1) The `beamercolorthemeuiowa.sty` file 

(2) The `preamble.tex` file 

(3) The `main.tex` file - use this to replace the file created by default in Overleaf. There is formatting at the top of `main.tex` that you'll probably want to keep, so just use this like a template to fill in. 

(4) The `IOWA-logo.png` file

## Details for R markdown users 
What you need to create UI Beamer slides in R markdown (this is my favorite approach):

(1) The `beamercolorthemeuiowa.sty` file 

(2) The `preamble.tex` file 

(3) The The `IOWA-logo.png` file

(4) Optional: the `.bib` file

The `ui_beamer.Rmd` file provides a template that incorporates all the elements you need to make a presentation. You can toggle/tweak the options to suit your preferences. 

## Details for Obsidian users 
On a tangentially related note: Obsidian users can now incorporate LaTeX preambles into their note taking vaults, making shortcuts accessible for notetaking. Follow the instructions given on [this repo README](https://github.com/RyotaUshio/obsidian-mathjax-preamble-manager), and get started by writing your shortcuts in the format shown in `preamble.md`. 
