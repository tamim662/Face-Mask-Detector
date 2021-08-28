# Face-Mask-Detection
### I, here implemented a deep learning model using YOLOv4 to detect Face Mask on Human face. 

------------------------------------------------------------------------------------------------
#### The Dataset collected from the [Kaggle Face Mask Detection Dataset](https://www.kaggle.com/andrewmvd/face-mask-detection)

Here, I was not using the default YOLOv4 model rather using the tiny version of it. The reason behind it the default version takes a huge amount of time to train, where the tiny version takes very little time. But the ability of detection was not compromised where I use the generated anchors on the custom dataset and turn on random initialization to increase the accuracy finally used 3 YOLO detection layers to detect objects in small, medium, and large scales.


