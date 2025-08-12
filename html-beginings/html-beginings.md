## Welcome to Web Development!

## 

Welcome to the world of web development! Today, we'll explore **HTML**, the fundamental building block of every website you've ever visited. 🏠

* * *

### What is HTML?

## 

Imagine you're building a house. Before you can paint the walls or add furniture, you need a solid structure—the foundation, walls, and roof. In the world of websites, **HTML is that structure**.

HTML stands for **H**yper**T**ext **M**arkup **L**anguage. Let's break that down:

*   **HyperText**: This means the text is more than just plain words. It can be "linked" to other documents or pages. When you click a link to go to another page, you're using hypertext.
    
*   **Markup Language**: This means HTML isn't a programming language that performs actions. Instead, it's a language that uses special keywords, called **tags**, to "mark up" or describe the content. It tells the web browser (like Chrome or Firefox) how to structure what it displays.
    

> **In short: HTML gives a webpage its structure and meaning.**

* * *

### The Building Blocks: Tags, Elements, and Attributes

## 

HTML works by using a system of tags, elements, and attributes.

#### Tags

## 

A **tag** is a keyword enclosed in angle brackets (`<` and `>`). Tags are the primary way we tell the browser what something is. Most tags come in pairs: an **opening tag** and a **closing tag**.

*   An **opening tag**: `<p>`
    
*   A **closing tag**: `</p>` (notice the forward slash `/`)
    

#### Elements

## 

An **element** is the complete package: the opening tag, the content inside, and the closing tag.

#### Attributes

## 

**Attributes** provide **additional information** about an element. They are always placed inside the opening tag and are made up of a `name` and a `value` in the format `name="value"`.

*   Example 1: A Link
    
    The <a> tag needs the href attribute to know where to link to.
    
    HTML
    
        <a href="https://www.google.com">Go to Google</a>
    
*   Example 2: An Image
    
    The <img> tag needs the src attribute to know which image to display.
    
    HTML
    
        <img src="images/cat.jpg" alt="A photo of a cat">
    

* * *

### The Basic Structure of Every HTML Page

## 

Every HTML document follows the same basic structure, often called "boilerplate." It tells the browser that it's reading an HTML page.

HTML

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <title>Page Title</title>
      </head>
      <body>
        </body>
    </html>

Let's look at each part:

*   `<!DOCTYPE html>`: This is the very first thing on the page. It's a declaration that tells the browser this document is an HTML5 page.
    
*   `<html>`: This is the **root element**. Everything else in the document is contained within it. The `lang="en"` attribute specifies the page language is English.
    
*   `<head>`: This section contains **metadata**—data _about_ the webpage. This information is **not** displayed on the page itself. It includes things like the page title and character set.
    
*   `<title>`: The title of your webpage. This is the text that appears in the browser tab.
    
*   `<body>`: This is where the magic happens! This section contains **all the visible content** of your webpage—headings, paragraphs, images, links, etc.
    

* * *

### Common Tags for Content

## 

Here are a few of the most common tags you'll use to add content inside the `<body>` tag.

| Tag(s) | Name | Purpose |
| --- | --- | --- |
| <h1> to <h6> | Headings | Defines headings. <h1> is the most important. |
| <p> | Paragraph | Defines a paragraph of text. |
| <a> | Anchor (Link) | Creates a clickable link. Requires the href attribute . |
| <img> | Image | Embeds an image. Requires src and alt attributes. |
| <ul> and <li> | Unordered List | Creates a bulleted list. <ul> is the container, <li> is each item. |
| <ol> and <li> | Ordered List | Creates a numbered list. <ol> is the container, <li> is each item. |

* * *

### Putting It All Together: A Full Example

## 

Here is a simple example of a complete HTML page that uses the concepts we've discussed.

HTML

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <title>My Favourite Place</title>
      </head>
      <body>
        <h1>My Favourite Place: Norwich</h1>
    
        <img src="norwich_cathedral.jpg" alt="A photo of the Norwich Cathedral spire.">
    
        <p>Norwich is a beautiful city in Norfolk, England. It has a rich history, a stunning cathedral, and a vibrant market.</p>
    
        <p>A few things I love about Norwich:</p>
        <ul>
          <li>The historic Norwich Lanes</li>
          <li>Walking by the River Wensum</li>
          <li>The friendly people</li>
        </ul>
    
        <p>You can learn more by visiting the <a href="https://www.visitnorwich.co.uk/">official tourism website</a>.</p>
      </body>
    </html>

If you saved this code as `index.html` and opened it in a web browser, you would see a structured, easy-to-read webpage! You've just taken your first step into web development.