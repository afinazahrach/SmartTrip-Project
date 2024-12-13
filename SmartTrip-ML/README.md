# SmartTrip-ML folder

This folder contains artifacts related to *machine learning models* used in the *SmartTrip* project. This model is designed to support the prediction of tourist attractions recommendations based on user data. The following is a description of the files contained in this folder:

## File Description

### model.tflite
- This file is a Machine Learning model that has been trained and converted to *TensorFlow Lite* format.  
- *Function:*  
  This model is designed to predict the recommendation of *tourist attractions* based on certain inputs.  
- *Input:*  
  The model accepts data with the following attributes:  
  - *Location:* Geographical location of tourist attractions.  
  - *Category:* Type of tourist attractions (e.g. nature, culture, entertainment, etc.).  
  - *Tariff:* Entry fee or price to enjoy the attraction.  
  - *Experience:* The experience or activity offered (e.g. trekking, photography, etc.).  
  - *Rating:* Ratings from previous users.  
- *Utilization:*  
  Integrate this model into an application using the TensorFlow Lite interpreter to get predictions of tourist attractions that match user preferences.

### final_notebook.ipynb
- A Google Colab notebook containing the model development pipeline.  
- *Main Contents:*  
  - Data preprocessing.  
  - Training Machine Learning model for tourist attractions recommendation.  
  - Model performance evaluation.  
  - Model conversion to TensorFlow Lite format (.tflite).  
- Uses:**  
  This file can be used to understand the model development process or as a reference for model retraining.  
- *Notes:*  
  To open this file in Google Colab, make sure you have uploaded it to Google Drive or use the “Open with Colab” option.

---
