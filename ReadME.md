# Workshop-Kotlin

## Install Kotlin:
```
```

# Launch Kotlin:

We provided a bash script for you in order to ease the execution of your code

```
```

# Exercice 1 : Syntax

Print every number between 1 and 100 as follows:

- For every multiple of 3 print "Three".
- For every multiple of 5 print "Five".
- And for every multiple of both 3 and 5 print "ThreeFive"

The output should be identical to the contents of [this file](./1.txt):


# Exercice 2 : List

Write a "Countword" function whose objective is to count the number of times a word appears in a sentence.
This function takes 2 parameters :

    - "sentence" -> the sentence you will search through
    - "target" -> the word you look for in the sentence


Example:

```
Countword('ton tonton tond ton thon', "ton") -> ton appears 2 times
```


# Exercice 3 : Fluctuating number of arguments

Write a function that takes n parameters as Strings and add them together.

Examples:

```
Calculator("4", '5') -> 9
Calculator('3', '4', '3', '5', '7', '8', '1') -> 31
```


# Exercice 4 : Error handling

Modify your Calculator function to now handle invalid parameters.

Example:

```
CalculatorV2("4", '5', 'a') -> "Invalid Parameter: a"
CalculatorV2("4", '5', 1) -> 10
```


# Exercice 5 : File Manipulation

Retrieve the contents of the file [5.txt](./5.txt) and parse through it to only display lines with an even number of characters.

The output should be as follows:

```
10
11
My name is Yoshikage Kira.
I work as an employee for the Kame Yu department stores, and I get home every day by 8 PM at the latest.
I don't smoke, but I occasionally drink.
I'm in bed by 11 PM, and make sure I get eight hours of sleep, no matter what.
I was told there were no issues at my last check-up.
I take care not to trouble myself with any enemies, like winning and losing, that would cause me to lose sleep at night.
```


# Exercice 6 : OOP basics

Create a Pet class with the properties "name" and "status".

If no parameter is provided, the default values for __"name"__ and __"status"__ will be __"Kikki"__ and __"Hungry"__ respectively.


# Exercice 7 : Methods

Add 2 methods to your Pet class:

    - check: display the pet's name and status
    - feed: set the pet's status to "Fed" 

Example:

```
val animal = Pet("Minou", "on fire")

animal.check() -> "Minou is on fire"
animal.feed() -> "Minou has been fed"
```


# Exercice 8 : Inheritance

Create a Dog class derived from your Pet class which takes 3 parameters : name, status and breed.

Add 2 new properties :

    - breed ("Australian Shepherd" by default)
    - loyalty (set to 0)

Over-ride the default name to now be __"Meimei"__.

Over-ride the FEED method to now also increase the LOYALTY by 10

Add a new method:

    - isLoyal -> display "is loyal" if loyalty is supertior to 10

Example:

```
    val dog = Dog()
    dog.isLoyal() -> "Meimei is NOT loyal"
    dog.feed()
    dog.isLoyal() -> "Meimei is loyal"
    dog.check() -> "Meimei is a Fed Australian Shepherd"
```


# Exercice 9 : extensions

Create a **bark** method *outside* of your Dog class

_This example is lackluster by choice_

Example:

```
    val dog = Dog()
    dog.bark() -> "woof woof"
```


# BONUS :

Write Unit Tests for ex 1, 4, 8, 9
