UCLResearchNoteStyle
====================

Latex style file to compile research note documents according to the guidelines of the University College London, Computer Science Department: 
http://www.cs.ucl.ac.uk/research/research_notes/

This is the Latex equivalent of:
http://www.cs.ucl.ac.uk/fileadmin/UCL-CS/research/Research_Student_Information/RNCoverpage.doc


this style file includes (and therefore depends on) the following packages:
- textpos    http://www.ctan.org/pkg/textpos
- xcolor     http://www.ctan.org/pkg/xcolor
- fancyhdr   http://www.ctan.org/pkg/fancyhdr
- graphicx   http://www.ctan.org/pkg/graphicx


usage:

- copy uclrn.sty and ucl.jpg in your document directory or in one of the default latex stayle directories

- add \usepackage{uclrn} at the beginning of your document

- define the number of your research note with the variable \rnnumber{XX/XX} 


Note:
This was tested only with pdfLatex on Ubuntu 12.10.
