# Cún Tý Homestay – Website quảng bá homestay

Website đơn giản, tốc độ cao, responsive (mobile-first), dễ dàng chỉnh sửa nội dung và deploy lên Vercel.

## Cấu trúc

```
homestay/
├── index.html    # Trang chủ đầy đủ
├── styles.css    # CSS (nếu muốn tách)
└── README.md     # Hướng dẫn
```

## Nội dung chính

- **Hero** – tên homestay, tagline, CTA booking
- **Stats** – thiên nhiên hoang dã, xe đạp, bếp chung
- **Dịch vụ** - Wi-Fi, bếp chung, xe đạp, vườn, sân hiên, bể cá
- **Về chúng tôi** – mô tả không gian và giá trị
- **Phòng** – 3 gói phòng (phòng thường, gia đình)
- **Ảnh** – placeholder (bạn sẽ thay bằng ảnh thật)
- **Đặt phòng** – form gửi yêu cầu → mở Zalo 0946979443
- **Footer** – fanpage placeholder, bản quyền

## Các thông tin đã cài sẵn

- Tên: **Cún Tý Homestay**
- Liên hệ: Zalo **0946979443** – Đinh Minh Quang
- Fanpage: placeholder
- Ảnh: placeholder (thay bằng ảnh thật)

## Cách chỉnh sửa

1. Mở file `index.html`
2. Tìm từ khóa "placeholder" để thay đổi
3. Thay giá tiền, số liệu, chữ giải thích...
4. Lưu thả và deploy lên Vercel

## Tối ưu SEO (dạng nhanh)

- `<title>`: Cún Tý Homestay – Nghỉ dưỡng giữa Thiên nhiên Hoang Dã
- `<meta name="description">`: Nội dung hiển thị trên Google
- Thêm `og:` tags nếu muốn chia sẻ lên Facebook/Zalo

## Đăng ký domain (tùy chọn)

1. Mua domain từ `namecheap.com`, `google.com/domains`, `netlify.com`...
2. Cấu hình DNS:
   - **A record** → Vercel: `https://vercel.com/dashboard` → viral
   - Hoặc dùng **CNAME** → `www.yourdomain.com` → `@` (hoặc `cname.vercel-dns.com`)

## Lưu ý

- Giá tiền đã được ước tính (theo giá sàn) – cần cập nhật lại đúng giá thực
- Ảnh thật giúp trang chắc chắn hơn – thay placeholder bằng ảnh
- Form booking hiện chỉ mở Zalo – thay bằng form HTML/email/booking.com nếu cần
