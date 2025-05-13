# 🧠 Azure Document Intelligence – Table Extractor

This project uses **Azure Document Intelligence (Form Recognizer)** to extract structured table data from scanned PDF documents — such as invoices, receipts, and forms.  
The model is trained by **Me** using Azure's no-code UI and works via REST API.

---

## ✨ Features

- ✅ Extract column-wise values from scanned PDFs
- 🧾 JSON output with clean field mappings
- 🧠 Powered by Azure AI (trained without code)
- 🔗 API-ready (works with cURL, Python, Postman)

---

## 🚀 How It Works

1. Upload individual scanned PDF pages (like invoice page 1, 2, etc.)
2. Call your custom-trained model using Azure's `analyze` endpoint
3. Get structured output — clean key-value pairs and tables

---

## 🛠️ Setup

### 1. 🔑 Create a `.env` file

Create a `.env` in the root folder:

```env
AZURE_FORM_RECOGNIZER_ENDPOINT=https://<your-region>.cognitiveservices.azure.com/
AZURE_FORM_RECOGNIZER_KEY=your_api_key_here
MODEL_ID=your_custom_model_id_here
