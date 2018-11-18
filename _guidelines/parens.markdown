---
layout: guideline
title:  "Parentheses"
date: 2018-09-09 00:06:00 +0800
---

Do not put parens next to keywords. Put a space between.

<p class="s-tag-caption do">Good</p>
```c++
if (condition) {

}
```

<p class="s-tag-caption dont">Bad</p>
```c++
if(condition) {

}
```

Keywords are not functions. By putting parens next to keywords keywords and function names are made to look alike.

On the other hand, do put parens next to function names.

<p class="s-tag-caption do">Good</p>
```c++
fibonacci(4);
```

<p class="s-tag-caption dont">Bad</p>
```c++
fibonacci (4);
```
