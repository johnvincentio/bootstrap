#Bootstrap Workshop

```
Milestone 1: Add on Bootstrap

Bootstrap comes with its own flavor of a reset/normalize CSS, so you will need to remove the existing normalize reference. Bootstrap also requires JQuery, so you will need to add that, as well as a reference to the Bootstrap CSS and the Bootstrap JavaScript files.

A copy of Bootstrap, and JQuery have been included in the bower_components folder. You will use the files inside the dist folder.
```

```
Milestone 2: Start at the top.

The first thing the client will see is the navigation. Head over to the bootstrap navbar section, and convert the current nav into a fixed Bootstrap navbar. The documentation shows a full example at the top of the section on navbars, and then elaborates below on how to make it fixed.

You will need pieces of code from both of those sections. Don't forget to remove or update the stylesheet to get rid of code for the old nav.
```

```
Milestone 3: Grid structure

Bootstrap has a solid grid structure that is based on a 12-column grid. Each column has the same value, and a small gutter, so content doesn't touch when it shouldn't. You are able to define how many columns your content should span, and for what screen size. For example, col-xs-3 would span 3 columns for all screen sizes.

Bootstrap is designed mobile first, so anything that is defined as xs will affect all screen sizes you don't specifically designate. col-md-4 would override the xs rule on medium screens and up, but small screens would still be 3 columns. For Bootstrap to know about the columns, they need to be inside a .container or .container-fluid element. The container can be anything, and can be nested, to create more dynamic layouts.

Head over to Bootstrap's documentation on their grid, then make the three columns of text each be full width for xs and sm screens, and 1/3 of the screen for medium. For large, they should be 1/4 of the screen width, with a small offset to space them out a little more. Again, remember to remove the old styles.
```

```
Milestone 4: Form

Bootstrap has some built in components, and forms are really powerful with bootstrap. Check out the documentation.

You are going to build an inline form. For this section, you can leave the existing styles. Notice that the example from Bootstrap has a class on the button? Check out the documentation on buttons.

There is a way to change the color theme - but for now, make the button the default, and you can remove the CSS for that as well!
```

```
Milestone 5: Footer

All that's left for structure is the footer. Take what you've learned, and make the footer .container-fluid, so it will touch the edges, and make the nav take up 50% of the screen on md screens and up and 100% on xs and sm. Then make the nav items evenly spaced for small and larger; on xs screens, the items should be full width.

You may notice that the copyright text creeps up on larger screens. Define that to be col-xs-12 to make it full width, and avoid the creep.
```

```
Milestone 6: Utility class

Bootstrap also has some useful utility classes for altering text, and creating other components.

For this example, you are going to make the page title uppercase, center the heading in the three articles, justify the paragraph text, and center the footer elements as well as the form elements, all using these utility classes, then remove the CSS from the original style.css file.
```

```
Milestone 7: Jumbotron

Bootstrap has many built-in components to give you the ability to customize a page layout, without having to write much CSS, including: glyphicons (an icon library), buttons, navbars, various types of page navigation elements, dropdowns, and much more here.

For the masthead image, you're going to use the jumbotron. For this to work, the header will need to have a container or container-fluid class, and the image should be changed into a background-image on the jumbotron.
```

