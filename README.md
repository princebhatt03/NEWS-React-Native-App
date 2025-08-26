# React-Native-Expo-News-App
NewsApp – React Native

NewsApp is a modern mobile application built with React Native that provides users with the latest news from multiple categories and sources. It features an intuitive UI, offline support, and fast performance for a seamless reading experience.

Table of Contents

Features

Demo

Tech Stack

Installation

Usage

Folder Structure

API Integration

Contributing

License

Features

Browse latest news articles from multiple categories: Technology, Sports, Business, Entertainment, Health, Science, and more.

Search for news articles by keyword.

Bookmark favorite articles for offline reading.

Pull-to-refresh to get the latest news.

Clean and responsive UI compatible with Android and iOS.

Dark mode support.

Demo

Tech Stack

Framework: React Native

State Management: Redux / Context API

Navigation: React Navigation

API: NewsAPI
 or other RESTful APIs

Styling: Styled Components / React Native Paper / Tailwind CSS

Others: Axios for API calls, AsyncStorage for caching

Installation

Clone the repository

```
git clone <your_github_repo_url>
cd <folder_name>
```

Install dependencies

```
npm install 
```

Run the app
```
npx expo start
```

Usage

Launch the app on your device or emulator.

Navigate between categories using the bottom tab or side menu.

Tap on an article to read full content.

Use the search bar to find articles by keyword.

Bookmark articles to view later, even offline.

Folder Structure
```
newsapp/
├── android/
├── ios/
├── src/
│   ├── assets/
│   ├── components/
│   ├── screens/
│   ├── navigation/
│   ├── redux/ or context/
│   ├── api/
│   ├── utils/
│   └── App.js
├── .env
├── package.json
└── README.md
```
API Integration

This app uses NewsAPI
 to fetch the latest news. Example API call:

import axios from 'axios';

const fetchNews = async () => {
  const response = await axios.get(
    `https://newsapi.org/v2/top-headlines?country=us&apiKey=${process.env.NEWS_API_KEY}`
  );
  return response.data.articles;
};

### 👨‍💻 Developer
Prince Bhatt

📧 Email: princebhatt316@gmail.com

🌐 Portfolio: [Prince Bhatt](https://princebhatt03.github.io/Portfolio)

💼 GitHub: [princebhatt03](https://github.com/princebhatt03)

💬 LinkedIn: [Prince Bhatt](https://www.linkedin.com/in/prince-bhatt-0958a725a/)

📄 License

This project is created and owned by Prince Bhatt

✨Thank you for connecting...
