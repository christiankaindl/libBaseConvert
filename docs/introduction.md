# Introduction to bases

In short, bases tell you in which numeric representation you want a value to be represented. *Value* is the important part here.

In long, let's deep right in ↓

## Numbers are a representation

![twelve dots.svg.png](https://draftin.com:443/images/54728?token=-ZMRhYE0Bx3-XfCVscx85QNm1PHH9qKVqjrnvZBhia02r-gC0rmKzHbFNhJFWEzCYH2zUgjXKAGlbh8z8pE4DMM)

How many dots are in the picture above? "12!", you now say, but that is not the only possibility. In most cultures today the base 10 (decimal) is used for numbers. That means there are 10 digits (0-9) and after the tenth digit we flip to 1 again and add a 0 to express the new value. So how can a 1 and 0 be more than a 9? That's because of decimal places.

The "1" from 10 is not actually 1 but rather represents a value (10 in this case). That is an important note: Any number we write only represents a value, that is whatever you want to count (sheep for example). With that in mind, we can now change how we represent a value. For example in hexadecimal (base 16):

**2A<sub>16</sub>**

The 2 represents (in this case) 32 (2*16) and the A represents 10 (10*1). Added together this results is 42 (in base 10). Note that the small number 16 that is written after the number is a *subscript*[] indicating the base that the number is meant to be interpreted in. If no subscript is provided a after a number it is assumed that it is a base 10 (decimal) number. The reason for that is that base 10 is base system that most human beings on the world have decided to act upon, so they can better work together and easily understand each others work.

Also, notice how we translate "A" to 10. That is because in base 16 (hexadecimal) there are 16 digits. In base 10 there are only 10 digits (0-9), in base 2 are 2 (0 and 1) and so on. So in order to write a number in a base system higher then 10, we need more digits. To get these, and to not invent new symbols, in general characters from the alphabet are used. The alphabet characters just extend the symbols 0-9 and make them go on: A=10, B=11, C=12, and so on.

This is also why libBaseConvert currently only converts up to base 36; 10 digits + 26 letters (used as digits). For anything greater than base 36 we would have to find new suitable symbols to use for number representation.


## Bases are important

There are a number (:P) of reasons why different bases exist and why we are using them. Here's a small overview of some of them

**Electronics**
Computers use, at their lowest level, base two systems to process data. This is due to a restriction in the hardware, e.g. logic gates are either on or off; nothing in-between.

**Encryption and storage**
Some encryption and also storage devices use higher base systems, such as base 16, because it allows you to save much more data at less length! Compare 10000000<sub>2</sub> to 8011<sub>16</sub>. They are the same. The latter one is just much shorter.

**It's fun**
Simple and plain, it's worth playing around with. And getting your head to think in other base systems is also cool. Ah, and finding patterns in conversions to other base systems is even more fun! Take the number 100 for example. Now, interpret this number in various base systems and check the results!

Play around with it. If you want more examples, check out the [patterns page]()

**Cultures**
Different cultures have historically counted in different base systems. It is a mere coincident that our western culture uses the base 10 notation. Other cultures have used base 12 which can be used to count to a _thousand_ only using one hand!

And if you've wondered how it would be to count and grow up in a completely different base notation, in your daily life, most things would be the same. If you want to find out why, check out the [being in a different base page]().

---

That's it for this introduction :)
If you're still awesome and want to know more, stay tuned and make a little search with your search engine, there are lots of good resources out there!

Happy converting!
