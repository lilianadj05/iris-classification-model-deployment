# 🌸 Iris Classification and Deployment Project

## 📌 Project Overview
This project focuses on building and deploying a machine learning model to classify iris species. The workflow includes exploratory data analysis (EDA) to understand the dataset, training a Support Vector Machine (SVM) model, and finally, deploying the model using a Streamlit application for interactive predictions.

## 📊 Dataset
The project uses the well-known Iris dataset. This dataset contains information on the physical characteristics of three species of iris flowers: Iris-setosa, Iris-versicolor, and Iris-virginica. The dataset includes measurements for sepal length, sepal width, petal length, and petal width.

## 🔍 Key Findings
1. The sns.pairplot visualization revealed distinct groupings for the three iris species based on their features, indicating that a classification model would likely perform well.
2. The average values of the four features (Sepal length, Sepal width, Petal length, and Petal width) differ significantly across the three species. This reinforces the idea that these features are strong predictors for classification.
3. The SVM model achieved a high accuracy of 90% on the test set, demonstrating its effectiveness in classifying the iris species.

## 📈 Steps
1. **Data Cleaning and Preprocessing**: The Iris dataset was loaded, and the columns were properly named. The data was then separated into features (X) and the target variable (Y), representing the measurements and the species labels, respectively. The dataset was split into training and testing sets to prepare for model building and evaluation.
2. **Modeling and Evaluation**: A Support Vector Machine (SVM) classifier was chosen and trained on the training data. The model's performance was evaluated using the test set, achieving an accuracy of 90% and a detailed classification report showed high precision and recall for the different classes. The trained model was then saved as SVM.pickle for later use in the Streamlit application.
3. **Deployment**: A Streamlit application (iris_streamlit.py) was created to serve as a user-friendly interface. This application loads the pre-trained SVM.pickle model. Users can interactively adjust the sepal and petal measurements using sliders, and the application will provide a real-time prediction of the iris species.

## 💡 Conclusion
This project successfully demonstrates the end-to-end process of building a machine learning model for a classification task and deploying it as an interactive web application. The SVM model proved to be effective for this task, and the Streamlit app provides a simple way for others to use the model without needing to write any code.

## 🔮 Possible Future Works
1. **Model Improvement**: Experiment with other machine learning algorithms like K-Nearest Neighbors (K-NN) or Random Forest to see if a higher accuracy can be achieved.
2. **Advanced Features**: Implement a feature that allows users to upload their own CSV data to make predictions in bulk.
3. **Deployment**: Deploy the Streamlit application on a cloud platform like Heroku or AWS so that it can be accessed publicly.
4. **Model Interpretability**: Incorporate a feature that explains why the model made a particular prediction, using techniques like SHAP or LIME.

## 👨‍💻 Author
**Liliana Djaja Witama** | Undergraduate Data Science Student at BINUS University
