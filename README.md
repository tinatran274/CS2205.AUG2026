# CS2205.AUG2026 – Phương pháp luận nghiên cứu khoa học

**Đề tài:** ĐÁNH GIÁ TÁC ĐỘNG CỦA CÁC PHƯƠNG PHÁP TĂNG SÁNG ẢNH THIẾU SÁNG ĐẾN HIỆU QUẢ PHÁT HIỆN ĐỐI TƯỢNG CỦA YOLO26: SO SÁNH GIỮA CHẤT LƯỢNG ẢNH VÀ ĐỘ CHÍNH XÁC PHÁT HIỆN

**English title:** EVALUATING THE IMPACT OF LOW-LIGHT IMAGE ENHANCEMENT METHODS ON YOLO26 OBJECT DETECTION: IMAGE QUALITY VERSUS DETECTION ACCURACY

- **Học viên:** Trần Thị Hồng Nhung – MSHV 26848157
- **Môn học:** CS2205 – Phương pháp luận nghiên cứu khoa học (PGS.TS. Lê Đình Duy)
- **Trường:** Trường Đại học Công nghệ Thông tin, ĐHQG-HCM

## Tài liệu đồ án

| Tài liệu | Link |
|---|---|
| Đề cương nghiên cứu (PDF) | [Đề cương](Nhung%20Tr%E1%BA%A7n%20Th%E1%BB%8B%20H%E1%BB%93ng%20-%20CS2205.AUG2026.DeCuong.FinalReport.Template.Doc.pdf) |
| Slide trình bày (PDF) | [Slide](Nhung%20Tr%E1%BA%A7n%20Th%E1%BB%8B%20H%E1%BB%93ng%20-%20CS2205.AUG2026.DeCuong.FinalReport.Template.Slide.pdf) |
| Poster (PDF) | [Poster](Nhung%20Tr%E1%BA%A7n%20Th%E1%BB%8B%20H%E1%BB%93ng%20-%20CS2205.AUG2026.DeCuong.FinalReport.Template.Poster.pdf) |
| Video YouTube (≤ 5 phút) | _cập nhật sau_ |

## Tóm tắt

Đề tài đánh giá tác động của sáu phương pháp tăng sáng ảnh thiếu sáng thuộc ba nhóm – cổ điển (HE, CLAHE), học sâu không cần dữ liệu cặp (Zero-DCE, EnlightenGAN) và học sâu có giám sát (RetinexNet, Retinexformer) – khi dùng làm bước tiền xử lý cho bộ phát hiện đối tượng YOLO26. Thực nghiệm dự kiến trên hai bộ dữ liệu LOL và ExDark; chất lượng ảnh (PSNR, SSIM, NIQE, BRISQUE) được so sánh với độ chính xác phát hiện (mAP@0.5, mAP@0.5:0.95, Precision, Recall) và thời gian xử lý, sau đó phân tích tương quan Spearman giữa hai nhóm chỉ số để đưa ra khuyến nghị lựa chọn phương pháp tăng sáng.
