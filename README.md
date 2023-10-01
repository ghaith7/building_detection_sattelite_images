# building detection in sattelite images

In this projest we use a U-net like architecture to segment buildings in sattelite images.

## Dataset

We used this dataset : [kaggle.com/datasets/km](https://www.kaggle.com/datasets/kmader/synthetic-word-ocr).

## Training

We used a batch size of only 16 because of the machine limilations, this resulted in more than 9000 steps per epoch, as a result we trained the model for only 4 epochs.
you can find the plot for the training here:
accuracy plot             |  loss plot
:-------------------------:|:-------------------------:
![assets/building_sat_im_acc.png](https://github.com/ghaith7/building_detection_sattelite_images/blob/main/assets/building_sat_im_acc.PNG)| ![](https://github.com/ghaith7/building_detection_sattelite_images/blob/main/assets/building_sat_im_loss.PNG)

## Results
These are the accuracy scores of the model:
| set | accuacy |
| ----------- | ----------- |
| Train | 94.97 |
| Validation | 95.63 |
| Test | 95.52 |

These are some sampled results from the test set.
![](https://github.com/ghaith7/building_detection_sattelite_images/blob/main/assets/results_sample.PNG)


