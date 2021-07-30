# CSS

- CSS stands for **C**ascading **S**tyle **S**heet.

- Contols what HTML looks like, how it is styled, laid out, can change color of text, etc...

- CSS is a rule based language where you define rules to be applied to certain elements on the webpage.

- Style sheets will have rules written one after another.

- Finding documentation on CSS and how it behaves is very helpful. Places like [mdn](https://developer.mozilla.org/en-US/docs/Web/CSS) and [W3Schools](https://www.w3schools.com/css/) are my favorite personally.

- Checking implementations status sense some features may or may or may not work.

- To check browser support status check the mdn property page in the section "Browser Compatibility". This will check if the property can be used onyour site. An example of the chart can be found [here](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS#browser_compatibility).

## How to add CSS

**_3 Ways to insert CSS:_**

1. **External CSS:** 

    - Change the appearance of the whole site by changing a single file.

    - HTML *has* to include the reference to the external style sheet in the ```<link>``` element that's in the ```<head>``` section.

    - Must have **.css** extension and not contain any HTML tags.

2. **Internal CSS:** 

    - Can be used if one HTML page has a unique style

    - Defined inside the ```<style>``` element in the ```<head>``` section.

3. **Inline CSS:**

    - Used to apply a unique style to a single element.

    - To use, add the style attribute to the relevant element. The attribute will contain CSS property.

    - *Example:* ```<h1 style="color: pink; text-align: right;">some text here<\h1>```

- If there are multiple style sheets, and properties have been defined for the same element, the value from the last read style sheet will be used.

## Cascading Order

Which style is used if there is more than one style for an HTML element?

- Styles will cascade into a virtual style sheet. Number one has the highest priority as follows:

    1. Inline style: this is what is inside the HTML element.

    2. External and Internal: this is what is in the ```<head>``` section.

    3. Browser default

## CSS Color Property

- color property specifies text color. Combine with a background color to make the text easier to read.

### Syntax

- color: *color*|*initial*|*inherit*

  - **Color:** the color of the text

  - **Initial:** set the default value of the property

  - **Inherit:** inherits property from parent element.

To find more CSS References, click [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference).

[Home](https://cquinn21.github.io/.github.io-reading-notes/index)
