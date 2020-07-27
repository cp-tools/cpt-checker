
PROGRAMS = $(basename $(wildcard *.cpp))

.PHONY: all
all: $(PROGRAMS)
$(PROGRAMS):
	g++ -std=c++11 -Os -o $@ $@.cpp
