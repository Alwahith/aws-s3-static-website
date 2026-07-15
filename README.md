# aws-s3-static-website/
# AWS S3 Static Website Hosting

## 📖 Project Overview

This project demonstrates how to host a static website using **Amazon S3 Static Website Hosting**.

---

## 🏗️ Architecture

![AWS S3 Architecture](architecture/architecture.png)

---

## ☁️ AWS Services Used

- Amazon S3
- IAM
- Bucket Policy

---

## 🚀 Project Workflow

1. Created an S3 bucket.
2. Uploaded HTML, CSS, and image files.
3. Enabled Static Website Hosting.
4. Configured Bucket Policy for public read access.
5. Tested the website using the S3 Website Endpoint.

---

## 📂 Project Structure

```text
aws-s3-static-website/
├── architecture/
├── bucket-policy/
├── screenshots/
├── website/
└── README.md
```

---

## 📸 Screenshots

### S3 Bucket

![Bucket](screenshots/01-bucket-created.png)

### Static Website Hosting

![Hosting](screenshots/02-static-hosting.png)

### Bucket Policy

![Policy](screenshots/03-bucket-policy.png)

### Live Website

![Website](screenshots/04-live-website.png)

---

## 🛠 Challenges Faced

### Problem

Received **404 Not Found** while accessing the website.

### Root Cause

`index.html` was uploaded inside a folder instead of the bucket root.

### Resolution

Moved `index.html` and `style.css` to the root of the bucket.

---

## 🎯 Skills Gained

- Amazon S3
- Static Website Hosting
- Bucket Policies
- Public Access Management
- Troubleshooting
