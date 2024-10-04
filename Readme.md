# Dissertation Report Template, SVNIT

The dissertation report template for SVNIT is written in simple latex, without creating horrendous classes or styles. 

To get started, open the `details.tex` in `metadata` folder and edit the values of your title, name etc. If you have an external supervisor, add the certificate of completion provided by them in `assets` folder and rename it to `external_certificate.pdf`. If you don't have an external supervisor, comment out the line `\ExternalSupervisor` in the `details.tex` file.

> [!WARNING]
> Do not touch `THESIS.tex` or any files in `preamble` folder if you don't know what you are doing.

You can add your own `\usepackage` statements to `usepackages.tex` and also your own `\newcommand` or `\def` statements to `defintions.tex` file in the `metadata` folder.

Further, add your acknowledgement and abstract to their respective `.tex` files in the `metadata` folder.

Create your thesis chapters in the folder `Chapters` in the form of `chapter#.tex` (i.e. `chapter1.tex`, `chapter2.tex`, ... ). Please stick to the naming convention. Set the `\numChapters` in the details.tex to the number of chapters. (Adding \newpage at the beginning and end of all the chapter#.tex files is suggested).

If you have appendices, create `appendix#.tex` files in the folder `Appendix`, i.e `appendix1.tex`, `appendix2.tex`, ... and set the `\numAppendix` in the `details.tex` to the number of appendices. If you don't have any appendices, set `\numAppendix` to 0.

Add your references as bibtex entries to the `references.bib` file in `metadata` folder.

> [!IMPORTANT]
> You need to set your LaTeX compiler to LuaLaTex to compile the thesis.
> If you are on overleaf, go to Menu on top left, and select LuaLaTeX in compiler.

After this compile the `THESIS.tex` file to get the final pdf.

> [!TIP]
> The theme for chapter titles is set by the `fncychap` package. Make changes [here](metadata/usepackages.tex#L19) to change the theme. To find what themes are available, [check this document](http://mirrors.ctan.org/macros/latex/contrib/fncychap/fncychap.pdf). To use the default LaTeX theme, comment out the line.
