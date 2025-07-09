# AECK - Trang Nhúng Khóa học TSA

Đây là trang web nhúng toàn bộ nội dung từ https://aeck.edubit.vn/ với đầy đủ các thông số SEO để tối ưu hóa công cụ tìm kiếm.

## 🎯 Tính năng chính

- **Nhúng full màn hình**: Iframe chiếm toàn bộ viewport, không có header hay thành phần nào khác
- **SEO tối ưu**: Đầy đủ meta tags, Open Graph, Twitter Cards, Structured Data
- **Responsive**: Tương thích với mọi thiết bị
- **PWA Ready**: Hỗ trợ Progressive Web App
- **Clean UI**: Giao diện sạch, chỉ hiển thị nội dung AECK

## 📁 Cấu trúc file

```
├── index.html          # Trang chính với iframe nhúng AECK
├── sitemap.xml         # Sitemap cho SEO
├── robots.txt          # Hướng dẫn cho search engine bots
├── manifest.json       # PWA manifest
└── README.md          # File hướng dẫn này
```

## 🔍 Tối ưu SEO

### Meta Tags được bao gồm:
- **Title & Description**: Tối ưu cho từ khóa "AECK", "khóa học TSA"
- **Keywords**: Các từ khóa liên quan đến giáo dục trực tuyến
- **Open Graph**: Tối ưu cho chia sẻ trên Facebook, LinkedIn
- **Twitter Cards**: Tối ưu cho chia sẻ trên Twitter
- **Canonical URL**: Tránh duplicate content
- **Structured Data**: JSON-LD cho rich snippets

### Hình ảnh SEO:
- Logo AECK: `https://file.edubit.vn/storage/.../aeck-2.png`
- Hình minh họa khóa học
- Hình ảnh về chất lượng và thanh toán

### Sitemap bao gồm:
- URL chính với priority 1.0
- Tất cả hình ảnh quan trọng với title và caption
- Thông tin lastmod và changefreq

## 🚀 Cách sử dụng

1. **Deploy lên web server**: Upload tất cả files lên hosting
2. **Cấu hình domain**: Đảm bảo domain trỏ đúng
3. **Test SEO**: Sử dụng Google Search Console để kiểm tra
4. **Submit sitemap**: Gửi sitemap.xml lên Google Search Console

## 📱 Tính năng PWA

- Manifest.json với đầy đủ thông tin app
- Icons và screenshots
- Hỗ trợ offline (có thể mở rộng thêm)
- Theme color và background color

## ⚡ Performance

- Lazy loading cho iframe
- Timeout handling (15 giây)
- Error handling với fallback
- Responsive design
- Optimized loading states

## 🛠️ Tùy chỉnh

### Thay đổi màu sắc:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
}
```

### Thêm Analytics:
Thêm mã tracking vào function `trackPageView()` trong script

### Tùy chỉnh loading:
Chỉnh sửa timeout và loading message trong JavaScript

## 📊 Monitoring

- Console logs cho debugging
- Error handling cho iframe loading
- Message handling từ iframe
- Responsive behavior tracking

## 🔒 Bảo mật

- Iframe sandbox với các quyền cần thiết
- Referrer policy strict-origin-when-cross-origin
- CSP headers (có thể thêm vào server config)

## 📞 Hỗ trợ

Nếu có vấn đề với trang web, vui lòng:
1. Kiểm tra console browser để xem lỗi
2. Đảm bảo kết nối internet ổn định
3. Thử truy cập trực tiếp https://aeck.edubit.vn/

## ✨ Điểm nổi bật

- **Full màn hình**: Iframe chiếm 100% viewport (100vw x 100vh)
- **Bảo mật**: Iframe sandbox với quyền hạn phù hợp
- **SEO hoàn chỉnh**: Tất cả meta tags cần thiết cho tối ưu tìm kiếm
- **Mobile-first**: Responsive và PWA ready
- **Tối giản**: Không có loading screen hay header, chỉ nội dung thuần từ AECK
- **Performance**: Tối ưu tốc độ tải và hiệu suất

---

**Phát triển bởi**: AECK Team
**Vận hành bởi**: [Edubit](https://edubit.vn)
**Cập nhật**: 2025-01-09
