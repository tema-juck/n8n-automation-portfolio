# Email → PDF Invoice → Google Drive (n8n Workflow)

This workflow automates order processing from incoming emails.  
When a customer sends an order via email, n8n automatically generates a PDF invoice and saves it to Google Drive. Optionally, the invoice can be sent back to the customer.

---

## 🚀 Features
- ✅ Capture incoming emails (IMAP/Gmail)  
- ✅ Extract customer and order details  
- ✅ Generate a professional **PDF invoice**  
- ✅ Save the invoice to Google Drive  
- ✅ (Optional) Send the invoice back to the customer  

---

## 📂 Workflow Overview
1. **Email Trigger** → Detects new orders.  
2. **Parse Fields** → Extracts sender, subject, and message.  
3. **Generate PDF** → Creates a simple invoice.  
4. **Google Drive Upload** → Stores the invoice.  
5. **Gmail Send (optional)** → Sends invoice back to customer.  

---

## 🖼️ Screenshots
- Example incoming email  
- Generated PDF invoice  
- Workflow in n8n  
- Google Drive with uploaded file  

---

## 💡 Use Cases
- Small businesses generating invoices from email orders  
- Automating paperwork for service requests  
- Quick prototype for CRM + billing  

---

## 🛠️ Technologies
- n8n  
- Gmail API (Email trigger + send)  
- PDF Generate node  
- Google Drive API  
