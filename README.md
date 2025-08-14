# Task 6 - Host a Static Website with GitHub Pages

## 📌 Objective
Deploy and host a simple HTML & CSS website using **GitHub Pages**.

---

## 🛠 Tools Used
- **Git** - Version control system
- **GitHub** - Repository hosting service
- **GitHub Pages** - Static site hosting

---

## 📂 Steps Performed

### 1️⃣ Created HTML and CSS Files
Created `index.html` and `style.css` in the project folder.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Pages Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to My Website!</h1>
    <p>This is my first website hosted on GitHub Pages.</p>
    <p>Pretty cool, right?</p>
</body>
</html>
css
Copy
Edit
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #74ABE2, #5563DE);
    color: white;
    text-align: center;
    padding: 50px;
}

2️⃣ Created a New GitHub Repository
Went to GitHub → New repository

Named it task-6

Selected Public visibility

Did not add README file

Clicked Create repository


3️⃣ Pushed Local Code to GitHub
Opened terminal in project folder and ran:

bash
Copy
Edit
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/task-6.git
git push -u origin main

4️⃣ Enabled GitHub Pages
Opened Settings in GitHub repo

Navigated to Pages

Under Source, selected:

Branch: main

Folder: / (root)

Clicked Save


5️⃣ Verified Live Website
After 1–2 minutes, accessed the site at:

arduino
Copy
Edit
https://YOUR-USERNAME.github.io/task-6/

✅ Outcome
Successfully hosted a static HTML & CSS website on GitHub Pages

Learned to configure Pages settings for correct file serving

Verified site works on a public URL
