# [A Novel algorithm for Planar Extracting of 3D Point Clouds](http://dl.acm.org/citation.cfm?id=3007746) [4]

> Xin Liu, Xiangwei Zhang, Siyuan Cheng, and Thach B. Nguyen

**A different approuch to getting plane in point clouds**

The three main steps to getting a plane is outlier removal, clustering for segmentation, then RANSAC to extract the plane. The only part they tried to tackle was using a self-organizing fuzzy K-means instead of the typical Fuzzy C-means(FCM). No data to if it's faster, more accurate, etc., just that this concept is another valid choice for doing this task.
