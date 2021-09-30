CC=gcc
BUILD_DIR=build
OBJECTS_DIR=objects
INCLUDE_DIR = include
LIBRARY_DIR = lib
STANDARD_LIBRARY=-lm

CFLAGS=-I.
DEPENDENCIES=f.h
OBJECTS = main.o a.o




../objects/%.o: %.c $(DEPENDENCIES)
	$(CC) -c -o $@ $< $(CFLAGS)

../build/andrzej: ../objects/$(OBJECTS)
	$(CC) -o $@ $^
	../build/./andrzej
run:
	