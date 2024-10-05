## 段落和换行符

段落只是一行或多行连续的文本。在 markdown 源代码中，段落由多个空行分隔。在Typora中，您只需按下 Return 即可创建新段落。

按 Shift + Return 可创建单个换行符。但是，大多数 markdown 解析器将忽略单行中断，要使其他 markdown 解析器识别您的换行符，可以在行尾留下两个空格，或者插入 .

## 标题

### 这是三级标题

#### 这是四级标题

---

## 有序列表

1. 这是有序列表
2. 

---

## 无序列表

* 这是无序列表 *号

+ +号

- -号

---

### 任务列表

任务列表是标记为[ ]或[x]（未完成或完成）的项目的列表。例如：

- [ ] 未完成任务列表

``` markdown
- [ ] 
```

- [x] 已完成任务列表

``` markdown
- [x] 
```

```markdown
- [ ] 这是一个任务列表项
- [ ] 需要在前面使用列表的语法
- [ ] normal **formatting**, @mentions, #1234 refs
- [ ] 未完成
- [x] 完成
```

您可以通过单击项目前面的复选框来更改完成/未完成状态。

---

## 引用

> 这是引用

---

## 字体
**加粗**

_斜体_

~~删除线~~

---

## 链接

[链接名称](https://www.example.com)

---

## 图片

![图片名称](https://www.example.com/image.jpg)

---

## 表格

| 表头1 | 表头2 | 表头3 |
| --- |
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |

## 代码块

``` markdown
可以做源码展示：
例如：
# 这是一级标题
## 这是二级标题

1. 有序列表

* 无序列表
+ 无序列表
- 无序列表

> 引用

--- 这是分割线

``` markdown 
这是代码块,可以指定特定语法markdown就是语法
      代码块```

- [ ] 未完成任务列表
- [x] 已完成任务列表

*加粗*
_斜体_
~~删除线~~

[链接名称](https://www.example.com)
![图片名称](https://www.example.com/image.jpg)
| 表头1 | 表头2 | 表头3 |
| --- |
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 | 
```
---


