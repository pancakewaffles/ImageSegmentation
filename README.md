# ImageSegmentation
Image segmentation using scikit-image

Image segmentation is an important step in recognising entities in images.

Supervised Segmentation: Where we help the algorithm by providing some information about the entity. Includes Thresholding, Active Contour ("Snakes"), Random Walker.

Unsupervised Segmentation: Where we do not provide the algorithm with any information and let them figure it out. Often used for processing large images that contain millions of pixels. The idea is to reduce the number of pixels by working with sub-regions of pixels that are representative of the whole image. Includes Thresholding with filters, Simple Linear Interative Clustering, Felzenszwalb.
