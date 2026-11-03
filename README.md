[comparison_report.pdf](https://github.com/user-attachments/files/34315604/comparison_report.pdf)
this project builds a sentiment classifier for financial tweets and news headlines to predict market sentiment as bearish,bullish,neutral.Dataset train_clen.csv is highly imbalanced.
## How to Run Complete Pipeline
Phase 1: Data Filtering - clean URLs, lowercase, tokenize
Phase 2: Model Training - Bi-LSTM (Approach 3) 74.28% -> save lstm_model.h5 + tokenizer.pkl / FinBERT fine-tune -> 81.8%
Phase 3: Evaluation - Accuracy, F1, Confusion Matrix
Phase 4: Dashboard - streamlit run app.py --server.port 8501


