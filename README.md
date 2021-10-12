# PorthDuck 🦆
A simple brainfuck interpreter written in porth.
Cells in PorthDuck are one byte long, but we can have *many* cells, which is always a good thing to have.
## Usage
```console
$ porth sim ./main.porth ',[.,]>++++++++++.' 'Hello, Github!'
PORTHDUCK INFO: finished parsing
Hello, World
```
PorthDuck accepts two arguments.
The first one is the brainfuck code to be interpreted, the second one is the input buffer from which the code can read.
## How To Run
For starters, you'll need to clone the [Porth](https://github.com/tsoding/porth) repository, or if you've already cloned it, pull the new changes.
(*I linked `porth/porth.py` into `/usr/local/bin` for convenience's sake, but you dont need to do that*)
And to finish it all off, you'll have to copy the standard library from [porth/std/](https://github.com/tsoding/porth/blob/master/std/) into porthduck/
Now, you're able to compile, or simulate porthduck on your machine (*hopefully* 😅)