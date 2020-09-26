SRC_FILES := $(wildcard *.cc)
H_FILES := $(wildcard *.h)
CXXFLAGS := -O3 -W -Wall -Wshadow -Wno-sign-compare -std=c++14
BIN := dynamic-submodular.exe

$(BIN): $(SRC_FILES) $(H_FILES)
	g++ $(CXXFLAGS) -o $@ $(SRC_FILES)

all: $(BIN)
