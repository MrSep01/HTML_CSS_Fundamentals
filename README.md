# 📚 HTML_CSS_Fundamentals

## 🚀 Web Development Fundamentals

👋 Welcome to this GitHub repository! Here, you'll find resources to understand the fundamentals of Web Development. We'll cover definitions, usage, and examples of essential terms. If you have any questions or suggestions, don't hesitate to raise an issue or submit a pull request. Happy learning! 🎉

## 📖 Terms and Definitions

### 🏷️ Attributes

- **Definition**: Attributes provide additional information about an HTML element.
- **Usage**: They are included in the opening tag of the element.
- **Example**: `<img src="image.jpg" alt="A beautiful image">` Here, `src` and `alt` are attributes.

### 💻 Client

- **Definition**: A client is the device or user that requests information or services from a server.
- **Usage**: In the context of web development, a client is typically a web browser.
- **Example**: When you access a webpage on your browser, the browser acts as a client requesting data from the server.

### 🎨 CSS

- **Definition**: Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document written in HTML or XML.
- **Usage**: CSS can be used to define styles for web pages, including the design, layout, and variations in display for different devices and screen sizes.
- **Example**:

  ```css
  body {
    background-color: lightblue;
  }
  ```

### 🖌️ CSS declaration

- **Definition**: A CSS declaration is a part of a CSS rule-set. It consists of a CSS property and a value separated by a colon.
- **Usage**: Declarations are used to provide the styling properties to the selected HTML elements.
- **Example**:

  ```css
  h1 {
    color: blue;
  }
  ```

  In the above example, `color: blue;` is a CSS declaration.

### 🎛️ CSS property

- **Definition**: A CSS property is a type of identifier that defines the aspect of a HTML element that will be styled.
- **Usage**: CSS properties are used in conjunction with HTML elements and CSS values to style web pages.
- **Example**: In the declaration `color: blue;`, `color` is the CSS property.

### 📏 CSS rule

- **Definition**: A CSS rule-set consists of a selector and a declaration block. The selector points to the HTML element you want to style.
- **Usage**: CSS rule-sets are used to apply styles to HTML elements selected by the selector.
- **Example**:

  ```css
  p {
    color: red;
    text-align: center;
  }
  ```

  In the above example, `p { color: red; text-align: center; }` is a CSS rule.

### 📄 DOM (Document Object Model)

- **Definition**: The Document Object Model (DOM) is a programming interface for web documents. It represents the structure of a document and enables a way to manipulate its content and visual presentation by connecting web documents to scripts or programming languages.
- **Usage**: DOM is used to manipulate, navigate, and interact with web pages using JavaScript.
- **Example**:

  ```javascript
  document.getElementById("demo").innerHTML = "Hello, World!";
  ```

  In the above JavaScript code, `document` is the entry point to the web page's content (the DOM).

### 📝 HTML

- **Definition**: HyperText Markup Language (HTML) is the standard markup language for creating web pages. It describes the structure of a web page.
- **Usage**: HTML is used to create the basic structure and content of a web page.
- **Example**:

  ```html
  <!DOCTYPE html>
  <html>
    <head>
      <title>Page Title</title>
    </head>
    <body>
      <h1>My First Heading</h1>
      <p>My first paragraph.</p>
    </body>
  </html>
  ```

### 📜 HTML document

- **Definition**: An HTML document is a file containing HTML code that describes the structure of a web page.
- **Usage**: HTML documents serve as the blueprint for web pages and are typically served to a client by a server in response to an HTTP request.
- **Example**: The HTML code block above represents a basic HTML document.

### 🧩 HTML element

- **Definition**: HTML elements are the building blocks of HTML pages. An HTML element is defined by a start tag, some content, and an end tag.
- **Usage**: HTML elements are used to structure content on a web page.
- **Example**: `<p>My first paragraph.</p>` Here, this is an example of a paragraph element in HTML.

### 📬 HTTP (Hypertext Transfer Protocol)

- **Definition**: HTTP is the protocol used for transferring data over the internet. It defines commands and services used for transmitting webpage data.
- **Usage**: HTTP is used when a browser requests a web page from a server.
- **Example**: When you type `https://www.example.com` in your web browser, it sends an HTTP request to the server that hosts `example.com`.

### 📨 HTTP request

- **Definition**: An HTTP request is made by a client to a server in the form of a request method, URL, and protocol version, followed by a MIME-like message containing request modifiers, client information, and possible body content.
- **Usage**: HTTP requests are used by browsers to request files from servers.
- **Example**: When you enter a URL into your browser, the browser sends an HTTP GET request to the appropriate web server.

### 📩 HTTP response

