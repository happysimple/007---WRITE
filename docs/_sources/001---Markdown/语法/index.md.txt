[TOC]

# Markdown语法

## 1.标题

```bash
#
##
###
####
#####
######
```

## 2.强调

```bash
**HappyLaber**
```

## 3.斜体

```bash
*HappyLaber*
```

## 4.删除线

```bash
~~HappyLaber~~
```

## 5.高亮

```bash
==HappyLaber==
```

## 6.代码

```bash
`HappyLaber`
```

````bash
```matlab
HappyLaber
```
````

## 7.引用

```bash
> HappyLaber
```

##  8.列表

```bash
- HappyLaber
```

```bash
1. HappyLaber
```

## 9.上下标

```bash
2^3^
```

2^3^

```bash
H~2~O
```

H~2~O

## 10.链接

```bash
[baidu](https://www.baidu.com)
```

```
[1.标题](# 1.标题)
```

## 11.任务列表

```bash
- [ ] HappyLaber
- [x] HappyLaber
```

- [ ] HappyLaber
- [x] HappyLaber

## 12.表格

```bash
| 学号 | 姓名 | 年龄 |
| :--- | :---: | ---: |
| 21407010770 | 董硕 | 20 |
| 17110901065 | 王开心 | 23
```

| 学号        |  姓名  | 年龄 |
| :---------- | :----: | ---: |
| 21407010770 |  董硕  |   20 |
| 17110901065 | 王开心 |   23 |

## 13.目录

```bash
[TOC]
```

## 14.图片

```
![fig.1](1.jpg)
```

```bash
<img src="1.jpg" style="zoom:50%;" />
```

## 15.分割线

```bash
---
```

## 16.Emoji表情

```bash
🏠
```

- 详情见[Emoji网站](https://emojipedia.org/apple/)

## 17.内联 HTML 代码

- 居中

  ```bash
  <center>我居中了!</center>
  ```

  <center>我居中了!</center>

- 下划线

  ```bash
  <center><u>我有下划线了!</u></center>
  ```

  <center><u>我有下划线了!</u></center>

- 前景色

  ```bash
  <center><font style="color:red">我有颜色了!</font></center>
  <center><font style="color:rgb(200,200,200)">我有颜色了!</font></center>
  ```
  
  <center><font style="color:rgb(200,200,200)">我有颜色了!</font></center>

- 后景色

  ```bash
  <center><font style="background:blue">我有颜色了!</font></center>
  <center><font style="background:rgb(200,200,200)">我有颜色了!</font></center>
  ```

  <center><font style="background:rgb(200,200,200)">我有颜色了!</font></center>

- 字体大小

  ```bash
  <center><font size=5>我变大了!</font></center>
  ```

  <center><font size=5>我变大了!</font></center>

## 18.数学公式

```bash
$a+b=c$
```

$a+b=c$

```bash
$$
a+b=c
$$
```

$$
a+b=c
$$

## 19.流程图

````bash
```mermaid
graph TD
    开始 --> 开心 --> 结束
    开始 --> 董硕 --> 结束
```
````

```mermaid
graph TD
    开始 --> 开心 --> 结束
    开始 --> 董硕 --> 结束
```

## 20.饼图

````bash
```mermaid
pie title Pie Chart
"Dogs" : 386
"cats" : 567
"rabbit" : 700
```
````

```mermaid
pie title Pie Chart
"Dogs" : 386
"cats" : 567
"rabbit" : 700
```

## 21.参考文献

这里有一个脚注[^1]

---

[^1]:张亭,赵庆鑫,钟慧鑫,张一彬,朱云聪,冯建迪.国际参考电离层2016模型在陆海区域的精度分析[J].测绘科学,2021,46(09):14-33.DOI:10.16251/j.cnki.1009-2307.2021.09.003.

## 22.Keyboard

<kbd>space</kbd>

## 23.注释

```bash
<!-- 这是个注释 -->
```



