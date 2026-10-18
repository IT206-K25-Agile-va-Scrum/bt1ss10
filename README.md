# BÀI THỰC HÀNH 1 - CHUẨN BỊ SPRINT REVIEW ỨNG DỤNG RIKKEISAFE

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Nhiệm vụ 1: Hoàn thành phiếu chuẩn bị Sprint Review

Dưới đây là bảng phiếu chuẩn bị Sprint Review hoàn chỉnh với các bước 2, 3, 5 được điền bổ sung dựa trên kết quả cuối Sprint và ngữ cảnh của ứng dụng RikkeiSafe.

- Bước 1, 4, 6 được giữ nguyên theo đúng đề bài.
- Bước 2 bám sát trạng thái thực tế của 5 PBI và các điều kiện DoD.
- Bước 3 xây dựng luồng User Journey thực tế của người dùng.

| Bước | Việc cụ thể cho buổi Review này |
| --- | --- |
| 1. Chốt mục tiêu và người tham gia | Mục tiêu: xem người dùng có tự kiểm tra được số, link và hiểu cảnh báo không. Mời đủ 3 Stakeholders. |
| 2. Kiểm tra Increment | PBI được trình diễn là Done: PBI-01, PBI-02, PBI-03. PBI chưa Done kèm DoD chưa đạt: PBI-04 (thiếu xóa lịch sử, lọc theo loại), PBI-05 (chưa review chéo, mới kiểm thử trên máy tính). |
| 3. Chọn User Journey và người demo | User Journey: Mở app -> Nhập số điện thoại nghi vấn -> Xem cảnh báo kèm lý do -> Gửi báo cáo số đáng ngờ. Người demo: Thu An. |
| 4. Chuẩn bị kỹ thuật | Kiểm tra bản chạy được, tài khoản dùng thử, đường truyền họp trực tuyến. |
| 5. Chuẩn bị trao đổi | 2 câu hỏi mở dành cho Stakeholders: 'Cô Mai thấy cỡ chữ cảnh báo trên điện thoại đã dễ đọc chưa?' và 'Anh Phúc đánh giá thế nào về tốc độ kiểm tra đường link?' |
| 6. Chia thời gian | Xem lịch trình ở Nhiệm vụ 2. |

## Nhiệm vụ 2: Sửa lịch trình Sprint Review

Lịch trình 35 phút của Product Owner Ngọc Hương cần được điều chỉnh lại cho phù hợp với vai trò của từng bên trong Scrum Team và Stakeholders, tránh việc Developer tự báo cáo việc cá nhân hoặc Product Owner làm thay việc của nhóm phát triển.

| Thời gian | Hoạt động | Nhận xét và cách sửa |
| --- | --- | --- |
| 0–5' | Product Owner nhắc Sprint Goal. | Phù hợp, giữ nguyên. |
| 5–20' | Product Owner trình diễn cả 5 PBI, giới thiệu PBI-05 là đã hoàn thành. | Sai ở chỗ Product Owner trình diễn PBI-05 (chưa Done) và làm thay việc của Developer. Sửa thành: Developers (Thu An) trình diễn các tính năng đã hoàn thành (PBI-01, PBI-02, PBI-03), đồng thời minh họa rõ trạng thái thực tế của PBI-04 và PBI-05. |
| 20–32' | Từng Developer lần lượt báo cáo việc cá nhân mình đã làm. | Sai ở chỗ Sprint Review không phải là buổi họp báo cáo công việc nội bộ cá nhân. Sửa thành: Mở rộng không gian để Stakeholders trực tiếp trải nghiệm bản Increment trên thiết bị của họ và đưa ra góp ý. |
| 32–35' | Stakeholders được nói trong 3 phút cuối; Scrum Master chốt góp ý nào sẽ làm ở Sprint sau. | Sai ở hai điểm: Thứ nhất, Stakeholders chỉ được nói 3 phút là quá ít. Thứ hai, Scrum Master không có quyền chốt góp ý nào sẽ làm ở Sprint sau. Sửa thành: Dành toàn bộ thời gian này để lắng nghe Feedback từ Stakeholders; Product Owner ghi nhận và sẽ quyết định đưa vào Product Backlog chứ không hứa làm ngay. |

## Nhiệm vụ 3: Ghi nhận Feedback

Việc xử lý các góp ý từ Stakeholders cần tuân thủ nguyên tắc ghi nhận khách quan vào Product Backlog để Product Owner sắp xếp độ ưu tiên, tuyệt đối không hứa hẹn làm ngay trong buổi Sprint Review.

| Mã | Góp ý | Cách xử lý |
| --- | --- | --- |
| FB-01 | Anh Phúc: nên có nút hướng dẫn gọi ngân hàng khi người dùng báo đã chuyển tiền. | Ghi vào Product Backlog để Product Owner xem xét cùng PBI-05; chưa hứa làm ngay. |
| FB-02 | Chị Vy: muốn thêm chức năng chia sẻ cảnh báo cho người thân. Việc này nằm ngoài Sprint Goal. | Product Owner ghi nhận ý kiến vào Product Backlog, cảm ơn chị Vy đã đóng góp ý tưởng mở rộng, giải thích tính năng này nằm ngoài phạm vi hiện tại và sẽ được cân nhắc cho các phiên bản phát hành tương lai. |
| FB-03 | Cô Mai: dán đường link rất dài thì nút 'Kiểm tra' bị đẩy ra ngoài màn hình điện thoại (PBI-02). | Scrum Team ghi nhận đây là lỗi giao diện thực tế trên thiết bị của người dùng lớn tuổi. Product Owner đưa vào Product Backlog dưới dạng lỗi UX cần ưu tiên xử lý sớm ở Sprint tiếp theo để cải thiện trải nghiệm. |

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
