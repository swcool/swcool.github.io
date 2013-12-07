---
layout: post
title: "MarkView Membership Features"
category: blog
tags: [markdown, jekyll]
---

## Introduction
Markview Memebership current has three execellent Features: **Custom Styling, Footnotes Support**, and **Slides Presentation.**  

### Public Trial Schedule: Twice A week
  1. Pacific Time Zone(UTC-8): Saturday 8:00 am - Saturday 8:00 pm (12 hours)
  2. Pacific Time Zone(UTC-8): Tuesday  8:00 pm - Wednesday 8:00 am (12 hours)

```
   # Login Info:
   Email:    member-test@markviewer.com
   Password: mypassword
```

<iframe width="420" height="315" src="//www.youtube.com/embed/uNu-lhxo4Vc" frameborder="0" allowfullscreen></iframe>

To be able to use membership, user need to sign up the memebership plan
through paypal. Membership has 10 days trial period for free. Membership
fee is $10 (USD) for 6 months.

## Join Membership Steps
  1. In Markview extension [option page](chrome-extension://ckaohobfbknbdldnafchijkpmfkncdml/options.html), 
     Click Paypal "Membership" Button to go to Paypal to apply, Memebership has 10 days trial period for free.
  2. After we recieve notice from Paypal if user sign up the membership plan successfully, we will send user email to let he/she sign in Markview Service Server. (This may take 1 to 12 hours)
  3. Go to Markview Extension Option page, click "Membership Access" to sign in, after "Membership Access" button 
     turn Green, you are ready to use membership features.
  4. If you have any issues regarding membership process, send email to: contact@baiyunconsulting.com  

**Make sure 'Membership Access' button is Green**  before you use any membership features! 

## Custom Styling Feature
  1. Select checkbox "Use Custom Style" and click "Save My Options"
  2. Enter the style you like (css) below in textarea and save.
  3. Navigate to your markdown page
  4. Click the browser action icon
  5. Hey, CSS is injected!
  6. [Sample online](http://shaneweng.com/projects/markview/tests/sample-custom-style.md)

## Footnotes Feature
  1. Make sure UNcheck checkbox "Use Slide Style".
  2. Navigate to your markdown page.
  3. Click the browser action icon
  4. Hey, footnotes are presented!
  5. [Sample online](http://shaneweng.com/projects/markview/tests/sample-footnotes.md)

### How To write footnotes:
  * Each footnote need to be in a separate line, start with 0 to 3 space ( less than 4 space).
	Here is an example:

	```
	This! is a test note[^note] this is awesome!
	What it is?  
	  [^note]: this is footnote 

	Ok, got it!
	```


## Slide Display Feature
  1. Select checkbox "Use Slide Style" and click "Save My Options"
  2. Navigate to your markdown page (file has "---" at the end to seperate each slide )
  3. Click the browser action icon
  4. Hey, slides are presented!
  5. [Sample online](http://shaneweng.com/projects/markview/tests/sample-slides.md)

### How To convert markdown document to slides:
  1. Inside markdown file, use '---' as seperator for each slide, make sure to put '---' at the end of each slide.

## Join Membership Here

<div id="signup">
    <h5><em>MarkView Membership Subscribe:</em> 10 days trial period for free, <br/>
    (USD) $10/6months, payment handle by PayPal</h5>

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="QJMWAN87X9S78">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_subscribeCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

<br/><br/>
</div>

## References
  1. [MarkView Free Version Features](http://shaneweng.com/blog/view-markdown-file-with-markview/)
  2. [MarkView Chrome Web Store](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)

---  

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-45893255-1', 'markview.herokuapp.com');
  ga('send', 'pageview');

</script>
