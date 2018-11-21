---
layout: guideline
title:  "Indentation"
date: 2018-09-09 00:03:00 +0800
---

Use consistent indentation (typically 2 spaces).
If the indenting level is more than 4 or 5 levels you may think about factoring out code.

<p class="s-tag-caption do">Good</p>
```c++
if (some_check) {
    if (some_other_check) {
        while (more input) {
        }
    }
}
```

<p class="s-tag-caption dont">Bad</p>
```c++
if (some_check) {
if (some_other_check) {
while (more input) {
}
}
}
```

Further, to make your code more readable, leave one blank space between operators.

<p class="s-tag-caption do">Good</p>
```c++
x = a + b * 3;
```

<p class="s-tag-caption dont">Bad</p>
```c++
x=a+b*3;
```
