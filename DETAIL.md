# comToolCss

一些常用到的 css 样式整合成类选择器使用。  
使用 jsdelivr 的 cdn：
https://cdn.jsdelivr.net/gh/tk914/comToolCss@v0.1.0/commonTool.min.css  
网页说明文档：（使用 markdown 转换工具 i5ting_toc）

> https://tk914.github.io/comToolCss/

**使用 scss 语法说明**：

## 清除浮动

> com-clearfix

```css
具体代码：
*zoom: 1;
  &::after {
    clear: both;
  }
  &::before,
  &::after {
    content: "";
    display: table;
  }
```

## 左浮动

> com-float-right

```css
具体代码：
float: left;
```

## 右浮动

> com-float-left

```css
具体代码：
float: right;
```

## 强制显示竖向滚动条

> com-overflow-scroll

```css
具体代码：
overflow: scroll;
overflow-x: hidden;
```

## 水平居中

> com-margin-center

```css
具体代码：
margin: 0 auto;
```

## 绝对定位水平垂直居中

> com-absolute-center

```css
具体代码：
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
```

## 绝对定位垂直居中

> com-absolute-center-y

```css
具体代码：
position: absolute;
top: 50%;
transform: translateY(-50%);
```

## 绝对定位水平居中

> com-absolute-center-x

```css
具体代码：
position: absolute;
left: 50%;
transform: translateX(-50%);
```

## 禁止用户选中

> com-user-none

```css
具体代码：
-webkit-user-select: none;
-moz-user-select: none;
-ms-user-select: none;
user-select: none;
```

## 溢出隐藏

> com-overflow-hidden

```css
具体代码：
overflow: hidden;
```

## 默认鼠标样式

> com-mouse-default

```css
具体代码：
cursor: default;
```

## 手形鼠标

> com-mouse-point

```css
具体代码：
cursor: pointer;
```