# 📚 Altaf Shaikh – Sindhi Literature, History, Philosophy & Politics Dataset (Preprocessed)

### 🏛️ Source: AMBILE Team  
### 📤 Compiled & Uploaded by: Abdul Majid Bhurgiri, *Institute of Language Engineering*  
### 🌐 Official Uploading Credit: [ambile.pk](https://ambile.pk/)  
### 📅 Release Year: 2025  
### 🌍 Language: Sindhi (سنڌي)  
### 📦 Dataset Type: Literary & Philosophical Sindhi Text Corpus  

---

## 📖 Overview

The **Altaf Shaikh Dataset** is a curated collection of Sindhi-language writings by renowned author **Altaf Shaikh**, focusing on **Sindhi literature, history, philosophy, and politics**.  

This dataset preserves the depth and diversity of Sindhi intellectual thought while serving as a valuable linguistic and cultural resource for **Natural Language Processing (NLP)** and **AI model training**.

It provides clean, structured text for research in **literary analysis**, **semantic understanding**, **text generation**, and **cultural knowledge representation**.

---

## 🧹 Data Cleaning & Preprocessing

All text has been **manually curated and automatically preprocessed** for research use.  
Cleaning steps include:

- ✅ Removal of **email addresses** and **URLs**  
- ✅ Removal of **special characters**, symbols, and **emojis**  
- ✅ Exclusion of **foreign-language** or non-Sindhi content  
- ✅ Normalization of Sindhi **Unicode characters**  
- ✅ Removal of numeric and formatting artifacts  
- ✅ Deduplication and whitespace cleanup  
- ✅ Conversion to **UTF-8** encoding  

The result is a **high-quality, clean Sindhi corpus** reflecting the linguistic and philosophical richness of Altaf Shaikh’s work.

---

## 📂 Dataset Contents

| File Name | Description | Format | Encoding |
|------------|-------------|---------|-----------|
| `AltafShaikh_Sindhi_Literature_Preprocessed.txt` | Clean Sindhi text from Altaf Shaikh’s works on literature, history, philosophy, and politics | `.txt` | UTF-8 |

Each line or paragraph corresponds to a preprocessed Sindhi text segment extracted from Altaf Shaikh’s literary and philosophical writings.

---

## 🧠 Research Applications

This dataset can be used for a wide range of **Sindhi NLP and cultural AI research** areas:

- 🗣️ **Language Modeling:** Train or fine-tune Sindhi text generation models  
- 💬 **Cultural Chatbots:** Build Sindhi chatbots grounded in historical or literary context  
- 🧩 **Embedding & Tokenization:** Fine-tune multilingual or monolingual embeddings  
- 📰 **Topic Classification:** Train models to detect literary, political, or historical themes  
- 📚 **Semantic Search:** Build retrieval systems for Sindhi philosophical or historical text  
- 🧠 **Digital Humanities:** Enable computational study of Sindhi thought and heritage  

---

## ⚙️ Technical Details

- **Data Type:** Literary, cultural, philosophical, and political text  
- **Language:** Sindhi (UTF-8)  
- **File Format:** Plain text (`.txt`)  
- **Source:** Altaf Shaikh’s public writings and Sindhi archives  
- **Preprocessing Level:** Fully cleaned and normalized  

### Example (Python)
```python
with open("AltafShaikh_Sindhi_Literature_Preprocessed.txt", "r", encoding="utf-8") as f:
    text = f.read()

print(text[:500])
