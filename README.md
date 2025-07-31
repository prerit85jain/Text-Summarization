## Text Summarization Project

This is a **natural language processing (NLP) project** that automatically generates concise summaries from longer text documents using **extractive summarization** techniques.

### 🎯 **Purpose**
The project takes a long text document and creates a summary by identifying and extracting the most important sentences based on keyword frequency analysis.

### �� **How It Works**
1. **Text Processing**: Uses spaCy's English language model to parse and analyze the input text
2. **Keyword Extraction**: Identifies important words (nouns, verbs, adjectives, proper nouns) while filtering out stop words and punctuation
3. **Frequency Analysis**: Calculates the frequency of each keyword and normalizes the scores
4. **Sentence Scoring**: Assigns strength scores to sentences based on the frequency of important keywords they contain
5. **Summary Generation**: Selects the top 3 sentences with the highest scores to create the final summary

### �� **Key Features**
- **Extractive Summarization**: Preserves original sentence structure
- **Keyword-based Scoring**: Uses TF-IDF-like approach for sentence importance
- **Configurable Output**: Can be easily modified to extract different numbers of sentences
- **Language Support**: Specifically designed for English text processing

### 🚀 **Results**
The project successfully processed an 8-sentence text about artificial intelligence and generated a coherent 3-sentence summary focusing on the key concepts of AI, machine learning, and deep learning.

### 💻 **Technologies Used**
- **spaCy**: Natural language processing library
- **Python**: Core programming language
- **NumPy**: Numerical computations (via spaCy dependencies)
- **Collections**: For frequency counting
- **Heapq**: For selecting top sentences

This project demonstrates practical application of NLP techniques for automatic text summarization, making it useful for quickly extracting key information from lengthy documents.
