# Intel Sustainability Timeline

An interactive timeline of Intel's sustainability milestones, built to work in
both left-to-right and right-to-left languages and tested for accessibility.

**[View the live site →](https://emcuberos1.github.io/intel-sustainability-timeline/)**

## Features

- Nine milestones, scrolling horizontally on desktop and stacking vertically
  on mobile
- Hover details that pull out from beneath each card, so nothing already on
  screen is covered
- CSS scroll snap for the horizontal navigation
- Right-to-left layout applied automatically when the page language changes
- A responsive three-column section, a newsletter signup form, and a
  confirmation modal

## Built with

HTML, CSS and Flexbox for the timeline, with Bootstrap for the grid section,
form and modal. No build step.

## Accessibility

Scores 100 on Lighthouse accessibility, on both desktop and mobile — contrast
ratios, descriptive alt text on every image, and properly labelled form fields.

## A note on the hover interaction

The obvious way to reveal extra detail on hover is to overlay it on the card,
which hides the title and date the user was just reading. These cards instead
expand downward into the space below the hovered card, so the detail appears
without anything disappearing.
