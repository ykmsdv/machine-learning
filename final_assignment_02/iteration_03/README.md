## Iteration 03


For the image transformation I used the scikit image transform.rescale, and feature.corner_harris functions and image dimensions (15, 35). The Multi-layer Perceptron (neural network) uses default parameters, with the exception of max\_iter=5000.
###### Original image
![](graphs/original_image.png)
###### Transformed image
![](graphs/transformed.png)

<br/>
Here is the ROC plot comparing the performance of of the model on train data and test data after the changes were introduced.

###### ROC train set
![](graphs/ROC.png)