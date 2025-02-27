# Amazon Alexa Sentiment Analysis 📊

This project performs sentiment analysis on Amazon Alexa customer reviews using **NLTK's VADER**. It categorizes reviews as **Positive, Negative, or Neutral** and visualizes sentiment distribution.

---

## 🚀 Features  
✔ Reads Alexa reviews dataset (`amazon_alexa.tsv`)  
✔ Uses **VADER Sentiment Analyzer** for text analysis  
✔ Categorizes reviews into **Positive, Negative, or Neutral**  
✔ **Visualizes** sentiment distribution with **Matplotlib**  

---

## 🛠 Installation  

### 1️⃣ Install Dependencies  
Ensure you have Python installed, then install required libraries:

```bash 
pip install pandas matplotlib nltk
```

#### 2️⃣ Download NLTK Data
Before running the script, download vader_lexicon:
```bash 
import nltk
nltk.download('vader_lexicon')
```
## 📌 Usage

Running the Python Script
Clone the repository and execute the script:
```bash
git clone https://github.com/Divyasreevaka/amazon_sentiment.git
cd amazon_sentiment
python amazon_sentiment.py
```
📜 License
This project is open-source under the MIT License.
