# Tags and Attributes
## Tags
HTML tags are used to define the structure and content of a web page. They are enclosed in angle brackets (< and >) and can be either opening tags, closing tags, or self-closing tags. Here are some commonly used HTML tags:

- `<html>`: This is the root element of an HTML document.

- `<head>`: This element contains meta-information about the HTML document, such as the title, stylesheets, scripts, and more.

- `<title>`: This element sets the title of the HTML document, which is displayed in the browser's title bar or tab.

- `<body>`: This element represents the content of the HTML document that is visible on the web page.

- `<h1>` to `<h6>`: These are heading tags used to define different levels of headings. `<h1>` is the highest level, and `<h6>` is the lowest level.

- `<p>`: This tag represents a paragraph of text.

- `<a>`: This tag is used to create links to other web pages or resources. The `href` attribute specifies the URL of the linked page.

- `<img>`: This tag is used to insert an image into the web page. The `src` attribute specifies the path to the image file, and the `alt` attribute provides alternative text for the image.

- `<ul>`: This tag represents an unordered list, typically displayed as a bulleted list. It contains one or more `<li>` (list item) tags.

- `<ol>`: This tag represents an ordered list, typically displayed as a numbered list. It also contains one or more `<li>` tags.

- `<li>`: This tag represents a list item within an ordered or unordered list.

- `<div>`: This tag is a generic container used to group elements together or create sections on the web page.

- `<span>`: This tag is used to apply styles or manipulate inline elements. It is often used in conjunction with CSS or JavaScript.

These are just a few examples of HTML tags. There are many more tags available for different purposes, such as form elements, tables, semantic elements, and more. Each tag serves a specific function and helps structure and format the content of a web page.

## Attributes
HTML attributes provide additional information or modify the behavior of HTML elements. They are added to the opening tags of HTML elements and are specified using the attribute name followed by an equals sign (=) and the attribute value, enclosed in quotation marks. Here are some commonly used HTML attributes:

- `class`: This attribute specifies one or more CSS classes to apply to an element. Multiple classes can be separated by spaces.

- `id`: This attribute provides a unique identifier for an element. It must be unique within the HTML document.

- `style`: This attribute allows you to apply inline CSS styles directly to an element. The value is a set of CSS property-value pairs.

- `src`: This attribute is used with elements like `<img>` or `<script>` to specify the source URL of an image or a script file.

- `href`: This attribute is used with the `<a>` (anchor) tag to specify the destination URL that the link should point to.

- `alt`: This attribute is used with the `<img>` tag to provide alternative text for the image. It is displayed if the image fails to load or for accessibility purposes.

- `width` and `height`: These attributes specify the width and height dimensions of an element, such as an image or a table cell.

- `disabled`: This attribute is used with form elements (e.g., `<input>`, `<button>`) to disable user interaction with the element.

- `placeholder`: This attribute is used with form input fields to provide a hint or example value that disappears when the user starts typing.

- `required`: This attribute is used with form input fields to make them required, preventing form submission if the field is empty.

- `target`: This attribute is used with the `<a>` tag to specify where the linked content should be displayed, such as in a new tab or in a specific frame.

These are just a few examples of HTML attributes. Different elements have different attributes available based on their purpose and functionality. HTML attributes help control the appearance, behavior, and interaction of HTML elements within a web page.

## Example
Here's an example that demonstrates the usage of HTML tags and attributes:

```html
<!DOCTYPE html>
<html>
<head>
  <title>HTML Tags and Attributes Example</title>
</head>
<body>
  <h1>Welcome to my Web Page!</h1>
  
  <p>This is a paragraph of text.</p>
  
  <img src="image.jpg" alt="Image Description" width="300" height="200">
  
  <a href="https://www.example.com" target="_blank">Visit Example.com</a>
  
  <ul>
    <li>Apple</li>
    <li>Orange</li>
    <li>Banana</li>
  </ul>
  
  <form>
    <input type="text" name="name" placeholder="Enter your name" required>
    <input type="email" name="email" placeholder="Enter your email" required>
    <button type="submit" disabled>Submit</button>
  </form>
</body>
</html>
```

In this example:

- The `<h1>` tag represents the main heading of the page.
- The `<p>` tag defines a paragraph of text.
- The `<img>` tag displays an image with the specified source, alternate text, width, and height.
- The `<a>` tag creates a link to Example.com with the specified URL and opens in a new tab using the `target="_blank"` attribute.
- The `<ul>` tag represents an unordered list, and each list item is defined using the `<li>` tag.
- The `<form>` tag creates a form, and the `<input>` tags define text input fields with the specified attributes, such as `name`, `placeholder`, and `required`.
- The `<button>` tag creates a submit button, and the `disabled` attribute is used to disable it.
