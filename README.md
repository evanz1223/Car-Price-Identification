# Car-Price-Identification-Through-Linear-Regression
This Repository was made to showcase a Machine Learning Model that I made about car price identification.
# Tech Stack:
I used the software Google colab to code this model, all the libraires I used are: 
pandas,
seaborn, 
numpy, 
matplotlib.pyplot, 
sklearn.metrics, 
ucimlrepo, 
sklearn.model_selection, 
sklearn.preprocessing, 
tensorflow, 
keras_tuner, 
sklearn.linear_model, 
gradio, 
joblib, 

# Accuracy:
The accuracy of this model that I developed gets around 1000 dollars off of the actual car price, the mse is around 4 million but the mae is around 3000. This means that the model is around 3000 dollars off the actual price on average I did this by using hyperparameters to train the model and things like early stopping which stops the epoches early when the model stops improving.

# Workflow:
I first got my dataset from UCI Machine Learning Repository, scaled the data, split the data into training data and testing data, started training the model with hyperparameters and keras_tuner. While I trained the model, I worked on this github repository and made my google slides presentation which is also in this repository. When I finished all of that, I finally started working on the UI.

# Dataset:
I found my dataset on the University Of California, Irvine, the dataset was created in 1985 by 1985 Ward's Automotive Yearbook on 5/18 the actual dataset is called [Automobile](https://archive.ics.uci.edu/dataset/10/automobile).

# UI:
I made the UI using Gradio in python and the link to the website is [car predicter](https://16e1233393187c6712.gradio.live/) The UI has a slot for every feature to input so just look up your cars specs and it will give you an estimated price. <img width="1587" height="1017" alt="image" src="https://github.com/user-attachments/assets/fa5f2d2b-d51e-4993-8e13-2d9166874e87" />
There are other, more important feature imputs above the screenshot but I wanted to show the button where it shows the price

# Problems:
Some problems that I face was since my dataset was made in 1985, the Model can not predict higher end cars like supercars but can still predict high-middle class vehicles. Another problem is that the UI that I made with Gradio only lasts a week from the start of making it so the only way to access it after 8/1 is by using the UI in the colab file.

# Examples:
First, this is an example of the model predicting a Mercedes-Benz GL500 which is around 80,000 dollars new
<img width="1616" height="1032" alt="Screenshot 2026-07-29 131631" src="https://github.com/user-attachments/assets/c3e79412-8923-4b45-8d93-d6f329ac7bc5" />

