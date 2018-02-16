# Startrly

A team of ambitious and passionate folks have assembled and they're creating a new product called Startrly. Startrly is a new and unique solution for some problem, and it's going to disrupt some industry. They've hired you to make a new front-page for their product's website. They have a good idea for what they want in their front page in terms of layout and content, so they've provided wireframes and the HTML for the front page. However, in terms of literal styles, colors, and visual design choices, they've left that freedom to you.

This is an individual, [stage 2](https://github.com/Ada-Developers-Academy/pedagogy/blob/master/rule-of-three.md) project.

## Learning Goals
- Practice Layout Techniques
- Have DRY, readable CSS code using CSS selectors with classes and ids
- Add Custom Styling

## Baseline
Using CSS, construct the layout of the site according to the following wireframes attached to the project:
- [Wireframe for mobile (smaller devices)](wireframes/mobile.png)
- [Wireframe for desktop (large devices)](wireframes/desktop.png)

These images are wireframes. Wireframes are used to convey a site's layout design. It highlights the layout without focusing on any of the design specifics (like color, typography, copy, etc).

Wireframes are important tools to help designers and developers communicate. Wireframes can be either high-fidelity (which show a goal for what the site should exactly look like with all colors, typography) or low-fidelity (which show a rough estimation of what the site should look like, and are often filled with placeholder boxes, and can often be drawn on paper). Our provided wireframes are closer to low-fidelity.

We've provided wireframes for both desktop view and mobile view.

Your goal is to create styles for Startrly's website so that its layout emulates the given wireframes as closely as possible, and also provide custom styles.

**You can make only make limited changes to the HTML**
- You cannot move any content around in the HTML
- You can add sectioning elements to wrap around content
- You can add IDs and classes to elements, as necessary

## Primary Requirements

- Add normalize.css
  - Normalize is a popular collection of CSS rulesets used to render elements more consistently across browsers.
  - Go to [https://necolas.github.io/normalize.css/](https://necolas.github.io/normalize.css/), click the red download button, copy and paste the code into a new file called 'normalize.css' and link to it as you would with main.css. The link to normalize.css should come before your main.css.
- Use CSS to rearrange the layout to match the drawing as much as possible (it doesn't need to be perfect). You should utilize the following layout techniques at least once:
  - CSS grid
  - Flexbox
- Add custom styling
  - At least one google font
  - At least one pseudo selector (like hover)
  - Background color on one section
- Identify repeated styles and use CSS selectors and class/id names to organize and DRY your code.



### Optional Enhancements

- Make the top nav fixed, so that the nav bar is stationary as the user scrolls through the site
- Add [parallax scrolling](https://www.w3schools.com/howto/howto_css_parallax.asp) to the hero banner
- Animate the h1 element to fade in on page load
- Create a new page for one of the articles
  - Create a wireframe for the layout design
  - Create the content and structure with HTML, in new HTML page
  - Style the new HTML page to match your wireframe
- Replace the copy and images on the site, while keeping the required layout. This is the only exception for being able to make large changes to the provided HTML
