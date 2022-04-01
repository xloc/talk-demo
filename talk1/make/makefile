all: eg.o foo.o
	cc eg.o foo.o

eg.o: eg.c
	cc -c -o eg.o eg.c

foo.o: foo.c
	cc -c -o foo.o foo.c

clean:
	rm -f *.o
	rm -f a.out
