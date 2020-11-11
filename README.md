# group-website
Repository for learning how to make websites with Jekyll Pages

Some **bold** font and some *italic* font.

## Learning Markdown

Vanilla text may contain *italic* and **bold words**.

This paragraph is separated from the previous one by a blank line. Line breaks  
are caused by two trailing spaces at the end of a line.

- make a list item1
- item 2

1. item1
1. item2
1. item3

2. item a
3. item b
4. item c

```
print("hello")
```

Here we will use some code with a `print` statement.

#### Exercise:

You can reference code __message='Hello World'__
or commands __git status__ inside text.
Larger code snippets look like this:
__
print('Hello World')
__

solution:

You can reference code `message='Hello World'`
or commands `git status` inside text.
Larger code snippets look like this:
```
print('Hello World')
```
Adding the language, in this example python
```python
print('Hello World')
```
#### R
```r
print(paste("How,"are","you?"), quote = FALSE)
```

#### Python
```python
s = "How are you?"
print(s)
```

```
<!DOCTYPE html>
<html>
  <body>
    <a href=https://carepntries.org/>This is a link</a>
  </body>
</html>
```

[The Carpentries](https://carpentries.org/)

I would like to use [this site][carpentries-tag].

[carpentries-tag]: https://carpentries.org/

#### Exercise

Example links:
1. [___](https://carpentries.org/)
2. [___]___case-InSeNsiTiVe-reference-tag___

[case-insensitive-reference-tag]: https://carpentries.org/

#### Solution
Example links:
1. [Reference link](https://carpentries.org/)
2. [Inline Link][case-InSeNsiTiVe-reference-tag]

[case-insensitive-reference-tag]: https://carpentries.org/
