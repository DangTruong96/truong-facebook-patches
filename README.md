# Bản vá Morphe cho Facebook (bản cá nhân)

Bundle `.mpp` dựng sẵn cho Morphe Manager. Hỗ trợ Facebook 584.0.0.51.56.

Thêm vào Morphe Manager: https://morphe.software/add-source?github=DangTruong96/truong-facebook-patches

Nguồn gốc: HushFacebook by SysAdminDoc (GPL-3.0) + feed Following/Mới nhất bật mặc định + lưu ảnh bật mặc định + ẩn thanh tab khi ở tab Reel (mặc định bật; tắt trong Cài đặt Hushfacebook → Appearance). Chỉ dùng cá nhân.

Lưu ý: APK vá bằng Morphe Manager được ký bằng keystore trong Manager của bạn; APK vá sẵn do chủ repo gửi riêng được ký bằng keystore khác — với mỗi app, hãy chọn một đường và dùng nhất quán để các bản cập nhật cài đè được lên nhau.

## Changelog

- **0.17.6** (30/10/2026): sửa dải đen ở đáy trang Reel khi thanh tab ẩn — nguyên nhân là phần đệm dưới của chính khung chứa các tab (Facebook tự đệm bằng đúng chiều cao thanh tab khi dựng khung), không phải chân trang của Reel. Khi ẩn thanh tab, bản vá nay thu hồi luôn phần đệm đó nên video tràn xuống đáy màn hình, thanh tiến trình nằm ở mép dưới video; hiện thanh lại thì trả đệm về như cũ. Đi cùng công tắc "Ẩn thanh tab khi ở trang Reel" (Cài đặt Hushfacebook → Appearance, mặc định Bật), không thêm công tắc mới. Tổng 98 bản vá.
- **0.17.4** (30/10/2026): thêm patch thử nghiệm "Chia đôi màn hình khi mở bình luận ở Reel" — tấm bình luận dừng ở nửa màn hình thay vì che ~80%, nửa trên vẫn hiển thị video, vẫn kéo tấm lên/xuống được. Công tắc ở Cài đặt Hushfacebook → Comments, mặc định Bật. Thêm công tắc "Nền thanh tab trong suốt hơn" — nền thanh tab khi đang hiện chỉ còn ~50% độ mờ đục so với gốc, icon giữ nguyên; Cài đặt Hushfacebook → Appearance, mặc định Bật. Tổng 98 bản vá.
- **0.17.3** (30/10/2026): thêm patch thử nghiệm "Đẩy video lên trên cùng khi mở bình luận" — khi mở bình luận, video được đẩy sát lên trên thay vì căn giữa, không còn dải đen phía trên video. Công tắc ở Cài đặt Hushfacebook → Comments, mặc định Bật. Tổng 97 bản vá.
