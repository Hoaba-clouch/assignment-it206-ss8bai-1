# ƯỚC LƯỢNG PRODUCT BACKLOG CHO NỀN TẢNG BÁN HÀNG QUA LIVESTREAM

## Nhiệm vụ 1 - Kiểm tra dữ liệu trước khi ước lượng

| Mã Story | Đủ rõ | Cần làm rõ | Thông tin/câu hỏi còn thiếu |
|---|---|---|---|
| LS01 | X | ☐ | |
| LS03 | ☐ | X | Nếu nhiều người mua cùng đặt sản phẩm cuối cùng trong cùng một thời điểm, hệ thống sẽ xử lý như thế nào để đảm bảo không bán vượt tồn kho? |

## Nhiệm vụ 2 - Phân tích Planning Poker và chốt Story Point

| Mã Story | Mức ưu tiên | Kết quả phiếu | SP cuối cùng | Lý do ngắn |
|---|---|---|---|---|
| LS01 | 1 | 3 - 3 - 5 - 3 | 3 | Ban đầu có sự chênh lệch do lo ngại về xử lý trạng thái và thời gian. Tuy nhiên, PO đã làm rõ rằng việc tự động chuyển trạng thái nằm ngoài phạm vi Story này, làm giảm độ phức tạp. Do đó, LS01 có phạm vi và độ phức tạp tương đương LS02. |
| LS02 | 2 | 3 - 3 - 3 - 3 | 3 | Reference Story; các phiếu đã trùng nhau. |
| LS03 | 3 | 5 - 8 - 8 - 5 | 8 | Chênh lệch do lo ngại về xử lý đơn hàng đồng thời và quy tắc tồn kho phức tạp. Dữ liệu mở khóa đã làm rõ kịch bản tranh chấp tồn kho, nhưng LS03 vẫn liên quan đến nhiều luồng nghiệp vụ phức tạp, xử lý giao dịch và cập nhật tồn kho chính xác, có độ phức tạp và rủi ro cao hơn đáng kể so với LS02. |

## Nhiệm vụ 3 - Phát hiện cách hiểu sai

Đề xuất cố định '1 Story Point = 4 giờ' là sai vì Story Point dùng để đo lường nỗ lực tương đối, độ phức tạp, rủi ro và sự không chắc chắn của một User Story, chứ không phải thời gian tuyệt đối. Việc quy đổi Story Point sang giờ cố định bỏ qua tính tương đối và sự biến động thực tế trong quá trình phát triển phần mềm. Thay vào đó, nhóm sử dụng Velocity (tổng số Story Point hoàn thành trong các Sprint trước đó) để dự báo khả năng hoàn thành công việc trong Sprint tiếp theo, cho phép dự đoán linh hoạt mà không cần chuyển đổi Story Point thành giờ làm việc cụ thể.
