# SWAG-Based Tamil Query Response Grading System 🧠🇮🇳

This project is a Final Year Research Work focused on building a **Query-Response (Q-R) grading system** for Tamil textual content using **SWAG-based Layered Bi-directional Transformers**.

---

## 🧠 Project Abstract

> SWAG (Situations With Adversarial Generations) enables grading of Tamil textual answers using a bi-directional transformer architecture. The system adapts to phonetic inflections, both context-sensitive and context-free, improving grading accuracy. It integrates BERT, GLUE, and other models, and uses custom embedding logic for Tamil language processing.

---

## ⚙️ Tech Stack

- 🔹 Python
- 🔹 TensorFlow (with `swag2i_tensorflow` library)
- 🔹 BERT / GPT-style Transformers
- 🔹 WordPiece Embeddings
- 🔹 Custom Tamil Dataset (Query-Response pairs)
- 🔹 Masked Language Model (MLM)
- 🔹 Fine-tuning, Dropout, L1/L2 Regularization

---

## 🔬 Features

- ✅ Tamil Phonetic Grading with Q-R input
- ✅ Handles context-sensitive + context-free cases
- ✅ Residual connections, Positional encodings
- ✅ Dynamic embedding logic
- ✅ Scalable to other Dravidian languages
- ✅ SWAG + BERT/GLUE integrated

---

## 📊 Dataset Format

Each input is in `<Query, Response>` pair format, converted into WordPiece embeddings and fed into SWAG architecture.

- CLS token: used for classification  
- SEP token: separates query from response

---

## 🖼 Architecture (From Report)

 Architecture Diagram here  
**_![Architecture]([architecture.png](https://drive.google.com/file/d/1dfRxI2F6QbeqC-OLOqr7ZLPMF-TWsinF/view?usp=sharing))_**

---

## 🔎 Future Improvements

- Adding multilingual model support  
- Integration with real-time Tamil QA bots  
- API-based deployment with Flask  

---

## 🙌 Credits

> This project was developed as part of B.E CSE Final Year Research Work (2025) under the guidance of [Thivaharan].

---

## 📄 Paper / Report

If you want to read the full paper, click [here]([[link-to-your-pdf-drive-or-website](https://drive.google.com/file/d/1aA2BA36cj9W8Rq8865E8v6Bd-4ASMunI/view?usp=drivesdk)](https://drive.google.com/file/d/1JFIMy-nI-H3yahjZ2cA25ADhfY5Mignh/view?usp=sharing))

---

## 👨‍💻 Author

- **Surya Narayanan** – [LinkedIn]([https://linkedin.com/in/Sur](https://www.linkedin.com/in/surya-narayanan-590357242?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)) | [GitHub](https://github.com/suryanarayanan20)

---
