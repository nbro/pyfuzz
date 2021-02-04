# PyFuzz

[![Build Status](https://travis-ci.org/github/nbro/pyfuzz.svg?branch=master)](https://travis-ci.org/github/nbro/pyfuzz)

`pyfuzz` is a random program generator for python. It was developed to test the JIT compiler of Unladen Swallow.

Execute [`pgen_example.py`](./pgen_example.py) to generate a new random program and output it to stdout.

Execute [`pygen_example.py`](./pygen_example.py) to test a Python binary. You must specify a base and a test binary using the `-b` and `-t` command-line options.

The [`pygen`](./pygen) directory contains a module to represent a Python program as an object tree and transform it into a text representation.
