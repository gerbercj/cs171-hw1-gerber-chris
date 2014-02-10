# 1. The domain() function is the data range upon which the scale is calculated. What does d3.selectAll("tbody tr")[0].length-1 mean?

This creates an array of all the table rows inside the table body, determines its length, and then subtracts 1 to determine the zero-based index of the last row.

# 2. Add the snippet in your code. Describe, in words, what the following function calls return: color(0), color(10) and color(150)?

The function calls return an interpolated color between orange and silver. The first two are very orange, and the second, as it is outside the range, is actually very teal.

# 3. If the array passed to domain() was the minimum and maximum rate values, how would that change the scale? In what situations would this be appropriate?

That would cause the individual rate values to determine the color, between orange and silver, which would be assigned. Interestingly, colors are not typically useful for quantitative data. A monochromatic scale can be useful for grouping, or when length and size have already been used to represent other variables. Color can also be useful for quantitative data when values are sufficiently different to cause contrast.

