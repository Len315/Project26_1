# Project26_1
Koodin perus käyttö ohjeet ja vaihtoehdot

Case 1, no arguments:
  $ ./reverse
  one
  two
  three
  (EOF or ctrl+D)
Result: prints 
  three
  two
  one
to stdout

Case 2, one argument:
  $ ./reverse input.txt
Result: prints the input.txt lines in reverse order to stdout

Case 3, two arguments:
  $ ./reverse input.txt output.txt
Result: prints the input.txt lines in reverse order to output.txt

2. Esimerkki käytöstä
$ make
$ ./reverse 8.in.txt
$ ./test-wish.sh

4. Edge cases / error handling
run existing tests with command ./test-wish.sh
not capable for other errors
