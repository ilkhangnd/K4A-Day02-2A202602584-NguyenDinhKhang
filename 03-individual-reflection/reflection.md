# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đình Khang
- Mã học viên: 2A202602584
- Nhóm: Nhóm 5 người
- Candidate problem nhóm chọn: Phát hiện và hỗ trợ sửa ID switch trong video multi-object tracking.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 8 vấn đề từ lịch học, email, họp, tài liệu và việc chạy code; chọn 3 card về biên bản họp, email-to-calendar và theo dõi build/train/test. | Nhóm có thêm một cụm candidate về quản lý thông tin; các card cho thấy không phải vấn đề nào cũng cần AI. |
| Pitch Problem Card | Pitch card email-to-calendar, nêu rõ bước đọc/trích xuất email là bottleneck và đề xuất chỉ tạo draft event. | Đưa vào thảo luận câu hỏi: rule/filter có đủ không và user nên xác nhận ở đâu để tránh lịch sai. |
| Challenge bài của bạn khác | Hỏi nhóm phải phân biệt bước nào rule xử lý được với bước nào thật sự cần AI; đặc biệt chú ý rủi ro AI tự kết luận hoặc tự sửa. | Thảo luận chuyển từ “làm Agent” sang so sánh baseline Rule, Workflow và Agent trên cùng một candidate. |
| Gom trùng / cluster | Góp phần đọc các candidate theo actor, workflow và bottleneck thay vì theo độ “hay” của ý tưởng. | Nhóm thấy rõ cụm Dataset và tracking QA có pain hẹp, đo được và có data pilot. |
| Chọn candidate problem | Đồng thuận chọn ID switch detection vì bottleneck là tìm đoạn lỗi, không phải thao tác đổi ID. | Scope được thu hẹp thành flag/xếp hạng candidate để người kiểm tra, thay vì tự sửa toàn bộ annotation. |
| Validation / research | Rà link survey MOT, ByteTrack, CLIP-ReID, Ultralytics và TrackEval; phân biệt evidence về thách thức MOT với evidence về ROI của nhóm. | Bổ sung research có link kiểm được và giữ quyết định Not Yet vì vẫn thiếu survey/interview độc lập, bấm giờ baseline và ground truth. |
| Workflow nhóm | Cùng dựng workflow trước/sau, chỉ ra bước xem tuần tự và tua lại là bottleneck; nêu fallback khi model lỗi hoặc confidence thấp. | Human review là boundary trước bước sửa ID, file annotation gốc được giữ để rollback. |
| Problem Statement | Góp phần làm rõ actor, intervention point, metric thời gian/recall/precision và phần không làm. | Problem Statement v1 tránh hứa “AI phát hiện và sửa” trên toàn bộ dataset. |
| Rule / Workflow / Agent | So sánh rule tạo candidate với workflow có ReID scoring và Agent tự hành động. | Chọn Workflow có đường đi cố định; Agent không phù hợp vì khó audit và vượt boundary. |
| Decision | Ủng hộ Not Yet thay vì Go ngay. | Nhóm có điều kiện rõ để chuyển Go: ground truth review chéo, benchmark rule-only và cải thiện đo được. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Phần tôi để lại rõ nhất là cách mô tả workflow trước/sau và human boundary: máy chỉ tạo, chấm điểm và xếp hạng candidate; người mới xác nhận và sửa ID. Tôi cũng giúp giữ các số ~50 phút và mục tiêu 15 phút ở trạng thái giả thuyết cần bấm giờ, không biến chúng thành kết luận.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý cách phân loại các problem theo lặp lại, thời gian, AI-fit và actor. | Giúp biến quan sát thành các câu hỏi đo được. | Có thể đề xuất pain quá rộng hoặc không thuộc trải nghiệm thật của tôi. | Giữ lại 8 pain tôi đã quan sát; bỏ ý trợ lý “toàn năng”. |
| Problem Card | Phản biện bottleneck, metric và phương án non-AI. | Nhắc đặt human review cho email và biên bản. | Dễ làm card trông như AI cần thiết ở mọi chỗ. | Với terminal, tôi chọn notification/rule làm đáp án chính. |
| Workflow | Gợi ý cách diễn đạt flow trước/sau. | Giúp nhìn thấy handoff và fallback. | Không biết thời gian thực tế trong dự án. | Chỉ giữ thời gian là ước lượng và yêu cầu bấm giờ trong pilot. |
| Research | Tìm survey/paper và tài liệu công cụ để tạo danh sách nguồn ban đầu. | Giúp nhanh chóng thấy pattern về occlusion, association và ID switch. | Có thể lẫn benchmark người/xe với domain lợn. | Chỉ dùng link kiểm được; ghi rõ giới hạn transfer và không suy diễn ROI. |
| Problem Statement | Chỉ ra các field còn mơ hồ như ground truth và định nghĩa ID switch. | Buộc mô tả intervention point và boundary cụ thể hơn. | Không thể thay nhóm quyết định threshold nào phù hợp. | Thêm precision, recall, IDSW, spot-check và human-approved correction. |
| Rule / Workflow / Agent | Lập bảng so sánh các mức tự động hóa. | Làm rõ Agent không mặc định tốt hơn Workflow. | Có xu hướng chọn phương án phức tạp nếu prompt không giới hạn scope. | Chọn workflow cố định và chỉ cân nhắc AI sau baseline rule. |
| Decision | Không dùng AI để chốt. | Tôi dùng AI như nguồn câu hỏi phản biện, không phải người ra quyết định. | AI không có dữ liệu pilot hoặc quyền chịu trách nhiệm với dữ liệu. | Giữ quyết định Not Yet và nêu điều kiện đo được trước khi Go. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe các bạn pitch, tôi nhận ra một ý tưởng có vẻ “AI” chưa chắc là bài tốt hơn một workflow đơn giản. Card theo dõi build/train/test của tôi là ví dụ rõ nhất: notification và script xử lý phần lớn pain, nên thêm Agent chỉ làm tăng phạm vi mà không giải đúng bottleneck. Với bài ID switch, tôi học được rằng thao tác sửa ID không phải chỗ khó nhất; phần đắt nhất là tìm đúng frame hoặc đoạn bắt đầu lỗi giữa rất nhiều frame bình thường. Điều này khiến tôi thay đổi cách mô tả solution từ “AI phát hiện và sửa ID switch” thành “workflow xếp hạng đoạn nghi vấn để người review”. Điều khó nhất khi viết Problem Statement là không lấy con số self-report 50 phút làm baseline đã được chứng minh. Vì vậy, tôi đồng ý giữ quyết định Not Yet dù bài toán có vẻ phù hợp với AI, vì nhóm chưa có ground truth review chéo và chưa bấm giờ đủ video. Tôi đóng góp nhiều nhất ở workflow trước/sau, nơi tôi giữ human review ngay trước bước sửa và thêm fallback quay về rule-only hoặc review thủ công. AI hữu ích khi gợi ý cấu trúc, nguồn tham khảo và điểm mơ hồ, nhưng nó không biết video lợn của nhóm có giống benchmark hay không. Nếu làm lại, tôi sẽ challenge sớm hơn về định nghĩa một ID switch “đúng”, số video pilot và ai là người gán nhãn chéo. Tôi cũng sẽ đề nghị làm một mini-survey hoặc hai cuộc phỏng vấn có lưu quote trước khi chấm điểm candidate để evidence pain không chỉ dựa vào một data owner.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
