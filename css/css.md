# CSS

### Box Model

* **Content** - The content of the box, where text and images appear
* **Padding** - Clears an area around the content. The padding is transparent
* **Border** - A border that goes around the padding and content
* **Margin** - Clears an area outside the border. The margin is transparent

![](../.gitbook/assets/wei-xin-jie-tu-20210625104217.png)

### Positioning: static, relative, absolute, and fixed

|  | static | relative | absolute |
| :--- | :--- | :--- | :--- |
|  | default | relative to myself | complete control over where an element is positioned |
|  |  |  | it will not take up space on the page. It acts its above the page.  |
| where it actually is |  | top: 10px -&gt; tag will be moved down 10px from **where it normally appear** | coordiantes relative to their **nearest ancestor element** that is not statistically positioned. So the anscestor needs to be _position: relative_ |
|  |  | top, right, left, down | top, right, left, down |
|  |  |  |  |

### Floating: seprate from position, never together at the same time

It helps building layouts, it allows us to align elements horizontally.

Caution: if a parent element contains only floated child elements, it has zero height. 

```text
/* Additional CSS */
section:after {
  content: ""; /* Empty content string */
  display: block; /* Only block elements can clear */
  clear: both;
}
```

### ::

