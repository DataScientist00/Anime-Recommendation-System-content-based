
# 🎥 Anime Recommendation System with TF-IDF

A content-based machine learning project that recommends similar anime shows based on genre using TF-IDF vectorization and cosine similarity. Built and visualized using pandas, seaborn, and matplotlib.

## Watch the Video 📺

[![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Video-red?logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/CwfkSYxl6xc)
---

![Image](https://github.com/user-attachments/assets/2e8d8f6b-2bd6-4c8c-bebc-bfee06fc21ba)

## 🎯 Project Overview
This project includes:
- **Dataset**: Anime metadata and ratings dataset (from Kaggle).
- **Notebook**: Jupyter notebook for preprocessing, analyzing, and building the recommender.
- **Recommendation System**: A TF-IDF based system that computes similarity between anime genres.
- **Streamlit App** : Interactive app to enter your favorite anime and get similar recommendations.

---

## 🗂 Project Structure

```
├── dataset.txt                              # Anime dataset used for analysis and recommendations  
├── genre-based-anime-recommender-system.ipynb  # Jupyter Notebook for EDA and recommender system  
├── app.py                                   # Streamlit web app for anime recommendations  
├── requirements.txt                         # Project dependencies  
├── README.md                                # Documentation (you're reading this!)

```


## 🚀 How to Run the Project

### 1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/Anime-Recommendation-System-content-based.git
cd Anime-Recommendation-System-content-based
```

### 2. **Install Required Dependencies**
Create a Python virtual environment and install dependencies:
```bash
pip install -r requirements.txt
```

### 3. **Run the Streamlit App**
```bash
streamlit run app.py
```

---

## 📈 Workflow Details

### 1. **Dataset**
The dataset includes:
- `anime.csv`: Contains `anime_id`, `name`, `genre`, `type`, `episodes`, `rating`, and `members`.
- `rating.csv`: Contains `user_id`, `anime_id`, and `rating`.

### 2. **Data Processing**
- Cleaned missing data in genres and ratings.
- Split and analyzed multi-label genres.
- Counted and visualized genre frequency.

### 3. **Recommendation Logic**
- Used **TF-IDF** vectorization on anime genres.
- Computed **cosine similarity** between TF-IDF vectors.
- Built a function to fetch top-N similar anime based on genre similarity.

---

## 🛠 Technologies Used
- **Languages**: Python
- **Libraries**:
  - Machine Learning: Scikit-learn
  - Data Handling: Pandas, NumPy
  - Visualization: Seaborn, Matplotlib
  - App Framework: Streamlit
- **Tools**: Jupyter Notebook, Git

---

## 📊 Visual Insights
- Most common anime genres
- Rating distributions
- Genre combinations
- WordCloud of genres

📷 Preview of Streamlit App

![Image](https://github.com/user-attachments/assets/34bc3bc6-a25b-414e-a23a-ba2be6788229)
---

## 🤝 Contributing
Contributions are welcome!
1. Fork the repo
2. Create a branch
3. Submit a Pull Request

---

## 💡 Acknowledgments
- Kaggle for the anime dataset.
- Streamlit and Scikit-learn for powering the recommender system.

---

## 📞 Contact
- Email: nikzmishra@gmail.com  

---

**⭐ If you liked this project, don't forget to star the repo! ⭐**
