## Grad-CAM and CAM implementation with Keras

<hr>

This repo contains Keras implementation of CAM, Grad-CAM, Guided Grad-CAM on the 2017 Korean presidential election candidates' face image data. 

![CAM, Grad-CAM, Guided Grad-CAM](resnet50_guided_grad_cam.png)

## Original Paper links
CAM: <a href="https://arxiv.org/abs/1512.04150"></a>
Grad-CAM: <a href="https://arxiv.org/abs/1610.02391">https://arxiv.org/abs/1610.02391</a>
Guided Backpropagation: <a href="https://arxiv.org/abs/1412.6806">https://arxiv.org/abs/1412.6806</a>

## Data Source
I crawled the original images from Google and cropped faces myself. The dataset is available for any research purposes.
<a href="https://www.floydhub.com/junkwhinger/datasets/presidential_candidates_2017_v2">https://www.floydhub.com/junkwhinger/datasets/presidential_candidates_2017_v2</a>

## Acknowledgement
### Keras implementation of class activation mapping
<a href="https://github.com/jacobgil/keras-cam">https://github.com/jacobgil/keras-cam</a>

### Grad-CAM implementation in Keras
<a href="https://github.com/jacobgil/keras-grad-cam#grad-cam-implementation-in-keras">https://github.com/jacobgil/keras-grad-cam#grad-cam-implementation-in-keras</a>

### Grad-CAM-tensorflow
<a href="https://github.com/insikk/Grad-CAM-tensorflow">https://github.com/insikk/Grad-CAM-tensorflow</a>