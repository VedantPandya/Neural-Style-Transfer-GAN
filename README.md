# Neural Art Style Transfer
An art style transfer model based on generative adversarial network, that is trained for a particular style. Model architecture consists of Image transform net and a pretrained VGG-16 model which acts as Loss Network.Input required is any image on which the user intends to perform style transfer, output will be an image of the selected style while still retaining the features of the input image.

* Style transfer could be done in realtime with passing a `Style` and `Content` image, and a `percentage/number indicating the significance` of style in the content image
* Another method could be training a model for a particular `Style` and then later using it.
* Time required to train the model is lot more in second case but the transfered image generation time is significantly less.

### Basic Flow Diagram for Second Method
![FlowChart](https://github.com/shivanshu1641/Neural-Art-Style-Transfer/blob/main/FlowChart.PNG?raw=true)

#### Language

[Python](https://linktodocumentation)

#### Model / Major Packages
[TensorFlow](https://tensorflow.org/),
[Keras](https://keras.io/),
[Pandas](https://pandas.pydata.org/),
[PIL](https://pypi.org/project/Pillow/)
