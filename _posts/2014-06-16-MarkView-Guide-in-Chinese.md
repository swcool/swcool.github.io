---
layout: post
title: "MarkView 中文说明"
category: blog
tags: [markdown, jekyll, markview]
---

## 关于 MarkView
MarkView中文意思是“标记显示”，就是使用者在原文做个标记符号，如"#", "##", "~~删除~~"或"- - -"，在浏览器里会鲜明地显示表达含意，非常实用和高效。

<embed src="http://player.youku.com/player.php/sid/XNjY5MzgxNTM2/v.swf" allowFullScreen="true" quality="high" width="480" height="400" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>

## 安装 MarkView
1. 安装 <a href="https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim" target="_blank">产品地址</a>
2. 安装后到 使用地址 `chrome://extensions/` 找到MarkView ![MarkView](https://raw.github.com/swcool/swcool.github.io/master/assets/images/icon.png), 选取“Enable” 和 “Allow access to file URLs”, 然后点击“Options”

## 进入高级功能
在[Options设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html):  

1.  点击"进接高级功能", 会跳到登录页面要求email和密码，分别输入`guest@markviewer.com` 和 `mypassword`， 然后点击”Sign in“ 登录。 登录成功后， 登录页面会自动关闭。  

2.  请回到[设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html)， 涮新页面，"进接高级功能"按钮会显示**绿色**。

### 1. 使用编辑器

![MarkView Editor: Chinese](/assets/images/editor-v224-cn.png)

1. 确认"进接高级功能"按钮显示**绿色**，然后点击"进入编辑器"按钮进入文件编辑器。
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

### 2. 展示演示片 
![MarkView Slides](/assets/images/slides-cn-v211.png)

#### 使用步骤
1. 在[设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html)，选择“采用滑动片格式"后，点击“保留选择项"， ““采用滑动片格式"会呈绿色。  
2. 在Chrome浏览器的网址栏输入markdown格式的演示片文件地址，让该文显示在浏览器里。
3. 然后点击浏览器上的“MarkView标示”按钮，这样演示片的形式会显示出来。
4. 用电脑键盘的上^下v键来选择演示展示格式，用左<右>键来浏览演示片
5. 进入全演示展示： Chrome->视图(View)->进入演示模式(Enter Presentation Mode)

  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-slides-cn.md" target="_blank">线上测试样版： 演示简报</a>
  </div>

  <p>样版在slideshare.net上展示</p>
<iframe src="http://www.slideshare.net/slideshow/embed_code/31255232"
width="427" height="356" frameborder="0" marginwidth="0"
marginheight="0" scrolling="no" style="border:1px solid #CCC;
border-width:1px 1px 0; margin-bottom:5px; max-width: 100%;"
allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a
href="https://www.slideshare.net/ShaneWeng/markview-cn"
title="标示简写易读器(MarkView) 演示片"
target="_blank">标示简写易读器(MarkView) 演示片</a> </strong> from
<strong><a href="http://www.slideshare.net/ShaneWeng"
target="_blank">Shane Weng</a></strong> </div>
<br/>  

#### 制作演示片
1. 用Markdown的格式写文档，并以".md"为文件后缀(扩展名).
2. 演示片之间用"---"来隔开，记得将"---"放在每个演示片的最后一行。

### 3. 自动生成滚动内容提纲和列表排序
1. 在[设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html)，退选“采用滑动片格式"后，点击“保留选择项"。如果之前没选，可免做此步。
2. 确认"进接高级功能"按钮显示**绿色**， ”基本功能“->选择区->文件展示类型, 选取“Advanced-Outline".
3. 在Chrome浏览器的网址栏输入markdown格式的文件地址，让该文显示在浏览器里即完成。

![Advanced-Outline](/assets/images/adv-outline.png)

  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-adv.md" target="_blank">线上测试样版： 滚动提纲和列表排序</a>
  </div>

## 参考资料
- [维基百科: Markdown](http://zh.wikipedia.org/wiki/Markdown)  
- [MarkView英文说明：基楚版](http://shaneweng.com/blog/view-markdown-file-with-markview/)  
- [MarkView英文说明：高级版](http://shaneweng.com/blog/markview-advanced-features/)

{% include analytics.html %}
