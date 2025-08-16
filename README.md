# Restaurant Search NER Recognition by Fine-Tuning DistilBERT

This project fine-tunes the **DistilBERT** model to perform **Named Entity Recognition (NER)** for restaurant search scenarios.  
It is built using the Hugging Face `transformers` library.

## 📌 Features
- DistilBERT-based NER model
- Step-by-step training process in Jupyter Notebook
- Includes tokenizer and trained model weights
- Example predictions on custom input sentences

## 📂 Project Structure
```
.
├── ner_distilbert/               # Fine-tuned model files
│   ├── config.json
│   ├── model.safetensors
│   ├── tokenizer.json
│   └── ...
├── Restaurant_Search_NER_Recognition_By_Fine_Tuning_DistilBERT.ipynb  # Training & inference notebook
```

## 🔧 Requirements
- Python 3.8+
- transformers
- datasets
- torch
- Jupyter Notebook

Install the required libraries:
```bash
pip install -r requirements.txt
```
or
```bash
pip install transformers datasets torch notebook
```

## 🚀 Usage
1. Open the notebook:
```bash
jupyter notebook Restaurant_Search_NER_Recognition_By_Fine_Tuning_DistilBERT.ipynb
```
2. Run all cells to train the model or load the pre-trained fine-tuned model.
3. Use the final model to predict entities in new sentences.

## 📊 Model Information
- **Base Model:** DistilBERT (Hugging Face)
- **Task:** Named Entity Recognition
- **Dataset:** Restaurant search dataset
- **Entity Types:** Location, cuisine type, restaurant name, etc.

