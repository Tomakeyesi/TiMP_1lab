CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra
TARGET = modAlphaCipher
SOURCES = main.cpp modAlphaCipher.cpp
HEADERS = modAlphaCipher.h

all: $(TARGET)

$(TARGET): $(SOURCES) $(HEADERS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SOURCES)

clean:
	rm -f $(TARGET) *.o

run: $(TARGET)
	./$(TARGET)

.PHONY: all clean run
