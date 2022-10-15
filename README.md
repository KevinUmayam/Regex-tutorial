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
"^" -  Matches the beginning of the string, or the beginning of a line if the multiline flag.

"()" Groups multiple tokens together and creates a capture group for extracting a substring or using a backreference.

"[]" Everything inside the brakets become a set to be matched with.

"a-z" is a Range: Matches characters from a to z, and these are case sensetive. 

"0-9" is a Range: Matches characters from 0 to 9. 

"_" is a character: Matches with a _. 

"\." is a character: Matches with a ".". 

"-" is a character: Matches with a "-".

"+" is a quantifier. Match with 1 or more of the preceding token.

"@" is a character: Matches with a "@".

"\d" is a digit: Matches with characters from 0 to 9.

"\." is an escaped character: Matches with a ".".

"{2,6}" is a quantifier. Match with 2 and 6 of the preceding token.

"$" end.  Matches the end of the string, or the end of a line if the multiline flag (m) is enabled.

### Anchors
"$" and "^" would be considered anchors that are resposible for specifying where the string would begin and end.

### Quantifiers

"+" is a quantifier. Match with 1 or more of the preceding token.

### Grouping Constructs

"()" Groups multiple tokens together and creates a capture group for extracting a substring or using a backreference.

([a-z0-9_\.-]+)
([\da-z\.-]+)
([a-z\.]{2,6})

### Bracket Expressions

"[]" Everything inside the brakets become a set to be matched with.

[a-z0-9_\.-]
[\da-z\.-]
[a-z\.]
### Character Classes

"_" is a character: Matches with a _. 

"\." is a character: Matches with a ".". 

"-" is a character: Matches with a "-".

"@" is a character: Matches with a "@".


### The OR Operator

There are no "OR" operators in this expression.

### Flags

The code it self does not appear to have any flags however we would probably want to add a golbal and case sensitive flags to this. 

### Character Escapes

Used to search for any special characters
"\." is an escaped character: Matches with a ".".

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
