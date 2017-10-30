
texfile := Publication_List
default: pdf

pdf:
	latex ${texfile}
	dvips -t letter ${texfile} -o ${texfile}.ps
	ps2pdf ${texfile}.ps

clean:
	rm -f \
	${texfile}.dvi
	${texfile}.ps \
	${texfile}.pdf \
	${texfile}.aux \
	${texfile}.bbl \
	${texfile}.blg \
	${texfile}.toc \
	${texfile}.log
