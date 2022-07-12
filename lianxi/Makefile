test:exp1.o exp2.o
	gcc -o test exp1.o exp2.o
exp1.o:exp1.c test.h
	gcc -c exp1.c
exp2.o:exp2.c test.h
	gcc -c exp2.c
clean:
	rm -rf test
	rm -rf *.o

