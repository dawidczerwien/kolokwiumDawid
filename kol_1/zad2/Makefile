all: myProgram

myProgram: main.o employee.o address.o
	g++ main.o employee.o address.o -o myProgram
main.o:
	g++ -c main.cpp
employee.o:
	g++ -c employee.cpp
address.o:
	g++ -c address.cpp
clean:
	rm -rf *.o myProgram
