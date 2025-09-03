# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge
The goal of this challenge was to build a clean and responsive results summary component that closely matches the provided design.

In this solution, I applied:

Semantic HTML structure to improve accessibility and readability.

Container and sub-container classes to organize the layout and separate content clearly.

CSS styling for typography, colors, and spacing to replicate the design mockup accurately.

Responsive design using media queries to ensure the component displays well on smaller screens (down to 320px).

Consistent CSS organization for maintainability and easier updates.

This challenge was a valuable opportunity to practice structuring layouts with containers, implementing responsive styling, and refining attention to detail when converting a visual design into code.

### Screenshot

![screenshot for desktop](./Screenshot%202025-09-03%20at%2006-13-11%20Frontend%20Mentor%20Results%20summary%20component.png)
![screenshot for mobile](./Screenshot%202025-09-03%20at%2006-14-05%20Frontend%20Mentor%20Results%20summary%20component.png)
![screenshot for active state](./Screenshot%202025-09-03%20at%2006-14-45%20Frontend%20Mentor%20Results%20summary%20component.png)

### Links
- Live Site URL: [View live site here](https://JhayCodesDev.github.io/Result-Summary-Component-Main/)

## My process
1. Setup

Downloaded the starter files and extracted them into a new project folder named results-summary-component-main.
Reviewed the provided design mockups and instructions to understand the project requirements and layout.

2. Structure

Built the HTML structure using semantic tags and organized containers for clear content separation:

A #container as the main wrapper for the component.

A .sub-container inside the container to hold content sections:

.con-one – used for the primary summary or heading section.

.con-two – contains detailed summary items:

A #sub div with an h3 tag for the section heading.

Four divs (#sum-one to #sum-four) each with display: flex; justify-content: space-between; applied inline to align content side by side.

An #attribution div placed outside #sub but still inside #container for credits and links.

This structure allowed for a clear hierarchy, making it easy to style and maintain.

3. Styling

Added base styles for typography, colors, and spacing.

Styled the container, sub-container, and content sections to replicate the design mockup accurately.

Applied flexbox styling for the summary items to ensure proper alignment and spacing.

Styled the attribution section to match the overall component design.

4. Responsiveness

Used a desktop-first approach, designing for larger screens first.

Applied media queries to adjust font sizes, spacing, and alignment for smaller screens (320px–767px).

Ensured that the flex layout and summary items remained readable and visually balanced on all screen sizes.

5. Finishing Up

Cleaned up the CSS by grouping selectors logically.

Tested the component across different screen sizes to ensure responsiveness and alignment.

Wrote the README and prepared the project for deployment.

### Built with

- Semantic HTML5 markup (div, h3, container/sub-container structure)

- CSS Flexbox for layout and alignment of summary items (#sum-one to #sum-four)

- Container-based layout for clear content hierarchy (#container, .sub-container, .con-one, .con-two)

- Responsive design using media queries to ensure the component works well on smaller screens (320px–767px)

- CSS styling for typography, colors, spacing, and hover states

- Inline CSS for quick flex alignment (used on summary items for side-by-side spacing)

## Author
- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.
