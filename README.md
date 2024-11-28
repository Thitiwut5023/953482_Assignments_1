# Thitiwut Thitnuea
- 652115023


# Text Preprocessing and Tokenization

This project provides Python code for text preprocessing, which includes:
1. **Text Cleaning**: Removing non-alphabetic characters and converting to lowercase.
2. **Tokenization**: Splitting text into sentences and words.
3. **Stopwords Removal**: Filtering out common words.
4. **Time Measurement**: Recording time for each step.

## Requirements

- Python 3.x
- `nltk` library

Install dependencies with:

```bash
pip install nltk
```

## Installation

1. Clone the repository or download the script.
2. Install the required packages:

```bash
pip install nltk
```

3. Download NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Usage

1. Place your text file (e.g., `alice29.txt`) in the `resources` folder.
2. Run the script:

```bash
python text_processing.py
```

### Output Files:
- `cleaned.txt`: Cleaned text (non-alphabetic characters removed and converted to lowercase).
- `words.txt`: Tokenized words (with stopwords removed).
- `top10words.txt`: Most common words and their counts.
- `time_compares.txt`: Time taken for each step (cleaning, tokenization, stopwords removal).

## Example Output:

After running the script, you'll get:
- **`cleaned.txt`**: The cleaned text.
- **`words.txt`**: Tokenized and stopword-removed words.
- **`top10words.txt`**: Top 10 frequent words with their counts.
- **`time_compares.txt`**: Execution time comparison for each step:

    ```
    Total Time: 10.25321 seconds
    Tokenizing Time: 2.34567 seconds
    Stopwords Removal Time: 6.67890 seconds
    ```


