# ssim_optimize

Implementation of algorithm to find highest SSIM image on the l2 ball of original image from "Image Quality Assessment: From Error Visibility to
Structural Similarity" (Zhou Wang, Alan C. Bovik)

In the original paper, the algorithm is written as:

![equation](/images/eq_12.png)

I have rewritten the first step for computational efficiency purposes as:

![equation](/images/eq_1.png)

This reduces space used in memory from O(n^2) to O(n)