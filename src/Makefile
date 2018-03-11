#
# Makefile for haskell
#

CC = ghc
RM = rm

CRUFT = $(wildcard *~ *.hi *.o intro)

all: intro

intro: intro.hs
	$(CC) -o intro intro.hs

.PHONY: clean
clean:
	$(RM) -- ${CRUFT}
