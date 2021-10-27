+++
title = "什么是 Zola"
date = 2021-10-03

[taxonomies]
tags = ["rust", "other"]
+++

Zola 是一个 Rust 编写的静态博客框架。 

<!-- more -->

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

轻轻地我走了，正如我轻轻地来；我轻轻地招手，作别西天的云彩。

那河畔的金柳，是夕阳中的新娘；波光里的艳影，在我的心头荡漾。

软泥上的青荇，油油的在水底招摇；在康河的柔波里，我甘心做一条水草。

那榆荫下的一潭，不是清泉，是天上的虹，揉碎在浮藻间，沉淀着彩虹似的梦。

寻梦？撑一支长篙，向青草更青处漫溯，满载一船星辉，在星辉斑斓里放歌。

但我不能放歌，悄悄是别离的笙箫；夏虫也为我沉默，沉默是今晚的康桥！

悄悄的我走了，正如我悄悄的来，我挥一挥衣袖，不带走一片云彩。

## 引用

> 轻轻地我走了，正如我轻轻地来；我轻轻地招手，作别西天的云彩。

## 表格

表格并不属于 Markdown 核心规范，但是 Zola 提供了对表格的支持。

   姓名 | 年龄
-------|------
   张三 | 27
   李四 | 23

### 表格中的行内 Markdown

| 表格&nbsp;&nbsp;&nbsp;     | 可以使用&nbsp;&nbsp;&nbsp;  | 行内&nbsp;&nbsp;&nbsp;                | Markdown      |
| ---------- | --------- | ----------------- | ---------- |
| *斜体*  | **粗体**  | ~~删除~~&nbsp;&nbsp;&nbsp; | `代码`     |

## 代码块

#### 使用三个反引号\`表示代码块

```python
prices = {'apple': 0.40, 'banana': 0.50}
my_purchase = {
  'apple': 1,
  'banana': 6
}
grocery_bill = sum(prices[fruit] * my_purchase[fruit]
                   for fruit in my_purchase)
print('I owe the grocer $%.2f' % grocery_bill)
```

## 列表

#### 有序列表

1. 第一项
2. 第二项
3. 第三项

#### 无序列表

* 某一项
* 另一项
* 其他项

#### 多级列表

* 第一级
    1. 第二级
    2. 还是第二级

## 其他元素：缩写、上下标、键位、突出

<abbr title="Graphics Interchange Format">GIF</abbr> 是一个位图格式。

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

按下 <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> 来结束会话。

<mark>蜥蜴</mark>外表有保护色（伪装），使得它们可以很容易地在栖息地中隐藏。