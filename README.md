# Interview Analysis using Face Detection and Facial Emotion Recognition

## Overview

Interview Analysis using Face Detection and Facial Emotion Recognition is a computer vision and deep learning project that analyzes a candidate's facial expressions during interviews. The system detects faces from recorded and live video streams, classifies facial emotions, and provides insights into the candidate's emotional state and engagement throughout the interview.

The project is being developed as part of the Master of Computer Applications (MCA) final-year curriculum.

---

## Objectives

- Detect faces in recorded and live interview videos.
- Recognize facial emotions using a deep learning model.
- Analyze emotional trends during an interview.
- Generate interview analysis reports based on detected emotions.
- Provide an easy-to-use interface for emotion analysis.

---

## Features

- Face Detection
- Facial Emotion Recognition
- Recorded Video Analysis
- Live Webcam Analysis
- Emotion Timeline Visualization
- Interview Analysis Report
- Interactive Dashboard

---

## Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Deep Learning | TensorFlow, Keras |
| Computer Vision | OpenCV, MediaPipe |
| Data Analysis | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Web Framework | Streamlit |

---

## Dataset

**Dataset:** FER2013

The FER2013 dataset consists of grayscale facial images categorized into seven different emotions:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

**Image Resolution:** 48 × 48 pixels

---

## Project Workflow

```
FER2013 Dataset
        │
        ▼
Dataset Inspection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Preprocessing
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Recorded Video Analysis
        │
        ▼
Live Webcam Analysis
        │
        ▼
Interview Report Generation
```

---

## Project Structure

```
Interview-Analysis-using-Face-Detection/
│
├── app/
├── dataset/
├── models/
├── notebooks/
│   ├── 01_Dataset_Inspection.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Exploratory_Data_Analysis.ipynb
│   ├── 04_Data_Preprocessing.ipynb
│   ├── 05_Model_Training.ipynb
│   ├── 06_Model_Evaluation.ipynb
│   ├── 07_Recorded_Video_Analysis.ipynb
│   ├── 08_Live_Interview_Analysis.ipynb
│   └── 09_Streamlit_Dashboard.ipynb
├── outputs/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Development Status

| Module | Status |
|---------|--------|
| Project Planning | Completed |
| Dataset Inspection | In Progress |
| Data Cleaning | Pending |
| Exploratory Data Analysis | Pending |
| Data Preprocessing | Pending |
| Model Training | Pending |
| Model Evaluation | Pending |
| Recorded Video Analysis | Pending |
| Live Webcam Analysis | Pending |
| Streamlit Dashboard | Pending |
| Documentation | Pending |

---

## Expected Outputs

- Clean and validated dataset
- Trained facial emotion recognition model
- Model evaluation metrics
- Emotion prediction on recorded videos
- Live webcam-based emotion analysis
- Interview analysis dashboard
- Final project report

---

## Future Enhancements

- Multi-face emotion recognition
- Head pose estimation
- Eye gaze tracking
- Speech emotion recognition
- Audio and facial emotion fusion
- AI-generated interview feedback
- Cloud deployment
- Real-time analytics dashboard

---

## Installation

Clone the repository:

```bash
git clone https://github.com/komalksyp-commits/Interview-Analysis-using-Face-Detection.git
```

Move to the project directory:

```bash
cd Interview-Analysis-using-Face-Detection
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

The project is organized into multiple notebooks covering each stage of the development process, from dataset inspection to live interview analysis.

Run the notebooks sequentially:

1. Dataset Inspection
2. Data Cleaning
3. Exploratory Data Analysis
4. Data Preprocessing
5. Model Training
6. Model Evaluation
7. Recorded Video Analysis
8. Live Webcam Analysis
9. Streamlit Dashboard

---

## License

This project is intended for educational and research purposes.

---

## Author

Komal
