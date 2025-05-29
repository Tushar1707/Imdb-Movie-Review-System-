# 🎬 IMDb Movie Review System

An intelligent web-based movie recommendation and review system that allows users to check movie ratings, cast details, and get personalized recommendations using machine learning.

## 🔍 Features

- ⭐ **Movie Ratings & Reviews**: View IMDb-style movie ratings and submit your own reviews.
- 🎭 **Cast Information**: See detailed cast and crew info for each movie.
- 🤖 **Recommendation Engine**: Get smart movie suggestions based on user sentiment and similarities.
- 🧠 **ML-Powered Sentiment Analysis**: Integrated with scikit-learn & pandas to analyze and classify reviews.

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **ML Tools**: scikit-learn, Pandas, NLP techniques
- **Deployment**: Localhost / Can be hosted on Render, Heroku, etc.

## 📁 Project Structure

├── app.py # Flask application entry point
├── templates/ # HTML templates
│ └── index.html
├── static/ # CSS & JS files
│ ├── style.css
│ └── recommend.js
├── transform.pkl # Serialized machine learning model
├── movies.csv # Dataset for recommendations
└── README.md # This file



## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Tushar1707/Imdb-Movie-Review-System-.git
   cd Imdb-Movie-Review-System-
Create a virtual environment and install dependencies:



pip install -r requirements.txt
Run the app:


python app.py
Open your browser and go to http://localhost:5000



📌 Future Improvements
User authentication system

Review moderation with profanity filter

Deploy on cloud with database integration

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

Developed with ❤️ by Tushar Solanki
