
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%
%%                              Latex2e package for 
%%                Journal of Space Qeather and Space Climate (SWSC)
%%
%%      This package was tested on MikTex 2.9 and TexLive 2009 with both 
%%      bibliography options (Jurgen Watermann, 26/01/2016)
%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%
%%                              swsc.tex
%%                             ==========
%%                                                          
%%      SWSC LaTeX class for Journal of Space Weather and Space Climate
%%
%%      This file was derived from aa.dem
%%      AA vers. 7.0, LaTeX class for Astronomy & Astrophysics
%%      demonstration file
%%                                      (c) Springer-Verlag HD
%%                                      revised by EDP Sciences
%%                                      further revised by J. Watermann 
%%
%%      Adapted to the Journal of Space Weather and Space Climate (SWSC)
%%      by Jurgen Watermann, Editorial Advisor to SWSC
%%
%%      01-04-2012 original version
%%      02-04-2012 revision 1
%%      12-07-2012 revision 2
%%      06-12-2012 revision 3 
%%      01-01-2014 revision 4
%%      05-03-2016 revision 5
%%      11-05-2018 revision 6  (equations and figure captions line numbered)
%%
%%      The two sub-figures referenced in the swsc.tex template are of eps and 
%%      png type, respectively, in order to demonstrate the usepackages 
%%      {subfigure} and {epstopdf} and thus create pdf-only output 
%%
%%      If you want to use TexLive or MikTex together with a bibtex bibliography 
%%      file you may run Latex2e from the command line with the set of commands

%%          pdflatex -shell-escape swsc.tex
%%          bibtex swsc (do not include the extension .tex)
%%          pdflatex -shell-escape swsc.tex
%%          pdflatex -shell-escape swsc.tex
%%
%%      A double call to pdflatex after calling bibtex is necessary in order to
%%      set citations and references correctly and insure that foreward/backward  
%%      linkage (backref option) is properly applied
%%      If you use MikTex you may need to issue a triple call to pdflatex
%%
%%      If you are using TexLive or MikTex but not a bibtex type of bibliography
%%      you may simply run Latex2e twice from the command line 
%%          pdflatex -shell-escape swsc.tex
%%          pdflatex -shell-escape swsc.tex
%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%
%%                              swsc.cls
%%                             ==========
%%
%%      The swsc.cls class file was derived from aa.cls
%%      A&A DOCUMENT CLASS -- version 7.0 for Latex2e
%%
%%      LaTeX document class for Astronomy and Astrophysics journal
%%
%%      modified for the Journal of Space Weather and Space Climate
%%      by Jurgen Watermann, Editorial Advisor to SWSC
%%
%%      01-04-2012 original version
%%      02-04-2012 revision 1   (bug fixes)
%%	    02-10-2012 revision 2   (typo fix)
%%	    02-01-2014 revision 3 
%%      04-11-2014 revision 3.1 (license update)
%%      06-06-2015 revision 4   (journal abbreviation update)
%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%
%%                              swsc.bst
%%                             ==========
%%
%%      SWSC referencing style for use with bibtex (requires usepackage natbib)
%%
%%      swsc.bst was generated with the docstrip utility
%%      The original source files was merlin.mbs 
%%      (with options `ay,nat,nm-rev1,jnrlst,keyxyr,yr-com,note-yr,
%%                     trnum-it,volp-com,pgsep-c,num-xser,btit-rm,bt-rm,isbn,
%%                     url-doi,ppx,ed,abr,xedn,jabr,and-com,revdata,eprint,url,
%%                     url-blk,nfss,')
%%
%%      Built for the Journal of Space Weather and Space Climate (SWSC)
%%      by Jurgen Watermann, Editorial Advisor to SWSC
%%      using the makebst tool (Copyright 1994-2007 Patrick W Daly)
%%
%%      SWSC referencing style for use with bibtex 
%%
%%      01-01-2014 original version
%%      30-01-2014 revision 1 
%%      05-03-2014 revision 2 
%%      11-05-2018 revision 3  (year placed between author and title)
%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

