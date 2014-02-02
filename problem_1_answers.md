# 1. What does the colspan="3" attribute of the <th> node do?

Using `colspan="3"` causes three horizontally adjacent cells to be treated as one large cell for features such as line wrapping.

# 2. List all the styles (e.g. border width, text alignment, etc.) applied to the th element containing "Rank". For each, state whether they are set as an HTML attribute or a CSS style and describe them in a few words. Include only styles directly applied to the element, not styles inherited/cascading from parent elements or styles from the default user agent stylesheet. Exclude overwritten styles. For HTML attributes, state the CSS equivalent.

Almost all of the styles are inherited. The only two that are explicitly related to `th` elements, or this specific element are:

`padding: 3px;` - Applied by CSS. This specifies the extra space, in pixels, around the content, inside the border.

`text-align: -webkit-center;` - This CSS comes from the HTML attribute `align="center"`, which is applied to the `th` tag. It specifies that the text should be centered horizontally within the cell.

# 3. What differences do you notice between the DOM inspector and the HTML source? Why would you use the DOM inspector? Why is the HTML source useful?

The HTML source only shows us a subset of the attributes being applied, whereas the DOM inspector shows us the results of interpreting all of the included files, as well as the styles being applied by the browser itself. This makes the DOM inspector more useful for seeing the resulting state of the world. The HTML source, on the other hand, shows a much cleaner picture where only specific attributes are being set. In addition, the HTML source can show us the original state of the DOM, before it is altered by Javascript code.

