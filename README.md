# Image-Segmentation
Description:  
Image segmentation using K-means clustering algorithm. The dataset used was Berkeley Segmentation Benchmark (BSDS500).

Approach:  


k-means algorithm was used to segment the images with different K values.  
The results were compared to several ground truth segmentation in the dataset F-measure and Conditional Entropy were the metrics used to compare the results.   
Then the segmentations were compared to the results of applying Normalized-cut algorithm on the images.  
Results were compared with a Spectral knn model and a spatial model.
