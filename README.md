# Faster R-CNN for Open Images Dataset by Keras
## Introduction
The original code of Keras version I used here is written by [yhenon](https://github.com/yhenon). This is the [github link](https://github.com/yhenon/keras-frcnn). He used the PASCAL VOC 2007, 2012, and MS COCO datasets. For me, I just extracted three classes which are "Person", "Car" and "Mobile phone" from Google's Open Images Dataset V4. I edited configures, remove some parts I didn't need and wrote some comments upon his work and train my own detector. Btw, in order to run this on **Google Colab** (for free GPU computing up to 12hrs), I compressed all the code in one .ipynb notebook. Sorry about the messy structure.

I wrote my exploring and experiment result for Faster R-CNN in this [article]() in Medium. If you are in China, you cannot access [Medium](https://medium.com). So I make a copy in [here]().

## Result for some test images
<p float="left">
    <img src="Assets/e2f4a864682b4645.jpg" width="425"/> 
    <img src="Assets/28cc7decbcc56aa1.jpg" width="425"/>
</p>
<img src="Assets/96b74d5aaadc2259.jpg" width="425"/> 
<img src="Assets/978cd66b8ca034fc.jpg" width="425"/> 
<img src="Assets/c3ca8496d6a9f2de.jpg" width="425"/> 
## Have fun

As the image shown above, they are three porcoelainous monks made by China. I just named them according to their face look (not sure about the sleepy one). They are definitely not included in the Open Images Dataset V4. Except for the three classes I used in Open Images Dataset V4, I also create my own six classes dataset ('Apple Pen', 'Lipbalm', 'Scissor', 'Sleepy Monk', 'Upset Monk' and 'Happy Monk') for fun and train another detector to find out these objects. If you want to know how to do this, just see this [article]() for more details.
<img src="Assets/Result_customdata3.png" width="425"/> 
<img src="Assets/Result_customdata1.jpg" width="425"/> 
<img src="Assets/Result_customdata2.jpg" width="425"/> 