- **Definition**: An HTTP response is what is sent by a server to a client in response to an HTTP request.
- **Usage**: HTTP responses are used to deliver requested resources from servers to clients.
- **Example**: When you request a webpage by entering a URL, the server processes that request and returns an HTTP response containing the webpage's HTML code.

### 📜 JavaScript

- **Definition**: JavaScript is a scripting language that allows you to create complex features on web pages.
- **Usage**: JavaScript is used for enhancing web pages to provide for a more user-friendly experience.
- **Example**:

  ```javascript
  document.getElementById("demo").innerHTML = "Hello, World!";
  ```

### 🏷️ Opening/closing tags

- **Definition**: Opening and closing tags are used in markup languages, such as HTML and XML, to denote the start and end of a tag or element.
- **Usage**: They are used to structure and order the content of a web page.
- **Example**: In `<p>My first paragraph.</p>`, `<p>` is the opening tag and `</p>` is the closing tag.

### 🖥️ Server

- **Definition**: A server is a computer that serves information to other computers on a network.
- **Usage**: In the context of web development, a server is typically a machine that hosts websites and responds to requests from clients.
- **Example**: When you access `https://www.example.com`, `example.com` is hosted on a server which responds to your request.

### 🌐 URL (Uniform Resource Locator)

- **Definition**: A URL is the address of a resource on the Internet.
- **Usage**: URLs are used to specify the location of a web page, image, file, or other resource on the internet.
- **Example**: `https://www.example.com`

### ✅ Validation

- **Definition**: Validation in the context of web development involves checking whether the HTML and CSS code adheres to the standards set by the W3C.
- **Usage**: Validation helps in writing syntactically correct code which in turn leads to better search engine rankings, enhanced accessibility, and easier maintenance.

## 🧠 Learning Summary

Let's recap what we've learned so far:

- **HTML** (Hypertext Markup Language) is like the skeleton of the web. It gives web pages structure and holds the content (like text, images, videos).
- **CSS** (Cascading Style Sheets) is like the clothing and makeup of the web. It styles the web pages to make them visually appealing.
- **JavaScript** is the brains of the operation. It makes the web pages interactive and dynamic.
- To view a web page, you just need to type its **URL** (Uniform Resource Locator) into the address bar of your browser.
- Ever wondered what's happening behind the scenes of a web page? Simply right-click on the page and select `View Page Source`.
- **HTTP** (Hypertext Transfer Protocol) is the messenger delivering messages (data) between the client (browser) and the server.
- Visiting a website is like a conversation: your browser sends an **HTTP request** to the server, and the server answers with an **HTTP response**.
- **DOCTYPE**, **html**, **head**, and **body** are some key parts of an HTML document. The `head` contains information about the page, and the `body` contains the actual content.
- **HTML tags** are like containers. They hold and structure content on a web page.
- **Attributes** in HTML are additional information about elements, coded inside the opening tag.
- **CSS rule** is a set of styles that you apply to a specific element on your webpage.
- Want to keep your code neat and readable? **Prettier** is a VSCode extension that auto-formats your code for you.
- Writing valid HTML/CSS code and following the official rules is not only good practice but also helps you rank better in search engines.

🎉 I hope you find this content helpful. Please consider giving this repository a star and sharing it with others. If you have any questions, or would like to contribute, don't hesitate to raise an issue or submit a pull request. For more resources, you can also visit my website. Happy Coding! 🎉

## 🔤 HTML Basics

- **🔗 Absolute URLs**: These are URLs that specify the full path to a resource, including the protocol (like `http://`), the domain, and the specific file or page.

  - **Usage**: Absolute URLs are used when linking to web pages or resources on different websites.
  - **Example**: `https://www.example.com/about.html`

- **📦 Block-level elements**: These are HTML elements that start on a new line in the document and occupy the full width available.

  - **Usage**: Block-level elements are typically used to structure the layout of the page.
  - **Example**: `<div>`, `<h1>` to `<h6>`, `<p>`, and `<ul>`

- **🔣 Character sets**: HTML documents should specify the character set used, typically UTF-8, using the `<meta charset="UTF-8">` tag within the `<head>` element.

  - **Usage**: Character sets ensure that the document can correctly render special or non-English characters.
  - **Example**: `<meta charset="UTF-8">`

- **📦 Container elements**: These are HTML elements that can contain other elements, including both block-level and inline elements.

  - **Usage**: Container elements are typically used for grouping related elements and for layout purposes.
  - **Example**: `<div>`, `<section>`, and `<article>`

