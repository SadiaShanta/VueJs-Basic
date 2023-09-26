# For 1st Heading 
## For 2nd Heading 
### For 3rd Heading
#### For 4rd Heading

If you write lines without any syntex it will be a paragraph.

**If you want to make Bold** 

*If you want to make Italic*

**Bold and *Italic* together**
---

1. If you want to create a list
1. you don't need to add numbers. 
1. Markdown handles numbering them based on their order. 
    1. Nest this list item by using Tab.
1. [Unordered list](#unordered-list)
1. [Inline code](#inline-code)
1. [Multiline code](#multiline-code)
1. [Citation](#citation)


---
### Unordered list
- For unordered list 
- you have to use dash 

~~If you want to create a line through the text use 2 Tilde Tilduh~~
### Inline code 
To create InLine code block: `Use one backtick`

### Multiline code
```
If We want to create Multiline code block: We need to use 3 backtick here You can also teel mark down the language you are using in this code blocks
```
```js
var favoriteButton = $('.favBtnList');

    favoriteButton.on("click", function(){
        var currentUrl = window.location.href;
        var movieUid = $(this).data('movie-uid');
        console.log($(this).data('favorite'));
        console.log(movieUid);
        if ($(this).data('favorite') === true) {
            // The button has already been clicked before
            deleteFavoriteMovie(movieUid);
            $(this).data('favorite', false);
            window.location = currentUrl;

        } else {
            addFavoriteMovie(movieUid);
            $(this).data('favorite', true);
            window.location = currentUrl;
        }
    });
```
### Citation

>To create a block quotes you have to use this angel bracket. 
>>For nested block quotes use 2 angel brackets.For citation you can use them like this 
> --<cite>Sadia Jahan Shnata</cite>