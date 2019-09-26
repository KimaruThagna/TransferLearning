# TransferLearning
Using the inception V3 model to perform transfer learning for pneumonia prediction from chest x-rays
Link to the kaggle notebook.
https://www.kaggle.com/kimaruthagana/transferlearning-pneumonia-xray-dataset <br/> <br/>
##METHODOLOGY

1.Use the inception_V3 model and eliminate the top layers to allow retraining with custom image dataset.<br/>
2. Set up your custom prediction output layer to the number of classes of your data, in this case 2<br/>
3. Create a model that is a combination of the inception and the custom output layers.<br/>
4. Train the whole network. You can decide to retrain the whole inception model or only the top x layers towards the output layer.

