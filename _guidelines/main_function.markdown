---
layout: guideline
title:  "Main Function"
date: 2018-09-09 00:02:00 +0800
---

The `main` function should always return a value which determines whether your program has terminated successfully.
There are conventions for what sorts of status values certain programs should return.
The most common convention is simply 0 for success and 1 for failure.


<p class="s-tag-caption do">Good</p>
```c++
int main() {
    // perform computation

    if (is_error) {
      // unsuccessful program completion
      return 1;
    }

    // program completed successfully
    return 0;
}
```