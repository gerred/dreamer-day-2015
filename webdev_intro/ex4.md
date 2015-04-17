# Organizing our Page with CSS

CSS isn't just for making our site look pretty. We can also change how our page is laid out. Remembering from before, our HTML is laid out like legos and grouped into sections. CSS can move these entire sections around, giving us a lot of power in layout.

There are many options in CSS for display. We can adjust the space around our elements with `padding` and `margin`. To change how sections sit next to each other, we can use the `display` directive. If we want total freedom, `position` and `float` will let us arbitrarily move content to where we want.

To change the size of your blocks, you can use `width` and `height` directives. Remember to use units. In this class, we will always use `px` as a unit for pixels. For example: `width: 300px;`.

Be careful with `position` and `float`. This level of freedom can affect how your page looks in other browsers and on mobile devices like phones and tablets.

## Exercises
1. Set the `body` width to 600px. What happens?
2. Now add `margin: auto` to the body rule and see what happens.
2. Make a `footer` tag with your names in it. Move the footer around. Try adding a CSS rule for the footer with `position: absolute` in it. Look at what happens. Now, add: `bottom: 0;` and `left: 0;` to it. What happens? Try changing these values to `10px`. Move the footer to a place you like.
3. Move our image to the right. Start with `float: right;`. What happens? Remove the float and change your HTML around to place the image on the right hand side of the facts.
4. Wrap your main text and image in a `div` of it's own. What happens? Can you make the main text and the image sit side by side?
5. Add a class called `article` to your wrapper so we can style it. Try adding `display: flex;` to this new rule. Now add two subrules for `.article p` and `.article img`. In each of those, put: `flex: 1;`. What happens?
6. In your `.article` rule, add: `align-self: middle;`. What happens? Try changing this to `baseline` and `flex-end`.
7. Spend a few minutes laying out the page how you like. What challenges did you encounter?
