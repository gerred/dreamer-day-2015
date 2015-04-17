# Making it Pretty with CSS

Cascading Style Sheets (CSS) is a language for changing the visual appearance of our page. We can use CSS to change our layout, fonts, colors, background, and even do things like add animations and shadows to our site. Let's make our article really stand out.

We can style by elements, but there may be a time when we don't want all of our paragraph tags to look the same. To do this, we can add information to our tags called classes and ids.

CSS is organized into blocks called rules. Each rule has a list of styling information called directives. These rules and directives change the visual appearance of your site.

It's important to know that you can only use a single id once. Use classes to get around this.

## Exercises

1. Change the font of your main title to "Helvetica Neue". Use the `font-family` directive shown in the page to do this.
2. Add a CSS rule for the "body" element. Inside of this rule, add the `background-color` directive. Try: `background-color: black;`. What happens? Try some other common colors, and then try: `#FFFF00`. What does this look like? Play with some other colors.
3. Change the "strong" tag to not be bold with the font-weight directive. Hint: try `font-weight: normal;`. Use the hover pseudoclass we used before to make it bold when you hover over it.
4. In your body CSS rule, remove the `background-color` directive. Replace it with: `background: linear-gradient(0deg, #CCC, white)`. What does it look like? This is called a CSS3 directive and is a feature of newer directives. Try adjusting the angles, colors, and add another color to the list.
5. In your `h1` directive, add: `text-shadow: 2px 2px 1px blue;`. This gives a shadow to your text. Try changing all of the numbers and colors to see what happens.
6. Add a `border-radius` to your figure. Start with 3px, and increase it to something crazy like 100px. What happens?
