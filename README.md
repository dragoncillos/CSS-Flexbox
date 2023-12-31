# CSS Flexbox simplified

- [CSS Flexbox simplified course by Shruti Balasa](https://laracasts.com/series/css-flexbox-simplified/)
- [Based of the original source code](https://github.com/laracasts/css-flexbox-simplified)

## Table of Contents

- [01 First look at CSS Flexbox](https://dragoncillos.github.io/CSS-Flexbox/01-first-look.html)
  - Navigation bar: basic. *display: display:flex, gap*
  - Testimonial section in a single row: all blocks are of the **same height** but **different widths** based on the length of text within
- [02 Spacing and alignment](https://dragoncillos.github.io/CSS-Flexbox/02-spacing-and-alignment.html)
  - Navigation bar with logo: display: *flex, gap, justify-content: center, align-items: center*
  - Testimonial section in a single row: all blocks are of the **same height** and **same widths**
  - [02b Center div on page](https://dragoncillos.github.io/CSS-Flexbox/02b-center-div.html): Fisrt method center div with *justify-content: center, align-items: center*
- [03 Wrap items into multiple rows](https://dragoncillos.github.io/CSS-Flexbox/03-wrap-items-multiple-rows.html): *flex-wrap: wrap, align-content*
- [04 Cross-axis alignment and flow direction](https://dragoncillos.github.io/CSS-Flexbox/04-cross-axis-alignment-and-flow-direction.html): Prices: *main axis, cross axis*
  - [04b Login screen](https://dragoncillos.github.io/CSS-Flexbox/04b-login-screen.html): flex-direction-column
  - [04c Testimonial](https://dragoncillos.github.io/CSS-Flexbox/04c-testimonial.html)
- [05 Grow and shrink flex items](https://dragoncillos.github.io/CSS-Flexbox/05-grow-and-shrink.html): common layout, sidebar and main content, *flex-grow: 1*
  - [05b Post vertical](https://dragoncillos.github.io/CSS-Flexbox/05b-post-vertical.html): *flex-grow: 1*
  - [05c Post horizontal](https://dragoncillos.github.io/CSS-Flexbox/05c-post-horizontal.html): *flex-grow: 1 and flex-shrink: 0*
- [06 Flex basis vs width](https://dragoncillos.github.io/CSS-Flexbox/06-flex-shorthand.html): *width: 33.33% vs flex-basis: 33.33% vs flex-basis: 0% and flex-grow: 1*. Flex shorthand: *flex: &lt;flex-grow&gt; &lt;flex-shrink&gt; &lt;flex basis&gt;*
- [07 The order property](https://dragoncillos.github.io/CSS-Flexbox/07-order.html): Switch mobile to desktop to see it
- [08 Aligning individual items](https://dragoncillos.github.io/CSS-Flexbox/08-align-individual-items.html): Post horizontal variant: *align self*
  - [08b Login screen](https://dragoncillos.github.io/CSS-Flexbox/08b-login-screen.html): flex-direction-column, *align self*
- [09 Flexbox and auto margins](https://dragoncillos.github.io/CSS-Flexbox/09-auto-margins.html): *margin-inline-start: auto;*, margin-inline-end: auto;
  - [09b Footer problem](https://dragoncillos.github.io/CSS-Flexbox/09b-footer.html): flex-direction: column, *margin-block-start: auto*
  - [09c Center div](https://dragoncillos.github.io/CSS-Flexbox/09c-center-div.html): Second method center div with *margin: auto*
- [10 Make a flex fontainer Inline](https://dragoncillos.github.io/CSS-Flexbox/10-flex-inline.html): *display: inline-flex*
- [11 Test everything you've learned about Flexbox](https://dragoncillos.github.io/CSS-Flexbox/11-everything.html)
- [12 Flexbox vs Grid](https://dragoncillos.github.io/CSS-Flexbox/06b-grid.html): Prices. View 06 flex basis and compare
  1. Flexbox is for one dimension layouts / Grid is for two dimension layouts
  2. Flexbox is for components / Grid is for layouts (or complex components)
  3. Flexbox for the content-first / Grid for the layout-first
