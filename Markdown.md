# Markdown

- https://guides.github.com/features/mastering-markdown/
- http://dillinger.io/
- https://stackedit.io/editor
- [Markdown Syntax Cheat Sheet](http://markable.in/file/aa191728-9dc7-11e1-91c7-984be164924a/)
- https://daringfireball.net/projects/markdown/syntax

## Exemples

- [nodejs api](https://github.com/nodejs/node/tree/master/doc/api)

    indent = 4 spaces
    with = 80 col
    comment = `<!-- -->`

## Syntax

### Headings

    # Header 1
    ## Header 2
    ### Header 3
    ...

### Styles

    *Italic*
    **Bold**
    ~~strikethrough~~
    `some code`

*Italic*,
**Bold**,
~~strikethrough~~,
`some code`


### Links

    url
    <url>

http://www.google.com/,
<http://www.google.com/>

    [text](url)
    [text](url "title")

[google 1](http://www.google.com/),
[google 2](http://www.google.com/ "title 2")

```
[text][ref-url]
[ref-url]: url, url "title", <url>, <url> (title)
```

[google 3][ref-3]
[ref-3]: http://www.google.com/ "title 3"
  
```
[text]
[text]: url, url "title", <url>, <url> (title)
```

[google 4], [google 5], [google 6]
[google 4]: http://www.google.com/
[google 5]: http://www.google.com/ "title 5"
[google 6]: <http://www.google.com/> (title 6)


### Images

```
![alt](img-url)
![](img-url)
![](img-url "title")
```

![](http://www.google.com/s2/favicons?domain=git-scm.com),
![](http://www.google.com/s2/favicons?domain=git-scm.com "git")

**And links**

```
[![](img-url](url)
[![](img-url "title")](url)
[![](img-url "title") text](url)
[![](img-url "title") text](url "title")
```

[![](http://www.google.com/s2/favicons?domain=git-scm.com)](http://git-scm.com/doc/),
[![](http://www.google.com/s2/favicons?domain=git-scm.com "git")](http://git-scm.com/doc/),
[![](http://www.google.com/s2/favicons?domain=git-scm.com "git") Git - Documentation](http://git-scm.com/doc/)
[![](http://www.google.com/s2/favicons?domain=git-scm.com "git") Git - Documentation](http://git-scm.com/doc/ "Goto git")

```
[![][ref-img] text][ref-url]
[ref-img]: img-url "title"
[ref-url]: url "title"
```

[![][git-ico] Git - Documentation][git-doc]
[git-ico]: http://www.google.com/s2/favicons?domain=git-scm.com "git"
[git-doc]: http://git-scm.com/doc/ "Goto git"


### Lists

```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

* Item 1
* Item 2
  * Item 2a
  * Item 2b


### Task list

```
- [x] Aaaa
- [ ] Bbbb
```

- [x] Aaaa
- [ ] Bbbb


### Blockquotes

```
> Aaaa
>> Bbbb
>
> Cccc
```

> Aaaa
>> Bbbb
>
> Cccc


### Lines

```
---
***
```

---
***


### Tables

```
Header 1 | Header 2
-------- | --------
Aaaa     | Bbbb
```

Header 1 | Header 2
-------- | --------
Aaaa     | Bbbb


### Code

```javascript
function toto() {
  // comment
  call();
}
```

### Special logos

[![Build Status](https://travis-ci.org/ekalinin/github-markdown-toc.svg?branch=master)](https://travis-ci.org/ekalinin/github-markdown-toc)


### Emoji

http://www.emoji-cheat-sheet.com/

```
:tada:
:exclamation:
:point_up:
:hand:
:thumbsup:
:zap:
:sunny:
:one:
```

:tada: |
:exclamation: |
:point_up: |
:hand: |
:thumbsup: |
:zap: |
:sunny: |
:one:


### Special char

➥
