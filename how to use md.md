全文来自 [鱼c](https://fishc.com.cn/thread-82341-1-1.html)

使用 Markdown 可以非常容易地为一些单词设置 **加粗** 而为另外一些单词设置 *倾斜*。你甚至可以 [超连接至谷歌！] (http://google.com)

有时候你可能需要带数字的列表：

1. One
2. Two
3. Three

有时候你可能需要带小圆点的列表：

* Start a line with a star
* Profit!

或者：

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

如果你希望嵌入一张图片，可以这么做：

Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![Yaktocat 的图片](https://octodex.github.com/images/yaktocat.png width="200" height="200" )  |  ![hulatocat 的动图](https://octodex.github.com/images/hula_loop_octodex03.gif width="200" height="200")


#![Yaktocat 的图片](https://octodex.github.com/images/yaktocat.png)

%![hulatocat 的动图](https://octodex.github.com/images/hula_loop_octodex03.gif)


# 结构化文件

有时，使用不同级别的标题来构造文档很有用。 用 `#` 开始创建标题。 行中的多个 `##` 表示较小的标题。

### 这是一个三级标题

你可以使用 1个 `＃` 到 6 个 `######` 表示不同尺寸的标题。

如果你想对某段文本进行引用，请在每行之前使用 > 字符：

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway


有很多不同的方式来使用 GitHub 的 markdown 来编写代码。如果你有内联代码块，用反引号包裹起来：`var example = true`。如果你有一个更长的代码块，你可以缩进四个空格：

    if (isAwesome){
      return true
    }

GitHub 还支持称为代码篱笆的功能，它允许多行没有缩进：

```
if (isAwesome){
  return true
}
```

如果你想使用对应语言的语法高亮：

```javascript
if (isAwesome){
  return true
}
```

```python3
def foo():
    if not bar:
        return True
```



GitHub 支持 Markdown 中的许多附加功能，它们可以帮助你引用和链接到别人。如果你想对某人发表评论，你可以在他们的名字前加上 @ 符号：Hey @kneath - 爱你的毛衣！

但我不得不承认，任务列表是我最喜欢的：

- [x] This is a complete item
- [ ] This is an incomplete item

当你在 Issue 的第一条评论中包含任务列表时，你会在 issues 列表中看到一条非常有用的进度条。它也工作在 Pull Requests 上！

还有，当然还可以使用 emoji 表情！:sparkles: :camel: :boom:

## Task Lists（任务列表）

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

如果在 Issue 的第一个评论中包含任务列表，则会在 issue 列表中获得一个便捷的进度指示器。它也适用于 Pull Requests！

## Tables（表格）

你可以通过连字符（-）和竖线（|）来创建一个表格，其中连字符用于分割行，竖线用于分割列：

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

## SHA 引用

对提交的 SHA-1 哈希的任何引用将自动转换为 GitHub 上该提交的链接。

16c999e8c71134401a78d4d46435517b2271d6ac

mojombo@16c999e8c71134401a78d4d46435517b2271d6ac

mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

## 在仓库中的 Issue 引用

#1

mojombo#1

mojombo/github-flavored-markdown#1

## 删除线

任何使用两个波浪符号包裹的单词（如 ~~this~~ ）会出现删除线。

