CC=g++
CFLAGS=-c -Wall -g -std=c++11
LDFLAGS=
SOURCES=pandigitalProducts.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=answer

all: $(SOURCES) $(EXECUTABLE)

$(EXECUTABLE): $(OBJECTS)
	$(CC) $(LDFLAGS) $(OBJECTS) -o $@

.cpp.o:
	$(CC) $(CFLAGS) $< -o $@

clean:
	-rm $(EXECUTABLE) *.o
