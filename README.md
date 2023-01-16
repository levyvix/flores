## Using transfer learning and fast.ai API to train a flower classifier

This project uses ResNet pre-trained model to a custom dataset to classify flower types.

### Steps

- Apply transformations and augment the data (Rotate, Crop, Brightness, Contrast, Cut)
- Instatiate a pre-trained model and configure the DataLoders for mini-batch gradient descent
- Visualize the predictions and set the data-predictions workflow
- Plot the tops losses of the model
- Save the model for further use