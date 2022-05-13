# What is REGEX

Imagine you are writing an application and you want to set the rules for when a user chooses their username. We want to allow the username to contain letters, numbers, underscores and hyphens. We also want to limit the number of characters in the username so it does not look ugly. We can use the following regular expression to validate the username:

## Summary

A regular expression is a pattern that is matched against a subject string from left to right. Regular expressions are used to replace text within a string, validate forms, extract a substring from a string based on a pattern match, and so much more. The term "regular expression" is a mouthful, so you will usually find the term abbreviated to "regex" or "regexp".

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

Regular expressions can contain multiple components to accomplish the following tasks when Requirements Gateway analyzes intermediate files: Matching Fixed Strings. Matching Special Characters. Matching Character Sets.

### Anchors

Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

### Grouping Constructs

Grouping constructs delineate the sub expressions of a regular expression and capture the substrings of an input string. You can use grouping constructs to do the following: Match a sub expression that is repeated in the input string.

### Bracket Expressions

A bracket expression is either a matching list expression or a non-matching list expression. It consists of one or more expressions: collating elements, collating symbols, equivalence classes, character classes, or range expressions.

### Character Classes

In the context of regular expressions, a character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string.

### The OR Operator

Patterns that are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

### Flags

A flag is an optional parameter to a regex that modifies its behavior of searching. A flag changes the default searching behaviour of a regular expression. It makes a regex search in a different way. A flag is denoted using a single lowercase alphabetic character.

### Character Escapes

The \ is known as the escape code, which restore the original literal meaning of the following character. Similarly, \* , + , ? (occurrence indicators), ^ , $ (position anchors) have special meaning in regex. You need to use an escape code to match with these characters.

## Author

*[GitHub](https://github.com/Emanconcepcion/regex)
