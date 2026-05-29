# 03 — Individual Reflection

## Đóng góp của Quân trong nhóm

| Hoạt động | Quân đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra 10 problems, tập trung vào đời sống hàng ngày (thuê đồ, quản lý chi tiêu, hợp đồng). | Nhóm có nguồn ý tưởng phong phú, thực tế về mảng B2C. |
| Pitch & Shortlist | Pitch problem "Thuê đồ đạc ngắn hạn", "Đọc hợp đồng" và "Quản lý chi tiêu". | Bài toán "Thuê đồ" lọt vào vòng thảo luận sâu nhưng loại do thiên về xây Platform. |
| Phân tích Workflow | Vẽ Current / Future Workflow cho 3 Problem Cards. | Đo lường được số liệu thời gian thật, xác định đúng điểm Bottleneck. |
| Đánh giá Rule/AI | Đặt ra các phương án "Non-AI Alternative" để so sánh với "AI Hypothesis". | Giúp nhóm có cái nhìn thực tế: có bắt buộc phải dùng AI không. |

## Bảng dùng AI trong quá trình làm bài

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan | Cấu trúc hóa 10 ideas thành bảng Markdown. | Viết nhanh, tự động phân cột rõ ràng, gọn gàng. | Đôi khi AI tự động tóm lược đi các dấu hiệu "đau" cốt lõi. | Ghi đè lại bằng văn phong thực tế và số liệu cụ thể. |
| Workflow | Tạo mã Mermaid Flowchart để visualize quy trình trước/sau. | Dựng biểu đồ trong vài giây thay vì tự vẽ tay thủ công. | Flowchart đôi khi bỏ qua các bước xác nhận rủi ro của con người. | Bổ sung các cụm từ làm rõ bottleneck và gán màu cảnh báo (đỏ). |
| Tham vấn | Nhờ AI đề xuất giải pháp Non-AI. | Chỉ ra được những cách giải quyết bằng hệ thống Rule-based/API. | AI thường cố gắng biện rạch để nhấn mạnh AI là hoàn hảo. | Giữ quan điểm trung lập, khẳng định AI chỉ là lớp giá trị gia tăng ở vài case. |

## Bài học của Quân

- **Hiểu sâu về Bottleneck:** Vấn đề có giá trị nhất không phải là vấn đề nghe có vẻ "đao to búa lớn", mà là quy trình nào có đo lường thủ công lặp lại tốn kém nhất.
- **Không thần thánh hóa AI:** Nếu có thể giải quyết nhanh bằng 1 rule đơn giản hay 1 nền tảng kết nối, thì không nên dùng AI. AI chỉ đắt giá nhất ở năng lực hiểu ngôn ngữ/hình ảnh mờ (như bài toán đọc hợp đồng ToS hay quét biên lai).
- **Rủi ro luôn đi kèm:** Ở bài toán Đọc hợp đồng, việc ảo giác (hallucination) có thể khiến người dùng mất tiền hoặc kiện tụng, nên quy trình Future Workflow thiết kế bắt buộc phải có bước con người tự đưa ra quyết định cuối cùng chứ không duyệt tự động.

Nếu làm lại:
> Tôi sẽ cố gắng bóc tách sâu hơn vào các bài toán quy trình chuyên môn hẹp (nơi ít có Data công khai) thay vì các ứng dụng hàng ngày, vì ở đó giá trị trả về của AI thường rõ ràng hơn và ít đụng các bài toán Platform.
