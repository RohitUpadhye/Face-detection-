# 🤖 AWS Infrastructure Automation using Face Detection 😊

This project automates **AWS infrastructure creation** using **face detection** with a **Haar Cascade classifier**.  
If a known face is detected ✅, it triggers a **Terraform** script to spin up resources in the **AWS Console** ☁️🖥️

---

## 🎯 Objective

- ✅ Detect known face using Haar Cascade + OpenCV
- ✅ Trigger AWS infra creation via Terraform
- ✅ View deployed infra in your AWS Console ☁️

---

## 🧠 Tech Stack

- 🐍 Python
- 🧠 OpenCV + Haarcascade (`haarcascade_frontalface_default.xml`)
- 🏗️ Terraform
- ☁️ AWS (EC2, S3, etc.)

---

## 🔍 Face Detection Details

- Uses OpenCV’s **Haar Cascade** classifier for real-time face detection
- Compares live face with a **known image**
- On match: Terraform script is automatically triggered ✅

---

## 📂 Project Structure

