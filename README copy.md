##Refactor
##Refactor another teams assignment


###We shortened the css file from 100 lines to 76 lines.

These are the changes:

####Naming:

 * Add "-" to compound names for easy reading
  e.g. titleBar to title-bar

####Short-handed:
 Margin, border, border-radius.e.g.
```css
margin-left: auto;
margin-right: auto;
```
```css
margin: 0 auto;
```

####Deleted unessary specifications on positions. e.g.
```css
.profile-text {
   -  position: absolute;
   -  bottom: 0px;}

    ```
####Deleted unnessary tag. e.g.

    <div></div>


####Deleted z-index.

The css originally had one class *headerimg* set to z-index 1 and *titleBar* at z-index 2. We deleted the z-index setting for headerimg and changed the other to z-index 1.
