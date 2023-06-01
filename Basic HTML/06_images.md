# Images
To display images on a web page, you can use the `<img>` tag in HTML. The `<img>` tag is a self-closing tag and requires the `src` attribute to specify the source (URL or file path) of the image. Here's an example:

```html
<img src="image.jpg" alt="Description of the image">
```

In this example, the `src` attribute specifies the path to the image file, such as "image.jpg". The `alt` attribute provides alternative text that describes the image. The `alt` attribute is important for accessibility and is displayed when the image cannot be loaded or for users who rely on screen readers.

You can also specify additional attributes to customize the display of the image, such as the width and height:

```html
<img src="image.jpg" alt="Description of the image" width="400" height="300">
```

In this example, the `width` and `height` attributes define the dimensions of the image in pixels. It's recommended to specify the dimensions to ensure proper spacing and layout while the image is being loaded.

Additionally, you can use the `title` attribute to provide a tooltip text that appears when the user hovers over the image:

```html
<img src="image.jpg" alt="Description of the image" title="Image Title">
```

Make sure to replace "image.jpg" with the actual path or URL of your image file. The image file should be accessible from the location where the HTML file is located or provide the full URL if the image is hosted on a different server.

Remember to optimize your images for web display by resizing and compressing them appropriately. This helps reduce file sizes, improve page load times, and enhance the overall user experience.

## Image File Formats, Inline Imaged and Hyperlinked Images
Image File Formats:
There are several common image file formats used on the web. Here are some of the most popular ones:

1. JPEG (Joint Photographic Experts Group): JPEG is a commonly used image format for photographs and complex images. It uses lossy compression, which reduces file size but may result in a slight loss of image quality. JPEG images can support millions of colors and are widely supported across different browsers and devices.

2. PNG (Portable Network Graphics): PNG is a widely used image format that supports lossless compression. It is suitable for images with transparency or sharp edges, such as logos or graphics. PNG images can support millions of colors and offer excellent image quality, but they tend to have larger file sizes compared to JPEG.

3. GIF (Graphics Interchange Format): GIF is a format commonly used for simple animations and images with limited color palettes. It uses lossless compression and supports transparency. GIF images are limited to 256 colors and are often used for small icons, animated images, and graphics with solid colors.

4. SVG (Scalable Vector Graphics): SVG is a vector-based image format that uses XML markup to define shapes, lines, and curves. SVG images are resolution-independent and can be scaled without loss of quality. They are well-suited for logos, icons, and graphics that require scalability and interactivity.

Inline Images:
Inline images are inserted directly within the HTML document using the `<img>` tag. The `<img>` tag is a self-closing tag and requires the `src` attribute to specify the source (URL or file path) of the image. Here's an example:

```html
<img src="image.jpg" alt="Description of the image">
```

In this example, the `src` attribute specifies the path to the image file, and the `alt` attribute provides alternative text that describes the image. The `alt` attribute is important for accessibility and is displayed when the image cannot be loaded or for users who rely on screen readers.

Hyperlinked Images:
To create a hyperlinked image, you can wrap an `<img>` tag with an `<a>` tag. Here's an example:

```html
<a href="https://www.example.com">
  <img src="image.jpg" alt="Description of the image">
</a>
```

In this example, the `<a>` tag specifies the target URL, and the `<img>` tag is nested within it. When the user clicks on the image, it will act as a hyperlink and navigate to the specified URL.

Hyperlinked images are commonly used for clickable banners, buttons, or navigation elements.

When using images on your web page, consider optimizing them for web display by resizing and compressing them appropriately. This helps reduce file sizes, improve page load times, and enhance the overall user experience.

## Image Height and Width, and Thumbnails
When displaying images on a web page, you can control the height and width of the image using the `height` and `width` attributes in the `<img>` tag. Here's how you can specify the dimensions:

```html
<img src="image.jpg" alt="Description of the image" width="400" height="300">
```

In this example, the `width` attribute is set to 400 pixels, and the `height` attribute is set to 300 pixels. These values determine the displayed dimensions of the image on the page.

It's important to note that specifying the exact dimensions can impact the aspect ratio and distort the image if the original proportions are not maintained. To preserve the aspect ratio while resizing an image, you can specify only one dimension (either width or height) and let the other dimension scale proportionally. For example:

```html
<img src="image.jpg" alt="Description of the image" width="400">
```

In this case, the `width` is set to 400 pixels, and the height is automatically adjusted to maintain the image's original aspect ratio.

Thumbnails are smaller versions of images that provide a preview or summary of the full-sized image. They are commonly used in galleries, image grids, or when displaying multiple images on a page. To create a thumbnail, you can create a smaller version of the image and adjust the dimensions accordingly. Here's an example:

```html
<a href="large_image.jpg">
  <img src="thumbnail.jpg" alt="Description of the image" width="100" height="100">
</a>
```

In this example, the `<img>` tag represents the thumbnail image with dimensions set to 100 pixels by 100 pixels. The `href` attribute of the surrounding `<a>` tag points to the full-sized image file (e.g., "large_image.jpg"). When the user clicks on the thumbnail, they are directed to the larger image.

By using thumbnails, you can optimize the loading time of your page and provide a compact representation of the images that users can click on to view the full version.