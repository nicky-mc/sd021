# HTML
## The Basics of HTML

Welcome to the world of web development! Today, we'll explore **HTML**, the fundamental building block of every website you've ever visited.

#### **1\. What is HTML?**

Imagine you are building a house. Before you can paint the walls or add furniture, you need a solid structure—the foundation, walls, and roof. In the world of websites, **HTML is that structure**.

HTML stands for **H**yper**T**ext **M**arkup **L**anguage. Let's break that down:

*   **HyperText:** This means the text is more than just plain words. It can be "linked" to other documents or pages. When you click a link to go to another page, you're using hypertext.
    
*   **Markup Language:** This means HTML is not a programming language that performs actions. Instead, it's a language that uses special keywords, called **tags**, to "mark up" or describe the content. It tells the web browser (like Chrome or Firefox) how to structure the text, images, and other content it needs to display.
    

> **In short: HTML gives a webpage its structure and meaning.**

#### **2\. The Building Blocks: Tags, Elements, and Attributes**

HTML works by using a system of tags, elements, and attributes.

**a) Tags**

A tag is a keyword enclosed in angle brackets (< and >). Tags are the primary way we tell the browser what something is. Most tags come in pairs:

*   An **opening tag**:
    
*   A **closing tag**:
    
    (notice the forward slash /)
    

**b) Elements**

An element is the complete package: the opening tag, the content inside, and the closing tag.

**c) Attributes**

Attributes provide **additional information** about an element. They are always placed inside the opening tag and are made up of a name and a value in the format name="value".

*   HTML[Go to Google](https://www.google.com)
    
*   HTML![](images/cat.jpg)
    

#### **3\. The Basic Structure of Every HTML Page**

Every HTML document follows the same basic structure, often called "boilerplate." It tells the browser that it's reading an HTML page.

HTML

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML          `Page Title`        

Let's look at each part:

*   : This is the very first thing on the page. It's a declaration that tells the browser this document is an HTML5 page.
    
*   : This is the **root element**. Everything else in the document is contained within it. The lang="en" attribute specifies the page language is English.
    
*   : This section contains **metadata**—data _about_ the webpage. This information is **not** displayed on the page itself. It includes things like the page title, character set, and links to stylesheets.
    
*   : The title of your webpage. This is the text that appears in the browser tab.</div></li><li class="slate-li"><div style="position:relative"><body>: This is where the magic happens! This section contains <strong class="slate-bold">all the visible content</strong> of your webpage—headings, paragraphs, images, links, lists, etc.</div></li></ul><p class="slate-paragraph"></p><h4 class="slate-h4"><strong class="slate-bold">4. Common Tags for Content</strong></h4><p class="slate-paragraph"></p><p class="slate-paragraph">Here are a few of the most common tags you'll use to add content inside the <body> tag.</p><p class="slate-paragraph">Tag(s)NamePurpose<h1> to <h6>HeadingsDefines headings. <h1> is the most important, <h6> is the least.<p>ParagraphDefines a paragraph of text.<a>Anchor (or Link)Creates a clickable link. Requires the href attribute.<img>ImageEmbeds an image. Requires the src and alt attributes. (Note: <img> is self-closing).<ul> and <li>Unordered ListCreates a bulleted list. <ul> is the container, and <li> is each list item.<ol> and <li>Ordered ListCreates a numbered list. <ol> is the container, and <li> is each list item.Export to Sheets</p><p class="slate-paragraph"></p><h4 class="slate-h4"><strong class="slate-bold">5. Putting It All Together: A Full Example</strong></h4><p class="slate-paragraph"></p><p class="slate-paragraph">Here is a simple example of a complete HTML page that uses the concepts we've discussed.</p><p class="slate-paragraph">HTML</p><pre class="slate-code\_block"><select style="float:right" contenteditable="false"><option value="">Plain text</option><option value="antlr4">ANTLR4</option><option value="bash">Bash</option><option value="c">C</option><option value="csharp">C#</option><option value="css">CSS</option><option value="coffeescript">CoffeeScript</option><option value="cmake">CMake</option><option value="dart">Dart</option><option value="django">Django</option><option value="docker">Docker</option><option value="ejs">EJS</option><option value="erlang">Erlang</option><option value="git">Git</option><option value="go">Go</option><option value="graphql">GraphQL</option><option value="groovy">Groovy</option><option value="html" selected="">HTML</option><option value="java">Java</option><option value="javascript">JavaScript</option><option value="json">JSON</option><option value="jsx">JSX</option><option value="kotlin">Kotlin</option><option value="latex">LaTeX</option><option value="less">Less</option><option value="lua">Lua</option><option value="makefile">Makefile</option><option value="markdown">Markdown</option><option value="matlab">MATLAB</option><option value="markup">Markup</option><option value="objectivec">Objective-C</option><option value="perl">Perl</option><option value="php">PHP</option><option value="powershell">PowerShell</option><option value="properties">.properties</option><option value="protobuf">Protocol Buffers</option><option value="python">Python</option><option value="r">R</option><option value="ruby">Ruby</option><option value="sass">Sass (Sass)</option><option value="scss">Sass (Scss)</option><option value="scheme">Scheme</option><option value="sql">SQL</option><option value="shell">Shell</option><option value="swift">Swift</option><option value="svg">SVG</option><option value="tsx">TSX</option><option value="typescript">TypeScript</option><option value="wasm">WebAssembly</option><option value="yaml">YAML</option><option value="xml">XML</option></select><code ><div class="slate-code\_line"><!DOCTYPE html></div><div class="slate-code\_line"><html lang="en"></div><div class="slate-code\_line"> <head></div><div class="slate-code\_line"> <title>My Favourite Place
    
    My Favourite Place: Norwich
    ===========================
    
    ![A photo of the Norwich Cathedral spire.](norwich_cathedral.jpg)
    
    Norwich is a beautiful city in Norfolk, England. It has a rich history,
    
    a stunning cathedral, and a vibrant market.
    
    A few things I love about Norwich:
    
*   The historic Norwich Lanes

*   Walking by the River Wensum

*   The friendly people

You can learn more by visiting the

[official tourism website](https://www.visitnorwich.co.uk/).

If you saved this code as index.html and opened it in a web browser, you would see a structured, easy-to-read webpage! You've just taken your first step into web development.