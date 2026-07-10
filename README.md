# Web Semantic Lab

A lab project focused on writing accessible, semantic HTML — covering
proper use of semantic elements, form validation, and ARIA labels for
screen-reader accessibility.

## 🛠️ Built With
- HTML5 (Semantic elements)
- ARIA (Accessible Rich Internet Applications)

## ✨ Features
- Semantic HTML structure (`header`, `nav`, `main`, `article`, `aside`, `footer`)
- Contact form with client-side validation
- ARIA labels and landmarks for accessibility

## 📄 Pages
- **Home (`index.html`)** — Homepage using full semantic structure
- **Contact (`contact.html`)** — Accessible contact form with validation
  and ARIA support

## 🎯 What I Practiced
- Structuring pages with semantic HTML tags instead of generic `<div>`s
- Building accessible forms (validation + ARIA labels)
- Using ARIA landmarks to improve screen-reader navigation
- Git feature-branch workflow (`feature/homepage`, `feature/contact`)
  merged via `development` branch

---
*Part of coursework for Web Frontend Development, focused on writing
accessible and semantically correct HTML.*

## git command used in this lab
- git config --global user.name Monthorn
- git config --global user.email 66160259@go.buu.ac.th
- git clone https://github.com/NekomaNaJa/web-semantic-lab.git
- git add README.md
- git commit -m "readme"
- git push
- git checkout -b development
- git add .
- git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"
- git checkout -b feature/homepage
- git add .
- git commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค"
- git add index.html
- git commit -m "เพิ่ม header และ nav ในหน้าหลัก"
- git add index.html
- git commit -m  "เพิ่มส่วน main และ article ในหน้าหลัก"
- git add index.html
- git commit -m "เพิ่ม aside และ footer ในหน้าหลัก"
- git checkout -b feature/contact
- git add contact.html
- git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
- git add contact.html
- git commit -m "เพิ่มฟอร์มพื้นฐานในหน้าติดต่อ"
- git add contact.html
- git commit -m "เพิ่ม validation ในฟอร์มติดต่อ"
- git add contact.html
- git commit -m "เพิ่ม ARIA labels ในฟอร์ม"
- git add contact.html
- git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
- git checkout development
- git merge feature/homepage
- git merge feature/contact
- git push origin development
- git add contact.html
- git commit -m "fix contact"
- git push origin development
