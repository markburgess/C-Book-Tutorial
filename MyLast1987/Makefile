#
# Simple build guide, requires texinfo 3.12c
#

all:
	tex *.texi
	texindex *.cp; 
	tex *.texi

clean: distclean

distclean:
	rm -f *.aux *.log *.cp *.vr *.ky *.pg *.toc *.tp *.fn *.dvi *.cps *~
