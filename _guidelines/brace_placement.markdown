---
layout: guideline
title:  "Brace Placement"
date: 2018-09-09 00:04:00 +0800
---

There are two major brace placement strategies that are acceptable:

1. Place brace under and inline with keywords:

<p class="s-tag-caption do">Good</p>
```c++
  if (condition)
  {

  }
```

{:start="2"}
2. Place the initial brace on the same line as the keyword and the trailing brace inline on its own line with the keyword:

<p class="s-tag-caption do">Good</p>
```c++
  if (condition) {

  }
```

You can choose either of the two strategies shown above. However, you should be consistent in using one strategy and not mix them together.

<p class="s-tag-caption dont">Bad</p>
```c++
    if (condition)
        {

        }
```

<p class="s-tag-caption dont">Bad</p>
```c++
    if (condition)
{

          }
```
