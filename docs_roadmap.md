
# 📊 Roadmap Xây dựng Website Đầu Tư với Python & Web

## 🎯 Mục tiêu:
Xây dựng một website đầu tư tích hợp các ứng dụng Python như dashboard NAV, phân tích danh mục, biểu đồ rủi ro – phục vụ khách hàng như sản phẩm Fintech chuyên nghiệp.

---

## 📅 Giai đoạn 1: Cơ bản đến MVP (2 tháng)

### ✅ Tháng 1 – Nền tảng & Dashboard đầu tiên

#### Tuần 1: HTML/CSS + Git cơ bản
- Học HTML: thẻ div, h1–h6, p, table, form...
- CSS: Flexbox, màu sắc, font chữ, responsive
- Git cơ bản: `git init`, `git add`, `git commit`, `git push`
- Tạo GitHub repo và kết nối VSCode

#### Tuần 2: Dashboard đầu tư bằng Python (Streamlit)
- Làm lại dashboard NAV với Pandas, Plotly
- Viết các hàm: `calculate_nav()`, `plot_nav_chart()`, `summary_risk_table()`
- Giao diện Streamlit hiển thị NAV, % lãi/lỗ, danh mục

#### Tuần 3: Làm quen backend Python – Flask hoặc FastAPI
- Route cơ bản: `/`, `/nav`, `/portfolio`
- Tạo API lấy dữ liệu từ file CSV hoặc SQLite
- Trả kết quả JSON để React/Streamlit lấy hiển thị

#### Tuần 4: Triển khai lên server
- Dùng Render hoặc Railway để host dashboard
- Tạo job tự động cập nhật giá sau 14h45
- Test tính năng hoạt động liên tục

---

### ✅ Tháng 2 – Frontend đẹp + Kết nối hoàn chỉnh

#### Tuần 5–6: React/Next.js + Tailwind CSS
- Tạo trang login, form nhập giao dịch
- Hiển thị danh mục, NAV, biểu đồ (gọi từ API)

#### Tuần 7: Kết nối React ↔ FastAPI
- Dùng `axios` hoặc `fetch` gọi API
- Tải dữ liệu đúng theo từng khách hàng
- Hiển thị đẹp với bảng, thẻ thông tin, loading UI

#### Tuần 8: Đưa vào production
- Setup domain riêng (VD: quanginvest.vn)
- Tối ưu server và UI
- Test lại toàn bộ dashboard

---

## 🛠 Công cụ sử dụng:

| Mục đích | Công cụ |
|----------|--------|
| Frontend | React, Tailwind CSS, Next.js |
| Backend  | FastAPI hoặc Flask |
| Dashboard đầu tư | Streamlit, Plotly, Pandas |
| Database | PostgreSQL hoặc SQLite |
| Hosting | Render.com, Railway.app |
| Quản lý version | Git + GitHub |

---

## 📂 Cấu trúc thư mục gợi ý:
```
investment_dashboard/
│
├── frontend/              # Giao diện React/Next.js
├── backend/               # FastAPI hoặc Flask API
├── dashboard/             # Code Streamlit và Python
├── data/                  # Dữ liệu .csv hoặc database
├── utils/                 # Hàm xử lý NAV, biểu đồ, đọc dữ liệu
└── README.md
```

---

## ✅ Bước tiếp theo:
> Tạo GitHub repo `investment_dashboard`, chia thành các thư mục như trên để bắt đầu project đầu tiên!
