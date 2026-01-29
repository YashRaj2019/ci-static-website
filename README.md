# CI for Static Website

![CI](https://github.com/YashRaj2019/ci-static-website/actions/workflows/ci.yml/badge.svg)

## 📌 Project Overview
This project demonstrates a Continuous Integration (CI) pipeline for a static website using GitHub Actions.  
The website is hosted on AWS S3 using static website hosting, and images are served directly from the S3 bucket.

On every commit, GitHub Actions automatically validates the HTML code to ensure correctness and code quality.

---

## 🎯 Objectives
- Automate CI for a static website
- Validate HTML on every commit
- Host static content using AWS S3
- Serve images from S3 bucket URLs
- Follow DevOps and Git best practices

---

## 🛠️ Technologies Used
- HTML5
- Git & GitHub
- GitHub Actions (CI)
- AWS S3 (Static Website Hosting)

---

## ⚙️ CI Workflow
- Triggered on every push to the `main` branch
- Checks out repository code
- Validates HTML using automated tools
- Fails the build if HTML errors are found

---

## ☁️ AWS S3 Hosting
- Static website hosting enabled on S3
- Public-read access configured using bucket policy
- Images served via S3 object URLs
- Live website accessible through S3 website endpoint

---

## 🚀 Outcome
- Fully automated CI pipeline
- Cloud-hosted static website
- Improved code quality through validation
- Resume-ready DevOps project

---

## 🔮 Future Enhancements
- Add Continuous Deployment (CD) to auto-deploy to S3
- Integrate CloudFront CDN
- Add CSS and JavaScript linting
