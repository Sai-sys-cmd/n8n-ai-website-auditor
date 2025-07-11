# 🧠 n8n AI Website Auditor

A no-code n8n workflow that:

- Scrapes a website  
- Extracts contact info (email, phone, address)  
- Uses OpenAI to audit the site (SEO, UX, speed, trust, etc.)

---

## ⚙️ How to Use

1. **Import `website-audit-workflow.json` into n8n**
2. Open the node called **“Edit Fields”**
3. 🔁 **Replace** the URL `"https://yourlink.com/"` with the site you want to audit
4. Make sure OpenAI is connected (use n8n free credits or your API key)
5. Click **“Execute Workflow”**

---

## 📝 Output Includes

- Company name, email, phone, address
- Contact or website link
- 5–10 audit suggestions (SEO, mobile, content, speed, trust)
