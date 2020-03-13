all: sample

sample: sample.cc
	mkdir bin
	g++ -o bin/$@ $<  -lleveldb -lpthread -lsnappy

clean:
	rm -f sample