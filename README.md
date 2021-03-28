# Design For Developers

This repo hosts code/notes taken from the course https://frontendmasters.com/courses/design-for-developers/

## Introduction

- Myth right vs left brain : https://www.health.harvard.edu/blog/right-brainleft-brain-right-2017082512222
- Right brain left brain article: https://www.britannica.com/story/are-there-really-right-brained-and-left-brained-people
- The more you use your brain in different types of ways. The stronger it becomes. Learning other uncomfortable things can make you a better developer.
- This course is not a replacement for design school. There will be lots of ressources to work from.
- This course is a place to understand some basic concepts. Tips on communicating with designers.
- We improve through repetition and reiteration along the way. Not theorizing about perfection.
- In the stage of learning and understanding : Quantity > Quality.
- A good way to have people interested in your code is through good design.

<details>
  <summary>Layout</summary>

- Grid systems are an old concept. They bring order to chaos and help to focus on navigating its space.
- We as humans thought of organizing things in systems of grids so we can find them easier.
- We can play with the base concept of the entire layout with just a few blocks rather than figuring out everything at once.

- Balance and symmetry: if you want to convey attention to a certain area, you can somehow break the rythme and keep the eye moving around.
- People do tend to gravitate more towards an assymetrical canvas.
- Example of assymetrical work : https://dribbble.com/Orizon
- Rule of thirds: Break your piece into thirds and add your key element into one of the third. : https://en.wikipedia.org/wiki/Rule_of_thirds
- Swiss deisgn is using and making and breaking grids.
- Saccade: a rapid movement of the eye between fixation points. Even if you are staring at an image, your eye is still scanning around for moving parts.
- Circles draw your eye more than other shapes.
- Scaling and cropping techniques can make your piece dynamic or a part of your layout.
- Book on grid and composition: https://www.amazon.com/Making-Breaking-Second-Updated-Expanded/dp/163159284X
- Anchoring things to one another to make things cohesive.
- If you are looking to move some elements of a design to another area, designers might ask questions to preserve anchoring or find another solutions with other anchoring techniques. They still need to follow some design rules while solving problems.
</details>

<details>
  <summary>CSS Layout</summary>

- CSS Grid ressource:

  1. https://gridbyexample.com/
  2. https://labs.jensimmons.com/
  3. http://cssgridgarden.com/
  4. https://cssgrid-generator.netlify.app/

- CSS Clip path tool: https://bennettfeely.com/clippy/
- CSS and SVG masks examples: https://codepen.io/yoksel/pen/fsdbu
- CSS writing mode article: https://24ways.org/2016/css-writing-modes/

</details>

<details>
  <summary>Color Modes</summary>

- Subtractive color mixing: Cyan, Magenta, Yellow and Black.
- Additive color mixing: Red, Green, Blue.
- All colors blended together lead to white.
- Color constrast tool to test a11y: https://colorable.jxnblk.com/
- Types of color combinations:

  1. MonoChromatic (1 color): 1 family of same color.
  2. Analogous: 1 color and it's neighbors colors.
  3. and many more.. https://learn.g2.com/color-schemes
  4. color wheel: https://color.adobe.com/create/color-wheel

- Color Theory reading: https://www.smashingmagazine.com/2010/02/color-theory-for-designer-part-3-creating-your-own-color-palettes/
- Color in code

  1. x is a num from 0-255
  2. y is a num from 0.0 to 1.0
  3. `rgb(x, x, x);` or `rgba(x, x, x, y);` a as in alpha or opacity.

  ***

  4. Hex: values use ranges from 0-9 and A-F.
  5. 0 being lowest. F being highest. `#00000` being black and `#FFFFFF` being white.
  6. ## #[red][green][blue] each bracket has 2 digits.
  7. HSL(A)
  8. x is a num from 0-360
  9. y is a percentage from 0% to 100%
  10. z is a number from 0.0 to 1.0
  11. `hsl(x, y, y);` or `hsla(x, y, y, z);`

- Color name game: http://codepo8.github.io/css-colour-names/
- Native css variable vs scss variables: js can read native css variable.
- You can steal color palettes on dribbble.
- Color tool: https://coolors.co/, https://paletton.com, https://palettab.com/, https://www.adobe.com/products/capture.html
- Gradient generator: https://www.colorzilla.com/gradient-editor/, https://uigradients.com
- Animating gradient is an expensive operation.
- Data viz with HSL colors: https://ich.unesco.org/dive/biome/?language=en
  </details>

<details>
  <summary>Typography</summary>

- Where to get fonts: google font, font squirrel, fonts.com, https://www.typography.com/
- Tool to identify font: https://www.myfonts.com/WhatTheFont/
- Protip: not more than 3 fonts per site. (it can be very expensive)
- Protip: Don't pair with similar fonts
- Font pairing tool: https://fontjoy.com/
- Responsive typography examples: https://codepen.io/MadeByMike/
- Term: Monospaced means every single characters takes same amount of space.
- Term: No Kerning means space between letters.
- Term: Leading means space between baselines.
- Term: Widows and orphans means one - two words at end or begin of paragraph.
- Tech blog: https://www.zachleat.com/web/
- Tool to analyse your page for fonts: https://github.com/Munter/subfont
- BLog: https://www.robinrendle.com/
</details>

<details>
  <summary>Inspiration</summary>

- https://danmall.me/
- https://give-n-go.co/
- https://codepen.io/topics/ui-pattern
- https://thenounproject.com/
</details>

<details>
  <summary>Images and Performance</summary>

- Free images: unplash, google image search license, freepik, pexels
- Paid images: shutterstock, iStockPhoto, Creative Market, Adobe Stock
- Image types article: https://99designs.ca/blog/tips/image-file-types/
- You need to be an image expert before claiming to be a web performance expert.
- PNG has ability for transparency.
- image compression tool: https://tinyjpg.com/
- SVG has a navigable DOM.
- SVG performance article: https://css-tricks.com/high-performance-svgs/
</details>

<details>
  <summary>Prototyping</summary>

- Why you need motion: Humans over-estimate passive waits by 36% - Eli Fitch and Richard Larson, MIT
- People are willing to wait twice as long for a custom experience (example: loaders.) - Viget
- https://css-tricks.com/writing-feature-requirements/
- https://medium.com/design-story/story-map-3cc64033128e
- Motion design language example: https://codepen.io/sdras/pen/JbaGwg
- Low-fi prototype example: https://codepen.io/yusufbkr/pen/ORBArk
- Flipping techniques: https://github.com/davidkpiano/
- https://tympanus.net/Development/PageFlipLayout/
</details>