- **📋 Description lists**: These are lists of terms with their associated descriptions, created using the `<dl>` (description list), `<dt>` (description term), and `<dd>` (description description) elements.

  - **Usage**: Description lists are often used for glossaries or to display metadata (name-value pairs).
  - **Example**:

  ```html
  <dl>
    <dt>Coffee</dt>
    <dd>A hot beverage made from coffee beans.</dd>
    <dt>Milk</dt>
    <dd>A nutritious liquid food produced by mammals.</dd>
  </dl>
  ```

- **ℹ️ Entities**: These are used to represent special characters that cannot be typed directly into the document, such as `&lt;` for `<`, `&gt;` for `>`, `&amp;` for `&`, `&quot;` for `"`, and `&apos;` for `'`.

  - **Usage**: Entities are used to display special characters that have a specific meaning in HTML.
  - **Example**: To display `<`, you can use `&lt;`.

- **📄 HTML boilerplate**: This refers to the basic HTML document structure that is the starting point for creating a web page. It includes the `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` elements.

  - **Usage**: The boilerplate is the starting point for any HTML document.
  - **Example**:

  ```html
  <!DOCTYPE html>
  <html>
    <head>
      <title>Page Title</title>
    </head>
    <body></body>
  </html>
  ```

- **🔗 Hyperlinks**: These are created using the `<a>` (anchor) element. The destination URL is specified in the `href` attribute.

  - **Usage**: Hyperlinks are used to navigate between web pages.
  - **Example**: `<a href="https://www.example.com">Visit Example.com</a>`

- **⚛️ Inline elements**: These are HTML elements that do not start on a new line and only take up as much width as necessary.

  - **Usage**: Inline elements are typically used for text-level semantics, formatting, and phrasing.
  - **Example**: `<span>`, `<img>`, `<a>`, and `<em>`

- **🔢 Ordered lists**: These are lists of items where the order does matter, created using the `<ol>` (ordered list) and `<li>` (list item) elements.

  - **Usage**: Ordered lists are typically used when the items' sequence is essential, such as instructions or rankings.
  - **Example**:

  ```html
  <ol>
    <li>First item</li>
    <li>Second item</li>
  </ol>
  ```

- **🔗 Relative URLs**: These are URLs that specify the path to a resource relative to the current document. They do not include the protocol or domain.

  - **Usage**: Relative URLs are used when linking to web pages or resources on the same website.
  - **Example**: `images/pic.jpg`

- **📚 Semantic HTML**: These are HTML elements that provide information about the type of content they contain, such as `<header>`, `<footer>`, `<nav>`, `<main>`, `<aside>`, `<article>`, `<section>`, `<figure>`, `<time>`, and `<mark>`.

  - **Usage**: Semantic elements are used to give meaning to the structure of web content, improving accessibility and SEO.
  - **Example**:

  ```html
  <article>
    <header>
      <h1>Title of the Article</h1>
    </header>
    <p>The content of the article...</p>
  </article>
  ```

- **🏗️ Structural elements**: These are HTML elements that describe the structure of the webpage and include elements like `<header>`, `<footer>`, `<nav>`, `<article>`, `<section>` and `<aside>`.

  - **Usage**: Structural elements are used to structure and organize the content of a web page.
  - **Example**:

  ```html
  <header>
    <!-- Header content -->
  </header>
  <nav>
    <!-- Navigation content -->
  </nav>
  <main>
    <!-- Main content -->
  </main>
  <aside>
    <!-- Sidebar content -->
  </aside>
  <footer>
    <!-- Footer content -->
  </footer>
  ```

- **✏️ Unordered lists**: These are lists of items where the order does not matter, created using the `<ul>` (unordered list) and `<li>` (list item) elements.

  - **Usage**: Unordered lists are typically used when the items' sequence isn't important, like a list of ingredients or a menu.
  - **Example**:

  ```html
  <ul>
    <li>First item</li>
    <li>Second item</li>
  </ul>
  ```

- **🖥️ Viewport**: The viewport is the user's visible area of a web page. It varies with the device used to access the web page.

  - **Usage**: The viewport is used for responsive web design to render pages correctly on different devices.
  - **Example**: `<meta name="viewport" content="width=device-width, initial-scale=1">`

- **📝 Zen coding**: Zen Coding (now known as Emmet) is a set of plug-ins for text editors that allow for high-speed coding and editing in HTML, XML, XSL, and other structured code formats.
  - **Usage**: Zen coding/Emmet is used to enhance the speed of writing HTML/CSS code.
  - **Example**: In Emmet, if you want to create a `div` with an id of `container`, which includes an unordered list with five items, you would type the following shorthand structure and then press `Tab`:
  ```plaintext
  div#container>ul>li*5
  ```
  This would immediately expand into:
  ```html
  <div id="container">
    <ul>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </div>
  ```
  ***

## 📚 HTML Basics in Practice

