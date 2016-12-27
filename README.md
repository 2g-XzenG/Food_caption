# Food_caption

In this project, I use the code from [show attend and tell](https://github.com/jazzsaxmafia/show_attend_and_tell.tensorflow), which is implemented base on paper: [show attend and tell](https://arxiv.org/abs/1502.03044)

Since the goal is to predict the label of the image, and eventually hope one can generate the ingredient of the food image, so we think using the image caption generation technique is more appropriate than image classification. But due to the limit of the dataset, for now, I can only use the image label as the caption. Overall though, the result is not bad.

# General Idea

1. Extract Image feature by CNN (VGG-19)
2. Use attention base LSTM model to generate the caption of the image, which in this case, is the label of the image

# Result
![alt tag](https://github.com/1230pitchanqw/Food_caption/Result/ice_cream293.jpg)

The white part is the attention area that the machine focus on to make the caption/label prediction
