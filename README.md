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

### How to Explore This Project:

You can explore this project in two primary ways:

1.  **Review the Code:**
    * Navigate to the `notebooks/` directory and open `your_sentiment_analysis.ipynb`. This notebook details the entire analytical pipeline, from data loading and cleaning to model training, evaluation, and the generation of the output data files.

2.  **Interact with the Power BI Dashboard:**
    * **Download:** Clone this entire repository or specifically download the `powerbi/Restaurant_Sentiment_Dashboard.pbix` file along with the two CSV files from the `data/` folder: `sentiment_analysis_data.csv` and `model_accuracies.csv`.
    * **Open:** Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed. Open the `.pbix` file.
    * **Explore:** The dashboard is designed to be interactive, allowing you to filter by restaurant, view sentiment distributions, compare model accuracies, and dive into specific review details.

---

### Technologies Used:

* Python (Pandas, NumPy, Scikit-learn, NLTK, TensorFlow/Keras, Matplotlib, Seaborn, WordCloud)
* Power BI Desktop
* Git & GitHub

---

### Setup and Running the Python Notebook (Local):

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/YourRepositoryName.git](https://github.com/YourUsername/YourRepositoryName.git)
    cd YourRepositoryName
    ```
    (Replace `YourUsername` and `YourRepositoryName` with your actual GitHub details.)

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
