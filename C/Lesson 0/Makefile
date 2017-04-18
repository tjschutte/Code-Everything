# compiler
CXX = gcc
# compiler flags
CXXFLAGS = -g -Wall -Werror

all: main

main: main.c
	$(CXX) $(CXXFLAGS) main.c -o $@

clean:
	rm -f core *.o main
