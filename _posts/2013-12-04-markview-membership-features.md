---
layout: post
title: "MarkView Membership Features"
category: blog
tags: [markdown, jekyll]
---

## Introduction
Markview Memebership current has three execellent Features: **custome style, footnotes**, and **slides.**  

To be able to use membership, user need to sign up the memebership plan
through paypal. Membership has 15 days trial period for free. Membership
fee is $10 (USD) for 6 months.

## Join Membership Steps
  1. In Markview extension [option page](chrome-extension://ckaohobfbknbdldnafchijkpmfkncdml/options.html), 
     Click Paypla "Membership" Button to go to Paypal to apply, Memebership has 15 days trial period.
  2. After we recieve notice from Paypal if user sign up the membership plan successfully, we will send user email to let he/she sign in Markview Service Server. (This may take 5 minutes to 12 hours)
  3. Go to Markview Extension Option page, click "Membership Access" to sign in, after "Membership Access" button 
     turn Green, you are ready to use membership features.
  4. If you have any issues regarding membership process, send email to: contact@baiyunconsulting.com  

**Make sure 'Membership Access' button is Green**  before you use any membership features! 

## Custom Styling Feature
  1. Select checkbox "Use Custome Style" and click "Save My Options"
  2. Enter the style you like (css) below in textarea and save.
  3. Navigate to your markdown page
  4. Click the browser action icon
  5. Hey, CSS is injected!
  6. [Sample online](http://shaneweng.com/projects/markview/tests/sample-custome-style.md)

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
