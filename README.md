# 📊 Amazon Review Analysis

## 🔍 Overview
This project performs **sentiment analysis** and builds a **recommendation system** using Amazon product reviews.  
- **Sentiment Analysis**: Uses **Naïve Bayes** to classify reviews as **Positive, Neutral, or Negative**.  
- **Recommendation System**: Implements **Collaborative Filtering (SVD)** to provide personalized product recommendations.  
- **Data Preprocessing**: Cleans and transforms text reviews using **TF-IDF vectorization**.  
- **Visualization**: Uses **Seaborn & Matplotlib** to analyze review distributions.  

## 🛠 Tech Stack
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: Scikit-Learn, Surprise (for recommendations)  

## 📂 Dataset
The dataset consists of **Amazon product reviews**, containing:  
- `user_id`: Unique ID for the user  
- `product_id`: Unique ID for the product  
- `review_text`: The user's review  
- `rating`: Given rating (1-5)  

## 🚀 Features Implemented
- **Data Cleaning & Preprocessing**  
- **Sentiment Classification using Naïve Bayes**  
- **Product Recommendation System using SVD**  
- **Data Visualization**  

## 📌 How to Run the Project
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/YOUR_USERNAME/Amazon-Review-Analysis.git
   cd Amazon-Review-Analysis
2. **Install Dependencies**
   pip install -r requirements.txt
3. **Run the Jupyter Notebook**
   jupyter notebook
4.**Open Amazon_Review_Analysis.ipynb and Execute the Cells**
  📊 Results & Insights
  Sentiment Analysis Accuracy: ~XX%
  Top Recommended Products for Users
  Review Sentiment Distribution
 📜 License
This project is open-source under the MIT License.
