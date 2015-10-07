An unofficial [Beamer](https://en.wikipedia.org/wiki/Beamer_(LaTeX)) theme for the [University of Sydney](http://sydney.edu.au)'s latest redesign.

Move the `beamerthemeusyd.sty` and `usyd-logo.jpg` to the root folder of your project. In the premable of your main `.tex` file, add

	\usetheme{usyd}
	...
	\titlegraphic{
  		\includegraphics[width=6cm]{usyd-logo}
	}

See `example.tex` for a reference file, and `example.pdf` for the output.

Make sure you have the font `Tw Cen MT` installed (this is the main font used by the theme).

This theme is based off Cameron Bracken's theme, originally posted here: [cameron.bracken.bz/beamer-template](http://cameron.bracken.bz/beamer-template).
