# 🐍 Text Classification with Transformers

## 📝 Description
This Python script demonstrates **text classification** using transformer models like **DistilBERT**. It fine-tunes the model on the **Emotion dataset** and evaluates its performance. The script includes data preprocessing, model training, and visualization of results using metrics like accuracy and F1 score.

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/navidfalah/text-classification-transformers.git
   cd text-classification-transformers
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Install additional libraries:
   ```bash
   pip install datasets transformers umap-learn wandb
   ```

## 🚀 Usage
1. Run the script:
   ```bash
   python text_classification_transformers.py
   ```
2. The script will:
   - Load and preprocess the Emotion dataset.
   - Fine-tune the DistilBERT model for text classification.
   - Evaluate the model using accuracy and F1 score.
   - Visualize embeddings using UMAP.
   - Save and push the fine-tuned model to Hugging Face Hub.

## 📂 File Structure
```
text-classification-transformers/
├── text_classification_transformers.py  # Main script
├── README.md                            # This file
├── requirements.txt                     # Dependencies
└── data/                                # (Optional) Data folder for local inputs
```

## 🧩 Key Features
- **Text Classification**:
  - Fine-tune DistilBERT on the Emotion dataset.
  - Evaluate model performance using accuracy and F1 score.
- **Data Preprocessing**:
  - Tokenize text data using Hugging Face's `AutoTokenizer`.
  - Extract hidden states for visualization.
- **Visualization**:
  - Use UMAP to visualize embeddings in 2D.
  - Plot confusion matrices for model evaluation.
- **Model Saving**:
  - Save the fine-tuned model locally and push it to Hugging Face Hub.

## 📊 Example Outputs
1. **Embedding Visualization**:
   - 2D UMAP plot of hidden states for different emotion classes.
2. **Confusion Matrix**:
   - Normalized confusion matrix for model predictions.
3. **Model Performance**:
   - Accuracy: 0.92
   - F1 Score: 0.91

## 🤖 Models Used
- **DistilBERT**: A lightweight transformer model for text classification.

## 📈 Performance Metrics
- **Accuracy**: Measures the proportion of correct predictions.
- **F1 Score**: Balances precision and recall for imbalanced datasets.

## 🛠️ Dependencies
- Python 3.x
- Libraries:
  - `torch`, `transformers`
  - `datasets`, `umap-learn`
  - `wandb`, `numpy`, `pandas`, `matplotlib`

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👤 Author
- **Name**: Navid Falah
- **GitHub**: [navidfalah](https://github.com/navidfalah)
- **Email**: navid.falah7@gmail.com
