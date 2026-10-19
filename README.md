# Bài Thực Hành: Luyện Tập Sử Dụng Phối Màu Trên Trang Web

Bài thực hành phối lại màu cho trang web theo phương pháp **Màu đơn tông (Monochromatic Color Palette)**.

---

## 1. Bảng màu đơn tông đã sử dụng

### Phiên bản 1 (Màu xanh chủ đạo theo logo `#0DADEE` / `#00ADEE` - Bước 1 đến Bước 7):
- **Bậc 1 (Màu chủ đạo logo):** `#00ADEE` / `#0DADEE` — Nền nhãn `ON SALE`, nhãn `PREVIEW`, icon nút play tròn.
- **Bậc 2:** `#00B2EF` — Màu điểm nhấn bổ trợ.
- **Bậc 4 (Màu nền toàn trang):** `#00BFF2` — Màu nền `body`.
- **Bậc 7 (Màu nền nội dung item):** `#BDD7F7` — Màu nền các khung nghe thử bài hát (`#main .preview li a`).
- **Bậc 9 (Màu nền chân trang):** `#C6E9FA` — Màu nền `footer`.
- **Màu chữ:** Toàn bộ văn bản giữ màu đen (`#000000`) để đảm bảo độ tương phản cao và dễ đọc trên nền sáng.

### Phiên bản 2 (Bước 8 - Mở rộng: Bảng màu đơn tông Xanh Lục / Emerald Green):
- File: `index-variant2.html` & `style-variant2.css`
- **Bậc 1 (Màu chính):** `#059669` (Emerald Dark)
- **Bậc 2:** `#10B981` (Emerald Accent)
- **Bậc 4 (Màu nền body):** `#6EE7B7` (Emerald Light)
- **Bậc 7 (Màu nền nội dung preview):** `#D1FAE5` (Emerald Pale)
- **Bậc 9 (Màu nền footer):** `#ECFDF5` (Mint White)
- **Màu chữ:** Màu đen (`#000000`).

---

## 2. Các bước đã thực hiện chi tiết

1. **Bước 1:** Xác định màu xanh logo `#00ADEE` làm màu bậc 1, phân chia các bậc giảm dần độ bão hòa / tăng dần độ sáng.
2. **Bước 2 (Đổi màu nền):** Cập nhật `body { background: #00BFF2; color: #000; }`.
3. **Bước 3 (Đổi màu nền ON SALE / PREVIEW):** Cập nhật `.trans .on-sale`, `.preview .title`, `.preview .circle` sang màu bậc 1 `#00ADEE`.
4. **Bước 4 (Đổi màu nền phần nội dung):** Cập nhật `#main .preview li a` sang màu bậc 7 `#BDD7F7`, chữ màu đen `#000`.
5. **Bước 5 (Đổi màu footer):** Cập nhật `footer { background: #C6E9FA; color: #000; }`.
6. **Bước 6 (Màu chữ toàn trang):** Chuyển các liên kết thanh điều hướng (`nav ul li a`) từ màu đỏ sang màu đen `#000` đồng bộ toàn trang.
7. **Bước 7:** Kiểm tra hiển thị file `index.html`.
8. **Bước 8:** Tạo thêm bản biến thể phối màu `index-variant2.html` với bảng màu xanh lục đơn sắc.

---

## 3. Cách nộp bài (GitHub / CodePen)

### Cách đưa lên GitHub:
1. Tạo 1 repository mới trên GitHub (ví dụ: `bai-tap-phoi-mau-web`).
2. Mở terminal tại thư mục này và chạy các lệnh:
   ```bash
   git add .
   git commit -m "Hoan thanh bai thuc hanh phoi mau don tong web"
   git branch -M main
   git remote add origin https://github.com/<tai-khoan-cua-ban>/bai-tap-phoi-mau-web.git
   git push -u origin main
   ```
3. Copy đường link repository vừa tạo (hoặc bật GitHub Pages) và dán vào ô nộp bài.

### Cách đưa lên CodePen:
1. Truy cập [codepen.io/pen](https://codepen.io/pen/)
2. Copy toàn bộ mã trong file [index.html](index.html) vào khung **HTML** (bỏ thẻ `<head>` hoặc đưa `<link>` vào Settings).
3. Copy toàn bộ mã trong file [style.css](style.css) vào khung **CSS**.
4. Lưu Pen và copy link dán vào phần nộp bài.
