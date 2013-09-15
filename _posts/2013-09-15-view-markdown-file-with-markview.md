---
layout: post
title: "View Markdown File with MarkView"
date:   2013-09-15 11:23:00
categories: blog
---
 
## MarkView

MarkView is a Chrome extention for reading markdown file with
an outline view, support multiple table format styles, code block syntax
highlight and [Github Flavored
Markdown](https://help.github.com/articles/github-flavored-markdown).

## Features

1. Viewing markdown file in HTML format
2. Auto reload local file when file is changed
3. Show outline beside the content in scrollable way
4. Have buttons for GoTop, ViewSource and GoBottom
5. Support multiple table format styles, code syntax highlight and
[GFM](https://help.github.com/articles/github-flavored-markdown).  
6. Highlight the code area for programming languages(eg. ```ruby)

## Sample
### Multiple Table Format Styles

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

### Ruby Code   

```ruby
  def test
    puts "Hello World!"
  end
```

### Code: JavaScript

```javascript
    function myFunction()
    {
      var obj=document.getElementById("h01");
      obj.innerHTML="Hello jQuery";
    }
    onload=myFunction;
```

### Code: CSS
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

### Code: Go 

```go
    package main
    import "fmt"

    func main() {
      fmt.Println("Hello, world.")
    }
```

## Screenshot Sample

![MarkView](/images/screen105.png)

## Chrome Web Store Location

- Project Name: [MarkView](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)  

- Report: [Any Suggestions](https://chrome.google.com/webstore/support/iaddkimmopgchbbnmfmdcophmlnghkim?hl=en&gl=US#bug)

## References  

- About Markdown, see [project
  site](http://daringfireball.net/projects/markdown/)  
- [Github Flavored
  Markdown](https://help.github.com/articles/github-flavored-markdown)  
- [Markdown Cheat
  Sheet](http://support.mashery.com/docs/customizing_your_portal/Markdown_Cheat_Sheet)