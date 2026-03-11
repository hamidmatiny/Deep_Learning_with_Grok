---

# Advanced Deep Learning: Code-Along Series 🚀

This repository contains a intensive "Code-Along" curriculum focused on mastering sequence models, Transformers, and Large Language Models (LLMs) using **PyTorch** and **Hugging Face**.

## 📌 Learning Philosophy

From this module forward, the focus shifts to **implementation-first learning**:

1. **Intuition:** Short, visual primers to understand the "Why."
2. **Code-Along:** 30–120 minute deep dives where concepts are built live, line-by-line.
3. **Application:** Weekly exercises and mini-projects to solidify the concepts.

---

## 🗓️ Syllabus Overview

### Week 1: Recurrent Neural Networks (RNNs) & LSTMs

*Focus: Handling sequential data and overcoming the vanishing gradient problem.*

* **Intuition:** [StatQuest RNNs](https://www.youtube.com/watch?v=SEnRbNS1nSA) & [LSTMs](https://www.youtube.com/watch?v=YCzL96nL7j0)
* **Code-Along:** [PyTorch RNN, LSTM, GRU](https://www.youtube.com/watch?v=0LhiS6Yu2q0) by Python Engineer.
* **Deliverable:** `advanced_dl_rnns.ipynb` — A character-level name classifier and sine-wave predictor.

### Week 2: Seq2Seq + Basic Attention

*Focus: The foundation of Neural Machine Translation (NMT).*

* **Intuition:** [StatQuest Attention](https://www.youtube.com/watch?v=SysgYptB198) & [Illustrated Seq2Seq](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)
* **Code-Along:** [Seq2Seq with Attention in PyTorch](https://www.youtube.com/watch?v=1Q2jz3aK2zA) by Aladdin Persson.
* **Deliverable:** An English → French translator and an addition task solver ("123+456" → "579").

### Weeks 3–4: Transformers – The Core 💎

*Focus: Understanding the architecture that changed AI.*

* **Intuition:** [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
* **Main Event:** [Let's build GPT: from scratch](https://www.youtube.com/watch?v=kCc8FmEb1nY) by Andrej Karpathy.
* **Mini-Project:**
* Build a character-level GPT trained on Shakespeare.
* **Twist:** Adapt the model to generate song lyrics or short stories.
* *Reference:* [Karpathy's nanoGPT](https://github.com/karpathy/nanoGPT)



### Week 5: Pre-trained Transformers & Fine-Tuning

*Focus: Leveraging SOTA models via the Hugging Face ecosystem.*

* **Intuition:** [Hugging Face NLP Course (Ch. 1-3)](https://huggingface.co/learn/nlp-course/chapter1/1)
* **Code-Along:** [Fine-Tuning BERT for Sentiment Analysis](https://www.youtube.com/watch?v=42m6YGwH5-8) by James Briggs or [Full LLM Fine-Tuning Crash Course](https://www.youtube.com/watch?v=SPNaP4ik9a4).
* **Deliverable:** A fine-tuned DistilBERT model for sentiment analysis on the IMDb dataset.

### Week 6: Capstone Wrap-up

*Focus: Integration and Comparison.*

* **Notebook:** `advanced_deep_learning_project.ipynb`
* **Tasks:** - Compare "From-Scratch" Transformer performance vs. "Fine-tuned" SOTA models.
* Visualize attention weights.
* Generate and document sample outputs.



---

## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **Frameworks:** [PyTorch](https://pytorch.org/), [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
* **Environment:** Google Colab (GPU Accelerated)
* **Tracking:** Git/GitHub

## 📂 Repository Structure

```bash
.
├── Week_01_RNN_LSTM/
│   └── advanced_dl_rnns.ipynb
├── Week_02_Seq2Seq/
│   └── seq2seq_attention.ipynb
├── Week_03_04_Transformers/
│   └── nanoGPT_reproduction.ipynb
├── Week_05_HuggingFace/
│   └── bert_finetuning.ipynb
└── Week_06_Final_Project/
    └── advanced_deep_learning_project.ipynb

```

---

*Follow my progress as I build these models from the ground up!*
