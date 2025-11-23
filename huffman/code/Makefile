CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra

TARGET = huffman
SRC = huffman.cpp

all: $(TARGET)

$(TARGET): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRC)

clean:
	rm -f $(TARGET)

.PHONY: all clean
