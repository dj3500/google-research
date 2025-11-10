SRC_FILES := $(wildcard *.cc)
H_FILES := $(wildcard *.h)
CXXFLAGS := -O3 -W -Wall -Wshadow -Wno-unused-parameter -Wno-sign-compare -std=c++17
BIN := fair-submodular.exe

$(BIN): $(SRC_FILES) $(H_FILES)
		g++ $(CXXFLAGS) -o $@ $(SRC_FILES)

all: $(BIN)
