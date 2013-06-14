ADCustomTableView
=============
-------------

An objective-c UITableView subclass which provide a custom cell appearance effect, like slide from right. Click screenshot to see the example video.

[![](https://dl.dropbox.com/u/25847340/ADCustomTableView/screenshot-thumb.png)](https://dl.dropbox.com/u/25847340/ADCustomTableView/video.mp4)

------------
Requirements
============

ADCustomTableView works on any iOS version only greater or equal than 5.0 and is compatible with only ARC projects. It depends on the following Apple frameworks:

* Foundation.framework
* UIKit.framework
* CoreGraphics.framework

You will need LLVM 3.0 or later in order to build ADTickerLabel. 

------------------------------------
Adding ADCustomTableView to your project
====================================

Source files
------------

First way to add the ADCustomTableView to your project is to directly add the source files and resources to your project.

1. Download the [latest code version](https://github.com/Antondomashnev/ADCustomTableView/downloads) or add the repository as a git submodule to your git-tracked project. 
2. Open your project in Xcode, than drag and drop ADCustomTableView.h and ADCustomTableView.m onto your project (use the "Product Navigator view"). Make sure to select Copy items when asked if you extracted the code archive outside of your project. 
3. Include ADGraphView wherever you need it with `#import "ADCustomTableView.h"`.

-----
Usage
=====

Just make your tableView a class of ADCustomTableView

```objective-c
UITableView *myTableView = [[ADCustomTableView alloc] initWithFrame:self.view.bounds style:UITableViewStylePlain];
//Rest of tableView initialization code
```

Also you can see the example of usage in ViewController.m in demo project.

-------
License
=======

This code is distributed under the terms and conditions of the MIT license. 

----------
Change-log
==========

**Version 0.5** @ 15.6.13

- Initial release.
