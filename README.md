# 📚 Riyaaz Sir's Premium Learning Portal

> **A fully-featured Learning Management System (LMS) running 100% FREE on GitHub Pages!**

---

## 🌟 Student Portal Features

| Feature | Description |
|---------|-------------|
| 🎨 **Beautiful UI** | Modern glassmorphism design with smooth animations |
| 🔍 **Smart Search** | Instantly search papers by name or subject |
| 🏷️ **Subject Tags** | Color-coded tags for easy identification |
| 📅 **Upload Dates** | See when each paper was uploaded |
| 📱 **Fully Responsive** | Works perfectly on mobile, tablet, and desktop |
| 🌙 **Dark/Light Mode** | Toggle between themes (saved automatically) |
| ⚡ **Instant Downloads** | One-click PDF downloads |
| 🔢 **Paper Counter** | Shows total available papers |

---

## 🔐 Admin Dashboard Features

| Feature | Description |
|---------|-------------|
| 🔒 **Secure Login** | GitHub Token authentication |
| 💾 **Remember Me** | Token saved securely in browser |
| 📤 **Easy Upload** | Upload PDFs with name, subject, and description |
| ✏️ **Edit Papers** | Change name, subject, or description anytime |
| 🔄 **Replace PDF** | Swap out old PDFs without changing the listing |
| 👁️ **Hide/Show** | Temporarily hide papers from students |
| 🗑️ **Delete Forever** | Permanently remove papers |
| 📊 **Stats Dashboard** | See total papers, live count, hidden count |
| 🎨 **Dark Theme** | Easy on the eyes for late-night work |
| 📋 **Activity Log** | See recent actions |

---

## 🚀 How to Use

### For Students:
Simply visit: `https://YOUR-USERNAME.github.io/sample-papers/`

### For Admin (Riyaaz Sir):
1. Visit: `https://YOUR-USERNAME.github.io/sample-papers/admin.html`
2. Enter your GitHub Personal Access Token
3. Start uploading and managing papers!

---

## 🔑 How to Get Your Admin Token

1. Go to GitHub → Click your Profile Picture → **Settings**
2. Scroll down → **Developer Settings** → **Personal Access Tokens** → **Tokens (classic)**
3. Click **Generate new token (classic)**
4. Name: `LMS Admin Key`
5. Expiration: `No expiration`
6. Scopes: Check `repo` (full control)
7. Click **Generate token**
8. **COPY AND SAVE IT SECURELY!**

---

## 📁 File Structure

```
sample-papers/
├── index.html      # Student Portal
├── admin.html      # Admin Dashboard
├── papers.json     # Database
├── papers/         # PDF Storage (auto-created)
└── README.md       # This file
```

---

## ⚙️ Configuration

To change the repository owner, edit `admin.html` line ~180:
```javascript
const REPO = 'YOUR-USERNAME/sample-papers';
```

---

## 💡 Tips for Riyaaz Sir

1. **Bookmark the admin page** for quick access
2. **Use descriptive names** like "Class 10 - Physics - 2024 Boards"
3. **Use consistent subjects** like "Physics", "Chemistry", "Maths"
4. **Hide papers** before exams, then reveal them after
5. **Replace PDFs** if you find errors - students won't notice!

---

Made with ❤️ for Riyaaz Sir's Students
