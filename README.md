# 🗂️ Internee.pk Cloud File Storage System

## Objective
Store and retrieve intern documents securely using AWS S3.

## Tech Stack
| Technology | Purpose |
|---|---|
| AWS S3 | Cloud File Storage |
| Python (boto3) | Signed URL Generation |
| AWS IAM | Access Management |

## S3 Bucket Structure
internee-pk-docs/
├── joining-letters/
│   └── joining_letter_ali.txt
├── certificates/
│   └── certificate_sara.txt
└── reports/
    └── report_usman.txt

## Features
- ✅ Secure file storage on AWS S3
- ✅ Organized folder structure
- ✅ Signed URLs for secure file sharing
- ✅ URLs expire after 1 hour

## How to Generate Signed URLs
pip install boto3
python generate_url.py

## 📸 Screenshots

### 1. S3 Bucket — 3 Folders Created

<img width="1912" height="677" alt="s3-folders" src="https://github.com/user-attachments/assets/6b1eaede-0c59-4886-b92c-ccc9c214a0f8" />


### 2. Joining Letter — Signed URL Working

<img width="782" height="447" alt="joining-letter-url" src="https://github.com/user-attachments/assets/f1caad64-f13a-434c-a508-a9b9577cd1ce" />

### 3. Certificate — Signed URL Working

<img width="758" height="392" alt="certificate-url" src="https://github.com/user-attachments/assets/8647a964-e6cd-4d59-8bdd-f0d36b9030b9" />

### 4. Report — Signed URL Working

(<img width="951" height="382" alt="report-url" src="https://github.com/user-attachments/assets/68d8a866-2a6d-45a1-b175-95b56658de76" />)

### 5. Python Script — URLs Generated

<img width="1895" height="456" alt="script-output" src="https://github.com/user-attachments/assets/4b01d2c9-3d6b-43e3-a5cf-849339000268" />



## Author
**Mubashar Akram**
Internee @ Internee.pk
GitHub: [@MubasharAkram05](https://github.com/MubasharAkram05)
