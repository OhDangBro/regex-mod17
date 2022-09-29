# Module 17

Matching email regex tutorial.

## Summary
Regex is a regular expression. I will be using the matching email regex which is demonstrated by '/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/  This regex is used to validate an email address. It can be compared to a validator but acts more in the sense of a search for correct input.  This email regex can be used in a contact form, sign up or other forms of input to make sure the input is in the correct format. 
      


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
<!-- - [OR Operator](#or-operator) -->
- [Flags](#flags)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
The anchors ^ and $ are used. In a singular line mode the anchor ^, is used to match the start of a line, while the $ is used to match the end of a line. 


### Quantifiers
Quantifiers are used to match a character, group or character class in a string. While using a regex for email validation one would want to use the +. This specific example is known as a "greedy operator", and is responsible for matching as many occurances as are available. While using the regex '[a-z0-9_\.-] and [A-Z0-9-] +@' will seach for all things in the bracket such as letters a-z and/or 0-9 covering all of the alphabet and all possible numbers, regardless of combination. The @ symbol will be used to verify the email as all email addresses have the "@aol.com/@gmail" for example. Another quantifier is the 


<!-- ### OR Operator  Doesnt exist-->


### Character Classes
This regex uses a \ and functions by looking for a single digit. It can be used solo and look for one digit or can be used multiple times to look for mulitple digits with each \ corresponding to a digit in the search. 

### Flags
/ is the flag for the email validation regex. You can see the / at the start followed by character, but also the final / being the end of this regex. 

### Grouping and Capturing
 This regex groups in the sense of how an email is formatted. It groups in the sense of   'string' '@' and a 'top-level-domain'. 

### Bracket Expressions

The bracket expressions are used to search for a string and match it with what is currently contained in the brackets. Such as a-z which is looking for all of the alphabet as opposed to the literal only a and z. The same can be used for the 0-9 with numbers. 

### Greedy and Lazy Match
These names are somewhat literal in the sense that a greedy match, will match as much as possible and be "greedy" about how much it can match, while on the opposite side the lazy match will try lazily match as little as possible. 





## Author

Check out my  <a href="github.com/ohdangbro">Github</a>!