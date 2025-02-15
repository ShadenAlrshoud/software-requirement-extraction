# 🚀 **Intelligent Requirement Elicitation**
🔍 **Automatically Extracting Software Requirements from App Reviews using Unsupervised Learning and LLMs**

## 📌 **Project Overview**
This project leverages **unsupervised learning** and **large language models (LLMs)** to **automatically extract software requirements** from user reviews of mobile applications.  

By **clustering** similar user reviews and **summarizing** them into structured software requirements, the project aims to:  
✅ **Reduce redundancy** in user feedback analysis  
✅ **Enhance requirement extraction** for software teams  
✅ **Streamline the software development process**  

---

## ✨ **Key Features**
✅ **Automated Clustering:** Groups similar user reviews using **BERTopic** with **SBERT embeddings**.  
✅ **Unsupervised Learning:** Eliminates the need for extensive **labeled datasets**.  
✅ **Scalable Approach:** Can be applied to any **app review dataset**.  
✅ **Requirement Generation:** Uses **GPT-4o** to generate **formal system requirements** from clustered reviews.  
✅ **Noise Filtering:** Implements techniques to **handle irrelevant or low-quality reviews**.  

---

## 📥 **Installation**
Since this project is executed in a **Kaggle Notebook**, minimal installation is required.

1️⃣ **Open the Kaggle Notebook**  
2️⃣ **Ensure Dependencies Are Installed** (The notebook automatically installs required libraries)  

If running locally, install the necessary dependencies:
```bash
pip install nltk bertopic openai pandas plotly umap-learn
