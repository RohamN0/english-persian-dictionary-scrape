# English-Persian Mathematical Dictionary CSV

A focused dataset of English–Persian mathematical terms scraped from IR-Translate. This repository hosts a CSV file containing two columns:

English: Mathematical words and terminology in English

Persian: Corresponding translations in Persian (Farsi)

---

## 📥 Data Source

The data was extracted from the IR-Translate Dictionary pages (p=1 to p=448), specifically filtering for mathematical vocabulary. For more math terms and translations, visit the IR-Translate homepage.

---

## 📁 Repository Structure

.
├── data/
│   └── en-fa-math-dictionary.csv  # Dataset of English-Persian mathematical terms
├── LICENSE                       # MIT License
└── README.md                     # This file

---

## 🚀 Usage

Clone the repository:

git clone https://github.com/<username>/english-persian-math-dictionary-scrape.git
cd english-persian-math-dictionary-scrape

Load the CSV in Python:

import pandas as pd

df = pd.read_csv("data/en-fa-math-dictionary.csv")
print(df.head())

Or open it in your favorite spreadsheet application.
