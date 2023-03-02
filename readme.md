# 积木编程
使用拼积木的方式编程，让编程变得更简单。

Code block:
```json
[
  {
    "model": "assignment",
    "name": "x",
    "value": "123456"
  },
  {
    "model": "assignment",
    "name": "s",
    "value": "\"123456\""
  },
  {
    "model": "console",
    "type": "log",
    "name": "x"
  },
  {
    "model": "console",
    "type": "info",
    "name": "s"
  },
  {
    "model": "operation",
    "type": "incremental",
    "name": "x"
  },
  {
    "model": "operation",
    "type": "multiply",
    "name": "x",
    "value": "x"
  },
  {
    "model": "alert",
    "name": "x"
  },
  {
    "model": "alert",
    "name": "s"
  }
]
```

Code:
```js
let x = 123456;
let s = "123456";
console.log(x);
console.info(s);
x++;
x = x * x;
alert(x);
alert(s);
```