- 📂 The `<head>` section is used to provide information about a webpage.

  - **Usage**: The `<head>` section usually contains meta-information about the document such as its title, scripts, and link to CSS files.
  - **Example**:

  ```html
  <head>
    <title>Page Title</title>
  </head>
  ```

- 📝 The `<p>` element is used to represent a paragraph. A paragraph can be one or many lines of text.

  - **Usage**: The `<p>` element is used to group sentences or phrases that form a standalone block of text.
  - **Example**: `<p>This is a simple paragraph.</p>`

- 🎯 The `<em>` element is used to define emphasized text. By default, emphasized text is displayed in italic.

  - **Usage**: The `<em>` element is used to give emphasis to a certain part of the text.
  - **Example**: `<p>I am <em>very</em> excited about learning HTML.</p>`

- 💪 The `<strong>` element is used to represent important content. Browsers, by default, render strong content in bold.

  - **Usage**: The `<strong>` element is used to highlight important parts of the text.
  - **Example**: `<p>This is a <strong>very important</strong> point.</p>`

- 📊 Headings are represented using `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`. Every web page should have one and only one `<h1>` element. Headings should have a natural hierarchy and should not be skipped.

  - **Usage**: Headings are used to structure the content of a webpage and make it easy to read and navigate.
  - **Example**:

  ```html
  <h1>Main Title</h1>
  <h2>Subheading 1</h2>
  <h3>Sub-subheading 1</h3>
  <h2>Subheading 2</h2>
  ```

- 🔗 The `<a>` (anchor) element, with its href attribute, is used to create a hyperlink to web pages, locations in the same page, files, and email addresses.

  - **Usage**: The `<a>` element is used to create clickable elements that redirect users to different parts of the webpage or to different webpages.
  - **Example**: `<a href="https://www.example.com">Visit Example.com</a>`

- 🖼️ The `<img>` element is used to display an image. It’s a common best practice to set the `alt` (alternative text) attribute. This helps visually impaired people understand the page content. Also, if the image cannot be loaded, the alternative text is displayed.

  - **Usage**: The `<img>` element is used to embed images in the webpage.
  - **Example**: `<img src="image.jpg" alt="A beautiful landscape">`

- 🎥 The `<video>` and `<audio>` elements are used to display video and audio. These elements have boolean attributes such as controls, autoplay, and loop.

  - **Usage**: These elements are used to embed media files in the webpage.
  - **Example**:

  ```html
  <video src="video.mp4" controls></video>
  <audio src="audio.mp3" controls></audio>
  ```

- 📜 The `<ul>` element is used to represent a list where the order of items doesn’t matter. The `<ol>` element is used to represent an ordered list of items. The `<dl>` (description list) element is used to implement a glossary or to display metadata.

  - **Usage**: These elements are used to create different types of lists in the webpage.
  - **Example**:

  ```html
  <ul>
    <li>Apple</li>
    <li>Banana</li>
  </ul>
  <ol>
    <li>First step</li>
    <li>Second step</li>
  </ol>
  <dl>
    <dt>HTML</dt>
    <dd>Hyper Text Markup Language</dd>
  </dl>
  ```

- 🎁 The `<div>` and `<span>` elements are generic containers used for styling purposes. Divs are block-level elements, spans are inline elements. A block-level element starts on a new line and takes up the entire available horizontal space.

  - **Usage**: `<div>` and `<span>` elements are used to group other elements for styling or to apply a specific style to a part of the text.
  - **Example**:

  ```html
  <div>
    <p>This is a paragraph inside a div.</p>
  </div>
  <p>
    This is a <span style="color: blue;">colored</span> word inside a paragraph.
  </p>
  ```

- 📖 Semantic elements help us write markup that is more meaningful and descriptive to search engines, screen readers, and other software. So, use `<div>` and `<span>` elements when no other semantic element is appropriate.

  - **Usage**: Semantic elements provide better structure and clarity to the webpage content, helping with SEO and accessibility.
  - **Example**:

  ```html
  <article>
    <header>
      <h1>Title of the Article</h1>
    </header>
    <p>The content of the article...</p>
  </article>
    <p>The content of the article...</p>
    </article>

  ```

- 🎭 The semantic elements in HTML5 are: `<header>`, `<footer>`, `<nav>`, `<main>`, `<aside>`, `<article>`, `<section>`, `<figure>`, `<time>`, and `<mark>`.

  - **Usage**: Semantic elements are used to structure the webpage content and convey the type of content they contain.
  - **Example**:

  ```html
  <section>
    <h1>Welcome</h1>
    <p>Hello, world! Welcome to my website.</p>
  </section>
  <aside>
    <h3>About Me</h3>
    <p>I'm a web developer.</p>
  </aside>
  ```

