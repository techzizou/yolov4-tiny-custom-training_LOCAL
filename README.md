

# Train a custom YOLOv4-tiny object detector on Windows


![](yolov4-tiny-custom.gif)

Original Video by cottonbro from Pexels


## Mask detection using YOLOv4-tiny

The **yolov4-tiny** folder in this repository contains the 4 custom files needed. (i.e. **yolov4-tiny-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images). I have shared my labeled custom mask dataset **obj.zip** file on the following link. You can download it from here.

https://www.kaggle.com/techzizou/labeled-mask-dataset-yolo-darknet


The **obj.zip** file contains 1510 images along with their YOLO labeled text files. I have labeled around 1350 of these and downloaded 149 labeled images from roboflow. I have given the links for my dataset sources at the bottom. 

This dataset has mostly close-up images (around 1300) and very few long-shot images (around 200). If you want to download more long-shot images, you can search for datasets online. There are many sites where you can find more datasets. Check out my Medium article below for links to these sites. I have also given a few links for mask datasets. Some of them have more than 10,000 images. You can add your own images and their YOLO labeled text files to the dataset. Try to find good quality images.

**<ins>NOTE</ins>** : The **yolov4-tiny-custom.cfg**, **obj.data**, and **obj.names** files are customized for the 2 classes I am working with. (i.e. "with_mask" & "without_mask"). You can edit these files for your custom objects.



## My article on this

https://medium.com/analytics-vidhya/train-a-custom-yolov4-tiny-object-detector-on-windows-5ec436100433


## Watch my YouTube video on this 

https://youtu.be/kCZUj6Xy6nM



# CREDITS 

## References

[AlexeyAB GitHub](https://github.com/AlexeyAB/darknet/)


## Mask Dataset Sources

I have used these 3 datasets for my labeled **obj.zip** dataset. Check out my medium article above for more mask datasets.

[Prajnasb Github](https://github.com/prajnasb/observations)

[Joseph Nelson Roboflow](https://public.roboflow.com/object-detection/mask-wearing)

[X-zhangyang Github](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset)


![](test2-tiny.gif)

Original Video by Nothing Ahead from Pexels
