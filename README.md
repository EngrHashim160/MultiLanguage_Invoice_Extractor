# 🧾📸 MultiLanguage Invoice Extractor using Gemini Pro

This project is a smart **AI-powered invoice analysis app** that uses **Google's Gemini Pro (2.5)** to extract and interpret information from invoices in various languages. Built with **Streamlit** for an interactive user experience.

---

## 🚀 Features

- 📤 Upload invoice images (JPG, JPEG, PNG)
- 🧠 Ask questions about the invoice using a prompt
- 🌐 Works with multi-language invoices
- 🤖 Uses Gemini Pro 2.5 for large language + vision tasks

---

## 🛠️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/multilang-invoice-extractor.git
cd multilang-invoice-extractor
```

2. **Create a Virtual Environment (Optional)**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup API Key

1. Create a `.env` file in the root directory.
2. Add your **Google Generative AI API Key**:

```env
GOOGLE_API_KEY=your_gemini_api_key_here
```

---

## 🧪 Usage

```bash
streamlit run app.py
```

- Visit `http://localhost:8501`
- Upload an invoice image.
- Enter a prompt like:  
  `What is the total amount?`,  
  `Extract customer details`,  
  `What is the invoice date?`

---

## 📂 Project Structure

```
multilang-invoice-extractor/
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
└── .env                 # API key file (not in Git)
```

---

## 🌟 Example Use Cases

- 🧾 Upload an invoice and ask:  
  `"What items are included in this bill?"`
- 💬 Multilingual Support: Invoice in Urdu, Spanish, French, etc.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

- [Google Generative AI](https://ai.google.dev)
- [Streamlit](https://streamlit.io)