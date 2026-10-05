# app-tonghop-xd

Kho công cụ HTML tĩnh của **NTCONS** — demo kỹ thuật 3D, tiện ích offline và trang giới thiệu liên minh chuyên gia.

**Repo:** [xaydungnguyenthuc-hub/app-tonghop-xd](https://github.com/xaydungnguyenthuc-hub/app-tonghop-xd)

---

## Mục lục nhanh

| Nhóm | Nội dung |
|------|----------|
| Trang chủ | `index.html` — danh mục tự động tất cả file HTML |
| NTCONS | Trang thương hiệu, QR Zalo, liên hệ |
| Demo / công cụ kỹ thuật | Bê BTCT, Cầu kiện 3D, Đặc trưng tiết diện, Thang Long… |
| Tiện ích | Bói bài (Tarot), Lịch Âm–Dương offline |
| Cẩm nang & quy trình | Quản lý ĐTXD, quy hoạch cấp xã, VBPL, render kiến trúc… |

---

## Trang chính & thương hiệu

| File | Mô tả |
|------|--------|
| [index.html](./index.html) | Danh mục công cụ — tự đọc danh sách file từ GitHub API |
| [NTCONS.html](./NTCONS.html) | Trang giới thiệu NTCONS · Liên minh chuyên gia |
| [ntcons-logo.png](./ntcons-logo.png) | Logo NTCONS |
| [zalo-qr.png](./zalo-qr.png) | Mã QR Zalo |

---

## Công cụ kỹ thuật & demo 3D

| File | Mô tả |
|------|--------|
| [Be BTCT.html](./Be%20BTCT.html) | Bê BTCT 3D |
| [Cau Kien 3D.html](./Cau%20Kien%203D.html) | Cầu kiện 3D |
| [Dac Tinh Tiet Dien.html](./Dac%20Tinh%20Tiet%20Dien.html) | Tính đặc trưng tiết diện |
| [Thang Long.html](./Thang%20Long.html) | Thang long thép 3D |
| [WindNTcons-main.html](./WindNTcons-main.html) | Wind NTCONS |

---

## Cẩm nang & quy trình

| File | Mô tả |
|------|--------|
| [camnanquanlydtxd-main.html](./camnanquanlydtxd-main.html) | Cẩm nang quản lý ĐTXD |
| [chondamxoan-giocotsanmong-main.html](./chondamxoan-giocotsanmong-main.html) | Chọn đầm xoắn / gio cốt sàn móng |
| [quytrinhquyhoachcapxa-main.html](./quytrinhquyhoachcapxa-main.html) | Quy trình quy hoạch cấp xã |
| [renderkientruc-main.html](./renderkientruc-main.html) | Render kiến trúc |
| [thuvienvbpl-main.html](./thuvienvbpl-main.html) | Thư viện VBPL |

---

## Tiện ích khác

| File | Mô tả |
|------|--------|
| [Boi Bai.html](./Boi%20Bai.html) | Bói bài (Tarot) |
| [Lich am Duong.html](./Lich%20am%20Duong.html) | Đổi Âm–Dương lịch offline |

---

## Deploy

- Stack: static HTML/CSS/JS — không cần build
- Nhánh deploy: `main`
- Mọi file `.html` (trừ `index.html`) được `index.html` nhận diện tự động qua GitHub API và hiện trên trang chủ.

---

## Ghi chú

- Thương hiệu **NTCONS**
- Liên hệ Zalo: quét QR trên [NTCONS.html](./NTCONS.html)

```
app-tonghop-xd/
├── index.html
├── NTCONS.html
├── ntcons-logo.png
├── zalo-qr.png
├── Be BTCT.html
├── Cau Kien 3D.html
├── Dac Tinh Tiet Dien.html
├── Thang Long.html
├── WindNTcons-main.html
├── camnanquanlydtxd-main.html
├── chondamxoan-giocotsanmong-main.html
├── quytrinhquyhoachcapxa-main.html
├── renderkientruc-main.html
├── thuvienvbpl-main.html
├── Boi Bai.html
├── Lich am Duong.html
└── README.md
```
