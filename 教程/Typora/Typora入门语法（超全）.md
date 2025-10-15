# Typora入门语法（超全）

## 基础

### 标题级别

语法：# 标题

示例

> # 一级标题
>
> ## 二级标题
>
> ###### 六级标题
>
> ```tex
> # 一级标题
> 
> ## 二级标题
> 
> ###### 六级标题
> ```

### 加粗、倾斜、高亮

语法：**加粗**，*倾斜*，***粗斜***，==高亮==

示例

> **加粗**，*倾斜*，***粗斜***，==高亮==
>
> ```markdown
> **加粗**，*倾斜*，***粗斜***，==高亮==
> ```
>
> 也可用<b>标签
>
> <b>粗体</b>
> 
> ```markdown
> <b>粗体</b>
> ```
>

### 居中、左/右对齐

语法：<center>文本</center>,<p align="left">文本</p>,<p lign="right">文本</p>

示例

> <center>居中</center>
> <p align="left">左对齐</p>
> <p align="right">右对齐</p>
> ```markdown
> <center>居中</center>
> <p align="left">左对齐</p>
> <p align="right">右对齐</p>
> ```
>

### 删除线、下划线

语法：~~删除线~~、<u>下划线</u>

示例

> ~~删除线~~、<u>下划线</u>
>
> ```markdown
> ~~删除线~~、<u>下划线</u>
> ```
>

### 分割线

语法：---(三个或以上-加Enter键)

示例

> ---
>
> ```markdown
> ---
> 
> ```
>

语法<hr>文本</hr>

示例

<hr>我是分割线</hr>

> <hr>我是分割线</hr>
> ```html
> <hr>我是分割线</hr>
> ```
>

### 上下标

语法：上^标^、下~标~

示例

> 上^标^、下~标~
>
> ```markdown
> 上^标^、下~标~
> ```
>

语法：<sup>上标</sup>、<sub>下标</sub>

示例

> 上<sup>标</sup>、下<sub>标</sub>
>
> ```html
> 上<sup>标</sup>、下<sub>标</sub>
> ```
>

### 转义字符

语法：在需要转义的符号前加\

示例

> **粗体**
> \**粗体**
>
> ```markdown
> **粗体**
> \**粗体**
> ```
>
> <www.baidu.com>
> \<www.baidu.com>
> 
> ```html
> <www.baidu.com>
> \<www.baidu.com>
> ```
>

### 引用内容

语法：> 引用内容

示例

> 引用
>
> > 引用的引用
> >
> > ```markdown
> > > 引用
> > >
> > > > 引用的引用
> > ```

### 添加列表

语法：无序列表：*/+/-加空格加列表内容

示例

> - 无序列表
>
> - 可以嵌套
>   * 嵌套成功
>   
>     + 嵌套
>     
>     ```markdown
>     - 无序列表
>     - 可以嵌套
>       * 嵌套成功
>         + 嵌套
>     ```
>

语法：有序列表：1.阿拉伯数字+小数点+空格+列表内容

示例

> 1. 有序列表
> 2. 可以嵌套
>    - 嵌套无序
>      1. 嵌套有序
>      2. 嵌套成功
>      
> ```markdown
> 1. 有序列表
> 2. 可以嵌套
>    - 嵌套无序
>      1. 嵌套有序
>      2. 嵌套成功
> ```
>

### 添加目录

语法：[toc]+Enter键
示例

> [toc]
> 
> ```markdown
> [toc]
> 
> ```

### 脚注及其内容

语法：文本[^脚注序号]、[^脚注序号]:这是脚注的内容。

示例

> 语法：文本[^1]
> 
> ```markdown
> 语法：文本[^脚注序号]
> 
> [^脚注序号]: 这是脚注的内容
> ```
>

## 进阶

### <font color=#ff0000 size=5 face="楷体">字体和颜色</font>

语法：\<font color=颜色代码 size=字号 face="字体名称">文本</font>

示例

> 红色的代码为#ff0000
>
><font color=#ff0000 size=4 face="黑体">红色的代码为#ff0000</font>
>
> ```css
> 红色的代码为#ff0000
> 
> <font color=#ff0000 size=4 face="黑体">红色的代码为#ff0000</font>
> 
> ```

### 设置背景色

语法：<table><tr><td bgcolor=颜色代码>背景色</td></tr></table>

示例

> <table><tr><td bgcolor=#ffff00><font color=#000000 size=4 face="黑体"><center>背景色为黄色</center></font></td></tr></table>
> <table><tr><td bgcolor=#ffff00>背景色为黄色</td></tr></table>
> ```css
> <table><tr><td bgcolor=#ffff00><font color=#000000 size=4 face="黑体"><center>背景色为黄色</center></font></td></tr></table>
> <table><tr><td bgcolor=#ffff00>背景色为黄色</td></tr></table>
> ```

语法：\<span style="background: yellow">文本</span>
示例

