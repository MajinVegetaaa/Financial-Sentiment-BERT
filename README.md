# Financial News Sentiment Classifier (BERT)

An end-to-level sentiment analysis project using **BERT** to classify financial headlines into three categories: **Positive, Negative, and Neutral**.

## 🚀 Project Overview
- **Dataset**: `financial_phrasebank` (approx. 4,800 human-annotated financial sentences).
- **Model**: `bert-base-uncased` fine-tuned with selective layer freezing (top 4 layers) to prevent overfitting.
- **Techniques**: Dropout regularization, Linear Learning Rate Decay with Warmup, Early Stopping, and Class Weight analysis.

## 📊 Results
- **Test Accuracy**: 85.26%
- **F1-Score**: Balanced performance across all classes, with particularly high precision in Neutral and Negative categories.

## 🛠️ Installation & Usage
1. Clone the repo:
   ```bash
   git clone <your-repo-link>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or use the `classify_headline` function in your own scripts.

## 📈 Visualizations
Included in the repository are PDF exports of:
- Training vs. Validation Loss/Accuracy curves.
- Confusion Matrix showing classification performance per class.
