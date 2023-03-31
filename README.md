# TexTome
A Template for `LaTeX` Reports

![banner](./assets/banner.jpg)  


This LaTeX report template was created with research and technical write-ups in mind. It can be adopted to work for any course or project, but specific care was put into creating this template in accordance with the writing manual of 20 March 2018 that is used for DBL projects (as of 2022).

## Contents

This documentation covers following topics:  

- [Getting Started](#getting-started)
  + [Template Structure](#template-structure)
  + [Usage](#usage)
  + [Adding Chapters](#adding-chapters)
  + [Preview](#preview)
- [Contribution](#contribution)
- [License](#license)

## Getting Started

The name **"TexTome"** _"TeX,"_ which is the markup language used in LaTeX, and _"Tome,"_ which means a large and scholarly book. It has a catchy and memorable sound to it, and it also hints at the professional and academic nature of the template. The name is a result of an edited suggestion by [ChatGPT](https://chat.openai.com/chat).To get started with this template, read through this file to optimize your usage of the template.

### Template Structure

The following files are included in the template:

- `main.tex`: This file loads all the `.tex` files for the preamble, title page, and different sections. It also adds a Table of Contents, bibliography, and appendices.
- `General/Preamble.tex`: This file contains packages that can be added to the preamble of the report, and `General/References.bib` contains the references for the report.
- `General/Settings.tex`: This file contains all the predefined formatting, including the title, subtitle, and authors for the front page.
- `Chapters/`: This folder contains `.tex` files for each chapter. Each file is numbered, and the file name is in the format `x <title>.tex`, where `x` is the chapter number (for chapters) or letter (for appendices) and `<title>` is any name you like.
- `Figures/`: This folder contains figures that can be used in the report. Always reference figures using `\includegraphics{Figures/<title>/figurename}`, where `<title>` is the subfolder where the image is located.

### Usage

To use this template, follow these steps:

1. Clone the repository or download the files.
2. Add your own content to the relevant files.
3. Customize the formatting in `Settings.tex` to your liking.
4. Compile the report using your preferred `LaTeX` compiler.

### Adding Chapters

To add a chapter, create a new `.tex` file in the `Chapters/` folder and name it `x.<title>.tex`, where `x` is the chapter number (for chapters) or letter (for appendices) and `<title>` is any name you like. Don't forget to add the chapter to the `main.tex` file using:

```latex
\input{Chapters/x.<title>.tex}
\newpage
``` 

### Preview

The `3 formatting.tex` file contains inspiration for formatting tables, images, text citations, etc. It also functions to preview the template. Feel free to use it as a reference or delete it.

## Contribution

Feel free to fork the repository and make changes to the template. Pull requests are welcome and you can contribute to the template by submitting a pull request. If you have any issues or feature requests, please submit them to the Issues section of this repository.

## License  

This template is licensed under the [Apache License](./LICENSE).
