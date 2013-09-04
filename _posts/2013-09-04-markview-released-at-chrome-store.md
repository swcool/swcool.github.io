---
layout: post
title: "MarkView First Release to Chome Web Store"
date:   2013-09-03 11:23:00
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

```
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

```
| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |
```

### Ruby Code   

{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

```ruby
  def test
    puts "Hello World!"
  end
```

### Code: JavaScript

```
    function myFunction()
    {
      var obj=document.getElementById("h01");
      obj.innerHTML="Hello jQuery";
    }
    onload=myFunction;
```

### Code: CSS
``` css  
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

```
    package main
    import "fmt"

    func main() {
      fmt.Println("Hello, world.")
    }
```

## Chrome Web Store Location

- Project Name: [MarkView](https://chrome.google.com/webstore/detail/markview/iaddkimmopgchbbnmfmdcophmlnghkim)  

- Report: [Any Suggestions](https://chrome.google.com/webstore/support/iaddkimmopgchbbnmfmdcophmlnghkim?hl=en&gl=US#bug)
