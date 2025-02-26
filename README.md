# Project Overview

In healthcare settings, doctors and nurses spend a lot of time manually entering patient information into assessment forms. This can be time-consuming, error-prone, and distracting for medical professionals.

Our project aims to solve this issue by developing a voice assistant that listens to doctor-patient conversations, automatically transcribes the speech, and fills out the required medical assessment forms. This will help:
- Reduce manual data entry
- Improve accuracy in patient records
- Allow healthcare professionals to focus more on their patients

# Features

- Speech-to-Text Processing: Converts doctor-patient conversations into text using advanced AI models.
-  NLP for Medical Term Extraction: Identifies key medical terms and maps them to the correct form fields.
-  Form Auto-Fill: Automatically fills healthcare assessment forms based on extracted information.
-  User-Friendly Interface: Simple and intuitive UI for healthcare professionals to review and edit transcriptions.
-  Cloud Storage & Integration: Securely stores transcriptions and integrates with existing healthcare systems.

# Tech Stack

- Programming Language: Python
- Machine Learning & AI: TensorFlow, OpenAI Whisper, Google Speech API
- NLP Frameworks: NLTK, SpaCy
- Backend: FastAPI, Flask
- Frontend: React.js
- Database: PostgreSQL, Firebase
- Cloud Services: Microsoft Azure / AWS

# Project Structure

📦 voice-assistant-healthcare  
 ┣ 📂 data                # Medical speech datasets & preprocessed files  
 ┣ 📂 models              # Trained speech-to-text and NLP models  
 ┣ 📂 backend             # API for handling speech data storage & integration  
 ┣ 📂 frontend            # UI for reviewing and editing transcriptions  
 ┣ 📜 requirements.txt    # Dependencies and packages  
 ┣ 📜 README.md           # Project documentation    
 ┗ 📜 main.py             # Main script to run the assistant  

