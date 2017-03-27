# F7Colors
An open source tool for Framework7 users to change their application color at anytime, and save the color in memory.
## update
A complete rebuild of color.js removing about 240 lines of code and an update to color.html to work with color.js. if you want to update, put both the html and js file in and swap with the old one's.
## Installaton Guide
first add color.js and color.html to the / of the app, next in your index.html/php file, add this line at the buttom before </body>:
<code><script type="text/javascript" src="color.js"></script></code>. next, we need to put color.html to your index to open. simply link <code>color.html</code> anywhere in your app. and last we need to add F7Color(); to body element, like this <code>onload="F7Color();"</code>
and thats all! 
## Looking for an easier way, or new to F7?
take my Template i made above, or checkout the live Demo at devsquadinc.github.io/F7Colors
Anyone who is using this must have the License and credit located somewhere in their application. 

The MIT License (MIT)

Copyright (c) 2016 S0n1c

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
