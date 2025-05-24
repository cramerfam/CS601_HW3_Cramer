# CS 601 Week 3 Assignment - CSS Portfolio

Please take a look around. You can open index.html in your browser to view the game or launch it live in your IDE with an extension.

## About My Project

I created a portfolio of produce I have grown in my small backyard garden over the past few years. I made sure to include all the key elements of the project: a header, a footer, main content with projects, and a sidebar. I used flexbox for the nav bar and footer, while the main section is a CSS grid. The page is responsive - you can shrink your browser from large to small to test it out, or open Chrome Dev Tools and select one of the built-in mobile emulators. 

I referenced this [list of pseudoclasses](https://www.w3schools.com/cssref/css_ref_pseudo_classes.php), and included the following:
 * :hover (on the nav links and all my project tiles)
 * :is() (for structuring a combinator with all the warm or cool tiles with the warm or cool overlay)
 * :nth-child (for adding a subtle dotted underline on that section of the sidebar that includes directions)
 * :root (for adding my color constants)

I used ::before as my pseudoelement to add the logo in front of the nav without including it in the html.

I used both descendant combinators (space) and child combinators (>).

My attribute selectors were "body", "a", "p", and "img". 

Note: All images are real images of produce I've grown over the past 3 years. There is also a week 1 assignment easter egg hidden somewhere on the page! :) 