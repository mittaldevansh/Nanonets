# 📄 Nanonets Bill Parser & OCR Automation

An AI-powered document processing solution built using **Nanonets OCR**. This project demonstrates the automated extraction of data from unstructured billing documents and invoices, converting them into actionable structured data.

---

## 🚀 How it Works

1.  **Upload:** An image or PDF of a bill/invoice is uploaded to the Nanonets model.
2.  **AI Extraction:** The deep learning model identifies key fields (Date, Vendor, Amount, Tax, etc.) regardless of the document layout.
3.  **Validation:** The AI answers specific questions about the document's content.
4.  **Export:** The extracted data is processed and converted into structured formats like **Excel/CSV**.

---

## 📸 Process Showcase

### 1. Automated Data Extraction
The model identifies and extracts critical information from the uploaded bills. Below are the steps and queries handled by the AI:

| Question 1 & 2 | Question 3 & 4 |
|---|---|
| <img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_1.jpeg" width="400"> | <img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_3.jpeg" width="400"> |
| <img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_2.jpeg" width="400"> | <img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_4.jpeg" width="400"> |

### 2. Complex Query Handling
The AI is trained to answer specific questions based on the document's text logic.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_5.jpeg" width="800" alt="Final Question">

---

### 3. Data Transformation (Export to Excel)
Once the extraction is complete, the data is seamlessly converted into a structured Excel format for accounting and record-keeping.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Convert%20to%20excel.jpeg">

---

## 🌟 Key Features

* **Intelligent OCR:** Captures text even from low-quality scans or photos.
* **Zero-Shot Learning:** Understands fields like "Total Amount" or "Billing Address" without manual tagging for every new bill format.
* **Table Extraction:** Efficiently handles line items and tabular data within invoices.
* **Export Ready:** Instantly converts image data into **Excel (.xlsx)** or CSV.

---

## 🛠️ Technical Stack

* **Engine:** Nanonets AI (Pre-trained/Custom OCR Models)
* **Format Handling:** JPEG, PNG, PDF
* **Data Output:** JSON, CSV, Excel

---

## 🚀 Getting Started

1.  **Clone the Repo:** `git clone https://github.com/mittaldevansh/Nanonets.git`
2.  **Setup Nanonets:** Create an account at [Nanonets](https://nanonets.com/).
3.  **API Integration:** Use your API Key to send the images in this repo to the `Invoices` model endpoint.
4.  **Review Results:** Check the JSON response or the generated Excel file.

---

## 👤 Author
**Devansh Mittal**
* GitHub: [@mittaldevansh](https://github.com/mittaldevansh)
