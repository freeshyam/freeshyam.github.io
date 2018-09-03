---
layout: single
title: "Take k elements at a time from an iterable"
date: 2018-09-01 21:50:00 -0700
categories: python generators
---

The following is a Python generator function that takes k elements at a time from an iterable (as a k-tuple). If 0 < g < k elements remain to be taken from the iterable, a g-tuple is the last thing returned.

{% highlight python %}
from itertools import islice

def take(iterable, k):
    it = iter(iterable)
    chunk = tuple(islice(it, k))
    while chunk:
        yield chunk
        chunk = tuple(islice(it, k))
{% endhighlight %}

```python
list(take(range(11), 3))

# [(0, 1, 2), (3, 4, 5), (6, 7, 8), (9, 10)]
```

```python
fruits = ['mango', 'apple', 'pineapple', 'cherry',
          'orange', 'jackfruit', 'pear', 'banana',
          'jujube', 'durian']

for grouping in take(fruits, 3):
    print(*grouping, sep=', ')

# mango, apple, pineapple
# cherry, orange, jackfruit
# pear, banana, jujube
# durian
```
