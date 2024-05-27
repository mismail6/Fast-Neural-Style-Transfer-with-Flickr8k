Reference code: https://github.com/jcjohnson/fast-neural-style

Dataset: https://www.kaggle.com/datasets/adityajn105/flickr8k

This project implements a Fast Neural Style Transfer to the Flickr8k dataset using different style images. How it works is that it trains to apply a specific image style to the entire dataset.
Then the learned style can be applied to an input image that matches the classifications of the dataset. In this case, Flickr8k is composed of various classifications and it was easier to train because it is small as compared to the COCO dataset which is originally used for this method.

Here are the results I got:
<p align="center">
  <img src="input_image.jpg" alt="Image" width="256" height="200">
  <img src="style1.jpg" alt="Style" width="256" height="200">
  <img src="results/style_out1.jpg" alt="Result" width="256" height="200">
</p>
<p align="center">
  <img src="input_image.jpg" alt="Image" width="256" height="200">
  <img src="style2.png" alt="Style" width="256" height="200">
  <img src="results/style_out2.jpg" alt="Result" width="256" height="200">
</p>
