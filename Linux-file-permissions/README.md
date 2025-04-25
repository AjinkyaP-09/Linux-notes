# 🔐 Linux File Permissions – A Beginner-Friendly Guide

This doc is a simplified and practical guide to understanding **Linux File Permissions** — a critical concept for anyone managing files in a Linux environment or working toward a DevOps role.

> ✅ Created while learning from [Abhishek Veeramalla's](https://github.com/iam-veeramalla/ultimate-linux-guide) fantastic [YouTube tutorial](https://youtu.be/kqTgHRKeb04?si=0qXi4ISEJZ8h7Fkj).  
> Highly recommend checking out his content for clear explanations and real-world demos.  
> This doc compiles everything I learned in a beginner-friendly format.

---

## 📂 What's Covered?

### 🔐 File Permissions Basics

- Categories: Owner, Group, Others
- Permissions: Read (`r`), Write (`w`), Execute (`x`)
- Viewing file permissions (`ls -l`)

### 🛠️ chmod – Change File Permissions

- Symbolic format: `chmod u=rw filename`
- Numeric format: `chmod 755 filename`
- Explanation of how `r=4`, `w=2`, `x=1` map into numbers

### 👑 chown – Change File Ownership

- Change owner: `chown user filename`
- Change owner & group: `chown user:group filename`
- Recursive ownership: `chown -R user:group folder/`

### 📘 Real-World Scenarios

- Why permissions matter in multi-user environments
- Common errors and their meaning
- Analogies to understand access rules better

---

## 💡 Why This Doc?

I created this as a quick reference and study guide while practicing file-level security in Linux. Ideal for:

- DevOps beginners
- System administrators in training
- Anyone wanting to understand how `chmod` and `chown` actually work

## 👤 Author

**Ajinkya Pame**  
[LinkedIn](https://www.linkedin.com/in/ajinkya-pame-4a752b346)

---
