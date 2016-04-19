# TEAMS Design Charter
## Design Components

- Placeholder
- Container
- Element
- Entry

##### (Placeholders, Containers, Elements & Entries)
- Placeholder
    - Placeholders represent the 
modular responsive breakpoints
with respect to current and future
target devices

- Container
    - Containers represent the use of
a specific element, design pattern or view component. A container is a logical level and contains DOM className.

- Element
    - An element is the behavior of the container. For example, in a many-to-one relationship the element would be the multi-instanciable capable extension of the container.

- Entry
    - The relationship between entry and element is could be described as by using a type example. The element could contain multiple types of entries.

##### A Sample Nesting
- Placeholder (Viewports) eg.an array of placeholders for containers within the viewport as possible locations for views
  - Container (View) eg.design patterns, ie.tab view component
    - Element (Dashboard) eg.multiple tabs of a dashboard element within view component
      - Entry (Widget) eg.a specific type or version of an element, ie.charts

### Component
- Spine (Vertical & Horizontal)
  - The spine has a higher z in relation to the drawer. It contains the TEAMS pendant button glyph and the other key glyphs that exist along its y-axis. The spine can be on the left or right side of the screen for accessibility purposes.
- Pendant
  - Clicking on this pendant causes it behavior to function like a button which toggles the drawer. The pendant does not move during drawer behavior.
- Glyphs
  - The glyphs are icons associated with each menu item.

- Drawer
  - The drawer is a panel section that sits off to the left of the main-canvas. When the TEAMS pendant button is clicked the main-container moves the main canvas to the right along the x-axis, thus bringing the panel into view and having a toggle-effect.
- My Favorites (Menu Item)
  - By default the user would see any default favorite items assigned. Upon initial login, a wizard would be available to walk the user through customizing their favorites.
- Recent Items
  - Recent items is a list of recently used menu items by frequency according to numerical weighting.
- Jump-Point Quick Search
  - A searchable, filterable list with auto-jump upon pressing enter. The search function of this component should be tightly coupled to the results returned as each key is pressed. The function should function with a predictive nature.



- Viewport
- Spine (Horizontal) Header Message
- Profile
- Notifications
- Messages

### Dashboards
Dashboards are default landing pages determined by specific user personas that are linked to each account. For example, teachers might see dashboard A and principals might see dashboard B. In part, for data security and in another part for design, 
- Charts
- Reports
- Actionable Items (eg. workflow, todos, tasks based on business logic)

## UI States

- Blank States, First impressions
- Loading States, Perception of loading
- Partial States, Walk-thrus, wizards
- Error States, 404, JS alert boxes
- Ideal State, Everything is normal

### Resolutions and Responsivness
- Breakpoints
  - Tablet (eg. tablet 2-column )
  - Mobile (eg. mobile 1-column )
- Target Devices
  - Current product - 1024px
  - Additional pixels - 52px (proposed)
- MSDN - [Link](https://blogs.msdn.microsoft.com/b8/2012/03/21/scaling-to-different-screens/)
- Responsive UI Breakpoints - [Link](https://www.google.com/design/spec/layout/responsive-ui.html#responsive-ui-breakpoints)

# Accessibility & Device Compliance

### Accessibility Goals
- ARIA W3C Spec - [Link](http://www.w3.org/TR/aria-in-html/)
- WCAG Guidelines - [Link](http://www.w3.org/TR/WCAG20/#visual-audio-contrast)
- U.S. Web Design Standards - [Link](https://playbook.cio.gov/designstandards/)

### UI Best Practices
- Style Guides for Apps - [Link](https://www.google.com/design/spec/style/)
- Sample UI Practices - [Link](http://developer.android.com/training/best-ui.html)
- Yahoo UI Library - [Link](https://github.com/yui/yui3)

### Accessible-Friendly Frameworks
- SVG Glyphs - [Link](https://www.paciellogroup.com/blog/2013/12/using-aria-enhance-svg-accessibility/)
- Low-level CSS Framework - [Link](http://www.basscss.com)
- A11Y Color Combos - [Link](http://clrs.cc/a11y/)

### Deliverables

### Buttons
Green means then and red means this and here are the colors and the sizes.



