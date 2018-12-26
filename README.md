# Mastering Markdown

## Paragraphs and Text Decoration

---

_Jonathan_ is really *cool*.

__Jonathan__ is really __cool__.

## Links in Markdown

---

jonathanhoy.com

[My Github](http://github.com/jonathanhoy)

[hackeryou.com](http://hackeryou.com "This is where I learned to code")

[Jonathan][1] is really cool.

[1]: http://jonathanhoy.com

![Alt text](http://unsplash.it/500/500?random "this is the tooltip")

![Cute pup][pup]

[pup]: http://unsplash.it/500/500?image=1012

[![](http://unsplash.it/50/50)](http://unsplash.it/500/500)
or
[<img src="http://unsplash.it/50/50">](http://unsplash.it/500/500)

## Unordered List

---

* milk
* eggs
* bread

+ milk
+ eggs
+ bread

- milk
- eggs
- bread

## Ordered List

---

1. step 1
  * indented
1. step 2
  * indented
    
    this is text
2. step 3

* [ ] Get milk
* [x] Crack eggs
* [ ] Cook bacon

## Blockquotes

---

> quote here
> 
> another **line**

> Do or do not, there is no try
> 
> -**Yoda**

## Codeblocks

---

Here is my code:

```js
const num = 100;
const dog = 'jihyo';
```

```css
body {
  border: 1px solid red;
}
```

Hey did you try `const num = 200;`?

```diff
var x = 100;
- var y = 200;
+ var y = 300;
```

## Tables

---

|Dog's Name|Dog's Age|Dog Type|
|:---|:---:|---:|
|left-aligned|center-aligned|right-aligned|
|Snickers|2|lab|
|Prudence|8|frenchie|