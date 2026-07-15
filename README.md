# 🧩 Custom Byte Pair Encoding (BPE) Tokenizer from Scratch

## 📌 Project Overview

This project implements the **Byte Pair Encoding (BPE)** algorithm from scratch using **Python** and **NumPy**. The tokenizer learns subword vocabulary by repeatedly merging the most frequent adjacent symbol pairs from a given text corpus.

---

## 🎯 Objective

- Implement the Byte Pair Encoding (BPE) algorithm from scratch.
- Learn subword vocabulary from a given corpus.
- Store merge rules for encoding.
- Encode and decode sample words.

---

## 🚀 Features

- Read text corpus
- Text preprocessing
- Character-level tokenization
- Word frequency calculation
- Pair frequency counting
- Merge frequent symbol pairs
- Build final vocabulary
- Encode words
- Decode words

---

## 📂 Project Structure

```text
BPE_Tokenizer/
│
├── corpus.txt
├── BPE_Tokenizer.ipynb
├── README.md
```

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- Jupyter Notebook

---

## 📚 Algorithm Steps

1. Read the corpus.
2. Split words into characters.
3. Add the `</w>` end-of-word symbol.
4. Count word frequencies.
5. Find adjacent symbol pairs.
6. Merge the most frequent pair.
7. Update the vocabulary.
8. Repeat the merge process.
9. Store merge rules.
10. Encode and decode words.

---

## 📄 Sample Corpus

```text
low
lower
lowest
new
newer
widest
```

---

## 📊 Output screenshots 


<img width="782" height="662" alt="OUT1" src="https://github.com/user-attachments/assets/fd9f5c15-5110-4f94-99ea-71fbd7d55e80" />



<img width="637" height="707" alt="OUT two" src="https://github.com/user-attachments/assets/719c1744-e542-4ee0-b063-c922b4dbc57b" />



<img width="962" height="692" alt="OUT three" src="https://github.com/user-attachments/assets/83c5c384-9f3e-499a-ac37-5877926c7e13" />





---

## 📈 Results

- Successfully implemented the Byte Pair Encoding algorithm.
- Generated merge rules from the corpus.
- Built the final vocabulary.
- Encoded and decoded words successfully.

---

## 💡 Applications

- Natural Language Processing (NLP)
- GPT Tokenization
- Language Models
- Text Compression


