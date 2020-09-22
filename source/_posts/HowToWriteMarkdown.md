---
title: Markdownの書き方
date: 2020-09-22 21:21:45
tags:
---

# ExecNoteでのMarkdownの書き方

このページでは、ExecNoteで使用可能なMarkdownの書き方を記載しています

## 段落

```
# Header 1
## Header 2
### Header 3
#### Header 4
```

# Header 1
## Header 2
### Header 3
#### Header 4


## リスト

```
- List 1
- List 2
- List 3
```

- List 1
- List 2
- List 3

## 番号つきリスト

```
1. List 1
1. List 2
1. List 3
```

1. List 1
1. List 2
1. List 3

## 表

|ヘッダ1|ヘッダ2|ヘッダ3|
|-|-|-|
|内容1|内容2|内容3|
|内容1|内容2|内容3|
|内容1|内容2|内容3|


## コード

\`\`\`py
a = 5
b = 10
print("a + b = " + str(a + b))
print("a - b = " + str(a - b))
print("a * b = " + str(a * b))
print("a / b = " + str(a / b))
\`\`\`


```py
a = 5
b = 10
print("a + b = " + str(a + b))
print("a - b = " + str(a - b))
print("a * b = " + str(a * b))
print("a / b = " + str(a / b))
```

**注意**
\`\`\` の右隣にプログラム言語を記述します。

現在、コード実行に対応しているプログラム言語と言語コードは以下のとおりです。

|言語コード|意味|
|-|-|
|py|Python|
|python|Python|
|js|Node JS|
|ps1|PowerShell|

## 斜体

```
*斜体*
```

*斜体*

## 太字

```
**太字**
```

**太字**

## 水平線

```
***
```

***


