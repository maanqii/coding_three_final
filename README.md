# Coding_three_final
The main thing I wanted to do was to make some changes to the style migration and make beautiful images in different ways that I was happy with.
All the training download images are stored in the image folder（⭐: The content in the 'here the link' under # comments is basically the template content, ## the content under comments is my modified content）

# YOUTUBE：https://youtu.be/RVFAbCpczrY

## Ⅰ  WROK
### Basic reference version: https://tensorflow.google.cn/tutorials/generative/style_transfer 

I have commented line of code with some of the numerical changes I made: , which facilitates my understanding of the convolutional network and its subsequent writing.
### Link:https://github.com/maanqii/coding_three_final/blob/main/style_transfer1.ipynb

The tutorial recommends the LBFGS optimiser. I went online and looked up the relevant information. And on the basis of the information I merged and wrote the results achieved using the LBFGS optimiser.
### reference version1：https://github.com/log0/neural-style-painting/blob/master/TensorFlow%20Implementation%20of%20A%20Neural%20Algorithm%20of%20Artistic%20Style.ipynb

### reference version2：https://github.com/ckmarkoh/neuralart_tensorflow

As the original base version used the Adam optimiser, this was changed and commented on. However, when running it, it would report an error. Although it was an attempt, it took a long time to study it, and I was exhausted because of the errors reported. This version is for reference only, but I will continue to study it and hope that the final version will run successfully.This is my final result.
### Link: https://github.com/maanqii/coding_three_final/blob/main/coding_three_change2.ipynb

## Ⅱ  ATTEMPT
I tried to train the dataset with gan. stylegan and dcgan, and of course the image class. An attempt to form a new set of images based on stylegan replacing the images. Since faces are better represented so I chose to select my favourite stars.

### Link: https://github.com/maanqii/coding_three_final/blob/main/inference_playground_change3.ipynb

Previously I tried to train the dataset with gan. An attempt to form a new set of images based on stylegan replaced the images.
I chose my favourite stars. And picked some patterns to run. But hardly changed the original code very much.

### Link:https://github.com/maanqii/coding_three_final/blob/main/Style_Transfer_Demo_change.ipynb

## Reference book
[1] GATYS, Leon A.; ECKER, Alexander S.; BETHGE, Matthias. Image styletransfer using convolutional neural networks. In: Proceedings of the IEEEconference on computer vision and pattern recognition. 2016. p. 2414-2423.

[2] YANG, Fu Wen, et al. A study on the convolutional neural algorithmof image style transfer. International Journal of Pattern Recognition andArtificial Intelligence, 2019, 33.05: 1954020.

[3] LIU, Long, et al. Advanced deep learning techniques for image styletransfer: A survey. Signal Processing: Image Communication, 2019, 78: 465-470.



