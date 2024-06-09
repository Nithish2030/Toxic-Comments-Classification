**Project Name:** Toxic-Comments-Classification

**Description:**
The Toxic-Comments-Classification project aims to identify and classify toxic comments using advanced natural language processing (NLP) techniques and deep learning models. The project features an interactive frontend developed with Gradio for user interaction and model evaluation.

**Technical Details:**

1. **NLP Techniques Used:**
   - **Text Preprocessing:** Applied essential NLP preprocessing steps such as tokenization, stopword removal, stemming, lemmatization, and text normalization to clean and prepare the text data for model training.

2. **Deep Learning Models Employed:**
   - **LSTM (Long Short-Term Memory):** Utilized LSTM networks to capture long-term dependencies in text sequences, helping in understanding the context of comments over time.
   - **BiLSTM (Bidirectional Long Short-Term Memory):** Implemented BiLSTM networks to analyze text sequences in both forward and backward directions, enhancing the model's ability to understand the context and improve classification accuracy.

3. **Frontend:**
   - **Gradio Interface:** Developed an interactive frontend using Gradio, allowing users to input comments and get real-time toxicity classification results. Gradio also provides a user-friendly interface for model evaluation and testing.

4. **Performance Measures:**
   - **Accuracy:** Calculated the overall correctness of the model's predictions.
   - **Precision:** Measured the proportion of true positive predictions among all positive predictions.
   - **Recall:** Assessed the proportion of true positive predictions among all actual positive instances.
   - **F1 Score:** Computed the harmonic mean of precision and recall to provide a balanced measure of the model's performance.

**Project Workflow:**
1. **Data Collection:** Gathered a dataset of comments labeled with various toxicity levels.
2. **Preprocessing:** Cleaned and prepared the text data using NLP preprocessing techniques.
3. **Model Training:** Trained LSTM and BiLSTM models on the preprocessed text data.
4. **Evaluation:** Evaluated the models using performance measures such as accuracy, precision, recall, and F1 score.
5. **Deployment:** Deployed the models through a Gradio interface, enabling users to classify comments in real-time.

This project successfully combines advanced NLP preprocessing, powerful deep learning models, and an interactive Gradio interface to effectively classify toxic comments, ensuring high accuracy and reliability in identifying harmful content.
