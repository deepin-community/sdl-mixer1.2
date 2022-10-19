# Makefile for playmus and playwave

CC = gcc
CFLAGS = -Wall -O
LIBS = -I/usr/include/SDL -lSDL_mixer
EXE = playmus playwave

all: $(EXE)

playmus: playmus.c Makefile
	$(CC) -o $@ $@.c $(CFLAGS) $(LIBS)

playwave: playwave.c Makefile
	$(CC) -o $@ $@.c $(CFLAGS) $(LIBS)

clean:
	-rm *.o $(EXE)
