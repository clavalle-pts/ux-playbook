# Technical Guidelines for Accessibility
### ToDo
- Primary Color Scheme
- Typeface Weights & Sizes

This document is a best practices guideline for UI behavior. Please follow as close as possible and refer to as often as needed.

#### Viewport/Placeholder
- Viewport is synonmous with placeholder
- No horizontal scrolling within viewport or placeholders
- No large fixed-width elements, adjust content to display appropriatly within width of the placeholder.
- Do not rely on viewport width to render well. Because screen dimensions and width in CSS pixels vary between devices, content should not rely on a particular viewport or placeholder to render width well.
- Do not use absolute CSS widths for page elements. It may cause an element to fall outside of the viewport/placeholder on smaller devices from that of the programed screen size. Do use CSS media queries to determine placeholder arrangements controlled by breakpoints. Use relative width values, such as width: 100%. Also, be careful of using large absolute positioning values. 

#### Breakpoints
- Breakpoints should be used in a way that provides optimum visual arrangement of the elements within the container. eg.pruduent use of visual real-estate, consideration of device orientation

#### Typeface
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

#### Color Scheme
- A11Y

#### Borders
- Borders are to the inside of the placeholder or container. ie. If a placeholder is 52 pixels in width, this remains the same with or without borders.