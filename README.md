# FaceRecognition
We are trying to build a deep model to recognize faces.<br />
The dataset is stricted to 5 images for each face.<br />
Five images for each (Trump, Putin, and Obama) are added as original images (our entire dataset).<br /> 
Interesting approaches are utilized to make the approach functional.<br />
Data augmentation increases the images in our dataset.<br />
Image augmentation techniques used are scaling, cropping, flipping, padding, rotation, and translation.<br />
Transfer learning provided us with a trained model to recognize faces.<br />
The trained model used is VGG16.<br />
We fine tuned the trained model to meet the specifications of out system.<br />
Then we modified the models parameters by training it on our dataset.<br />
finally, the model was tested on the test set and achieved 92.5% accuracy.<br />
Other performance metrics (precision and recall) aren't taken into consideration becuase the dataset is balanced.<br />
Moreover, the system was tested on new data too and it did well. <br /> 

Codes are stored in notebooks file. <br />
