# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

- Purple 100: hsl(254, 88%, 90%)
- Purple 500: hsl(256, 67%, 59%)

- Yellow 100: hsl(31, 66%, 93%)
- Yellow 500: hsl(39, 100%, 71%)

- White: hsl(0, 0%, 100%)
- Black: hsl(0, 0%, 7%)

## Typography

### Body Copy

- Font size (paragraph): 18px

### Font

- Family: [DM Sans](https://fonts.google.com/specimen/DM+Sans)
- Weights: 400, 500

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma. The design file for this challenge also includes a design system and tablet layout to help you build a more accurate solution faster.



/* 
#child-item2 {
  grid-column: 2 / 4;
  grid-row: 1 / 2.5;
  background-color: var(--color-purple);
}
#child-item3 {
  grid-column: 4 / 5;
  grid-row: 1/4;
}

#child-item4 {
  grid-column: 1 / 2;
  grid-row: 3 / 5;
  height: 100%;
  width: 100%;
  background-color: hsl(39, 100%, 71%);
}

#child-item4 div {
  width: 100%;
  height: 50%;
  border: 1px solid black;
}

#child-item4 img {
  height: 100%;
  width: 100%;
  object-fit: contain;
}

.nested-container {
  display: grid;
  grid-column: 2 / 4;
  grid-row: 2 / 5;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 0.5fr 1.5fr;
  gap: 1em;
  padding: 1rem;
}

#child-item1-of-5 {
  height: 100%;
  width: 100%;
  grid-column: 1 / 2;
}

#child-item1-of-5 .text-container {
  height: 60%;
  width: 100%;
}
#child-item1-of-5 .img-container {
  /* height: 40%; */
  /* width: 100%;
  border: 1px solid black;
  overflow: hidden;
  /* padding: 1rem; */
}
#child-item1-of-5 img {
  height: 100%;
  width: 100%;
  transform: scale(1.25);
  /* transform-origin: left; */
  object-fit: cover;
  object-position: 40px;
}

#child-item2-of-5 {
  height: 100%;
  width: 100%;
  grid-column: 2 / 3;
  background-color: hsl(39, 100%, 71%);
  padding: 1rem;
}

#child-item2-of-5 .text-container {
  height: 60%;
  width: 100%;
  margin-bottom: 1rem;
}
#child-item2-of-5 .img-container {
  height: 40%;
  width: 100%;
  border: 1px solid black;
  overflow: hidden;
}
#child-item2-of-5 img {
  /* padding-top: 5rem; */
  /* height: 130%; */
  width: 100%;
  /* transform: scale(1.1); */
  transform-origin: top;
  object-fit: contain;
  object-position: top;
  /* border: 1px solid black; */
}

#child-item3-of-5 {
  height: 100%;
  width: 100%;
  grid-column: 1 / 2;
}

#child-item3-of-5 .text-container {
  height: 70%;
  width: 100%;
}

#child-item3-of-5 .img-container {
  height: 30%;
}

#child-item3-of-5 img {
  width: 100%;
  object-fit: cover;
}

#child-item4-of-5 {
  grid-column: 2 / 3;
}

#child-item6 {
  grid-column: 3 / 5;
  grid-row: 4 /5;
  background-color: hsl(256, 67%, 59%);
  padding: 1rem;
  align-items: center;
}

#child-item6 .img-container {
  padding: 1rem;
  width: 50%;
}

#child-item6 img {
  width: 100%;
  height: 100%;
  transform: scale(1.2);
  object-fit: contain;
}
#child-item6 .text-container {
  width: 50%;
/* }  */