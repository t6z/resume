# My resume

Hire me :)

## Building LaTex

Option A
1. Create an account at [Overleaf](www.overleaf.com)
2. Create a new Blank project and copy/paste source from `main.tex`

Option B
1. Clone repo
2. Install [texlive](https://www.tug.org/texlive/)
3. Install required packages
   1. On Debian/Ubuntu `sudo apt-get install texlive-latex-recommended texlive-latex-extra`
5. Execute `latex main.tex` to build, then `xdvi main.dvi &` to view
6. Execute `pdflatex main.tex` to generate PDF
