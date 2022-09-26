# Module 17

Regex Tutorial 

## Summary

     Regex.   


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Flags](#flags)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors are used to match the start or end of a line.  These are used for matching locations. The two anchors used are ^ and $. 
^ is used for the start of a line, while $ is used for the end of a line.


### Quantifiers
Quantifiers are used to set a limit on characters/numbers. The two main are + and ?.  + can be used to search a pattern atleast once or multiple times, while ? can be used to search once or none at all.
### OR Operator
OR operators are used to match what is on either side of a character. They can be thought of as functioning in a continuation of something and are easily thought of as and/or systems.

### Character Classes
Character classes(also called character sets), can be used to match only one out of several characters.  A good example of character classes is that you can use something such as [] and search for 'ae' inside the []. This allows a user to search for gray or grey, an easy way to search through documents that may be American or British. 

### Flags
Flags, are an optional parameter, that can be used to change the behavior of searching. It searches for something given by the user until it can find a condition that matches.

### Grouping and Capturing
"Groups group multiple patterns as a whole, and capturing groups provide extra submatch information when using a regular expression pattern to match against a string. Backreferences refer to a previously captured group in the same regular expression."
(src=https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Groups_and_Backreferences)

-From what I'm reading and my understanding it's almost similiar to marking classes to catch certain data. 

### Bracket Expressions
-[abcd]	Matches any character in the square brackets.	[nN][oO] matches no, nO, No, and NO.
gr[ae]y matches both spellings of the word 'grey'; that is, gray and grey.

--------------------------------------------------------
[a-d]	Matches any character in the range of characters separated by a hyphen (-).	[0-9] matches any decimal digit.
[ab3-5] matches a, b, 3, 4, and 5.

[0-9]{4} matches any four-digit string.

^[A-Za-z]+$ matches any string that contains only upper or lowercase characters.

\[[0-9 ]*\] matches an opening square bracket, followed by any digits or spaces, followed by a closed bracket.

--------------------------------------------------
[^abcd]
[^a-d]

Matches any character except those in the square brackets or in the range of characters separated by a hyphen (-).	[^0-9] matches any string that does not contain any numeric characters.

----------------------------------------------------------------
[.ab.]	Matches a multi-character collating element.	[.ch.] matches the multi-character collating sequence ch (if the current language supports that collating sequence).

----------------------------------------------------------------
[=a=]	Matches all collating elements with the same primary sort order as that element, including the element itself.	[=e=] matches e and all the variants of e in the current locale.

### Look-ahead and Look-behind
Look ahead and look behind will follow grouped symbols and look ahead of them or after them. Such as "find expression A where B does not follow A(?|B) or a look behind where "find expression A where expression B preceds"  such as (?<=B)A

## Author

Check out my  <a href="github.com/ohdangbro">Github</a>!