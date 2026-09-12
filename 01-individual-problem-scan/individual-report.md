# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thị Phương Duyên
- Mã học viên: 2A202603001
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên AI thực chiến khóa IV, sinh viên mới tốt nghiệp ngành công nghệ kỹ thuật máy tính, sale engineer, gia sư online,...
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    - Học tập ở Vin Uni
    - Check email và đồng bộ time line
    - Tìm kiếm, tổng hợp và phân tích SWOT khách hàng
    - Tìm, tham khảo, đọc và soạn thảo giáo án dạy học
---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Lặp lại | Mỗi tuần phải check nhiều email để tìm deadline, lịch học và việc cần làm| Người đi làm, sinh viên | Lặp lại mỗi tuần|
| 2 |Lặp lại |Sau khi nhận deadline mới phải copy thông tin từ email sang timeline/calendar |Sales Engineer |Lặp lại mỗi tuần |
| 3 |Tốn Thời gian |Tìm tài liệu cho một chủ đề dạy học nhưng phải mở và đọc nhiều nguồn trước khi chọn được tài liệu phù hợp |Bản thân, gia sư |Tốn khoảng 90/ tuần |
| 4 |Lặp lại |Mỗi buổi dạy phải chuyển nội dung giáo án thành bài tập, câu hỏi và homework |Bản thân, gia sư |Tốn khoảng 60p/tuần |
| 5 |Tốn thời gian |Khi phân tích khách hàng phải tìm thông tin từ nhiều nguồn rồi tự tổng hợp thành SWOT |bản thân, sales egineer | 90p/ tuần|
| 6 |AI có thể tốt hơn |Sau khi có thông tin khách hàng, phải tự phân loại thông tin thành Strength – Weakness – Opportunity – Threat |Bản thân, sales egineer | 90p/ tuần|
| 7 |Sai sót / AI có thể tốt hơn |Sau khi phân tích SWOT phải tự đối chiếu với sản phẩm để tìm solution phù hợp cho từng khách hàng |Sales Engineer + khách hàng |120p/tuần |
| 8 |Tốn thời gian |Phải xem bài giảng trước và sau các buổi học ( đọc slide, ghi chú, tổng hợp kiến thức)  |Học sinh- sinh viên |30-60p/buổi |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Email → tìm deadline, lịch học, việc cần làm |Lặp lại hàng tuần, workflow rõ, dễ đo thời gian và lỗi |Có bao nhiêu Email cần xử lý/tuần? |
| 2 |Research khách hàng → SWOT |Workflow rõ, mất ~90p/tuần, AI có thể hỗ trợ tốt | 90p là mất ở giai đoạn nào tìm hay tổng hợp? |
| 3 |Xem bài giảng → tổng hợp kiến thức để ôn tập |Lặp lại trong quá trình học, kiến thức nằm rải rác ở video/slide/ghi chú, AI có thể hỗ trợ tổng hợp và hệ thống hóa |Phần nào là tốn thời gian nhất? |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:
Mỗi tuần phải kiểm tra nhiều email để tìm deadline, lịch học và các việc cần làm rồi tự tổng hợp lại.
Actor:
Sinh viên - Người đi làm
Thời điểm / bối cảnh:
Mỗi ngày/mỗi tuần, khi có nhiều email từ trường, giảng viên và các bên liên quan.
Current workflow 3-7 bước:
1.Mở mail
2.Đọc subject và nội dung từng mail
3.Xác định email nào có deadline/lịch/việc cần làm.
4. Đọckỹ để lấy ngày/ giờ, địa điểm và yêu cầu
5.Tự tổng hợp thành danh sách việc cần làm.

