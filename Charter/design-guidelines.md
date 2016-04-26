# Technical Guidelines for Accessibility
### ToDo
- [ ] Primary Color Scheme
- [ ] Typeface Weights & Sizes (Open Sans Rendering Problems)
- [ ] FavIcon SVG
- [ ] Apple Touch Icon SVG

This document is a best practices guideline for UI behavior. Please follow as close as possible and refer to as often as needed.

### Viewport/Placeholder
- Viewport is synonymous with placeholder
- No horizontal scrolling within viewport or placeholders
- No large fixed-width elements, adjust content to display appropriately within width of the placeholder.
- Do not rely on viewport width to render well. Because screen dimensions and width in CSS pixels vary between devices, content should not rely on a particular viewport or placeholder to render width well.
- Do not use absolute CSS widths for page elements. It may cause an element to fall outside of the viewport/placeholder on smaller devices from that of the programed screen size. Do use CSS media queries to determine placeholder arrangements controlled by breakpoints. Use relative width values, such as width: 100%. Also, be careful of using large absolute positioning values.

### RWD and Media Queries

The media query has two components:
- media type:screen
- max-device-width: in p


#### Apple Specific Meta Tags

Sets whether a web application runs in full-screen mode.<br>```<meta name="apple-mobile-web-app-capable" content="yes">```

If content is set to yes, the web application runs in full-screen mode; otherwise, it does not. The default behavior is to use Safari to display web content.
You can determine whether a webpage is displayed in full-screen mode using the window.navigator.standalone read-only Boolean JavaScript property.

###### Apple Touch Icon
```<link rel="apple-touch-icon" href="apple-touch-icon.png">
```<br>
Icon Size - 180x180 pixels<br>
[This article discusses the history of the Apple touch icon size](https://realfavicongenerator.net/blog/apple-touch-icon-the-good-the-bad-the-ugly/)

#### Web Based Specifics

###### FavIcon

The current HTML5 specification recommends specifying multiple sizes for the icons, using the attributes rel="icon" sizes="space-separated list of icon dimensions" within a <link> tag.[43] Multiple icon formats, including container formats such as Microsoft .ico and Macintosh .icns files, as well as Scalable Vector Graphics may be provided by including the icon's content type in the format type="file content-type" within the <link> tag.

As of iOS 5, Apple mobile devices ignore the HTML5 recommendation and instead use the proprietary apple-touch-icon method detailed above. The Google Chrome web browser however, will select the closest matching size from those provided in the HTML headers to create 128×128 pixel application icons, when the user chooses the Create application shortcuts... from the "Tools" menu.


### Breakpoints
- Breakpoints should be used in a way that provides optimum visual arrangement of the elements within the container. eg.pruduent use of visual real-estate, consideration of device orientation

### Typeface
- Weights
    - Open-sans normal
    - Open-sans medium
    - Open-sans light
- Sizes
    - h1
    - h2
    - h3
    - h4
    - h5
    - h6
    - p
    - a

### Color Scheme
- A11Y

### Borders
- Borders are to the inside of the placeholder or container. ie. If a placeholder is 52 pixels in width, this remains the same with or without borders.
