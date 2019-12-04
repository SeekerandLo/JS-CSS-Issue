## display

### 常用

- display: [none](#none);

- display: [block](#block);

- display: [inline](#inline);

- display: [inline-block](#inline-block);

- display: [list-item](#list-item);

- display: [inherit](#inherit);

## none

&emsp;&emsp;当设置为 none 的时候就不显示。一般切换一个模块显示和隐藏时使用它。

## block[默认]

&emsp;&emsp;块级元素，一行一个。元素会自动填满一行。

## inline

- inline 元素一行多个，直到一行放不下为止。

- 宽度随内容变化。

- 同时 width、height 设置失效，竖直方向上的 `margin-top`、`margin-bottom` 也会无效。

## inline-block

&emsp;&emsp;inline 和 block 的结合体，能在一行展示了，也能设置 `width`、`height`、`margin-top`、`margin-bottom` 了。

## list-item

&emsp;&emsp;以 list 的形式展示，特点是前面带一个 ·。如果想修改掉样式，可以使用 list-style
```css
/* 取消样式 */
list-style: none
```

## inherit

&emsp;&emsp;继承父元素 display 的样式
