---
layout: post
title: "View Markdown File with MarkView"
category: blog
tags: [markdown, jekyll]
---
 
## MarkView

MarkView is a Chrome extention for reading markdown file with
an outline view, support multiple table format styles, code block syntax
highlight and [Github Flavored
Markdown](https://help.github.com/articles/github-flavored-markdown).

<iframe width="420" height="315"
src="//www.youtube.com/embed/GhLN1m2NeUY" frameborder="0"
allowfullscreen></iframe>

<a href="http://v.youku.com/v_show/id_XNjM0MjI1NTI4.html" target="_blank">Same Video on YouKu</a>

### Features

1. Viewing markdown file in web page style.
2. Auto reload local file when file is changed (Post-installation:
select "Allow access to file URLs" option in chrome://extensions/)
3. Show outline beside the content in scrollable way
4. Have buttons for GoTop, ViewSource and GoBottom
5. Support multiple table format styles, code syntax highlight and
[GFM](https://help.github.com/articles/github-flavored-markdown).  
6. Highlight the code area for programming languages(eg. ```ruby)
7. Support web pages printing with decent outlook(Chrome->File->Print...)  
8. Responsive: when the window size small than 940px, outline section
will automatically hidden; resize bigger than 940px, outline section
will display.  
9. MarkView will view all markdown files except those under
raw.github.com because that subdomain only displays the source.

### Sample

#### [Basic Sample Online](http://shaneweng.com/projects/markview/tests/sample-basic.md)  

#### Multiple Table Format Styles

<table>
  <tr>
     <th>Head1</th><th>Head2</th>
  </tr>
  <tr>
     <td>Foo1</td><td>Foo2</td>
  </tr>
  <tr>
     <td>Foo3</td><td>Foo4</td>
  </tr>
</table>  


```html
<table>
  <tr>
     <th>Head1</th><th>Head2</th>
  </tr>
  <tr>
     <td>Foo1</td><td>Foo2</td>
  </tr>
  <tr>
     <td>Foo3</td><td>Foo4</td>
  </tr>
</table>
```

| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |  


```sh
| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |
```

#### Ruby Code   

```ruby
  def test
    puts "Hello World!"
  end
```

#### Code: JavaScript

```javascript
    function myFunction()
    {
      var obj=document.getElementById("h01");
      obj.innerHTML="Hello jQuery";
    }
    onload=myFunction;
```

#### Code: CSS
```css  
  #markdown-container {
    display: inline;
    float: left;
    width: 70%;
    padding: 10px 40px 10px 60px;
    line-height: 1.4em;
    font: 13.34px helvetica,arial,freesans,clean,sans-serif;
    color: black;
  }
```

#### Code: Go 

```go
    package main
    import "fmt"

    func main() {
      fmt.Println("Hello, world.")
    }
```

### Screenshot Sample

![MarkView](/assets/images/screen105.png)

### Markdown Cheat Sheet

![Markdown Cheat Sheet](/assets/images/markdown-cheatsheet.jpg)

Above Cheat Sheet is available through this
[link](http://packetlife.net/media/library/16/Markdown.pdf)

### Support MarkView as a free tool at Chrome Web Store  
<br/>

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

### Chrome Web Store Location

- Project Name: [MarkView](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)  

- Report: [Any Suggestions](https://chrome.google.com/webstore/support/iaddkimmopgchbbnmfmdcophmlnghkim?hl=en&gl=US#bug)

### References  

- For MarkView Membership Features, [click here](http://shaneweng.com/blog/markview-membership-features/)
- About Markdown, see [project
  site](http://daringfireball.net/projects/markdown/)  
- [Github Flavored
  Markdown](https://help.github.com/articles/github-flavored-markdown)  
- Note: Markview code is private, will not be posted in public.
