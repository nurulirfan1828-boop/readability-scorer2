# AI Reading Level & Linguistic Complexity Scorer

Built for the **Veritas AI International High School Hackathon**.

## 💡 The Problem
Teachers and students frequently encounter educational texts that are either too dense or too simple for a target grade level. Standard readability formulas only count syllables and sentence length without capturing deeper vocabulary and structural complexity.

## 🛠️ How It Works
This application analyzes any pasted educational text and predicts its reading grade level and linguistic complexity:
1. **Feature Extraction:** Uses `textstat` and Python NLP techniques to extract sentence length, syllable density, and vocabulary metrics.
2. **Machine Learning Model:** Combines linguistic features with TF-IDF text representations in a `scikit-learn` regression model to score readability.
3. **Interactive Web App:** Built with `Streamlit` to give teachers and students instant visual feedback and highlight complex sentences.

## 🚀 How to Run Locally
1. Install the required libraries:
   ```bash
   pip install -r requirements.txt
  
