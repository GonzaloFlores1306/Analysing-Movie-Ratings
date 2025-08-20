# Analyzing & Predicting MovieRatings
This project presents a complete **data analysis and machine learning pipeline** to explore and predict movie ratings based on various features such as title, genre, and year.

---

## 📦 Dataset
The dataset was sourced from a Kaggle file containing metadata on various films:
🔗 [**Movies Dataset**](https://www.kaggle.com/datasets/shivvm/popular-movies-imdb-reviews-dataset/code)

---

## 🛠️ Tools and Technologies Used
- **Programming Language:** Python  
- **Development Environment:** Jupyter Notebook (via VSCode / Anaconda)  
- **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-learn, NumPy  

---

## 🧹 Data Preprocessing and Cleaning
- Merging of separate movie data files into a unified dataset  
- Handling of missing values and data type corrections  
- Feature engineering: extraction of categorical and numerical variables (e.g., one-hot encoding for `genre`)  
- Filtering out outliers and formatting inconsistent entries  

---

## 🔍 Exploratory Data Analysis (EDA)
- Analysis of rating distribution and trends over the years  
- Exploration of genres with the highest average ratings  
- Correlation analysis between `rating` and other numerical features  
- Ranking of top-rated and worst-rated films  
- Analysis of genre frequency and rating per genre  

---

## 📊 Visualizations
- **Bar charts** showing average ratings per genre  
- **Pie charts** indicating percentage of each genre  
- **Histograms** to visualize rating distribution  
- **Line plots** showing rating trends over time  
- **Scatter plots** to compare features like year vs. rating  

---

## 🤖 Machine Learning Model
A **Random Forest Regressor** was trained to predict the official rating (`rating`) of a movie based on genre and year:

- Data was split into **training (80%)** and **test (20%)** sets  
- Used **OneHotEncoding** for categorical data (`genre`)  
- Performance metrics:
  - **RMSE:** `0.28`  
  - **R² Score:** `0.79`  
- The pipeline was built using `ColumnTransformer` and `Pipeline` from `sklearn`  

---

## 🔮 Prediction
The model can be used to predict a movie’s expected rating given its genre and release year.

---

## 🧠 Key Questions Answered
- What genres receive the highest average ratings?  
- Are there certain years with more highly-rated movies? 
- Can we predict the rating of a movie using its genre and year?
- What genres dominate the dataset?
- Are there patterns in how ratings evolve across time?

---

✅ This project demonstrates the integration of EDA, data cleaning, and machine learning to extract insights and make predictions on real-world entertainment data. It showcases the full data science pipeline from raw CSV files to model deployment-ready predictions.

[Watch the full project here](https://github.com/GonzaloFlores1306/MovieRatings/blob/main/Analysis_Movie_Reviews.ipynb)

---

✅ This project highlights the power of Python and Jupyter for real-world data analysis and storytelling with data.
