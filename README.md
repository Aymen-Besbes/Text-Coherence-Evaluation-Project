# Automatic-Analysis-of-Inter-sentential-Coherence-in-Text
This project is a classroom mini-project aiming to develop a system for analyzing inter-sentential coherence in English text. The goal is to evaluate the coherence between pairs of sentences within paragraphs, between paragraphs, and across the entire text using machine learning models.

## Project Description
The project involves the following steps:

### Data Collection
- Collect a diverse corpus of English text including paragraphs and larger sections.

### Human Annotation
- Annotate inter-sentential coherence for each pair of sentences using a numerical scale to represent the degree of coherence.

### Data Preprocessing
- Clean and preprocess textual data by removing irrelevant elements.

### Feature Extraction
- Use pretrained language models (BERT) to generate vector representations of sentences.

### Inter-sentential Similarity Measurement
- Calculate similarity between sentence representation vectors using metrics like cosine similarity.

### Automatic Annotation
- Compare automatic similarity measurement results with human annotations to evaluate model performance.

### Score Aggregation
- Aggregate inter-sentential similarity scores to obtain coherence measures at the paragraph, inter-paragraph, and whole text levels.

### Results Analysis
- Analyze results to identify areas where coherence varies across different levels of analysis.

### Model Adjustment
- Adjust or explore different language models based on analysis results to improve inter-sentential coherence capture.

## Results
The following machine learning models were evaluated:

- SVM with TF-IDF
- SVM with Bag of Words
- SVM with Word2Vec
- Gaussian Naive Bayes with TF-IDF

### Best Model Performance:
| Model              | Accuracy | Precision | Recall |
|--------------------|----------|-----------|--------|
| SVM with TF-IDF    | 0.12     | 0.30      | 0.30   |
| SVM with Bag of Words | 0.12  | 0.30      | 0.30   |
| SVM with Word2Vec  | 0.11     | 0.25      | 0.25   |
| Gaussian Naive Bayes with TF-IDF | 0.15 | 0.25 | 0.15 |

### Interpretation
- **Accuracy**: Indicates overall correctness of predictions.
- **Precision**: Proportion of correctly predicted coherent pairs out of all predicted coherent pairs.
- **Recall**: Proportion of correctly predicted coherent pairs out of all actual coherent pairs in the dataset.

### Conclusion
- Based on the results, further improvements and adjustments can be made to enhance the model's ability to detect inter-sentential coherence in Arabic text.
