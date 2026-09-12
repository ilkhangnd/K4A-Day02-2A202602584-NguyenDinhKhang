# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đình Khang
- Mã học viên: 2A202602584
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4, Trường Đại học Công nghệ Thông tin, ĐHQG-HCM; thường xuyên tham gia tổ chức các hoạt động ngoại khoá, có nhiều cuộc họp, đầu việc và checklist cần theo dõi cùng lúc, bên cạnh lịch học, lịch thực hiện các project và deadline cá nhân. 
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    + Theo dõi email, thông báo môn học, lịch họp và các deadline. 
    + Thực hiện đồ án/lab, thường xuyên làm việc với build, train và test code. 
    + Tham gia các buổi họp của tổ chức/nhóm và tổng hợp tiến độ công việc của các bên. 
    + Đọc và xử lý các tài liệu PDF, Docs và các file được chia sẻ.
    + Theo dõi nhiều kênh thông báo/MXH để không bỏ sót các thông tin liên quan (đời sống, chính trị, kinh tế,...).

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại / Tốn thời gian | Phải kiểm tra email thường xuyên để tìm/phân loại thông báo họp/gặp mặt rồi note lại vào lịch cá nhân | Sinh viên tham gia nhiều môn học, CLB/BTC, project và thường xuyên họp; hoặc trưởng nhóm/BTC nếu thành viên bỏ sót lịch hoặc phản hồi chậm. | Microsoft Work Trend Index cho thấy nhóm người dùng email nhiều nhất dành 8,8 giờ/tuần cho email; 62% người được khảo sát nói họ mất quá nhiều thời gian tìm kiếm thông tin. Ở nhóm người dùng Microsoft 365 cường độ cao, lượng trao đổi có thể vượt 250 email và 150 chat/ngày. Nghiên cứu về email đại học cũng ghi nhận sinh viên bị quá tải email, khiến thông tin quan trọng dễ bị “chôn” trong inbox. |
| 2 | Tốn thời gian / AI có thể tốt hơn | Mỗi lần báo cáo project hoặc tiến độ công việc, đòi hỏi phải nhớ lại và tổng hợp các đầu mục công việc đã hoàn thành | Thành viên project/đồ án phải báo cáo; hoặc team leader/PM/mentor cần progress để ra quyết định. | Asana khảo sát 9.615 knowledge workers và cho thấy khoảng 58% ngày làm việc bị dành cho “work about work” như phối hợp, cập nhật và tìm thông tin thay vì công việc chuyên môn. Người được khảo sát ước tính quy trình tốt hơn có thể tiết kiệm khoảng 4,9 giờ/tuần. |
| 3 | Lặp lại | Copy nội dung từ các file PDF sang phần mềm chỉnh sửa khác như Word/Docs rồi chỉnh lại format cho đồng bộ cách thủ công | Sinh viên viết báo cáo, assignment, nghiên cứu; hoặc thành viên khác cùng chỉnh sửa tài liệu nếu format không đồng nhất. | Khảo sát của Adobe cho biết người lao động Mỹ được khảo sát dành trung bình 24 giờ 54 phút/tuần cho các công việc tạo, đọc, chỉnh sửa và tổng hợp tài liệu; 71% cho biết từng cảm thấy quá tải khi xử lý thông tin trong tài liệu. Đây là benchmark rộng về document work, không phải riêng PDF → Word. |
| 4 | Lặp lại / Pain | Sinh viên phải tự kiểm tra deadline mỗi ngày và tính việc nào gần tới hạn | Sinh viên có nhiều môn, project, hoạt động ngoại khóa và deadline song song; hoặc nhóm/project nếu thành viên trễ task làm chậm dependency. | Nghiên cứu đăng trên IEEE Transactions on Learning Technologies thử nghiệm reminder deadline cho sinh viên. Experiment 1 ghi nhận reminder làm tăng tỷ lệ nộp bài khoảng 3,7%; trong experiment lớn hơn, hệ thống liên quan tới mức tăng 5,7% tỷ lệ submission và khoảng 3,36% kết quả môn học. |
| 5 | Lặp lại / Tốn thời gian | Khi thực hiện build/train/test code phải quay lại check terminal nhiều lần để xem code đã chạy xong hay có lỗi gì không | Sinh viên AI/Software, developer, researcher chạy build/train/test hoặc đồng đội đang chờ model/result/artifact. | Nghiên cứu về interruption của Gloria Mark tại UC Irvine thường được dẫn với con số khoảng 23 phút 15 giây để quay trở lại task ban đầu sau một interruption. Việc job monitoring là pain được các công cụ chuyên dụng xử lý: W&B hỗ trợ báo khi run finished/crashed, còn GitHub Actions cho phép notification khi workflow hoàn thành hoặc failed. |
| 6 | Lặp lại | Tải nhiều file rồi thực hiện đổi tên từng file theo format yêu cầu | Sinh viên hoặc thành viên BTC phải quản lý nhiều tài liệu/ảnh/file submission hoặc người tổng hợp file hoặc người nhận nếu naming không chuẩn.| Một nghiên cứu về document management trên 73 knowledge workers chỉ ra các thao tác tạo tên, đổi tên, filing, tìm và xóa file tuy nhỏ lẻ nhưng lặp lại đủ nhiều để cộng thành đáng kể. Một review tổng hợp hơn 230 công trình cũng xác định downloading, moving, naming và organizing file là hoạt động quản lý file phổ biến hằng ngày. |
| 7 | Pain / Lặp lại | Khi môn hết slot phải thường xuyên vào hệ thống để kiểm tra xem có người huỷ môn hoặc mở thêm slot để đăng ký | Sinh viên cần đăng ký môn bắt buộc/môn đúng tiến độ hoặc cố vấn học tập/phòng đào tạo khi sinh viên không thể xây lịch học phù hợp. | Đây là problem có external evidence rất mạnh: UCLA dẫn khảo sát của Instructure cho biết 85% sinh viên báo cáo gặp khó khăn khi đăng ký các môn cần thiết; gần 3/4 cho rằng thiếu chỗ học làm tăng khả năng họ phải học thêm học kỳ. Vanderbilt thậm chí vận hành waitlist tự động 8 lần/ngày, mỗi 3 giờ để xử lý slot mới mở. |
| 8 | Tốn thời gian / AI có thể làm tốt hơn | Sau khi họp xong phải tự viết biên bản, tổng hợp các kết luận trong cuộc họp thủ công | Thư ký/người được giao ghi biên bản hoặc toàn bộ thành viên cuộc họp, trưởng nhóm/BTC và người vắng họp cần decision/action item. | Microsoft thử nghiệm với 60 nhân viên phải tóm tắt một cuộc họp ghi hình 35 phút. Nhóm dùng Copilot hoàn thành trung bình 11 phút 13 giây, so với 42 phút 34 giây ở nhóm không dùng — nhanh gần 3,8 lần. Tuy nhiên độ đầy đủ giảm nhẹ: 11/15 chi tiết so với 12/15, nên vẫn cần human review. Microsoft cũng mô tả meeting recap có thể trích key points và action items nhưng khuyến cáo phải xác minh output AI. |

