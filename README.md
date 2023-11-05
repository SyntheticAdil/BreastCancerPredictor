# BreastCancerPredictor
A beginner's insight to Deep Learning &amp; using it for the betterment of the world. 

# Overview of the model 

I began this project after learning a bit about Deep Learning & thought of using it to make a project which can detect breast cancer with a decent accuracy. 
The way this model works is that, it takes dataset from the SKLearn library & using it, I created a Pandas dataframe for the easier comprehension of the dataset. After that, it was mainly the same 
machine learning process. Splitting the data into traning & testing data and then using the Keras library from Tensorflow to create a normal model with 30 weights while using the Adam optimiser to compile the model. Additionally, using the normal dataset was giving me low accuracies so I used the StandardScaler function to standardise my data for better accuracies.  To understand how the model was doing in terms of accuracy, I plotted out a Model Accuracy chart which visualised the difference between the training & valid data, which seemed to be precise. After evaluation, the model was around 95% accurate. Furthermore, I built a predective model & converted the values to labels and used it to turn it into an array along with reshaping & standardising it and found the argument that gives the maximum value from a target function. If the model converts the input values into a 0, it means the patient has a malignant tumour while an output of 1 indicates that it's benign.

## User Manual :

 1. Clone the project.
 2. Under the Predictive model, there's a line called "input_data"
 3. Here, add the patient's data (for eg : mean compactness, mean fractal dimensions, etc) & run the file
 4. The model will tell you whether the patient has a malignant tumour or not.
