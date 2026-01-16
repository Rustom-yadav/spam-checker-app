# 🚫 Spam Filter App

🔗 **Live Demo:** [live link](https://your-username.github.io/spam-filter-app)  
📁 **GitHub Repository:** [GitHub Repo](https://github.com/your-username/spam-filter-app)

---

## 📌 Overview

Spam Filter App is a simple, lightweight web application built using **Vanilla JavaScript** that detects whether a user message contains spam patterns based on predefined regular expressions.

The project focuses on **regex-based text analysis**, clean DOM handling, and clear user feedback — without using any external libraries or frameworks.

---

## ✨ Features

- Real-time spam detection
- Uses Regular Expressions for pattern matching
- Highlights spam-related keywords
- Clear success and error messages
- Clean and minimal UI
- Fully client-side (no backend required)

---

## 🧠 How It Works

1. The user enters a message into the input field.
2. On button click:
   - The message is tested against a deny-list of regex patterns.
   - If **any pattern matches**, the message is marked as spam.
   - Otherwise, it is considered safe.
3. The result is displayed immediately to the user.

The logic uses JavaScript’s `.test()` and `.some()` methods for efficient evaluation.

---

## 🛠️ Tech Stack

- **HTML** – structure
- **CSS** – styling
- **JavaScript (ES6)** – logic and regex handling

---

## 📂 Project Structure

- `index.html`
- `styles.css`
- `script.js`               
- `.gitignore`      
- `README.md`       
- `LICENSE`