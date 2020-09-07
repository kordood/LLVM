CXX = clang
CXXFLAG = -O3
src = dep.c main.c
target = main

$(target): $(src)
	$(CXX) $(CXXFLAG) -o $@ $^

clean:
	rm *.o $(target)
