# CV sources (English and Chinese)

The PDFs on the CV page are built from these files.

- `cv-en.tex`, `cv-zh.tex`: CV content (edit these for education, grants, awards, ...)
- `cvstyle.sty`: shared layout, colours and fonts
- `fonts/`: Source Serif 4 and Source Sans 3 (SIL Open Font License)
- Publications are generated automatically from `../_data/publications.yml`,
  the same file the Publications page uses.

Build (needs XeLaTeX with xeCJK and the Noto CJK SC fonts):

    cd _cv_src
    python3 build.py

This writes `../files/Jidu_Yu_CV.pdf` and `../files/Jidu_Yu_CV_zh.pdf`.
