# ssim_optimize

Implementation of algorithm to find highest SSIM image within the L2 ball from [Image Quality Assessment: From Error Visibility to
Structural Similarity](https://www.cns.nyu.edu/pub/lcv/wang03-preprint.pdf)

In the original paper, the algorithm is written as:

![equation](/images/eq_12.png)

The implementation here rewrites this as the equivalent

![equation](/images/eq_new.png)

in order to reduce memory complexity from quadratic to linear
