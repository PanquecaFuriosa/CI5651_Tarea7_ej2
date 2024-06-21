# Onions with Convex Hull

## Problem:

Let $`P = {p1, p2, · · · , pn}`$ be a set of points in the Cartesian plane. We define a layer as those points that are part of the smallest convex polygon that surrounds all the points in $`P`$. But points are like ogres or onions and can have more than one layer. In particular, we can remove the layer for $`P`$ and obtain a set of points $`P_0`$ whose layer can also be calculated. How many layers does the point set $`P`$ have?
Design an algorithm that can answer this query using $`O(n^{2} log(n))`$ time and O(n) memory.
