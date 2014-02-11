# 1. What's missing? Is this bar chart usable in its current form?

This chart is not usable, as there is no way to interpret the data. There needs to be some sort of labels on the bars, and some way to determine the scale applied to the length of the bars.

# 2. What is the role of each of the three nested levels of g elements? (keep in mind you'll be adding a title to the chart)

The first level specifies the position of the chart, including it's labels, on the page. The second level sets the size of the container for the bars, and the third level is used to contain each of the individual bars.

# 3. Complete the implementation section below. Is there any consequence if you add the text elements before or after the rect elements? Why?

The order that the elements are created affects their z-order. Subsequent elements are painted on top of existing elements, so the labels should be created last if they need to appear on top.

