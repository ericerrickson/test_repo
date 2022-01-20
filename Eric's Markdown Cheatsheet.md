# Eric's Markdown Cheatsheet

## H2 is '##'

### H3 or "###"

#### H4 or "####"

##### H5 or "#####"

Regular text

**Bold Text** == `**Bold Text**`

*Italic Text* == `*Italic Text*`

_Underlined Text_ == `_Underlined Text_`

1. This is an ordered list. It begins with: **'1.'** and ends with **TWO SPACES**  
1.1. and the next level begins with '**1.1**'  
1.2 and the next level begins with '**1.2**' and so on.
2. Not much to it.

---

### Links

[I'm an inline-style link](https://www.google.com)

```cs
[I'm an inline-style link](https://www.google.com)
```

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

```cs
[I'm an inline-style link with title](https://www.google.com "Google's Homepage")
```

[I'm a relative reference to a repository file](../blob/master/LICENSE)

```cs
[I'm a relative reference to a repository file](../blob/master/LICENSE)
```

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

```cs
Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
```
---

### Codeblocks and fencing

```python
#!/usr/bin/env python3

s = "Python syntax highlighting"

def main():
    """ Main entry point of the app """
    print("hello world")
```
Begin with three backticks and the language, like **```Python**,
then a newline and your code, closed with a newline and three backticks.

```
 ```Python
 Your code here...
` ``
 ``` 
