# MarkView

MarkView is a Chrome extention for reading markdown file with
an outline view, support Github Flavored Markdown which includeing 
table styles and code block syntax highlight.

## Features

1. Viewing markdown file in HTML format
2. Auto reload local file when file is changed
3. Show outline beside the content in scrollable way
4. Have buttons for GoTop, ViewSource and GoBottom
5. Support Github Flavored Markdown table styles and code highlight.
6. Highlight the code area for programming languages(eg. ```ruby)

## Sample

### Test footnote
[Google][1]  
[Test][2]  
Text[^word] Text

Footnotes:
[1]: http://www.google.com
[2]: This is a test  
[^word]: a note  


See Euclid's 5<sup>th</sup> postulate.

These lines are _going to_ intersect[^1]!

...

[^1]: See Euclid's 5<sup>th</sup> postulate.

### Task List

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del>
  supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


### Test Block

  `\tcode\n\n\tcode\n\n\tcode`
Hello World!\n
\tGood! 
This is test\n\n

> \tcode\n\n\tcode\n\n\tcode

```ruby
\tcode\n\n\tcode\n\n\tcode
```

```
Note line: download if failed, and "reboot".
Note line: download if failed, and "reboot".
Note line: download if failed, and "reboot".
```

    11   Note line: download if failed, and "reboot".
    11   Note line: download if failed, and "reboot".
    11   Note line: download if failed, and "reboot".

Hello world! This is a test:  
    11   Note line: download if failed, and "reboot".
> Email-style angle brackets
> are used for blockquotes.

> > And, they can be nested.

> #### Headers in blockquotes
> 
> * You can quote a list.
> * Etc.

### Test Strike Through
~~abc test~~

### List 
```
+ xxx

1. xxx

2. xxx

- xxx
```

1. good
1. better
1. best
  -  abcd
  -  efg
1. wonderful
  * football
  * basketball
1. great

### Test backtick with list

   - `--recursive`, `-r` — Turn on recursive retrieving.
   - `--level=inf`, `-l 0` — Specify recursion maximum depth  level, i.e., sets infinite recursion depth.
   - `--level=inf, -l 0` — Specify recursion maximum depth level,
i.e., sets infinite recursion depth.
   - `--level=inf`, `-l 0` — Specify recursion maximum depth level, i.e., sets infinite recursion depth.

### Table Styles

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

| Tables        | Are             | Cool   |
| ------------- | :-------------: | -----: |
| `col 3 is`    | right-aligned   | $1600  |
| col 2 is      | centered        | $12    |
| zebra stripes | are neat        | $1     |

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This
| column     |      column |    column
| will       |        will |     will
| be         |          be |      be
| left       |       right |    center
| aligned    |     aligned |   aligned

### Ruby Code   
```ruby
  def test
    puts "Hello World!"
  end
```

### Code: JavaScript

```javascript

function initHighlight(block, flags) {
  try {
    if (block.className.search(/\bno\-highlight\b/) != -1)
      return processBlock(block, true, 0x0F) + ' class=""';
  } catch (e) {
    /* handle exception */

    var e4x =
        &lt;div&gt;Example
            &lt;p&gt;1234&lt;/p&gt;&lt;/div&gt;;
  }
  for (var i = 0 / 2; i &lt; classes.length; i++) { // "0 / 2" should
not be parsed as regexp
    if (checkCondition(classes[i]) === undefined)
      return /\d+[\s/]/g;
  }
}
    function myFunction()
    {
      var obj = document.getElementById('h01');
      obj.innerHTML = "Hello jQuery";
    }
    onload = myFunction;
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

```go
    package main
    import "fmt"

    func main() {
      fmt.Println("Hello, world.")
    }
```

## Change Log
### 0.0.8
  `git pull --tags`  

  `git add .`

  - Using Github like sytles, support Github like table styles.
  - Update the screenshot  

### 0.0.7
  - Move buttons to right bottom corner.
  - Update the screenshot

### 0.0.6
  - move buttons to right to keep outline and buttons in one place;
  - Update outline css to have better fit size  
  
### 0.0.5  
  - Some UI changes: change width percentage; move top, source, bottom to left

### 0.0.4  
  - Used marked.js instead of showdown.js to render MD  

### 0.0.3  
  - Removed container border when print  

### 0.0.2  
  - Add Wiki and Screen Shot

### 0.0.1  
  - Initial  

## License
### Copy Right

## Wiki
### Website 

