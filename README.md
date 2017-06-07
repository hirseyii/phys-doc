# phys-doc
University of Manchester undergraduate physics notes document
=================================================================

Please ONLY commit .tex, .jpg, .png, (etc). No auxiliary files.

This document is designed to be a comprehensive summary of the 
University of Manchester undergraduate physics syllabus 2015-2018.

The master-doc.tex file will import and compile individual volumes.
Each volume will be comprised of individual chapters. These chapters
should be edited in isolation of each volume.


Please comment all code and make use of whitespace for readability
===================================================================
Yes, even in TeX. 


A note on structure
===================================================================
Each volume is split into volumes and volumes call individual
chapter files using the \include command. Note that \include cmmds
CANNOT be nested, so don't do it.
All formatting is handled by the parent file hence, chapters should
only contain text and no global formatting. Commands and custom
environments should carry through as well.

Do not give your files names like "chapter_01.tex" or 
"figure_03.png", i. e. try to avoid using numbers in file-names: 
if the numbering LaTeX gives them automatically, is different from 
the one you gave (and this will likely happen) you will get confused.

For more info see https://en.wikibooks.org/wiki/LaTeX/Modular_Documents
