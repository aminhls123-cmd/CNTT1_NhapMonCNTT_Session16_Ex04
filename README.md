# Bài 4 : Tối ưu hóa Lưu trữ Dữ liệu Doanh nghiệp

## 1. Giải pháp kỹ thuật
* **Cơ chế:** Máy chỉ lưu vài MB trên local SSD, file video thực tế nằm trên Cloud và chỉ tải xuống khi mở trực tiếp.
* **Trạng thái:** tiết kiệm ổ cứng và tải tạm khi xem.

## 2. Báo cáo Dung lượng
| Chỉ tiêu | Trước khi tối ưu | Sau khi tối ưu |
| :--- | :--- | :--- |
| **Cloud Storage** | 500 GB | 500 GB |
| **Local SSD** | 500 GB (Tràn ổ cứng, treo máy) | ~ 50 - 200 MB (Chỉ chứa metadata) |
