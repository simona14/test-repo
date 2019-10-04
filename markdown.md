# Markdown Cheatsheet

## [References](#references)
* [Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown in VS Code](https://code.visualstudio.com/Docs/languages/markdown)

## [Sections](#sections)
---

Using Header Anchor Links:
- [Headers](#headers)
- [Emphasis](#emphasis) 
- [Lists](#lists)
- [Links](#links)
- [Images](#images)
- [Code and Syntax Highlighting](#code-and-syntax-highlighting)
- [Tables](#tables)
- [Blockquotes](#blockquotes)
- [Inline HTML](#inline-html)
- [Horizontal Rule](#horizontal-rule)
- [Line Breaks](#line-breaks)
- [Youtube Videos](#youtube-videos)
---

## Headers

### H3
Vestibulum mattis vel nulla non pulvinar. 

#### H4
Cras sed diam augue. Mauris pharetra neque hendrerit pulvinar ultricies. 
Donec vulputate commodo velit, non sollicitudin quam congue ut. 
Cras nisi leo, rhoncus nec ipsum id, feugiat posuere enim. Quisque felis arcu, posuere volutpat feugiat sit amet, lacinia non augue. Sed eget orci in justo suscipit venenatis. 

##### H5
Phasellus cursus pulvinar diam, at blandit nisl malesuada vel. Praesent finibus sapien vitae fermentum euismod. 
Curabitur eget enim in magna imperdiet lobortis ac et magna. Nulla id metus varius, dapibus orci sit amet, molestie massa. 

###### H6
Fusce sed ultricies ex. Nam tempus sollicitudin congue. 
Fusce malesuada lacus semper sollicitudin suscipit. In pellentesque orci eget luctus fermentum.

_[Back to Top](#sections)_

## Emphasis

Vestibulum mattis vel nulla non pulvinar. Cras sed diam augue. Mauris pharetra neque hendrerit pulvinar ultricies. _Donec vulputate commodo velit, non sollicitudin quam congue ut._ 

Cras nisi leo, rhoncus nec ipsum id, feugiat posuere enim. Quisque felis arcu, __posuere volutpat feugiat sit amet, _lacinia_ non augue.__ Sed eget orci in justo suscipit venenatis. **Phasellus cursus pulvinar diam, at blandit nisl malesuada vel.** 

Praesent finibus sapien vitae fermentum euismod. Curabitur eget enim in magna imperdiet lobortis ac et magna. Nulla id metus varius, dapibus orci sit amet, molestie massa. _Fusce sed **ultricies** ex. Nam tempus sollicitudin congue._ Fusce malesuada lacus semper sollicitudin suscipit. In pellentesque ~~orci leget luctus~~ fermentum.

_[Back to Top](#sections)_

## Lists

**Ordered**

1. Vestibulum mattis vel nulla non pulvinar. 
1. Cras sed diam augue. 
1. Mauris pharetra neque hendrerit pulvinar ultricies. 
1. Cras sed diam augue. 
    1. Mauris pharetra neque hendrerit pulvinar ultricies. 
    1. Cras sed diam augue. 
        1. Mauris pharetra neque hendrerit pulvinar ultricies. 
        1. Donec vulputate commodo velit, non sollicitudin quam congue ut. 
        1. Mauris pharetra neque hendrerit pulvinar ultricies. 
    1. Donec vulputate commodo velit, non sollicitudin quam congue ut. 
    1. Mauris pharetra neque hendrerit pulvinar ultricies. 
1. Donec vulputate commodo velit, non sollicitudin quam congue ut. 
    * Mauris pharetra neque hendrerit pulvinar ultricies. 
    * Donec vulputate commodo velit, non sollicitudin quam congue ut. 
        * Mauris pharetra neque hendrerit pulvinar ultricies. 
        * Donec vulputate commodo velit, non sollicitudin quam congue ut. 
        * Mauris pharetra neque hendrerit pulvinar ultricies. 
    * Donec vulputate commodo velit, non sollicitudin quam congue ut. 
1. Mauris pharetra neque hendrerit pulvinar ultricies. 
1. Donec vulputate commodo velit, non sollicitudin quam congue ut. 


**Unordered**
* Cras nisi leo, rhoncus nec ipsum id, feugiat posuere enim. 
* Quisque felis arcu, posuere volutpat feugiat sit amet, lacinia non augue. 
* Sed eget orci in justo suscipit venenatis. 
- Phasellus cursus pulvinar diam, at blandit nisl malesuada vel. 
+ Praesent finibus sapien vitae fermentum euismod. Curabitur eget enim in magna imperdiet lobortis ac et magna. 
    * Nulla id metus varius, dapibus orci sit amet, molestie massa. 
    * Fusce sed ultricies ex. Nam tempus sollicitudin congue. 
    * Fusce malesuada lacus semper sollicitudin suscipit. 
    * In pellentesque orci eget luctus fermentum.
        * Fusce sed ultricies ex. Nam tempus sollicitudin congue. 
            * Fusce malesuada lacus semper sollicitudin suscipit. 
                * In pellentesque orci eget luctus fermentum.
                    * Fusce sed ultricies ex. Nam tempus sollicitudin congue. 
                        * Fusce malesuada lacus semper sollicitudin suscipit. 
                            * In pellentesque orci eget luctus fermentum.

_[Back to Top](#sections)_

## Links

**Inline-style link:**

* Inline-style link:

    * [CodeCamp Schedule](https://condescending-curie-17cf21.netlify.com/#/schedule)

* Inline-style link with title - _hover over the link to see the diff_:

    * [CodeCamp Schedule](https://condescending-curie-17cf21.netlify.com/#/schedule "CodeCamp's Schedule")

**Reference-style link:**

* [CodeCamp Modules w/ reference text][Arbitrary case-insensitive reference text]

[arbitrary case-insensitive reference text]: https://condescending-curie-17cf21.netlify.com/#/modules

_OR_

* [CodeCamp Modules w/ reference number][1]

[1]: https://condescending-curie-17cf21.netlify.com/#/modules

_OR_

* [CodeCamp Modules text as link]

[CodeCamp Modules text as link]: https://condescending-curie-17cf21.netlify.com/#/modules


**Note:**
URLs can turn into links by using angle brackets as well <>

<https://condescending-curie-17cf21.netlify.com/#/modules>

_[Back to Top](#sections)_

## Images

* **Inline-style image:**

![Alternative text for images](https://s1.qwant.com/thumbr/0x380/8/1/cf3ffcdbb68734c99ab9f11de2e4843846f937253adee6df8648ebf1495428/99059361-choose-cat-litter-632x475.jpg?u=https%3A%2F%2Fd17fnq9dkz9hgj.cloudfront.net%2Fuploads%2F2012%2F11%2F99059361-choose-cat-litter-632x475.jpg&q=0&b=1&p=0&a=1)


* **Reference-style image:**

![Alternative text for images][cat]

[cat]: https://s1.qwant.com/thumbr/0x380/8/1/cf3ffcdbb68734c99ab9f11de2e4843846f937253adee6df8648ebf1495428/99059361-choose-cat-litter-632x475.jpg?u=https%3A%2F%2Fd17fnq9dkz9hgj.cloudfront.net%2Fuploads%2F2012%2F11%2F99059361-choose-cat-litter-632x475.jpg&q=0&b=1&p=0&a=1

_[Back to Top](#sections)_

## Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's and Markdown Here -- support syntax highlighting. Which languages are supported and how those language names should be written will vary from renderer to renderer. Markdown Here supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers); to see the complete list, and how to write the language names, see the highlight.js demo page.

Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.

```javascript

var s = "JavaScript syntax highlighting";
alert(s);

```

```html
<b>tag</b>
```

```
<b>tag</b>
```

_[Back to Top](#sections)_

## Tables

Colons can be used to align columns.
There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional.

| Header 1 | Header 2 | Header 3 |
| ---------| -------- | -------- |
| Row1 Col1 | Row1 Col2 | Row1 Col3 |
| Row2 Col1 | Row2 Col2 | Row2 Col3 |
| Row3 Col1 | Row3 Col2 | Row3 Col3 |


Colons can be used to align column content.

| Header 1 | Header 2 | Header 3 |
| ---------| :--------: | --------: |
| R1C1 left | R2C1 center | R2C1 right |
| R2C1 | R2C1 | R2C1 |
| R2C1 | R2C1 | R2C1 |

_[Back to Top](#sections)_

## Blockquotes

Blockquotes are very handy in email to emulate reply text.

> Cras sed diam augue. Mauris pharetra neque hendrerit pulvinar ultricies. Donec vulputate commodo velit, non sollicitudin quam congue ut. Cras nisi leo, rhoncus nec ipsum id, feugiat posuere enim. Quisque felis arcu, posuere volutpat feugiat sit amet, lacinia non augue.
This line is part of the same quote.
> This line is part of the same quote. 

Quote break.
> Sed eget orci in justo suscipit venenatis. Phasellus cursus pulvinar diam, at blandit nisl malesuada vel. Praesent finibus sapien vitae fermentum euismod. Curabitur eget enim in magna imperdiet lobortis ac et magna. Nulla id metus varius, dapibus orci sit amet, molestie massa. Fusce sed ultricies ex. Nam tempus sollicitudin congue. Fusce malesuada lacus semper sollicitudin suscipit. In pellentesque orci eget luctus fermentum.

_[Back to Top](#sections)_

## Inline HTML

Raw HTML can be used!

<d1>
 <dt>Vestibulum mattis vel nulla non pulvinar.</dt>
 <dd>
  Cras sed diam augue. Mauris pharetra neque hendrerit pulvinar ultricies. Donec   vulputate commodo velit, non sollicitudin quam congue ut. Cras nisi leo, rhoncus nec ipsum id, feugiat posuere enim. Quisque felis arcu, posuere volutpat feugiat sit amet, lacinia non augue. Sed eget orci in justo suscipit venenatis.
 </dd>
    
<dt>Phasellus cursus pulvinar diam, at blandit nisl malesuada vel. Praesent finibus sapien vitae fermentum euismod. </dt> 
 <dd>
 Curabitur eget enim in magna imperdiet lobortis ac et magna. Nulla id metus varius, dapibus orci sit amet, molestie massa. Fusce sed ultricies ex. Nam tempus sollicitudin congue. Fusce malesuada lacus semper sollicitudin suscipit. In pellentesque orci eget luctus fermentum.
 </dd>

 Note: Does *not* work **very** well. Use HTML tags.

 _[Back to Top](#sections)_

## Horizontal Rule

Make with:
- hyphens
- asterisks
- underscores

---
A
***
B
___
C
___

_[Back to Top](#sections)_

## Line Breaks

**Note:** One \<enter> does not add a new line break. Two \<enter> adds a new line break.

Vestibulum mattis vel nulla non pulvinar. 
Cras sed diam augue. 

Mauris pharetra neque hendrerit pulvinar ultricies. Donec vulputate commodo velit, non sollicitudin quam congue ut. Cras nisi leo, rhoncus nec ipsum id, feugiat posuere enim. Quisque felis arcu, posuere volutpat feugiat sit amet, lacinia non augue. Sed eget orci in justo suscipit venenatis. Phasellus cursus pulvinar diam, at blandit nisl malesuada vel. Praesent finibus sapien vitae fermentum euismod. Curabitur eget enim in magna imperdiet lobortis ac et magna. Nulla id metus varius, dapibus orci sit amet, molestie massa. Fusce sed ultricies ex. Nam tempus sollicitudin congue. Fusce malesuada lacus semper sollicitudin suscipit. In pellentesque orci eget luctus fermentum.

_[Back to Top](#sections)_

## [Youtube Videos](#youtube-videos)

They can't be added directly but you can add an image with a link to the video like this:


[![Computer Science Crash Course](http://img.youtube.com/vi/O5nskjZ_GoI/0.jpg)](http://www.youtube.com/watch?v=O5nskjZ_GoI)

---

_[Back to Top](#sections)_