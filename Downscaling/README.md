## Dowscaling Methodology

In this repository, we explore how we can utilize deep-learning techniques to improve the resolution of satellite images. Residual Dense Network is used as it has the best performance when compared against other conventional methods like linear interpolation or nearest neighbour clustering.

# Why coventional methods are insufficient?

Conventional methods tries to establish a simple mathematical relationship between points and attempts to interpolate the data. Often time, this leads to the deletion or inability of the interpolation method to capture extreme data points. An example is shown below where the interpolation methods fail to capture the extreme points. This is especially problematic when these extreme points are our points of interest.

![image](https://github.com/user-attachments/assets/b818141b-965e-413a-b2cf-a723c1f59919)

# Training methodology

![image](https://github.com/user-attachments/assets/bc57ee6b-470f-45d9-b4eb-53570b81736e)

# Model Architecture

![image](https://github.com/user-attachments/assets/6d4a265b-4de4-4d99-9e84-3ff50a02ae11)


# Reference
1) https://sh-tsang.medium.com/review-rdn-residual-dense-network-super-resolution-9738b8ce51e2
