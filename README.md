# 📂 Topic-Modelling-using-Bunka-with-Topics

📝 Problem Statement:
Perform topic modeling to uncover dominant themes within patent texts related to next-generation telecom technologies.

🎯 Task:
Apply Bunka to perform topic modeling exclusively on the subset of patents labeled as **4G**, in order to identify key focus areas and trends within 4G innovation.


🧠 Bunka Topic Modeling Pipeline

1️⃣ 🧹 Text Cleaning
   - 🔤 Lowercasing
   - ❌ Removing special characters

2️⃣ ✂️ Tokenization
   - 🧩 Splitting text into tokens

3️⃣ 🔗 Embedding
   - 🤖 Using Sentence Transformers (e.g., MiniLM, BERT) to convert text into vectors

4️⃣ 📉 Dimensionality Reduction
   - 📊 Applying UMAP to reduce vector dimensions

5️⃣ 🧱 Clustering
   - 🧭 Utilizing HDBSCAN to group similar documents

6️⃣ 🏷️ Topic Keyword Extraction
   - 🧠 Identifying representative keywords for each cluster

✅ Output:
   - 📂 Topics with associated keywords
   - 📈 Visualizations for topic analysis

