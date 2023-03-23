Here we are using VGG16 to train the model.
From the above model you would be able to notice the disease class of the plant and where exactly the problem is present in the plant which would help the farmer to easily recognize it.
For our case we decided to focus on one plant that is potato which is basically having two diseases and the other one is healthy.
so they have been depicted as the individual classes
    1.Healthy leaf--> 0
    2.Early_blight --->1
    3.Late_blight --->2
so with all this information, we are trying to predict whether the plant is infected using the model.The model performs at the accuracy that is greater than 75% on the test dataset so we would be able to use this in the real time.

Then we are greating a Website where you could able to upload the image of the leaf it will tell about the disease class and bounding baox will show the place where it is actually present.