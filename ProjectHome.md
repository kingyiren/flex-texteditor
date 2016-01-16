The Flex Rich Text Editor mimics the popular Microsoft Word document editor. It is aimed at flex developers who want to integrate a word like editor into their flex applications.

## Features ##
The editor itself is relatively basic. It includes most of the core features for any given editor.

Features include:
  * WYSIWYG
  * Font size adjustments
  * Font selection
  * Text alignment
  * Text colour selection
  * Text formatting (bold, italic and underline)
  * Text indentation
  * Document Zoom In/Out
  * Text copy/paste (using shortcuts ctrl+c and ctrl+p)
  * Full page selection using ctrl+a

## Pictures ##
[Please Click here for a screenshot](http://img339.imageshack.us/img339/7526/flexeditor.png)

## Bugs ##
There is one current UI bug which I cannot fix:

  1. There is some padding which has created a slight overflow on the horizontal scrollbar. If you manage to fix this then please drop me an email so I can update the code.

Please report any bugs by clicking the Issues tab and selecting 'New Issue'. Alternatively, you can drop me an email at shadybee.dev@gmail.com

## Website ##
[www.ShadyBee.com](http://www.shadybee.com)


---


## Release Change Log ##

**15.10.2009** - v1.0.1 <br />
_Nine fixes_
  1. UI FIX: verticalScrollBar has been removed from the textarea
  1. FIXED: New textareas were not scaling properly
  1. FIXED: Text would disappear whenever user would change textsize
  1. FIXED: Text format would be lost on text selection (ctrl+a)
  1. FIXED: Textarea would disappear on manual page zoom in input
  1. FIXED: When moving from one textarea to another via the enter button the cursor would go to the end of the text on the line when it should go to the first letter on the line.
  1. FIXED: Pressing backspace would cause text to be copied to previous textarea but the copied text would not be deleted from the existing textarea
  1. FIXED: Selecting all text (ctrl+a) whilst there are more than one textareas would copy data from the first textarea into all other textareas
  1. FIXED: Pressing backspace on first textarea would throw an exception