# minigame_cam

Kho công cụ HTML tĩnh của **NTCONS** — demo 3D kỹ thuật, tiện ích offline và trang giới thiệu liên minh chuyên gia.

**Live:** [https://minigame-cam.vercel.app/](https://minigame-cam.vercel.app/)  
**Repo:** [trixd2026-max/minigame_cam](https://github.com/trixd2026-max/minigame_cam)

---

## Mục lục nhanh

| Nhóm | Nội dung |
|------|----------|
| Trang chủ | `index.html` — danh mục tự động tất cả file HTML |
| NTCONS | Trang thương hiệu, QR Zalo, liên hệ |
| Demo 3D | Drone Sky, Dải Ngân Hà, mô hình BTCT / LPG / cầu kiện… |
| Tiện ích | Tarot, Đổi Âm–Dương lịch offline |

---

## Trang chính & thương hiệu

| File | Mô tả |
|------|--------|
| [index.html](./index.html) | Danh mục công cụ — tự đọc danh sách file từ GitHub API |
| [NTCONS.html](./NTCONS.html) | Trang giới thiệu NTCONS · Liên minh chuyên gia |
| [ntcons-logo.png](./ntcons-logo.png) | Logo NTCONS |
| [zalo-qr.png](./zalo-qr.png) | Mã QR Zalo (`https://zalo.me/0389216492`) |

---

## Demo 3D & không gian

| File | Mô tả |
|------|--------|
| [Drone Sky Milky.html](./Drone%20Sky%20Milky.html) | Nhà 3D · Galaxy · điều khiển drone |
| [Drone Sky.html](./Drone%20Sky.html) | Nhà 3D interactive |
| [DAI NGAN HA.html](./DAI%20NGAN%20HA.html) | Dải Ngân Hà procedural |

---

## Công cụ kỹ thuật NTCONS

| File | Mô tả |
|------|--------|
| [NTCONS_Be_BTCT_3D_R15_Maps_Separate_Control.html](./NTCONS_Be_BTCT_3D_R15_Maps_Separate_Control.html) | Bê BTCT 3D R15 — maps & control tách |
| [NTCONS_Cau_kien_3D_DXF_R8.html](./NTCONS_Cau_kien_3D_DXF_R8.html) | Cầu kiện 3D DXF R8 |
| [NTCONS_CumBe_LPG_3D_R15.html](./NTCONS_CumBe_LPG_3D_R15.html) | Cụm bể LPG 3D R15 |
| [NTCONS_CumBe_LPG_3D_R16.html](./NTCONS_CumBe_LPG_3D_R16.html) | Cụm bể LPG 3D R16 |
| [NTCONS_CumBe_LPG_3D_R24.html](./NTCONS_CumBe_LPG_3D_R24.html) | Cụm bể LPG 3D R24 |
| [NTCONS_Thang_long_thep_3D_R5.html](./NTCONS_Thang_long_thep_3D_R5.html) | Thang long thép 3D R5 |
| [NTCONS_Tinh_dac_trung_tiet_dien_R3.html](./NTCONS_Tinh_dac_trung_tiet_dien_R3.html) | Tính đặc trưng tiết diện R3 |

---

## Tiện ích khác

| File | Mô tả |
|------|--------|
| [NTCONS_Tarot_R4.html](./NTCONS_Tarot_R4.html) | NTCONS Tarot R4 — 78 lá (Rider–Waite–Smith) |
| [Doi_Am_Duong_Lich_Offline_1800_2199_v2.html](./Doi_Am_Duong_Lich_Offline_1800_2199_v2.html) | Đổi Âm–Dương lịch offline (1800–2199) |

---

## Deploy

- **Production:** [https://minigame-cam.vercel.app/](https://minigame-cam.vercel.app/)
- **Vercel project:** `minigame-cam` (team `trixd2026-9658s-projects`)
- Stack: static HTML/CSS/JS — không cần build
- Nhánh deploy: `main`

Mọi file `.html` (trừ `index.html`) được `index.html` nhận diện tự động qua GitHub API và hiện trên trang chủ.

---

## Ghi chú

- Repo private; trang public qua Vercel.
- Thương hiệu **NTCONS** (đổi từ AS Group / AS_*).
- Liên hệ Zalo: quét QR trên [NTCONS.html](./NTCONS.html) hoặc mở [zalo.me/0389216492](https://zalo.me/0389216492).

```
minigame_cam/
├── index.html
├── NTCONS.html
├── ntcons-logo.png
├── zalo-qr.png
├── Drone Sky*.html
├── DAI NGAN HA.html
├── NTCONS_*.html          # công cụ kỹ thuật + Tarot
├── Doi_Am_Duong_Lich_*.html
└── README.md
```
