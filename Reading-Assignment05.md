# Reading Assignment 05
## Design Web Pages with CSS

Cascading Style Sheets, or CSS, are used to define the layout and design of your web page. When using CSS, the code renders from the top to the bottom by default. However, specificity allows you to give certain rules precedence over previously stated items in your code by creating more specific rules than those already written. Also, rules of a parent element are automatically inherited by all of their children elements \(you are also able to manually apply inheritence\). Using varying selectors and sets of declarations, or rules, within those selectors you are offered an extremely diverse capability of customizing your pages. The different types of selectors include:

- Universal
- Element
- Class
- ID
- Child
- Descendant
- Adjacent Sibling
- General Sibling

Using these different selectors, you are able to define how your HTML code looks to the user in many different ways. The color template of your entire page, font size and interactivity, and even the physical layout of your page are just a few examples of what you are able to work with using CSS. When designing the layout of your page, you must consider the fact that each element of your HTML code is rendered as an invisible box that you can physicaly see using your browsers inspector \(as well as a few other ways\). These boxes are very important because of what they are comprised of; the actual content, the contents padding, the padding border, and then the margin. Customizing these propeties of an element can be difficult because of how they respond to all of the boxes that are surrounding them but once you know how to work with them it can be very rewarding with rendering the final result of your page and its presentability to the user.

Now, on the subject of the user, it is very important to consider your color scheme for your page. Contrast is a key property, as it affects not only the readability of your page, but also the presentability. There are a few web pages that can help you choose a complimentary color scheme, but for now we will stick to terminology and the different ways you can work with your overall color template. Hue is the general basis of color, saturation is the amount of gray in that color, and brightness is the amount of black in that color \(adversely lightness is the amount of white in your color\). Later versions of code allow you to work with an alpha property as well that defines the transparency of your color. Cumulatively, these properties allow you to define your color within CSS using the hsla declaration, or hsl if you aren't customizing transparency. Other common ways to set your color are with RGB that expresses how much red, green and blue is used, hex codes that you can find in a color creator online, or finally there are 147 predetermined color names.