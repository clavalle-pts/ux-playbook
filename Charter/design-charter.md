# TEAMS Design Charter (Style-guide & Development Process Methodology)

### Preface
1. This is an living, evolving document, a guide for all. Pull-requests are welcome.
2. Deliverables, what are deliverables? Deliverables for now are everything that gets produced in a single design round. This could include things like comps, worksheets that explain the various SDPM entities (TEAMS components) such as logical states, ui states, behavior states, data states, vector drawings, style attributes, graphic and code assets such as SVG, PNG, CSS files, wireframes, mockups and prototypes delivered with front-end dependency package managers such as NPM or Bower.
3. Feedback, what channels? Google Docs Internal, InVision.
4. Testing, who does this? How does this feed back into the next design round?
5. Iteration, how does testing get communicated back to dev?
6. Timeline, milestones, goals.

## SDPM (Style-guide & Development Process Methodology) /a/k/a TEAMS Components

- Placeholder, holds the component entity, represents modular breakpoints with respect to device viewport.
- Container, logical entity in DOM, various technologies, specific set of elements.
  - Behavior, JS, JQuery, etc.
  - Appearance, CSS, etc.
  - Tests, Java
  - Templates, JSP
  - Documentation, Markdown
  - Dependencies, NPM, Gulp, Bower
  - Assets, Glyphs, Typefaces, Icons, Images
- Element, constituent of container, no stand-alone meaning, can be semantically-tied to container for organizational needs
- Entry, data-driven state and behavior
- Entry Item, data elements of an entry
- Modifier, defines appearance and/or behavior, optional. In essence HTML attributes.
- UI State
  - Blank States, First impressions
  - Loading States, Perception of loading
  - Partial States, Walk-thrus, wizards
  - Error States, 404, JS alert boxes
  - Ideal State, Everything is normal

##### A Sample Nesting
- Placeholder (Breakpoints) eg.an array of virtual-viewports that hold containers within the device viewport in an accessible manner.
  - Container (View) eg.design patterns, ie.tab-view, scroll-sort, nav-bar
    - Element (Dashboard) eg.multiple tabs, each containing a dashboard element within a view container
      - Entry (Widget) eg.a specific type or version of an element, ie.charts, reports, actionable items
        - Modifier (JS grid library), allowing for multiple drag-and-drop Entries on same page.
          - UI States
            - Default (blank or default set)
            - Loading (loading animation)
            - Ideal (ready for user input)

# Accessibility Resources

### Resolutions and Responsiveness
- MSDN - [Link](https://blogs.msdn.microsoft.com/b8/2012/03/21/scaling-to-different-screens/)
- Responsiveness & Accessibility - [Link](http://www.ssbbartgroup.com/blog/what-does-responsive-web-design-have-to-do-with-accessibility/)

### Accessibility Goals
- ARIA W3C Spec - [Link](http://www.w3.org/TR/aria-in-html/)
- WCAG Guidelines - [Link](http://www.w3.org/TR/WCAG20/#visual-audio-contrast)
- U.S. Web Design Standards - [Link](https://playbook.cio.gov/designstandards/)
- W3C Accessibility Use of Color [link](http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html)

### Misc Accessibility Resources
- SVG Glyphs - [Link](https://www.paciellogroup.com/blog/2013/12/using-aria-enhance-svg-accessibility/)
- CSS Layout Grid W3C Draft - [Link](http://www.w3.org/TR/css-grid-1/)
- A11Y Color Combos - [Link](http://clrs.cc/a11y/)

### UI Best Practices
- Style Guides for Apps - [Link](https://www.google.com/design/spec/style/)
- Sample UI Practices - [Link](http://developer.android.com/training/best-ui.html)
- Yahoo UI Library - [Link](https://github.com/yui/yui3)
- Responsive UI Breakpoints from Google - [Link](https://www.google.com/design/spec/layout/responsive-ui.html#responsive-ui-breakpoints)

### Color and Palette Tools
- Some primary palettes from Google [link](https://www.google.com/design/spec/style/color.html#)
- SASS Script Functions [link](http://sass-lang.com/documentation/Sass/Script/Functions.html)
- Programmatically generate a color scheme in SASS [link](http://thesassway.com/advanced/how-to-programtically-go-from-one-color-to-another-in-sass)
- SASS & Compass Color Functions [link](http://jackiebalzer.com/color)
- Practical Color Theory [link](http://tallys.github.io/color-theory/)
