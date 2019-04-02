# Markdown基本用法 

- [Markdown基本用法](#markdown基本用法)
  - [简介](#简介)
  - [演示](#演示)
    - [目录](#目录)
    - [标题](#标题)
    - [文本](#文本)
      - [普通文本](#普通文本)
      - [文本块](#文本块)
      - [换行](#换行)
    - [字体](#字体)
      - [粗体](#粗体)
      - [斜体](#斜体)
      - [粗斜体](#粗斜体)
      - [删除线](#删除线)
      - [下划线（有道支持）](#下划线有道支持)
      - [标记（有道支持）](#标记有道支持)
    - [分割线](#分割线)
    - [列表](#列表)
      - [无序列表](#无序列表)
      - [多级无序列表](#多级无序列表)
      - [有序列表](#有序列表)
      - [多级有序列表](#多级有序列表)
      - [待办事项](#待办事项)
      - [多级待办事项](#多级待办事项)
    - [代码块](#代码块)
    - [表格](#表格)
    - [图片](#图片)
    - [超链接](#超链接)
    - [引用](#引用)
    - [多级引用](#多级引用)
    - [分割线](#分割线-1)
  - [___](#___)
    - [diff](#diff)
    - [绘图（有道云笔记支持）](#绘图有道云笔记支持)
      - [流程图](#流程图)
      - [序列图](#序列图)
      - [甘特图](#甘特图)
      - [数学公式](#数学公式)
    - [常用的Markdown 编辑器](#常用的markdown-编辑器)

## 简介 
## 演示

### 目录


### 标题
标题目前最大支持6个级别，大于6个'#'则无效，多个'#'分别对应多少个级别。其中'#' 和标题必须要用空格分开，不能连接在一起。

# 一级标题  <!-- omit in toc -->
## 二级标题  <!-- omit in toc -->
### 三级标题  <!-- omit in toc -->
#### 四级标题  <!-- omit in toc -->
##### 五级标题  <!-- omit in toc -->
###### 六级标题  <!-- omit in toc -->

### 文本
#### 普通文本
大家好我是小白！

#### 文本块
在文本的开头加上1个Tab或者4个空格即可
    离思五首·其四

    【作者】元稹 【朝代】唐 

    曾经沧海难为水，

    除却巫山不是云。

    取次花丛懒回顾，
    
    半缘修道半缘君。

#### 换行
一行结束时输入两个空格

### 字体

#### 粗体
**粗体1**  
__粗体2__

#### 斜体
*斜体1*  
_斜体2_

#### 粗斜体
***粗斜体1***  
___粗斜体2___  


#### 删除线

~~删除线~~

####  下划线（有道支持）

++ 下划线 ++  

####  标记（有道支持）

== 地方 ==

### 分割线

### 列表
#### 无序列表
无序列表使用星号、加号或是减号作为列表标记：
- 特点
- 功能
- 资料

+ 特点
+ 功能
+ 资料

* 特点
* 功能
* 资料

#### 多级无序列表
- 特点
  - 功能
    - 资料
#### 有序列表
有序列表则使用数字接着一个英文句点：
1. 步骤一
2. 步骤二
3. 步骤三
#### 多级有序列表
1. 步骤一
   1. 步骤二
      1. 步骤二
#### 待办事项
- [x] 待办事项1
- [ ] 待办事项2
#### 多级待办事项
- [x] 待办事项1
  - [ ] 待办事项2
    - [ ] 待办事项2
### 代码块

对方答复地方的负担`alert('Hello World');`大幅度
```java
public static void main(String[]args){} //java
```
```c
int main(int argc, char *argv[]) //C
```
```Bash
echo "hello GitHub" #Bash
```
```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```
```cpp
string &operator+(const string& A,const string& B) //cpp
```
### 表格
功能|性能|
-|-|
功能|心动|

- 对齐
- 混合

### 图片
![显示文本](图片链接地址)

### 超链接
 [百度](https://www.baidu.com)  


### 引用
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.



 This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.



> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

### 多级引用
### 分割线
三个或三个以上的'-','*','_'都可以生成分割线。  

***
___
----


### diff
``` diff
+ dfd
+ dfd
- dfd
- dfdf
+ dfdf
- dfdf
- dfdf
```



### 绘图（有道云笔记支持）
#### 流程图
#### 序列图
#### 甘特图
#### 数学公式 

### 常用的Markdown 编辑器
- OSX
  - VSCode
  - Atom
  - Byword
  - Mou
  - Typora
  - MacDown
  - RStudio
- Linux
  - VSCode
  - Atom
  - Typora
  - ReText
  - UberWriter
  - RStudio
- Windows  
  - VSCode
  - 有道云笔记
  - Atom
  - CuteMarkEd
  - MarkdownPad2
  - Miu
  - Typora
  - RStudio
- iOS
  - Byword
- Android
  - 有道云笔记
  - 印象笔记
- 浏览器插件
  - MaDo (Chrome)
  - Marxico（Chrome）
- 高级应用
  - Sublime Text 3 + MarkdownEditing / 教程 [1] 