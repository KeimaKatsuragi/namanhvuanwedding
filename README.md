# 💍 Thiệp Cưới Online - Clone Cinelove Template 42

Clone hoàn chỉnh website thiệp cưới từ https://cinelove.me/template/pc/thiep-cuoi-42

## ✨ Đặc điểm

- **Clone 100% giao diện** từ website gốc
- **Absolute positioning** giống hệt template gốc
- **Animations** chính xác theo từng element
- **Fonts** chính xác: Great Vibes, Quicksand, Carlytte, Belinda Avenue, HoaTay1, The Artisan, PlayfairDisplay, Aquarelle, The Hamstter
- **Layout** 500px x 8382px canvas container
- **All images** từ CDN Cinelove

## 📂 Cấu trúc

```
wedding-invitation/
├── index.html          # HTML với absolute positioning
├── css/
│   └── style.css      # CSS với animations
├── js/
│   └── script.js      # JavaScript countdown, music, form
├── images/            # (Sử dụng CDN, không cần tải)
└── assets/
    └── music.mp3      # Nhạc nền (cần thêm)
```

## 🎯 Các section đã clone

1. ✅ Opening Screen với cover photo
2. ✅ WEDDING INVITATION header
3. ✅ Countdown timer (đếm ngược đến 25/12/2025 10:30)
4. ✅ INVITATION message
5. ✅ Lễ Thành Hôn
6. ✅ Thông tin cha mẹ hai bên
7. ✅ Tên cô dâu chú rể
8. ✅ Địa điểm và thời gian
9. ✅ SWEET WEDDING (MARRY ME? YES I DO!)
10. ✅ About us (thông tin cô dâu chú rể)
11. ✅ Save the date (lịch tháng 12/2025)
12. ✅ Timeline (08:00 Lễ Rước Dâu, 09:30 Chụp hình, 10:30 Khai tiệc)
13. ✅ RSVP Form (xác nhận tham dự)
14. ✅ Quotes (I love you forever, Nice to meet you)
15. ✅ Gửi quà mừng (QR code chuyển khoản)
16. ✅ Thank you

## 🎨 Fonts được sử dụng

- **Great Vibes**: Cho chữ &, decorative
- **Quicksand**: Font chính cho text
- **Carlytte**: Titles lớn
- **Belinda Avenue**: Roles (Bride/Groom)
- **HoaTay1**: Tên người
- **The Artisan**: Địa chỉ
- **PlayfairDisplay**: Event details
- **Aquarelle**: Subtitles
- **The Hamstter**: Thank you

## 🖼️ Images từ CDN

Tất cả ảnh đều dùng trực tiếp từ CDN:
- Cover photo: `https://cdn.cinelove.me/templates/assets/5731de59-c0f3-4fa7-9860-e5e47b829ce3/...`
- Icons: `https://cdn-resource.cinelove.me/resources/...`
- Music icon: `https://cdn.cinelove.me/assets/audio-6.png`

## 🎵 Thêm nhạc nền

1. Tải file nhạc (MP3)
2. Đặt vào `assets/music.mp3`
3. Website sẽ tự động phát khi mở thiệp

## 🔧 Tùy chỉnh

### Thay đổi thông tin cặp đôi

Mở `index.html` và tìm các phần sau:

```html
<!-- Tên cô dâu -->
Mai Anh

<!-- Tên chú rể -->
Quốc Huy

<!-- Ngày sinh -->
12/05/2000
05/08/1995

<!-- Địa chỉ -->
TP. Điện Biên
TP. Hà Nội
```

### Thay đổi ngày cưới

Mở `js/script.js`:

```javascript
const weddingDate = new Date('2025-12-25T10:30:00').getTime();
```

### Thay đổi thông tin cha mẹ

```html
<!-- Nhà Trai -->
Ông: Phạm Quang Hải
Bà : Định Thị Mai

<!-- Nhà Gái -->
Ông : Nguyễn Tiến Minh
Bà : Lê Thị Hải Yến
```

### Thay đổi địa điểm tổ chức

```html
TRỐNG ĐỒNG PALACE
(18A Lý Văn Phức, P. Ô Chợ Dừa, Tp Hà Nội)
```

### Thay đổi số tài khoản

```html
MB Bank : 012345678
```

## 📱 Responsive

Website có responsive cơ bản cho mobile:
- Scale down canvas container
- Điều chỉnh font sizes
- Cover photo nhỏ hơn

## 🌐 Deploy

### GitHub Pages

```bash
git init
git add .
git commit -m "Wedding invitation"
git branch -M main
git remote add origin https://github.com/username/wedding.git
git push -u origin main

# Vào Settings > Pages > chọn branch main
```

### Netlify

1. Kéo thả thư mục vào Netlify
2. Website live ngay lập tức

### Vercel

```bash
npm install -g vercel
vercel
```

## 📊 Kích thước

- **Canvas**: 500px x 8382px
- **Opening Screen**: Full viewport
- **Total elements**: ~50+ positioned divs
- **Fonts loaded**: 9 Google Fonts

## ⚡ Performance

- Sử dụng CDN cho tất cả images
- Lazy load fonts
- Minimal JavaScript
- CSS transitions smooth

## 🐛 Troubleshooting

### Nhạc không tự động phát
- Browser chặn autoplay, cần user interaction
- Click nút "Chạm để mở thiệp" sẽ phát nhạc

### Font không hiển thị đúng
- Kiểm tra Google Fonts link trong `<head>`
- Clear cache browser

### Layout bị lệch
- Kiểm tra viewport meta tag
- Kiểm tra absolute positioning values

## 📝 Notes

- Website clone theo cấu trúc **absolute positioning** giống y hệt gốc
- Tất cả positions (top, left) được copy chính xác
- Colors, fonts, sizes đều match với original
- Animations: fade-in-up, slide-left, slide-right
- Scroll animations khi user scroll

## 🎓 Học từ template này

Template này dạy bạn:
- Absolute positioning layout
- Complex animations
- Countdown timer
- Music player integration
- Form handling
- Responsive design
- CDN usage

## 💝 Credits

- Original template: [Cinelove.me](https://cinelove.me)
- Template: Thiệp Cưới 42
- All images © Cinelove
- Fonts: Google Fonts

## 📄 License

Educational purpose only. Original design © Cinelove.

---

**Made with ❤️ for Mai Anh & Quốc Huy - 25/12/2025**