---
title: Convert to string
tags: string
cover: image
firstSeen: 2023-02-25T18:23:29+0000
---

Convert a number into string using '+' operator

- Use concatenation operator followed by empty quotation marks (a + "")

```js
const convertToString = (a) => {
  a = a + "";
  console.log(typeof a);
};
```

```js
convertToString(10); // string
convertToString(10.1); //string
```
