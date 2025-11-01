# 🕵️‍♂️ Fake Review Detection using Python

## 📖 Overview
This project analyzes product reviews and detects potentially fake or suspicious ones using rule-based scoring.

## 🧠 Technologies Used
- Python 🐍
- Pandas & NumPy
- Matplotlib (Visualization)
- TextBlob (for text analysis)
- Google Colab (Development Environment)

## ⚙️ Key Features
- Cleans and processes Amazon-style review data
- Adds custom features like review length, word count, exclamation marks, and promo phrases
- Detects suspicious users (bursty reviewers and always-5-star users)
- Flags fake reviews using a combined scoring system
- Visualizes patterns using bar charts

## 📊 Outputs
- Rating Distribution Chart
- Suspicious Score Distribution Chart
- List of Top 15 Most Suspicious Reviews

## 🚀 How to Run
1. Download the notebook: `Fake_Review_Detection.ipynb`
2. Open it in [Google Colab](https://colab.research.google.com/)
3. Upload your review dataset and run all cells.

## 💡 Example
| reviewerID | productID | rating | suspicious_score |
|-------------|------------|--------|------------------|
| U001 | P010 | 5 | 10 |
| U007 | P002 | 5 | 8 |

## 🧩 Author
Kriti Tiwari 
⭐ *Feel free to fork or star this project if you like it!*