Bottleneck:
Phải đọc nhiều email để lọc thông tin quan trọng và tổng hợp thủ công giữa email → calendar/note → to-do list.
Impact:
- Mất thời gian hàng tuần
- Dễ bỏ sót deadline và nhầm thời gian
Success metric:
- Giảm thời gian xử lý email.
- Giảm số deadline/lịch bị bỏ sót
- Có danh sách task, lịch chính xác sau mỗi lần check mail.
Non-AI alternative:
- Dùng Gmail filter/label.
- Tạo rule cho email có từ khóa “deadline”, “assignment”, “schedule”.
- Tự động chuyển email có lịch vào Calendar.
AI hypothesis:
AI đọc email → xác định deadline/lịch/task → trích xuất thông tin → đề xuất hoặc tạo task/calendar → người dùng review trước khi lưu.
Quick gut:
[ ] No AI / process fix
[ ] Rule
[+] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 30-60 phút/ tuần

[1 Mở email: 5'] → [2 Đọc/lọc email: 15-30'] → [3 Tìm deadline/lịch/task: 10-15'] → [4 tổng hợp vào note/calendar: 5-10']  <-- bottleneck

FUTURE STATE — 10-15 phút? tuần

[1 AI đọc & phân loại email: 5'] → [2 AI trích xuất deadline/lịch/task: 2'] → [3 Human review: 5']  <-- human boundary

Fallback: nếu AI trích xuất sai hoặc thiếu → không tạo calendar, giữ nguyên email để người dùng kiểm tra thủ công.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:
Mỗi tuần phải tìm kiếm, đọc và tổng hợp nhiều nguồn thông tin về khách hàng để xây dựng SWOT phục vụ sales.
Actor:
Sales Engineer
Thời điểm / bối cảnh:Khi chuẩn bị gặp khách hàng hoặc cần nghiên cứu khách hàng trước khi đề xuất giải pháp.
Current workflow 3-7 bước:
1.Xác định thông tin cần tìm về khách hàng.
2.Tìm thông tin trên website, mạng xã hội, tin tức hoặc tài liệu.
3.Mở và đọc nhiều nguồn.
4.Lọc thông tin liên quan.
5.Phân loại thành Strengths, Weaknesses, 6.Opportunities, Threats.
6.Tổng hợp thành SWOT.
7.Review lại trước khi sử dụng.
Bottleneck:
Thông tin nằm ở nhiều nguồn khác nhau, phải đọc và tự xác định thông tin nào có giá trị để đưa vào SWOT.
Impact:
Mất khoảng 90 phút/tuần theo bảng scan hiện tại.
Tốn công tìm kiếm và tổng hợp.
Chất lượng SWOT phụ thuộc nhiều vào khả năng research và phân tích.
Success metric:
Giảm thời gian research từ ~90 phút xuống mức thấp hơn.
Không bỏ sót thông tin quan trọng.
SWOT có nguồn dẫn chứng rõ ràng.
Người dùng đánh giá SWOT đủ chính xác để sử dụng.
Non-AI alternative:
Tạo template SWOT cố định.
Dùng checklist nguồn cần kiểm tra.
Bookmark các nguồn thường xuyên sử dụng.
Dùng spreadsheet để tổng hợp.
AI hypothesis:
AI thu thập thông tin từ các nguồn → tóm tắt → phân loại Strength/Weakness/Opportunity/Threat → dẫn nguồn → người dùng kiểm chứng.
Quick gut:
[ ] No AI / process fix
[ ] Rule
[+] Workflow
[+] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 90 phút/ tuần

[1 Xác định thông tin cần tìm: 10']
→ [2 Search nhiều nguồn: 25']
→ [3 Đọc & lọc thông tin: 30']  <-- bottleneck
→ [4 Phân tích + phân loại SWOT: 15']
→ [5 Tổng hợp + review: 10']

FUTURE STATE — 25-35 phút/ tuần

[1 AI research nhiều nguồn: ~10']→ [2 AI tóm tắt + phân loại SWOT + dẫn nguồn: ~10']→ [3 Human review & chỉnh sửa: ~15']  <-- human boundary

Fallback: nếu AI thiếu nguồn hoặc phân loại SWOT không hợp lý → quay lại nguồn gốc để kiểm tra và bổ sung thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:
Sau khi xem bài giảng phải tự đọc lại slide, ghi chú và tổng hợp kiến thức để có tài liệu hệ thống hóa cho việc ôn tập.
Actor:
sinh viên
Thời điểm / bối cảnh:
Trước và sau mỗi buổi học hoặc khi cần ôn lại kiến thức trước bài kiểm tra/project.
Current workflow 3-7 bước:
1.Xem video/bài giảng.
2.Đọc slide hoặc tài liệu đi kèm.
3.Ghi lại các ý chính.
4.Xác định khái niệm/công thức/nội dung quan trọng.
5.Đối chiếu giữa slide, lời giảng và ghi chú.
6.Tự hệ thống hóa kiến thức.
7.Đọc lại để ôn tập.

Bottleneck:
Kiến thức nằm rải rác ở video, slide và ghi chú, phải tự chuyển từ nhiều nguồn thành một hệ thống kiến thức dễ hiểu và dễ ôn.
Impact:
Lặp lại trong quá trình học.
Mất thêm thời gian sau khi đã xem bài giảng.
Dễ bỏ sót hoặc ghi chú trùng lặp.
Khó biết phần nào là kiến thức trọng tâm.
Success metric:
Giảm thời gian tổng hợp sau mỗi bài.
Tạo được một bản kiến thức có cấu trúc.
Không bỏ sót nội dung quan trọng.
Có thể dùng bản tổng hợp để ôn tập/trả lời câu hỏi.
Non-AI alternative:
Template ghi chú cố định.
Cornell Notes.
Mindmap.
Notion/OneNote để tổ chức kiến thức.
Tự highlight và tóm tắt slide.
AI hypothesis:
Template ghi chú cố định.
Cornell Notes.
Mindmap.
Notion/OneNote để tổ chức kiến thức.
Tự highlight và tóm tắt slide.
Quick gut:
[ ] No AI / process fix
[ ] Rule
[+] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 60 phút

[1 Xem bài giảng: 30']→ [2 Đọc lại slide: 10']→ [3 Ghi chú các ý chính: 10']→ [4 Hệ thống hóa kiến thức: 10']  <-- bottleneck

FUTURE STATE — 25-35 phút/ buổi

[1 AI đọc transcript + slide: ~5']→ [2 AI tổng hợp & hệ thống hóa: ~10']→ [3 Human review + bổ sung: ~10-20']  <-- human boundary

Fallback: nếu AI tóm tắt sai/thiếu → đối chiếu trực tiếp với
slide hoặc transcript gốc và tự chỉnh sửa.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```
Research khách hàng → SWOT
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```
Đây là workflow lặp lại hàng tuần: tìm kiếm → đọc/lọc nhiều nguồn → phân tích → tổng hợp thành SWOT để phục vụ sales.
Hiện tại mất khoảng 90 phút/tuần và bottleneck lớn nhất là phải đọc, lọc và tổng hợp thông tin từ nhiều nguồn.
AI có thể hỗ trợ research, tóm tắt, phân loại SWOT và dẫn nguồn, giúp giảm thời gian nhưng vẫn để sales review trước khi sử dụng.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
90 phút/tuần thực sự mất nhiều nhất ở bước nào: tìm kiếm, đọc/lọc hay phân tích và tổng hợp?

Nếu AI tự động tạo SWOT, làm sao đảm bảo các insight là chính xác và có đủ bằng chứng từ nguồn gốc?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: SWOT do AI tạo có rủi ro sai insight hoặc thiếu bằng chứng, đặc biệt khi thông tin từ nhiều nguồn không đồng nhất.
- Tôi sửa gì:
Thu hẹp MVP vào tóm tắt + phân loại SWOT có dẫn nguồn, thay vì để AI tự động hoàn toàn.
Giữ Human review ở cuối để kiểm chứng insight trước khi dùng cho sales.
### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
