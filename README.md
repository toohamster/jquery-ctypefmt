# jquery-ctypefmt

This little beautifier will reformat and reindent bookmarklets, ugly
JavaScript, unpack scripts packed by Dean Edward’s popular packer,
as well as deobfuscate scripts processed by
[javascriptobfuscator.com](http://javascriptobfuscator.com/).

# Usage
You can beautify json,xml,html using jquery-ctypefmt in your web browser.


## JavaScript

As an alternative to the Python script, you may install the NPM package `js-beautify`. When installed globally, it provides an executable `js-beautify` script. As with the Python script, the beautified result is sent to `stdout` unless otherwise configured.

```html
<script src="//yourdomain/jquery.ctypefmt.js"></script>
```

```js
$.cTypeDetect = function(str);// detect your code type: "json,xml or html" will return
$.cTypeParse = function(str, ctype); // parse str and return "json,xml or html" Object, if ctype not set,the type will auto detect.
$.cTypeFmt = function(str, ctype); // format str and return "json,xml or html" style string, if ctype not set,the type will auto detect.
```

# License

You are free to use this in any way you want, in case you find this
useful or working for you but you must keep the copyright notice and license. (MIT)

# Credits

* Created by toohamster, <vb2005xu@qq.com>

jquery-ctypefmt@0.1-0
