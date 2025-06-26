# Restaurant-Reviews-Sentiment-Analysis
This project performs multi-class sentiment analysis on restaurant reviews, classifying feedback as Positive, Neutral, or Negative. Models suite primarily include Logistic Regression, LSTM, BiLSTM, and BiGRU.

---

### Project Files:

* `notebooks/your_sentiment_analysis.ipynb`: The Python notebook containing all data preprocessing, model training, and evaluation steps.
* `data/Restaurant_reviews_corrected.csv`: The original raw dataset used for the analysis.
* `data/sentiment_analysis_data.csv`: This file contains the full dataset with predicted sentiment labels from the best-performing model, ready for immediate use in Power BI.
* `data/model_accuracies.csv`: Summarizes the performance (accuracy) of all trained models, allowing for a clear comparison.
* `powerbi/Restaurant_Sentiment_Dashboard.pbix`: The Power BI Desktop file for the interactive dashboard.

---

### Model Performance Summary

This table summarizes the accuracy achieved by each predictive model on the test set:

| Model             | Accuracy   |
| :---------------- | :--------- |
| LSTM              | 0.8500     |
| BiLSTM            | 0.8539     |
| BiGRU             | 0.8496     |
| Logistic Regression | 0.8533     |
| Lasso Regression  | 0.8388     |
| Random Forest     | 0.8259     |


---

### Technologies Used:

* Python (Pandas, NumPy, Scikit-learn, NLTK, TensorFlow/Keras, Matplotlib, Seaborn, WordCloud)
* Power BI Desktop
* Git & GitHub

---

### Setup and Running the Python Notebook (Local):

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/afreenasif/Restaurant-Reviews-Sentiment-Analysis.git
    cd Restaurant-Reviews-Sentiment-Analysis
    ```

2.  **Install Dependencies:** It's recommended to create a virtual environment.
    ```bash
    # Create virtual environment
    python -m venv venv
    # Activate virtual environment (Windows)
    .\venv\Scripts\activate
    # Activate virtual environment (macOS/Linux)
    source venv/bin/activate
    # Install libraries
    pip install pandas numpy scikit-learn nltk tensorflow matplotlib seaborn wordcloud
    ```

3.  **Run the Notebook:**
    * Launch Jupyter Notebook: `jupyter notebook`
    * Navigate to `notebooks/your_sentiment_analysis.ipynb` and run all cells. This will generate the `sentiment_analysis_data.csv` and `model_accuracies.csv` files in your `data/` directory.

---
