# Crowd Counting ( Work in Progress )
<p> Crowd Counting is a technique to count or estimate the number of people in an image. Most computer vision techniques can produce impressively precise estimates. <\p>

# Algorithms & Techniques
<p>In CNN instead of looking at the patches of an image, we build an end-to-end regression method using CNNs. This takes the entire image as input and directly generates the crowd count. CNNs work really well with regression or classification tasks, and they have also proved their worth in generating density maps. <\p>

<p>Using CSRNet to provide a data-driven and deep learning method that can understand highly congested scenes and perform accurate count estimation as well as present high-quality density maps. The proposed CSRNet is composed of two major components: a convolutional neural network (CNN) as the front-end for 2D feature extraction and a dilated CNN for the back-end, which uses dilated kernels to deliver larger reception fields and to replace pooling operations.<\p>

[Dataset link]

# How is it working 
<p>1. The dataset consists of the images in .jpeg format and the ground truth. The below image shows the Image + Ground Truth : <\p>
<img src="https://user-images.githubusercontent.com/35666615/57588278-4d965800-74d7-11e9-89eb-9da9247f87d4.PNG">

 
[Dataset link]: http://personal.ie.cuhk.edu.hk/~ccloy/downloads_mall_dataset.html
