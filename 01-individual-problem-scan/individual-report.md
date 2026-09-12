# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Tất Đạt
- Mã học viên: 2A202602578
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm cuối
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính          | Problem quan sát được                                            | Ai chịu ảnh hưởng?             | Dấu hiệu thật                                                           |
| - | ------------------ | ---------------------------------------------------------------- | ------------------------------ | ----------------------------------------------------------------------- |
| 1 | Tốn thời gian      | Tìm và lọc paper, trend, expert insight từ nhiều nguồn           | AI Engineer, Research Engineer | Mất vài giờ/topic trước khi đọc sâu
| 2 | Tốn thời gian      | Đọc nhiều paper để tìm đúng method phù hợp với bài toán hiện tại | AI Engineer, Research Engineer  | Đọc 5–10 paper nhưng chỉ dùng 1–2 paper                                         |
| 3 | Pain từ người khác | Giải thích technical progress cho stakeholder không chuyên       | AI Engineer, Tech Lead         | Phải giải thích lại nhiều lần; nhiều câu hỏi về ETA/kết quả             |
| 4 | Pain từ người khác | Requirement qua PM/nhiều team bị thiếu context và business rule  | Engineer, PM, team liên quan   | 2–3 vòng clarification/task; vẫn phát sinh rule mới                     |
| 5 | AI có thể tốt hơn  | Phát hiện requirement mơ hồ trước khi bắt đầu implementation     | Engineer, PM, QA               | Clarification/rework chỉ xuất hiện sau khi đã code hoặc chạy experiment |


> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác. Với mỗi gợi ý, ghi actor, workflow sơ bộ và cách đo. Đừng đưa ý tưởng quá rộng kiểu "xây trợ lý AI toàn năng".
- Ý dùng được: AI có thể tốt hơn  | Phát hiện requirement mơ hồ trước khi bắt đầu implementation     | Engineer, PM, QA               | Clarification/rework chỉ xuất hiện sau khi đã code hoặc chạy experiment |
- Ý bỏ vì không phải pain thật: 
Lặp lại | Tổng hợp hypothesis, config, metric và conclusion sau experiment | AI Engineer, Tech Lead | Lặp lại mỗi experiment/tuần; dữ liệu nằm ở nhiều tool

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tìm và lọc paper, trend, expert insight từ nhiều nguồn | Workflow lặp lại trước mỗi topic; đang mất vài giờ; có thể thu hẹp thành tạo shortlist paper cho một technical question | Chưa bấm giờ từng bước; chưa định nghĩa shortlist "đủ tốt" |
| 2 | Phát hiện requirement mơ hồ trước khi bắt đầu implementation | Có thời điểm can thiệp rõ trước khi code; rework muộn tạo impact lớn; có thể so sánh checklist với AI-assisted review | Chưa đo tỷ lệ task phát sinh clarification và thời gian rework |
| 3 | Giải thích technical progress cho stakeholder không chuyên | Actor và bối cảnh rõ; workflow update vẽ được; có dấu hiệu phải giải thích lại về ETA/kết quả | Chưa có baseline thời gian chuẩn bị và số lần phải giải thích lại; template có thể đã đủ |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tìm và lọc paper cho một technical question

