# 🎬 Netflix Content Clustering and Analysis

This project involves **unsupervised machine learning techniques** to analyze and cluster Netflix titles based on various metadata such as title, genre, cast, director, and release year. The goal is to uncover hidden patterns in the content library using **textual and numerical features**, and group similar content using clustering algorithms.

---

## 📌 Project Objective

- Explore and analyze Netflix content data.
- Understand the **distribution of content across countries and types**.
- Use **TF-IDF feature engineering** to process textual metadata.
- Apply **KMeans** and **Agglomerative Clustering** to group similar titles.
- Derive actionable insights like content trends, popular genres, and cluster themes.

---

## 📁 Dataset

- **Source**: [`netflix_titles.csv`](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Features used**:
  - Title
  - Director
  - Cast
  - Country
  - Date Added
  - Release Year
  - Rating
  - Duration
  - Genre
  - Description

---

## 🔧 Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK / TextVectorization (TF-IDF)
- Google Colab (for notebook development)

---

## 📊 Key Steps & Methodology

### 1. **Exploratory Data Analysis**
- Checked missing values, value counts, and visualized content types and countries.
- Analyzed how content types (TV Shows vs Movies) changed over time.

### 2. **Data Preprocessing**
- Cleaned null values in text features (director, cast, etc.)
- Created derived columns like `year_added`, `duration_int`, `type_encoded`.

### 3. **Text Feature Engineering (TF-IDF)**
- Combined `title`, `description`, `cast`, `listed_in`, and `director` into a new column.
- Applied **TF-IDF Vectorizer** to convert textual data into numerical features.

### 4. **Clustering**
- Used **KMeans** (with Elbow Method) to determine optimal clusters.
- Applied **Agglomerative Clustering** as a second algorithm for evaluation.

### 5. **Cluster Profiling**
- Grouped content by cluster and observed common patterns.
- Visualized clusters using PCA for 2D projection.

---

## 💡 Key Insights

- **TV Shows have increased** significantly in recent years compared to movies.
- Most content comes from the **United States**, followed by India and UK.
- Certain clusters are heavily composed of **international reality shows**, while others contain **crime dramas** or **comedy films**.
- Clustering was successful in identifying **thematic groupings** based on text features.

---

## 📁 File Structure
Netflix-Content-Analysis/
│
├── Netflix_Clustering_Project.ipynb # Main notebook (Colab)
├── netflix_titles.csv # Dataset
├── README.md # Project overview (this file)

---

## 🧠 Future Work

- Deploy as a recommendation engine.
- Perform sentiment analysis on descriptions.
- Integrate user ratings or watch-time data for deeper clustering.

---

## 📎 Submission Details

- ✅ Code Notebook (.ipynb)
- ✅ PowerPoint Slides (.pptx)
- ✅ Project Report / Summary
- ✅ GitHub Link:

---

## 🔗 Connect

Feel free to fork, star ⭐, or connect if you found this interesting!

