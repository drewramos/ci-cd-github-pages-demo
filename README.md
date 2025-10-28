# CI/CD GitHub Pages Demo

This is a **starter project for learning CI/CD and DevOps workflows** using **GitHub Actions** and **GitHub Pages**.

Students will:
1. Understand how GitHub Actions automates build and deployment.
2. Trigger automatic deployment on every push.
3. See how DevOps practices apply even to a simple static website.

## 🚀 Step-by-Step Guide

### 1. Clone this repo
```bash
git clone https://github.com/<your-username>/ci-cd-github-pages-demo.git
cd ci-cd-github-pages-demo
```

### 2. Make a small change
Edit `index.html` and change the greeting message, for example:
```html
<h1>Hello from [Your Name]!</h1>
```

Then commit and push:
```bash
git add index.html
git commit -m "Updated greeting"
git push
```

### 3. Watch the CI/CD pipeline
Go to your repo’s **Actions** tab → open the latest workflow run.
You’ll see:
- Checkout code  
- Upload static site  
- Deploy to GitHub Pages

### 4. Visit your live site
After a successful run:
- Go to **Settings → Pages**
- The site should be deployed at  
  `https://<your-username>.github.io/ci-cd-github-pages-demo/`

### 5. Reflection
Answer briefly:
- What triggers the workflow?
- How does GitHub Actions automate deployment?
- How could we add testing or code review before deployment?

## 🧠 Learning Objectives
- Understand what CI/CD means in a DevOps context  
- See how automated deployment increases reliability  
- Learn to read and debug workflow logs  
- Experience version control and deployment integration

## 🔧 Requirements
- GitHub account  
- Basic knowledge of Git and HTML/CSS/JS  
- VS Code or any text editor

## 📄 License
MIT License — free to use for educational purposes.
