# Hướng dẫn Setup Form Contact

## Vấn đề hiện tại
FormSubmit có thể không hoạt động trên GitHub Pages do một số lý do:

1. **CORS Policy**: GitHub Pages có thể block một số request
2. **Email chưa được xác nhận**: Cần xác nhận email với FormSubmit
3. **JavaScript can thiệp**: Code JS có thể ngăn form submit

## Giải pháp

### 1. Kiểm tra FormSubmit
- Mở trang web trên GitHub Pages
- Điền form và submit
- Kiểm tra email `educenterhl@gmail.com` có nhận được email xác nhận không
- Nếu có, click vào link xác nhận trong email

### 2. Backup: Sử dụng Netlify Forms
Nếu FormSubmit không hoạt động, deploy lên Netlify:

1. **Tạo tài khoản Netlify**: https://netlify.com
2. **Deploy site**:
   - Drag & drop thư mục `lcm-landingpage-ver02` lên Netlify
   - Hoặc connect GitHub repository
3. **Form sẽ tự động hoạt động** với Netlify Forms

### 3. Test Form
```bash
# Test local với Python server
cd lcm-landingpage-ver02
python -m http.server 8000
# Mở http://localhost:8000
```

### 4. Debug Form
Mở Developer Tools (F12) và kiểm tra:
- Console có lỗi gì không
- Network tab xem request có được gửi không
- Form data có đúng format không

## Cấu hình hiện tại

### FormSubmit
```html
<form action="https://formsubmit.co/educenterhl@gmail.com" method="POST">
```

### Netlify Forms (Backup)
```html
<form data-netlify="true" netlify-honeypot="bot-field">
```

### Field Names
- `name`: Họ và tên
- `email`: Email
- `subject`: Tiêu đề
- `message`: Nội dung

## Troubleshooting

### Nếu form không submit:
1. Kiểm tra JavaScript không can thiệp
2. Kiểm tra email đã được xác nhận
3. Thử deploy lên Netlify
4. Kiểm tra CORS policy

### Nếu không nhận được email:
1. Kiểm tra spam folder
2. Thử email khác
3. Sử dụng Netlify Forms thay thế

## Contact Info
- Email: educenterhl@gmail.com
- Phone: +84 984 668 448
- Address: No 1 Xa Muc Uyen, Xa Muc Uyen, Huyen Thach That, Ha Noi 