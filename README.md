# Image-classification-to-detect-car-using-resnet-18---ml
Image Classification for detecting the type of the car using resnet 18 Algorithm, pytorch libraries. This is done using both pretrained and non pretrained algorithms of the resnet - 18.

### Finding
Pretrained Model is more accurate in test data, but one key point to observe in the accuracies of that model is, in the training data it is overfitting. Overfitting is a modeling error which
occurs when a function is too closely fit to a limited set of data points. This results in a much complex model. To overcome this overfitting, we have to early stop training the model. The pretrained model
is also said to be overfitting by observing the training and validation loss. In this case of the model (pretrained = true) training loss is much less than validation loss, which
means that our model is fitting very nicely the training data, but not at all the validation data, in other words it's not generalizing correctly to unseen data which is called as “Overfitting”.

On the contrary, the model which is trained from scratch is learning and improving its accuracy over epochs. It can also be justified by observing the training and validation losses which are
almost similar. Hence, if data is more transformed and clear, model without transfer learning will be more perfect for this scenario.
