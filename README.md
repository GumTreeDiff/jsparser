# jsparser

`jsparser` is a JS tool that produces a GumTree compatible JS AST. It uses the awesome `acorn` module under the hood.

## Installation

`jsparser` requires nodejs. To install it, just clone the repository and install the dependencies using

~~~
npm install
~~~~

`jsparser` can be used as a standalone tool like this:

~~~
jsparser /path/to/script.py
~~~~

If you plan to use it with gumtree, you need to put `jsparser` in your system's path.