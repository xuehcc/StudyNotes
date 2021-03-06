# HTML 笔记

## HTML实例

- `<!DOCTYPE html>`声明为HTML5文档
- `<html>`元素是HTML页面的根元素
- `<head>`元素包含了文档的元(meta)数据,如`<meta charset="UTF-8" >`定义网页编码格式为UTF-8
- `<title>`元素描述了文档的标题
- `<body>`元素包含了可见的页面内容
- `<h1>`元素定义一个大标题
- `<p>`元素定义一个段落

## 什么是HTML?

HTML是用来描述网页的一种语言

- HTML是指超文本标记语言
- HTML不是编程语言,而是一种是**标记**语言
- 标记语言是一套**标记标签**
- HTML使用标记标签来**描述**网页
- HTML包含了HTML**标签**及**文本**内容
- HTML文档也叫**web页面**

## HTML标签

HTML标记标签称为HTML标签

- HTML标签是由尖括号包围的关键词,比如`<html>`
- HTML标签成对出现,比如`<p>`和`</p>`
- 标签对中第一个是开始标签,第二个是结束标签
- 开始标签和结束标签也称为开放标签和闭合标签

## HTML元素

一个HTML元素包含了开始标签和结束标签

- HTML元素以**开始标签**起始
- HTML元素以**结束标签**终止
- **元素的内容**是开始标签与结束标签之间的内容
- 某些HTML元素具有**空内容**(empty content)
- 空元素**在开始标签中进行关闭**(以开始标签的结束而结束)
- 大多数HTML元素可拥有**属性**

## HTML属性

属性是 HTML元素提供的附加信息

```HTML
`<a href="www.baidu.com">这是一个链接</a>`
```

- HTML元素可以设置**属性**
- 属性可以在元素中添加**附加信息**
- 属性一般描述于**开始标签**
- 属性总是以名称/值对形式出现,比如:name="value"
- 属性值应该始终被包括在引号内

## HTML标题

`<h1>`定义最大标题,`<h6>`定义最小标题

```HTML
<h1>标题1</h1>
```

## HTML水平线

`<hr />`

## HTML注释

`<!-- 注释 -->`

## HTML段落

`<p>段落</p>`

## HTML换行

`<br />`

## HTML链接

```HTML
<a href="www.baidu.com" target="_blank" rel="noopener noreferrer">这是一个链接</a>`<br />
```

target属性可以定义被链接的文档在何处显示

- _blank：新的窗口中打开
- _self：在相同的框架或窗口中打开链接
- _parent：在父窗口中打开链接
- _top：清除所有被包含框架，打开链接

## HTML创建电子邮件链接

```HTML
<a href="mailto:john.shen@jimmychoo.com?cc=xuexhc@gmail.com&bcc=xuexhc@outlook.com&Subject=Hello%20again&body=Thank%20You!" target="_top">发送邮件</a>
```

|参数                  |描述            |
|:-                   |:-              |
| mailto:name@email.com|邮件接收地址    |
| cc=name@email.com    |抄送地址        |
| bcc=name@email.com   |密件抄送地址    |
| subject=subject text |邮件主题        |
| body=body text       |邮件主题        |
| ?                    |第一个参数分隔符 |
| &                    |其他参数分隔符   |




## HTML图像

```HTML
<img src="/images/logo.jpg" height="10" width="10" />
```

## HTML头部


- `<head>`元素

  `<head>`元素包含了所有头部标签元素:`<title>`、`<style>`、`<meta>`、`<link>`、`<script>`、`<noscript>`、`<base>`

- `<title>`元素
  
  `<title>`标签定义了不同文档的标题

  ```HTML
  <title>标题</title>
  ```

- `<base>`元素

  `<base>`标签描述了基本的链接地址/链接目标，该标签为HTML中所有链接标签的默认链接
  ```HTML
  <base href="C:\Users\xue\Desktop\Myproject\images\" traget="_blank">
  ```
  
- `<link>`元素

  `<link>`标签定义了文档与外部资源之间的关系
  `<link>`标签一般用于链接到样式表
  
  ```HTML
  <link rel="stylesheet" type="text/css" href="C:\Users\xue\Desktop\Myproject\CSS\mystyle.css">
  ```
  
  `<link>`标签显示图片
  
  ```HTML
  <link rel="shortcut icon" href="图片url">
  ```

- `<style>`元素

  `<style>`标签定义了HTML文档的样式文件引用地址
  `<style>`元素中可以直接添加样式
  
  ```HTML
  <style type="text/css">
  body {background-color:yellow}
  </style>
  ```

- `<meta>`元素

  `<meta>`标签描述了基本的元数据（网页描述、关键词、作者等）
  
  - 为搜索引擎定义关键词
  
  ```HTML
  <meta name="keywords" content="HTML，CSS，JavaScript">
  ```
  - 为网页定义描述内容
  
  ```HTML
  <meta name="description" content="代码测试">
  ```
  - 定义网页作者
  
  ```HTML
  <meta name="author" content="xhc">
  ```
  - 每30秒刷新当前页面
  
  ```HTML
  <meta http-equiv="refresh" content="30">
  ```

### `<script>`元素
`<script>`标签用于加载脚本文件

### `<header>`元素


## CSS

CSS可以通过以下方式添加到HTML中

- 内联样式：在HTML元素中使用"style"属性
- 内部样式表：在HTML文档头部<head>区域使用<style>元素来包含CSS
- 外部引用：使用外部CSS文件
  
###内联样式





## 小语法

- `%20`显示空格
- ``














