hello:hello.o
	$(CC) $(LDFLAGS) hello.o -o hello
hello.o:hello.cpp
	$(CC) $(CXXFLAGS) -c hello.c


# remove object files and executable when user executes "make clean"
clean:
	rm *.o hello



