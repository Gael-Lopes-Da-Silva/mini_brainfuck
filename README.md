<div align="center">
	<h1>Tiny Brainfuck</h1>
    <a href="https://github.com/Gael-Lopes-Da-Silva/tiny.brainfuck">https://github.com/Gael-Lopes-Da-Silva/tiny.brainfuck</a>
</div>


Description
------------------------------------------------------------------

This is my own implementation of an interpreter for the [brainfuck](https://en.wikipedia.org/wiki/Brainfuck) programming language in Rust.


Usage
------------------------------------------------------------------

~~~
USAGE: mini_brainfuck --file <filename>

  -f, --file       Open a file and interpret it's content
  -i, --interpret  Interpret a given input
  -d, --debug      Print a debug output of the interpreted input
  -t, --tape       Print the tape after the interpretation of the input
  -v, --version    Print the interpreter version
~~~


Build From Source
------------------------------------------------------------------

Make sure to have a ready to use installation of rust. More info [here](https://www.rust-lang.org/tools/install).

~~~
git clone https://github.com/Gael-Lopes-Da-Silva/tiny.brainfuck.git
cd tiny.brainfuck
cargo build --release
~~~
