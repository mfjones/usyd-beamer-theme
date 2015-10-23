An unofficial [Beamer](https://en.wikipedia.org/wiki/Beamer_(LaTeX)) theme for the [University of Sydney](http://sydney.edu.au)'s latest redesign.

Move the `beamerthemeusyd.sty`, `usyd-logo.pdf`, and `usyd-logo.pdf_tex` to the root folder of your project. In the premable of your main `.tex` file, add

	\usetheme{usyd}
	...
	\titlegraphic{
			\def\svgwidth{0.55\columnwidth}
			\input{usyd-logo.pdf_tex}
	}

See `example.tex` for a reference file, and [`example.pdf`](https://github.com/mfjones/usyd-beamer-theme/blob/master/example.pdf) for the output. This example is compiled using the command `xelatex example.tex`.

Make sure you have the font `Tw Cen MT` installed (this is the main font used by the theme). Depending on the location of the installed font, the path may need to be modified (line 14 of `beamerthemeusyd.sty`). Or, if it can't find the font and you already have it installed, try removing the `Path=...` in the `beamerthemeusyd.sty` file and let XeLaTeX find it automatically.

This theme is based off Cameron Bracken's theme, originally posted here: [cameron.bracken.bz/beamer-template](http://cameron.bracken.bz/beamer-template).
