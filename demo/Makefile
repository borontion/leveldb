all: sample

sample: sample.cc
	mkdir -p bin
	g++ -o bin/$@ $<  -lleveldb -lpthread -lsnappy

clean:
	rm -rf bin/