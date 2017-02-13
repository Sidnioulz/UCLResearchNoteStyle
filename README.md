UCLResearchNoteStyle
====================

Latex style file to compile research note documents according to the guidelines of the University College London, Computer Science Department: 
http://www.cs.ucl.ac.uk/research/research_notes/

This is the Latex equivalent of:
http://www.cs.ucl.ac.uk/fileadmin/UCL-CS/research/Research_Student_Information/RNCoverpage.doc

This version is designed for use with the SIGCHI paper template. A minimal working example is provided.

This style file includes (and therefore depends on) the following packages, on top of the usual SIGCHI dependencies:
- textpos    http://www.ctan.org/pkg/textpos
- xcolor     http://www.ctan.org/pkg/xcolor
- fancyhdr   http://www.ctan.org/pkg/fancyhdr
- graphicx   http://www.ctan.org/pkg/graphicx


### Usage (easier):

- copy the content of your paper directly into sigchi-example.tex in the appropriate areas

### Usage (manual):

- copy uclrn.sty and ucl.pdf in your document directory or in one of the default latex stayle directories

- add \usepackage{uclrn} at the beginning of your document

- define the number of your research note with the variable \rnnumber{XX/XX}

- define the short title for the research note header with the variable \rntitle{...}

- define the full title for the research note title page with the variable \fulltitle{...}

- define the short author list for the research note header with the variable \rnauthor{...}

- define the full author list for the research note title page with the variable \fullauthor{...}
 
Note:
This was tested only with pdfLatex 3.14 on ArchLinux as of 2017-02-13.
