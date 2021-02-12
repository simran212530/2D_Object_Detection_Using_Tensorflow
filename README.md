# 2D_Object_Detection_Using_Tensorflow

# Scope

This repo is aiming to provide production ready **2D object detection** code basics.

It's based on official tensorflow API jupyter notebook but I will gradually add more popular models such as `yolo` series.

### More

If you are interested in **3D object detection**, visit this [repo](https://github.com/KleinYuan/tf-3d-object-detection).

If you are interested in **Segmentation**, visit this [repo](https://github.com/KleinYuan/tf-segmentation).


# Introduction
# Run Demo


```
# Clone this repo
git clone https://github.com/KleinYuan/tf-object-detection.git

# Setting up
cd tf-object-detection
bash setup.sh

# Run demo
python app.py

```

# Image Classifications

I also put an image classifications inference app (VGG16) here.

```
# Assuming you already run setup.sh, which will download vgg16.np

python app_ic.py
```

# Networks

| Model name  | Architecture|
| ------------ | :--------------: |
| [AlextNet](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks) | ![AlexNet](https://kratzert.github.io/images/finetune_alexnet/alexnet.png)|
| [Vgg 16](https://arxiv.org/abs/1409.1556) | ![VGG16](https://www.cs.toronto.edu/~frossard/post/vgg16/vgg16.png)|
| [SSD](https://arxiv.org/abs/1512.02325) | ![SSD](http://joshua881228.webfactional.com/media/uploads/ReadingNote/arXiv_SSD/SSD.png)|
| [Faster R-CNN](https://arxiv.org/abs/1506.01497) | ![fasterrcnn](https://raw.githubusercontent.com/sunshineatnoon/Paper-Collection/master/images/faster-rcnn.png)|
