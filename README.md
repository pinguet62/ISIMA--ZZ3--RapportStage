RapportStageSopra
=================

Rapport de stage de 3ème année à Sopra Group


Compilation
	Makeindex : makeindex %.glo -t %.glg -s %.ist -o %.gls
	Compilation rapide : pdflatex -synctex=1 -interaction=nonstopmode %.tex|makeindex %.glo -t %.glg -s %.ist -o %.gls |pdflatex -synctex=1 -interaction=nonstopmode %.tex|"C:/Program Files (x86)/Adobe/Reader 11.0/Reader/AcroRd32.exe" %.pdf
		PdfLaTeX : pdflatex -synctex=1 -interaction=nonstopmode %.tex
		Makeindex : makeindex %.glo -t %.glg -s %.ist -o %.gls 
		PdfLaTeX : pdflatex -synctex=1 -interaction=nonstopmode %.tex
		Afficheur Pdf : "C:/Program Files (x86)/Adobe/Reader 11.0/Reader/AcroRd32.exe" %.pdf
