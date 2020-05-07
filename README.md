# MaltaCV: Modern CV LaTeX template

This is the source code of my CV, inspired by the [AltaCV](https://github.com/liantze/AltaCV) template.

The name is just Manciukic + AltaCV.


## Requirements and Compilation
I've tested it on my Fedora 32 laptop.
This section is copied from AltaCV.


* pdflatex + biber + pdflatex
* AltaCV uses [`fontawesome`](http://www.ctan.org/pkg/fontawesome) and [`academicons`](http://www.ctan.org/pkg/academicons); they're included in both TeX Live 2016 and MikTeX 2.9.
* Loading `academicons` is optional: enable it by adding the `academicons` option to `\documentclass`.
* Use the `normalphoto` option to get a normal (i.e. non-circular) photo.
* Use the `ragged2d` option to activate hyphenations while keeping text left-justified; line endings will thus be less jagged and more aesthetically pleasing.
* Can now be compiled with pdflatex, XeLaTeX and LuaLaTeX!
* However, if you're using `academicons`, you _must_ use either XeLaTeX or LuaLaTeX. If the doc then compiles but the icons don't show up in the output PDF, try compiling with LuaLaTeX instead.
