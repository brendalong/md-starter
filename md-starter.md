#Get Started with Markdown

#### Install some help with Sublime
1. Tools >> Command Palette >> Package Controll: Install Package
2. Search for Markdown - there will be several.
3. Be sure to install Markdown Preview which will allow you to view in the browser.

#### Checkout some additional resources:

* Markdown Cheatsheet - https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
* Github Writing - https://help.github.com/categories/writing-on-github/
* Awesome Markdown - https://github.com/mundimark/awesome-markdown

***

## Highlights

* Headlines: use `#` through `######` for h1 - h6
* Inline `code` has `back-ticks around` it.
* Blocks of code can be fenced by lines with three back-ticks ` ``` `

```
Here is a block without a language specified
```

Languages support and how those language names are written will vary from renderer to renderer.
```js
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```

* Links: [Search Google](https://www.google.com)
         or: https://www.google.com

* Italics, with `*asterisks*` or `_underscores_`
     *asterisks* or _underscores_

* Strong aka bold, with `**asterisks**` or `__underscores__`
    **asterisks** or __underscores__

* Lists - all numbered `1.` or `1.` `2.` `3.` Indentation can affect display, too.
```
1. Apple
1. Pear
1. Peach
```

1. Apple
1. Pear
1. Peach

* You can use raw HTML in your Markdown, and it'll mostly work.

<div>
    <input type="text" style="width: 40%" placeholder="How tall should the tree be?">
</div>
<div>
    <input type="text" style="width: 40%" placeholder="Which character should be used?">
</div>

<button>Grow your tree</button>

