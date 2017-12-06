test_world_sample:hello_world_sample.o
	g++ -o test_world_sample hello_world_sample.o /usr/local/lib/libcaf_core.so

hello_world_sample.o:hello_world_sample.cpp
	g++ -c -std=c++11 hello_world_sample.cpp

PHYON:clean
clean:
	rm *.out *.o
    