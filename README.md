1. Phân tích lỗi

Prompt cũ chỉ yêu cầu “ngắn gọn”, chưa quy định số ý, độ dài và nội dung bị cấm. Ba phần văn bản thừa cần loại bỏ (ví dụ minh họa do đề chưa cung cấp câu trả lời cũ):

- Lời chào: “Xin chào bạn! Mình rất vui được hỗ trợ bạn.” Không cung cấp kiến thức được hỏi.

- Lời dẫn: “Trước khi tìm hiểu, chúng ta cần biết đây là những kỹ thuật rất hữu ích.” Dài dòng, chưa đi vào nội dung chính.

- Lời kết: “Hy vọng câu trả lời hữu ích. Nếu cần thêm thông tin, hãy hỏi mình nhé!” Không phục vụ yêu cầu giải thích.

2. Prompt đã sửa

Giải thích ngắn gọn ba nội dung: Chain-of-Thought, Prompt Chaining và xử lý đứt gãy câu trả lời bằng Continue Prompting.

Bắt buộc tuân thủ:

- Chỉ trả về đúng 3 gạch đầu dòng, mỗi dòng bắt đầu bằng dấu “- ”.

- Mỗi gạch đầu dòng giải thích một nội dung theo đúng thứ tự trên, gồm tên kỹ thuật và một câu không quá 40 từ.

- Dùng ngôn ngữ đơn giản, phù hợp với sinh viên năm nhất CNTT.

- Không viết lời chào hoặc lời dẫn ở đầu; không thêm tiêu đề, lời kết, lời mời hỏi tiếp hay ví dụ.

- Không có văn bản ngoài 3 gạch đầu dòng.

3. Kết quả phản hồi mẫu của AI

- Chain-of-Thought: Hướng dẫn AI chia bài toán thành các bước trung gian trước khi đưa ra đáp án.

- Prompt Chaining: Chia nhiệm vụ thành chuỗi prompt, dùng kết quả của bước trước làm đầu vào cho bước sau.

- Continue Prompting: Yêu cầu AI tiếp tục từ điểm bị ngắt, cung cấp đoạn cuối và nhắc lại ràng buộc để tránh lặp hoặc lệch nội dung.
