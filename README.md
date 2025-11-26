# Hiver AI Intern Evaluation Assignment

Implementation of three AI systems for customer support: Email Tagging, Sentiment Analysis, and Knowledge Base RAG.

## Project Structure

```
Hiver Project/
├── data/
│   ├── small_dataset.csv
│   └── large_dataset.csv
├── part_a_email_tagging/
│   ├── email_tagger.ipynb
│   └── README.md
├── part_b_sentiment_analysis/
│   ├── sentiment_analysis.ipynb
│   ├── prompt_v1.txt
│   ├── prompt_v2.txt
│   └── README.md
├── part_c_mini_rag/
│   ├── rag_system.ipynb
│   └── README.md
└── requirements.txt
```

## Setup

### 1. Install Dependencies

```bash
# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
# source venv/bin/activate  # macOS/Linux

# Install packages
pip install -r requirements.txt
```

### 2. Configure API Key

Create a `.env` file in project root:

```
GROQ_API_KEY=your_api_key_here
```

Get free API key at: https://console.groq.com/

## Running the Code

**Part A - Email Tagging:**
```bash
cd part_a_email_tagging
jupyter notebook email_tagger.ipynb
```

**Part B - Sentiment Analysis:**
```bash
cd part_b_sentiment_analysis
jupyter notebook sentiment_analysis.ipynb
```

**Part C - RAG System:**
```bash
cd part_c_mini_rag
jupyter notebook rag_system.ipynb
```

## Assignment Parts

- **Part A**: Email classification with customer isolation
- **Part B**: Sentiment analysis prompt evaluation and improvement
- **Part C**: RAG-based knowledge base answering

See individual README files in each part's directory for detailed documentation.
