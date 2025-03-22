# 🌟 Airtable Data Manager  

A simple web app to **submit and fetch data from Airtable** using JavaScript.  

---

## 🚀 Features  

✔️ **Submit data** directly to Airtable  
✔️ **Fetch and display stored records** in real-time  
✔️ **Prevents duplicate submissions** (Disables submit button after clicking)  
✔️ **Re-enables submission when the user edits any field**  
✔️ **Works directly in the browser** (No backend required)  

---

## 🔧 How to Use  

### 1️⃣ **Copy or Download** the complete code of `index.html`  

### 2️⃣ **Replace the following placeholders** in `index.html` with your actual Airtable credentials:  

- 🔑 **API Token** → Replace `"YOUR_AIRTABLE_TOKEN"`  
- 🆔 **Base ID** → Replace `"YOUR_BASE_ID"`  
- 📌 **Table Name** → Ensure it matches your Airtable table  

⚠️ **WARNING:** Using API keys directly in source code is a **security risk**!  
Your Airtable API key can be exposed in the browser. Consider using a **backend server** for better security.  

---

## ▶️ Run the Project  

- **Simply double-click** on `index.html` to open it in a browser ✅  
- Or use a **local server** (optional for better performance):  

  ```sh
  python -m http.server 8000  # Using Python  
  npx serve                  # Using Node.js
  
