---
layout: post
title: "MarkView Advance Features"
category: blog
tags: [markdown, jekyll]
---

## Introduction
Markview advance version current has three execellent Features: **Custom Styling, Footnotes Support**, and **Slides Presentation.**  

### Options Page

Location: `chrome-extension://iaddkimmopgchbbnmfmdcophmlnghkim/options.html`  

![MarkView Options Page](/assets/images/options-v210.png)

## Advance Features

![MarkView Advance Features](/assets/images/adv-v210.png)

### Custom Styling Feature

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

### Footnotes Support Feature
  1. Make sure UNcheck checkbox "Use Slide Style".
  2. Navigate to your markdown page.
  3. Click the browser action icon
  4. Hey, footnotes are presented!
  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-footnotes.md" target="_blank">Sample Online: Footnotes Support</a>
  </div>

#### How To write footnotes:
  * Each footnote need to be in a separate line, start with 0 to 3 space ( less than 4 space).
	Here is an example:

	```
	This! is a test note[^note] this is awesome!
	What it is?  
	  [^note]: this is footnote 

	Ok, got it!
	```


### Slides Presentation Feature
  1. Select checkbox "Use Slide Style" and click "Save My Options"
  2. Navigate to your markdown page (file has "---" at the end to seperate each slide )
  3. Click the browser action icon
  4. Hey, slides are presented!
  <div>
    <a href="http://shaneweng.com/projects/markview/tests/sample-slides.md" target="_blank">Sample Online: Slides Presentation</a>
  </div>

#### How To convert markdown document to slides:
  1. Inside markdown file, use '---' as seperator for each slide, make sure to put '---' at the end of each slide.

### More New Advance Features are coming ...

## Access Advance Feature Steps
  1. In Markview extension [option page](chrome-extension://ckaohobfbknbdldnafchijkpmfkncdml/options.html), 
     Click "Subscribe" Button to go to Paypal subscribe Memebership. Membership has 10 days trial period for free, membership fee is $10 (USD) for 6 months.
  2. After we recieve notice from Paypal when user sign up the membership plan successfully, we will send user email to let he/she sign in Markview Service Server.
  3. Go to Markview Extension Option page, click "Advance Access" to sign in. After sign in successfully, refresh the options.html, you shoud see "Advance Access" button turn Green, you are ready to use Advance features.
  4. If you have any issues regarding access advance features process, send email to: contact@baiyunconsulting.com  

### Three Free Ways to try Advance Features
<div>
  <ol>
    <li>Use share testing account (instant): <br/>
       <p style="margin-left: 50px">email: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;member-test@markviewer.com<br/>
       password: &nbsp;mypassword </p></li>
    <li>Send email to contact@baiyunconsulting.com to request membership 5 days trial period.</li>
    <li>Request Advance Features full access to get first 10 days trial period</li>
  </ol>
</div>

##### Make sure 'Advance Access' button is Green before you use any membership features! 
##### Don't forget to try out sample cases for each feature in below sections.

### Request Advance Features Access Here
<div id="signup">
  <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
  <input type="hidden" name="cmd" value="_s-xclick">
  <input type="hidden" name="hosted_button_id" value="QJMWAN87X9S78">
  <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_subscribe_SM.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
  <img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
  </form>
</div>

## References
  1. [MarkView Free Basic Version Features](http://shaneweng.com/blog/view-markdown-file-with-markview/)
  2. [MarkView Chrome Web Store](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)

---  

{% include analytics.html %}
