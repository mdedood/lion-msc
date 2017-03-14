The lion-msc thesis class
*********************

This class file is intended for B.Sc. and M.Sc. students stuyding physics 
at Leiden University, i.e. at the Leiden Institute of Physics (LION).

The purpose of this class is twofold: It creates a uniform layout of the
student theses from our department. More importantly it contains several
fields on the front-page that the user needs to fill that are used in the
university administration (name, student number and name of supervisor)

The complete documentation is provided in lion-msc.pdf. 

**  to generate the documentation yourself, run york-thesis.dtx through pdflatex 

** $ latex york-thesis.dtx

The minimal.tex file is an empty template. 


author: Michiel de Dood <dood@physics.leidenuniv.nl>

Copyright (C) 2014-16 by M.J.A. de Dood
-------------------------------------------------------

This file may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in:

    http://www.latex-project.org/lppl.txt

and version 1.3 or later is part of all distributions of LaTeX 
version 2003/06/01 or later.

This work has the LPPL maintenance status "author-maintained".

---------------------------------------------------------

Known Issues and bugs

- Cannot pass options 10pt and 11pt from the \documentclass in the main tex file.
- Several ideas to make things more beautiful thanks to Casper Remeijer