# Eric's Markdown Cheatsheet

## H2 is '##'

### H3 or "###"

#### H4 or "####"

##### H5 or "#####"

Regular text

**Bold Text**

```
**Bold Text**
```

*Italic Text*

```
*Italic Text*
```

_Underlined Text_

```
_Underlined Text_
```

> Blockquote

```
> Blockquote
```

### Lists

---

1. Hi, I'm an ordered list!  
    1. *and I am a sub-heading!*  
        1. **Gosh, isn't this fun?**  
        1. I think that's enough.
2. Not much to it.

---

+ And this is an unordered list
+ Not much here either  
  + unless you like subheadings  
    + then you'll love this  
      + Much order, such wow

---

### Code

```Markdown

1. Hi, I'm an ordered list!  
    1. *and I am a sub-heading!*  
        1. **Gosh, isn't this fun?**  
        1. I think that's enough.
2. Not much to it.

---

+ And this is an unordered list
+ Not much here either  
  + unless you like subheadings  
    + then you'll love this  
      + Much order, such wow

```

---

### Links

[I'm an inline-style link](https://www.google.com)

```
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

---

### Images

Inline-style:
![alt text](https://avatars.githubusercontent.com/u/36175119?v=4 "Look at the head on that man!")

Reference-style:
![alt text][logo]

[logo]: https://avatars.githubusercontent.com/u/36175119?v=4 "I bet it has its own gravity!"

### Code

```CS
Inline-style:
![alt text](https://avatars.githubusercontent.com/u/36175119?v=4 "Look at the head on that man!")

Reference-style: 
![alt text][logo]

[logo]: https://avatars.githubusercontent.com/u/36175119?v=4 "I bet it has its own gravity!"
```
---
