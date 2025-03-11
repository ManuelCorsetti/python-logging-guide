# Python Logging Guide

Welcome to the **Python Logging Guide**! This GitHub Pages site serves as a reference for best practices in Python logging, with a focus on **GCP Logging** and cloud-based log management.

## 📌 How to View the Guide
The documentation is hosted on **GitHub Pages** at:
👉 [https://manuelcorsetti.github.io/python-logging-guide/](https://manuelcorsetti.github.io/python-logging-guide/)

## 🛠 How to Make Changes
If you need to update the documentation, follow these steps:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/manuelcorsetti/python-logging-guide.git
cd python-logging-guide
```

### 2️⃣ Modify or Add Documentation
All documentation files are inside the `docs/` folder. To update existing content, open and edit the corresponding `.md` file.

For example, to edit the homepage:
```bash
nano docs/index.md
```
To create a new page:
```bash
touch docs/gcp-logging.md
```

### 3️⃣ Install MkDocs
This project uses **MkDocs with Material Theme** to generate a professional-looking site.
```bash
pip install mkdocs-material
```

### 4️⃣ Preview Changes Locally
```bash
mkdocs serve
```
Then open **http://127.0.0.1:8000/** in your browser.

### 5️⃣ Commit and Push Changes
```bash
git add docs/
git commit -m "Updated logging best practices"
git push origin main
```

### 6️⃣ Deploy to GitHub Pages
```bash
mkdocs gh-deploy
```

Once changes are pushed and deployed, GitHub Pages will automatically update the website within a few minutes.

## 📖 Topics Covered
- Python Logging Basics
- Logging Levels and Formatters
- Structuring Logs for Cloud Environments
- GCP Logging with `google-cloud-logging`
- Best Practices for Log Storage & Retrieval

## ❓ Need Help?
If you have any questions or want to contribute, feel free to open an **issue** or **pull request** in this repository.

Happy logging! 🚀
