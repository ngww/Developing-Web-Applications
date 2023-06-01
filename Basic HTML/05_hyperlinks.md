# Hyperlinks
Hyperlinks, also known as links, are an essential element in HTML for creating connections between different web pages or resources. They allow users to navigate between pages or access external content. In HTML, hyperlinks are created using the `<a>` (anchor) tag and the `href` attribute to specify the target URL. Here's an example of how to create a hyperlink:

```html
<a href="https://www.example.com">Visit Example.com</a>
```

In this example, the text "Visit Example.com" is the visible link text that the user sees on the webpage. The `href` attribute specifies the URL of the target page or resource. When the user clicks on the link, the browser navigates to the specified URL.

You can also create internal links within the same webpage by using anchor tags with a `href` attribute that points to an element's `id` attribute. For example:

```html
<a href="#section1">Jump to Section 1</a>

<h2 id="section1">Section 1</h2>
<p>This is the content of Section 1.</p>
```

In this case, the link "Jump to Section 1" will scroll the page to the section with the `id="section1"` attribute, allowing users to navigate within the same page.

Additionally, you can use the `target` attribute to specify how the link should be opened. For example, to open the link in a new tab or window, you can use `target="_blank"`:

```html
<a href="https://www.example.com" target="_blank">Visit Example.com</a>
```

This attribute value tells the browser to open the link in a new tab or window.

Hyperlinks are a fundamental component of web navigation and allow users to explore different web pages and resources.

## Named Anchors
Named anchors, also known as anchor targets or fragment identifiers, are used to create links within the same webpage to specific sections or elements. They allow users to navigate directly to a specific location on a page without having to scroll manually. Named anchors are created using the `id` attribute on the target element and the `href` attribute of the anchor tag.

Here's an example of how to create a named anchor and link to it within the same page:

```html
<h2 id="section1">Section 1</h2>
<p>This is the content of Section 1.</p>

<p><a href="#section1">Go to Section 1</a></p>
```

In this example, the `<h2>` tag with the `id="section1"` attribute creates a named anchor at the beginning of the "Section 1" content. The anchor tag `<a>` with the `href="#section1"` attribute is used to link back to the named anchor. When the user clicks on the "Go to Section 1" link, the page will scroll to the corresponding section.

Named anchors can be used to create a table of contents or provide quick navigation within a long webpage. You can create multiple named anchors and link to them from different parts of the page.

Note that the value of the `id` attribute should be unique within the HTML document. Ensure that each named anchor has a unique `id` value to avoid conflicts.

Named anchors are a useful feature to enhance navigation and user experience within a webpage, allowing users to jump directly to specific sections of content.

## Absolute and Relative URLs and Hyperlink Targeting
Absolute and relative URLs are two different ways to specify the target of a hyperlink in HTML.

1. Absolute URLs: An absolute URL provides the complete address of a resource, including the protocol (such as "http://" or "https://"), domain name, and path. Absolute URLs point to a specific location on the internet. Here's an example:

```html
<a href="https://www.example.com">Visit Example.com</a>
```

In this example, the absolute URL "https://www.example.com" is used as the value of the `href` attribute. Clicking on the link will take the user to the specified URL.

2. Relative URLs: A relative URL specifies the location of a resource relative to the current page or the current folder structure. It doesn't include the protocol or domain name, but only the path to the resource. Relative URLs are useful when linking within the same website or when the target resource is located on the same server. Here are some examples:

```html
<a href="about.html">About</a>
<a href="images/picture.jpg">View Picture</a>
```

In the first example, the relative URL "about.html" points to a page named "about.html" in the same directory as the current page. In the second example, the relative URL "images/picture.jpg" points to an image named "picture.jpg" located within a subfolder called "images" relative to the current page.

Hyperlink Targeting:
When creating a hyperlink, you can specify the target window or frame where the linked content should be opened. The `target` attribute is used for this purpose. Common target values include:

- `_blank`: Opens the linked content in a new tab or window.
- `_self`: Opens the linked content in the same tab or window (default behavior).
- `_parent`: Opens the linked content in the parent frame or window, if applicable.
- `_top`: Opens the linked content in the top-level frame or window, replacing any framesets if applicable.
- `<framename>`: Opens the linked content in the specified frame, if applicable.

Here's an example of using the `target` attribute:

```html
<a href="https://www.example.com" target="_blank">Visit Example.com</a>
```

In this example, the `target="_blank"` attribute opens the linked content in a new tab or window.

Understanding and correctly using absolute and relative URLs, as well as specifying the target of hyperlinks, is important for linking to resources effectively within your web pages.

## Mailto Links
Mailto links are a special type of hyperlink in HTML that allow users to compose and send emails by clicking on the link. When a user clicks on a mailto link, it automatically opens their default email client or webmail service with a new email message pre-populated with the specified recipient, subject, and body.

To create a mailto link, you use the `<a>` tag with the `href` attribute set to the email address you want to send the email to. Here's an example:

```html
<a href="mailto:example@example.com">Send Email</a>
```

In this example, the mailto link is created with the email address "example@example.com". When the user clicks on the "Send Email" link, it will open their default email client or webmail service with a new email message addressed to "example@example.com".

You can also include additional information in the mailto link, such as the subject and body of the email. Here's an example with subject and body:

```html
<a href="mailto:example@example.com?subject=Hello&body=I wanted to say hi!">Send Email</a>
```

In this example, the mailto link includes a subject "Hello" and a body "I wanted to say hi!". When the user clicks on the link, the email client will open with the recipient, subject, and body pre-filled.

Mailto links provide a convenient way for users to send emails directly from your web page. However, it's important to note that the behavior of mailto links depends on the user's system and email client configuration. If a user does not have an email client configured, or if they are accessing the web page from a device that doesn't support email functionality, the mailto link may not work as expected.