- 📊 The `<table>` element should only be used to represent tabular data. A table can have zero or more `<tr>` (table row) elements. Each `<tr>` element can have zero or more cells. Cells can be data cells (`<td>`) or header cells (`<th>`).

  - **Usage**: `<table>` is used to display tabular data, and it is organized into rows (`<tr>`) and cells (`<td>` or `<th>`).
  - **Example**:

  ```html
  <table>
    <tr>
      <th>Firstname</th>
      <th>Lastname</th>
    </tr>
    <tr>
      <td>Jane</td>
      <td>Doe</td>
    </tr>
  </table>
  ```

- 🖌️ The `<i>` and `<b>` elements are considered deprecated because HTML should not be used for styling. That’s the role of CSS.

  - **Usage**: While `<i>` and `<b>` can still be used for italics and bold text respectively, it is better practice to use CSS for these purposes, or the `<em>` and `<strong>` elements for conveying emphasis.
  - **Example**: Instead of `<b>Bold text</b>`, use `<strong>Important text</strong>` and style it using CSS: `strong { font-weight: bold; }`.

- 🚀 Entities are used to display special characters such as angle brackets, copyright symbol, etc. The most important entities are: `&nbsp;` (non-breaking space), `&lt;` (less than sign), `&gt;` (greater than sign), and `&copy;` (copyright symbol).

  - **Usage**: Entities are used to represent special characters in HTML that have a specific meaning in the syntax.
  - **Example**: To display a copyright symbol, you can use `&copy;`.

- 🌐 A relative URL specifies the target resource relative to the current resource. An absolute URL specifies the location of a resource irrespective of the current resource. It can start with a `/` to indicate the root of the website or a protocol (eg `http://`) to represent a resource on a different website.

  - **Usage**: Relative URLs are typically used for resources within the same website, while absolute URLs are used for external resources.
  - **Example**:

  ```html
  <!-- Relative URL -->
  <a href="/contact.html">Contact</a>
  <!-- Absolute URL -->
  <a href="https://www.example.com/contact.html">Contact</a>
  ```

  - 📸 The `<img>` element is used to display an image. It’s a common best practice to set the `alt` (alternative text) attribute. This helps visually impaired people understand the page content. Also, if the image cannot be loaded, the alternative text is displayed.
  - **Usage**: The `<img>` element is used to embed images in the webpage.
  - **Example**: `<img src="image.jpg" alt="A beautiful landscape">`

- 📺 The `<video>` and `<audio>` elements are used to display video and audio. These elements have boolean attributes such as controls, autoplay, and loop.

  - **Usage**: These elements are used to embed media files in the webpage.
  - **Example**:

  ```html
  <video src="video.mp4" controls></video>
  <audio src="audio.mp3" controls></audio>
  ```

- 📝 The `<ul>` element is used to represent a list where the order of items doesn’t matter. The `<ol>` element is used to represent an ordered list of items. The `<dl>` (description list) element is used to implement a glossary or to display metadata.

  - **Usage**: These elements are used to create different types of lists in the webpage.
  - **Example**:

  ```html
  <ul>
    <li>Apple</li>
    <li>Banana</li>
  </ul>
  <ol>
    <li>First step</li>
    <li>Second step</li>
  </ol>
  <dl>
    <dt>HTML</dt>
    <dd>Hyper Text Markup Language</dd>
  </dl>
  ```

- 📊 The `<table>` element should only be used to represent tabular data. A table can have zero or more `<tr>` (table row) elements. Each `<tr>` element can have zero or more cells. Cells can be data cells (`<td>`) or header cells (`<th>`).

  - **Usage**: `<table>` is used to display tabular data, and it is organized into rows (`<tr>`) and cells (`<td>` or `<th>`).
  - **Example**:

  ```html
  <table>
    <tr>
      <th>Firstname</th>
      <th>Lastname</th>
    </tr>
    <tr>
      <td>Jane</td>
      <td>Doe</td>
    </tr>
  </table>
  ```

- 📦 The `<div>` and `<span>` elements are generic containers used for styling purposes. Divs are block-level elements, spans are inline elements. A block-level element starts on a new line and takes up the entire available horizontal space.

  - **Usage**: `<div>` and `<span>` elements are used to group other elements for styling or to apply a specific style to a part of the text.
  - **Example**:

  ```html
  <div>
    <p>This is a paragraph inside a div.</p>
  </div>
  <p>
    This is a <span style="color: blue;">colored</span> word inside a paragraph.
  </p>
  ```

