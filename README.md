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
