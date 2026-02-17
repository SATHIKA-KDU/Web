# AI-Assisted Policy Adaptation System 🇱🇰⚡

This project is a web-based AI-assisted system developed to **summarise a real-world policy document** and **generate scenario-based adapted policy drafts** using the generated summary.

The selected policy document for this project is:

📌 **National Energy Policy and Strategies of Sri Lanka (2019)**

---

## 📌 Project Objective

In real life, policy documents are often complex and not used exactly as written.  
This system helps users to:

- Upload or paste a policy document
- Generate a clear, concise summary using NLP-based summarisation
- Select different scenarios
- Generate adapted policy drafts for each scenario using Generative AI
- Compare how the same policy changes under different contexts

---

## ✅ Key Features

### 🔹 Policy Summarisation Module
- Extracts policy text from PDF or pasted input
- Applies preprocessing (cleaning, tokenization)
- Generates a concise summary using **TF-IDF sentence scoring**

### 🔹 Scenario-Based Policy Draft Generation Module
- Uses the policy summary as input
- Generates policy drafts based on selected scenario prompts
- Produces multiple outputs from the same summary

### 🔹 Web Application Interface
- Left panel: summarisation
- Right panel: scenario selection + generation
- Supports regeneration and iteration

---

## 🧩 Scenarios Used

### Scenario 1: Rural Electrification and Energy Access
Focus on:
- rural communities
- affordability
- solar mini-grids and off-grid energy
- equitable access to modern energy services

### Scenario 2: Industrial Energy Efficiency and Carbon Reduction
Focus on:
- industrial sector energy audits
- compliance monitoring
- energy efficiency improvements
- carbon emission reduction strategies

---

## 🛠️ Technologies Used

- Python
- Streamlit (Web Application)
- PyMuPDF (PDF Text Extraction)
- NLTK (Sentence Tokenization)
- Scikit-learn (TF-IDF Summarisation)
- Transformers (Text Generation Model)

---

## 📂 Project Structure