- 🎭 Semantic elements help us write markup that is more meaningful and descriptive to search engines, screen readers, and other software. So, use `<div>` and `<span>` elements when no other semantic element is appropriate. The semantic elements in HTML5 are: `<header>`, `<footer>`, `<nav>`, `<main>`, `<aside>`, `<article>`, `<section>`, `<figure>`, `<time>`, and `<mark>`.
  - **Usage**: Semantic elements provide better structure and clarity to the webpage content, helping with SEO and accessibility.
  - **Example**:
  ```html
  <section>
    <h1>Welcome</h1>
    <p>Hello, world! Welcome to my website.</p>
  </section>
  <aside>
    <h3>About Me</h3>
    <p>I'm a web developer.</p>
  </aside>
  ```

# 📘 CSS Basics

## 📂 Embedded stylesheets

Embedded stylesheets are CSS rules that are placed within `<style>` tags in an HTML document. This method is ideal for single-page websites or for testing CSS rules. However, they lack the benefits of maintainability and scalability associated with external stylesheets. - **Usage**: `<style>` tags in the HTML file - **Example**:
`html
      <style>
        body {
          background-color: lightblue;
        }
      </style>
      `

## 🌐 External stylesheets

External stylesheets are CSS rules written in a separate file (with .css extension) linked to an HTML document using the `<link>` tag. This method allows for more maintainability, scalability and separation of concerns. - **Usage**: Linked .css file in HTML document - **Example**:
`html
      <link rel="stylesheet" href="styles.css">
      `

## 🔢 Hexadecimal colors

Hexadecimal colors are a six-digit combination of numbers and letters defined by its mix of red, green and blue (RGB). Each hexadecimal code will range from #000000 (Black) to #FFFFFF (White). - **Usage**: To set color in CSS with high precision - **Example**:
`css
      body {
        background-color: #4286f4;
      }
      `

## 🌈 HSL colors

HSL stands for hue, saturation, and lightness, and is a way to define colors in CSS. It is designed to be more intuitive and user-friendly than RGB or hexadecimal color definitions. - **Usage**: To set color in CSS in a more intuitive way - **Example**:
`css
      body {
        background-color: hsl(120, 100%, 50%);
      }
      `

## 👪 Inheritance

Inheritance is a key feature in CSS; it is the mechanism by which properties are applied not only to a specified element, but also to its descendants. - **Usage**: Automatically applying styles to nested elements - **Example**:
`css
      body {
        color: red;
      }
      `
In this example, all body text and text within any nested elements will be red, unless specified otherwise.

## 📌 Inline styles

Inline styles are CSS rules that are added directly within the HTML tags using the `style` attribute. This method has the highest specificity but is not recommended as it does not promote reusability and maintainability. - **Usage**: To add unique styles to a single HTML element - **Example**:
`html
      <h1 style="color: blue;">Hello World</h1>
      `

## ↔️ Linear gradients

Linear gradients in CSS are backgrounds created with a smooth transition between two or more colors. - **Usage**: To set a gradient as the background of an element - **Example**:
`css
      body {
        background: linear-gradient(red, yellow);
      }
      `

## 🔄 Normalizing CSS

Normalizing CSS means making the default rendering of all elements consistent across all browsers. This is typically done with a CSS file called a CSS Reset or a CSS Normalize. - **Usage**: To start with a clean slate in styling your web page, without any default styles provided by the browser - **Example**:
`css
      html, body, div, span, applet, object, iframe,
      h1, h2, h3, h4, h5, h6, p, blockquote, pre,
      a, abbr, acronym, address, big, cite, code,
      del, dfn, em, img, ins, kbd, q, s, samp,
      small, strike, strong, sub, sup, tt, var,
      b, u, i, center,
      dl, dt, dd, ol, ul, li,
      fieldset, form, label, legend,
      table, caption, tbody, tfoot, thead, tr, th, td,
      article, aside, canvas, details, embed, 
      figure, figcaption, footer, header, hgroup, 
      menu, nav, output, ruby, section, summary,
      time, mark, audio, video {
          margin: 0;
          padding: 0;
          border: 0;
          font-size: 100%;
          font: inherit;
          vertical-align: baseline;
      }
      /* HTML5 display-role reset for older browsers */
      article, aside, details, figcaption, figure, 
      footer, header, hgroup, menu, nav, section {
          display: block;
      }
      body {
          line-height: 1;
      }
      ol, ul {
          list-style: none;
      }
      blockquote, q {
          quotes: none;
      }
      blockquote:before, blockquote:after,
      q:before, q:after {
          content: '';
          content: none;
      }
      table {
          border-collapse: collapse;
          border-spacing: 0;
      }
      `

## 👤 Pseudo-class selectors

