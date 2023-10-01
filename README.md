# building detection in sattelite images

In this projest we use a U-net like architecture to segment buildings in sattelite images.

## Dataset

We used this dataset : [Link text](https://www.kaggle.com/datasets/kmader/synthetic-word-ocr).

## Training

We used a batch size of only 16 because of the machine limilations, this resulted in more than 9000 steps per epoch, as a result we trained the model for only 4 epochs.
you can find the plot for the training here:
[alt text](assets/building_sat_im_acc.png)
[alt text](assets/building_sat_im_loss.png)

## Results

These are some sampled results from the test set.
[alt text](assets/building_sat_im_loss.png)



