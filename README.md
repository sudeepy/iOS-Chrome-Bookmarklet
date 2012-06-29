# Chrome Bookmarklet for iOS
I'm super excited about [Chrome for iOS](http://itunes.apple.com/us/app/chrome/id535886823?mt=8). However, unlike Android, iOS does not allow you to register alternate default browsers. So when you open a link in your email/text message/etc, you're stuck with Safari. Until Apple changes this, here's the next best thing: a bookmarklet to help bridge the gap to Chrome. So now, any page you open in Safari, you can transfer straight to Chrome.

# Setup
Here's the bookmarklet: javascript:window.location=document.location.href.replace('http://','googlechrome://');

For setup instructions, you can follow [this tutorial](http://iosbookmarklets.com/tutorials/pinterest-bookmarklet-ipad/) with following modifications:
* Ignore steps 2 and 3.
* For step 4, copy the code above.
* For step 7, you'll want choose a name like "Open in Chrome."
* For step 8, paste the code above.

That's it! Enjoy [Chrome for iOS](http://itunes.apple.com/us/app/chrome/id535886823?mt=8)!

## License
Copyright (C) 2012 Sudeep Yegnashankaran

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