```text
Problem 1 câu:
Trước khi nghiên cứu một technical question mới, AI Engineer hoặc Research
Engineer mất vài giờ tìm và lọc paper từ nhiều nguồn để có shortlist phù hợp.

Actor:
AI Engineer, Research Engineer.

Thời điểm / bối cảnh:
Khi bắt đầu một topic hoặc chuẩn bị experiment mới.

Current workflow 3-7 bước:
1. Xác định technical question và constraint của bài toán.
2. Tạo keyword và các biến thể truy vấn.
3. Search trên nhiều nguồn.
4. Đọc title, abstract và method của từng kết quả.
5. Loại kết quả trùng hoặc không phù hợp.
6. Tạo shortlist để đọc sâu.

Bottleneck:
Bước 3-5 — kết quả nằm ở nhiều nguồn và Engineer phải đọc lặp lại từng
abstract để đánh giá relevance.

Impact:
Mất vài giờ/topic trước khi có thể đọc sâu, làm chậm việc chọn method và
bắt đầu experiment.

Success metric:
Giảm thời gian tạo shortlist xuống dưới 60 phút/topic; trong 5 paper được
shortlist có ít nhất 3 paper được Engineer xác nhận là đáng đọc sâu; mỗi kết
quả phải có link nguồn để kiểm chứng.

Non-AI alternative:
Search-query template, danh sách venue/author tin cậy, citation chaining,
Google Scholar Alert và quy ước tag trong Zotero.

AI hypothesis:
AI hỗ trợ mở rộng keyword, chuẩn hóa metadata, loại trùng và trích xuất
problem, method, dataset, metric, limitation. Engineer kiểm nguồn và chốt
shortlist.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — vài giờ/topic

[1 Xác định câu hỏi]
→ [2 Tạo keyword]
→ [3 Search nhiều nguồn]
→ [4 Skim từng kết quả]  <-- bottleneck
→ [5 Loại trùng/không phù hợp]
→ [6 Tạo shortlist]

FUTURE STATE — target dưới 60 phút/topic

[1 Nhập câu hỏi + constraint: 5']
→ [2 Gom candidate: 10']
→ [3 AI trích xuất + loại trùng: 10']
→ [4 Engineer kiểm nguồn/relevance: 25']  <-- human boundary
→ [5 Chốt shortlist: 10']

Fallback: citation hoặc nội dung không kiểm chứng được → loại candidate và
quay về search thủ công trên các nguồn tin cậy.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Phát hiện requirement mơ hồ trước implementation

```text
Problem 1 câu:
Khi nhận task mới, Engineer thường chỉ phát hiện requirement, acceptance
criteria hoặc business rule còn thiếu sau khi đã code hoặc chạy experiment,
dẫn đến clarification và rework muộn.

Actor:
Engineer trực tiếp nhận và implementation task.

Thời điểm / bối cảnh:
Sau khi nhận ticket/PRD và trước khi estimate hoặc bắt đầu implementation.

Current workflow 3-7 bước:
1. Nhận ticket hoặc PRD.
2. Đọc requirement và acceptance criteria.
3. Hỏi những điểm mơ hồ dễ nhận thấy.
4. Estimate và bắt đầu implementation.
5. Khi code/test mới phát hiện rule hoặc edge case còn thiếu.
6. Clarify rồi sửa lại phần đã làm.

Bottleneck:
Không có bước review requirement có cấu trúc trước khi implementation; vấn đề
chỉ lộ ra khi chi phí sửa đã cao hơn.

Impact:
Implementation bị gián đoạn, estimate thay đổi và phát sinh rework. Cần log
trên ít nhất 5 task để có baseline riêng cho problem này.

Success metric:
Giảm ít nhất 50% số clarification phát sinh sau khi bắt đầu implementation;
không tăng số requirement defect bị phát hiện ở QA/nghiệm thu.

Non-AI alternative:
Definition of Ready, checklist requirement và review ngắn trước khi estimate.

AI hypothesis:
AI review ticket theo checklist, chỉ ra câu mơ hồ và sinh câu hỏi cần xác nhận.
Engineer và người giao task vẫn approve requirement cuối cùng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 6 bước; baseline thời gian chưa đo

[1 Nhận ticket]
→ [2 Đọc requirement]
→ [3 Hỏi các điểm dễ thấy]
→ [4 Bắt đầu implementation]
→ [5 Phát hiện rule/edge case còn thiếu]  <-- bottleneck
→ [6 Clarify + rework]

FUTURE STATE — target giảm ít nhất 50% clarification muộn

