Move DOF
========

This is a utility to facilitate swapping DOFs around on the Xitome MDS robot.

It's unlikely that you have an MDS robot, so it's unlikely that you'll find this useful, but hey, I've been wrong before (once).

## Dependencies
* docopt (https://github.com/docopt/docopt) - sudo pip install docopt==0.6.1
* Python 2.7

## Usage
```
> ./moveDof -h

Usage:
  moveDof list <address>
  moveDof backup <address> [--output-file=<of> | -o <of>]
  moveDof restore <address> (--input-file=<if> | -i <if>)
  moveDof move <from-address> <to-address> [--output-file=<of> | -o <of>]
  moveDof swap <a-address> <b-address>
  moveDof (-h | --help)

Options:
  -h --help                   Show this screen.
  -o <of> --output-file=<of>  Store the parameters in a file, default is stdout.
  -i <if> --input-file=<if>   Load the parameters from a file into a DOF.
```

## License
(http://opensource.org/licenses/MIT)
The MIT License (MIT)

Copyright (c) 2013 M@ Dunlap

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.