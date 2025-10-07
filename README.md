# YouTube Sentiment Insights

A powerful Chrome extension that provides real-time sentiment analysis of YouTube video comments using machine learning.

## 🎯 Overview

YouTube Sentiment Insights helps content creators and brands understand their audience's reactions by analyzing comment sentiments in real-time. The solution combines machine learning with an easy-to-use Chrome extension interface.

## ✨ Features

- Real-time sentiment analysis of YouTube comments
- Sentiment classification (Positive/Neutral/Negative)
- Interactive visualization dashboard
- Temporal sentiment tracking
- Word cloud generation for key themes
- Automated ML pipeline with continuous training

## 🛠️ Technical Architecture

### Frontend
- Chrome Extension (JavaScript)
- Interactive charts and visualizations
- Real-time data updates

### Backend
- Flask RESTful API
- MLflow for model tracking and deployment
- DVC for ML pipeline versioning
- AWS EC2 for server hosting

### ML Pipeline
- Data preprocessing with NLTK
- TF-IDF vectorization
- LightGBM classifier
- Automated model training and evaluation
- Model versioning and tracking

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Youtube_Sentiment_Insights.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure AWS and MLflow:
```bash
aws configure
```

4. Load the Chrome extension:
- Open Chrome
- Go to `chrome://extensions/`
- Enable Developer mode
- Click "Load unpacked"
- Select the `yt-chrome-plugin-frontend` folder

## 📊 MLOps Pipeline

The project follows MLOps best practices:
- Version control with Git and DVC
- Automated model training pipeline
- Model performance tracking with MLflow
- Continuous integration and deployment
- Model registry and versioning

## 🔧 Usage

1. Open any YouTube video
2. Click the extension icon
3. View real-time sentiment analysis
4. Explore visualizations and trends
5. Export analytics data as needed

## 📈 Model Performance

- Accuracy: [Add your model's accuracy]
- F1 Score: [Add your model's F1 score]
- Precision: [Add your model's precision]
- Recall: [Add your model's recall]

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

[Shubham Sarkar] - [shubhamsarkarthe1@gmail.com]
