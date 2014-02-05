---
layout: post
title: "MarkView Advanced Features"
category: blog
tags: [markdown, jekyll]
---

### Introduction
MarkView advanced version current has FOUR excellent Features: **Visual Editor**, **Custom Styling**, **Footnotes Support**, and **Slides Presentation.**  

<iframe width="640" height="480" src="//www.youtube.com/embed/1BQmsd2v-Hg" frameborder="0" allowfullscreen></iframe>

*Options Page*

Location: `chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html`  
<br/>
![MarkView Options Page](/assets/images/options.png)
<br/>

### Access Advanced Features

#### Public Account for Advanced Feature Access
<div>
  click 'Advanced Feature Access' button, when asked for login, enter:
  <br/><br/>
  <p style="margin-left: 50px">email: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;guest@markviewer.com<br/>
  password: &nbsp;mypassword </p>

  <p>Login page will <strong>Close Automatically</strong> after login sucessfully. Refresh this options page to make sure 'Advanced Feature Access' button is <strong>Green</strong> before using advanced features!</p>
  <p>If you have any questions regarding to the process of advanced feature access, send email to: contact@baiyunconsulting.com</p>
</div>

### Advanced Features

#### 1. Visual Markdown Editor
![Visual Markdown Editor](/assets/images/editor-v221.png)
<br/><br/>

  - WYSIWYG Markdown editor: What you see is what you get
  - Easy to use: edit area and preview area side by side, instant update
  - Auto-save editing document inside browser by every 10 seconds.
  - Be able to open file from local disk and save(download) file to local disk.
  - Both editor and preview have syntax highlight, editor also show line number, fold/unfold ability.
  - **Usage:** 
    1. Go to optiongs.html -> click "Advance Access" and input login info. 
    2. Refresh optiongs.html page to see "Advance Access" turn Green, then click "Open Markdown Editor".

  <div><a href="http://shaneweng.com/projects/markview/tests/sample-editor.md" target="_blank">Sample Online: Editor Startup File</a>
  </div>

<br/>
![MarkView Advanced Features](/assets/images/slides.png)

<br/>

#### 2. Custom Styling Feature

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

#### 3. Footnotes Support Feature
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


#### 4. Slides Presentation Feature
  1. Select checkbox "Apply Slide Format" and click "Save Options"
  2. Navigate to your markdown page (file has "---" at the end to seperate each slide )
  3. Click the browser action icon, Slides will show up.
  4. Use keyboard's ^ and v to select slides themes, use > and < to go through each slide.
  5. Full Presentation Mode: Chrome -> View -> Enter Presentation Mode

  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-slides.md" target="_blank">Sample Online: Slides Presentation</a>
  </div>

##### How To convert markdown document to slides:
  1. Inside markdown file, use '---' as seperator for each slide, make sure to put '---' at the end of each slide.

#### More New Advanced Features are coming ...

<br/>

### References
  1. [MarkView Chrome Web Store](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)  
  2. [MarkView Basic Features Version](http://shaneweng.com/blog/view-markdown-file-with-markview/)
  3. [MarkView User's Guide in Chinese 中文说明](http://shaneweng.com/blog/MarkView-Guide-in-Chinese/)

---  

{% include analytics.html %}
