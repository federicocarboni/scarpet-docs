---
title: sort()
name: sort
signatures:
  - params:
      - name: list
  - params:
      - name: args
        rest: true
---

Sorts in the default sortographical order either all arguments, or a list if its
the only argument. It returns a new sorted list, not affecting the list passed
to the argument

```scarpetsort(3,2,1) => [1, 2, 3]
sort('a',3,11,1)  => [1, 3, 11, 'a']
list = [4,3,2,1]; sort(list)  => [1, 2, 3, 4]
```
