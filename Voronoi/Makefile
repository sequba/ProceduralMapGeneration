CXX = g++
CXXFLAGS = -std=c++11 -pedantic -Wall -Wextra -Wformat -Wfloat-equal -W -Wreturn-type  -Wundef
LDLIBS =
TARGETS = 
 
all: main

main: Makefile Constants.o Sector.o Site.o Tile.o TileGrid.o TileGridGenerator.o
	$(CXX) $(CXXFLAGS) -o main *.o Main.cpp

clean:
	rm -f *.o

distclean: clean
	rm -f $(TARGETS)

real: distclean all
