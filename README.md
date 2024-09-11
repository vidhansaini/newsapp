# 📰 News Teller (NewsApp)

## 📖 Project Overview

News Teller (or NewsApp) is a Python-based project that allows users to fetch and listen to the latest news headlines based on their chosen country and news category. It uses NewsAPI to retrieve top headlines and pyttsx3 to convert the text to speech for an interactive experience.

## 🎯 Features

**🌍 Country-based news** : Fetch news from different countries by providing the country name.

**🗂️ Category filtering** : Choose from various news categories like business, entertainment, health, science, technology, and more.

**🗣️ Text-to-speech support** : Listen to the latest headlines with built-in voice support using pyttsx3.

**🔄 Interactive** : Allows continuous querying until the user decides to exit.

**🏗️ Scalable** : Easily expandable by adding more features like fetching news from multiple APIs, or supporting multiple languages.

## 🛠️ Technologies Used

- Python 3: Core language

- News API: To fetch the latest news headlines

- pyttsx3: For text-to-speech functionality

- pycountry: For handling country names and codes


## ⚙️ How It Works

- The user provides a country name.

- The app fetches the respective country code using pycountry.

- The user chooses a news category (e.g., Business, Technology, etc.).

- The app retrieves the latest news from NewsAPI for the selected country and category.

- The headlines are displayed and spoken aloud via pyttsx3.

## 🧩 Project Structure

newsapp/

│

├── newsapp.py                                # Main script to run the application

├── requirements.txt                          # List of required libraries

└── README.md                                 # Project documentation


## 📝 Requirements

To run this project, make sure you have the following libraries installed:

- newsapi-python
- pyttsx3
- pycountry

## 🗂️ News Categories

You can choose from the following news categories:
- Business
- Entertainment
- General
- Health
- Science
- Technology

## 🔑 API Key Setup

This project uses NewsAPI to fetch news data. You will need to sign up for a free API key:

- Go to NewsAPI.
- Create an account and get your API key.
- Replace the placeholder in the script with your API key:

- newsapi = NewsApiClient(api_key='your_api_key_here')

## 💡 Future Enhancements

- 🔊 Support for multiple languages in news reading.

- 🌍 Option to fetch news from multiple countries at once.

- 📰 Ability to filter news by more granular criteria, like keyword searches.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## 🏅 Acknowledgements

- NewsAPI for providing an easy way to access global news.

- pyttsx3 for making text-to-speech integration seamless.

## 📜 License

This project is licensed under the MIT License.
