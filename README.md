# image
$r_1$ and $r_2$ are two lines in the original image, each of which intersects with three lanes. 
This set is referred to as a "lane pixel set". 
For the same pair of lanes, the variation rule of distance between them, such as $d_1$ and $d_2$, 
is difficult to be captured by conventional means, so it needs to be fitted by neural network.
In addition, it can be seen that in the same row, the distance($d_1$ and $d_3$) between lane pixel sets of different lanes is very long,
which means that the general convolution is insufficient to capture all lane pixel sets in a row.
Therefore, we use transformer because it can capture contextual information effectively.
