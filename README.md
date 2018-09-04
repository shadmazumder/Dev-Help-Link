# Dev-Help-Link

### iPhone resolutions
**Rasterization** is the process of layouting or rendering the pixes from point. Scale factor, example 2X 3X, are multiplied with the point for getting the pixed based rendering.

**Downsampling** on the case of `6+, 6s+, 7+, 8+` the screen, in pixel, is not exactly 3 times of their point based coordinate system. They have a less dense screen, what does that mean? It simply means that, the `+` series does not have enough pixels to draw the whole points on their screen. Their ppi, Points per Pixel, is lower than the ppi for a pure three times sacle factor(3X). So after the rendering using a three scale factor, 3X, the screen need to be downsampled by `1.15`. Finally it looks like this: `414 X 736 in points` rendered as `3X` makes it `(414*3 X 736*3) = (1242 X 2208) in pixels` and at the end downsampled by `1.15` makes it `(1242*1.15 X 2208*1.15) = (1080 X 1920) device pixels`

Device | Scale factor
--- | ---
iPhone X, iPhone 8 Plus, iPhone 7 Plus, and iPhone 6s Plus | @3x
All other high-resolution iOS devices | @2x

About | Link
--- | ---
iPhone resolutions  | [paintcodeapp](https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions)
iPhone 6 Screens Demystified | [paintcodeapp](https://www.paintcodeapp.com/news/iphone-6-screens-demystified)
iPhone X Screens Demystified | [paintcodeapp](https://www.paintcodeapp.com/news/iphone-x-screen-demystified)

### Doc writing

Topic | Link
--- | ---
Markdown cheatsheet | [adam-p](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables)
