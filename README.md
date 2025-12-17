# 🎤 Grammar Scoring Engine from Voice Samples


## SHL Assessment Project

A complete machine learning pipeline that analyzes spoken audio and predicts grammar proficiency scores.

---

##  Project Overview

This system extracts audio features from voice recordings and uses machine learning to:
- **Score grammar proficiency** (0-100 scale)
- **Classify proficiency level** (Beginner/Intermediate/Advanced)
- **Provide personalized feedback** for improvement
- **Analyze speaking patterns** (fluency, pronunciation, rhythm)

**Key Achievement**: Achieved **R² = 0.862** accuracy using Random Forest regression.

---

##  Quick Start

### Option 1: Run on Kaggle (Recommended)
[(https://www.kaggle.com/code/arshitaverma123/grammar-scoring-system-for-spoken-audios)]

### Option 2: Run Locally
```bash
# Clone repository
git clone https://github.com/Arshita1234/grammar-scoring.git
cd grammar-scoring

# Install dependencies
pip install -r requirements.txt

# Run the scoring engine
python grammar_scoring.py

