# Deconstructing Synthetic Intelligence: Fine-Grained Emotion Recognition and the Ethics of Algorithmic Consumer Manipulation

This project bridges the gap between natural language processing (NLP) and behavioral economics. It explores the sociotechnical implications of "Artificial Empathy"—investigating how modern transformer models can map fine-grained human emotional states and the ethical risks this presents for consumer decision-making.

---

## 📘 Foundational Research
The theoretical and sociotechnical framework of this implementation is built directly upon my philosophical thesis:
* **Thesis Title:** *Emotions and Economic Decision Making* (Calvary Institute of Philosophy and Religion, Jan 2025).
* **Core Argument:** Human choices are fundamentally driven by emotional cognitive lenses (such as fear and anger) rather than pure linear rationality. Therefore, an AI system capable of highly accurate "Artificial Empathy" can be weaponized to manipulate consumer behavior.
  * [Read the Background Thesis...](EMMANUEL-1.pdf)

---

## 🛠️ Project Architecture & Roadmap

### 1. The Dataset
* **GoEmotions (Google AI):** A human-annotated dataset of 58,000 English Reddit comments mapped to 27 distinct, fine-grained emotional categories (e.g., *remorse, realization, fear, anger, joy*).

### 2. Technical Execution
* **Baseline Model (System 1):** A classic machine learning model (TF-IDF Vectorization + Logistic Regression) to establish how basic algorithms handle word frequencies.
* **Advanced Model (System 2 / SOTA):** A fine-tuned multilingual Transformer model (e.g., BERT/IndicBERT) to demonstrate the technical leap in capturing context, slang, and subtle emotional variance.

### 3. Sociotechnical & Ethical Analysis
* Analyzing the trade-offs between model accuracy and user manipulation.
* Evaluating the ethics of commercializing "Emotional Contagion" and automated "Emotion Work" via conversational agents.

---

## 🤖 Project Context & Disclosures
* **Development Type:** Independent self-study project conducted during vacation using open university course structures (inspired by Stanford CS 281).
* **AI Usage Statement:** Assisted by an AI collaborator for structural planning, code debugging, boilerplate machine learning setups, and document formatting. The final experimental conclusions and sociotechnical critiques are verified and owned by the author.
  
📊 Experimental Results: System 1 vs. System 2
To test the viability of "Artificial Empathy," this project evaluated two distinct machine learning models on the GoEmotions dataset (a dataset featuring 28 fine-grained emotional categories, which is notoriously difficult even for human annotators to agree upon).

System 1 Baseline (Logistic Regression): Analyzing mere word frequencies via TF-IDF yielded an accuracy of 47.05%. This represents a rapid, blunt-force approach to emotion detection, which misses the crucial nuances of human communication.

System 2 Contextual Model (RoBERTa Transformer): Utilizing a state-of-the-art transformer architecture to analyze deep linguistic context resulted in a significant leap to 54.40% accuracy.

⚖️ Sociotechnical Conclusion
While 54.40% may appear modest in binary classification tasks, in the realm of 28-category subjective emotional mapping, it is an exceptionally high performance metric. Random chance would yield only a ~3.5% accuracy.

This context-aware leap proves the core argument of the foundational thesis: modern natural language processing is highly capable of mapping fine-grained human emotional states. If an algorithm can accurately detect specific emotional vulnerabilities (such as Fear, Anger, or Desire) more than half the time simply by analyzing text, it possesses a statistically significant edge. This proves that Artificial Empathy is a viable, weaponizable tool for corporate entities seeking to bypass rational decision-making and manipulate consumer behavior through targeted algorithmic interventions.
