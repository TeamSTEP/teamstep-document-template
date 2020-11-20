# Team STEP Document Template

This is a LaTex template used for dev logs, research papers, and white papers for Team STEP.

This template is based on the [EPEL Report Template](https://www.overleaf.com/latex/templates/epfl-report-template/kykfrsqrjtxh) made by Todd C. Harris under the Creative Commons license.
All credit goes to the original creator.

## Usage

Most of the settings are done inside the `Preamble.sty` file and the `main.tex` file.

The `main.tex` file is the entry point, and all the chapters are declared in that file.
All the important document content will be inside the `chapters/` folder.
You can add or modify the chapters, but for every file name changes, you will need to reference them inside the `main.tex` by adding the following snippet.

```tex
\chapter{chapter-name}
\subfile{chapters/file-name}
```
