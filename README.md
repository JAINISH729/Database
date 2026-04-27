# 📂 Digital Document Manager

A modern web application to upload, manage, and preview documents using **React (Vite)**, **Redux Toolkit**, and **Cloudinary**.

---

## 🚀 Features

* 📤 Upload files (images, PDFs, documents)
* 🖼️ Preview uploaded images
* 🔍 Search files by name
* 🗑️ Delete files from UI
* ☁️ Cloud storage using Cloudinary
* 💾 Local storage persistence (no backend required)
* 🎨 Modern dark UI

---

## 🛠️ Tech Stack

* **Frontend:** React (Vite)
* **State Management:** Redux Toolkit
* **Cloud Storage:** Cloudinary
* **Styling:** Custom CSS (AI-assisted)

---

## 📂 Folder Structure

```
src/
├── app/
│   └── store.js
├── features/
│   └── fileSlice.js
├── components/
│   ├── UploadFile.jsx
│   ├── FileList.jsx
│   ├── FileCard.jsx
│   └── SearchFilter.jsx
├── cloudinary/
│   └── cloudinaryConfig.js
├── pages/
│   └── Dashboard.jsx
├── App.jsx
├── main.jsx
└── App.css
```

---

## ☁️ Cloudinary Setup

1. Create an account at https://cloudinary.com

2. Go to **Settings → Upload → Upload Presets**

3. Create a preset:

   * Mode: **Unsigned**
   * Name: `m6i2qt0u` (or update in code)

4. Add your Cloudinary config:

```js
const CLOUDINARY_CLOUD_NAME = "your_cloud_name";
const CLOUDINARY_UPLOAD_PRESET = "your_preset";
```

---

## ⚠️ Notes

* Files are stored in **Cloudinary**
* Metadata is stored in **localStorage**
* Delete only removes files from UI (not Cloudinary server)

---

## 🎨 UI & Design

The user interface is designed with a modern dark theme.

> ⚡ The CSS styling in this project is **AI-assisted** to achieve a clean and modern design quickly.

---

## 🔮 Future Improvements

* Drag & drop upload
* File categories
* Backend integration for secure delete
* User authentication
* Progress bar for uploads

### SCREENSHOT OF OUTPUT:
<img width="1919" height="670" alt="Screenshot 2026-04-27 210018" src="https://github.com/user-attachments/assets/c915390f-7f32-4fd9-876c-36ba650297e4" />
<br/><br/>
<img width="1574" height="514" alt="Screenshot 2026-04-27 210126" src="https://github.com/user-attachments/assets/7136e0ed-b498-4e58-9464-3609351b812d" />
