# Advent of Code [YEAR]
C++ solutions for [Advent of Code [YEAR]](https://adventofcode.com/[YEAR]).

## Build All
```bash
rm -rf ./build      # clean up previous build
cmake -B build -S .
cmake --build build --config Release
```

## Build Specific
```bash
rm -rf ./build      # clean up previous build
cmake -B build -S .
cmake --build build --config Release --target day01
```