> <span style="background: yellow">背景色 </span>
>
> <span style="background: aqua">背景色</span>
>
> <span style="background: #00FFFF;">背景色</span>
>
> <span style="background: rgb(0, 255, 255);">背景色</span>
>
> <span style="background: aqua; padding: 4px 8px; border-radius: 4px;">背景色</span>
>
> <span style="background: aqua; color: darkblue; padding: 4px 8px;">背景色</span>
>
> <span style="background: linear-gradient(45deg, red, blue);">渐变背景色</span>
>
> ```css
> 使用background-color属性:
> <span style="background: yellow">背景色 </span>
> <span style="background: aqua">背景色</span>
> 
> 使用十六进制值：
> <span style="background: #00FFFF;">背景色</span>
> 
> 使用RGB值：
> <span style="background: rgb(0, 255, 255);">背景色</span>
> 
> 添加内边距让效果更好：
> <span style="background: aqua; padding: 4px 8px; border-radius: 4px;">背景色</span>
> 
> 配合文字颜色：
> <span style="background: aqua; color: darkblue; padding: 4px 8px;">背景色</span>
> 
> 设置渐变背景：
> <span style="background: linear-gradient(45deg, red, blue);">渐变背景色</span>
> ```
>
> 1. 线性渐变 (Linear Gradient)基本语法：
>
>
> ```css
> background: linear-gradient(方向, 颜色1, 颜色2, ...);
> ```
>
> 方向示例：
>
> 
> > ```css
> > /* 从上到下（默认） */
> > background: linear-gradient(blue, red);
> > 
> > /* 从左到右 */
> > background: linear-gradient(to right, blue, red);
> > 
> > /* 对角线 */
> > background: linear-gradient(to bottom right, blue, red);
> > 
> > /* 使用角度 */
> > background: linear-gradient(45deg, blue, red);
> > ```
>
>
> 2. 径向渐变 (Radial Gradient)
>
>     基本语法：
>
>     ```css
>    background: radial-gradient(形状 大小 at 位置, 颜色1, 颜色2, ...);
>    ```
> 
>     示例：
>
>     > ```css
>     > /* 圆形渐变 */
>     > background: radial-gradient(circle, blue, red);
>     > 
>     > /* 椭圆形渐变 */
>     > background: radial-gradient(ellipse, blue, red);
>     > 
>     > /* 指定位置 */
>     > background: radial-gradient(circle at center, blue, red);
>     > ```
>     > 
>   
> 3. 锥形渐变 (Conic Gradient)
>
>     基本语法：
>
>     ```css
>    background: conic-gradient(颜色1, 颜色2, ...);
>    ```
> 
>     示例：
>
>     > ```css
>     > /* 简单的锥形渐变 */
>     > background: conic-gradient(red, yellow, green, blue);
>     > 
>     > /* 从特定角度开始 */
>     > background: conic-gradient(from 45deg, red, blue);
>     > ```
>     > 

### 折叠内容

语法: <details>展开后显示的内容<summary>需要点击的标题</summary>展开后显示的内容</details>
示例

><details>展开后显示的内容<summary>需要点击的标题</summary>展开后显示的内容</details>
>
><details>隐藏内容</details>
>我是点我展开隐藏内容 ` 我是点我展开隐藏内容 `
>也可不加标题，效果如下
>隐藏内容
>
>```html
><details>展开后显示的内容<summary>需要点击的标题</summary>展开后显示的内容</details>
><details>隐藏内容</details>
>```

### 页内跳转

#### 跳转到标题所在位置

语法：[点我跳转到标题名称](#标题名称)
示例

>[点我跳转到二级标题](#二级标题)
>```markdown
>[点我跳转到二级标题](#二级标题)
>```
>跳转操作需要按 `Ctrl` 并点击鼠标左键

#### 跳转到页面内任何位置

语法：\<a name="跳转目标名称">锚点名称</a>、\<a href="#跳转目标名称">链接文本</a>
示例

><a name="锚点1">锚点1</a>
><a href="#锚点1">跳转到锚点1</a>
>```html
><a name="跳转目标名称">锚点1</a>
><a href="#跳转目标名称">跳转到锚点1</a>
>```
>相当于设置了一个锚点和一个跳转到锚点的链接，激活该锚点的链接就能跳转到该锚点==
>比如我在==这里==设置一个锚点2的链接，在顶部设置锚点2，点击==这里==看看会发生什么？
>==锚点名称可以是空格，这样锚点就隐形了==
>==注意不要忘记井号 #==

### 插入图片

语法：\![]()
示例

>[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-rQCyjkm8-1589962252550)(1569036943692.jpg)]
>```markdown
>[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-wNY1lS3F-1589962252553)(1569036943692.jpg)]
>```

### 插入链接

#### 行内式

语法：\[链接名称](链接地址 "title属性")
示例
>[google](http://www.google.com "谷歌")
>```markdown
>[google](http://www.google.com "谷歌")
>```
>==链接地址和title属性间要有空格==
>==将鼠标悬停在链接名称上以查看 title 属性（也可没有 title）==
>Typora中链接地址要有`http://`

#### 参考式

语法：\[链接文本][链接标记]、[链接标记]：链接地址 "链接标题"
示例
>[Google][1]、[Baidu][2]
>[1]:http://www.google.com
>[2]:http://www.baidu.com
>```markdown
>[Google][1]、[Baidu][2]
>[1]:http://www.google.com
>[2]:http://www.baidu.com
>```
>链接文字本身也可作链接标记
>[Gnosis][]
>
>[Gnosis]:http://www.gonsis2000.com
>```markdown
>[Gnosis][]
>[Gnosis]:http://www.gonsis2000.com
>```
>参考式链接常用于学术论文以便于统一管理

#### 自动链接

语法<链接地址>
示例

><www.baidu.com>
>```html
><www.baidu.com>
>```
>
>==链接可以是邮箱地址==

### 插入代码

#### 插入单行代码

语法:\`代码`
示例

>`代码`
>```markdown
>`代码`
>```

#### 插入代码块

语法:/```加代码语言名称加回车键
示例
>````markdown
>```markdown
>
>```
>````

