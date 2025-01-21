# Phonics-Master

Final project for the Building AI course

## Summary

Building AI course project

Phonics Master is an interactive application designed to help users improve their natural phonics skills. Through engaging lessons, pronunciation exercises, and gamified learning, users can easily master English letter sounds, letter combinations, and gradually enhance their reading and pronunciation abilities.

## **Features**

- **Letter and Letter Combination Sounds**: Learn the pronunciation rules of letters and common letter combinations.
- **Phonics Practice**: Strengthen pronunciation skills through word-reading exercises.
- **Syllable Division Practice**: Learn how to divide words into syllables and pronounce them correctly.
- **Stress Position Training**: Master word stress placement for accurate pronunciation.
- **Listening and Spelling Integration**: Practice spelling words based on their pronunciation.
- **Gamified Learning**: Improve learning motivation through fun games.
- **Personalized Learning Plan**: Receive tailored learning content based on your skill level.
- **Pronunciation Comparison and Feedback**: Record your pronunciation, compare it with the standard, and receive improvement suggestions.
- **Learning Progress and Achievement System**: Track your progress and stay motivated.
- **Community and Sharing**: Join a learning community to share experiences and participate in challenges.

## **Tech Stack**

- **Frontend**: React Native (Cross-platform mobile development)
- **Backend**: Node.js + Express (API services)
- **Database**: Firebase / MongoDB (User data storage)
- **Pronunciation Features**:
  - Text-to-Speech (TTS): Google TTS or Amazon Polly
  - Speech-to-Text (STT): Google Speech API
- **Data Analysis**: Python (Machine learning for pronunciation analysis)

## **Installation and Setup**

### **Prerequisites**

- Node.js (v16+)
- npm or yarn
- React Native development environment (Android Studio / Xcode)
- Firebase or MongoDB account (for database)

### **Steps**

1. **Clone the Repository**

   bash

   ```
   git clone https://github.com/panghu1569/phonics-master.git
   cd phonics-master
   ```

2. **Install Dependencies**

   bash

   ```
   npm install
   # or
   yarn install
   ```

3. **Configure Environment Variables**

   - Create a `.env` file in the root directory and add the following:

     ```
     API_KEY=your_firebase_or_mongodb_api_key
     TTS_API_KEY=your_google_tts_api_key
     STT_API_KEY=your_google_speech_api_key
     ```

4. **Run the Project**

   - Start the development server:

     bash

     ```
     npm start
     # or
     yarn start
     ```

**Project Structure**

    phonics-master/
    ├── assets/               # Static assets (images, audio, etc.)
    ├── components/           # Reusable React components
    ├── screens/              # Application screens
    │   ├── HomeScreen.js     # Home screen
    │   ├── LearnScreen.js    # Learning screen
    │   ├── GameScreen.js     # Game screen
    │   └── ProfileScreen.js  # Profile screen
    ├── services/             # Backend services and API calls
    │   ├── auth.js           # User authentication
    │   ├── tts.js            # Text-to-speech service
    │   └── stt.js            # Speech-to-text service
    ├── utils/                # Utility functions
    │   ├── phonicsRules.js   # Phonics rules
    │   └── syllableSplit.js  # Syllable division utility
    ├── App.js                # Application entry point
    └── README.md             # Project README file

## **License**

This project is licensed under the [MIT License].

## **Contact**

- **Developer**: Your Name
- **Email**: [wy_kim@126.com](mailto:your.email@example.com)
- **GitHub**: [panghu1569](https://github.com/panghu1569)
- **Project Link**: [Phonics Master](https://github.com/panghu1569/phonics-master)

## **Acknowledgments**

- Thanks to [React Native](https://reactnative.dev/) for the cross-platform development framework.
- Thanks to [Google TTS](https://cloud.google.com/text-to-speech) and [Google Speech API](https://cloud.google.com/speech-to-text) for pronunciation features.
- Thanks to all contributors and users for their support!
