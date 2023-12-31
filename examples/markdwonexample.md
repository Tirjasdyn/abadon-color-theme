# This is an H1
## This is an H2
###### This is an H6

This is also an H1
==================

This is also an H2
------------------

Paragraph 1

Paragraph 2

*Italic characters* 
_Italic characters_
**bold characters**
__bold characters__
~~strikethrough text~~

*  Item 1
*  Item 2
*  Item 3
    *  Item 3a
    *  Item 3b
    *  Item 3c

    1.  Step 1
2.  Step 2
3.  Step 3
    1.  Step 3.1
    2.  Step 3.2
    3.  Step 3.3

    1.  Step 1
2.  Step 2
3.  Step 3
    *  Item 3a
	*  Item 3b
	*  Item 3c

    Introducing my quote:

> Neque porro quisquam est qui 
> dolorem ipsum quia dolor sit amet, 
> consectetur, adipisci velit...

Use the backtick to refer to a `function()`.
 
There is a literal ``backtick (`)`` here.

Indent every line of the block by at least 4 spaces.

This is a normal paragraph:

    This is a code block.
    With multiple lines.

Alternatively, you can use 3 backtick quote marks before and after the block, like this:

```
This is a code block
```

To add syntax highlighting to a code block, add the name of the language immediately
after the backticks: 

```javascript
var oldUnload = window.onbeforeunload;
window.onbeforeunload = function() {
    saveCoverage();
    if (oldUnload) {
        return oldUnload.apply(this, arguments);
    }
};
```

This is [an example](http://www.example.com/) inline link.

[This link](http://example.com/ "Title") has a title attribute.

Links are also auto-detected in text: http://example.com/

![Alt text](/path/to/image.jpg)
![Alt text](/path/to/image.png "Optional title attribute")
![Alt text](/url/to/image.jpg)

| Day     | Meal    | Price |
| --------|---------|-------|
| Monday  | pasta   | $6    |
| Tuesday | chicken | $8    |

