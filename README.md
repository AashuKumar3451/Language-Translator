# 🌐 Multilingual Neural Machine Translation

This repository contains a Jupyter notebook implementing multiple deep learning models for machine translation, including:
- **Urdu → English** (LSTM-based Seq2Seq)
- **English → French** (Transformer)
- **French → English** (Transformer)
- **English → Urdu** (LSTM-based Seq2Seq)

The project demonstrates how to translate across low-resource and high-resource language pairs using encoder-decoder and attention-based architectures.

---

## 🧠 Models Included

- ✅ **Model 1:** Urdu → English (Bidirectional LSTM Encoder → LSTM Decoder)
- ✅ **Model 2:** English → French (Transformer using Multi-head Attention)
- ✅ **Model 3:** French → English (Standard Seq2Seq LSTM)
- ✅ **Model 4:** English → French (Transformer using Multi-head Attention)

All models are implemented and evaluated within a single notebook for reproducibility and easier comparison.

---

## 📁 Dataset Links

Please download and extract the datasets into a `data/` directory at the root of the project.

- [🔗 Urdu-English Dataset](#https://www.kaggle.com/datasets/adnanzaidi/testurdu)   
- [🔗 French-English Dataset](#https://object.pouta.csc.fi/OPUS-GNOME/v1/mono/en.txt.gz)  

---

## 🚀 How to Run

> 💡 All code is inside `Language_Translation.ipynb`
>     The previous approach is in `previous_approach.ipynb` 

1. Clone this repository:
   ```bash
   git clone https://github.com/AashuKumar3451/Language-Translator
   
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Language_Translation.ipynb
   ```

---

## 🛠️ Features

- Integrated training and inference workflows
- EarlyStopping and learning rate control
- Model comparison in one place
- Custom preprocessing and tokenizer saving
- Sample translation outputs for qualitative testing

---

## 📚 References

- TensorFlow/Keras Official Docs  
- [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215)  
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)  
- Dataset sources (linked above)

---