> Gợi ý tự soi: Tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Dựa vào các “Problem” mà tôi đã quan sát được trong quá trình học tập, làm project và tham gia hoạt động ngoại khóa, hãy giúp tôi phân tích từng problem theo các lăng kính: mức độ lặp lại, mức độ tốn thời gian, khả năng AI có thể hỗ trợ tốt hơn và pain đối với người dùng. Đồng thời xác định đối tượng chịu ảnh hưởng, đưa ra cách đo bằng số liệu thực tế từ các bài báo/nghiên cứu trên Internet có liên quan đến problem đó. 
- Ý dùng được: AI giúp biến các quan sát rời rạc thành actor, workflow, bottleneck và cách đo. Các gợi ý về biên kiểm soát như notification cho job hoặc human review cho biên bản họp giúp tôi tách phần có thể tự động hóa khỏi phần cần người xác nhận.
- Ý bỏ vì không phải pain thật: các gợi ý quá rộng như một trợ lý quản lý toàn bộ lịch, task và email không phù hợp với một pain cụ thể. Với việc theo dõi build/train/test, tôi cũng không chọn “AI agent” vì notification/rule là phương án đơn giản hơn cho nhu cầu chính.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|----|---|---|---|
| 1 | Sau khi họp xong phải tự viết biên bản, tổng hợp các kết luận trong cuộc họp thủ công | Đây là việc xảy ra khá thường xuyên, tốn nhiều công sức sau mỗi cuộc họp và dễ phát sinh sai sót hoặc bỏ sót ý quan trọng. Đồng thời đây là một pain đủ rõ để thử xem AI có thật sự giúp giảm tải công việc thủ công hay không. | AI có đủ chính xác để xác định đúng kết luận, action item, owner và deadline không? |
| 2 | Phải kiểm tra email thường xuyên để tìm/phân loại thông báo họp/gặp mặt rồi note lại vào lịch cá nhân | Đây là một công việc lặp lại nhiều, dễ gây bỏ sót lịch và tạo thêm thao tác thủ công không cần thiết. Problem này cũng xuất hiện trong nhiều bối cảnh khác nhau như học tập, project và hoạt động ngoại khóa.| Có cần AI thật sự không, hay chỉ cần rule/filter và Calendar automation là đủ? |
| 3 | Khi build/train/test code phải quay lại check terminal nhiều lần để xem code đã chạy xong hay có lỗi gì không | Đây là một việc gây gián đoạn khi đang làm công việc khác, đặc biệt với các job chạy lâu. Nó cũng là một problem thú vị để kiểm tra xem đâu là phần nên tự động hóa và đâu là phần AI có thể tạo thêm giá trị. | Có thể chỉ cần notification/script là đủ; chưa rõ AI sẽ giúp tốt hơn ở phần nào ngoài việc đọc và giải thích log. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Viết biên bản cuộc họp thủ công

