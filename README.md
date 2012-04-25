# LeetEdit 0.0.1

*LeetEdit* is an HTML editor (WYSIWYG) for Eclipse RCP based on [TinyMCE](http://www.tinymce.com). TinyMCE is a platform independent JavaScript HTML WYSIWYG editor.

2012 by http://tim-pietrusky.de

**Note: This is an early beta version. Please help me find bugs.**

## In Action

![in action](http://tim-pietrusky.de/img/leetedit_preview.png)

## Currently available options

* bold
* italic
* underline
* strike through
* justify left
* justify center
* justify right
* justify full
* bullet-list
* numbered-list
* format
* font
* font-size
* foreground-color
* background-color

## Install via Update-Site

### Add Update-Site

1. In Eclipse open the *Install* dialog with the menu _*Help / Install New Software...*_

2. Push the *Add* button (top right)

3. Name: "LeetEdit - Update-Site"
   Location: http://timpietrusky.github.com/lab/leetedit/update-site

### Install

1. In Eclipse open the *Install* dialog with the menu _*Help / Install New Software...*_

2. Under the *Work with* dropdown select "LeetEdit - Update-Site"

3. Select *LeetEdit* and press _next_

4. Follow the wizard and restart eclipse after completion


## How to use

```java
LeetEdit leetEdit = new LeetEdit(parent, SWT.NONE);

// Set text
leetEdit.setText("LeetEdit is kind of leet.");

// Get text
String text = leetEdit.getText();
```

## License

Dual-licensed under LGPL and EPL.

## Contributors
[igordejanovic](http://github.com/igordejanovic)
