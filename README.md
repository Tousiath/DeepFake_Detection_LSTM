# Fake Video Classification using LSTM

### 1. Introduction
The Fake Video Classification project utilizes a Long Short-Term Memory (LSTM) algorithm to detect and classify deepfake videos. By analyzing the temporal patterns in video frames, the model can distinguish between genuine and manipulated content. This project also features a user-friendly website built with Flask, allowing users to easily upload and classify videos in real-time.

### 2. Structure
The project is organized as follows:

```text
Fake_Video_Classification
│
├── Model Creation
│   ├── preprocessing.ipynb
│   ├── Predict.ipynb
│   └── Model_and_train_csv.ipynb
│
├── Model
│   └── trained_model6.pt
│
├── Flask Application
│   ├── app.py
│   ├── templates/
│   ├── static/
│
```


**Model Creation**  
This directory contains Jupyter notebooks used for preprocessing the data, making predictions, and training the LSTM model. It showcases the step-by-step process of how the deepfake detection model is created.


**Model**  
The trained LSTM model is saved as `trained_model6.pt`. The model can be found at this [link](https://drive.google.com/file/d/1ycyQwouJkzc7FRlCR_QbheJZvZgPI_7O/view?usp=sharing).


**Flask Application**  
It includes the files for Flask-based web application. Users can upload videos, which are then processed by the LSTM model to classify them as real or fake, with results displayed on the web interface.


### 3. System Architecture

![system architecture](https://github.com/user-attachments/assets/91402a17-1b81-4821-be1b-70fd3abb884b)

### 4. My Project Demo

https://github.com/user-attachments/assets/69c47d93-d1fe-4534-9b61-35625989dbe8

### 5. Results
The results of this model are summarized below. The metrics provide insights into the performance of the LSTM-based fake video classification system.

| Metric             | Value   |
|--------------------|---------|
| Precision          | 91.23%  |
| Recall             | 85.25%  |
| F1 Score           | 88.17%  |
| Overall Accuracy   | 88.71%  |

---

**Happy learning and keep exploring!😊😊**


