Image Cache
===========

An image download-and-cacher that also knows how to efficiently generate
and retrieve thumbnails of various sizes.

Android-Image-Cache是一个能够自动判断从内存还是网络获取图片、缓存可以自动回收、自动判断如何有效地生成并检索各种尺寸缩略图的图像download-and-cacher。





Features
--------
只需提供一个适配器即可从光标读取本地、网络URL；
基于一个已下载的图像自动生成并缓存多种尺寸图像；
同时提供磁盘缓存和内存缓存；
自动磁盘缓存管理；不需进行设置，但如果需要的话，参数可进行调整；
根据现有设置进行运作；
光标适配器支持一个ImageView中多个图像字段；当是null或为空时自动跳过；
当加载光标时，光标适配器会有一个自动进度提示条。
* easily integrates into content-provider backed applications, providing an
  adapter that can read local and web URLs from a cursor
* automatic generation and caching of multiple sizes of images based on one
  downloaded asset
* provides a disk cache as well as a memory cache
* automatic disk cache management; no setup necessary, but parameters can be
  fine-tuned if desired
* designed to work with your existing setup: no extending a custom application
  or activity needed
* cursor adapter supports multiple image fields for each ImageView; skips
  fields that are null or empty
* cursor adapter has an automatic progress bar when loading the cursor

Using
-----

Please see the `test/` directory for both a simple example of using it as well as
some unit tests. When running the application in `test/` make sure to run it as
an Android activity if you want to see the demo.

Both the unit tests and the interactive test load some images from our lab's servers.

License
=======

MEL Android Image Cache  
Copyright (C) 2011-2013 [MIT Mobile Experience Lab][mel]

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License version 2.1 as published by the Free Software Foundation.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA

[mel]: http://mobile.mit.edu/
