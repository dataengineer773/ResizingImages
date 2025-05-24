We want to resize an image for further preprocessing, Use resize to change the size of an image, Resizing images is a common task in image preprocessing for two reasons. First, images come in all
shapes and sizes, and to be usable as features, images must have the same dimensions. This
standardization of image size does come with costs, however; images are matrices of information and
when we reduce the size of the image we are reducing the size of that matrix and the information it
contains. Second, machine learning can require thousands or hundreds of thousands of images. When
those images are very large they can take up a lot of memory, and by resizing them we can dramatically
reduce memory usage. Some common image sizes for machine learning are 32 × 32, 64 × 64, 96 × 96,
and 256 × 256. In essence, the method we choose for image resizing will often be a tradeoff between the
stastical performance of our model and computational cost to train it. The Pillow library offers many
different options for resizing images for this reason.
