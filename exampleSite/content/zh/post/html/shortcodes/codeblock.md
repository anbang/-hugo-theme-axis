---
title: "Code"
date: 2020-10-20T19:19:37+09:00
draft: false
weight: 4
enableToc: false
---

code / codes => 选项卡式代码块。缩进很重要。

## 1. How to use

````
{{</* codes java javascript */>}}
  {{</* code */>}}
  ```java
  System.out.println('Hello World!');
  ```
  {{</* /code */>}}
  {{</* code */>}}
  ```javascript
  console.log('Hello World!');
  ```
  {{</* /code */>}}
{{</* /codes */>}}
````

## 2. 长什么样子

{{< codes java javascript >}}
{{< code >}}

```java
System.out.println('Hello World!');
```

{{< /code >}}
{{< code >}}

```javascript
console.log("Hello World!");
```

{{< /code >}}
{{< /codes >}}
