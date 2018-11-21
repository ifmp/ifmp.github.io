---
layout: guideline
title:  "Function Names"
date: 2018-09-09 00:01:00 +0800
---

Usually every function performs an action, so the name should make clear what it does.

Suffixes are sometimes useful:
- *max* – to mean the maximum value something can have.
- *cnt* – the current count of a running count variable.
- *key* – key value.

Prefixes are sometimes useful:
- *is* – to ask a question about something. Whenever someone sees *is* they will know it's a question.
- *get* – get a value.
- *set* – set a value.

<p class="s-tag-caption do">Good</p>
```c++
bool is_even(unsigned int i) {
    if (i % 2 == 0) return true;
}

bool is_odd(unsigned int i) {
    if (i % 2 == 1) return true;
}
```

<p class="s-tag-caption dont">Bad</p>
```c++
bool helper1(unsigned int i) {
    if (i % 2 == 0) return true;
}

bool helper2(unsigned int i) {
    if (i % 2 == 1) return true;
}
```
