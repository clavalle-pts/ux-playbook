# TEAMS Components List

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
  - Recent items is a list of recently used menu items by frequency according to frequency function.
- Jump-Point Quick Search
  - A searchable, filterable list with auto-jump associated with carriage return. The search function of this component should be tightly coupled to the results returned as each letter is entered. The function should search with a predictive nature taking into account the frequency function.
- Profile
  - The user profile section is for user maintaining user-related elements such as passwords. According to the security procedures, the avatar and display name of the user may need to be set in the administration portion of the system without user control.
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
