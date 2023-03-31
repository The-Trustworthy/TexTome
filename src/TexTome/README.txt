# TexTome LaTeX Template

### A report template developed by Ravi Prakash (https://raviprakash.cf), inspired from "Report Template V1.0" at overleaf


Thank you for choosing the TexTome LaTeX template! This template was designed with the specific needs of research and computer science in mind, but it can be easily adapted for any course or project.

Getting Started
To get started, please read through this file to optimize your usage of this template.

The template consists of several files that aim to create an organized and aesthetically pleasing report while maintaining user-friendliness.

main.tex: loads all the .tex files for the preamble, title page, and different sections. It also adds a Table of Contents, bibliography, and appendices.
General folder: allows you to add packages to the Preamble.tex and add references in the References.bib files. The Settings.tex file contains all the predefined formatting, including the title, subtitle, authors, and more for the front page. If anything is not to your liking, you can edit it in this file. Comments are used to explain everything, but a decent understanding of LaTeX is advised if you desire to change anything. In this file, you will find a comment stating that the code after a certain line is not essential. You can remove all the code from there onward to (pretty much) revert to default LaTeX behavior.
Chapters folder: contains a .tex file for each chapter, numbered to remain in the same order for easier navigation. To add a chapter, simply add a .tex file and name it x.<title>.tex, where x is the chapter number (for chapters) or letter (for appendices) and <title> is any name you like. Don't forget to add the chapter in the main.tex file using:
latex

```
Copy code
\input{Chapters/x.<title>.tex}
\newpage
```

A few chapters are already predefined based on the writing manual. There is a front page, list of symbols, introduction, and appendix entry template. Other chapters can also be added by copying and renaming the 2. Copy me.tex file. Finally, the Z. Template.tex contains inspiration for formatting tables, images, text citations, etc. It also serves to preview the template. You can use it as a reference or delete it.

Figures folder: allows you to put figures for use in the report. Make sure to always reference figures using \includegraphics{Figures/x.<title>/figurename}, where x.<title> is the subfolder the image is located in. The 0. General folder contains figures used for creating the template. Moving or removing this folder is not recommended.
Contributing
Please feel free to contribute to this template by submitting a pull request. If you have any issues or feature requests, please submit them to the Issues section of this repository.

Credits
This template was created by modifying a suggestion from ChatGPT. Thank you, ChatGPT, for your contribution!

License
This template is licensed under the MIT License.