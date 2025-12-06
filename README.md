✈️ Airline Delay Prediction using Deep Learning (LSTM Classifier)

📌 Project Overview
Flight delays affect millions of passengers and airline operations worldwide.
This project builds a Deep Learning model using LSTM + categorical embeddings to predict whether a flight will be delayed (>15 minutes).

✔ Dataset: US DOT Airline Flights (Kaggle)
✔ Model Framework: PyTorch
✔ Output: Binary classification — Delayed vs On‑time

📂 Repository Structure
├── data/
│   ├── flights.csv
│   ├── airlines.csv
│   ├── airports.csv
├── models/
│   ├── best_lstm_airline.pt
├── notebooks/
│   ├── Airline_Delay_Training.ipynb
├── results/
│   ├── loss_curve.png
│   ├── accuracy_curve.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
├── docs/
│   ├── Final_Report.docx
│   ├── Presentation.pptx
│   ├── Literature_Survey.pdf
└── README.md
Folder names may vary — update if needed.

📊 Dataset Used
🔗 Kaggle Link:
https://www.kaggle.com/datasets/usdot/flight-delays

Key features include:
✈ Airline, Origin Airport, Destination Airport
🕑 Departure/Arrival Time
📅 Date
📏 Distance
📌 Arrival Delay minutes

Target label:

1 → Delayed (>15 min)
0 → On-Time
🔧 Technologies Used
Python

PyTorch

Pandas / NumPy

Scikit‑Learn

Matplotlib & Seaborn

Google Colab

🧠 Model Architecture Summary
✔ Embedding layers for categorical values
✔ LSTM for temporal/sequence learning
✔ Fully connected neural layer for classification

Loss Function → CrossEntropyLoss
Optimizer → Adam

🚀 How to Run the Project
1. Clone Repo
git clone https://github.com/<username>/<repo>.git
cd <repo>
2. Install Dependencies
pip install -r requirements.txt
3. Add Dataset
Place these files inside /data/:

flights.csv  
airlines.csv  
airports.csv  
4. Train the Model
Open and execute:

notebooks/Airline_Delay_Training.ipynb
📈 Model Performance
Metric	Score
Accuracy	~83–84%
ROC-AUC	~0.75
F1-Score	~0.27 (class imbalance effect)
📉 Visual Results Included
✔ Training Loss Curve
✔ Validation Accuracy
✔ Confusion Matrix Heatmap
✔ ROC Curve

All stored in /results/.

📚 Documentation Included
📄 Final Report → /docs/Final_Report.docx
📊 PPT Slides → /docs/Presentation.pptx
📑 Literature Survey → /docs/Literature_Survey.pdf

🔮 Future Scope
🔹 Add weather features
🔹 Try attention/transformer architectures
🔹 Improve recall for delay class using class‑balancing
🔹 Deploy as real‑time web API

👥 Contributors
Parshav Goyal
Charu
Vaibhavi Kumari

