[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## 项目概述

欢迎来到卷积神经网络（CNN）项目！在这一项目中，你将学到如何建立一个处理现实生活中的，用户提供的图像的算法。给你一个狗的图像，你的算法将会识别并估计狗的品种，如果提供的图像是人，代码将会识别最相近的狗的品种。

![Sample Output][image1]

在学习用于分类的最先进的 CNN 模型的同时，你将会为用户体验做出重要的设计与决定。我们的目标是，当你完成这一项目时，你将可以理解，通过将一系列模型拼接在一起，设计数据处理管道完成各式各样的任务所面临的挑战。每个模型都有它的优点与缺点，并且设计实际应用时，经常会面对解决许多没有最优解的问题。尽管你的解答不是最优的，但你的设计将带来愉快的用户体验！


## 项目指南

### 步骤

1. 进入文件夹并激活环境。

 ```bash
cd iResearch/dog_classification
source activate iResearch
```

2. 下载[狗狗数据集](https://pan.baidu.com/s/1Ka0BHL8ls3OQEAm4LYItag)，并将数据集解压大存储库中，地点为`项目路径/dogImages`. 

3. 下载[人类数据集](https://pan.baidu.com/s/106X1yILobxWx0O915-kPjw)。并将数据集解压大存储库中，位置为`项目路径/lfw `。

4. 为狗狗数据集下载 [VGG-16关键特征](https://pan.baidu.com/s/1_R_95GaaI56lIUERJnrhCQ) 并将其放置于存储库中，位置为`项目路径/bottleneck_features `。

5. 打开 notebook

 ```
jupyter notebook dog_app.ipynb
```

__注意：__ 我们虽然已经实现了一些代码，让你更快地开始工作，你仍需要实现额外的功能，以回答 notebook 中所有的问题。
__除非有要求，否则不要修改任何已经包含的代码。__

## 项目提交

当你准备好提交你的项目时，将下列文件整理并压缩成一个文件，以便上传。

- 代码完整可运行的文件 `dog_app.ipynb`，所有的代码块都要执行并展示结果，并要求回答所有问题
- 将你的 notebook 导出为 HTML 或 PDF 格式，并以 `report.html` 或是 `report.pdf` 命名
- 任何用于项目中，并且并非由我们为这一项目提供的额外数据图片。
__请不要将 `dogImages/` 或是 `lfw/` 文件夹中的项目数据包含在内，同样的，请不要将 `bottleneck_features/` 文件夹包含在内。__
