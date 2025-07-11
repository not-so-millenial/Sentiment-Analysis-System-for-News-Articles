
# Sentiment Analyzer for News Articles

This project focuses on extracting and analyzing sentiment from online news articles using advanced Natural Language Processing (NLP) and Machine Learning techniques. The goal is to create an end-to-end system that can query news articles, extract and preprocess the unstructured text, and perform in-depth textual analysis including sentiment detection, topic modeling, and named entity recognition.

---

## 🧠 Key Features

- 🔍 **News Scraping**: Automatically fetches the latest news articles from Google News based on a user query.
- 🧹 **NLP Preprocessing Pipeline**: Tokenization, Part-of-Speech (POS) tagging, Named Entity Recognition (NER), and more.
- 😃 **Sentiment Analysis**: Uses HuggingFace Transformers to classify sentiments in news headlines or article content.
- 🧠 **Topic Modeling**: Employs LDA (Latent Dirichlet Allocation) for extracting topics from the text corpus.
- 📊 **Statistical Insight Extraction**: Computes variable distributions, word frequencies, and topic relevance.
- ⚙️ **Streamlit Interface** *(optional)*: Interactive UI for real-time sentiment extraction.

---

## 📁 Project Structure

```
Sentiment_Analyzer/
│
├── Sentiment Analyzer.ipynb     # Main Jupyter notebook
├── requirements.txt             # Package requirements
├── README.md                    # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Sentiment_Analyzer.git
cd Sentiment_Analyzer
```

### 2. Install Dependencies

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install requests html5lib beautifulsoup4 pandas numpy nltk seaborn matplotlib streamlit transformers gensim pyLDAvis
```

Download required NLTK data:

```python
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
nltk.download('stopwords')
```

---

## 🧾 Usage

### Step 1: Run the Notebook
Open `Sentiment Analyzer.ipynb` and run the cells step by step.

### Step 2: Enter Your Query
You can change the search term in:

```python
query = 'modi'  # Replace with any keyword/topic
```

### Step 3: Scrape and Analyze
The notebook performs:
- URL fetching from Google News
- Text extraction using BeautifulSoup
- Preprocessing using NLTK
- Sentiment analysis using HuggingFace Transformers
- Topic modeling using Gensim LDA

---

## 🧪 NLP Techniques Used

| Technique | Description |
|----------|-------------|
| **Tokenization** | Splitting text into meaningful units |
| **POS Tagging** | Identifying parts of speech in the text |
| **NER** | Identifying entities like names, places, etc. |
| **Sentiment Analysis** | Classifying sentiment using Transformer-based models |
| **Topic Modeling** | Extracting high-level topics using LDA |
| **Text Cleaning** | Removing stopwords, punctuation, and noise |

---

## 📈 Sample Output

- 📄 Dataframe of scraped news links
- 📊 Bar plots of sentiment distribution
- 📚 Top keywords per topic
- 🧾 Named entities highlighted in articles

---

## 🧠 Technologies Used

- `BeautifulSoup` for web scraping
- `NLTK` for preprocessing
- `Transformers (HuggingFace)` for sentiment classification
- `Gensim` for topic modeling
- `Seaborn/Matplotlib` for visualization
- `Streamlit` for interactive web UI (if deployed)

---

## 📌 Resume Highlights (as per usage in this project)

- **Developed data pipelines** to efficiently extract, clean, and transform unstructured text from the web.
- **Applied advanced NLP techniques** including tokenization, POS tagging, and named entity recognition.
- **Leveraged Transformers** for sentiment analysis and **LDA** for topic modeling.
- **Generated actionable insights** through visualizations and computed statistics on text data.

---

## 📬 Contact

For questions or collaborations, reach out at:  
**[Your Name]** – *AI Engineer*  
📧 your.email@example.com  
📍 Bangalore, India
