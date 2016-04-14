# TEAMS Design Charter



## Design Components
##### (Placeholders, Containers, Objects & Entries)
- Object Placeholder
  - Placeholder Container
    - Container Object
      - Object Entry

##### A Sample Nesting
- Placeholder (eg.Segmented View within responsive breakpoints)
  - View Container (eg.Design Pattern ie.Tabs)
    - Dashboard View (eg.Multiple Dashboard Entires)
      - Dashboard Entry (eg.Dashboard Widget)

### Key Components
- Pendant
  - Clicking on this pendant causes it behavior to function like a button which toggles the drawer. The pendant does not move during drawer behavior.
- Drawer
  - The drawer is a panel section that sits off to the left of the main-canvas. When the TEAMS pendant button is clicked the main-container moves the main canvas to the right along the x-axis, thus bringing the panel into view and having a toggle-effect.
- Butt
  - The butt has a higher z in relation to the drawer. It contains the TEAMS pendant button glyph and the other key glyphs that exist along its y-axis. The butt can be on the left or right side of the screen.
- My Favorites
  - By default the user would see any default favorite items assigned. Upon initial login, a wizard would be available to walk the user through customizing their favorites.
- Recent Items
  - Recent items is a list of recently used menu items by frequency according to numerical weighting.
- Jump-Point Search
  - A searchable, filterable list with auto-jump upon pressing enter. The search function of this component should be tightly coupled to the results returned as each key is pressed. The function should function with a predictive nature.

### A list of components with its sub-components
###### Nav-Bar
- Header Placeholder

###### Drawer
- Predictive Navigation Search
- My Favorites
- Recent Items

###### Butt
- Pendant Button
- Menu Item Glyphs

###### Dashboards Entries
- Charts
- Reports
- Actionable Items (eg. workflow, todos, tasks based on business logic)

### Pending Documentation
- Nav Bar
- Jump Point Quick Search
- View Panel
- View Header (Message Center)
- User Profile
- User Notifications
- System Notifications
- View Container
- Dashboard
- Dashboard Entry

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
- Visually indicate each component, any sub-components with accompanying description
- Components are the pieces of the application that have some function
- Behaviors could include visual behavior or logical behavior and is based on a state
- Quality research helps us filter bias and make it better





