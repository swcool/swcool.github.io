---
layout: post
title: "MarkView 中文说明"
category: blog
tags: [markdown, jekyll, markview]
---

## 关于 MarkView
MarkView中文意思是“标记显示”，就是使用者在原文做个标记符号，如"#", "##", "~~删除~~"或"- - -"，在浏览器里会鲜明地显示表达含意，非常实用和高效。  

![MarkView Editor: Chinese](/assets/images/editor-v224-cn.png)

## 安装 MarkView
1. 安装 <a href="https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim" target="_blank">产品地址</a>
2. 安装后到 使用地址 `chrome://extensions/` 找到MarkView ![MarkView](https://raw.github.com/swcool/swcool.github.io/master/assets/images/icon.png), 选取“Enable” 和 “Allow access to file URLs”, 然后点击“Options”

## 进入高级功能
在[Options设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html):  

1.  点击"Advanced Feature Acsess", 会跳到登录页面要求email和密码，分别输入`guest@markviewer.com` 和 `mypassword`， 然后点击”Sign in“ 登录。 登录成功后， 登录页面会自动关闭。  

2.  请回到[设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html)， 涮新页面，"Advanced Feature Acsess"会显示**绿色**。

### 1. 编辑器

1. 确认"Advanced Feature Acsess"显示**绿色**，然后点击"Open Markdown Editor" 进入文件编辑器。
2. 在文件编辑器里，左边是编辑区，右边是浏览器的显示结果。用户可将右边显示结果复制到自己email里发出去。
3. 以下是例子说明，用户可复制到左边编辑区里，然后看到右边的显示结果。

- - -

## 例子说明: 即写即现
> 左边写什么右边就显示什么  

<marquee style="color: red">标示简写易读器</marquee>

### 神奇的“标示简写易读器” MarkView
#### 标记编辑器
* 使用方法
  - **粗体**  *斜体*  `代码`  ~~删除~~  
  - [联接](http://google.com 'tooltip')  注释[^1]
  
  [^1]: 具体说明

* 代码区

  ```ruby  
    def test
      puts 'hi'
    end
  ```

* 贴图片  
  ![MarkView](https://raw.github.com/swcool/swcool.github.io/master/assets/images/icon.png)  

* 表格

|   表格         |    文字        | 数据    |
| :-----------: | :------------- | -----: |
| **第一栏**     | 居中           | $100    |
| `第二栏`       | 向左看齐        | $1600  |
| 第三栏         | 向右看齐        | $12    |
| 每行斑马线显示  | 很清楚          | $1     |

### 例子原文

	## 例子说明: 即写即现
	> 左边写什么右边就显示什么  

	<marquee style="color: red">标示简写易读器</marquee>

	### 神奇的“标示简写易读器” MarkView
	#### 标记编辑器
	* 使用方法
	  - **粗体**  *斜体*  `代码`  ~~删除~~  
	  - [联接](http://google.com 'tooltip')  注释[^1]
	  
	  [^1]: 具体说明

	* 代码区
	  ```ruby  
	    def test
	      puts 'hi'
	    end
	  ```

	* 贴图片  
	  ![MarkView](https://raw.github.com/swcool/swcool.github.io/master/assets/images/icon.png)  

	* 表格

	|   表格         |    文字        | 数据    |
	| :-----------: | :------------- | -----: |
	| **第一栏**     | 居中           | $100   |
	| `第二栏`       | 向左看齐        | $1600  |
	| 第三栏         | 向右看齐        | $12    |
	| 每行斑马线显示  | 很清楚          | $1     |

- - -

### 2. 投影片 
![MarkView Slides](/assets/images/adv-v210.png)

#### 使用步骤
1. 在[设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html)，选择“Use Slide Style"后点击“Save My Options"  
2. 在Chrome浏览器的网址栏输入markdown格式的投影片文件地址，让该文显示在浏览器里。
3. 然后点击浏览器上的“MarkView”按钮，这样投影片的形式会显示出来。

线上测试样版：[投影简报](http://shaneweng.com/projects/markview/tests/sample-slides.md)

#### 制作投影片
1. 用Markdown的格式写文档，并以".md"为文件后缀(扩展名).
2. 投影片之间用"---"来隔开，记得将"---"放在每个投影片的最后一行。


## 参考资料
- [维基百科: Markdown](http://zh.wikipedia.org/wiki/Markdown)  
- [MarkView英文说明：基楚版](http://shaneweng.com/blog/view-markdown-file-with-markview/)  
- [MarkView英文说明：高级版](http://shaneweng.com/blog/markview-advanced-features/)

{% include analytics.html %}
