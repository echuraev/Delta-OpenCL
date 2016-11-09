SOURCES=*.cpp
TARGET=OpenCLImages
CXX_FLAGS=-g -std=c++11 -lOpenCL

.PHONY: all

all: $(TARGET)

$(TARGET): $(SOURCES)
		$(CXX) $^ $(CXX_FLAGS) -o $@

.PHONY: clean

clean:
		rm -vf $(TARGET)

