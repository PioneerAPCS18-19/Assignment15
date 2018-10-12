# Assignment 15

You will make a few methods for this assignment and it is fine if you just use one class.

## Part 1
Given an "out" string length 4, such as "\<\<\>\>", and a word, return a new string where the word is in the middle of the out string, e.g. "\<\<word\>\>". Note: use str.substring(i, j) to extract the String starting at index i and going up to but not including index j.

### Sample Outputs

```
makeOutWord("<<>>", "Yay") → "<<Yay>>"
makeOutWord("<<>>", "WooHoo") → "<<WooHoo>>"
makeOutWord("[[]]", "word") → "[[word]]"
```

## Part 2

Given a string of any length, return a new string where the last 2 chars, if present, are swapped, so "coding" yields "codign" (using concatenation is helpful).

### Sample Outputs
```
lastTwo("coding") → "codign"
lastTwo("ab") → "ba"
lastTwo("a") → "a"
lastTwo("") → ""
```

## Part 3

Given two strings, append them together (known as "concatenation") and return the result. However, if the strings are different lengths, omit chars from the longer string so it is the same length as the shorter string. So "Hello" and "Hi" yield "loHi". The strings may be any length.

### Sample Outputs

```
minCat("Hello", "Hi") → "loHi"
minCat("Hello", "java") → "ellojava"
minCat("java", "Hello") → "javaello"
minCat("abc", "x") → "cx"
minCat("", "Hello") → ""
```

## Part 4

Given a string and a second "word" string, we'll say that the word matches the string if it appears at the front of the string, except its first char does not need to match exactly. On a match, return the front of the string, or otherwise return the empty string. So, so with the string "hippo" the word "hi" returns "hi" and "xip" returns "hip". The word will be at least length 1.

### Sample Outputs

```
startWord("hippo", "hi") → "hi"
startWord("hippo", "xip") → "hip"
startWord("hippo", "i") → "h"
startWord("h", "ix") → ""
startWord("hippo", "ix") → ""
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

