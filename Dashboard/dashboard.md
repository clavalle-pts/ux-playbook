# Dashboard

### Jasper Charts Prototype

git@bitbucket.org:uxteams/dashboard_widgets.git

http://ux-dev.ptsteams.local/

### Dashboard Prototype

https://invis.io/5G72R3LKY

Dashboard Prototype Instructions

1. Click the Student Performance button, the student performance report is shown in placeholder
2. Click the Absence button, the absences report is shown in placeholder
3. Click the clear button, the containers are cleared. In this example the placeholders are revealed for illustration purposes.
4. Click the New tab, a new container view is added.

Styleguide: https://zpl.io/Z21f74f

Note: Styleguide, color-pallete and typeface not final.

##### Items in Production

- Button Elements
- Styleguide

### Tab Functions
The new tab functions as a button. Upon clicking the tab, a new tab will appear to the right that also says New. Upon clicking the first tab, the cursor will now blink and the user can rename the tab. The user can create a certain number of tabs. Each tab represents a custom dashboard view. Any pre-loaded views, such as a default landing page, would be configured and linked to tab links in front of the new tab.

### Elements

- Chart Buttons - The list of buttons of reports and charts available to the user are determined by the administration panel and defaults set to the particular persona.

- Make default - This button selects the active view within the container as the default view to load upon login.

- Save - this button saves the view, including the settings of elements and entries for controls, etc.

- Clear - This button clears the canvas. A dialog should appear to confirm.

### Components

- Placeholder, see prototype link
- Container, tab-based pattern
- Element, horizontal Jasper chart
- Entry, controls, button elements, etc.

These are cascading controls. The controls are cascading from left to right and are just plain data controls. These values are pulled from the logged in user-attributes, following existing Jasper and TEAMS security.

##### Student Performance (First Chart)
Location, this is principal view, access to multiple campus views
Course, select course first, then section
Section, section of course
Submit Button, the go button
Export Button, select type, then click export
Type Selector

##### Absences Report (Second Chart)
Location, principal view, campus
Type, absence or tardy


### UI States

- Blank, add elements (widgets)
- Loading, the elements will load while a loading screen is displayed
- Partial, certain media queries
- Error, error messages, browser compatibilities
- Ideal, everything is fine

### Some general questions for the user
- What is available to the user, 2 are in the view and another 2 are in development. these live on the ux-dev Jasper server.
- How do widgets get displayed, the user clicks the chart button and embedded-report.js uses visualize.js to call the Japser server and get a response. Reports are design in studio.
- Drag and drop, user can drag and drop elements in the container thanks to gridster.js
- Size, size of the report is set in studio, otherwise refer to responsive planning worksheet
- Saving, user clicks save button and ui state is saved.
- Default screen, blank.
- Chart examples at different placeholders, prototype is showing Student Performance followed by Absences Report
