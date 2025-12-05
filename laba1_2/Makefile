CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra
TARGET = routeCipher
SOURCES = main.cpp routeCipher.cpp
HEADERS = routeCipher.h

all: $(TARGET)

$(TARGET): $(SOURCES) $(HEADERS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SOURCES)

clean:
	rm -f $(TARGET) *.o

run: $(TARGET)
	./$(TARGET)

.PHONY: all clean run
