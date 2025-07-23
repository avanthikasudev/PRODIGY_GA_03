# 🧠 Text Generation with Markov Chains

This project implements a simple yet powerful text generation model using **Markov Chains** with trigrams. It analyzes a given input text file and generates new sentences that statistically resemble the training text. The project is implemented in Python and presented in a Jupyter Notebook.

---

## 📁 Project Files

| File Name                             | Description                                               |
|--------------------------------------|-----------------------------------------------------------|
| `Text_Generation_with_Markov_Chains.ipynb` | Main Jupyter Notebook containing code and output        |
| `input.txt`                          | Source text file used to build the Markov model          |
| `README.md`                          | Project documentation                                     |

---

## 📚 How It Works

1. **Text Preprocessing**  
   Reads and cleans the input text, splitting it into a list of words while preserving punctuation.

2. **Trigram Markov Chain**  
   Constructs a trigram-based Markov chain where each key is a 3-word tuple and the value is a list of possible next words.

3. **Sentence Generation**  
   Takes a user-provided 3-word starting prompt and generates a sentence by randomly selecting next words based on the chain.

---

## 🛠️ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- `random` – for probabilistic next word selection  
- `re` – for text tokenization and cleanup

---

