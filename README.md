# zero-shot-qa-nlp

# 🧠 Zero-Shot Question Answering Using Pre-Trained Models

A  NLP project developed for Intro to Natural Language Processing

This research explores how advanced multilingual pre-trained models like **mBERT** and **XLM-RoBERTa** can be used to build a scalable, domain-agnostic zero-shot question answering system without the need for additional training on domain-specific data.

## ✨ Key Highlights

- 🔍 **Zero-Shot Learning**: Model answers questions from unseen domains with no additional training.
- 🌐 **Multilingual Support**: Leverages mBERT and XLM-RoBERTa for broader generalization.
- 📊 **Natural Questions Dataset**: Used for evaluation to reflect real-world, open-domain questions.
- 🔧 **End-to-End Pipeline**: From data preprocessing and model inference to performance evaluation and visualization.

---

## 📌 Objectives

- Build a flexible and scalable question answering system using **zero-shot learning**.
- Minimize the need for domain-specific retraining.
- Evaluate system performance using **Natural Questions**, a real-world benchmark dataset.
- Demonstrate adaptability across domains and languages.

---

## 🧠 Models Used

- [**mBERT**](https://arxiv.org/abs/1810.04805): Multilingual BERT model trained on 104 languages.
- [**XLM-RoBERTa**](https://arxiv.org/abs/1911.02116): Robust cross-lingual language model.

These transformer-based models are used with no fine-tuning to evaluate zero-shot generalization capabilities.

---

## 📚 Dataset: Natural Questions

- Source: [Google Research](https://ai.google.com/research/NaturalQuestions)
- Contains real user queries and corresponding Wikipedia context passages.
- Each item includes: `id`, `context`, `options`, `correct`, and `is_possible`.

---

## 🧪 Experimental Results

- ✅ Successfully answered diverse questions using only pre-trained models.
- ⚠️ Struggled with ambiguous or extremely context-sensitive questions.
- 📈 Metrics used: Accuracy, Precision, Recall, F1-Score
- 📉 Error analysis reveals scope for context enrichment and hybrid modeling.

---

## 👥 Authors

- Shashank Yelagandula
- Bhavesh Kurella
- Akhil Reddy Chimmula

- Course: AIT526-001 – NLP
- Instructor: Dr. Ray Islam
- Institution: George Mason University
- Date: May 9, 2024
---

## 🔮 Future Work

- Incorporate more advanced models like LLama, Mistral, or Gemma.
- Improve multilingual robustness and context comprehension.
- Expand to other NLP tasks: summarization, classification, information extraction.

---
## 🙌 Acknowledgments

- Google Research for the Natural Questions dataset.
- Hugging Face & SimpleTransformers for their open-source models.
- George Mason University – NLP Course Spring 2024

