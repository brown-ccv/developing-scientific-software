CXX = g++
CXXFLAGS = -Wall

fib:
	$(CXX) $(CXXFLAGS) fib.cpp -o fib 

install: fib
	mv fib /usr/bin

.PHONY: clean
clean:
	-rm fib
