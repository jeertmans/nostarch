# No Starch Press LaTeX Template, made simple

This repository is a minimal working example to build documents with the
*No Starch Press* LaTeX template class.

It provides free font
(not for commercial use, see [fonts/](./fonts/) directory) atlernatives
to the commercial ones.

## Prerequisites

To use this template, you have two options:

1. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
  this repository[^1] and make your have a `TexLive` distribution
  installed with XeLaTeX.
2. or [download](https://github.com/jeertmans/nostarch/archive/refs/heads/main.zip)
   this project as a `.zip` and import it on [Overleaf](https://www.overleaf.com/).

[^1]: or download it using the link below, it also works fine.

## Building locally

Building the document is as simple as invoking `latexmk` in a terminal.
It will run all the necessary commands to produce the `nssample.pdf` file.
