### HTML & CSS Box Model

The **CSS box model** is a fundamental concept that defines how elements are structured and rendered on a web page. It consists of four key components:

1. **Content**: The actual content of the box, such as text or an image. It occupies the inner-most area of the element.

2. **Padding**: Space between the content and the border. Padding is transparent and increases the clickable or visible area without affecting the content.

3. **Border**: A visible or invisible line surrounding the padding and content. Its style, width, and color can be customized.

4. **Margin**: The outermost space that separates the element from other elements. Margins are also transparent and help in positioning elements on the page.

---

### Visual Representation

```
+-------------------------+ <- Margin (transparent)
|  +-------------------+  | <- Border
|  |   Padding         |  | <- Padding (transparent)
|  |  +------------+   |  | <- Content
|  |  |            |   |  |
|  |  +------------+   |  |
|  +-------------------+  |
+-------------------------+
```

---

### Key Notes:
- The total size of an element is calculated as:
  ```
  Total Width = Content Width + Padding + Border + Margin
  Total Height = Content Height + Padding + Border + Margin
  ```
- The `box-sizing` property can alter the box model behavior:
  - `content-box` (default): Padding and border are *not* included in the content's width and height.
  - `border-box`: Padding and border are included in the content's width and height, making layout calculations easier.

Author - Riya Vishwakarma
Contact for Webdevelopment Projects - riyavishwa2411@gmail.com