Pseudo-class selectors are keywords added to selectors that specify a special state of the selected element. For instance, `:hover` can be used to change a button's color when the user's pointer hovers over it. - **Usage**: To style an element when it's in a specific state - **Example**:
`css
      button:hover {
        background-color: blue;
      }
      `

## 🧩 Pseudo-element selectors

Pseudo-element selectors are keywords added to selectors that let you style a specific part of the selected element(s). For example, `::first-letter` can be used to style the first letter of a paragraph. - **Usage**: To style a specific part of an element - **Example**:
`css
      p::first-letter {
        color: blue;
        font-size: xx-large;
      }
      `

## ⭕ Radial gradients

Radial gradients in CSS are backgrounds created with a smooth transition between two or more colors that radiates from an origin. The color stops are placed along a radial line. - **Usage**: To set a radial gradient as the background of an element - **Example**:
`css
      body {
        background: radial-gradient(circle, red, yellow);
      }
      `

## 👫 Relational selectors

Relational selectors (combinators) are patterns that match based on a specific relationship between two elements. - **Usage**: To select an element based on its relationship with another element - **Example**:
`css
      div > p {
        color: blue;
      }
      `
This example selects all `<p>` elements that are direct children of `<div>` elements.

## 🎨 RGB colors

RGB colors are defined by specifying the level of red (R), green (G) and blue (B) with an integer between 0 and 255, or as a percentage. - **Usage**: To set color in CSS using RGB values - **Example**:
`css
      body {
        background-color: rgb(255, 0, 0);
      }
      `

## 🔍 Selectors

Selectors are the part of CSS rules that describe to which elements the styling should be applied. - **Usage**: To target elements on which to apply styles - **Example**:
`css
      p {
        color: red;
      }
      `
This example selects all `<p>` elements.

## 🏋️ Selectors specificity

Selectors specificity is the set of rules applied by CSS to determine which styles are most relevant to an element and, therefore, will be applied. It is based on the matching rules which are composed of different sorts of CSS selectors. - **Usage**: To control which styles are applied when there are multiple competing styles - **Example**:
`css
      #id1 {color: red;} /* ID selector, specificity is 1,0,0 */
      .class1 {color: green;} /* Class selector, specificity is 0,1,0 */
      p {color: blue;} /* Type selector, specificity is 0,0,1 */
      `
Here, color red will be applied if these selectors are targeting the same element.

## 🏞️ Separation of concerns

Separation of concerns in CSS means that CSS should only be used for styling, and not for defining the structure of the content (that's what HTML is for) or for controlling how the content behaves (that's what JavaScript is for). - **Usage**: To write maintainable and understandable code - **Example**: Using external CSS file (styles.css) linked in HTML
`html
      <link rel="stylesheet" href="styles.css">
      `

