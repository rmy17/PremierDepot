sources=carre.cpp
objets=$(sources:.cpp=.o)


CourbeCarre:$(objets)
	g++ -l QtGui -l QtCore -L /net/cremi/rviannais/espaces/travail/ProjLog/makefile/qcustomplot/sharedlib/compilation -l qcustomplot $^ -o $@


carre.o:carre.cpp 
	g++ -I /usr/include/qt4/ -I /usr/include/qt4/QtGui -I /usr/include/qt4/QtCore -I /net/cremi/rviannais/espaces/travail/ProjLog/makefile/qcustomplot -c $^ -o $@

clean :
	rm -f *~ *.o
