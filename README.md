# **Emotion Recognition from EEG Signals**

## **Overview**
This project shows how brain signals can be used to recognize human emotions using machine learning.  
It uses EEG (electroencephalogram) data to predict whether a person is feeling **Positive**, **Neutral**, or **Negative**.  

The goal is to demonstrate how a computer model can learn patterns from brainwave signals and link them to emotional states.

---

## **Purpose:**
The purpose of this project is to explore how artificial intelligence can interpret EEG data for emotion recognition.  
It also helps understand the connection between neuroscience and machine learning.

---

## **Why I Did This:**
I wanted to learn how brain-computer interfaces work and how machines can understand human brain signals.  
This project helped me practice working with real EEG data, build a machine learning model, and visualize the results.

---

## **How It Works:**
1. **Load Data:** Real EEG brainwave data is used from a public dataset.  
2. **Clean Data:** Missing values are removed to prepare clean data for training.  
3. **Train Model:** A **Random Forest Classifier** is used to learn emotional patterns.  
4. **Predict Emotions:** The model predicts emotions based on new EEG readings.  
5. **Visualize Results:** Accuracy and most important EEG features are shown in graphs.

---

## **Tools Used**
- Python  
- Google Colab  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## **Results**
The model achieved about **96.8 percent accuracy**, which means it correctly predicted emotions in almost all test cases.  
It also showed which EEG signal patterns had the biggest influence on the predictions.

---

## **What I Learned:**
- How EEG data represents brain activity and emotions  
- How to process and analyze real-world data  
- How Random Forest models make predictions  
- How AI can be applied to emotion recognition and neuroscience research  

---

## **How to Run:**
1. Open the notebook in **Google Colab**.  
2. Upload the EEG dataset file (`data.csv`) from the **EEG Brainwave Dataset: Feeling Emotions** on Kaggle.  
3. Run each code cell step by step.  
4. View the accuracy, predictions, and visualizations.  

---

## **Dataset:**
**Name:** EEG Brainwave Dataset: Feeling Emotions  
**Source:** Available publicly on Kaggle  

---

## **Summary:**
This project shows how brainwave data can be used to identify emotional states using machine learning.  
It is a simple example of how computers can interpret human emotions from EEG data.

---

## **Future Improvements**
- Add real-time emotion detection using live EEG signals  
- Create a visual interface to display predicted emotions  
- Experiment with deep learning models for higher accuracy  