I hope you find these explanations helpful. If you have any questions, feel free to open an issue or submit a pull request. And if you like this project, please consider giving it a star! ⭐ For more educational content, you can visit my [website](#).

## 📘 Summary of CSS Basics

1. 📁 **Embedded, External, and Inline Styles**

   - **Definition**: CSS styles can be embedded in an HTML document, written in a separate file (as an external stylesheet), or written inline in an HTML element using the `style` attribute.
   - **Usage**: Inline styles overwrite embedded styles which in turn overwrite external styles. External stylesheets provide the best separation of HTML and CSS code and result in more maintainable code. Plus, an external stylesheet can be used in many HTML documents.
   - **Example**:

   ```css
   /* External CSS */
   p {
       color: blue;
   }

   <!-- Embedded CSS -->
   <style>
   p {
       color: green;
   }
   </style>

   <!-- Inline CSS -->
   <p style="color: red;">This is a paragraph.</p>
   ```

2. 🎯 **Selectors**

   - **Definition**: We can select elements by their type, class, attribute, or ID.
   - **Usage**: Class and attribute selectors are less specific because we can have many elements with the same class and/or attributes. Element selectors are the least specific selectors.
   - **Example**:

   ```css
   p /* type selector */ {
     color: blue;
   }

   .highlight /* class selector */ {
     background-color: yellow;
   }

   #header /* id selector */ {
     font-size: 24px;
   }

   a[href="https://example.com"] /* attribute selector */
   {
     text-decoration: none;
   }
   ```

3. 🏷️ **Pseudo-classes and Pseudo-elements**

   - **Definition**: We can use pseudo-classes to target elements without the need to give them a specific class. Pseudo-elements allow us to style a part of an element.
   - **Usage**: The most common pseudo-classes are `:first-child`, `:last-child`, and `:nth-child()`. Pseudo-classes start with a single colon. The most common pseudo-elements are `::first-letter`, `::first-line`, `::before`, and `::after`. Pseudo-elements start with double colons.
   - **Example**:

   ```css
   p:first-child {
     color: blue;
   }

   p::first-letter {
     font-size: 200%;
   }
   ```

4. 🎨 **Colors**

   - **Definition**: We can specify colors by their name, hexadecimal value, RGB/RGBA value, or HSL/HSLA value.
   - **Usage**: RGBA and HSLA values include an alpha channel used for transparency. The value for the alpha channel is a decimal point number between 0 (completely transparent) and 1 (completely opaque).
   - **Example**:

   ```css
   p {
     color: #ff0000; /* hexadecimal */
     background-color: rgb(0, 255, 0); /* RGB */
     border-color: rgba(0, 0, 255, 0.5); /* RGBA */
   }
   ```

5. 🌈 **Gradients**

   - **Definition**: Using the `linear-gradient()` and `radial-gradient()` functions we can create gradients in CSS.
   - **Usage**: Gradients are images so they cannot be used as the value of `background-color` property. We can use them as the value of `background-image` or `background` properties.
   - **Example**:

   ```css
   div {
     background: linear-gradient(red, yellow, blue);
   }
   ```

6. 🖼️ **Borders**

   - **Definition**: The `border` property is a shorthand property for `border-top`, `border-right`, `border-bottom`, and `border-left`. It takes three values: the thickness of the border, its style, and its color.
   - **Usage**: We also have specific properties like `border-width`, `border-style`, and `border-color`. These properties take four values for the top, right, bottom, and left borders.
   - **Example**:

   ```css
   div {
     border: 1px solid black;
     border-radius: 5px;
   }
   ```

7. 🌑 **Shadows**

   - **Definition**: Using the `box-shadow` and `text-shadow` properties we can apply a shadow to elements and text.
   - **Usage**: These properties take a few values. The first two values determine the horizontal and vertical distance of the shadow from the element. The third value (called blur radius) determines the softness of the border. We can specify the color as the fourth value.
   - **Example**:

   ```css
   div {
     box-shadow: 10px 5px 5px black;
   }

   p {
     text-shadow: 2px 2px 2px gray;
   }
   ```

Don't hesitate to star ⭐ this repository if you find it helpful and share it with others. Contributions and feedback are always welcome. Visit my [website](#) for more resources.

## 📜 CSS Cheat Sheet

This cheat sheet provides you with a quick reference to essential CSS syntax.

### 🔬 Basic Selectors

These are the foundational selectors to target elements on a webpage.

- `article`

  - **Usage**: Selects all `<article>` elements
  - **Example**:
    ```css
    article {
      font-size: 20px;
    }
    ```

- `.product`

  - **Usage**: Selects all elements with `class="product"`
  - **Example**:
    ```css
    .product {
      background-color: lightblue;
    }
    ```

- `#products`
  - **Usage**: Selects the element with `id="products"`
  - **Example**:
    ```css
    #products {
      border: 1px solid black;
    }
    ```

### 📌 Relational Selectors

These selectors target elements based on their relationships in the HTML document.

- `#products > p`
  - **Usage**: Selects all `<p>` elements that are direct children of an element with `id="products"`
  - **Example**:
    ```css
    #products > p {
      color: blue;
    }
    ```

### 🎭 Pseudo-class Selectors

These selectors target elements that are in a certain state, like being hovered over or being the first child of a parent.

- `article :first-child`
  - **Usage**: Selects the first child element of every `<article>` element
  - **Example**:
    ```css
    article :first-child {
      font-weight: bold;
    }
    ```

### 🌈 Colors

Different ways to specify colors in CSS

- `rgb(252, 186, 3)`
  - **Usage**: Specifies a color in the RGB color model
  - **Example**:
    ```css
    body {
      background-color: rgb(252, 186, 3);
    }
    ```

### 🎢 Gradients

Create smooth transitions between multiple specified colors

- `background: linear-gradient(blue, yellow);`
  - **Usage**: Sets a linear gradient as the background image
  - **Example**:
    ```css
    body {
      background: linear-gradient(blue, yellow);
    }
    ```

### 🖼️ Borders

Control the border that goes around elements

- `border: 10px solid blue;`
  - **Usage**: Sets the border style
  - **Example**:
    ```css
    p {
      border: 10px solid blue;
    }
    ```

### 🌑 Shadows

Adds shadows effects to elements

- `box-shadow: 10px 10px grey;`
  - **Usage**: Applies a shadow effect to the box of an element
  - **Example**:
    ```css
    p {
      box-shadow: 10px 10px grey;
    }
    ```

Once again, if you have any questions, suggestions, or spot any mistakes, please feel free to open an issue or submit a pull request. Your contributions are always welcome. And don't forget to star ⭐ this repository if you find it useful. For more resources, visit my [website](#).
