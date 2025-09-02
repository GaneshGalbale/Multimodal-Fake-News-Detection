# 📰 Multimodal Fake News Detection  

This project implements a **fake news classification model** using **multimodal learning** by combining image and text features. We leverage **OpenAI’s CLIP (ViT-B/32)** model to extract joint embeddings, followed by a **neural network classifier** to detect misinformation effectively.  

---

## 📊 Results  
- Achieved **91.2% accuracy** on the **Fakeddit dataset** (benchmark for multimodal misinformation detection).  
- Outperforms unimodal baselines by effectively capturing cross-modal correlations.  

---

## ⚙️ Tech Stack  
- **Languages & Frameworks:** Python, PyTorch  
- **Models & Libraries:** CLIP (OpenAI), NumPy, Matplotlib, Scikit-learn, pandas, tqdm  
- **Platform:** Google Colab  

---

## 📂 Dataset  
- **Dataset Used:** [Fakeddit](https://github.com/entitize/Fakeddit)  
- Contains multimodal (image + text) fake news samples.  
- Preprocessed into suitable format for CLIP embeddings.  

---

## 🚀 Features  
- Multimodal (image + text) embedding extraction using CLIP (ViT-B/32)  
- Neural network classifier for misinformation detection  
- Evaluation on large-scale Fakeddit dataset  
- End-to-end pipeline built and tested on **Google Colab**  

---

## 📖 Usage
- **Open the project in Google Colab.**
- **Upload the notebook and connect to a GPU runtime.**
- **Run all cells to:**
- Load the Fakeddit dataset
- Extract multimodal embeddings using CLIP
- Train the neural network classifier
- Evaluate accuracy and visualize results