[1 Nhận ticket]
→ [2 Kiểm tra Definition of Ready]
→ [3 AI flag điểm mơ hồ/thiếu]
→ [4 Engineer chọn câu hỏi phù hợp]
→ [5 Người giao task xác nhận]  <-- human boundary
→ [6 Estimate + implementation]

Fallback: AI flag sai hoặc bỏ sót → Engineer dùng checklist và review trực tiếp;
AI không tự sửa requirement hoặc approve ticket.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Giải thích technical progress cho stakeholder không chuyên

```text
Problem 1 câu:
Khi cập nhật tiến độ dự án AI, Engineer phải tự chuyển kết quả kỹ thuật thành
thông tin dễ hiểu nhưng stakeholder vẫn thường hỏi lại về kết quả và ETA.

Actor:
AI Engineer hoặc Tech Lead chuẩn bị update cho stakeholder không chuyên.

Thời điểm / bối cảnh:
Trong weekly sync, milestone review hoặc khi được hỏi về trạng thái task.

Current workflow 3-7 bước:
1. Gom kết quả experiment, metric và blocker.
2. Chọn thông tin cần đưa vào update.
3. Diễn giải thuật ngữ kỹ thuật bằng ngôn ngữ ít chuyên môn hơn.
4. Trình bày kết quả, uncertainty và ETA.
5. Nhận câu hỏi vì stakeholder chưa rõ tác động hoặc trạng thái.
6. Giải thích lại bằng ví dụ hoặc mức chi tiết khác.

Bottleneck:
Bước 2-4 — chuyển technical evidence và uncertainty thành một update ngắn,
đúng và hướng tới quyết định.

Impact:
Engineer mất thêm thời gian chuẩn bị và giải thích lại; stakeholder chậm nắm
status, blocker hoặc ETA. Cần log ít nhất 5 lần update để có baseline.

Success metric:
Giảm ít nhất 30% thời gian chuẩn bị và 50% số câu hỏi/vòng giải thích lại do
update không rõ; không có số liệu hoặc kết luận sai trong bản được gửi.

Non-AI alternative:
Status-update template gồm objective, result, business meaning, confidence,
blocker, ETA và decision/ask.

AI hypothesis:
AI tạo executive summary và technical details từ input có cấu trúc. Engineer
kiểm số liệu, uncertainty và approve trước khi chia sẻ.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 6 bước; cần bấm giờ 5 lần để có baseline

[1 Gom result/metric]
→ [2 Chọn thông tin]
→ [3 Tự diễn giải technical detail]  <-- bottleneck
→ [4 Trình bày update]
→ [5 Nhận câu hỏi]
→ [6 Giải thích lại]

FUTURE STATE — target giảm ít nhất 30% thời gian chuẩn bị

[1 Nhập result + evidence]
→ [2 Điền update template]
→ [3 AI draft hai lớp nội dung]
→ [4 Engineer kiểm số liệu/ETA]  <-- human boundary
→ [5 Gửi hoặc trình bày]

Fallback: AI làm sai hoặc mất nuance → Engineer bỏ draft và dùng template thủ
công; AI không tự gửi update hoặc cam kết ETA.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #2 — Phát hiện requirement mơ hồ trước implementation
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow hiện tại đi từ nhận ticket, đọc requirement đến implementation, nhưng
nhiều business rule hoặc edge case chỉ được phát hiện khi đã code/test nên phải
quay lại clarification và rework. Tôi chọn card này vì vấn đề làm gián đoạn tiến
độ và thay đổi estimate; mục tiêu là giảm ít nhất 50% số clarification phát sinh
muộn trên tối thiểu 5 task mà không tăng requirement defect ở bước QA/nghiệm thu.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Definition of Ready và checklist có đủ giải quyết vấn đề mà chưa cần AI không?
Làm sao đo AI đang phát hiện ambiguity có giá trị thay vì tạo thêm nhiều câu hỏi
không cần thiết và làm chậm thời điểm bắt đầu implementation?
```

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
