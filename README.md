# CNN : torch_vs_Tensorflow2.0


### compare torch vs tensorflow

|Framework|Tensorflow|Pytorch|
|:-----:|------|-------|
|Pros|- Simple built-in high-level API  <br>- Visualizing training with Tensorboard (also torch) <br> - Production-ready <br>- Easy mobile support (TF Light) |- Python-like coding <br> - Dynamic graph. <br> - Easy & quick editing <br> Plenty of projects using Pytorch.|
|Cons|- Static graph <br> - Debuggin method <br> - bug..... (2.* ver) <br> - Hard to make quick changes. | - Third-party needed for visualization. (need Tensorboard) <br>- API server needed for production |
|Recommendation|If you want to make thing faster and build AI-related products. | for research-oriented developers as it supports fast and dynamic training. |



-------------------------------------------------------------

### 1. basic CNN - torch vs tensorflow

![3depth_cnn](img/depth3_cnn.png)
_from : http://personal.ie.cuhk.edu.hk/~ccloy/project_target_code/index.html_
* Pytorch 1.4.0 version's CNN 3depth layers : [basic_cnn_torch](/basic_cnn_torch.ipynb)
* Tensorflow 2.3.1 version's CNN 3depth layers : [basic_cnn_tensorflow](/basic_cnn_keras_2.3.1.ipynb)

### 2. Advanced CNN(VGG) - torch vs tensorflow
### 3. ResNet - torch vs tensorflow

