# EE541-Final

'ASL_model.h5' model is trained with data without skeletenization.
'ASL_model_modified.h5' is the model we get following the procedure mentioned in report.

'project_processing.ipynb' includes 3 different parts. 
First one is to preprocessing the training data. It adds skeletens to the figures of hands and save the new figures at a new folder.

Second one is using the CNN model for traning. It saves the model as 'ASL_model_modified.h5' at root folder. The traning set usually takes around 8 to 10 hours.

Running the third part of ipynb starts a real-time hand gesture capturer window to recognize the ASL letter based of the trained model from 'ASL_model_modified.h5'.

'project_processing.ipynb' requires installing the following modules:
matplotlib
pandas
os
tensorflow
cv2
cvzone
