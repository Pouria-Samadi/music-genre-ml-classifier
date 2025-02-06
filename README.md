```markdown
# 🎵 Music Genre ML Classifier

A Machine Learning project using **Decision Trees** to predict music genres based on **age** and **gender**. Built with Python, scikit-learn, pandas, and Graphviz, it trains a model, saves it using joblib, and visualizes the decision process. Run in Jupyter Notebook for easy data exploration.

## 📂 Project Structure

```
music-genre-ml-classifier/
├── MusicAPP.ipynb             # Jupyter Notebook with code and analysis
├── music.csv                  # Dataset containing age, gender, and genre
├── music-recommender.dot      # DOT file for decision tree visualization
├── music recommender.joblib   # Serialized trained model
└── Visualization.svg          # Decision tree visualization
```

## 📊 Dataset

The dataset (`music.csv`) includes:

- **Age**: Listener's age
- **Gender**: Listener's gender
- **Genre**: Preferred music genre

## 🛠️ Methods Used

1. **Data Loading**: Imported the dataset using pandas.
2. **Data Preprocessing**: Prepared the data for training by encoding categorical variables.
3. **Model Training**: Utilized scikit-learn's `DecisionTreeClassifier` to train the model.
4. **Model Serialization**: Saved the trained model using joblib for future use.
5. **Visualization**: Generated a visual representation of the decision tree using Graphviz.

## 🚀 How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Pouria-Samadi/music-genre-ml-classifier.git
   cd music-genre-ml-classifier
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required libraries:
   ```bash
   pip install pandas scikit-learn joblib graphviz
   ```

3. **Run the Jupyter Notebook**:
   Launch Jupyter Notebook and open `MusicAPP.ipynb` to explore the code and results:
   ```bash
   jupyter notebook MusicAPP.ipynb
   ```

## 📈 Visualization

The decision tree visualization provides insight into the model's decision-making process.  
🔗 **Click the image to view full size:**

[![Decision Tree](https://raw.githubusercontent.com/Pouria-Samadi/music-genre-ml-classifier/main/Visualization.svg)](https://github.com/Pouria-Samadi/music-genre-ml-classifier/blob/main/Visualization.svg)


## 🤖 Technologies Used

- **Python** 🐍
- **pandas**: Data manipulation and analysis
- **scikit-learn**: Machine learning library
- **Graphviz**: Graph visualization software
- **Jupyter Notebook**: Interactive computing environment
- **joblib**: Efficient serialization of Python objects

## 📬 Contact

For any questions or suggestions, feel free to reach out or open an issue in this repository.

---
