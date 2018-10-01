/*

   Author-> Raj Mehrotra
   Date-> 24-09-2018
   
*/

The dataset is Flower Recognition on Kaggle. 

The dataset consists of 4232 images each of different pixel values. Each of the image can be classified into either of 5 types-> 'Daisy','Rose', 'Sunflower','Tulip' or 'Dandelion' . 

I have trained Convolutional Neural Network written in Keras to predict the type of flower on the validation set.  Also used ImageDataGenerator to augment the training set and avoid overfitting problem and a LR annealer to schedule the learning rate.

Finally the accuracy on the validation set using the self-laid ConvNet is close to 80%.

Lastly I have also used transfer learning and used the pretrained VGG model and then fine tune it to achieve even greater validation accuracy of close to 93%.
