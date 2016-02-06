## Headings

```md
# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1 Alternative H1 Heading
=============================

Alt-H2 Alternative H2 Heading
-----------------------------
```


# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1 Alternative H1 Heading
=============================

Alt-H2 Alternative H2 Heading
-----------------------------

## Code Block

```css
/*Navigation container*/

#navigation {
	position: relative;
	max-width: 800px;
	margin: 0 auto;
	padding: 0 20px;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}
```

## JS Code Block

```js
$(document).ready(function(){  
	$('a#ham').click(function(e){

		if($('#navigation ul').hasClass('nav-open')){
			 $('#navigation ul').removeClass('nav-open');
			 $('a#ham').html('&#9776;');
		} else {
			$('#navigation ul').addClass('nav-open');
			$('a#ham').html('&#x274C;');
		}
	});
});  //end ready
```

## Links

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../basico/blob/gh-pages/index.html)

```md
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../basico/blob/gh-pages/index.html)
```

## Task List

- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links: markdown-test](https://github.com/simplu27/markdown-test), 
**formatting**, and <del>tags</del> 
supported
- [x] list syntax required (any 
unordered or ordered list 
supported)

## Ordered Lists

1. First
2. Second
	1. Second One
	2. Second Two
3. Third
4. Four

```md
1. First
2. Second
	1. Second One
	2. Second Two
3. Third
4. Four
```

## Unordered List

* Uno
* Due
	* Due.1
	* Due2
* Tre
* Quatro

```md
* Uno
* Due
	* Due.1
	* Due2
* Tre
* Quatro
```
