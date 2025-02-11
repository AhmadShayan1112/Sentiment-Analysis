## **Sentiment Analysis - Urdu Sarcasm Detection**  

### **Overview**  
This project focuses on **Urdu sarcasm detection** using **Natural Language Processing (NLP)**. It includes **spelling correction** with the **LughaatNLP** library and leverages **parallel processing** for efficient text preprocessing.  

### **Features**  
✅ Preprocessing of an Urdu sarcasm dataset  
✅ Spelling correction using **LughaatNLP**  
✅ Parallel processing with **joblib** & **multiprocessing**  
✅ Saves a cleaned dataset for further analysis  

### **Installation**  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/AhmadShayan1112/Sentiment-Analysis.git
cd Sentiment-Analysis
pip install -r requirements.txt
```
If `requirements.txt` is missing, install manually:  
```bash
pip install pandas tqdm joblib LughaatNLP
```

### **Usage**  
Open and run the Jupyter Notebook:  
```bash
jupyter notebook NLP(1).ipynb
```
Or run the script version (if available):  
```bash
python preprocess.py
```

### **Dataset**  
- Input: `urdu_sarcastic_dataset.csv`  
- Output: `urdu_sarcastic_dataset_corrected.csv` (after processing)  

### **Dependencies**  
- **Python 3.x**  
- **Pandas** – Data handling  
- **LughaatNLP** – Spelling correction  
- **TQDM** – Progress tracking  
- **Joblib** – Parallel processing  

### **Contributing**  
Contributions are welcome! Feel free to submit issues or pull requests.  

