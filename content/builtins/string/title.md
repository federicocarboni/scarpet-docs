---
title: title()
name: title
signatures:
  - params:
      - name: string
---

Returns a new string representing the value of string converted to title case.

### Examples

```scarpet
print(title('heLlo wOrlD')); // 'Hello World'
```

#### Notes

Supplementary unicode characters are not handled. Java whitespace rules are
used.
