# Deep Learning and Neural Networks

A curated collection of **hands-on case studies** exploring deep learning techniques on real-world datasets.  
Each case study is self-contained with its own **notebooks, scripts, and README** to help you understand the concepts step by step.

---

## 📚 Case Studies

1. **[Titanic Survival](case_studies/01_titanic_survival/)**  
   - Dataset: Titanic passenger data  
   - Goal: Predict passenger survival using deep learning.  
   - Concepts: Data preprocessing, feedforward neural networks, binary classification.

2. **[Image Classification with Optimization & Regularization (CIFAR-10)](case_studies/02_cifar10_optimization_regularization/)**  
   - Dataset: CIFAR-10 (60,000 32×32 color images across 10 classes)  
   - Goal: Build robust CNNs with optimization tricks.  
   - Concepts: Data augmentation, dropout, batch normalization, optimizer comparison.

3. **[Sentiment Analysis (IMDB)](case_studies/03_imdb_sentiment_analysis/)**  
   - Dataset: IMDB movie reviews (50,000 labeled reviews)  
   - Goal: Classify reviews as positive or negative.
   - Concepts: Word embeddings, LSTMs, text preprocessing.

4. **[Fashion Classification & Anomaly Detection](case_studies/04_fashion_classification_anomaly/)**  
   - Dataset: Fashion-MNIST (70,000 28×28 grayscale images across 10 categories)  
   - Goals:  
     - Classify clothing items using CNNs.  
     - Detect anomalies using Autoencoders.  
   - Concepts: CNN architecture, unsupervised learning, reconstruction error for anomaly detection.

---

## Quick Start

```bash
git clone https://github.com/SoeRatch/applied-deep-learning.git
cd applied-deep-learning
# Navigate to specific case folder, then:
# pip install -r case_studies/<folder_name>/requirements.txt

# launch notebooks via Jupyter or VS Code
