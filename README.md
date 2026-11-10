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
- **Stats** – 50+ con cún, thiên nhiên hoang dã, xe đạp, bếp chung
- **Dịch vụ** – cún tý, Wi-Fi, bếp chung, xe đạp, vườn, sân hiên, bể cá
- **Về chúng tôi** – mô tả không gian và giá trị
- **Phòng** – 3 gói phòng (phòng thường, gia đình, Hiền Yến)
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

## Hướng dẫn deploy lên Vercel (bước 1)

1. Mở [Vercel](https://vercel.com) → đăng nhậprepo GitHub
2. Nhấn "New Project" → import repo này
3. Cài đặt:
   - **Framework Preset**: Other
   - **Root Directory**: isolate (hoặc để trống)
   - **Build Command**: `echo "Static site"` (hoặc để trống)
   - **Output Directory**: `/` hoặc không cần
   - **Install Command**: (không cần, luôn thành công)
4. Chọn môi trường: **Production**
5. Nhấn **Deploy**

## Hướng dẫn deploy (bước 2 – CLI nếu đã có Vercel CLI)

```bash
# Cài Vercel CLI (nếu chưa)
npm i -g vercel

# Truy cập vào folder
cd /c/Users/Adminstrations/AppData/Local/hermes/cache/scratch/homestay

# Deploy
vercel --prod
```

## Tự động deploy (nếu dùng GitHub)

- Vercel sẽ tự cập nhật mỗi khi push code lên GitHub
- Cấu hình webhook tự động được thiết lập trong Vercel dashboard

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

- Giá tiền đã được ước tính (placeholder) – cần cập nhật lại đúng giá thực
- Ảnh thật giúp trang chắc chắn hơn – thay placeholder bằng ảnh
- Form booking hiện chỉ mở Zalo – thay bằng form HTML/email/booking.com nếu cần

## Tham khảo

- [Vercel Docs](https://vercel.com/docs)
- [GitHub Pages vs Vercel](https://vercel.com/docs)
