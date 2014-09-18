---
layout: post
title: "Markdown Cheat Sheet"
category: blog-tech
tags: [markdown, jekyll]
---

## View in [PDF](http://shaneweng.com/assets/pdf/markdown-cheatsheet.pdf)


## View in HTML as below:

### Header

|   Markdown     | HTML             | View           |
| :------------- | :------------:   | :------------: |
| `# Text`       | `<h1>Text</h1>`  | <h1>Text</h1>  | 
| `## Text`      | `<h2>Text</h2>`  | <h2>Text</h2>  |
| `### Text`     | `<h3>Text</h3>`  | <h3>Text</h3>  | 
| `#### Text`    | `<h4>Text</h4>`  | <h4>Text</h4>  |
| `##### Text`   | `<h5>Text</h5>`  | <h5>Text</h5>  | 
| `###### Text`  | `<h6>Text</h6>`  | <h6>Text</h6>  |

### Emphasis

|   Markdown        | HTML                           |              View             |
| :---------------- | :--------------------------:   | :---------------------------: |
| `*Emphasis*`      | `<em>Emphasis</em>`            | <em>Emphasis</em>             | 
| `_Emphasis_`      | `<em>Emphasis</em>`            | <em>Emphasis</em>             |
| `**Strong**`      | `<strong>Strong</strong>`      | <strong>Strong</strong>       | 
| `__Strong__`      | `<strong>Strong</strong>`      | <strong>Strong</strong>       |
| `*Super*emphasis` | `<em>Super</em>emphasis`       | <em>Super</em>emphasis        | 
| `**Super**strong` | `<strong>Super</strong>strong` | <strong>Super</strong>strong  |

### Links

|   Markdown                               |                              View                    |
| :--------------------------------------  | :--------------------------------------------------: |
| `[Google](http://google.com)`            | <a href="http://google.com">Google</a>               | 
| `[Google](http://google.com "Search")`   | <a href="http://google.com" title="Search">Google</a>|
| `[Google][google]`                       |                                                      | 
| `[google]: http://google.com "Search"`   | <a href="http://google.com" title="Search">Google</a>|
| `<http://google.com>`                    | <a href="http://google.com">http://google.com</a>    | 

### Images

|         Markdown                            |                              View                             |
| :-----------------------------------------  | :-----------------------------------------------------------: |
| `![Alt text](http://bit.ly/19M10jb)`        |<img src="http://bit.ly/19M10jb" alt="Alt text"/>              | 
| `![Alt text](http://bit.ly/19M10jb "Title")`|<img src="http://bit.ly/19M10jb" alt="Alt text" title="Title"/>|
| `![Alt text][img1]`                         |                                                               | 
| `[img1]: http://bit.ly/19M10jb "Title"`     |<img src="http://bit.ly/19M10jb" alt="Alt text" title="Title"/>|

### Horizontal Rules

|   Markdown | HTML      | View    |
| :----------| :-------: | :-----: |
| `***`      | `<hr />`  | <hr />  | 
| `* * *`    | `<hr />`  | <hr />  | 
| `---`      | `<hr />`  | <hr />  | 
| `- - -`    | `<hr />`  | <hr />  | 

### Inline Code

|         Markdown          |                    HTML             |           View                      |
| :-------------------------| :---------------------------------: | :---------------------------------: |
| Use `<div>` tags          | `Use <code>&lt;div&gt;</code> tages`| Use <code>&lt;div&gt;</code> tages  | 
| ` `echo `uname -a` ` `    | `<code>echo `uname -a`</code>`      | <code>echo `uname -a`</code>        | 

### Code Blocks

#### Four space indent

	#include <stdio.h>


#### ``` with programming language name
	```ruby
	def test
	  puts "Hello"
	end
	```

**View**


```ruby
def test
  puts "Hello"
end
```

### Blockquotes `>`

**Source Text**

	> This is the first class item
	> That is the second class item

	> These are the
	third class items

	> Level one
	>
	> > Level two
	> >
	> > > Level three

**View**

> This is the first class item
> That is the second class item

> These are the
third class items

> Level one
>
> > Level two
> >
> > > Level three

### Lists

**Source Text**

	* Sizes
	* Shapes
	* Colors
	  * Blue
	  * Green

	1. First
	2. Second
	3. Third  
	  1. Alpha
	  2. Bravo

**View**

* Sizes
* Shapes
* Colors
  * Blue
  * Green


1. First
2. Second
3. Third
  1. Alpha
  2. Bravo

### Strike

**Source Text**

    ~~Useless, must be removed~~

**View**


~~Useless, must be removed~~


---

