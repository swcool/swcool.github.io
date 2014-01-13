---
layout: post
title: "MarkView Advance Features"
category: blog
tags: [markdown, jekyll]
---

### Introduction
MarkView advance version current has three excellent Features: **Custom Styling, Footnotes Support**, and **Slides Presentation.**  

#### Options Page

Location: `chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html`  
<br/>
![MarkView Options Page](/assets/images/options-v221.png)
<br/>
### Advance Features

#### Awesome Markdown Editor
![Awesome Markdown Editor](/assets/images/editor-v221.png)

  - WYSIWYG Markdown editor: What you see is what you get
  - Easy to use: edit area and preview area side by side, instant update
  - Auto-save editing document inside browser by every 10 seconds.
  - Be able to open file from local disk and save(download) file to local disk.
  - Both editor and preview have syntax highlight, editor also show line number, fold/unfold ability.

![MarkView Advance Features](/assets/images/adv-v210.png)

#### Custom Styling Feature

  - Add Theme CSS into Selection  
    More markdown theme css files can be seen from [here](http://jasonm23.github.io/markdown-css-themes/), and [css source](https://github.com/jasonm23/markdown-css-themes) 
  - Add Code Style CSS into Selection  
    More code style css files can be seen from [here](http://highlightjs.org/static/test.html), and [css source](https://github.com/isagalaev/highlight.js)
  - Write CSS in this textarea and save
    1. Select checkbox "Use Custom Style" and click "Save My Options"
    2. Enter the style you like (css) below in textarea and save.
    3. Navigate to your markdown page
    4. Click the browser action icon

  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-custom-style.md" target="_blank">Sample Online: Custom Styling</a>
  </div>

#### Footnotes Support Feature
  1. Make sure UNcheck checkbox "Use Slide Style".
  2. Navigate to your markdown page.
  3. Click the browser action icon
  4. Hey, footnotes are presented!
  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-footnotes.md" target="_blank">Sample Online: Footnotes Support</a>
  </div>

##### How To write footnotes:
  * Each footnote need to be in a separate line, start with 0 to 3 space ( less than 4 space).
	Here is an example:

	```
	This! is a test note[^note] this is awesome!
	What it is?  
	  [^note]: this is footnote 

	Ok, got it!
	```


#### Slides Presentation Feature
  1. Select checkbox "Use Slide Style" and click "Save My Options"
  2. Navigate to your markdown page (file has "---" at the end to seperate each slide )
  3. Click the browser action icon
  4. Hey, slides are presented!
  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-slides.md" target="_blank">Sample Online: Slides Presentation</a>
  </div>

##### How To convert markdown document to slides:
  1. Inside markdown file, use '---' as seperator for each slide, make sure to put '---' at the end of each slide.

#### More New Advance Features are coming ...

<br/>

### Access Advance Features

#### Public Account to Access Advance Features
<div>
  click 'Advance Access' button, when asked for login, enter:
  <br/><br/>
  <p style="margin-left: 50px">email: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;guest@markviewer.com<br/>
  password: &nbsp;mypassword </p>
</div>

- Refresh options page to make sure 'Advance Access' button is Green before using advance features! 
- Don't forget to try sample cases online for each feature. 
- If you have any issues regarding access advance features process, send email to: contact@baiyunconsulting.com

### References
  1. [MarkView Basic Features Version](http://shaneweng.com/blog/view-markdown-file-with-markview/)
  2. [MarkView Chrome Web Store](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)

---  

{% include analytics.html %}
