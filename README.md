# Don't fuck with copy and paste


## Background

It annoys me to no end when a web application prevents me from being able to
paste content into an input field, or copy it out.  If I paste an incorrect
email address, that's my own damn fault.  I use tools like 1Password to
remember all kinds of things for me, and it's actually more error prone for me
to type out all the characters than it is for me to copy from 1Password and
paste into a text box.

## Solution

This is a dead simple Microsoft Edge extension that removes copy and paste
blocking.

## Usage

The easiest way to add a site to the blacklist is to click on the extension
icon ![inactive
icon](https://raw.githubusercontent.com/jswanner/DontFuckWithPaste/09339b4f43d5bac9ddbdeea75051c6d9c017951f/clipboard-inactive-32.png),
then optionally edit the auto-generated pattern, lastly click "Save":

![New pattern dialog
example](https://raw.githubusercontent.com/jswanner/DontFuckWithPaste/73e5d11eba02213ae28ac0ced28f54a1d1af6a09/dialog-example.png)

After that, the extension icon should now be blue, meaning the extension is
active for your current tab: ![active
icon](https://raw.githubusercontent.com/jswanner/DontFuckWithPaste/73e5d11eba02213ae28ac0ced28f54a1d1af6a09/clipboard-active-32.png)

You can use https://jsfiddle.net/k04p7a2h/2/ verify that the extension is successfully installed.

# See Also
- [Don't Fuck With Paste by Aaron Raimist](https://addons.mozilla.org/en-US/firefox/addon/don-t-fuck-with-paste/) for Mozilla
- [Don't Fuck With Paste by Jacob Swanner](https://chrome.google.com/webstore/detail/dont-fuck-with-paste/nkgllhigpcljnhoakjkgaieabnkmgdkb) for Chrome