## Markdown Cheat Sheet Source

	## Markdown

	### Header

	|   Markdown     | HTML             | View           |
	| :------------- | :------------:   | :------------: |
	| `# Text`       | `<h1>Text</h1>`  | <h1>Text</h1>  | 
	| `## Text`      | `<h2>Text</h2>`  | <h2>Text</h2>  |
	| `### Text`     | `<h3>Text</h3>`  | <h3>Text</h3>  | 
	| `#### Text`    | `<h4>Text</h4>`  | <h4>Text</h4>  |
	| `##### Text`   | `<h5>Text</h5>`  | <h5>Text</h5>  | 
	| `###### Text`  | `<h6>Text</h6>`  | <h6>Text</h6>  |

	### Emphasis

	|   Markdown        | HTML                           |              View             |
	| :---------------- | :--------------------------:   | :---------------------------: |
	| `*Emphasis*`      | `<em>Emphasis</em>`            | <em>Emphasis</em>             | 
	| `_Emphasis_`      | `<em>Emphasis</em>`            | <em>Emphasis</em>             |
	| `**Strong**`      | `<strong>Strong</strong>`      | <strong>Strong</strong>       | 
	| `__Strong__`      | `<strong>Strong</strong>`      | <strong>Strong</strong>       |
	| `*Super*emphasis` | `<em>Super</em>emphasis`       | <em>Super</em>emphasis        | 
	| `**Super**strong` | `<strong>Super</strong>strong` | <strong>Super</strong>strong  |

	### Links

	|   Markdown                               |                              View                    |
	| :--------------------------------------  | :--------------------------------------------------: |
	| `[Google](http://google.com)`            | <a href="http://google.com">Google</a>               | 
	| `[Google](http://google.com "Search")`   | <a href="http://google.com" title="Search">Google</a>|
	| `[Google][google]`                       |                                                      | 
	| `[google]: http://google.com "Search"`   | <a href="http://google.com" title="Search">Google</a>|
	| `<http://google.com>`                    | <a href="http://google.com">http://google.com</a>    | 

	### Images

	|         Markdown                            |                              View                             |
	| :-----------------------------------------  | :-----------------------------------------------------------: |
	| `![Alt text](http://bit.ly/19M10jb)`        |<img src="http://bit.ly/19M10jb" alt="Alt text"/>              | 
	| `![Alt text](http://bit.ly/19M10jb "Title")`|<img src="http://bit.ly/19M10jb" alt="Alt text" title="Title"/>|
	| `![Alt text][img1]`                         |                                                               | 
	| `[img1]: http://bit.ly/19M10jb "Title"`     |<img src="http://bit.ly/19M10jb" alt="Alt text" title="Title"/>|

	### Horizontal Rules

	|   Markdown | HTML      | View    |
	| :----------| :-------: | :-----: |
	| `***`      | `<hr />`  | <hr />  | 
	| `* * *`    | `<hr />`  | <hr />  | 
	| `---`      | `<hr />`  | <hr />  | 
	| `- - -`    | `<hr />`  | <hr />  | 

	### Inline Code

	|         Markdown          |                    HTML             |           View                      |
	| :-------------------------| :---------------------------------: | :---------------------------------: |
	| Use `<div>` tags          | `Use <code>&lt;div&gt;</code> tages`| Use <code>&lt;div&gt;</code> tages  | 
	| ` `echo `uname -a` ` `    | `<code>echo `uname -a`</code>`      | <code>echo `uname -a`</code>        | 

	### Code Blocks

	#### Four space indent

		#include <stdio.h>


	#### ``` with programming language name
		```ruby
		def test
		  puts "Hello"
		end
		```

	**View**


	```ruby
	def test
	  puts "Hello"
	end
	```

	### Blockquotes `>`

	**Source Text**

		> This is the first class item
		> That is the second class item

		> These are the
		third class items

		> Level one
		>
		> > Level two
		> >
		> > > Level three

	**View**

	> Lorem ipsum
	> dolor sit amet

	> Lorem ipsum dolor
	sit amet

	> Level one
	>
	> > Level two
	> >
	> > > Level three

	### Lists

	**Source Text**

		* Sizes
		* Shapes
		* Colors
		  * Blue
		  * Green

		1. First
		2. Second
		3. Third  
		  1. Alpha
		  2. Bravo

	**View**

	* Sizes
	* Shapes
	* Colors
	  * Blue
	  * Green


	1. First
	2. Second
	3. Third
	  1. Alpha
	  2. Bravo

	### Strike

	**Source Text**

	    ~~Useless, must be removed~~

	**View**

	~~Useless, must be removed~~