```text
Problem 1 câu: Sau khi họp xong, người phụ trách phải tự xem lại nội dung và tổng hợp các kết luận, quyết định và đầu việc thành biên bản cuộc họp.

Actor: Thư ký/người được giao ghi biên bản; các thành viên, trưởng nhóm/BTC và người vắng họp cần nắm lại decision/action item.

Thời điểm / bối cảnh: Sau các buổi họp nhóm project, đồ án hoặc hoạt động ngoại khóa.

Current workflow:
1. Tham gia cuộc họp và ghi chú.
2. Sau họp xem lại note/chat/recording.
3. Tổng hợp các nội dung chính.
4. Xác định kết luận, action item, owner và deadline.
5. Format biên bản và gửi cho các thành viên.

Bottleneck: Phải đọc/xem lại nội dung cuộc họp và tự xác định đâu là thông tin quan trọng, kết luận và action item.

Impact: 
- Microsoft thử nghiệm trên 60 nhân viên với một cuộc họp ghi hình dài 35 phút. 
- Nhóm không dùng Copilot mất trung bình 42 phút 34 giây để hoàn thành bản tóm tắt, trong khi nhóm dùng Copilot chỉ mất 11 phút 13 giây, nhanh khoảng 3,8 lần.
- Tuy nhiên, nhóm dùng AI ghi nhận trung bình 11/15 chi tiết,
so với 12/15 ở nhóm không dùng AI, cho thấy vẫn cần bước human review.

Success metric:
- Giảm đáng kể thời gian xử lý sau cuộc họp.
- Có thể lấy benchmark nghiên cứu là từ ~42 phút xuống khoảng 11 phút cho tác vụ tương tự.
- Không bỏ sót các quyết định/action item quan trọng.
- Bản AI draft phải được người dùng review trước khi gửi.

Non-AI alternative:
- Dùng template biên bản cố định.
- Chỉ định thư ký.
- Chốt action items trong 5 phút cuối meeting.
- Mỗi thành viên tự xác nhận task của mình.

AI hypothesis: AI có thể xử lý transcript/ghi chú để tạo bản tóm tắt, trích xuất decisions, action items, owner và deadline, sau đó để con người review trước khi phát hành.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE

[1 Tham gia meeting + note]
        ↓
[2 Xem lại note/recording]
        ↓
[3 Tổng hợp nội dung]  <-- bottleneck
        ↓
[4 Xác định decisions/action items]
        ↓
[5 Format + gửi]

Benchmark: Microsoft: 42 phút 34 giây để tóm tắt meeting 35 phút khi không có Copilot.

FUTURE STATE

[1 Meeting → transcript]
        ↓
[2 AI summarize + extract decisions/action items]
        ↓
[3 Human review]  <-- human boundary
        ↓
[4 Confirm + gửi]

Benchmark: Microsoft: 11 phút 13 giây với Copilot cho cùng tác vụ.

Fallback: Nếu AI không chắc owner/deadline hoặc bỏ sót nội dung hiển thị transcript gốc và yêu cầu người dùng xác nhận.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Check email và note lịch vào calendar

```text
Problem 1 câu: Người dùng phải thường xuyên kiểm tra email để tìm và phân loại các thông báo họp/gặp mặt, sau đó tự note lại vào Calendar cá nhân.

Actor: Sinh viên tham gia nhiều môn học, CLB/BTC, project và thường xuyên họp; Trưởng nhóm/BTC cũng bị ảnh hưởng nếu thành viên bỏ sót lịch.

Thời điểm / bối cảnh: Trong ngày khi nhận email từ giảng viên, nhóm project, CLB/BTC hoặc các bên liên quan.

