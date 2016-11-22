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

### Test Block

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

| Tables        | Are             | Cool   |
| ------------- | :-------------: | -----: |
| `col 3 is`    | right-aligned   | $1600  |
| col 2 is      | *centered*      | $12    |
| zebra stripes | **are neat**    | $1     |


| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This
| column     |      column |    column
| will       |        will |     will
| be         |          be |      be
| left       |       right |    center
| aligned    |     aligned |   aligned

| Item       |  Catalog    | Price        | Quantity | Discount | Date
|------------|-------------|--------------|----------|----------|--------------|
| Magic      |        Book |    $10.50    | 15       | 11%      | Feb 15, 2010 10:15 AM
| Travel     |        Book |    $10.50    | 15       | 11%      | Feb 15, 2010 10:15 AM
| Magic      |        Arts |    $500.99   | 20       | 22%      | Feb 15, 2012 11:15 AM
| Tablet     | Electronics |    $399      | 40       | 22.5%    | Mar 5, 2013 9:15 AM
| Laptop     |   Computers |    $599.99   | 25       | 25%      | Dec 10, 2012 11:15 AM
| Ruby       |    Jewelry  |    $999.99   | 18       | 44%      | Jun 15, 2014 6:15 PM

**Note:** Sort multiple columns by holding down the shift key then clicking other header.

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
### 0.0.6 
  - Update  

### 0.0.5  
  - Update

### 0.0.4  
  - Update  

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

