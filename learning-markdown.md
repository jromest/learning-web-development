# MARKDOWN SYNTAX

```
# This is an h1 tag
## This is an h2 tag
### This is h3 tag
#### This is h4 tag
##### This is h5 tag
###### This is h6 tag

```

# This is an h1 tag
## This is an h2 tag
### This is h3 tag
#### This is h4 tag
##### This is h5 tag
###### This is h6 tag

-----

### Text Formatting

```
*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

*You **can** combine them*

~~This text will be deleted~~
```

*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

*You **can** combine them*

~~This text will be deleted~~

To put a new line in the paragraph  
add two trailing space. (*This is for Markdown*)

*\*GFM (Github Flavored Markdown) only uses \<Enter\> to put a new line*

-----

### Blockquotes

```
As Grace Hopper said:

> I've always been more interested
> in the future than in the past
```

As Grace Hopper said:

> I've always been more interested
> in the future than in the past

-----

### Unordered List

```
* Item 1
* Item 2
    * Item 2a
    * Item 2b

    To properly indented the paragraph put leading space(s)
    This is only applicable in list
```

* Item 1
* Item 2
    * Item 2a
    * Item 2b

    To properly indented the paragraph put leading space(s)
    This is only applicable in list

-----

### Ordered List

```
1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b
```

1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b

-----

### Image

```
![Sample Image](img/dog-invocation.jpg "Dog with Glasses")
```

![Sample Image](img/dog-invocation.jpg "Dog with Glasses")

-----

### Links

```
http://github.com - automatic

Inline-style link
Visit [Github](http://github.com)

Inline-style link with tooltip
[Github](http://github.com "Github")

Reference-style link using text
[From Github][reference text]

Reference-style link using number
[From Google][1]

Reference-style link without text or number
[From Github link itself]

*Below will be the reference of the above links this will be not visible during preview*

[reference text]: http://github.com
[1]: https://www.google.com
[From Github link itself]: http://github.com
```

http://github.com - automatic

Inline-style link
Visit [Github](http://github.com)

Inline-style link with tooltip
[Github](http://github.com "Github")

Reference-style link using text
[From Github][reference text]

Reference-style link using number
[From Google][1]

Reference-style link without text or number
[From Github link itself]

*Below will be the reference of the above links this will be not visible during preview*

[reference text]: http://github.com
[1]: https://www.google.com
[From Github link itself]: http://github.com

-----

### Escaping Character Using Backlash

```
\*literal asterisks\*
\\literal backlash\\
\`literal backtick\`
\_literal underscore\_
\{literal curly braces\}
\[literal square brackets\]
\(literal parenthesis\)
\#literal hashmark\#
\+literal plus sign\+
\-literal minus\-
\.literal dot\.
\!literal exclamation mark\!
```

\*literal asterisks\*
\\literal backlash\\
\`literal backtick\`
\_literal underscore\_
\{literal curly braces\}
\[literal square brackets\]
\(literal parenthesis\)
\#literal hashmark\#
\+literal plus sign\+
\-literal minus\-
\.literal dot\.
\!literal exclamation mark\!

-----

### Github support EMOJI

```
:+1: :sparkles: :camel: :tada:
:rocket: :facepunch: :octocat:
```

:+1: :sparkles: :camel: :tada:
:rocket: :facepunch: :octocat:

To see the list of supported emoji [check this out](http://www.emoji-cheat-sheet.com)

-----

### Code Blocks


Use single backtick for inline `code block` in a sentence

```
`codeblock`

```javascript
function test() {
    console.log("hello world!");
}
```(end)
```

```javascript
function test() {
    console.log("hello world!");
}
```

```python
def test(arg1):
    print("hello world!")
    return arg1
```

-----

### Task Lists

```
- [x] this is a complete item
- [ ] this is a incomplete item
- [x] @mention, #ref, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered list or ordered list supported)
```

- [x] this is a complete item
- [ ] this is a incomplete item
- [x] @mention, #ref, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered list or ordered list supported)

-----

### Tables

There must be atleast **3 dashes** separating each header cell
Outer pipes (|) are *optional*

```
First Header | Second Header
--- | ---
Content cell 1 | Content cell 2
Content column 1 | Content column 2
1 | 2 |
```

First Header | Second Header
--- | ---
Content cell 1 | Content cell 2
Content column 1 | Content column 2
1 | 2 |


Colons can be used to align columns

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:|------:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      | $12   |
| zebra stripes | are neat      | $1    |
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:|------:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      | $12   |
| zebra stripes | are neat      | $1    |

-----

### Inline HTML

```
<dl>
  <dt>Definition List</dt>
  <dd>Is something people use sometimes</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em></dd>
</dl>
```

<dl>
  <dt>Definition List</dt>
  <dd>Is something people use sometimes</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em></dd>
</dl>

*Using four spaces will convert the markdown as code blocks*

-----
