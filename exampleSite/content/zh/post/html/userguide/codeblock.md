---
title: "代码块"
date: 2020-10-21T08:19:01+09:00
draft: false
weight: 4
---

## 代码块的正常使用

````
```javascript
console.log('Hello World!');
```
````

## 您可以将代码块标题和行号设置为 $, > 符号。

````
```>:s22adg.sh
agasgas
```

```$:sadg.sh
agasgas
agasgas
agasgas
agasgas
agasgas
```

```:/etc/profile.java
System.out.println();
```
````

```>:s22adg.sh
agasgas
```

```$:sadg.sh
agasgas
agasgas
agasgas
agasgas
agasgas
```

```:/etc/profile.java
System.out.println();
```

## 你也可以这样做。

````
```javascript:etc/dir/myscript.js
console.log('Hello World!');
```
````

```javascript:etc/dir/myscript.js
console.log('Hello World!');
```

请记住，代码块标题应以扩展名结尾。 （例如：`.js`、`.c`、`.python`）否则，代码块将无法正确呈现

## 我们有一个代码选项卡

方便在不同代码之间切换

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
