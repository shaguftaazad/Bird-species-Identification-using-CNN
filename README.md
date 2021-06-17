# Bird-species-Identification-using-CNN
Understanding the communication patterns and behaviour of bird species is critical for understanding the quality of the environment in which we live . 
Since 1990, the global area of primary forest has been reduced by more than 80 million hectares due to rapid urbanisation 
In this project we used audio data to classify the bird species. Because of limited resources we were limited to 5 classes: 
aldfly, dowwoo, robgro, scatan, hamfly.
We tried to extract these 5 species data from the audio data. We used STFT and MFCC feature extraction method to make the updated data. And performed CNN,RNN-LSTM and Dense NN.
The main findings are: dense ANN: The model is fast and has a simple pattern but it produces too much overfitting and has too many trainable parameters for a lower accuracy than the other models. Moreover, the model is not stable from one run to another.
RNN-LSTM: The model is the more accurate but the cost in computation time is not worth it.
CNN: The model is slightly less accurate than the RNN-LSTM but it is marginal compared to its very low computational time, number of trainable parameters and over-fitting.
MFCCs are definitely better to use than STFTs both for accuracy and computational time.
