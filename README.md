# Startrly

## At a Glance

- Individual, [stage 2](https://github.com/Ada-Developers-Academy/pedagogy/blob/master/rule-of-three.md#stage-2) project
- Due **before class, Friday September 14**

## Introduction

A team of ambitious and passionate folks have assembled and they're creating a new product called Startrly. Startrly is a new and unique solution for some problem, and it's going to disrupt some industry. They've hired you to make a new front-page for their product's website. They have a good idea for what they want in their front page in terms of layout and content, so they've provided wireframes and the HTML for the front page. However, in terms of literal styles, colors, and visual design choices... they've left that freedom to _you_.

## Learning Goals
- Practice layout techniques
- Have DRY, readable CSS code using CSS selectors with classes and ids
- Add styles

## Baseline
Using CSS, construct the layout of the site according to the following wireframe attached to the project:
- [Wireframe for desktop (large devices)](wireframes/desktop.png)

The above image is a wireframe. Wireframes are used to convey a site's layout design. It highlights the layout without focusing on any of the design specifics (like color, typography, copy, etc).

Wireframes are important tools to help designers and developers communicate. Wireframes can be either high-fidelity (which show a goal for what the site should exactly look like with all colors, typography) or low-fidelity (which show a rough estimation of what the site should look like, and are often filled with placeholder boxes, and can often be drawn on paper). Our provided wireframes are closer to low-fidelity.

We've provided wireframes for desktop view (and the mobile view for the optional enhancements).

Your goal is to create styles for Startrly's website so that its layout emulates the given wireframes as closely as possible, and also provide styles.

**You can make only make limited changes to the HTML**
- You cannot move any content around in the HTML
- You can add sectioning elements to wrap around content
- You can add IDs and classes to elements, as necessary

## Primary Requirements

- Add normalize.css
  - Normalize is a popular collection of CSS rulesets used to render elements more consistently across browsers.
  - Go to [https://necolas.github.io/normalize.css/](https://necolas.github.io/normalize.css/), click the red download button, copy and paste the code into a new file called `normalize.css` and link to it as you would with `styles.css`. The link to `normalize.css` should come before your `styles.css`
- Use CSS to rearrange the layout to match the drawing as much as possible (it doesn't need to be perfect). You should utilize the following layout techniques at least once:
  - CSS Grid
  - flexbox
- Add styling/theming
  - At least one font found from [Google Fonts](https://fonts.google.com/)
  - At least one pseudo selector (like hover)
  - Background color on one section
- Identify repeated styles and use CSS selectors and class/id names to organize and DRY your code.

### About Perfection

You are not expected to match the wireframes to perfection in this project. While this given layout is certainly achievable with pure CSS, it is less important to achieve every style than it is to practice CSS Grid and flexbox and achieving a "close enough" layout.

You will be evaluated on hitting the learning goals of working with CSS layout techniques, and not evaluated on perfectly matching the given wireframe.

## Optional Enhancements

- Make the top nav fixed, so that the nav bar is stationary as the user scrolls through the site
- Create a new page for one of the pages
  - Create a wireframe for the layout design
  - Create the content and structure with HTML, in new HTML page
  - Style the new HTML page to match your wireframe
- Replace the copy and images on the site, while keeping the required layout. This is the only exception for being able to make large changes to the provided HTML
- Make your website responsive! Check your site against this recommended wireframe for mobile/responsive design
  - [Wireframe for mobile (smaller devices)](wireframes/mobile.png)
- Add [parallax scrolling](https://www.w3schools.com/howto/howto_css_parallax.asp) to the hero banner
- Animate the h1 element to fade in on page load

## What Instructors Are Looking For
Check out the [feedback template](feedback.md) which lists the items instructors will be looking for as they evaluate your project.
