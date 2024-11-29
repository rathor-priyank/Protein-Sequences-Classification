# Protein Classification using Deep Learning  

## 📚 Overview  
This project classifies proteins into families using deep learning models (LSTM, RNN, CNN) based on amino acid sequences. The goal is to explore their effectiveness in biological sequence analysis.  

## 📂 Dataset  
- **Source**: [Protein Data Set](https://www.kaggle.com/shahir/protein-data-set) from the PDB.  
- **Size**: 214,106 cleaned entries after preprocessing.  
- **Key Features**: Protein sequences (`sequence`) and family types (`classification`).  

## ⚙️ Methodology  
1. **Preprocessing**:  
   - Tokenized and padded sequences to length 200.  
   - Encoded family labels.  
   - Split data into training and testing sets (80:20 and 70:30 splits).  
2. **Models**:  
   - **LSTM**: Captures long-range sequence dependencies.  
   - **RNN**: Simpler sequential model.  
   - **CNN**: Extracts spatial features for faster training.  
3. **Training**:  
   - 10 epochs, batch size 32.  
   - Accuracy and loss tracked for validation.  

## 🏆 Results  
- **Best Model**: RNN achieved highest validation accuracy (61.18%) with the 80:20 split.  
- CNN trained faster but showed signs of overfitting.  

## 🚀 Future Work  
- Explore advanced architectures (e.g., Transformers).  
- Use additional structural features and address class imbalance.  
