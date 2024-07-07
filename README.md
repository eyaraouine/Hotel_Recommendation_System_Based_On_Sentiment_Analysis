# Hotel Recommentation Based On Sentiement Analysis Project Overview 
## Description 
This project aims to develop a hybrid hotel recommendation system that leverages both user profiles and the preferences of similar users to deliver highly personalized hotel recommendations by harnessing data from social media user interests and hotel reviews from Booking.com. The system includes the extraction and clustering of user interests, sentiment analysis of hotel reviews using deep learning models, and a web application built with Django and a Flask API for real-time recommendations.
## Project Structure 
- **Django_Web_App/**: Directory containing the Django web application for the hotel recommendation system.
- **User_Interests_And_FlaskAPI.ipynb**: Notebook for extracting and clustering user interests from Instagram posts, and implementing the Flask API that serves as the backend connecting with the Django web application.
- **Hotel_Reviews_Sentiment_Analysis.ipynb**: Notebook for performing sentiment analysis on hotel reviews using BiLSTM and GloVe embeddings.
- **Image_Scraping.ipynb**: Notebook for scraping hotel images and details from Booking.com.
- **Project Report.PDF**: This file includes a comprehensive project report covering key elements such as general introduction, business understanding, data preparation, modeling and evaluation, deployment details, conclusions, and future perspectives.
- **Project Presentation.PDF**: Completed project presentation
  
## Key Components 
### 1. Data Extraction and Clustering 

-  Scripts for extracting user data from social media and clustering their interests.
-  Extracts user data including username, user ID, followers count, posts count, posts, and interests.
-  Clusters user interests to generate meaningful groups using cosine similarity matrix .

### 2. Sentiment Analysis 

- Implementation of sentiment analysis on hotel reviews using deep learning models.- 
- Performs sentiment analysis ans aspects extraction using NLP, BiLSTM and GloVe embeddings.
- **Models**: Pre-trained BiLSTM model files and GloVe embeddings.

### 3. Image Scraping 

- Scripts for scraping images and information of hotels from Booking.com.
- Scrapes hotel images and details such as names, URLs, and ratings.

### 4. Flask Backend 

- Flask API to connect the backend processes with the Django web application.
  
### 5. Web Application 
 **Features**:
- A Secure and intuitive authentication interface ensures that each user accesses personalized recommendations tailored to their profile.
- Personalized Hotel List recommended specifically for the authenticated user.
- Interactive visualizations with pie charts providing a comprehensive view of trends within user groups sharing similar preferences.
- A Rubric showcasing the top 5 users most similar to the authenticated user within the same cluster, fostering a sense of community and shared preferences among users.

## Installation

 **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Hotel-Recommendation-System-based-on-sentiment-analysis.git
   ```
## Project Demo Video
https://youtu.be/CscYpiVqiJA
