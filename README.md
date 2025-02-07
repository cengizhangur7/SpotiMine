# SpotiMine

## 📌 Project Description

This project aims to develop an AI-powered music recommendation system. The system analyzes the user's emotional state through facial expressions and collects contextual data through a chatbot to provide music recommendations that best match their current mood. Music recommendations can be added to user playlists or played directly through Spotify API integration.

This project aims to provide a more dynamic and personalized experience by overcoming the limitations of traditional music recommendation systems. It offers a continuously evolving recommendation mechanism through emotion analysis, chatbot interaction, and user feedback.

## 🎯 Project Goals

- **Emotion-based music recommendation:** Makes recommendations by analyzing the user's current emotional state from facial expressions.
- **Chatbot integration:** Contextual data collection and customization of music recommendations with OpenAI GPT-4o powered chatbot.
- **Spotify API integration:** Synchronization of recommended music with users' Spotify accounts and adding to playlists.
- **Statistics and analysis:** Providing visual reports on users' emotional changes and music preferences.

## 🚀 Features

- 🎭 **Emotion Analysis:** Uses DeepFace library to determine emotional state from user's facial expressions.

- 💬 **Chatbot Interaction:** OpenAI GPT-4o powered chatbot offers music recommendations based on user's mood.

- 🎵 **Spotify Integration:** Includes API connection that allows users to listen to recommended music through Spotify.
  <sub>

  - OAuth 2.0 Authorization: Ensures secure authentication with Spotify accounts using PKCE flow.
  - Playlist Creation & Management: Automatically generates and updates personalized playlists for users.
  - Real-time Music Access: Allows seamless playback of recommended songs directly within the application.
  - User Preference Learning: Tracks user feedback on recommendations to refine future suggestions.
  </sub>

- 📊 **Statistics & Feedback:** Provides statistical analysis based on users' music preferences and interactions.

- 📌 **Real-time Analysis:** Updates recommendations as user facial expressions change.

- 🔒 **Secure Login & Data Storage:** User information is securely stored with Firebase authentication and data management.

- 🌤️ **Weather-Based Music System:** The system combines real-time weather data with AI-powered chatbot recommendations.
  <sub>

  Weather Integration:
  - Real-time weather updates every 30 minutes via AccuWeather API
  - Tracks temperature, conditions, time of day, and weather intensity
  - Location-based weather monitoring
  - Seamless adaptation to weather changes

  Dynamic AI Recommendations:
  - Real-time Chatbot Responses
  - AI analyzes weather data every 10 seconds
  - Generates unique, contextual music suggestions
  - Never repeats the same recommendation twice
  - Personalizes message tone based on weather conditions
  </sub>

- 🎯 **Direct Music Recommendation:** Quick and efficient music suggestions through text-based chatbot interaction.
  <sub>
  
  Natural Language Processing:
  - Text-based music requests
  - Context-aware responses
  - Personalized conversation flow
  - Intelligent music matching
  </sub>

## 🛠️ Technologies Used
- **Flutter & Dart:** Mobile application development.
- **Python & TensorFlow:** Emotion analysis model.
- **OpenAI GPT-4o:** Chatbot.
- **Spotify API:** Music recommendations and playlist creation.
- **Firebase:** User data management and authentication.

## 📷 Screenshots
The application consists of several key interfaces:

### 1. Authentication Flow
<div align="center">
  <img src="README Photos/AuthenticationFlow.png" width="600">
</div>

### 2. Home Page
<div align="center">
  <img src="README Photos/HomePageOld.png" width="200">
  <img src="README Photos/HomePageNew.png" width="200">
</div>

### 3. Spotify Integration
<div align="center">
  <img src="README Photos/SpotifyAuth.png" width="600">
</div>

### 4. Emotion-Based Music Recommendation
<div align="center">
  <img src="README Photos/EmotionBasedRecommendation.png" width="600">
</div>

### 5. Direct Music Recommendation
<div align="center">
  <img src="README Photos/DirectMusicRecommendationPage.png" width="200">
</div>

### 6. Statistics Page
<div align="center">
  <img src="README Photos/StatisticPage.png" width="600">
  <img src="README Photos/TopStatistic.png" width="600">
</div>

### 7. User Page
<div align="center">
  <img src="README Photos/UserPage.png" width="800">
</div>

## 🔒 Security & Privacy Note
The source code of this project is not shared due to security and privacy reasons. However, this README file is provided for detailed information about the project.

## 📈 Future Developments
- **Voice Command Support:** Adding a voice assistant feature for users to communicate verbally with the chatbot.
- **Real-time Emotion Tracking:** Developing a system that tracks changes in user's mood in real-time.
- **In-car Assistant:** Integration of a system that offers music recommendations suitable for the driver's mood in the vehicle.
- **Personal Music Preference Learning:** Continuously improving the recommendation model by analyzing user's music preferences.



