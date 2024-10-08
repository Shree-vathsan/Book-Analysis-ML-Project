# 📚 Amazon Bestselling Books Analysis & Interactive Dashboard 🚀

Welcome to the Amazon Bestselling Books Analysis & Dashboard project! This project leverages machine learning, data visualization, and web development to provide insights into Amazon's bestselling books. Using Python libraries like Pandas, Scikit-learn, Plotly, and Dash, we have created a comprehensive analysis tool and an interactive dashboard for book trends.

## 🎯 Project Objectives
- **Predict Book Genres:** Build a machine learning model to predict whether a book is Fiction or Non-Fiction based on its attributes.
- **Visualize Insights:** Create interactive visualizations to explore top authors, genres, ratings, and more.
- **Interactive Dashboard:** Develop a dynamic dashboard using Dash to make data exploration more intuitive.

## 🚀 Features
- **Logistic Regression Model:** Predicts whether a book is Fiction or Non-Fiction based on features like title, user rating, reviews, and price.
- **Interactive Dashboard:** Visualize top authors, genre distribution, and rating trends. Filter by author and year for more granular analysis.
- **TF-IDF Analysis:** Text analysis of book titles using the TF-IDF technique to better understand common terms in bestselling books.
- **Data Visualizations:** Bar charts, pie charts, and scatter plots for deeper insight into bestselling books.

## 🛠️ Installation Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/amazon-bestselling-books.git
   cd amazon-bestselling-books
2. **Install Required Libraries**
   ```bash
   pip install -r requirements.txt
3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook
4. **Launch the Interactive Dashboard**
   ```bash
   python app.py
   
## 🧠 Machine Learning Model
**We used Logistic Regression to predict book genres based on:**
- Book Title (TF-IDF Vectorization)
- User Ratings
- Reviews
- Price
- **The model achieved an accuracy of X%, with the following evaluation metrics:**
- Precision: X%
- Recall: X%
- F1-Score: X%

## 📊 Dashboard Overview
**Key Visualizations:**
- Top 10 Authors: A bar chart showing the authors with the highest number of bestselling books.
- Genre Distribution: A pie chart representing Fiction vs. Non-Fiction distribution.
- Rating vs. Reviews: Scatter plot analyzing the relationship between user ratings and the number of reviews.
- Interactive Filters: Select authors or filter by publication year to refine the analysis.
  
## 🚀 Future Enhancements
**To make this project more robust and feature-packed, we propose the following additions:**
- **Advanced Predictive Models:** Explore and implement more sophisticated models like Random Forests or Neural Networks to improve genre prediction accuracy.
- **Sales Trend Analysis:** Investigate how external factors such as movie adaptations or awards affect book reviews and ratings.
- **Additional Data:** Incorporate additional data like book length, publisher, or user demographics to enrich the analysis.
- **Extended Dashboard Features:** Add filtering options for price, user rating, and reviews. Include trend lines for year-over-year performance.
  
## 📁 Project Structure
**Here's a quick overview of the files in this repository:**
- notebooks/: Contains the Jupyter notebooks for data analysis and model building.
- app.py: The Python file that launches the interactive Dash dashboard.
- data/: Folder containing the dataset used for analysis.
- requirements.txt: List of Python packages and dependencies required to run the project.

## 📚 Dataset
**The dataset used for this analysis is Amazon's Bestselling Books (2009 - 2019), containing the following features:**
- **Name:** The title of the book.
- **Author:** The name of the author.
- **User Rating:** Average user rating of the book.
- **Reviews:** Number of reviews received.
- **Price:** Price of the book in USD.
- **Year:** Year of publication.
- **Genre:** Whether the book is Fiction or Non-Fiction.

## 👤 Author
**SHREEVATHSAN R**
- **LinkedIn:** https://www.linkedin.com/in/shreevathsan-r-91183625b
- **Github:** https://github.com/Shree-vathsan

## 🔗 Contributing
We welcome contributions! Please feel free to submit a Pull Request or open an issue for any improvements, bugs, or new features.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
