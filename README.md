Jekyll Watermark
=============================

This is a plugin for [Jekyll](https://github.com/mojombo/jekyll) that is designed to watermark all your images.

Requirements
------------

You must install ImageMagick and add the following lines to your Gemfile:

	gem 'mini_magick'
	gem 'jekyll-minimagick'
	gem 'fileutils'
	
Usage
---------------

 - Copy `watermark.rb` to your `_plugins` directory.
 - Create a `_photos` directory and put your photos in it.
 - Choose 2 stamp images and put them in `/img/watermark-large.png` and `/img/watermark-small.png`.
 - Run Jekyll and the plugin will create in `/photos` the watermarked images with their thumbnails.

License
-------
(The MIT License)

Copyright (c) 2012 Simone Grignola (<http://www.grignola.ch>, <https://github.com/SitoCH>)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the 'Software'), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.