# 📄 Nanonets Bill Parser & OCR Automation

An AI-powered document processing solution built using **Nanonets OCR**. This project demonstrates the automated extraction of data from unstructured billing documents and invoices, converting them into actionable structured data.

---

## 🚀 How it Works

1.  **Upload:** An image or PDF of a bill/invoice is uploaded to the Nanonets model.
2.  **AI Extraction:** The deep learning model identifies key fields (Date, Vendor, Amount, Tax, etc.) regardless of the document layout.
3.  **Validation:** The AI answers specific questions about the document's content.
4.  **Export:** The extracted data is processed and converted into structured formats like **Excel/CSV**.

---

## 📸 Project Showcase

### 1. Initial Data Extraction (Key Fields)
The first step involves identifying and extracting key fields such as dates, amounts, and vendor names from the raw document.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_1.jpeg" width="700" alt="Extraction Step 1" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">

---

### 2. Contextual Field Validation
The AI confirms and validates secondary fields like invoice numbers and specific line items.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_2.jpeg" width="700" alt="Extraction Step 2" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">

---

### 3. Verification of Amounts & Dates
Ensuring accuracy in the total amounts, due dates, and tax breakdown.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_3.jpeg" width="700" alt="Extraction Step 3" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">

---

### 4. Processing Specific Queries
Handling custom queries relevant to the specific type of bill or industry standards.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_4.jpeg" width="700" alt="Extraction Step 4" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">

---

### 5. Deep Learning Final Validation
A final comprehensive review by the AI to reconcile all extracted data before finalizing the output.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Question_5.jpeg" width="700" alt="Extraction Step 5" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">

---

### 6. Data Transformation (Export to Excel)
The final unstructured image data is converted into a structured Excel (.xlsx) format for easy auditing and integration.
<img src="https://github.com/mittaldevansh/Nanonets/blob/main/Convert%20to%20excel.jpeg" width="700" alt="Excel Output" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">

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
