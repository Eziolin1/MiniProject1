Hi, this is our repo for MiniProject1 about ResNet!

Our final model was stored in the project1_final_model.py and the parameters were stored in project1_final_model.pt.
Both files can be found under the root directory /MiniProject/

We have used normalization at the last step of data augmentation and the mean and std value were calculated as below,
transforms.Normalize((0.4244, 0.4146, 0.3836), (0.2539, 0.2491, 0.2420)).
We believe it's reasonable to do the exact same normalization on testdataset before testing.
