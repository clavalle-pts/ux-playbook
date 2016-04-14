# TEAMS Design Charter

### Deliverables
- Visually indicate each component, any sub-components with accompanying description
- Components are the pieces of the application that have some function
- Behaviors could include visual behavior or logical behavior and is based on a state
- Quality research helps us filter bias and make it better

### A list of components with its sub-components
###### Nav-Bar
- Notifications
- Messages
- User Profile

###### Drawer
- Predictive Navigation Search
- My Favorites
- Recent Items

###### Butt
- Menu Item Glyphs
- Drawer Toggle
- Brand Emblem

###### Dashboards
- Charts
- Reports
- Actionable Items (eg. workflow, todos, tasks based on business logic)

### Components
- Drawer
  - The drawer is a panel section that sits off to the left of the main-canvas. When the TEAMS icon is clicked the main-container moves the main canvas to the right along the x-axis, thus bringing the panel into view and having a toggle-effect.
- Butt
  - The butt has a higher z in relation to the drawer. It contains the TEAMS button glyph and the other key glyphs that exist along its y-axis.
- My Favorites
  - By default the user would see any default favorite items assigned. Upon initial login, a wizard would be available to walk the user through customizing their favorites.
- Recent Items
  - Recent items is a list of recently used menu items by frequency according to numerical weighting.
- Jump-Point Search
  - A searchable, filterable list with auto-jump upon pressing enter. The search function of this component should be tightly coupled to the results returned as each key is pressed. The function should function with a predictive nature.
- TEAMS Button (Menu Toggle)
  - This button opens and closes the drawer. The drawer can be positioned on the left or the right side of the screen. The button does not move after being pressed, it stays in the same location on the screen. This allows the user to easily toggle and access their favorite and recent items.
  - Note: The image of the button will be provided as a png for design purposes and should be replaced with an accessable compliant svg with proper documentation.

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
- Responsive Breakpoints - [Link](https://www.google.com/design/spec/layout/responsive-ui.html#responsive-ui-breakpoints)

# Accessibility Compliance

### Accessibility Goals
- ARIA W3C Spec - http://www.w3.org/TR/aria-in-html/
- WCAG Guidelines - http://www.w3.org/TR/WCAG20/#visual-audio-contrast
- Style Guides for Apps - https://www.google.com/design/spec/style/
- Sample UI Practices - http://developer.android.com/training/best-ui.html
- Yahoo UI Library - https://github.com/yui/yui3
- U.S. Web Design Standards - https://playbook.cio.gov/designstandards/

### Accessible-Friendly Frameworks
- SVG Glyphs - https://www.paciellogroup.com/blog/2013/12/using-aria-enhance-svg-accessibility/
- Low-level CSS Framework - http://www.basscss.com
- A11Y Color Combos - http://clrs.cc/a11y/





