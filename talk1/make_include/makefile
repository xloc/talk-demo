DEPS = eg.o foo.o
INCLUDE_DIR = .


all: ${DEPS}
	cc ${DEPS}

%.o: %.c
	cc -c -o $@ $< -I${INCLUDE_DIR}

clean:
	rm -f *.o
	rm -f a.out