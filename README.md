# Vườn Ép — Thế giới giấy mở

Thế giới giấy vô tận cho quán nước ép Vườn Ép: đi bộ khám phá, bấm vào quán để xem thực đơn.

## Chạy thử

Mở trực tiếp `index.html` bằng trình duyệt, hoặc chạy server tĩnh:

```bash
python3 -m http.server 8000
```

Rồi mở http://localhost:8000

Cần mạng để tải three.js (CDN) và font Baloo 2 (Google Fonts).

## Có gì trong này

- **Quán 2 tầng** ở trung tâm: mặt tiền mở hẳn, cầu thang gỗ 16 bậc đi lên sân thượng được thật, sân thượng có bàn ghế camping, hộp hoa, dây đèn lồng và 2 mèo giấy.
- **Đi bộ**: phím WASD / mũi tên, joystick trên cảm ứng; kéo chuột để xoay camera.
- **Thực đơn 20 món**: bấm vào thân quán hoặc quầy để mở (giá theo ngày, hỏi tại quán).
- **22 loại cây quả**, mỗi loại vẽ riêng đúng dáng thật: cam sành, chanh leo, dứa, dưa hấu, xoài, ổi, cóc, bưởi, táo, thanh long, chuối, dừa, sầu riêng, măng cụt, chôm chôm, vải, nhãn, nho, dâu tây, bơ, đu đủ, mít.
- **Người giấy**: 2 nhân viên đi lại mang khay ra bàn, 3 khách ngồi uống nước; chó mèo đi lại quanh quán, chim bay.
- **Thời tiết theo giờ thật** (nắng, mây, mưa) và đèn sáng về đêm.
- **Khu Chợ** phía bắc quán: 3 sạp (trái cây tươi, trà trái cây, bánh ngọt), bấm để xem món đặc trưng.

## Kỹ thuật

- Một file duy nhất `index.html` (HTML + CSS + JS inline), không cần build.
- three.js r128 qua CDN, mọi hình vẽ bằng code (không dùng ảnh ngoài hay model 3D).
- Nội dung thực đơn lấy từ data pack tháng 10/2026 của quán.

## Nguồn gốc

Source xuất từ Space "Vườn Ép" (bản v21, 26/11/2026), làm bằng skill papercraft (xikhar/papercraft, MIT) trên nền three.js.
