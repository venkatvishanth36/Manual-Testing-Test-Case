# 📂 File Upload & Download Module - Manual Testing Project

This project contains a comprehensive set of manual test cases for a **File Upload and Download Module** commonly used in document management or HR systems.

## ✅ Objective

To manually verify the functionality, validation, and error handling of:
- File upload (PDF, DOCX, XLSX)
- File download
- Size and format restrictions
- Corrupted file handling

## 🧪 Modules Covered

1. **File Upload**
   - Upload valid/invalid files
   - Max file size validation
   - Format restrictions
   - Corruption checks
   - Cancel/Resume upload

2. **File Download**
   - Download uploaded files
   - Handle slow/cancelled downloads
   - Corrupted or missing files
   - Special characters in filenames

## 🧾 Test Case Highlights

| Area                  | Details |
|-----------------------|---------|
| ✅ Input Validation    | File extension, size, format |
| ❌ Negative Scenarios  | Corrupt files, unsupported formats |
| 🌀 Upload UI Feedback  | Progress bar, cancel options |
| 🔁 Download Flow       | Retry, resume, cancel |
| ⚠️ Error Handling       | Proper user messages |
| 🔐 Security (Optional) | Reject executable files (.exe, .bat) |
