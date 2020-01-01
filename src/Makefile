
output: main.o TestObject.o
	g++ main.o TestObject.o -o output

main.o: main.cpp
	g++ -c main.cpp

TestObject.o: TestObject.cpp TestObject.h
	g++ -c TestObject.cpp

clean:
	rm *.o output