# Repository guide #

This repository presents implementations of various algorithms in various programming languages (the [author](https://github.com/VitasSalvantes) mainly uses Java). You can suggest your own options for implementing existing examples (naming them in accordance with the samples) or new options in any programming language.

For quick access to the discription of the program and its implementation you can use the [list of all programs](#List-of-all-programs).

If you want to contribute to the development of the project, please visit the [wiki](https://github.com/VitasSalvantes/Simple-Examples/wiki).

## List of all programs ##

- [AmountOfSalaries](#AmountOfSalaries)
- [AtbashCipher](#AtbashCipher)
- [ArrayInitialization](#ArrayInitialization)
- [CaesarCipher](#CaesarCipher)
- [ChangingArrayType](#ChangingArrayType)
- [CodeWordCipher](#CodeWordCipher)
- [ConsoleCalc](#ConsoleCalc)
- [ExchangedValues](#ExchangedValues)
- [Factorial](#Factorial)
- [FibonacciNumbers](#FibonacciNumbers)
- [FizzBuzz](#FizzBuzz)
- [PerfectNumbers](#PerfectNumbers)
- [PrimeNumbers](#PrimeNumbers)
- [RecamanSequence](#RecamanSequence)

## AmountOfSalaries ##
[Here](AmountOfSalaries.java) you can see how the static method of summing salaries of two workers (instances of the same class) is implemented in Java.

## AtbashCipher ##
The Atbash cipher is a particular type of monoalphabetic cipher formed by taking the alphabet (or abjad, syllabary, etc.) and mapping it to its reverse, so that the first letter becomes the last letter, the second letter becomes the second to last letter, and so on. For example, the Latin alphabet would work like this:

<table>
<tbody>
<tr>
<th>Plain</th>
<td>A</td>
<td>B</td>
<td>C</td>
<td>D</td>
<td>E</td>
<td>F</td>
<td>G</td>
<td>H</td>
<td>I</td>
<td>J</td>
<td>K</td>
<td>L</td>
<td>M</td>
<td>N</td>
<td>O</td>
<td>P</td>
<td>Q</td>
<td>R</td>
<td>S</td>
<td>T</td>
<td>U</td>
<td>V</td>
<td>W</td>
<td>X</td>
<td>Y</td>
<td>Z</td>
</tr>

<tr>
<th>Cipher</th>
<td> Z</td>
<td>Y</td>
<td>X</td>
<td>W</td>
<td>V</td>
<td>U</td>
<td>T</td>
<td>S</td>
<td>R</td>
<td>Q</td>
<td>P</td>
<td>O</td>
<td>N</td>
<td>M</td>
<td>L</td>
<td>K</td>
<td>J</td>
<td>I</td>
<td>H</td>
<td>G</td>
<td>F</td>
<td>E</td>
<td>D</td>
<td>C</td>
<td>B</td>
<td>A</td>
</tr>
</tbody>
</table>

(See more in [Wikipedia](https://en.wikipedia.org/wiki/Atbash))

[Here](AtbashCipher.java) you can see the implementation of Atbash Cipher in Java.

## ArrayInitialization ##
[Here](ArrayInitialization.java) you can see how array initialization is implemented in the class constructor in Java.

## CaesarCipher ##
In cryptography, a Caesar cipher, also known as Caesar's cipher, the shift cipher, Caesar's code or Caesar shift, is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence.

The transformation can be represented by aligning two alphabets; the cipher alphabet is the plain alphabet rotated left or right by some number of positions. For instance, here is a Caesar cipher using a left rotation of three places, equivalent to a right shift of 23 (the shift parameter is used as the key):

<table>
<tbody>
<tr>
<th>Plain</th>
<td>A</td>
<td>B</td>
<td>C</td>
<td>D</td>
<td>E</td>
<td>F</td>
<td>G</td>
<td>H</td>
<td>I</td>
<td>J</td>
<td>K</td>
<td>L</td>
<td>M</td>
<td>N</td>
<td>O</td>
<td>P</td>
<td>Q</td>
<td>R</td>
<td>S</td>
<td>T</td>
<td>U</td>
<td>V</td>
<td>W</td>
<td>X</td>
<td>Y</td>
<td>Z</td>
</tr>

<tr>
<th>Cipher</th>
<td>X</td>
<td>Y</td>
<td>Z</td>
<td>A</td>
<td>B</td>
<td>C</td>
<td>D</td>
<td>E</td>
<td>F</td>
<td>G</td>
<td>H</td>
<td>I</td>
<td>J</td>
<td>K</td>
<td>L</td>
<td>M</td>
<td>N</td>
<td>O</td>
<td>P</td>
<td>Q</td>
<td>R</td>
<td>S</td>
<td>T</td>
<td>U</td>
<td>V</td>
<td>W</td>
</tr>
</tbody>
</table>

(See more in [Wikipedia](https://en.wikipedia.org/wiki/Caesar_cipher))

[Here](CaesarCipher.java) you can see the implementation of Caesar Cipher (i used offset to the right) in Java.

## ChangingArrayType ##
[Here](ChangingArrayType.java) you can see how a class with two arrays (the first with int values, the second with String values) is implemented in Java. The second array takes all the values of the first array, converts them to String type and stores them in reverse order.

## CodeWordCipher ##
Substitution of single letters separately — simple substitution — can be demonstrated by writing out the alphabet in some order to represent the substitution. This is termed a substitution alphabet. The cipher alphabet may be shifted or reversed (creating the Caesar and Atbash ciphers, respectively) or scrambled in a more complex fashion, in which case it is called a mixed alphabet or deranged alphabet. Traditionally, mixed alphabets may be created by first writing out a keyword, removing repeated letters in it, then writing all the remaining letters in the alphabet in the usual order.

Using this system, the keyword "zebras" gives us the following alphabets:

<table>
<tbody>
<tr>
<th>Plain</th>
<td>A</td>
<td>B</td>
<td>C</td>
<td>D</td>
<td>E</td>
<td>F</td>
<td>G</td>
<td>H</td>
<td>I</td>
<td>J</td>
<td>K</td>
<td>L</td>
<td>M</td>
<td>N</td>
<td>O</td>
<td>P</td>
<td>Q</td>
<td>R</td>
<td>S</td>
<td>T</td>
<td>U</td>
<td>V</td>
<td>W</td>
<td>X</td>
<td>Y</td>
<td>Z</td>
</tr>

<tr>
<th>Cipher</th>
<td>Z</td>
<td>E</td>
<td>B</td>
<td>R</td>
<td>A</td>
<td>S</td>
<td>C</td>
<td>D</td>
<td>F</td>
<td>G</td>
<td>H</td>
<td>I</td>
<td>J</td>
<td>K</td>
<td>L</td>
<td>M</td>
<td>N</td>
<td>O</td>
<td>P</td>
<td>Q</td>
<td>T</td>
<td>U</td>
<td>V</td>
<td>W</td>
<td>X</td>
<td>Y</td>
</tr>
</tbody>
</table>

(See more in [Wikipedia](https://en.m.wikipedia.org/wiki/Substitution_cipher))

[Here](CodeWordCipher.java) you can see the implementation of code word cipher in Java.

## ConsoleCalc ##
[Here](ConsoleCalc.java) you can see the implementation of a simple calculator in Java. You can enter an unlimited number of numbers and perform various mathemathical operations with them.

## ExchangedValues ##
[Here](ExchangedValues.java) you can see how to exchange values between two variables without using a third in Java.

## Factorial ##
In mathematics, the factorial of a positive integer n, denoted by n!, is the product of all positive integers less than or equal to n:

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4f850a56fb2d948805be9a7eb87b7b0bbeacb1c5">

For example,

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/7ef2aaeff6a5a3fe133932ab28153a750783a9ab">

The value of 0! is 1, according to the convention for an empty product.

<table style="text-align:center;">
<tbody>
<tr>
<th>n</th>
<td>0</td>
<td>1</td>
<td>2</td>
<td>3</td>
<td>4</td>
<td>5</td>
<td>6</td>
</tr>

<tr>
<th>n!</th>
<td>1</td>
<td>1</td>
<td>2</td>
<td>6</td>
<td>24</td>
<td>120</td>
<td>720</td>
</tr>
</tbody>
</table>

(See more in [Wikipedia](https://en.wikipedia.org/wiki/Factorial))

[Here](Factorial.java) you can see the implementation of Factorial in Java and [here](factorial.py) in Python.

## FibonacciNumbers ##
In mathematics, the Fibonacci numbers, commonly denoted Fn, form a sequence, called the Fibonacci sequence, such that each number is the sum of the two preceding ones, starting from 0 and 1. That is,

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/3c667d91153450b3a161371582ee8227af85951f">

and

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/4fa6d281e7a54e08aeffeef7458ddc0884333686">

for n > 1.

The beginning of the sequence is thus:

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/d9941f4184ea7677a056402b98d8b741af937f80">

(See more in [Wikipedia](https://en.wikipedia.org/wiki/Fibonacci_number))

[Here](FibonacciNumbers.java) you can see the implementation of Fibonacci numbers in Java and [here](FibonacciNumbers.py) in Python.

## FizzBuzz ##
[Here](FizzBuzz.java) you can see the solution to the popular FizzBuzz task in Java.

The program should print numbers from 1 to 100. But instead of multiples of three, it prints "Fizz", and instead of numbers that are multiples of five, - "Buzz". Instead of numbers that are multiples of both three and five at the same time, it prints "FizzBuzz".

## PerfectNumbers ##
In number theory, a perfect number is a positive integer that is equal to the sum of its positive divisors, excluding the number itself. For instance, 6 has divisors 1, 2 and 3 (excluding itself), and 1 + 2 + 3 = 6, so 6 is a perfect number.

<table style="text-align:center;">
<tbody>
<tr>
<th>Rank</th>
<td>1</td>
<td>2</td>
<td>3</td>
<td>4</td>
<td>5</td>
<td>6</td>
<td>7</td>
</tr>

<tr>
<th>Perfect number</th>
<td>6</td>
<td>28</td>
<td>496</td>
<td>8128</td>
<td>33550336</td>
<td>8589869056</td>
<td>137438691328</td>
</tr>
</tbody>
</table>

(See more in [Wikipedia](https://en.wikipedia.org/wiki/Perfect_number))

[Here](PerfectNumbers.java) you can see the implementation of a sequence of perfect numbers in Java.

**Attention! To display more than four numbers, you will have to wait!** :)

## PrimeNumbers ##
A prime number (or a prime) is a natural number greater than 1 that is not a product of two smaller natural numbers. A natural number greater than 1 that is not prime is called a composite number. For example, 5 is prime because the only ways of writing it as a product, 1 × 5 or 5 × 1, involve 5 itself. However, 4 is composite because it is a product (2 × 2) in which both numbers are smaller than 4. Primes are central in number theory because of the fundamental theorem of arithmetic: every natural number greater than 1 is either a prime itself or can be factorized as a product of primes that is unique up to their order.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f0/Primes-vs-composites.svg/800px-Primes-vs-composites.svg.png" width="220" heigth="309">

(See more in [Wikipedia](https://en.wikipedia.org/wiki/Prime_number))

[Here](PrimeNumbers.java) you can see the implementation of prime numbers in Java.

## RecamanSequence ##
In mathematics and computer science, the Recamán's sequence (or Recaman's sequence) is a well known sequence defined by a recurrence relation, because its elements are related to the previous elements in a straightforward way, they are often defined using recursion.

It takes its name after its inventor Bernardo Recamán Santos (Bogotá, August 5, 1954), a Colombian mathematician.

The Recamán's sequence <img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/f98223b2560de036588b919037549a149aeb7eda"> is defined as:

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/89ab504e66d289aeb91cdd3c9b3d88212a13f506">

The first terms of the sequence are:

0, 1, 3, 6, 2, 7, 13, 20, 12, 21, 11, 22, 10, 23, 9, 24, 8, 25, 43, 62, 42, 63, 41, 18, 42, 17, 43, 16, 44, 15, 45, 14, 46, 79, 113, 78, 114, 77, 39, 78, 38, 79, 37, 80, 36, 81, 35, 82, 34, 83, 33, 84, 32, 85, 31, 86, 30, 87, 29, 88, 28, 89, 27, 90, 26, 91, 157, 224, 156, 225, 155, ...

I like the drawing better:

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/d/da/Reacam%C3%A1nSequenceDrawing.png/375px-Reacam%C3%A1nSequenceDrawing.png">

(See more in [Wikipedia](https://en.wikipedia.org/wiki/Recam%C3%A1n%27s_sequence))

[Here](RecamanSequence.java) you can see the implementation of the Recaman sequence.