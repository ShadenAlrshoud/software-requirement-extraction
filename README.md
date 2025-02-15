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

---

## 📥 **Installation**
Since this project is executed in a **Kaggle Notebook**, minimal installation is required.

1️⃣ **Open the Kaggle Notebook**
2️⃣ **Ensure Dependencies Are Installed** (The notebook automatically installs required libraries)  

If running locally, install the necessary dependencies:
```bash
pip install nltk bertopic openai pandas plotly umap-learn
```

## ⚙️ **How to Run**
Since all steps are **included in a single notebook**, follow these steps:

### 🔹 **1. Run Preprocessing**
📌 **Cleans text**, removes stopwords, filters irrelevant reviews  
📌 Converts text to **lowercase and tokenizes words**  

### 🔹 **2. Perform Clustering**
📌 Uses **BERTopic** to **cluster similar reviews**  
📌 Assigns **topic labels** to each review  
📌 Saves the **processed dataset**  

### 🔹 **3. Generate Requirements Using GPT-4o**
📌 **Groups reviews by cluster**  
📌 Uses **GPT-4o** to generate **structured software requirements**  
📌 Outputs results in a **CSV file**  

#### 🚀 **Running the Notebook**
1️⃣ Open the **Kaggle Notebook**  
2️⃣ Click **"Run All"** to execute all cells in order  
3️⃣ Alternatively, run each **cell step by step** to track progress  

✅ Once complete, the extracted requirements will be **saved as a CSV file**.  

---

## 📊 **Dataset**
📌 The dataset consists of **app store reviews** from various domains.  
📌 **No labeled dataset** is needed, as we use **unsupervised learning**.  

---

## 🏆 **Results**
✅ Successfully extracted **structured requirements** from app reviews  
✅ Reduced the **need for manual review labeling**  
✅ Improved **efficiency** compared to traditional methods  

---

## 📈 **Evaluation & Limitations**
### ✅ **Strengths**:
- 🚀 **Eliminates the need for manual labeling**.  
- 🧠 **Groups semantically similar reviews effectively**.  
- 🔍 **Automates requirement generation for software engineers**.  

### ⚠️ **Limitations**:
- 🔹 **Clustering performance** depends on **dataset quality**.  
- 🔹 **Rare user concerns** may not form **strong clusters**.  
- 🔹 **Requirement summarization** relies on the **language model’s quality**.  

---

## 🔮 **Future Work**
🚀 **Enhancing clustering** to improve **requirement consolidation** and reduce **redundancy**.  
🧠 **Exploring fine-tuned LLMs** for **domain-specific accuracy** in requirement extraction.  
🔄 **Integrating active learning** for **semi-supervised improvements** in review labeling.  

---

## 👥 **Contributors**
💡 Developed by: **[Shaden Alrshoud]**, **[Maram Alshammary]**, **[Dalia Alasmari]**, **[Lama Alamari]**
📌 **Supervised by**: **[Suha Althunyyan]**  
