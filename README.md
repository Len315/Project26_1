# Project26_1

This project implements a simple Unix utility for reversing the order of lines in a file.

## Build
```bash
make
```

# reverse.c

Description:
Prints the contents of one or more text files in reverse order to standard output.

Case 1, no arguments:
```bash
./reverse
  one
  two
  three
```
Result:
```
  three
  two
  one
```

Case 2, one input file:
```bash
./reverse input.txt
```
Result:
```
third line
second line
first line
```

Case 3, two input files:
```bash
./reverse input.txt output.txt
```
Result:
Reads input.txt and writes the reversed lines to output.txt

Example:
```bash
make
./reverse tests/8.in
./test-reverse.sh
```

### Edge cases / Error handling
Run the provided test suite:
```bash
./test-reverse.sh
```
