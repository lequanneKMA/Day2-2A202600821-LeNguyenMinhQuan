# 03 — Individual Reflection

## Đóng góp của Quân trong nhóm

| Hoạt động | Quân đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra 10 problems, tập trung vào đời sống hàng ngày (thuê đồ, quản lý chi tiêu, hợp đồng). | Nhóm có nguồn ý tưởng phong phú, thực tế về mảng B2C. |
| Pitch & Shortlist | Pitch problem "Thuê đồ đạc ngắn hạn", "Đọc hợp đồng" và "Quản lý chi tiêu". | Bài toán "Thuê đồ" lọt vào vòng thảo luận sâu nhưng loại do thiên về xây Platform. |
| Rule / Workflow / Agent | Làm Phase 6: Lập luận ma trận AI, phân tích chi tiết lý do chọn Workflow và không chọn Rule/Agent cho bài Đối chiếu bill. | Nhóm thống nhất được decision chọn Workflow và kiểm soát được rủi ro AI. |
| Problem Statement v1 & Decision | Hoàn thiện bảng Problem Statement v1 và lập bảng rủi ro/human review. Đưa ra quyết định "Go - pilot nhỏ". | Trình bày rõ ràng boundary của AI, chốt được các bước test OCR tiếp theo. |

## Bảng dùng AI trong quá trình làm bài

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan | Cấu trúc hóa 10 ideas thành bảng Markdown. | Viết nhanh, tự động phân cột rõ ràng, gọn gàng. | Đôi khi AI tự động tóm lược đi các dấu hiệu "đau" cốt lõi. | Ghi đè lại bằng văn phong thực tế và số liệu cụ thể. |
| Workflow | Tạo mã Mermaid Flowchart để visualize quy trình trước/sau. | Dựng biểu đồ trong vài giây thay vì tự vẽ tay thủ công. | Flowchart đôi khi bỏ qua các bước xác nhận rủi ro của con người. | Bổ sung các cụm từ làm rõ bottleneck và gán màu cảnh báo (đỏ). |
| Tham vấn Phase 6 | Nhờ AI phân tích ma trận độ phù hợp Rule/Workflow/Agent. | Giúp liệt kê các rủi ro nếu dùng Agent cho bài toán tài chính. | AI thường đề xuất Agent quá sớm hoặc over-engineer. | Ép AI phân tích ngược lại lý do tại sao Workflow là đủ cho bài này. |

## Bài học của Quân

- **Hiểu sâu về Bottleneck:** Vấn đề có giá trị nhất không phải là vấn đề nghe có vẻ "đao to búa lớn", mà là quy trình nào có đo lường thủ công lặp lại tốn kém nhất (như việc quản lý phải dò tay tìm bill trùng mất 30-40 phút).
- **Agent không phải đích đến mặc định:** Trong case của nhóm (Đối chiếu bill chuyển khoản), Workflow hợp lý hơn rất nhiều vì đường đi cố định, rủi ro tài chính cao, bắt buộc phải có human review (Quản lý ca check).
- **Rủi ro luôn đi kèm:** Thiết kế luồng AI cần có "fallback" (phương án lùi). Ví dụ mô hình OCR không đọc được ảnh mờ thì quản lý có thể tự nhập tay dòng đó, tuyệt đối không block hệ thống thay vì phụ thuộc 100% vào AI.

Nếu làm lại:
> Tôi sẽ đặt thêm các khảo sát về thực tế chất lượng ảnh đầu vào (ảnh Zalo bị mờ, vỡ nét, ... có chiếm tỷ trọng lớn không) để validate xem giải pháp OCR Workflow có thực sự khả thi trước khi quyết định "Go".
