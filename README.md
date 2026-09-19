# 📧 Email Automation

<img width="1918" height="820" alt="email automation" src="https://github.com/user-attachments/assets/387dfcb2-9753-48b2-b203-07b656c56102" />

---

## 🔑 Setup Instructions

### 1️⃣ Get Your Groq API Key  
Generate an API key here:  
**https://console.groq.com/keys**

Update the value of `GROQ_API_KEY` inside `app/.env`.

---

## ⚙️ Installation & Running the App

### **1. Create a virtual environment**
```bash
python -m venv venv
````

### **2. Activate the virtual environment**

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### **3. Install uv**

```bash
pip install uv
```

### **4. Sync dependencies**

```bash
uv sync
```

### **5. Run the Streamlit app**

```bash
streamlit run app/main.py
```


