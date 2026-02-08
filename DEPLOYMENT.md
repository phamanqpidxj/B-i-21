# Hướng dẫn Deploy lên GitHub Pages

## Cấu trúc dự án

```
B-i-21/
├── index.html          # Trang chủ
├── TK4/index.html      # Bài TK4: Tab View
├── TK5/index.html      # Bài TK5: Accordion
├── K3/index.html       # Bài K3: Kiểm tra mật khẩu
├── K7/index.html       # Bài K7: Parallax Scrolling
└── K8/index.html       # Bài K8: Tính BMI
```

## Các bước deploy lên GitHub Pages

1. Vào repository trên GitHub: https://github.com/phamanqpidxj/B-i-21
2. Click vào **Settings** (Cài đặt)
3. Trong menu bên trái, click vào **Pages**
4. Trong phần **Source**, chọn branch `main` hoặc `copilot/create-html-css-js-exercises`
5. Chọn thư mục root `/` 
6. Click **Save**
7. Đợi vài phút để GitHub build và deploy
8. Website sẽ có URL: https://phamanqpidxj.github.io/B-i-21/

## Các tính năng của từng bài

### Trang chủ (index.html)
- Menu liên kết đến tất cả các bài tập
- Thiết kế responsive với gradient backgrounds
- Chia thành 2 nhóm: Trung Bình-Khó và Khó

### TK4: Tab View
- 3 tabs với nội dung khác nhau
- Chuyển đổi mượt mà giữa các tab
- Animation fade in khi chuyển tab

### TK5: Accordion
- 5 accordion items
- Hiệu ứng slide toggle
- Có thể mở nhiều items cùng lúc

### K3: Kiểm tra mật khẩu
- Form đăng ký với validation
- Kiểm tra email hợp lệ
- Password strength indicator
- Kiểm tra password confirmation khớp

### K7: Parallax Scrolling
- Hiệu ứng parallax với nhiều sections
- Gradient backgrounds
- Smooth scrolling với JavaScript

### K8: Tính BMI
- Input cân nặng và chiều cao
- Tính toán BMI real-time
- Phân loại với màu sắc và icon
- Auto-calculate khi nhập đủ thông tin

## Lưu ý kỹ thuật

- Tất cả CSS và JavaScript được viết inline trong file HTML
- Không cần build process hay dependencies
- Hoạt động hoàn toàn với static files
- Responsive design cho mobile và desktop
- Nội dung bằng tiếng Việt
