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

## 🔄 Airtable Setup Instructions  

### **1️⃣ Create an Airtable Account**  
Go to **[Airtable.com](https://airtable.com/)** and sign up or log in.  

### **2️⃣ Create a New Base**  
- Click **"Create a Base"** (or open an existing one).  
- Note down your **Base ID** (found in the URL after `/app`).  

### **3️⃣ Create a Table**  
- Name the table **(e.g., "Sample")**.  
- Add the following **columns (fields)**:  
  - `Name` → Type: **Single line text**  
  - `Email` → Type: **Email**  
  - `Age` → Type: **Number**  

### **4️⃣ Get Your API Key & Base ID**  
- Go to **[Airtable API](https://airtable.com/api)**  
- Select your base → Find your **Base ID** at the top.  
- Click on your profile (top-right corner) → **"Developer Hub"** → **"API Key"**  
- Copy your API key and replace it in the code.  

---

## ▶️ Run the Project  

- **Simply double-click** on `index.html` to open it in a browser ✅  
- Or use a **local server** (optional for better performance):  

  ```sh
  python -m http.server 8000  # Using Python  
  npx serve                  # Using Node.js
  
