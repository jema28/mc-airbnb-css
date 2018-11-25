# airbnb CSS challenge

## Learning Outcomes

- Practice implementing a design with CSS
- Practice writing CSS using pre-defined variables (a style guide)
- Exposure to [BEM](https://css-tricks.com/bem-101/), a CSS class-naming convention
- To see an example of a well structured semantic HTML and CSS

## Task

Your task is to implement the following **mobile design** using CSS:

<p align="left">
  <img src="https://user-images.githubusercontent.com/25960351/48894868-76089800-ee4c-11e8-8125-70f977b0902b.png">
</p>

**Notes:**

- Read the HTML, but you shouldn't change it.
- We have provided **CSS Variables** to be used in the style rules. You should use them! And you do not need to edit them.
- We have provided empty CSS rules for all the classes in the html. Not every CSS rule needs to be filled.
- Have fun!

**Stretch Goal:**

- Draw your own desktop design and implement it using media queries!

## CSS Variables

We have defined some CSS variables ([MDN link](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)) to be used in style rules. Check them out at the top of the `main.css` file.

Variable definition:

```css
html {
  --spacing-x-large: 4rem;
}
```

How to use them:

```css
.my-class {
  margin: var(--spacing-x-large);
}
```

### Colours

Here you can see a screenshot from my editor, displaying the colours which we have defined for you:

![colours](https://user-images.githubusercontent.com/16781318/48892918-cfba9380-ee47-11e8-8c9b-2481912c05fe.png)

If you haven't already, add the extension to your editor to allow you to see the colours!

## Further Reading

- [introduction to BEM](http://getbem.com/introduction/)

**Design source:** Nicole Saidy, [Streamline your workflow: The efficient UI/UX design process in Figma](https://www.skillshare.com/classes/Streamline-your-workflow-The-efficient-UIUX-design-process-in-Figma/1199486748/project-guide) / [Figma link](https://www.figma.com/file/eYSN1YL4WnSvEojPzmUIOp/Airbnb-Design)
