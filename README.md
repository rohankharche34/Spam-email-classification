# Spam-email-classification
# 🧠 Text Classification using Voting Ensembles

This project implements a **text classification pipeline** using **Hard Voting** and **Soft Voting** ensemble techniques. It uses classical machine learning models to classify text messages based on their content.

---

## 📁 Dataset

- **Filename**: `combined_dataset.csv`
- **Location**: `data/combined_dataset.csv`
- **Shape**: 83,448 rows × 2 columns
- **Columns**:
  - `label`: Integer class label (0 or 1)
  - `Message`: Text message content to classify

---

## 📊 Models Used

### ✅ Base Models:
- `MultinomialNB` (Naive Bayes)
- `LinearSVC` (for hard voting)
- `LogisticRegression` (for soft voting)

### ✅ Ensemble Techniques:
- **Hard Voting Classifier**
- **Soft Voting Classifier**

---

## 🧪 Performance Results

### 🔷 Hard Voting
- **Test Accuracy**: `0.9719`

### 🔷 Soft Voting
- **Test Accuracy**: `0.9772`


---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/rohankharche34/Spam-email-classification.git
cd Spam-email-classification
```

### 2. Create and activate a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # on Windows use `venv\Scripts\activate`
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```