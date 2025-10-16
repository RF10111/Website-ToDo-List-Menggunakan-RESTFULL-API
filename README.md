# 📝 To-Do App 

Aplikasi To-Do **berbasis web** yang dirancang untuk membantu pengguna dalam mengelola dan mengatur daftar tugas secara efisien. Sistem ini mempermudah pengguna dalam merencanakan aktivitas harian agar lebih terstruktur, terpantau, dan produktif. Dengan tampilan yang responsif dan antarmuka modern, website ini mendukung kebiasaan kerja yang lebih terorganisir serta meningkatkan manajemen waktu pengguna.


---

## 🚀 Backend (Express.js API)

### 🔑 Fitur Utama
- **CRUD Operations lengkap** (Create, Read, Update, Delete)  
- **Filtering & Search** menggunakan query parameters  
- **Input Validation** dengan **Joi**  
- **Error Handling middleware** yang profesional  
- **Security** menggunakan **Helmet** dan **Rate Limiting**  
- **CORS Support** untuk integrasi frontend  

### 📌 API Endpoints
- `GET /api/todos` → Ambil semua todos (dengan filtering)  
- `GET /api/todos/:id` → Ambil todo berdasarkan ID  
- `POST /api/todos` → Buat todo baru  
- `PUT /api/todos/:id` → Update todo  
- `DELETE /api/todos/:id` → Hapus todo  
- `PATCH /api/todos/:id/toggle` → Toggle status completion  

---

## 💻 Frontend (User Interface)

### ⚡ Functionality
- **CRUD Operations lengkap** (Create, Read, Update, Delete)  
- **Real-time Search** pada title & description  
- **Multi-filter** (priority, status, category)  
- **Statistics Dashboard** (total, completed, pending)  
- **Toggle Status** todo dengan satu klik  
- **Form Validation & Error Handling**  
- **Success/Error Messages** dengan auto-hide  

### 🎨 Features
- **Priority Badges** (Tinggi/Sedang/Rendah) dengan warna berbeda  
- **Category System** (Kerja, Personal, Belajar, Kesehatan, dll)  
- **Date Display** (created & updated timestamps)  
- **Empty State** ketika tidak ada todos  
- **Loading States** untuk UX yang lebih baik  

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js, Joi, Helmet  
- **Frontend:** React.js / Vanilla JS (sesuaikan implementasi)  
- **Database:** MongoDB / MySQL (sesuaikan setup)  
