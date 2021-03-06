ASCII art to Unicode converter
==============================

Hackage Link: [https://hackage.haskell.org/package/ascii-art-to-unicode](https://hackage.haskell.org/package/ascii-art-to-unicode)

Small CLI program to convert ASCII box drawings to unicode. Inspired
by [svgbob](https://github.com/ivanceras/svgbobrus)
and
[The Monads Hidden Behind Every Zipper](http://blog.sigfpe.com/2007/01/monads-hidden-behind-every-zipper.html).

![Screenshot](./screenshot.png)

### Usage:

```bash
aa2u > outfile  # Reads from stdin
aa2u < infile   # Prints to stdout
aa2u infile     # Input file as argument works as well
aa2u < infile > outfile  # Convert a file
```
