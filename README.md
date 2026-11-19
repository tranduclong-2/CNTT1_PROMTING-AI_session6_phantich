# [Phân tích] So sánh Trade-off các giải pháp ra lệnh cho Ứng dụng AI trong Học tập & Nghiên cứu

### Bước 1: Đề xuất 2 prompt mẫu

```Giải pháp 1: Prompt đơn giản, ngắn gọn
Hãy giải thích Feynman Prompt gia sư và Rubric chấm bài tự động. Trình bày ngắn gọn bằng gạch đầu dòng, sử dụng ngôn ngữ dễ hiểu và đưa ra ví dụ minh họa cho mỗi nội dung.
```

```Giải pháp 2: Prompt chi tiết, có nhiều ràng buộc
Bạn là trợ lý AI hỗ trợ sinh viên học tập và nghiên cứu.

Hãy giải thích và hướng dẫn cách ứng dụng:
1. Feynman Prompt gia sư.
2. Rubric chấm bài tự động.

Yêu cầu:
- Giải thích khái niệm bằng ngôn ngữ đơn giản, phù hợp với sinh viên năm nhất.
- Trình bày từng nội dung theo cấu trúc:
  + Khái niệm.
  + Mục đích sử dụng.
  + Cách áp dụng.
  + Ví dụ thực tế.
- Sử dụng gạch đầu dòng và đánh số rõ ràng.
- Mỗi nội dung không quá 150 từ.
- Không sử dụng thuật ngữ chuyên ngành phức tạp nếu không cần thiết.
- Không tự tạo thông tin sai lệch.
- Không viết lời chào, lời dẫn hoặc lời kết.
- Chỉ trả về nội dung theo đúng cấu trúc yêu cầu.
```

### Bước 2: Lập bảng so sánh Trade-off

| Tiêu chí | Giải pháp 1 (Đơn giản) | Giải pháp 2 (Chi tiết) |
|---|---|---|
| Độ dễ hiểu | Cao | Trung bình |
| Tốn token | Ít | Nhiều hơn |
| Thời gian tạo prompt | Nhanh | Lâu hơn |
| Kiểm soát định dạng | Trung bình | Tốt |
| Độ chi tiết kết quả | Trung bình | Cao |
| Chặn lỗi biên | Trung bình | Tốt |
| Khả năng áp dụng | Linh hoạt | Theo yêu cầu cụ thể |
| Phù hợp | Câu hỏi đơn giản | Bài tập, báo cáo nghiên cứu |

Bước 3: Lựa chọn và chạy thử
1. Lựa chọn phương án
Chọn Giải pháp 2 – Prompt chi tiết.

Lý do:
- Kiểm soát nội dung và định dạng đầu ra tốt hơn.
- Giúp AI trả lời đầy đủ theo từng mục.
- Hạn chế câu trả lời lan man hoặc thiếu ý.
- Phù hợp với việc học tập và làm báo cáo của sinh viên.
Mặc dù tốn nhiều token hơn, nhưng kết quả có cấu trúc rõ ràng và dễ sử dụng.
2. Kết quả chạy thử
1. Feynman Prompt gia sư
- Khái niệm: Phương pháp yêu cầu AI giải thích kiến thức bằng ngôn ngữ đơn giản như đang dạy cho người mới bắt đầu.
- Mục đích: Giúp người học hiểu sâu và phát hiện kiến thức chưa nắm vững.
- Cách áp dụng: Yêu cầu AI giải thích một chủ đề, đưa ra ví dụ và kiểm tra lại mức độ hiểu bài.
- Ví dụ: Yêu cầu AI giải thích khái niệm AI như đang giảng cho học sinh lớp 6.
2. Rubric chấm bài tự động
- Khái niệm: Bảng tiêu chí đánh giá bài làm theo các mức điểm cụ thể.
- Mục đích: Giúp chấm bài có hệ thống và thống nhất hơn.
- Cách áp dụng: Cung cấp bài làm, thang điểm và tiêu chí đánh giá cho AI.
- Ví dụ: Yêu cầu AI chấm bài thuyết trình theo nội dung, hình thức, kỹ năng trình bày và thang điểm 10.
