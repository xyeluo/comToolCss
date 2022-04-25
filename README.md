# comToolCss

一些常用到的 css 样式整合成类选择器使用。
使用jsdelivr的cdn：
https://cdn.jsdelivr.net/gh/tk914/comToolCss@v0.0.1/commonTool.min.css

[toc]

## 横向居中

> .com-marginCenter

```css
margin: 0 auto;
```

## 绝对定位垂直居中

> .com-absoultCenter

```css
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
```

## 禁止用户选中

> .com-userNone

```css
-webkit-user-select: none;
-moz-user-select: none;
-ms-user-select: none;
user-select: none;
```

## 溢出隐藏

> .com-overflowHidden

```css
overflow: hidden;
```

## 默认鼠标样式

> .com-mouseDefault

```css
cursor: default;
```

## 手形鼠标

> .com-mousePoint

```css
cursor: pointer;
```

## 强制竖向滚动条

> .com-overflowScroll

```css
overflow: scroll;
overflow-x: hidden;
```

## 左浮动

> .com-floatRight

```css
float: right;
```

## 右浮动

> .com-floatLeft

```css
float: left;
```

## 清除浮动

> .com-clearfix

```css
.com-clearfix {
  *zoom: 1;
}
.com-clearfix:before,
.com-clearfix:after {
  content: "";
  display: inline-block;
  height: 0;
  clear: both;
  visibility: hidden;
}
```
