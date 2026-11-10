# Predicting Sales Performance of Steam Games (MSc Data Science Dissertation)

**Institution:** Coventry University, United Kingdom — MSc in Data Science (1/2024 – 3/2025)  
**Author:** Vinay Kumar Chinthamalla

---

## Project Overview
This project develops an end-to-end machine learning and deep learning system to forecast video game sales performance on the **Steam** platform. By analyzing developer/publisher reputation, pricing strategies, release trends, user engagement metrics, and natural language game reviews, the framework identifies key commercial drivers and achieves **84% prediction accuracy** on a dataset of **over 83,000 games and 39 features**.

---

## Key Achievements & Methodology

1. **Large-Scale Data Engineering (`83,000+` Rows, `39` Features):**
   - Cleaned, normalized, and encoded high-cardinality categorical and numerical metadata (genres, tags, release dates, multi-platform support, pricing tiers, and ownership brackets).
   - Imputed missing values and applied feature scaling to stabilize gradient-based and tree-based learners.

2. **NLP & Sentiment Analysis (`NLTK VADER`):**
   - Conducted sentiment analysis on user feedback and community game reviews using **VADER (Valence Aware Dictionary and sEntiment Reasoner)** to quantify review polarity and compound sentiment scores as predictive features.

3. **Machine Learning & Deep Learning Models Evaluated:**
   - **Ensemble & Tree Models:** Random Forest, Gradient Boosting, Decision Trees
   - **Deep Learning Architectures:** Long Short-Term Memory (`LSTM`) and Convolutional Neural Networks (`CNN`) built with `TensorFlow` and `Keras`

4. **Model Evaluation & Performance:**
   - Achieved **84% predictive accuracy** on unseen test data.
   - Rigorously evaluated regression and classification performance using **Mean Squared Error (MSE)**, **R² (Coefficient of Determination)**, and **Mean Absolute Error (MAE)** to surface actionable insights for game publishers and pricing strategists.

---

## Technologies Used
- **Languages & Core Libraries:** `Python`, `Pandas`, `NumPy`
- **Machine Learning & Deep Learning:** `Scikit-learn`, `TensorFlow`, `Keras`
- **NLP:** `NLTK` (`VADER Sentiment Analysis`)
- **Visualization & EDA:** `Matplotlib`, `Seaborn`
