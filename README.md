# *YOLOv5 based thermal image detection*
 <a href="https://github.com/ultralytics/yolov5/actions/workflows/ci-testing.yml"><img src="https://github.com/ultralytics/yolov5/actions/workflows/ci-testing.yml/badge.svg" alt="YOLOv5 CI"></a>
 <a href="https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

YOLOv5 (you only look once 5) is a compound-scaled object detector trained on the COCO dataset. It has 80 classes such as car, person and bicycle. It has been applied to various datasets. 
<div align="center">
  <img src="https://user-images.githubusercontent.com/26456083/86477109-5a7ca780-bd7a-11ea-9cb7-48d9fd6848e7.jpg" width = 800 height = 500>
</div>
We used the <a href = "https://www.shorturl.at/ahAY4">FLIR dataset</a> that was used for multispectral Image classification. We cleaned the dataset and revamped it to fit the needs for only thermal image classification and detection. An example image taken from the thermal camera is shown below.
<div align="center">
<img src = "https://i.ibb.co/f0QxtqV/FLIR-00312.jpg" width = 320 height = 256>
</div>

The annotations given with the dataset were in the format of POC XML, we converted it into the format that is accepted by the YOLO model. We then trained the model on the dataset and achieved almost 90% accuracy. 

The YOLOv5 Example of the results

![image](/Result/image_result.png "Result1")


We used YOLOv5 for thermal image detection and localization of various classes. The classes that we used were:
- Car
- Bicycle
- Person
- Dog


## <div align="center">Documentation</div>

See the [YOLOv5 Docs](https://docs.ultralytics.com) for full documentation on training, testing and deployment.

## <div align="center">Quick Start Examples</div>
