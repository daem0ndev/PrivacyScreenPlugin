PivacyScreenPlugin
==================

Both iOS (as of iOS 7) and Android have app switchers that display a screenshot of your app.

This is a lovely feature for most apps, but if your app displays sensitive information this is a possible privacy risk.

This plugin flags your app so that it doesn't show your users' sensitive data in the task switcher. It sets the [FLAG_SECURE](http://developer.android.com/reference/android/view/WindowManager.LayoutParams.html#FLAG_SECURE) flag in Android and hides the window in iOS.

Installation
------------

For Cordova 3.x.x:

1. To add this plugin just type: `cordova plugin add https://github.com/devgeeks/PrivacyScreenPlugin.git` or `phonegap local plugin add https://github.com/devgeeks/PrivacyScreenPlugin.git`
2. To remove this plugin type: `cordova plugin remove org.devgeeks.PrivacyScreenPlugin` or `phonegap local plugin remove org.devgeeks.PrivacyScreenPlugin`

Usage:
------

This plugin exposes no interface, it simply sets your app to be private. You don't need to do anything except install the plugin.

## License

The MIT License

Copyright (c) 2014 Tommy-Carlos Williams (http://github.com/devgeeks)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
