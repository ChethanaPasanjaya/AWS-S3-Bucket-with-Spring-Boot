# 🚀 Spring Boot AWS S3 File Upload & Download API

A Spring Boot application that integrates with Amazon S3 for file storage. Provides REST APIs to upload, download, list, delete files, and generate public or pre-signed URLs.

---

## Features

- 📤 Upload files (with optional folder support)  
- 📥 Download files  
- 📜 List all files in the bucket  
- ❌ Delete files  

---

## Tech Stack

- Spring Boot  
- AWS SDK v2 for Java  
- Amazon S3  

---

## API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| POST   | /upload | Upload a file |
| GET    | /download/{fileName} | Download a file |
| GET    | /files | List all files |
| DELETE | /delete/{fileName} | Delete a file |

---
