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
    