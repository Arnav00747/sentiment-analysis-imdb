# Sentiment Analysis on IMDb Movie Reviews 🎬

This project uses Natural Language Processing (NLP) and Machine Learning to classify IMDb movie reviews as **Positive** or **Negative**.

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- NLTK (stopwords)
- Scikit-learn (TF-IDF, Logistic Regression)
- Matplotlib, Seaborn
- WordCloud

##  Dataset
- IMDb reviews dataset (`IMDB Dataset.csv`)
## Due to GitHub’s 25 MB upload limit, the dataset is hosted externally on Google Drive.

🔗 [Click here to download IMDB Dataset (ZIP)](https://drive.google.com/file/d/1F70CNkwU1T8sYzHesC7NhSOHgHDI_HhW/view?usp=sharing)

### Steps to Use:
1. Download the `.zip` file from the link above.
2. Extract the file – you will get `IMDB Dataset.csv`.
3. Place the CSV file in the **same folder** where your Jupyter Notebook (`.ipynb`) is located.
4. Run the notebook. It will work without any issues.

##  How It Works
1. Text cleaning & preprocessing
2. Stopword removal
3. TF-IDF vectorization
4. Model training using Logistic Regression
5. Accuracy & performance metrics
6. Real-time sentiment prediction

## 📈 Accuracy
Achieved ~88% accuracy on test data

##  Example
review = "This movie was really boring and slow"
# Output: Sentiment: negative
