---
layout: guideline
title:  "Operators Clarity"
date: 2018-09-09 00:07:00 +0800
---

Use parentheses for clarity, especially with boolean operations.
If you have to think about what is the operator precedence then it's likely that it's unclear other people as well.

<p class="s-tag-caption do">Good</p>
```c++
if ((a || b) && c) {

}
```

<p class="s-tag-caption dont">Bad</p>
```c++
if (a || b && c) {

}
```
