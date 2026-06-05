# Markdown 基本格式学习

## 一、标题（Headings）

使用 `#` 符号创建标题，最多支持6级标题。

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

---

## 二、段落（Paragraphs）

这是一个普通的段落。段落之间需要空一行来分隔。

这是另一个段落，展示段落之间的换行效果。

---

## 三、粗体与斜体（Bold & Italic）

| 格式 | 语法 | 效果 |
|------|------|------|
| 粗体 | `**文本**` | **粗体文本** |
| 斜体 | `*文本*` | *斜体文本* |
| 粗斜体 | `***文本***` | ***粗斜体文本*** |

---

## 四、列表（Lists）

### 无序列表

- 项目一
- 项目二
- 项目三
  - 子项目 A
  - 子项目 B

### 有序列表

1. 第一步
2. 第二步
3. 第三步
   1. 子步骤 1
   2. 子步骤 2

---

## 五、链接（Links）

### 基本链接
[访问 GitHub](https://github.com)

### 带标题的链接
[GitHub](https://github.com "GitHub官网")

### 引用链接
这是一个[引用链接][1]的示例。

[1]: https://github.com

---

## 六、图片（Images）

### 基本图片
![示例图片](https://picsum.photos/400/200)

### 带标题的图片
![示例图片](https://picsum.photos/400/200 "这是一张示例图片")

---

## 七、代码（Code）

### 行内代码
使用 `console.log()` 输出信息。

### 代码块

```javascript
function hello() {
  console.log("Hello, Markdown!");
}
hello();
```

```python
def greet(name):
    print(f"Hello, {name}!")
    
greet("World")
```

---

## 八、引用（Blockquotes）

> 这是一个引用块。
> 
> 引用可以包含多个段落。

> **嵌套引用**
> > 这是嵌套的引用内容。

---

## 九、表格（Tables）

| 姓名 | 年龄 | 职业 |
|------|------|------|
| 张三 | 25 | 工程师 |
| 李四 | 30 | 设计师 |
| 王五 | 28 | 产品经理 |

### 带对齐的表格

| 左对齐 | 居中对齐 | 右对齐 |
|:------|:-------:|-------:|
| 内容1 | 内容2 | 内容3 |
| 短 | 中等长度 | 这是一段较长的内容 |

---

## 十、分割线（Horizontal Rules）

使用三个或更多的 `-`、`*` 或 `_` 创建分割线。

---
***
___

---

## 十一、任务列表（Task Lists）

- [x] 完成基础学习
- [x] 练习各种格式
- [ ] 创建自己的文档
- [ ] 分享给他人

---

## 十二、删除线（Strikethrough）

~~这是被删除的文本~~

---

## 十三、脚注（Footnotes）

这是一个带脚注的文本[^1]。

[^1]: 这是脚注的内容。

---

## 十四、自动链接

<https://github.com>
<user@example.com>

---

## 十五、颜色格式（Colors）

> **注意**: Markdown 标准语法本身不支持颜色，但许多 Markdown 渲染器（如 GitHub、Typora、VS Code 等）支持使用 HTML 标签或特定语法来设置颜色。

### 1. 使用 HTML `<span>` 标签

<span style="color:red">红色文本</span>
<span style="color:blue">蓝色文本</span>
<span style="color:green">绿色文本</span>
<span style="color:#FF5733">橙色文本（十六进制）</span>
<span style="color:rgb(255, 192, 203)">粉色文本（RGB）</span>

**语法：** `<span style="color:颜色值">文本</span>`

### 2. 使用 HTML `<font>` 标签

<font color="red">红色文本</font>
<font color="#4CAF50">绿色文本</font>
<font color="rgb(76, 175, 80)">深绿色文本</font>

**语法：** `<font color="颜色值">文本</font>`

### 3. 常见颜色名称

| 颜色名称 | 效果 | 颜色名称 | 效果 |
|----------|------|----------|------|
| red | <span style="color:red">红色</span> | blue | <span style="color:blue">蓝色</span> |
| green | <span style="color:green">绿色</span> | yellow | <span style="color:yellow">黄色</span> |
| orange | <span style="color:orange">橙色</span> | purple | <span style="color:purple">紫色</span> |
| gray | <span style="color:gray">灰色</span> | black | <span style="color:black">黑色</span> |

### 4. 背景颜色

<span style="background-color:yellow">黄色背景</span>
<span style="background-color:#E7E9EB">灰色背景</span>
<span style="background-color:rgb(255, 255, 0);color:black">黄色背景黑色文字</span>

**语法：** `<span style="background-color:颜色值">文本</span>`

### 5. 十六进制颜色值

十六进制颜色值格式：`#RRGGBB`

<span style="color:#FF0000">#FF0000 - 红色</span>
<span style="color:#00FF00">#00FF00 - 绿色</span>
<span style="color:#0000FF">#0000FF - 蓝色</span>
<span style="color:#FFFF00">#FFFF00 - 黄色</span>
<span style="color:#FF00FF">#FF00FF - 紫色</span>
<span style="color:#00FFFF">#00FFFF - 青色</span>

### 6. RGB 颜色值

RGB 颜色值格式：`rgb(红色, 绿色, 蓝色)`，每个值范围 0-255

<span style="color:rgb(255, 0, 0)">rgb(255, 0, 0) - 红色</span>
<span style="color:rgb(0, 255, 0)">rgb(0, 255, 0) - 绿色</span>
<span style="color:rgb(0, 0, 255)">rgb(0, 0, 255) - 蓝色</span>
<span style="color:rgb(255, 255, 0)">rgb(255, 255, 0) - 黄色</span>

### 7. 带透明度的 RGBA

RGBA 格式：`rgba(红色, 绿色, 蓝色, 透明度)`，透明度范围 0-1

<span style="color:rgba(255, 0, 0, 1)">不透明红色</span>
<span style="color:rgba(255, 0, 0, 0.7)">半透明红色</span>
<span style="color:rgba(255, 0, 0, 0.4)">较透明红色</span>
<span style="color:rgba(255, 0, 0, 0.1)">几乎透明红色</span>

---

## 练习建议

1. 复制此文件内容
2. 在 Markdown 编辑器中打开
3. 修改内容并预览效果
4. 尝试创建自己的 Markdown 文档