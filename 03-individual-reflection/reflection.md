# 03 — Individual Reflection — Nguyễn Minh Phúc

## Đóng góp của Phúc trong nhóm

| Hoạt động               | Phúc đã làm gì?                                             | Kết quả                                                               |
| ----------------------- | ----------------------------------------------------------- | --------------------------------------------------------------------- |
| Scan cá nhân            | Đưa ra 10 problems                                          | Nhóm có nguồn candidate rộng về workflow/automation                   |
| Pitch                   | Pitch bài Lên lịch trình du lịch cá nhân                    | Bài được đưa vào shortlist                                            |
| Challenge               | Hỏi nhóm dữ liệu phòng trọ có verify được không             | Nhóm loại bớt bài phòng trọ vì rủi ro data freshness                  |
| Workflow                | Đóng góp thiết kế bước Human Review trong Future Workflow   | Nhóm có boundary kiểm soát 100% claim xuất ra từ Master CV            |
| Research                | Phân tích Teal Resume Builder và Kickresume AI              | Nhóm rút ra bài học về evidence mapping thay vì chạy theo match score |
| Rule / Workflow / Agent | Lập luận chọn Workflow, phản biện việc dùng Agent tự nộp CV | Nhóm thống nhất decision và boundary                                  |

## Bảng dùng AI trong reflection

| Phase             | Tôi dùng AI để làm gì?                      | AI hữu ích ở đâu?                                        | AI sai/hời hợt ở đâu?                           | Tôi sửa gì                                                |
| ----------------- | ------------------------------------------- | -------------------------------------------------------- | ----------------------------------------------- | --------------------------------------------------------- |
| Scan              | Gợi ý thêm problems theo role BA            | Mở rộng góc nhìn về đọc PRD và quản lý chi tiêu          | Gợi ý vài ý quá rộng kiểu trợ lý toàn năng      | Bỏ các ý không có workflow và baseline rõ                 |
| Workflow          | Nhờ AI phản biện rủi ro của future workflow | Chỉ ra rủi ro hallucination khi viết CV                  | Đề xuất tự động nộp hồ sơ không cần duyệt       | Bắt buộc thêm bước Human Approval trước khi xuất file     |
| Research          | Tìm tool tương tự về CV tailoring           | Gợi ý Teal, Kickresume, Europass                         | Đưa ra các claim tăng 80% đậu CV không có nguồn | Chỉ giữ bài học về workflow pattern, bỏ số liệu marketing |
| Problem Statement | Nhờ AI phản biện field mơ hồ                | Chỉ ra metric "tỷ lệ đậu phỏng vấn" bị xa điểm can thiệp | AI đề xuất chuyển sang Agent quá sớm            | Nhóm sửa metric về thời gian và hạ về Workflow            |

## Bài học của Phúc

- Problem tốt không phải problem nghe "AI" nhất, mà là problem có workflow, bottleneck và metric đo được trong thực tế.
- Vẽ workflow giúp thấy bước nào dùng Rule đủ (parse/validate), bước nào AI hữu ích (semantic match & draft), bước nào con người phải giữ (review).
- Agent không phải đích đến mặc định. Với CV/Cover Letter, Workflow + Human-in-the-loop phù hợp hơn vì tránh rủi ro hallucination không thể thu hồi.
- Research không phải để copy tool, mà để thấy pattern: AI hỗ trợ draft và map evidence, người thật kiểm tra và quyết định bản cuối.

Nếu làm lại:

```text
Tôi sẽ tự bấm giờ workflow điều chỉnh CV của mình cho 3 JD khác nhau ngay ở Phase 1 để có baseline timer log chính xác, thay vì chỉ dựa vào ước lượng 20 phút/hồ sơ của problem owner.
```
