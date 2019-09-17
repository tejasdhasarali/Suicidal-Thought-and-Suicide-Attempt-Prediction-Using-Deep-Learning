# Suicidal Thought and Suicide Attempt Prediction Using Deep Learning

* The project aims to predict the Suicidal Thoughts and Suicide Attempts with the help of Neural Network

* The data was collected from the National Comorbidity Survey (NCS-1), which was conducted in 1990 to spring 1992. The questions for this survey was prepared based on the book Diagnostic and Statistical Manual of Mental Disorders (DSM), which defines and classifies mental disorders to improve diagnoses, treatment, and research.

* In the collected data the number of people who had suicidal thoughts or attempted suicide was very less compared to the people who haven't. This data imbalance problem was solved using upsampling, SMOTE and Class weights. 

* Five models each for Suicidal Thought and Suicide Attempt was built using Fully Connected and Locally Connected Neural Networks.

* The results of these trained neural networks was cross verified using stratified 10 fold cross-validations.

* A new consensus method was used on the five trained models to improve the accuracy and reliability of the trained models. 

* In consensus method at least k out of n models should predict the same class with a probability greater than the selected threshold.

* Finally the model's prediction was interpreted to find the features that are affecting the model's classification positively and negatively. 

* The model was interpreted by finding the Jacobian Matrix/Gradient of the model's classification with respect to each input feature.

### The research paper on this project is being written and will be published this year. After that, the code will be made public.
