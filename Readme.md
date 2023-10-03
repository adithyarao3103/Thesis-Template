# Dissertation Report Template, SVNIT

The dissertation report template is written in simple latex, without creating horrendous classes or any stupid hell of codes. 

To get started, open the **metadata.tex** and edit the values of your title, name etc. You can add your own border by replacing the border.jpg file in **assets** folder (and rename the new file to border.jpg).

Further, add your acknowledgement and abstract to their respective .tex files in the **preamble** folder.

Create your thesis chapters in the folder **Chapters** in the form of chapter#.tex (i.e. chapter1.tex, chapter2.tex, ... ) please stick to the naming convention, and set the \numChapters in the metadata.tex to the number of chapters. (Adding \newpage at the beginning and end of all the chapter#.tex files is suggested).

Add your references as bibtex entries to the **references.bib** file.

After this compile the **THESIS.tex** file, you will have your thesis ready. 