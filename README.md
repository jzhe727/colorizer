# colorizer
This project was written by John Zheng, Deliar Mohammadi, and Xinzhou Li. It primarily reproduces the results of *Image Colorization Algorithm Based on Deep Learning*, by Na Wang, Guo-Dong Chen, and Ying Tian, which can be found at https://www.mdpi.com/2073-8994/14/11/2295

This is an image colorizer, which takes a black-and-white image and adds color to it. It uses the above architecture, CU-net, which is based on the standard U-net architecture with several max-pool layers replaced with dilated convolution.

### Example

Original (left) and model output (right) when given a black-and-white version of the image.

![Sample image](assets/sample.png?raw=true)

Original image taken from dataset at https://www.kaggle.com/datasets/ashwingupta3012/human-faces.

## Links

These links below can be used to find more information about the project.

The [demo notebook](https://github.com/jzhe727/colorizer/blob/main/demo.ipynb) can be found here, or run the notebook yourself on [Google Colab](https://colab.research.google.com/github/jzhe727/colorizer/blob/main/demo.ipynb).

The [final paper](https://github.com/jzhe727/colorizer/blob/main/docs/Colorization.pdf) and [poster](https://github.com/jzhe727/colorizer/blob/main/docs/colorization_poster.drawio.pdf) can also be found in this repository.