Current workflow:
1. Mở inbox và kiểm tra email mới.
2. Đọc/phân loại từng email.
3. Xác định email nào chứa lịch họp/gặp mặt.
4. Trích xuất ngày, giờ, địa điểm/link.
5. Mở Calendar và nhập lại event.
6. Kiểm tra lịch trùng.

Bottleneck: Phải đọc email thủ công để xác định email nào liên quan đến lịch và lấy chính xác thông tin sự kiện.

Impact: Microsoft Work Trend Index cho thấy:
- Nhóm 25% người dùng email nhiều nhất dành khoảng 8,8 giờ/tuần cho email.
- 62% người được khảo sát cho biết họ dành quá nhiều thời gian
  tìm kiếm thông tin trong ngày làm việc.
- Với nhóm người dùng Microsoft 365 cường độ cao,
  lượng trao đổi có thể vượt 250 email và gần 150 chat/ngày.

Các số liệu này cho thấy khối lượng communication lớn làm tăng chi phí tìm và xử lý thông tin quan trọng.

Success metric:
- Giảm số email người dùng phải tự kiểm tra để tìm lịch.
- Phát hiện đúng ≥90% email chứa lịch/sự kiện.
- Giảm số thao tác thủ công từ email → Calendar.
- Không tự tạo Calendar event khi ngày/giờ chưa chắc chắn.

Non-AI alternative:
- Email filter/label.
- Rule dựa trên keyword như "họp", "meeting", "schedule".
- Người gửi sử dụng Calendar invitation hoặc file .ics.

AI hypothesis: AI phân loại email có chứa sự kiện, trích xuất title/date/time/location, sau đó tạo một draft event để người dùng xác nhận.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE

[1 Check inbox]
      ↓
[2 Đọc/phân loại email]  <-- bottleneck
      ↓
[3 Tìm ngày/giờ/địa điểm]
      ↓
[4 Mở Calendar]
      ↓
[5 Tạo event + kiểm tra]

External evidence: Top 25% heavy email users: 8,8 giờ/tuần cho email. 62% cho rằng họ mất quá nhiều thời gian tìm kiếm thông tin.

FUTURE STATE

[1 Email mới]
      ↓
[2 AI classify event/non-event + extract information]
      ↓
[3 Tạo draft Calendar event]
      ↓
[4 User review/confirm]  <-- human boundary
      ↓
[5 Add Calendar]

Fallback: Email có thông tin mơ hồ hoặc AI confidence thấp → không tự tạo event, yêu cầu người dùng xác nhận.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Theo dõi build/train/test

