# 🧠 Hướng Dẫn Chạy Project Python với Jupyter

Dự án này sử dụng Jupyter Notebook để phát triển và thử nghiệm mã Python trong một môi trường ảo cách ly.

---

## ⚙️ Yêu Cầu Trước Khi Bắt Đầu

- Python 3.8+
- `virtualenv` (nếu chưa có, cài bằng `pip install virtualenv`)

---

## 🚀 Các Bước Thiết Lập

### 1. 📦 Cài Đặt Thư Viện Jupyter

```bash
pip install jupyter
```

---

### 2. 🧪 Tạo Môi Trường Ảo

```bash
virtualenv jupyter_env
```

---

### 3. 🔄 Kích Hoạt Môi Trường Ảo

**Windows**:

```bash
jupyter_env\Scripts\activate
```

**macOS / Linux**:

```bash
source jupyter_env/bin/activate
```

---

### 4. 📥 Cài Đặt Các Thư Viện Cần Thiết

```bash
pip install -r requirements.txt
```

---

### 5. 🔄 Cập Nhật Danh Sách Thư Viện

Nếu bạn đã cài thêm thư viện mới và muốn cập nhật file `requirements.txt`:

```bash
pip freeze > requirements.txt
```

---

### 6. ▶️ Chạy Jupyter Notebook

```bash
jupyter notebook
```

Sau đó trình duyệt sẽ mở ra giao diện Jupyter, bạn có thể tạo và chạy notebook tại đó.

---

## 📁 Cấu Trúc Thư Mục Đề Xuất

```
project/
├── notebooks/              # chứa các file .ipynb
├── jupyter_env/            # môi trường ảo
├── requirements.txt        # thư viện cần cài
├── .env                    # file môi trường
├── example.env                    # file môi trường mẫu
├── README.md               # file hướng dẫn
└── ...
```

---

## ✅ Gợi Ý

- Dùng `requirements.txt` để đảm bảo đồng bộ thư viện giữa các máy.
- Có thể dùng `jupyter-lab` thay vì `jupyter notebook` nếu muốn giao diện nâng cao hơn.

---

Chúc bạn code vui vẻ! 🚀
