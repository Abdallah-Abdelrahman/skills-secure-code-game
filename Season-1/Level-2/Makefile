# Purpose: Makefile for hack.c and test.c
.PHONY:  clean

hack: hack.c code.h
	cc hack.c -o hack
	./hack
tests: tests.c code.h
	cc tests.c -o tests
	./tests
clean:
	$(RM) hack
	$(RM) tests
