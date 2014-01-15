---
layout: post
title: "MarkView 中文说明"
category: blog
tags: [markdown, jekyll, markview]
---

## 关于 MarkView
MarkView中文意思是“标记显示”，就是使用者在原文做个标记符号，如"#", "##", "~~删除~~"或"- - -"，在浏览器里会鲜明地显示表达含意，非常实用和高效。  

![MarkView Editor: Chinese](/assets/images/editor-v224-cn.png)

## 使用MarkView
1. 安装 [产品地址](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)
2. 安装后到 使用地址 `chrome://extensions/` 找到MarkView ![MarkView](https://raw.github.com/swcool/swcool.github.io/master/assets/images/icon.png), 选取“Enable” 和 “Allow access to file URLs”, 然后点击“Options”
3. 在[Options设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html):
  1. 点击"Advance Acsess", 会跳出页面要求email和密码，分别输入`guest@markviewer.com` 和 `mypassword`， 然后点击”Sign in“登录. 登录页面会关闭，请回到[设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html)
  2. 在[Options设置页面里](chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html),
  涮新页面，"Advance Acsess"会显示绿色，然后点击"Open Markdown Editor" 进入文件编辑器。
  3. 在文件编辑器里，左边是编辑区，右边是浏览器的显示结果。用户可将右边显示结果复制到自己email里发出去。
  4. 以下是例子说明，用户可复制到左边编辑区里，然后看到右边的显示结果。

## 例子说明: 即写即现
> 左边写什么右边就显示什么  

<marquee style="color: red">标示简写易读器</marquee>

### 神奇的“标示简写易读器” MarkView
#### 标记编辑器
* 使用方法
  - **大体**  *斜体*  `代码`  ~~删除~~  
  - [联接](http://google.com 'tooltip')  脚注[^1]
  
  [^1]: 测试

* 代码区
  ```ruby  
    def test
      puts 'hi'
    end
  ```

* 贴图片  
  ![MarkView](https://raw.github.com/swcool/swcool.github.io/master/assets/images/icon.png)  

* 表格

|   表格         |    显示        | 美观    |
| ------------- | :------------- | -----: |
| **第一栏**     | 居中           | $100    |
| `第二栏`       | 向左看齐        | $1600  |
| 第三栏         | 向右看齐        | $12    |
| 每行斑马线显示  | 很漂亮          | $1     |

## 例子原文

	## 例子说明: 即写即现
	> 左边写什么右边就显示什么  

	<marquee style="color: red">标示简写易读器</marquee>

	### 神奇的“标示简写易读器” MarkView
	#### 标记编辑器
	* 使用方法
	  - **大体**  *斜体*  `代码`  ~~删除~~  
	  - [联接](http://google.com 'tooltip')  脚注[^1]
	  
	  [^1]: 测试

	* 代码区
	  ```ruby  
	    def test
	      puts 'hi'
	    end
	  ```

	* 贴图片  
	  ![MarkView](https://raw.github.com/swcool/swcool.github.io/master/assets/images/icon.png)  

	* 表格

	|   表格         |    显示        | 美观    |
	| ------------- | :------------- | -----: |
	| **第一栏**     | 居中           | $100   |
	| `第二栏`       | 向左看齐        | $1600  |
	| 第三栏         | 向右看齐        | $12    |
	| 每行斑马线显示  | 很漂亮          | $1     |


