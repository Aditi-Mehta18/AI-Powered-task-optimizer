# AI-Powered-task-optimizer
The AI-Powered Task Optimizer is an intelligent employee emotion and mood analysis system that enhances productivity and well-being in the workplace. It uses Natural Language Processing (NLP) and AI-based emotion recognition models to detect emotions from text, images, and video, and recommends tasks or alerts HR when stress or negative moods are identified.

Features

✅ Text Emotion Detection: Detects emotions from user-written messages.

🖼️ Image Emotion Detection: Analyzes facial expressions in images to predict emotions.

🎥 Video Emotion Detection: Uses real-time or recorded video to assess user mood.

📋 Task Recommendation: Suggests tasks suitable for the user's current emotional state.

📈 Mood Tracking: Continuously monitors and logs emotional states over time.

🚨 Stress Detection: Flags stress indicators and initiates alerts.

🧠 Team Mood Analytics: Aggregates mood data to provide insights at the team level.

Modules

The application consists of the following modules accessible via a dropdown:

✅ Text Emotion Detection

✅ Image Emotion Detection

✅ Video Emotion Detection

✅ Task Recommendation

✅ Mood Tracking

✅ Stress Detection

✅ Team Mood Analytics

🛠️ Technologies Used

🎨 Frontend

Streamlit: Used for building the interactive web interface, including module selection, input fields, and real-time output display.

🧠 Backend

Python: Core programming language for backend logic, model integration, and API handling.

🤖 Machine Learning Models

1. Text Emotion Classifier

Built using NLP techniques (e.g., TF-IDF, Word2Vec, or transformer-based models like BERT).

Classifies emotions such as joy, anger, sadness, fear, and surprise from textual input.

2. Image/Video Emotion Detectors
   
Based on Convolutional Neural Networks (CNNs).

May utilize pretrained models such as FER (Facial Emotion Recognition) or DeepFace.

Extracts facial features from images or video frames to predict emotional state.

3. Stress and Mood Classifiers
   
Uses patterns in text, facial expressions, or historical emotion data to detect:

Libraries:

transformers, scikit-learn, opencv, deepface, pandas, matplotlib

Installation:

Clone the repository:

git clone https://github.com/your-username/ai-task-optimizer.git
cd ai-task-optimizer

📦 Install the Dependencies

Make sure you have Python installed (preferably Python 3.8+). Then, run the following command to install all required packages:

pip install -r requirements.txt

▶️ Run the Application

Launch the Streamlit web app using:

streamlit run app.py
🧪 Sample Usage

Select a Module

From the left sidebar, choose a module like Text Emotion Detection, Image Emotion Detection, or Task Recommendation.

Enter Input

For text-based analysis, type a message (e.g.):

Why does no one ever listen to me? I'm furious!

Click Detect Emotion

Hit the Detect Emotion button to analyze the input.

View Results

See the predicted emotion (e.g., anger) displayed below.

Follow-up Actions

Use the predicted emotion to recommend suitable tasks.

Trigger alerts or stress analysis via other modules (like Stress Detection or Team Mood Analytics).



Screenshots

Text Emotion Detection Module

![WhatsApp Image 2025-04-19 at 17 46 14_dde757cc](https://github.com/user-attachments/assets/83fca5a9-33a6-4ba1-9e78-606d68e6eedb)
![WhatsApp Image 2025-04-19 at 17 46 14_d0315a73](https://github.com/user-attachments/assets/83dd1adb-1653-4ebc-900a-75073e57b778)



Contributors

Aditi

