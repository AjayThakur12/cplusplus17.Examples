CXX_FLAGS=-std=c++17
CXX=g++

inline-test: point.cpp main.cpp point.hpp header_only.hpp
	$(CXX) $(CXX_FLAGS) point.cpp main.cpp -o inline-test

clean:
	rm -f inline-test

all: inline-test
