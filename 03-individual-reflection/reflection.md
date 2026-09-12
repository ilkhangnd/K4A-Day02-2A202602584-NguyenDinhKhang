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
| Scan cá nhân | Mình ghi lại 8 vấn đề mình hay gặp khi học, họp, xử lý email, tài liệu và chạy code; sau đó chọn 3 bài đủ cụ thể để kể với nhóm. | Nhóm có thêm một góc nhìn về quản lý thông tin và thấy rõ: có bài chỉ cần quy trình hoặc rule là đủ. |
| Pitch Problem Card | Mình pitch bài email-to-calendar, tập trung vào lúc phải đọc email rồi tự nhặt ngày giờ để nhập lịch. | Câu hỏi “rule/filter đã đủ chưa?” khiến nhóm nói kỹ hơn về bước người dùng cần xác nhận để không tạo lịch sai. |
| Challenge bài của bạn khác | Mình hỏi từng bước nào thật sự cần AI, bước nào có thể làm bằng rule trước; cũng nhắc đến rủi ro nếu hệ thống tự kết luận hoặc tự sửa. | Nhóm bớt nhìn Agent như lựa chọn mặc định và bắt đầu so sánh Rule, Workflow, Agent trên cùng một bài. |
| Gom trùng / cluster | Mình cùng nhóm đọc các ý theo người gặp vấn đề, quy trình và điểm nghẽn, thay vì chỉ chọn ý nghe hấp dẫn. | Nhờ vậy, cụm dataset và tracking QA nổi lên vì scope hẹp, dễ đo và có dữ liệu để thử. |
| Chọn candidate problem | Mình đồng ý chọn ID switch vì phần mệt nhất là tìm đoạn lỗi chứ không phải thao tác đổi ID. | Nhóm thu hẹp solution thành việc đánh dấu và xếp hạng đoạn nghi vấn cho người xem, không tự sửa toàn bộ annotation. |
| Validation / research | Mình rà các link survey MOT, ByteTrack, CLIP-ReID, Ultralytics và TrackEval. | Research giúp nhóm có nền tảng, nhưng cũng nhắc cả nhóm rằng vẫn thiếu bấm giờ thực tế, ground truth và ý kiến độc lập. |
| Workflow nhóm | Mình góp phần phác workflow trước/sau, chỉ ra chỗ phải xem tuần tự rồi tua lại nhiều lần. | Bước review của người được đặt ngay trước khi sửa, và vẫn có đường quay về rule-only hoặc review tay nếu model không ổn. |
| Problem Statement | Mình cùng nhóm làm rõ ai dùng, AI xuất hiện ở bước nào, cần đo gì và không được làm gì. | Bản v1 không còn hứa chung chung rằng “AI sẽ phát hiện và sửa” trên cả dataset. |
| Rule / Workflow / Agent | Mình so sánh rule tạo candidate với workflow có ReID scoring và một Agent có quyền tự hành động. | Nhóm chọn workflow cố định vì dễ kiểm tra hơn và không vượt quá phạm vi pilot. |
| Decision | Mình ủng hộ giữ kết luận Not Yet thay vì vội Go. | Nhóm có điều kiện cụ thể để đi tiếp: ground truth review chéo, benchmark rule-only và kết quả cải thiện có thể đo. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Phần mình để lại rõ nhất là workflow trước/sau và ranh giới của AI: máy chỉ tạo, chấm điểm, xếp hạng candidate; người vẫn là người xác nhận và sửa ID. Mình cũng giữ con số khoảng 50 phút và mục tiêu 15 phút ở dạng giả thuyết cần bấm giờ, thay vì viết như thể nhóm đã chứng minh xong.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý cách nhìn problem theo mức lặp lại, thời gian mất và người bị ảnh hưởng. | Giúp mình chuyển quan sát hằng ngày thành câu hỏi có thể đo. | Có lúc AI gợi ý pain quá rộng, không đúng với trải nghiệm của mình. | Mình chỉ giữ 8 vấn đề đã quan sát; bỏ ý tưởng trợ lý “làm hết mọi thứ”. |
| Problem Card | Gợi ý các câu hỏi về bottleneck, metric và phương án không dùng AI. | Nhắc mình đặt bước người review cho email và biên bản. | Dễ khiến card nào cũng trông như phải có AI. | Với terminal, mình chọn notification/rule là giải pháp chính. |
| Workflow | Hỗ trợ diễn đạt flow trước và sau rõ hơn. | Làm lộ ra handoff, fallback và chỗ cần người kiểm tra. | Không thể biết chính xác nhóm mất bao lâu trên dự án thật. | Mình giữ các con số là ước lượng và yêu cầu phải bấm giờ ở pilot. |
| Research | Tìm survey, paper và tài liệu công cụ để có danh sách nguồn ban đầu. | Giúp thấy nhanh mối liên hệ giữa occlusion, association và ID switch. | Có nguy cơ lẫn benchmark người/xe với video lợn của nhóm. | Mình chỉ dùng link kiểm được và ghi rõ giới hạn khi áp dụng sang domain khác. |
| Problem Statement | Chỉ ra các chỗ còn mơ hồ như ground truth và định nghĩa ID switch. | Ép nhóm nói rõ AI can thiệp ở đâu và không được làm gì. | Không thể tự đặt threshold thay cho nhóm. | Nhóm thêm precision, recall, IDSW, spot-check và human-approved correction. |
| Rule / Workflow / Agent | Gợi ý khung so sánh ba mức tự động hóa. | Làm rõ Agent không tự nhiên tốt hơn Workflow. | Nếu không giới hạn scope, AI thường nghiêng về phương án phức tạp. | Mình chọn workflow cố định và chỉ cân nhắc AI sau baseline rule. |
| Decision | Không dùng AI để chốt quyết định. | Mình chỉ dùng AI như người hỏi ngược, không phải người ra quyết định. | AI không có dữ liệu pilot và cũng không chịu trách nhiệm với dữ liệu đó. | Mình giữ Not Yet, kèm những điều kiện có thể đo trước khi Go. |

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
Lúc nghe các bạn pitch, mình mới thấy một ý tưởng nghe rất “AI” chưa chắc đã là bài đáng làm nhất. Bài theo dõi build/train/test của mình là ví dụ rõ nhất: một notification hoặc script đã xử lý phần lớn việc phải quay lại check terminal, nên thêm Agent chỉ làm bài toán phình to. Với bài ID switch, mình cũng hiểu ra thao tác đổi ID không phải phần tốn sức nhất. Cái mất thời gian là phải ngồi lướt qua rất nhiều frame bình thường để tìm đúng đoạn lỗi bắt đầu, nhất là lúc các con vật đi sát nhau hoặc bị che khuất. Từ đó, mình đổi cách nói về solution: không phải “AI phát hiện và sửa ID switch”, mà là “hệ thống gợi ý những đoạn đáng xem để người kiểm tra nhanh hơn”. Phần khó nhất khi viết Problem Statement là kiềm lại trước một con số nghe có vẻ thuyết phục, như 50 phút cho một vòng QA. Đó mới chỉ là self-report, nên chưa thể xem như baseline đã được chứng minh. Vì vậy, mình đồng ý giữ quyết định Not Yet dù hướng này khá hợp với AI. Phần mình đóng góp nhiều nhất là workflow trước/sau và điểm chặn human review ngay trước khi sửa, để vẫn có thể quay về rule-only hoặc review thủ công nếu model gợi ý sai. AI giúp mình tìm nguồn, gợi ý cách đặt câu hỏi và chỉ ra chỗ mơ hồ, nhưng nó không biết video lợn của nhóm có giống benchmark hay không. Nếu làm lại, mình sẽ hỏi sớm hơn về định nghĩa một ID switch “đúng”, số video pilot và người nào sẽ review chéo nhãn; đồng thời làm một mini-survey hoặc vài cuộc phỏng vấn có lưu quote ngay từ đầu.
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
