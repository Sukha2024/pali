Installation steps:

1. Copy gloss-pali.ldf to: /usr/share/texlive/texmf-dist/tex/latex/polyglossia/

2. Copy hyphenation patterns file to: /usr/share/texlive/texmf-dist/tex/generic/hyph-utf8/patterns/tex

3. Copy loadhyph-pli.tex to /usr/share/texlive/texmf-dist/tex/generic/hyph-utf8/loadhyph/

4. Update language.def, language.dat and ls-R files to contain relevant references to above new files.

5. Run fmutil-sys --all or fmutil-sys --byfmt xelatex