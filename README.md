# Python Pattern Parser (PPP)

Take an text file and apply regexes read from a pattern file.


# RegEx Pattern File

Those regexes are done in a pattern file as follows:

 - Lines starting with `#` are regarded as comments
 - Empty lines are ignored too
 - Search and replace pattern are separated by !
 - Group backreferences work with backslash

A minimal file may look like this:

```
# Comment
a(.*?)b!c\1d
```
