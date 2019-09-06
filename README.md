# otf2ttf

This script can convert fonts in OTF format (or any other format fontforge can read) into TTF. 

It requires [fontforge](https://fontforge.github.io/) to be installed. `otf2ttf` can be used either as a fontforge script (extended or in combination with others) or as an executable (run `chmod a+x otf2ttf` and ensure it's somewhere $PATH like). It will convert one or more fonts into TTF files in the current directory.

# usage

as a script `fontforge -script otf2ttf.pe FONT.otf` or standalone `otf2ttf FONT-*.otf`

# further

* [fontforge tutorial](https://fontforge.github.io/editexample.html)
* [Differences between LuaTeX, ConTeXt and XeTeX](https://tex.stackexchange.com/questions/36/differences-between-luatex-context-and-xetex)
