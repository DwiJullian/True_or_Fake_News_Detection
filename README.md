# 📰 Fake News Detection using LSTM

This project is a Deep Learning–based text classification model designed to detect whether a news article is **real or fake**.

The model leverages **Long Short-Term Memory (LSTM)** architecture and is combined with additional layers such as **Dense** layers or **GlobalAveragePooling1D** to improve performance.

> ⚠️ This project is implemented as a model-only experiment and has not been deployed into a web or production application.

---

# 🎯 Background

The rapid spread of misinformation has become a major global issue. Fake news can influence public opinion, create social unrest, and spread misleading narratives.

This project aims to explore how Deep Learning, specifically sequential neural networks, can be used to classify news articles as:

* **1 → Real News**
* **0 → Fake News**

---

# 🧠 Project Objective

* Build multiple LSTM-based models for fake news classification
* Compare different architectures
* Select the best-performing model based on accuracy and overfitting behavior
* Achieve high predictive performance while maintaining good generalization

---

# 🏗 Model Architecture

Several experimental architectures were implemented inside the notebook.

### Core Components:

* **Embedding Layer** – Converts words into dense vector representations
* **LSTM Layer** – Captures sequential dependencies and contextual meaning in text
* Additional layers experimented with:

  * Dense Layer
  * GlobalAveragePooling1D
* Output Layer:

  * Sigmoid activation for binary classification

---

# 🧪 Experimental Approach

This project was structured as a comparative experiment:

* Multiple models were trained with different architectural combinations
* Performance was evaluated across:

  * Training accuracy
  * Validation accuracy
  * Loss curves
* Special attention was given to detecting **overfitting**

Model selection criteria:

* High validation accuracy
* Stable training–validation gap
* Minimal overfitting behavior

---

# 📊 Model Performance

* Best model achieved **accuracy above 90%**
* Demonstrated strong ability to distinguish between real and fake news
* Selected model showed better generalization compared to other experimental architectures

Although multiple models were tested, the final chosen architecture balanced:

* High accuracy
* Controlled overfitting
* Stable learning curve

---

# ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* LSTM (Long Short-Term Memory)
* Dense Layers
* GlobalAveragePooling1D
* Tokenization & Text Preprocessing

---

# 🔧 Training Strategy

* Text cleaning and preprocessing
* Tokenization and padding
* Train–validation split
* Multiple model training experiments
* Performance comparison and best-model selection

---

# 📌 Project Status

✅ Multiple experimental models implemented
✅ Best-performing model selected
❌ No deployment (model-only project)

This project serves as an experimental study on sequential deep learning architectures for text classification.

---

# 💡 Key Takeaways

* LSTM is effective for sequential text classification tasks
* Architectural variations (Dense vs GlobalAveragePooling1D) impact generalization
* High accuracy alone is not enough — overfitting must be considered
* Proper model comparison is essential in experimental deep learning workflows

---

# 🚀 Future Improvements

* Implement attention mechanisms
* Use Bidirectional LSTM
* Try transformer-based models (e.g., BERT)
* Deploy as a web-based news verification tool
* Integrate real-time news scraping

---

This project demonstrates how deep learning can be applied to combat misinformation by automatically detecting fake news with high accuracy.
