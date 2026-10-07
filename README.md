# Ứng dụng Xây dựng — NTCONS Application Portal

Cổng tổng hợp các **công cụ HTML tĩnh** của **NTCONS**: demo kỹ thuật 3D, cẩm nang quản lý dự án đầu tư xây dựng, quy trình quy hoạch, thư viện văn bản pháp luật và tiện ích offline.

**Demo online:** [https://ungdungxaydung.vercel.app](https://ungdungxaydung.vercel.app)

---

## Tính năng trang chủ

- `index.html` — danh mục tất cả ứng dụng, tìm kiếm & lọc theo nhóm
- Giao diện responsive, hỗ trợ dark mode
- Mỗi công cụ là file HTML độc lập, mở trực tiếp trên trình duyệt (không cần server)

---

## Danh mục công cụ

### Trang chính & thương hiệu

| File | Mô tả |
|------|--------|
| [index.html](./index.html) | Cổng ứng dụng — danh mục, tìm kiếm, lọc |
| [NTCONS.html](./NTCONS.html) | Trang giới thiệu NTCONS · Liên minh chuyên gia |
| [ntcons-logo.png](./ntcons-logo.png) | Logo NTCONS |
| [zalo-qr.png](./zalo-qr.png) | Mã QR Zalo |

### Công cụ kỹ thuật & demo 3D

| File | Mô tả |
|------|--------|
| [Be BTCT.html](./Be%20BTCT.html) | Bê BTCT 3D |
| [Cau Kien 3D.html](./Cau%20Kien%203D.html) | Cầu kiện 3D |
| [Dac Tinh Tiet Dien.html](./Dac%20Tinh%20Tiet%20Dien.html) | Tính đặc trưng tiết diện |
| [Thang Long.html](./Thang%20Long.html) | Thang long thép 3D |
| [WindNTcons-main.html](./WindNTcons-main.html) | Wind NTCONS |

### Cẩm nang & quy trình

| File | Mô tả |
|------|--------|
| [camnanquanlydtxd-main.html](./camnanquanlydtxd-main.html) | Cẩm nang quản lý ĐTXD |
| [chondamxoan-giocotsanmong-main.html](./chondamxoan-giocotsanmong-main.html) | Chọn đầm xoắn / gio cốt sàn móng |
| [quytrinhquyhoachcapxa-main.html](./quytrinhquyhoachcapxa-main.html) | Quy trình quy hoạch cấp xã |
| [renderkientruc-main.html](./renderkientruc-main.html) | Render kiến trúc |
| [thuvienvbpl-main.html](./thuvienvbpl-main.html) | Thư viện VBPL |

### Tiện ích khác

| File | Mô tả |
|------|--------|
| [Boi Bai.html](./Boi%20Bai.html) | Bói bài (Tarot) |
| [Lich am Duong.html](./Lich%20am%20Duong.html) | Đổi Âm–Dương lịch offline |

---

## Cách sử dụng

### Online
Truy cập: [https://ungdungxaydung.vercel.app](https://ungdungxaydung.vercel.app)

### Offline
Tải từng file `.html` và mở bằng trình duyệt (Chrome, Edge, Firefox…).

### Deploy riêng
```bash
git clone https://github.com/xaydungnguyenthuc-hub/ungdungxaydung.git
cd ungdungxaydung
# Deploy lên Vercel / Netlify / GitHub Pages — không cần build
```

---

## Stack kỹ thuật

- HTML / CSS / JS tĩnh — không framework, không build step
- Mỗi tool là một file độc lập
- Trang chủ tự nhận diện danh sách file HTML

---

## Thương hiệu & liên hệ

- **NTCONS** — Liên minh chuyên gia
- Liên hệ Zalo: quét QR trên [NTCONS.html](./NTCONS.html)

---

## Đóng góp

Nếu muốn bổ sung công cụ mới hoặc sửa lỗi, hãy tạo Issue / Pull Request trên repository này.
