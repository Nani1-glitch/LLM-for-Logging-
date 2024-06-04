# 📊 LLM for Logging 🚀

Welcome to the *LLM for Logging* project! This repository showcases the use of Large Language Models (LLMs) for log data analysis and categorization.

## 🌟 Overview

This project leverages BERT and other NLP techniques to categorize and analyze log data. The workflow includes data preprocessing, model training from scratch, evaluation, and saving the trained model.

## 🗂 Repository Structure

```plaintext
LLM-for-Logging/
├── .gitattributes
├── .DS_Store
├── Final.ipynb
├── Log categorization using LLM.pdf
├── Manual Approach(EX).ipynb
├── Train BERT.pdf
├── Trained BERT Model.ipynb
├── Trained Bert Model from scratch.ipynb
├── cisco_log.txt
├── enhanced_cisco_logs.csv
├── sample_logs.txt
├── structured_logs.csv
├── structured_output.csv
└── README.md (You are here!)


📖 How to Use
Clone the repository:
sh
Copy code
git clone https://github.com/Nani1-glitch/LLM-for-Logging-.git
Navigate to the project directory:
cd LLM-for-Logging
Run the Jupyter notebooks:
Final.ipynb for the final implementation.
Manual Approach(EX).ipynb for manual log categorization examples.
Trained Bert Model from scratch.ipynb for training BERT from scratch.
🧩 Key Components
Data Preprocessing
Log Parsing: Extracts relevant information from raw log files.
Labeling: Identifies and labels error messages.
Model Training
BERT Model: Utilizes BERT for sequence classification.
Training Loop: Implements a custom training loop with logging.
Evaluation
Metrics: Computes accuracy, precision, recall, and F1-score.
Outputs
Trained Model: Saves the trained BERT model and tokenizer.
Evaluation Results: Displays performance metrics of the trained model.
📈 Results
Evaluation Metrics
Accuracy: 63.97%
Precision: 63.01%
Recall: 67.65%
F1 Score: 65.25%
📂 Data Files
Logs: cisco_log.txt, sample_logs.txt
Enhanced Logs: enhanced_cisco_logs.csv
Structured Logs: structured_logs.csv
Structured Output: structured_output.csv
🛠 Tools & Libraries
Python
Pandas
PyTorch
Transformers
Scikit-Learn
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

👥 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

📞 Contact
For any questions or feedback, please contact me!
