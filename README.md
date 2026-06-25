# CS566 – Artificial Intelligence: Classification Algorithms

## 📘 Course Information

- **Course:** CS566 – Artificial Intelligence  
- **Term:** Summer 2024  
- **Institution:** Bishop's University  
- **Project Type:** Final Project  
- **Topic:** Classification Algorithms — Perceptron, MIRA & Behavioral Cloning  

---

## 📌 Project Overview

This project implements and evaluates multiple **classification techniques** in Python, with an emphasis on perceptron-based models and margin-based learning. The implementations are based on the **UC Berkeley Pacman AI framework**.

Key components:
- Feature design for image and agent-based classification
- Model training with iterative weight updates
- Performance evaluation on digit recognition and Pacman behavior
- Comparative analysis of Perceptron vs. MIRA

---

## 🧠 Algorithms Implemented

- **Perceptron** — standard linear classifier with online weight updates
- **MIRA (Margin Infused Relaxed Algorithm)** — margin-based perceptron variant
- **Behavioral Cloning** — learning Pacman actions from expert demonstrations
- **Pacman Feature Design** — custom feature engineering for agent classification

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- UC Berkeley Pacman AI framework
- Command-line execution

---

## 📂 Repository Structure

```
cs566-advanced-ai-classification/
├── src/
│   ├── dataClassifier.py       # Main classifier driver
│   ├── perceptron.py           # Perceptron classifier
│   ├── perceptron_pacman.py    # Pacman behavioral cloning
│   ├── mira.py                 # MIRA classifier
│   └── answers.py              # Analysis answers
├── report/
│   └── Final Project report.pdf
├── .gitignore
└── README.md
```

---

## ▶️ How to Run

1. Navigate to the `src/` directory:
   ```bash
   cd src
   ```

2. Run a classifier:
   ```bash
   python dataClassifier.py -c perceptron
   python dataClassifier.py -c mira
   ```

---

## 📝 Notes

This project was developed as part of an academic course.  
The code is intended for educational and research purposes only.  
Base framework provided by UC Berkeley (Pacman AI Projects).

## 👤 Author

**Ahmad Issa**  
Bishop's University  
Department of Computer Science

---

**Ahmad Issa**  
Master's Student in Computer Science  
Bishop's University  
Student ID: 002230777
