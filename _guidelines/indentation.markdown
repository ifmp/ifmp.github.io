---
layout: guideline
title:  "Indentation"
date: 2018-09-09 00:03:00 +0800
---

Use consistent indendation (typically 2, 3 or 4 spaces).
If the indenting level is more than 4 or 5 levels you may think about factoring out code.

<p class="s-tag-caption do">Good</p>
```c++
if (something bad) {
    if (another thing bad) {
        while (more input) {
        }
    }
}
```

<p class="s-tag-caption dont">Bad</p>
```c++
if (something bad) {
if (another thing bad) {
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