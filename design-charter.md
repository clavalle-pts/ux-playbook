# TEAMS Design Charter

### Preface
- 1. This is an evolving document, a guide for all involved parties, pull-requests for edits are welcome.
- 2. Deliverables, what are deliverables? Deliverables for now are everything that UX produces in a standard round of design. This includes but is not limited to a teams component worksheet which explains in detail the components and the various UI states, high-fidelity vector drawings, color and typeface attribuites, graphic and code assets such as svg files and css files, respectivly. This may and/or can be changed as developer needs change.
- 3. Feedback, what channels? For now, google docs.
- 4. Testing, who does this? Need management preferences.
- 5. Iteration, how does testing get communicated back to dev? 

## Components

- Placeholder
- Container
- Element
- Entry

##### (Placeholders, Containers, Elements & Entries)
- Placeholder
    - Placeholders represent modular responsive breakpoints with respect to device viewport.

- Container
    - Containers represent a specific element, design pattern or view component. A container is logical and contains a DOM className.

- Element
    - An element could be a component the container. For example, a many-to-one relationship between the element and the container could be menu buttons (elements) in a menu (container).

- Entry
    - The relationship between entry and element is could be described as a type of element. Each element could contain multiple types of entries. For example, a menu could have buttons for navigation and buttons for search. This would represent two types of entries each with differient behavior.

##### A Sample Nesting
- Placeholder (Breakpoints) eg.an array of virtual-viewports that hold containers within the device viewport in an accessible manner.
  - Container (View) eg.design patterns, ie.tab-view, scroll-sort, nav-bar
    - Element (Dashboard) eg.multiple tabs, each containing a dashboard element within a view container
      - Entry (Widget) eg.a specific type or version of an element, ie.charts, reports, actionable items

### Drawer & Menu Containers
- Spine (Vertical)
  - The spines have a higher z in relation to the drawer or other screen and they are fixed position, sized according the the device viewport. They contain the TEAMS pendant button glyph and the other key glyphs that exist along their axis. The vertical spine can be on the left or right side of the screen for accessibility purposes.
- Spine (Horizontal) Header Message
- Pendant
  - Clicking on the pendant button-like behavior for opening and closing the drawer. The pendant remains in a fixed position during drawer operation.
- Glyphs
  - The glyphs are icons associated with each menu item. The order of the glyphs are in-line with the associated menu item icon.
- Drawer
  - The drawer has two ideal UI states. Open and closed. The drawer is in a placeholder along the (-) x-axis in relation to the (0,0) "normal" viewport . When the pendant button is clicked, the (0,0) intersection is moved right along the x-axis, revealing the placeholder within the (-) axis space, thus pushing the content in the placeholder to the right of (0,0) off the screen. The drawers two ideal UI states, open and closed also depend on the size of the viewport. If the viewport is greater than or equal to the sum of the main-viewport and the drawer-viewport, then the ideal UI state is open, else the ideal UI state is closed.

### Menu Elements
- My Favorites
  - My favorites items are jump-points and jump-point headers with nested jump-points sourced from the users customized menu items. Each favorite item can contain a custom icon and can be custom named.
- Recent Items
  - Recent items is a list of recently used menu items by frequency according to frequency funciton.
- Jump-Point Quick Search
  - A searchable, filterable list with auto-jump associated with carriage return. The search function of this component should be tightly coupled to the results returned as each letter is entered. The function should search with a predictive nature taking into account the frequency function.
- Profile
  - The user profile section is for user maintaining user-related elements such as passwords. According to the security procedures, the avitar and display name of the user may need to be set in the administration portion of the system without user control. 
- Notifications
  - The notifications section should show all the current notifications with button options to clear one or all notifications. The user can click on the notification a a link which acts as jump point, navigating the user to that particular record. 
- Messages
  - Messages are system messages for user notification 

### Dashboard Container
Dashboards are default landing pages determined by specific user personas that are linked to each account. For example, teachers might see dashboard A and principals might see dashboard B. In part, for data security and in another part for design, 
- Charts
- Reports
- Actionable Items (eg. workflow, todos, tasks based on business logic)

### Button Components
Buttons have style variances with size and color. Generally speaking the color red would be reserved for a cancel or delete action and the color green would be reserved for saving. Blue buttons are reserved for actions and yellow buttons are reserved for alerts.

## UI States

- Blank States, First impressions
- Loading States, Perception of loading
- Partial States, Walk-thrus, wizards
- Error States, 404, JS alert boxes
- Ideal State, Everything is normal

# Accessibility & Device Compliance

### Resolutions and Responsivness
- MSDN - [Link](https://blogs.msdn.microsoft.com/b8/2012/03/21/scaling-to-different-screens/)
- Responsive UI Breakpoints - [Link](https://www.google.com/design/spec/layout/responsive-ui.html#responsive-ui-breakpoints)
- 7 Deadly Mobile Myths - [Link](http://globalmoxie.com/jhc/prez/mobile-myths.pdf)

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




