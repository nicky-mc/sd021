## Introduction to CSS

## 

Welcome to the next step in your web development journey: **CSS**! If HTML is the structure of your house, CSS is the interior designer, painter, and landscaper. It's what makes your website look good!

* * *

### What is CSS?

## 

**CSS** stands for **C**ascading **S**tyle **S**heets.

*   **Cascading**: This refers to how CSS rules are applied and how conflicts are resolved when multiple rules apply to the same element. We'll dive deeper into this later, but for now, think of it as a hierarchy of styles.
    
*   **Style**: This is all about how your content looks—colors, fonts, spacing, layout, and much more.
    
*   **Sheets**: CSS rules are typically written in separate files (or "sheets") from your HTML, making your code organized and easier to manage.
    

> **In short: CSS describes how HTML elements are to be displayed on screen, paper, or in other media.**

* * *

### Why Use CSS?

## 

Before CSS, all styling had to be done directly within the HTML using attributes. This led to:

*   **Messy HTML**: Your structural code was cluttered with presentation details.
*   **Difficult Maintenance**: Changing the look of your entire website meant editing every single HTML page.
*   **Limited Design Options**: HTML alone doesn't offer much in terms of sophisticated design.

CSS solves these problems by:

*   **Separation of Concerns**: Keeping content (HTML) and presentation (CSS) separate.
*   **Efficiency**: You can change the style of an entire website by changing just one CSS file.
*   **Rich Design**: CSS provides a vast array of properties to create visually appealing and responsive designs.

* * *

### How CSS Works: Selectors, Properties, and Values

## 

CSS rules are made up of three main parts:

#### 1. Selectors

## 

A **selector** points to the HTML element(s) you want to style. There are many types of selectors, but here are the most common:

*   **Element Selector**: Selects all instances of a specific HTML element.
    
    ```css
    p {
      /* styles for all paragraphs */
    }
    h1 {
      /* styles for all h1 headings */
    }
*   **Class Selector**: Selects all instances of a specific class.
    
    .my-class {
      /* styles for all elements with the class "my-class" */
    }
            
*   **ID Selector**: Selects a specific element by its ID.
    
    #my-id {
      /* styles for the element with the ID "my-id" */
    }                                    **
*   **Attribute Selector**: Selects elements based on their attributes.
    
    [data-custom="value"] {
      /* styles for elements with the attribute "data-custom" set to "value" */
    }
*   **Universal Selector**: Selects all elements.
    
    * {
      /* styles for all elements */
    }   

#### 2. Properties

##
A **property** is the aspect of the element you want to change, like color, font size, or margin. Each property has a specific name.
#### 3. Values

  ## A **Value** is selector {
  property: value;
  property-2: value-2;
}
```

**Example:**

```css
p {
  color: blue; /* 'color' is the property, 'blue' is the value */
  font-size: 16px; /* 'font-size' is the property, '16px' is the value */
}

h1 {
  font-weight: bold; /* 'font-weight' is the property, 'bold' is the value */
}
```

###
#### Putting It All Together
##
Here's how a complete CSS rule looks:

```css
selector {
    property: value;
    property-2: value-2;
    }
    ```
```html
        <p>Norwich is a city in Norfolk, England, known for its rich history and beautiful architecture.</p>
        <img src="norwich.jpg" alt="A view of Norwich">
        <h2>Why I Love Norwich</h2>
        <ul>
          <li>Historic buildings</li>
          <li>Beautiful parks</li>
          <li>Great food scene</li>
        </ul>
      </body>
    </html> 
```

###     
This example includes a heading, an image, a paragraph, and a list—all styled with CSS.
* * *
### Conclusion
##
Now you have a solid understanding of the basics of HTML and CSS! You've learned how to structure a webpage with HTML and style it with CSS.
You can create simple yet effective webpages that are both functional and visually appealing.