

Add columns to the right of the table in each sheet and conduct monthly frequency analysis on both vegetables and fruits using:

Mode
Median
Mean
Range





=MODE.SNGL(value1, [value2, ...])
=MODE.MULT(value1, [value2, ...])

MODE.SNGL does the same as MODE and returns only one value (picking the first it finds).

MODE.MULT returns multiple values if there are more than one that is the most common.

Find the mode using this formula:
=MODE(C2:N2)

Find the median using this formula:
=MEDIAN(C2:N2)

Find the mean using this formula:
=AVERAGE(C2:N2)

Find the range using this formula:
=(MAX(C2:N2) - MIN(C2:N2))
=ROUND(MAX(C2:N2) - MIN(C2:N2))








