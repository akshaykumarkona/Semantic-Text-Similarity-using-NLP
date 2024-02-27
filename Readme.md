## Introduction
This project focuses on analyzing semantic text similarity using natural language processing (NLP) techniques. The goal is to determine the degree of similarity between pairs of text documents, with potential applications in information retrieval, recommendation systems, and plagiarism detection.

## Installation
To run the code, ensure you have Python installed on your system along with the following dependencies:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- beautifulsoup4

You can install these dependencies using pip:
```python
pip install pandas numpy matplotlib seaborn scikit-learn beautifulsoup4
```

## Usage
+   **Loading the Dataset:** The code reads input data from CSV or Excel files (Text_Similarity.csv).
+   **Text Preprocessing:** Preprocessing steps include removing duplicates, null values, HTML tags, punctuation, and replacing chat words with their full forms.
+   **TF-IDF for Text Representation:** TF-IDF (Term Frequency-Inverse Document Frequency) is used to numerically represent the text data.
+   **Calculating Similarity:** Cosine similarity is computed between pairs of text documents to quantify their similarity.
+   **Evaluation:** The model's performance is evaluated by comparing similarity scores with benchmark scores.
+   **Sample Testing:** Use the provided sample data to test the code with sample sentences and interpret the results.
+   **Conclusion:** Summarize findings and insights gained from the text similarity analysis.

## Sample Testing
To test the code with sample sentences, use the provided sample data in the code. The similarity scores between text pairs will be calculated and displayed, allowing you to assess the effectiveness of the NLP-based approach.

## Conclusion
The project demonstrates an effective NLP-based approach for analyzing semantic text similarity. Evaluation against benchmark scores shows a strong positive correlation, indicating the model's capability to accurately capture text similarity.

## Note
You can find more about benchmark datasets and it's similarity scores in ***"Benchmark_readme.txt"***.