# 🌧 RainDrop — Zero-Shot Classifier (English)

RainDrop is a **zero-shot text classification** model built from scratch — including the tokenizer, transformer architecture, and training pipeline.

It’s fully open-source, designed for deep understanding of category-label alignment using contrastive learning techniques.

This repo includes:
- The raw text data used for tokenizer and model training
- SentencePiece tokenizer training and vocab files
- Model architecture and training scripts
- Example inference pipeline

---

## ⚡ What is Zero-Shot Classification?

Zero-Shot Classification (ZSC) means predicting the correct label for a text without the label ever being seen during training.

For example, given the text:
> "The match ended with a dramatic penalty shootout"

And labels:
> `["Technology", "Health", "Sports"]`

RainDrop should confidently classify it as:
> 🏷️ **Sports**

No fine-tuning required. No examples per label needed.

---

## 💧 Why RainDrop?

Most open-source ZSC models:
- Use massive pretrained LLMs
- Are complex to fine-tune or deploy
- Depend on external APIs or datasets

**RainDrop is different.**  
It was built:
- 💥 From scratch — custom tokenizer, model, and training loop
- 🧠 Focused on **English**, ensuring language-specific precision
- 🔬 Optimized for **accuracy and clarity**, not just scale
- 🌱 Fully open-source and understandable at every level
