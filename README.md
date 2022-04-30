# My resume

Hire me :)

## Building LaTex

Option A
1. Create an account at [Overleaf](www.overleaf.com)
2. Create a new Blank project and copy/paste source from `resume.tex`

Option B
1. Clone repo
2. Install [texlive](https://www.tug.org/texlive/)
3. Install required packages
   1. On Debian/Ubuntu `sudo apt-get install texlive-latex-recommended texlive-latex-extra`
5. Execute `latex resume.tex` to build, then `xdvi resume.dvi &` to view
6. Execute `pdflatex resume.tex` to generate PDF

## Credit where it is due

The original tex file is from [dickwyn](https://github.com/dickwyn/resume)'s profile
