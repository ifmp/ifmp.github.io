---
layout: guideline
title:  "Brace Usage"
date: 2018-09-09 00:05:00 +0800
---

All `if`, `while` and `do while` statements must either have braces or be on a single line.
It ensures that when someone adds a line of code later there are already braces and they don't forget. It provides a more consistent look and this doesn't affect execution speed.

<p class="s-tag-caption do">Good</p>
```c++
if (condition) {
    return 0;
}
```

<p class="s-tag-caption do">Good</p>
```c++
if (condition) ++i;
```

To illustrate what can go wrong consider an example shown below which does not use braces.

<p class="s-tag-caption dont">Bad</p>
```c++
if (condition)
    ++i;
```

The code can be later modified by adding more statements in the if condition but forgetting to put the braces.

<p class="s-tag-caption dont">Bad</p>
```c++
if (condition)
    ++j;
    ++i; // misleading. Seems like it's executed when the conditions is true
```

By mistake, the code is now executing `++i` every time, even when the `condition` is false.
This is because the indentation does not any effect on the scope of statements that belong to the `if`, only braces have.
As a result, the above code is equivalent to:

<p class="s-tag-caption do">Good</p>
```c++
if (condition) {
    ++j;
}
++i;
```

where it is clear that `++i` is executed all the time.

