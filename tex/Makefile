doc.pdf: doc.ps
	ps2pdf doc.ps
doc.ps: doc.dvi
	dvips doc.dvi
doc.dvi: doc.tex
	latex doc.tex
	latex doc.tex

clean:
	rm doc.ps doc.dvi doc.pdf doc.aux doc.loc doc.toc
