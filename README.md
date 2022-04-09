# Difference_CNN_DNN

In this case we will see the difference using convolutional and without convolutional to train our model. 

Even though the accuracy is not really big because I think the data is not really good. as you can see in the sample of data, Iron Man's sample shows that in there is captain america and thor in the same image, that will confuse the model as well. The actual dataset has 8 classes. But in this project we will only use 2 classes because when I'm using all the classes my computer will crash so I just used 2 classes here.

![Screenshot 2022-04-09 191812](https://user-images.githubusercontent.com/91602612/162569571-0a97e025-2481-4417-948b-5a5c93be7ebb.png)

But with this experiment we can see that using convolutional will perform a better accuracy and reduce the loss between train and validation significantly.

## Without Convolutional

  1. The train's accuracy in 10 epoch is 52% and the loss in train is 11.87
  2. The validation's accuracy in 10 epoch is 53% and the loss in validation is 7.23
 
![Screenshot 2022-04-09 192004](https://user-images.githubusercontent.com/91602612/162569623-df6b6843-01cc-4fd5-b074-a4827146140f.png)

![Screenshot 2022-04-09 192015](https://user-images.githubusercontent.com/91602612/162569629-aef9959a-f441-4600-908d-b971c989bd7e.png)

## With Convolutional

  1. The  train's accuracy in 10 epoch is 61% and the loss train is 0.66
  2. The validation's accuracy in 10 epoch is 66% and the loss validation is 0.66
  
![Screenshot 2022-04-09 192541](https://user-images.githubusercontent.com/91602612/162569839-117ecba4-a6cc-4202-9f2a-173f95e48484.png)

![Screenshot 2022-04-09 192551](https://user-images.githubusercontent.com/91602612/162569848-f9d2de04-22ab-46f7-9455-1bea3fdae52f.png)


