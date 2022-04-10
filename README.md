# Crypto Arbitrage

This program analyses data from two different bitcoin exchanges looking for divergence in price that can be monetized. The program picks three days in a three month period and produces line graphs on prices and box graphs on arbitrage opportunites. Finally the program filters those trades that give a profit of less than 1% (assuming this is the trade cost) and computes the total potential income for each of those dates. 

---

## Technologies

This program is written in Python and it uses the following dictionaries: pandas, pathlib, matplotlib. 

## Installation Guide

You need to have Python and GitBash installed in your computer. You also need the libraries mentioned in the section above. 

## Contributors

This program was created using the help of the Columbia FinTech bootcamp TAs.

## License


[MIT License](https://en.wikipedia.org/wiki/MIT_License)

Copyright (c) 2022 daniel-lobster

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
