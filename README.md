# Landing Page - BrandName

Đây là phiên bản HTML/CSS thuần túy của landing page, được chuyển đổi từ dự án React gốc.

## Cấu trúc thư mục

```
landing-page/
├── index.html          # File HTML chính
├── styles.css          # File CSS với tất cả styles
├── script.js           # File JavaScript cho tương tác
└── README.md           # File hướng dẫn này
```

## Tính năng

### 🎨 Thiết kế
- **Responsive Design**: Tương thích hoàn hảo trên mọi thiết bị
- **Modern UI**: Giao diện hiện đại với gradient và shadow effects
- **Smooth Animations**: Hiệu ứng mượt mà khi scroll và hover
- **Typography**: Sử dụng font Inter cho typography đẹp

### 📱 Tương tác
- **Mobile Menu**: Menu hamburger cho mobile với animation
- **Smooth Scrolling**: Cuộn mượt đến các section
- **Form Validation**: Validate form liên hệ với thông báo
- **Ripple Effects**: Hiệu ứng ripple khi click buttons
- **Scroll Animations**: Animation khi scroll đến các element

### 🚀 Performance
- **Vanilla JavaScript**: Không phụ thuộc framework
- **CSS Variables**: Sử dụng CSS custom properties cho dễ customize
- **Optimized Images**: Sử dụng emoji thay vì images để tối ưu tốc độ
- **Minimal Dependencies**: Chỉ sử dụng Font Awesome cho icons

## Cách sử dụng

### 1. Mở file
Chỉ cần mở file `index.html` trong trình duyệt web.

### 2. Chỉnh sửa nội dung
- **Brand Name**: Thay đổi "BrandName" trong HTML
- **Colors**: Chỉnh sửa CSS variables trong `:root`
- **Content**: Thay đổi text trong các section
- **Contact Info**: Cập nhật thông tin liên hệ

### 3. Customize styles
```css
:root {
    --primary-600: #2563eb;    /* Màu chủ đạo */
    --secondary-500: #64748b;  /* Màu phụ */
    /* Thêm các màu khác... */
}
```

### 4. Thêm sections mới
1. Thêm HTML structure trong `index.html`
2. Thêm CSS styles trong `styles.css`
3. Thêm JavaScript interactions nếu cần

## Sections có sẵn

### 1. Navigation
- Logo/Brand name
- Menu navigation
- Mobile responsive menu
- Call-to-action buttons

### 2. Hero Section
- Headline chính
- Description
- Call-to-action buttons
- Feature highlights card

### 3. Features Section
- 4 feature cards
- Icons (emoji)
- Hover effects

### 4. About Section
- Company description
- Statistics counter
- Visual element

### 5. Testimonials Section
- 3 testimonial cards
- Star ratings
- Author information

### 6. Contact Section
- Contact form với validation
- Contact information
- Social media links

### 7. Footer
- Company info
- Quick links
- Social media
- Copyright

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Tùy chỉnh nâng cao

### Thay đổi màu sắc
```css
:root {
    --primary-50: #eff6ff;
    --primary-100: #dbeafe;
    /* ... */
    --primary-600: #your-color;
}
```

### Thêm animations
```css
@keyframes yourAnimation {
    from { /* ... */ }
    to { /* ... */ }
}

.your-element {
    animation: yourAnimation 1s ease-out;
}
```

### Thêm sections mới
```html
<section id="your-section" class="your-section">
    <div class="container">
        <!-- Your content -->
    </div>
</section>
```

## Deployment

### GitHub Pages
1. Push code lên GitHub repository
2. Vào Settings > Pages
3. Chọn source branch
4. Deploy

### Netlify
1. Drag & drop thư mục `landing-page`
2. Hoặc connect GitHub repository
3. Auto deploy

### Vercel
1. Import project từ GitHub
2. Auto detect static site
3. Deploy

## Tối ưu hóa

### Performance
- ✅ Minify CSS và JS cho production
- ✅ Optimize images
- ✅ Enable gzip compression
- ✅ Use CDN cho fonts

### SEO
- ✅ Meta tags
- ✅ Semantic HTML
- ✅ Alt text cho images
- ✅ Structured data

### Accessibility
- ✅ ARIA labels
- ✅ Keyboard navigation
- ✅ Color contrast
- ✅ Screen reader friendly

## License

MIT License - Tự do sử dụng và chỉnh sửa.

## Support

Nếu có vấn đề hoặc cần hỗ trợ, vui lòng tạo issue hoặc liên hệ trực tiếp. 