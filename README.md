# Bollywood-Celebrity-You-Look-Alike

# Overview
Welcome to the Celebrity Face Match App! This project uses a dataset downloaded from Kaggle, containing 8,500 photos of 100 Bollywood celebrities. The goal is to determine which celebrity matches the most with a user-uploaded image. The process involves face extraction using the MTCNN detector, feature extraction using the Keras-VGGFace model, and similarity comparison using cosine similarity.

# Workflow
# Face Extraction 
Utilizing the MTCNN detector, the app extracts the face portion from user-uploaded images. This step is crucial for accurate celebrity matching.

# Feature Extraction
The Keras-VGGFace model is employed to extract detailed facial features from both the dataset images and the user's image.

# Cosine Similarity: 
The app calculates the cosine similarity between the features of the user's image and those of celebrities in the dataset. The celebrity with the highest cosine similarity is recommended as the best match.

# Technologies Used
MTCNN detector for face extraction
Keras-VGGFace for feature extraction
Cosine similarity for matching
Streamlit for app deployment
# Usage
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Run the Streamlit app with streamlit run app.py.
Upload your image to find your Bollywood celebrity match!

Enjoy exploring the world of Bollywood celebrities with the Celebrity Face Match App!
