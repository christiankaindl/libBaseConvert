# libBaseConvert

This is a small library for simple base conversions.
Ever wondered what 42 is in hexadecimal? It's 2A. Not particularly interesting, but still cool.

libBaseConvert is written in JavaScript and lets you convert numbers between bases 2 (binary) up to 36. If you want to try it out in action, here's a simple web application that implements libBaseConvert: [Convert Bases](https://christiankaindl.github.io/base-converter/)

If you want to use libBaseConvert in your own project, it has an easy API as well. To convert any number in any of the supported bases use the in-built `convert` method:

`BaseConvert.convert(10, 16, 42)`

This converts the number 42 from base 10 to base 16 and returns the result ("2A" in this case).
Other APIs that libBaseConvert offers are

+ `BaseConvert.getNumberCharacter(number)` - takes a base ten number and returns its corresponding digit (e.g. 13 returns "D"). Returns `false` when there is no match
+ `BaseConvert.getDigitValue(digit)` - takes a digit and returns its value in base 10 (e.g. "D" returns 13)
+ `BaseConvert.validateNumber(number, base)` - takes a number and base and checks the number for correctness
+ `BaseConvert.digits` - array that containes all supported 36 digits

---
Released under the MIT license
