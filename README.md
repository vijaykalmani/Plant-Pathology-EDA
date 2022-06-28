# Plant-Pathology-EDA
Tasks to be performed:
#### 1) A Plant Pathology client is working on identifying diseases impacting agricultural crops. They have a dataset of crop images with labels of diseases impacting them. Dataset can be found here: https://www.kaggle.com/c/plant-pathology-2020-fgvc7/overview
- Create an EDA report for the above stated problem, outlining what & why of your approach?

#### 2) A Plant Pathology client is working on identifying diseases impacting agricultural crops. They have a dataset of crop images with labels of diseases impacting them. But the client is unable to provide more images (as requested by you) for training:
- What is the typical routine you will follow here (when data is scarce)?
- What are the basic augmentation techniques you can follow here, please explain how and why they are useful (for plant leaf images) ?
- Try to use augmentation packages other than ImagDataGenerator from keras, example - `imgaug` 
#### 3) Iterate over and try different architecture and topologies and preserve the results of each experiment using TensorBoard. Also, save major metrics in an Excel (or try W&B).
#### 4) For the above prepared model prepare a classification report with major metrics (confusion metric, recall, precision., etc) on the test data.  
#### 5) For the above problem statement, save the model and re-use it in another Collab sheet and perform a prediction. For prediction, create a separate function which will expect an input image and output the prediction label (with confidence).
