# ssim_optimize

Implementation of algorithm to find highest SSIM image on the l2 ball of original image from "Image Quality Assessment: From Error Visibility to
Structural Similarity" (Zhou Wang, Alan C. Bovik)

In the original paper, the algorithm is written as:

![equation](/images/eq_12.png)

In the implementation above, the first step is rewritten for efficiency:

![equation](/images/eq_new.png)

This reduces space used in memory from O(n^2) to O(n)