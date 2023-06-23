Regex Tutoring

Regular expressions can be used to find certain patterns of characters within a string. You can also find and replace a character or sequence of characters within a string. They are also frequently used to validate input. This regex matches character information for valid e-mail addresses.

## Summary

The regex code that we will be looking at today is:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors:

Anchors serve as markers that define the starting and ending points of a regular expression. The "^" symbol denotes the beginning of a string, while the "$" symbol indicates the end of a string.

### Quantifiers:

Quantifiers determine the number of times a character, group, or character class should be matched. The "+" symbol matches one or more occurrences of the preceding element, while the "\*" symbol matches zero or more occurrences. The "{n}" syntax matches exactly "n" occurrences, whereas "{n,m}" matches between "n" and "m" occurrences.

### OR Operator:

The "|" symbol allows for the specification of alternative patterns to match. For instance, the regular expression "cat|dog" matches either "cat" or "dog".

### Character Classes:

Character classes are used to match a range of characters. The "." character matches any character except a newline, while the "\d" character class matches any digit from 0 to 9. The "\w" character class matches any word character (letters, digits, underscores). The "^" symbol negates a character class, so "\D" matches any non-digit character.

### Flags:

Flags modify the behavior of a regular expression. The "i" flag enables case-insensitive matching, while the "g" flag enables global matching (matches all occurrences of the pattern in the string).

### Grouping and Capturing:

Grouping and capturing are employed to extract specific portions of a string that match a pattern. Groups are defined using parentheses, and the "\1" syntax refers to a captured group.

### Bracket Expressions:

Bracket expressions match a range of characters that may not be contiguous. For example, the "[a-z]" expression matches any lowercase letter from "a" to "z".

### Greedy and Lazy Match:

Greedy and lazy matching specify the extent to which a quantifier matches characters. Greedy quantifiers match as much of the input as possible, whereas lazy quantifiers match as little as possible.

### Boundaries:

Boundaries are used to match the start or end of a string. The "\b" expression matches a word boundary, while "\B" matches any non-word boundary.

### Back-references:

Back-references refer to a captured group earlier in the regular expression. For instance, "(foo)\1" matches the string "foofoo" and captures the "foo" group twice.

### Look-ahead and Look-behind:

Look-ahead and look-behind are employed to match a pattern only if it is preceded or followed by a specific pattern. The "?" symbol denotes a non-greedy look-ahead, while the "\*" symbol denotes a non-greedy look-behind.

## Author

Dorian Henry
https://github.com/DHenry24
