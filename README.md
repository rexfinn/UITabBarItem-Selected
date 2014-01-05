UITabBarItem+Selected
=====================

Easy to use to init tab bar items, especially helpful when using http://www.glyphish.com.

##Use
This category takes a string name instead of a UIImage, and renders it with `UIImageRenderingModeAlwaysTemplate` and sets it as the normal and selected images for a UITabBarItem.

**Example usage:**
```objective-c
UITabBarItem *tabBarItem = [[UITabBarItem alloc] initWithTitle:@"Title"
                                                                imageName:@"example_icon"
                                                        selectedImageName:@"example_icon_selected"];
viewController.tabBarItem = tabBarItem;

// or, you can use it in viewDidLoad:
self.tabBarItem = [[UITabBarItem alloc] initWithTitle:@"test"
                                                    imageName:@"test"
                                            selectedImageName:@"test"];
```

##License

The MIT License (MIT)

Copyright (c) 2013 Rex Finn

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
