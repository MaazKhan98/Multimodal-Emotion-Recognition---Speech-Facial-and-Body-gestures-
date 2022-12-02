# Multimodal-Emotion-Recognition-speech-facial-and-body-gestures

This work specifies techniques used for the Emotion Recognition on multimodal emotional database - Polish Emotion dataset. The current state of sentiments in the database
videos were acknowledged by preprocessing of data and extraction of robust features. We have presented three modalities: facial expression, speech, and body language and 
each modality has been approached twice by different methods .For the case of facial expression and speech modality , both were trained for its specific CNN and LSTM 
model , in order to return the model which gives better results. In the case of body gesture modality , we implemented LSTM model and ML classifier - Support Vector 
Machine (SVM) . 
The training and testing accuracies of all the models of all three modalities have been tabulated and analyzed. Facial landmark detection was used to detect emotion 
through facial expression and Mel-Frequency Cepstral Coefficients (MFCCs) for speech audio. Further, the results obtained from the three unimodal models can be fused by 
decision level and feature level fusion to get multimodal models with much better accuracies.

