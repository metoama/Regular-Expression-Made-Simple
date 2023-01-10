# Regular Expression Made Simple 

## Summary

A Regular Expression or Regex in a sense have nothing to do with progamming. They are a sequence of characters that defines a search
pattern in text. They Regex I will be explaining is one that can be used to locate email addresses in text documents or editors.



## Table of Contents

-[Anchors](#anchors)
-[Quantifiers](#quantifiers)
-[OR Operator](#or-operator)
-[Character Classes](#character-classes)
-[Flags](#flags)
-[Grouping and Capturing](#grouping-and-capturing)
-[Bracket Expressions](#bracket-expressions)
-[Greedy and Lazy Match](#greedy-and-lazy-match)
-[Boundaries](#boundaries)
-[Back-references](#back-references)
-[Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

EMAIL REGEX:   /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
An anchor can specify the start or end of a line or string. Anchors can also be used to create word boundary for searching purposes. It can also determine the search parameters for the start or end of a word. 

In my Regex example I have two anchors. 

'^': This character denotes the beginning of a line and can be use to confirm the regex must will search for matches to the start of the string. 

'$': This character dentoes the end of a line and can be used to confirm the reg will search for matches to the end of the line or string. 

### Quantifiers 

Quantifiers are essentially meta characters the modify the previous character in a regualr expression and can dictate how many of the characters you want to match in a row.

The quantifiers in my Regex are: 

'+': This denotes that the character or group preceding must be matched by expression 1 or more times. 

'{2,6}': Using these digits inside a set of '{}' will let you insert a minimum and maxium. In this expression this will look to bee matched 2 and 6 times. 2 min and 6 max. 
