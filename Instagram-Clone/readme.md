# Fixed Navbar and Responsive Layout Project

This project involves creating a layout with a fixed navbar, responsive content areas, and several custom UI elements. Below is a detailed breakdown of the tasks and how they were implemented.

## Features and Tasks

### 1. **Fixed Navbar**
   - The navbar should stay fixed at the top of the page even when the user scrolls.
   - Add padding to the body to prevent the navbar from overlapping with the content.

### 2. **Navbar Styling**
   - The navbar’s height should be 54px.
   - The navbar's background color should be white.

### 3. **Navbar Logo Positioning**
   - Add a left margin of 192px to the `logo` class inside the navbar to position it correctly.

### 4. **Search Bar**
   - Center the search bar within the navbar using `d-flex` class.
   - Add a left margin of 5 units to the search bar.
   - The placeholder text in the search bar should have a background image from the assets folder, and the image should not repeat.

### 5. **FontAwesome Icons**
   - The icons used in the clone project were taken from FontAwesome.
   - Refer to the FontAwesome website for detailed information on how to integrate and use them.

### 6. **Menu Positioning**
   - The menu at the top-right of the navbar should have a left margin of 5 units and a top margin of 2 units.
   - Ensure that the menu disappears on smaller screen sizes using Bootstrap's display property.

### 7. **Content Area Styling**
   - The content area (middle posts section) should have an offset of 4 units and a top margin of 2 units.
   - Set a maximum height of 200px for the `.middlearea` class and use `!important` to enforce it.
   - Adjust the default column value to 12 for larger screens, and to 6 for smaller screen sizes (responsive design).

### 8. **Stories Section**
   - Display user names under the images in the Stories section.
   - Use the same styling approach applied to the search section for consistency.

### 9. **Post Options**
   - Ensure the ellipsis (three dots) in the content section is aligned to the right.
   - The like, comment, and share buttons should have no borders.
   - Set the bookmark icon’s left margin to 7 units.
   - Ensure the card headers and footers have a white background.

## Tasks Not Completed

### 1. **Footer Text Alignment**
   - Align the "See All" and "Follow" texts to the right side.

### 2. **Right Panel Sticky Sidebar**
   - The `stickysidebar` class should make the right panel follow the page scroll. This can be achieved by using the `position` property in CSS.
   - The `rightpanel` class should have a white background and no border.