

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
