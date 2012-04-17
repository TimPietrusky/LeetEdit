# LeetEdit

*LeetEdit* is an HTML editor for Eclipse RCP based on TinyMCE. 

2012 by http://tim-pietrusky.de

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