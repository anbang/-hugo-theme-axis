+++
author = "朱安邦"
title = "Emoji Support"
date = "2019-03-05"
description = "这篇文章介绍了Emoji表情的支持情况"
tags = [
    "emoji",
]
+++

表情符号可以通过多种方式在 Hugo 项目中启用。

<!--more-->

该[`emojify`](https://gohugo.io/functions/emojify/)函数可以直接在模板或[Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes)中调用。

要全局启用表情符号，请在您的站点[配置](https://gohugo.io/getting-started/configuration/)`enableEmoji`中设置为，然后您可以直接在内容文件中键入表情符号简写代码；例如`true`[](https://gohugo.io/getting-started/configuration/)

<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>

[表情符号备忘单](http://www.emoji-cheat-sheet.com/)是表情符号速记代码的有用参考。

---

**NB**上述步骤在 Hugo 中启用了 Unicode 标准表情符号字符和序列，但是这些字形的呈现取决于浏览器和平台。要设置表情符号的样式，您可以使用第三方表情符号字体或字体堆栈；例如

{{< highlight html >}}
.emoji {
font-family: Apple Color Emoji,Segoe UI Emoji,NotoColorEmoji,Segoe UI Symbol,Android Emoji,EmojiSymbols;
}
{{< /highlight >}}

{{< css.inline >}}

<style>
.emojify {
	font-family: Apple Color Emoji,Segoe UI Emoji,NotoColorEmoji,Segoe UI Symbol,Android Emoji,EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}

@media screen and (max-width:650px) {
.nowrap {
	display: block;
	margin: 25px 0;
}
}
</style>

{{< /css.inline >}}