```text
Problem 1 câu: Khi chạy build/train/test dài, người dùng phải quay lại terminal nhiều lần để kiểm tra job đã hoàn thành hoặc gặp lỗi chưa.

Actor: Sinh viên AI/Software, developer hoặc researcher chạy các job dài; đồng đội cũng có thể bị ảnh hưởng nếu đang chờ model/result/artifact.

Thời điểm / bối cảnh: Khi training model, chạy experiment, build hoặc test project.

Current workflow:
1. Start build/train/test.
2. Chuyển sang làm công việc khác.
3. Sau một khoảng thời gian quay lại terminal.
4. Đọc log và kiểm tra trạng thái.
5. Nếu chưa xong thì tiếp tục chờ và kiểm tra lại.
6. Nếu lỗi thì đọc log để tìm nguyên nhân.

Bottleneck: Polling thủ công khiến người dùng phải liên tục chuyển giữa công việc đang làm và terminal.

Impact: 
- Nghiên cứu về interruption của Gloria Mark tại UC Irvine được dẫn lại với con số trung bình khoảng 23 phút 15 giây để một người quay lại task ban đầu sau khi bị gián đoạn.
- Do đó, việc liên tục rời công việc đang làm để check terminal có thể gây chi phí context switching lớn hơn chính thời gian check.
- Ngoài ra, việc các công cụ như W&B và GitHub Actions đã hỗ trợ notification khi run/workflow finished hoặc failed cho thấy đây là một workflow có nhu cầu monitoring thực tế.

Success metric:
- Giảm số lần người dùng phải chủ động quay lại terminal.
- Notification ngay khi job finished/failed.
- Giảm context switching không cần thiết.
- Đối với error, chỉ sử dụng AI để hỗ trợ summarize/explain log.

Non-AI alternative:
- Shell notification.
- Telegram/email webhook.
- CI/CD notification.
- W&B alert.
- Monitoring script.

AI hypothesis: Không cần AI để xác định job đã done/error. Rule-based monitoring có thể giải quyết phần này.

AI chỉ nên được thêm vào bước sau: Khi job lỗi → AI đọc log → tóm tắt lỗi → gợi ý hướng debug.

Quick gut:
[ ] No AI / process fix
[x] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE

[1 Start job]
      ↓
[2 Làm task khác]
      ↓
[3 Quay lại terminal]  <-- bottleneck / interruption
      ↓
[4 Check log]
      ↓
   chưa xong
      ↓
[Quay lại task khác rồi tiếp tục check]

External evidence: Sau một interruption, thời gian để quay lại task ban đầu có thể khoảng 23 phút 15 giây.


FUTURE STATE

[1 Start job]
      ↓
[2 Monitor tự động]
      ↓
   Running → không làm gì
      ↓
 Done/Error → Notification
      ↓
[3 User review]  <-- human boundary
      ↓
Nếu error → AI summarize/explain log

Fallback: Nếu monitoring service lỗi, user vẫn truy cập trực tiếp terminal/log như hiện tại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```
Problem Card #2 — Check email và note lịch vào Calendar
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```
Hiện tại, khi nhận email mới tôi phải tự đọc và phân loại xem email nào có chứa thông tin về lịch họp/gặp mặt, sau đó trích xuất ngày giờ, địa điểm và nhập lại thủ công vào Calendar. Bottleneck nằm ở bước đọc, xác định email nào thực sự liên quan đến lịch và lấy đúng thông tin sự kiện.

Đây là một workflow xảy ra thường xuyên trong bối cảnh tôi vừa học nhiều môn, tham gia project và các hoạt động ngoại khóa. Nếu bỏ sót một email quan trọng, impact không chỉ là mất thời gian mà còn có thể dẫn đến quên hoặc trễ lịch họp, vì vậy tôi muốn kiểm tra liệu AI có thể giảm thao tác thủ công nhưng vẫn giữ
người dùng ở bước xác nhận cuối cùng hay không.

Microsoft Work Trend Index cho thấy nhóm 25% người dùng email nhiều nhất có thể dành khoảng 8,8 giờ mỗi tuần cho email, và 62% người được khảo sát cho rằng họ mất quá nhiều thời gian để tìm kiếm thông tin. Điều này cho thấy việc tìm và xử lý thông tin quan trọng giữa lượng communication lớn là một pain có thật.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```
1. Với problem này, AI có thực sự cần thiết hay chỉ cần email filter, keyword rule và Calendar automation là đã giải quyết được phần lớn pain?

2. Nếu AI hiểu sai ngày giờ hoặc nhận nhầm một email bình thường thành sự kiện, human boundary nên đặt ở đâu để vẫn tiết kiệm thời gian mà không tạo lịch sai?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: card dễ bị solution-first; phần lớn email có cấu trúc có thể xử lý bằng rule/filter, còn lỗi ngày giờ hoặc email mơ hồ có hậu quả trực tiếp lên lịch.
- Tôi sửa gì: hạ phạm vi xuống phân loại và tạo **draft** event; chỉ dùng AI cho trường hợp khó, không tạo event tự động khi thông tin thiếu hoặc confidence thấp.

### Self-check nộp phần 01
- [X] Có 5+ problems + top 3 Cards đủ field
- [X] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [X] Đã chọn 1 card pitch + câu hỏi challenge

### Links kiểm chứng cho các benchmark chính

- [Microsoft Work Trend Index 2023](https://info.microsoft.com/rs/157-GQE-382/images/SREVM16705-CNTNT.pdf) — nguồn cho 8,8 giờ/tuần của nhóm dùng email nhiều nhất và 62% người khảo sát gặp khó khăn vì tốn thời gian tìm thông tin.
- [Asana Anatomy of Work Global Index 2023](https://investors.asana.com/news-releases/news-release-details/asana-anatomy-work-global-index-2023-smart-collaboration-and/) — nguồn cho khảo sát 9.615 knowledge workers, 58% thời gian “work about work” và ước lượng 4,9 giờ/tuần có thể tiết kiệm nhờ cải thiện quy trình.
- [Microsoft WorkLab: nghiên cứu tóm tắt cuộc họp](https://www.microsoft.com/en-us/worklab/work-trend-index/copilots-earliest-users-teach-us-about-generative-ai-at-work) — nguồn cho thử nghiệm 60 nhân viên, 35 phút recording và kết quả 11 phút 13 giây so với 42 phút 34 giây; đồng thời cho thấy độ đầy đủ giảm nhẹ, nên không bỏ bước review.
