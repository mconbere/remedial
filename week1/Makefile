CXXFLAGS += -std=c++11 -stdlib=libc++
LDFLAGS += -lc++

all: main

main: main.o

main.o: main.cc sort.h vector.h

.PHONY: clean
clean:
	-rm -rf *.o main
