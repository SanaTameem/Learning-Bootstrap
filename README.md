Bootstrap is a free and open source front-end framework.
It is highly customizable , mobile first and semantic.
Bootstrap 5 alpha and beta were released in 2020.
There are 59 UI components exixisting in Bootstrap which is created with SASS.

1 :

- Layout : styles for creating responsive grid systems:
- 4 components : Containers , Grid , Columns and Gutters

<div class="container">
  <div classe="row">
    <div class="col"></div>
  </div>
  <div classe="row">
    <div class="col"></div>
    <div class="col"></div>
  </div>
  <div classe="row">
    <div class="col"></div>
    <div class="col"></div>
    <div class="col"></div>
  </div>
</div>

2 :

- Content : Styles for various texts and images
- It has 4 components: Typography, Images, Tables, Figures

Typography:

<p class="lead">Lorem ipsum dolor sit amet consectetur</p>   // making the text larger

<p class="text-decoration-underline">Lorem ipsum dolor sit amet consectetur</p>

Image :
<img src = "something.jpg" class="img-thumbnail"> // adding a white border to the image

3 :

- Forms : Styles for various forms elements as well as layout and validations.
- It has 8 components : Form control, Select, Checks and Radios, Range , Input Groups, Floating Labels, Layout , Validation.

<label class="form-label">Name:</label>
<input type="text" class="form-control" />

4:

- Components: The biggest category , Styles for common user interface components.
- 22 components :
  - Accordion (The Bootstrap accordion is a component that organizes content within collapsable items.),
  - Alerts,
  - Badge(Badges are used to add additional information to any content.),
  - Breadcrumbs(Indicate the current page’s location within a navigational hierarchy that automatically adds separators via CSS.),
  - Buttons,
  - Button group(Group a series of buttons together on a single line or stack them in a vertical column.)
  - Card (A card is a flexible and extensible content container.),
  - Crousel (The carousel is a slideshow for cycling through a series of content, built with CSS 3D transforms and a bit of JavaScript.),
  - Close Buttons (A generic close button for dismissing content like modals and alerts.),
  - Collapse (The collapse JavaScript plugin is used to show and hide content.),
  - Dropdowns,
  - List Groups
  - Modal (Use Bootstrap's JavaScript modal plugin to add dialogs to your site for lightboxes, user notifications, or completely custom content),
  - Navs,
  - Navbars,
  - Pagination (Documentation and examples for showing pagination to indicate a series of related content exists across multiple pages.),
  - popovers (t is a pop-up box that appears when the user clicks on an element.),
  - Progress (A progress bar can be used to show a user how far along he/she is in a process.),
  - Scrollspy(Automatically update Bootstrap navigation or list group components based on scroll position to indicate which link is currently active in the viewport.),
  - Spinners(Indicate the loading state of a component or page with Bootstrap spinners),
  - Toasts(Push notifications to your visitors with a toast, a lightweight and easily customizable alert message.),
  - Tooltips(The Tooltip plugin is small pop-up box that appears when the user moves the mouse pointer over an element)

5:
Helpers : 7 components :

- Helper class to make minor formatting changes
- Clearfix , Colored Links, Ratio, Position, Visually hidden, stretched link, and text truncation.

6:
Utilities: 14 components

- Class for making minor formatting changes.
- Borders, Colors, Display, Flex, Float, Interactions, Overflow, Position, Shadows, Sizing, Spacing, Text, Vertical Align ,and visibility.

- To use bootstrap we have to download the compiled CSS and JS from getbootstrap.com website and import the bootstrap.css or bootstrap.min.css and bootstrap.bundle.js or bootstrap.bundle.min.js to our project directory.
Then for linking the css in the head of our html file we should write :
<link rel="stylesheet" href="css/bootstrap.min.css"> 
For linking the JS before the closing body tag we should write : 
<script src="js/bootstrap.bundle.min.js"></script>
