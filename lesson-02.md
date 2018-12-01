# Lesson 02

## What Are HTML & CSS?

> HTML, HyperText Markup Language 超文本标记语言
> CSS, Cascading Style Sheets 层叠样式表

CSS should not be written inside of an HTML document and vice versa. As a rule, HTML will always represent content, and CSS will always represent the appearance of that content.

将 CSS 文件独立的放在一个 .css 文件中，是编写前端页面一个优秀的习惯

## Understanding Common HTML Terms

### Element 元素


```html
<a>
```

### Tags 标签

```html
<a>...</a>
```

### Attributes 属性

```html
<a href="http://shayhowe.com/">Shay Howe</a>
```
## Setting Up the HTML Document Structure



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Hello World</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>This is a web page.</p>
  </body>
</html>

```

## Understanding Common CSS Terms

### Selectors 选择器

* Type Selectors 标签选择器

```html
标签名 {
  样式属性: 属性值;
  样式属性: 属性值;
}

p {
  color: red;
  margin: 5px;
}

```

* Class Selectors 类选择器

```html
.className {
  样式属性: 属性值;
  样式属性: 属性值;
}
```

* ID Selectors ID选择器

```html
#id {
  样式属性: 属性值;
  样式属性: 属性值;
}
```


## Referencing CSS

```
<head>
  <link rel="stylesheet" href="main.css">
</head>

```

> 相对路径和绝对路径
> 相对路径： ./ 当前目录 ../ 上级目录

## Using CSS Resets

> 因为不同的浏览器默认的样式是有一定的区别的，比如说边距、边框这样。通过一个全局的 css 样式定义，让后续的 css 编写在一个统一的环境里进行。



```css
/* http://meyerweb.com/eric/tools/css/reset/ 2. v2.0 | 20110126
  License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
  display: block;
}
body {
  line-height: 1;
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}

```












