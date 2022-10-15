# Regex Tutorial



  Regular expressions are a way to efficiently search through text, in order to do things like validate or advance find and replace. Instead of staring with quotes like we would with strings, we would write the regular expression with in slashes "/".  Regular expressions also have flags which are filters that allow us to further our power to througly read text.

## Summary

Matching an Email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

As it is written above, this is a regular expression that is used to compare and validate and email adress. Throughout this readme I will be dissecting this expression to further understand its inner workings.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
^ -  Matches the beginning of the string, or the beginning of a line if the multiline flag.

() -  Groups multiple tokens together and creates a capture group for extracting a substring or using a backreference.
[] - Everything inside the brakets become a set to be matched with.

a-z is a Range: matches characters from a to z, and these are case sensetive. 
0-9 is a Range: matches characters from 0 to 9. 
_ is a character: matches with a _. 
\.is a character: matches with a ".". 

### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
