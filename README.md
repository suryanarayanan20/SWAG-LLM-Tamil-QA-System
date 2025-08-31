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

Each input is in <Query, Response> pair format, converted into WordPiece embeddings and fed into SWAG architecture.

- CLS token: used for classification  
- SEP token: separates query from response

---

## 🖼 Architecture (From Report)

## 🏗️ Architecture Diagrams
[![Architecture Diagram 1](https://img.shields.io/badge/Architecture%20Diagram%201-view%20on%20Drive-blue?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1kPN-YbF-bT19FOGwxsJKGKaw5MdShzUf/view?usp=drive_link)  
[![Architecture Diagram 2](https://img.shields.io/badge/Architecture%20Diagram%202-view%20on%20Drive-blue?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/10TSaNKWlw8r31FE3njhQvmz3NyI1w4xP/view?usp=drive_link)

---

## 🔎 Future Improvements

- Adding multilingual model support  
- Integration with real-time Tamil QA bots  
- API-based deployment with Flask  

---

## 🙌 Credits

> This project was developed as part of B.E CSE Final Year Research Work (2025) under the guidance of [Thivaharan].

---
>## 🎥 Demo Video  
[![Demo Video](https://img.shields.io/badge/Demo%20Video-view%20on%20Drive-red?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1G099bz2vhskxDhVxSvC8bQOJqq-TxRbH/view?usp=drive_link)

## 📄 Paper / Report
[![Patent Publication](https://img.shields.io/badge/Patent%20Publication-view%20on%20Drive-green?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1EuzM8frbSM9_psxXouDCEaNt1WkMV-kq/view?usp=drive_link)

---

## 👨‍💻 Author

- **Surya Narayanan** – [LinkedIn]([https://linkedin.com/in/Sur](https://www.linkedin.com/in/surya-narayanan-590357242?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)) | [GitHub](https://github.com/suryanarayanan20)

---
