# Design Goals for Accessibility
This document is a best practices guideline for UI behavior. Please follow as close as possible and refer to as often as needed.
#### Viewport/Placeholder
- Viewport is synonmous with placeholder
- No horizontal scrolling within viewport or placeholders
- No large fixed-width elements, adjust content to display appropriatly within width of the placeholder.
- Do not rely on viewport width to render well. Because screen dimensions and width in CSS pixels vary between devices, content should not rely on a particular viewport or placeholder to render width well.
- Do not use absolute CSS widths for page elements. It may cause an element to fall outside of the viewport/placeholder on smaller devices from that of the programed screen size. Do use CSS media queries to determine placeholder arrangements controlled by breakpoints. Use relative width values, such as width: 100%. Also, be careful of using large absolute positioning values. 

#### Breakpoints
-Breakpoints should be used when the elements within a container can be visually represented in an optimum manner. eg.pruduent use of visual real-estate 

#### Typeface
- Open-sans normal
- Open-sans medium
- Open-sans light

#### Color Scheme
- 