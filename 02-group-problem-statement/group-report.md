# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Thị Bảo Trang    |      2A202602580       |                       Leader                                      |
| 2   | Nguyễn Tất Đạt          |   2A202602578        |            writer, research                                                   |
| 3   |   Nguyễn Hồng Cường        |     2A202602415     |                           research                          |
| 4   |       Nguyễn Thanh Giang |   2A202602576           |                    writer, research                                           |
| 4   |       Đặng Thế Vinh  |   2A202602587         |                   workflow                                            |
**Candidate problem nhóm chọn (1 câu):**

Sinh viên đại học phải tự theo dõi deadline học tập từ nhiều kênh rời rạc, khiến họ mất thời gian tổng hợp và có nguy cơ bỏ sót hoặc xử lý công việc sát hạn.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Thị Bảo Trang | Khó bàn giao task giữa người mạnh Finance và người mạnh Technology | Sinh viên Fintech năm 3 làm bài nhóm, đặc biệt các thành viên phụ trách Finance, Technology, dữ liệu và báo cáo | Ghép các phần và kiểm tra sự thống nhất; input, output, công thức, biến số hoặc tiêu chí hoàn thành chưa rõ | Workflow rõ, đúng đặc thù bài nhóm Fintech; cần kiểm tra nguyên nhân chính là task chưa rõ hay thiếu kiến thức |
| 2 | Nguyễn Thị Bảo Trang | Khó liên kết một khái niệm tài chính với cách công nghệ triển khai khái niệm đó | Sinh viên Fintech năm 3 làm bài tập hoặc thuyết trình liên ngành | Tự nối tài liệu Finance với tài liệu Technology để tạo ví dụ hoặc cách giải thích thống nhất | Đúng đặc thù Fintech và có thể đo thời gian chuẩn bị; cần làm rõ cách đo mức độ hiểu và chất lượng liên kết |
| 3 | Nguyễn Thị Bảo Trang | Không biết cách xác định và xử lý lỗi Python/SQL trong bài phân tích tài chính | Sinh viên Fintech năm 3 làm bài thực hành hoặc project phân tích dữ liệu tài chính | Tìm nguyên nhân và thử cách sửa khi lỗi có thể đến từ code, dữ liệu hoặc logic tính toán | Workflow lặp lại, dễ đo thời gian xử lý lỗi; cần kiểm chứng kết quả tài chính sau khi sửa |
| 4 | Cường|Agent chọn sai tool trong 170+ tool registry, phải trace log thủ công |Dev vận hành agent | Đọc reasoning trace + so khớp registry thủ công| |
| 5 |Cường |Debug latency spike trên pipeline giọng nói robot, đối chiếu log 4 lớp thủ công | Dev tối ưu pipeline|Đối chiếu timestamp qua VAD/ASR/TTS/ALSA | |
| 6 |Cường |Handoff task thiếu context |Người nhận task |Note bàn giao thiếu chuẩn | |
| 7 | Nguyễn Tất Đạt | Phát hiện requirement mơ hồ trước khi bắt đầu implementation | Engineer, PM, QA | Clarification/rework chỉ xuất hiện sau khi đã code hoặc chạy experiment |  |
| 8 | Nguyễn Tất Đạt | Tìm và lọc paper, trend, expert insight từ nhiều nguồn | AI Engineer, Research Engineer | Mất vài giờ/topic trước khi đọc sâu | |
| 9 | Nguyễn Thanh Giang | Kiểm tra và đồng bộ dữ liệu từ nhiều nguồn trước khi ghép thành dataset cuối cùng | Người xử lí dữ liệu | Phải kiểm tra nhiều file/bảng, đối chiếu ngày tháng, tên biến và đơn vị trước khi merge |
| 10 | Người đưa ra |Tìm kiếm và đọc nhiều bài báo để xác định phương pháp, biến đầu vào và kết quả liên quan đến đề tài | Người thực hiện nghiên cứu | Phải đọc từng bài, tìm thông tin cần thiết và ghi chú lại để so sánh |
|11 | Đặng Thế Vinh | Nhân viên mới thường hỏi lặp lại các câu hỏi nội bộ | Newbie/mentor/HR | Phải dành thời gian trả lời lại | 
|12| Đặng Thế Vinh | Quên deadline công việc, bài tập hoặc lịch kiểm tra | Học sinh/ Người đi làm| Phải dành thời gian tra cứu từ nhiều kênh thông tin|

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Phối hợp công việc, yêu cầu và deadline | #1 Bàn giao Finance–Technology; #6 Handoff task thiếu context; #7 Phát hiện requirement mơ hồ trước implementation; #12 Quên deadline do thông tin nằm ở nhiều kênh | Thông tin cần để thực hiện công việc chưa được chuẩn hóa hoặc tập trung, khiến người nhận phải hỏi lại, phát hiện mơ hồ muộn hoặc bỏ sót mốc thời gian. | #1 có workflow chi tiết nhất; #12 có tập người dùng rộng hơn nhưng phải thu hẹp actor còn sinh viên đại học và pain còn deadline học tập đa kênh trước khi đưa vào shortlist. |
| B — Tìm, tổng hợp và sử dụng tri thức | #2 Kết nối Finance với Technology; #8 Tìm/lọc paper, trend, expert insight; #10 Tìm và đọc bài báo để xác định phương pháp, biến và kết quả; #11 Nhân viên mới hỏi lặp lại câu hỏi nội bộ | Người dùng phải tìm thông tin từ tài liệu hoặc từ người khác, rồi chọn, kết nối và diễn giải thông tin để hoàn thành công việc. | #8 và #10 gần như cùng một pattern research. #11 có thể xử lý một phần bằng FAQ/onboarding chuẩn trước khi cần AI. |
| C — Kiểm tra, debug và đồng bộ dữ liệu/kỹ thuật | #3 Xác định và xử lý lỗi Python/SQL; #5 Debug latency spike qua 4 lớp log; #9 Kiểm tra và đồng bộ dữ liệu đa nguồn trước khi merge | Cùng là workflow đối chiếu nhiều tín hiệu để tìm nguyên nhân sai lệch trước khi tạo output cuối. | #9 có workflow dữ liệu khá rõ; #3 và #5 cần boundary kiểm chứng rất chặt vì code chạy được chưa chắc kết quả đã đúng. |
| D — Chọn công cụ cho agent | #4 Agent chọn sai tool trong registry 170+ tools | Cần tìm đúng công cụ từ tập lựa chọn lớn và trace lại lý do chọn sai. | Pain kỹ thuật cụ thể nhưng nhóm có ít thông tin về registry, log và môi trường vận hành thực tế để validate trong lab. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #12 — Theo dõi deadline học tập từ nhiều kênh | Thu hẹp actor còn sinh viên đại học và scope còn deadline trên LMS, email, nhóm chat và lịch học. Problem scan cá nhân đã có baseline sơ bộ: kiểm tra khoảng 4 kênh, mất khoảng 10 phút/ngày. Bài toán dễ khảo sát trong lớp và có thể đo thời gian tổng hợp, số deadline bỏ sót, số việc làm sát hạn. | Chưa có dữ liệu tại VinUni về tỷ lệ bỏ sót deadline và chưa biết pain chính là thông tin phân tán, thông báo quá nhiều hay thói quen lập kế hoạch. Cần tránh mở rộng thành “trợ lý quản lý cuộc sống”. |
| #1 — Khó bàn giao task giữa người mạnh Finance và Technology | Actor, workflow 6 bước và bottleneck ghép bài đều rõ; baseline sơ bộ là 30–60 phút, 3–5 lần hỏi lại và 1–2 lần sửa. Có thể thử template handoff trước khi đánh giá AI. | Khá đặc thù với nhóm Fintech và phụ thuộc cách phân chia năng lực trong từng nhóm. Cần xác nhận nguyên nhân là task thiếu cấu trúc hay thành viên thiếu kiến thức liên ngành. |
| #11 — Nhân viên mới hỏi lặp lại câu hỏi nội bộ | Pain onboarding dễ hiểu; có thể đo số câu hỏi lặp lại và thời gian mentor/HR trả lời. Có thể so sánh handbook/FAQ, search workflow và chatbot có kiểm soát. | Actor và tổ chức chưa cụ thể; chưa có số câu hỏi, thời gian hoặc kho tài liệu nội bộ thật. Nhóm khó validation nhanh nếu không tiếp cận đủ nhân viên mới và mentor. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #12 — Theo dõi deadline học tập đa kênh | 5 | 5 | 4 | 5 | 5 | 5 | 5 | 34 |
| #1 — Bàn giao Finance–Technology | 5 | 5 | 4 | 5 | 5 | 5 | 4 | 33 |
| #11 — Câu hỏi nội bộ lặp lại khi onboarding | 4 | 3 | 3 | 4 | 5 | 5 | 4 | 28 |

**Cách đọc điểm:** #12 đạt điểm cao nhất vì actor đã được thu hẹp thành sinh viên đại học, workflow kiểm tra nhiều kênh có thể vẽ và mọi thành viên đều tiếp cận được người dùng để validation. Evidence chỉ là 4, không phải 5, vì baseline 4 kênh và 10 phút/ngày mới đến từ problem scan cá nhân; bằng chứng bên ngoài chưa đại diện cho sinh viên VinUni. #1 rất rõ nhưng phạm vi người gặp hẹp hơn; #11 dễ hiểu nhưng thiếu workflow và bằng chứng nội bộ cụ thể.

**Tín hiệu research hỗ trợ việc chọn #12:** Khảo sát Pathify 2025 với 1.010 sinh viên đại học Mỹ cho biết 47% từng bỏ lỡ một deadline quan trọng vì không biết hạn, thường trong bối cảnh phải điều hướng nhiều portal tách rời; 75% ưu tiên một điểm truy cập tập trung. Đây là khảo sát do nhà cung cấp giải pháp tài trợ nên chỉ dùng làm bằng chứng định hướng, không thay validation tại VinUni. Ngoài ra, hai thử nghiệm được công bố trên *IEEE Transactions on Learning Technologies* cho thấy thông báo chủ động trước hạn làm giảm assignment bị bỏ lỡ, chứng minh đây là pain có thể can thiệp và đo lường. Nguồn: [EDUCAUSE/Pathify Student Digital Experience Survey 2025](https://www.educause.edu/about/corporate-participation/member-press-releases/new-survey-finds-fragmented-digital-systems-are-eroding-student-success), [ERIC — Automated Educative Nudges to Reduce Missed Assignments in College](https://eric.ed.gov/?id=EJ1297780).

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Sinh viên đại học phải tự kiểm tra deadline bài tập, quiz, thuyết trình và lịch họp từ LMS, email, nhóm chat và lịch học; thông tin phân tán khiến họ mất thời gian tổng hợp và có nguy cơ bỏ sót hoặc xử lý công việc sát hạn.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn candidate này vì deadline phân tán là vấn đề mà nhiều sinh viên có thể trải nghiệm và nhóm dễ tiếp cận người dùng để khảo sát. Problem scan cá nhân đã ghi nhận workflow phải kiểm tra khoảng bốn kênh và tốn khoảng 10 phút mỗi ngày; research bên ngoài cũng cho thấy bỏ lỡ deadline do hệ thống số phân mảnh là một pain đáng kể. Bài toán có thể đo bằng thời gian tổng hợp lịch, số deadline phải nhập tay, số deadline bị bỏ sót và số đầu việc chỉ bắt đầu sát hạn. Scope được thu hẹp vào deadline học tập của sinh viên đại học, không bao gồm toàn bộ công việc và đời sống cá nhân. Nhóm vẫn phải khảo sát tại VinUni xem nguyên nhân chính là thông tin phân tán, thông báo quá tải hay thói quen quản lý thời gian trước khi chọn giải pháp.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#1 — Bàn giao Finance–Technology: Candidate có workflow và baseline cụ thể, nhưng chỉ tác động mạnh đến một nhóm sinh viên Fintech có sự phân chia vai trò Finance–Technology. #12 được ưu tiên vì có tập người dùng rộng hơn và dễ validation với sinh viên trong lớp.

#2 — Kết nối khái niệm Finance với cách Technology triển khai: Candidate đúng bối cảnh Fintech và có workflow tìm–đọc–kết nối tài liệu, nhưng “hiểu đúng” và chất lượng liên kết hiện chưa có thước đo khách quan. Phạm vi người gặp cũng hẹp hơn bài toán deadline học tập.

#3 — Xác định và xử lý lỗi Python/SQL: Thời gian debug có thể đo, nhưng bài toán đang gộp lỗi cú pháp, dữ liệu và logic tài chính thành nhiều nguyên nhân khác nhau. Việc kiểm chứng kết quả sau khi sửa cũng cần test case và người hiểu domain sâu.

#4 — Agent chọn sai tool trong registry: Pain kỹ thuật rõ và có số lượng 170+ tools, nhưng cần quyền truy cập registry, reasoning trace và log thực tế để validate. Scope dễ chuyển thành bài toán vận hành agent chuyên sâu, khó hoàn thành chắc chắn trong lab.

#5 — Debug latency pipeline giọng nói: Workflow đối chiếu bốn lớp log khá cụ thể nhưng cần log thật và kiến thức về VAD, ASR, TTS, ALSA. Nhóm chưa có đủ evidence về tần suất và thời gian debug nên không chọn.

#6 — Handoff task thiếu context: Candidate gần như trùng pattern với #1 nhưng actor, bối cảnh, workflow và metric còn quá ngắn. Nếu tiếp tục nghiên cứu cluster handoff, nhóm sẽ dùng #1 làm phiên bản cụ thể hơn.

#7 — Requirement mơ hồ trước implementation: Actor và tác động rework rõ, nhưng notes chưa có baseline hoặc ví dụ requirement cụ thể. Scope cũng có thể mở rộng sang toàn bộ quy trình phát triển sản phẩm, nên nhóm chưa đưa vào shortlist cuối.

#8 — Tìm và lọc paper, trend, expert insight: Pain mất vài giờ mỗi topic là tín hiệu đáng chú ý nhưng workflow tìm, tiêu chí lọc và output mong muốn chưa cụ thể. Candidate cũng gần trùng với #10 và cần metric chất lượng nguồn.

#9 — Đồng bộ dữ liệu trước khi merge: Workflow và impact có thể đo, nhưng nhóm chưa ghi nhận dataset mẫu, schema chuẩn hoặc bối cảnh dữ liệu mà mọi người cùng hiểu sâu. Việc validation cũng khó mở rộng ra nhiều người bằng #12.

#10 — Đọc bài báo để xác định phương pháp, biến và kết quả: Workflow research có thể vẽ được nhưng chưa có baseline thời gian, số bài phải đọc hoặc tiêu chí thế nào là trích xuất đúng. Candidate gần trùng #8 nên nhóm không giữ cả hai trong shortlist.

#11 — Nhân viên mới hỏi lặp lại câu hỏi nội bộ: Pain dễ hiểu và có thể đo số câu hỏi hoặc thời gian mentor trả lời, nhưng chưa có tần suất, loại câu hỏi, nguồn tri thức nội bộ hay bối cảnh tổ chức cụ thể. Nhóm khó tiếp cận dữ liệu doanh nghiệp và cần thử FAQ/handbook trước khi giả định cần AI.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Ban đầu nhóm nghiêng về #1 vì workflow và baseline cụ thể, nhưng có lo ngại rằng bài toán quá đặc thù và khó chứng minh nhiều người gặp. Sau khi so lại các candidate và xem tín hiệu research, nhóm chuyển sang #12 nhưng thu hẹp actor còn sinh viên đại học và pain còn việc theo dõi deadline học tập đa kênh. Đây vẫn là quyết định tạm thời: nếu Phase 4 cho thấy sinh viên không thường bỏ sót deadline vì thông tin phân tán, nhóm sẽ hạ bài toán xuống một giải pháp Rule/process như lịch chung và checklist, hoặc quay lại candidate #1.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Phỏng vấn mô phỏng — Sinh viên A | 1 (Nguyên - Zone C) | “Mình phải xem LMS, email và nhóm chat; tuần trước suýt quên một quiz vì thông báo bị trôi.” | Bạn này vẫn dùng Google Calendar nên chưa bỏ lỡ deadline hoàn toàn. | Tập trung vào bước gom deadline từ nhiều kênh, không chỉ gửi thêm thông báo. |
| Phỏng vấn mô phỏng — Sinh viên B | 1 (Nhóm Hắc Bạch Vô Thường - Zone B) | “Mỗi tối mình mất khoảng 10 phút kiểm tra ba hoặc bốn kênh để cập nhật việc ngày mai.” | Deadline trên LMS tương đối rõ; đôi khi nguyên nhân làm sát hạn là trì hoãn. | Tách pain thông tin phân tán khỏi pain quản lý thời gian cá nhân. |
| Phỏng vấn mô phỏng — Sinh viên C | 1 (Đình Long - Zone A) | “Lịch họp nhóm hay đổi trong chat nhưng lịch cá nhân không cập nhật, nên mình từng nhớ nhầm giờ.” | Một lịch chung của nhóm có thể đã đủ, chưa chắc cần AI. | So sánh lịch/checklist đơn giản với workflow có AI trước khi chọn giải pháp. |

> **Lưu ý:** Ba câu trả lời trên là dữ liệu mô phỏng để chuẩn bị phỏng vấn, không phải quote thật. Trước khi nộp, nhóm phải hỏi 2–3 sinh viên và thay bằng câu trả lời thực tế.

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Giả thuyết ban đầu là pain nằm ở bước sinh viên phải tự gom và đối chiếu deadline từ nhiều kênh. Tuy nhiên, nhóm cần phân biệt ba nguyên nhân: thông tin phân tán, lịch thay đổi không đồng bộ và trì hoãn cá nhân.
```

**Ba câu hỏi phỏng vấn thật cần hỏi:**

1. Tuần gần nhất bạn phải kiểm tra những kênh nào để biết deadline?
2. Lần gần nhất bạn bỏ sót hoặc phát hiện deadline muộn là khi nào, vì sao?
3. Một lịch tập trung có đủ giải quyết vấn đề không, hay bạn cần hỗ trợ gì khác?

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Canvas Calendar | [Canvas Guide](https://community.canvaslms.com/html/assets/Canvas_Basics_Guide.pdf) | Gom assignment/event trong LMS và xuất lịch sang Google/Outlook. | Tự đồng bộ deadline có cấu trúc, không cần AI. | Không lấy được deadline chỉ xuất hiện trong email hoặc nhóm chat. | Dùng Rule/calendar feed cho nguồn có cấu trúc. |
| Google Tasks/Calendar | [Google Calendar Help](https://support.google.com/calendar/answer/9901136) | Lưu task, deadline và gửi nhắc việc. | Dễ dùng và phù hợp làm pilot. | Vẫn phải nhập tay; nhập sai thì lịch cũng sai. | Đây là phương án non-AI cần thử trước. |
| Todoist | [Calendar integration](https://www.todoist.com/help/todoist/integrations/use-the-calendar-integration-rCqwLCt3G) | Hiển thị task và lịch trong một nơi, hỗ trợ Today/Upcoming. | Hữu ích cho planning và time-blocking. | Không tự xác minh deadline từ email/chat; thêm app có thể tăng phân mảnh. | Khoảng trống nằm ở thu thập và xác minh deadline. |
| Automated Educative Nudges | [Nghiên cứu IEEE/ERIC](https://eric.ed.gov/?id=EJ1297780) | Gửi nhắc việc khi assignment sắp đến hạn nhưng chưa nộp. | Hai pilot ghi nhận giảm bài bị bỏ lỡ. | Phụ thuộc dữ liệu LMS và có thể tạo quá nhiều thông báo. | Chỉ nhắc đúng lúc, có điều kiện và đo mức độ khó chịu. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm nên thử một lịch tập trung và quy tắc nhập deadline trước. Chỉ dùng AI để trích xuất deadline từ email/chat không có cấu trúc; sinh viên phải xác nhận nội dung và thời hạn trước khi lưu. Chưa cần Agent tự quản lý toàn bộ lịch.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: [02-group-problem-statement-workflow.png](02-group-problem-statement-workflow.png)

![Current và future workflow](02-group-problem-statement-workflow.png)

```text
[1 Nhận thông báo: theo sự kiện - hệ thống/giảng viên]
→ [2 Đọc và tự trích xuất thông tin: 2-3'/thông báo - sinh viên]
→ [3 Đối chiếu phiên bản giữa 3-4 nguồn: 3-5'/lần thay đổi - sinh viên, bottleneck]
→ [4 Ghi deadline vào note/calendar/todo: 1-2'/deadline - sinh viên]
→ [5 Tự sửa deadline khi có thông báo mới: 1-2'/lần thay đổi - sinh viên]
→ [6 Mở lại các kênh để rà soát: khoảng 10'/ngày - sinh viên]
→ [7 Phát hiện sát hạn nếu kiểm tra muộn: phát sinh làm/ôn gấp - sinh viên]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | LMS, email, nhóm chat, giảng viên hoặc tài liệu môn học | Thông báo mới về bài tập, quiz, thuyết trình hoặc lịch kiểm tra | Thông báo nằm rải rác tại từng kênh | Theo sự kiện; nhiều lần trong tuần | Handoff từ nhiều nguồn sang sinh viên; định dạng và độ đầy đủ không đồng nhất. |
| 2 | Sinh viên | Nội dung từng thông báo | Tên môn, tên việc, deadline và yêu cầu được hiểu tạm thời | Khoảng 2-3 phút/thông báo (ước lượng cần đo trong pilot) | Trích xuất thủ công; dễ đọc thiếu chi tiết hoặc hiểu sai ngày giờ. |
| 3 | Sinh viên | Các thông báo có thể trùng, nhắc lại hoặc thay đổi | Phiên bản deadline được cho là mới nhất | Khoảng 3-5 phút/lần có thay đổi (ước lượng cần đo) | **Bottleneck:** phải so nguồn, thời điểm và ngữ cảnh; không có một nguồn sự thật duy nhất. |
| 4 | Sinh viên | Deadline đã tự xác định | Một mục trong note, calendar, todo app hoặc trí nhớ | Khoảng 1-2 phút/deadline (ước lượng cần đo) | Handoff thủ công sang công cụ cá nhân; có thể nhập thiếu hoặc sai. |
| 5 | Sinh viên | Thông báo cập nhật deadline | Mục cũ được tìm và sửa lại | Khoảng 1-2 phút/lần thay đổi (ước lượng cần đo) | Dễ tồn tại hai phiên bản nếu quên sửa hoặc sửa nhầm mục. |
| 6 | Sinh viên | Calendar, LMS, email và nhóm chat | Danh sách deadline được rà soát lại | Khoảng 10 phút/ngày theo baseline sơ bộ | Công việc lặp lại; phụ thuộc thói quen chủ động của sinh viên. |
| 7 | Sinh viên | Deadline bị bỏ sót hoặc được phát hiện muộn | Bài làm/việc ôn tập phải xử lý gấp | Khi bước rà soát không diễn ra kịp thời | Đây là hậu quả của workflow, không phải một bước tạo giá trị. |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck nằm ở bước 3 và lặp lại ở bước 5-6: sinh viên phải tự đối chiếu nhiều thông báo để xác định phiên bản deadline mới nhất, sau đó nhớ cập nhật đúng mục đã lưu. Việc này không khó ở từng thao tác riêng lẻ nhưng diễn ra trên 3-4 kênh, phụ thuộc vào thói quen kiểm tra hằng ngày và hiện tốn khoảng 10 phút/ngày; nếu bỏ một lần kiểm tra, lỗi chỉ được phát hiện khi đã gần hạn.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Thu nhận thông báo: liên tục - Rule/connector]
→ [2 Import trường có cấu trúc từ LMS/calendar: <0,5'/batch - Rule]
  hoặc [2 AI trích xuất email/chat không cấu trúc: <1'/batch - AI]
→ [3 Chuẩn hóa về cùng schema và gắn link nguồn: <0,5'/batch - Workflow]
→ [4 So khớp, gộp trùng, phát hiện thay đổi/xung đột: <0,5'/batch - Rule + AI]
→ [5 Sinh viên xem nguồn, sửa nếu cần và xác nhận: 1-2'/batch - HUMAN BOUNDARY]
→ [6 Ghi/cập nhật lịch tập trung và tạo nhắc việc: <0,5'/batch - Rule]

Fallback: Nếu thiếu quyền truy cập, AI có độ tin cậy thấp hoặc hai nguồn xung đột, workflow không ghi lịch mà đưa mục vào hàng chờ. Sinh viên mở thông báo gốc, nhập/sửa thủ công; mọi cập nhật lịch có lịch sử và có thể hoàn tác.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | Khoảng 10 phút/ngày | Không quá 3 phút/ngày | Ghi time log trong 2 tuần, tính trung bình theo người/ngày. |
| Số bước | 7 bước | 6 bước | Đếm các bước từ lúc nhận thông báo đến khi lịch tập trung được cập nhật; bước phát hiện sát hạn được loại khỏi happy path. |
| Số bước thủ công | 5 bước xử lý thủ công (bước 2-6) | 1 bước bắt buộc review/xác nhận; 1 bước sửa khi có ngoại lệ | Ghi log thao tác và đếm số lần sinh viên phải đọc, nhập hoặc sửa bằng tay. |
| Bottleneck chính | Đối chiếu phiên bản và kiểm tra lại 3-4 kênh | Review các mục bị đổi, xung đột hoặc độ tin cậy thấp | Đo thời gian review và số mục bị đưa vào hàng chờ. |
| Risk mới | Không có lỗi do AI, nhưng dễ bỏ sót do thao tác tay | AI có thể trích sai ngày, môn hoặc chọn sai phiên bản | Đối chiếu output với thông báo gốc trước khi xác nhận; theo dõi số trường phải sửa và số lần hoàn tác. |
| Deadline bị bỏ sót từ nguồn theo dõi | Chưa có baseline chắc chắn; đã có nguy cơ phát hiện sát hạn | 0 deadline bị bỏ sót trong pilot | Cuối mỗi tuần đối soát lịch tập trung với toàn bộ thông báo thuộc phạm vi pilot. |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học phải quản lý bài tập, quiz, thuyết trình và lịch kiểm tra trong nhiều môn học. Họ nhận thông tin qua LMS, email, nhóm chat, giảng viên và tài liệu môn học. |
| **Workflow** | Sinh viên đọc từng thông báo, tự trích xuất thông tin, đối chiếu phiên bản, nhập hoặc sửa deadline trong công cụ cá nhân rồi định kỳ mở lại các kênh để kiểm tra. Current workflow gồm 7 bước và phụ thuộc chủ yếu vào thao tác thủ công. |
| **Bottleneck** | Bước đối chiếu phiên bản mới nhất là điểm nghẽn vì thông báo có thể bị nhắc lại, thay đổi hoặc chỉ xuất hiện ở một kênh. Điểm nghẽn lặp lại khi sinh viên phải tìm đúng mục cũ để cập nhật và rà soát 3-4 kênh. |
| **Impact** | Baseline sơ bộ là khoảng 10 phút/ngày chỉ để kiểm tra và tổng hợp deadline. Nếu kiểm tra muộn hoặc nhập sai, sinh viên có thể phát hiện bài tập/lịch kiểm tra sát hạn và phải làm hoặc ôn tập gấp. |
| **Success Metric** | Trong pilot 2 tuần, giảm thời gian theo dõi trung bình từ khoảng 10 xuống không quá 3 phút/ngày và giảm còn một bước review bắt buộc. Không bỏ sót deadline từ các nguồn thuộc phạm vi pilot; các trường AI trích xuất phải được đo bằng tỷ lệ đúng trước khi người dùng sửa. |
| **Boundary** | Chỉ xử lý deadline học tập từ các nguồn người dùng cho phép và chỉ ghi lịch sau khi sinh viên xác nhận. Không tự nộp bài, tự quyết định ưu tiên học tập, quản lý lịch cá nhân ngoài học tập hoặc coi nội dung AI suy luận là nguồn chính thức. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Baseline số deadline bị bỏ sót và tỷ lệ trích xuất đúng chưa có số đo; khái niệm “nguồn mới nhất” cũng chưa đủ chặt khi email, chat và LMS mâu thuẫn.
- Tôi sửa gì: Ở v1, nhóm quy định output bắt buộc có link nguồn, thời điểm thông báo và trạng thái xác nhận; mọi thay đổi/xung đột phải qua sinh viên review. Metric được gắn với pilot 2 tuần và cách đo cụ thể.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì email/chat có thể diễn đạt deadline gián tiếp, thiếu múi giờ hoặc mâu thuẫn với một thông báo trước đó; hệ thống phải thể hiện độ tin cậy thay vì tự coi một suy luận là đúng.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì workflow nhận dữ liệu từ 3-4 nguồn, chuẩn hóa, so khớp phiên bản, review rồi mới cập nhật lịch.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ phức tạp cao × độ mơ hồ cao.
```

**Vì sao (2-3 câu):**

```text
Dữ liệu đi qua nhiều nguồn và bước sau phụ thuộc kết quả trích xuất, chuẩn hóa ở bước trước nên độ phức tạp cao. Ngôn ngữ tự nhiên và thông báo thay đổi làm đầu vào có độ mơ hồ cao; tuy nhiên đường xử lý sau khi nhận input vẫn cố định, vì vậy nhóm có thể kiểm soát bằng Workflow và human boundary thay vì giao toàn quyền cho Agent.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Đồng bộ calendar feed, map các trường cố định, gộp bản ghi theo ID và gửi reminder theo mốc thời gian. | Đủ khi deadline có cấu trúc chuẩn và nguồn cung cấp ID/version đáng tin cậy. | Không hiểu tốt email/chat tự nhiên; có thể tạo mục trùng hoặc bỏ qua thay đổi diễn đạt tự do. | Chọn cho thu nhận nguồn có cấu trúc, ghi/cập nhật calendar và reminder. |
| **Workflow** | Connector/forward input → Rule hoặc AI trích xuất → chuẩn hóa → phát hiện trùng/thay đổi → sinh viên xác nhận → Rule cập nhật lịch. | Đủ vì chuỗi bước và điểm rẽ nhánh đã biết trước; AI chỉ xử lý ngôn ngữ và hỗ trợ so khớp. | Sai ngày, môn hoặc phiên bản có thể đi tiếp qua nhiều bước nếu thiếu review; cần log nguồn và cơ chế hoàn tác. | **Chọn làm mức tổng thể**, với human boundary trước mọi thay đổi lịch. |
| **Agent** | Tự truy cập nhiều hệ thống, quyết định nguồn nào cần kiểm tra, hỏi thêm, sửa lịch và điều chỉnh kế hoạch học tập. | Chỉ cần nếu hệ thống phải tự lập kế hoạch, chọn công cụ và xử lý nhiều nhánh chưa biết trước. | Quyền truy cập rộng, hành vi khó dự đoán và nguy cơ tự sửa deadline sai; khó audit trong scope lab. | Không chọn; bài toán chưa cần tự chủ ở mức Agent. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule chưa giải được 70-80% toàn bộ case vì chỉ đáng tin với LMS/calendar có cấu trúc, trong khi email và nhóm chat có cách diễn đạt và cập nhật không cố định.
2. Workflow có một đường chính cố định nhưng rẽ nhánh tại loại input có cấu trúc/không cấu trúc và tại trường hợp xung đột hoặc độ tin cậy thấp.
3. Không cần Agent tự lập kế hoạch hoặc tự chọn tool; các nguồn, schema, thứ tự xử lý và điểm review đều có thể cấu hình trước.
4. Sinh viên là người phát hiện đầu tiên tại màn hình review bằng cách so với đoạn trích và link nguồn; mục tiêu là sửa trong cùng batch, không quá 2 phút trước khi lịch được ghi.
5. Có thể hạ từ Agent xuống Workflow ngay; với môn học có calendar feed chuẩn, nhánh đó còn có thể hạ tiếp xuống Rule.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn Workflow vì bài toán có nhiều nguồn và nhiều bước phụ thuộc nhau nhưng đường xử lý có thể xác định trước. Rule đảm nhiệm dữ liệu có cấu trúc và cập nhật lịch, AI chỉ trích xuất/so khớp ngôn ngữ tự nhiên, còn sinh viên xác nhận trước khi ghi. Cách này giảm thao tác lặp lại mà vẫn giữ được nguồn tham chiếu, khả năng audit và quyền quyết định cuối ở người dùng. Agent không cần thiết vì hệ thống không phải tự lập kế hoạch hay tự chọn hành động tiếp theo ngoài workflow đã định nghĩa.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule đơn thuần chưa đủ cho email/chat không có schema và các câu cập nhật như “lùi bài thêm hai ngày” vốn cần hiểu ngữ cảnh. Tuy vậy, từng nhánh có input/output rõ nên nhóm dùng Rule ở nơi có cấu trúc và chỉ thêm AI ở bước ngôn ngữ, thay vì nâng toàn bộ hệ thống thành Agent.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học quản lý deadline bài tập, quiz, thuyết trình và lịch kiểm tra của nhiều môn, với thông báo đến từ LMS, email, nhóm chat, giảng viên hoặc tài liệu môn học. Người dùng cuối đồng thời là owner chịu trách nhiệm xác nhận thay đổi lịch. |
| **Workflow** | Current: nhận thông báo → đọc/trích xuất → đối chiếu phiên bản → nhập lịch → sửa khi thay đổi → rà soát kênh → có thể phát hiện sát hạn. Future: thu nhận → Rule/AI trích xuất → chuẩn hóa → so khớp/xử lý xung đột → sinh viên xác nhận → Rule cập nhật lịch và reminder. |
| **Bottleneck** | Sinh viên phải đối chiếu thông báo trên 3-4 nguồn để xác định deadline mới nhất, rồi cập nhật đúng bản ghi cũ. Đây là bước tốn công nhận thức và tạo rủi ro bỏ sót cao hơn thao tác nhập lịch đơn thuần. |
| **Impact** | Baseline sơ bộ là khoảng 10 phút/ngày, tương đương khoảng 70 phút/tuần, cho việc kiểm tra và tổng hợp. Khi workflow bị gián đoạn, deadline có thể chỉ được phát hiện khi gần hạn, làm giảm thời gian chuẩn bị. |
| **Success Metric** | Trong pilot 2 tuần: thời gian trung bình không quá 3 phút/ngày; 0 deadline bị bỏ sót trong các nguồn được theo dõi; ít nhất 90% trường tên việc, môn và deadline được AI trích đúng trước khi người dùng sửa. Đồng thời theo dõi tỷ lệ mục cần sửa và số lần hoàn tác để không đánh đổi tốc độ bằng độ chính xác. |
| **Boundary** (làm / không làm) | Làm: thu nhận từ nguồn được cấp quyền, trích xuất dữ liệu deadline, gắn link nguồn, phát hiện trùng/thay đổi, xin xác nhận rồi cập nhật lịch học tập tập trung. Không làm: tự ghi khi chưa xác nhận, tự nộp bài, tự lập kế hoạch học, đọc nguồn ngoài quyền cho phép hoặc quản lý lịch cá nhân ngoài học tập. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | AI can thiệp sau khi thông báo không cấu trúc từ email/chat được thu nhận và trước khi sinh viên review. AI chỉ đề xuất trường dữ liệu và khả năng bản ghi mới thay thế bản ghi cũ; không có quyền commit vào calendar. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Workflow:** phối hợp Rule cho thao tác xác định, AI cho ngôn ngữ không cấu trúc và sinh viên cho quyết định cuối trong một chuỗi bước cố định. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI trích sai ngày hoặc coi nhầm một thông báo cũ là bản mới. Sinh viên kiểm tra đoạn trích, timestamp và link nguồn tại bước review; mục xung đột bị chặn, mọi thay đổi được ghi log và có thể hoàn tác. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor là sinh viên đại học; current workflow 7 bước và future workflow 6 bước đã chỉ rõ input, output, actor, bottleneck và handoff. |
| Baseline + metric đo được chưa? | Yes | Có baseline sơ bộ khoảng 10 phút/ngày và 3-4 kênh; pilot sẽ đo thời gian, tỷ lệ trích xuất đúng và số deadline bị bỏ sót theo cùng một cách trong 2 tuần. |
| Data/input đủ dùng chưa? | Yes | Có thể bắt đầu bằng 20-30 thông báo lịch sử đã ẩn dữ liệu nhạy cảm và các notification mới từ LMS, email hoặc chat do người tham gia chủ động cung cấp. |
| AI sai, hậu quả chấp nhận được không? | Yes | Hậu quả chấp nhận được trong pilot vì AI chỉ tạo đề xuất; sinh viên phải xác nhận trước khi ghi và có thể hoàn tác mọi thay đổi. |
| Có người review/owner không? | Yes | Mỗi sinh viên là owner của lịch mình và chịu trách nhiệm review các mục mới, thay đổi hoặc xung đột. |
| Có cách non-AI đơn giản hơn không? | Yes | Calendar feed, checklist và reminder theo Rule được dùng cho nguồn có cấu trúc; AI chỉ bổ sung cho email/chat mà Rule không xử lý ổn định. |

**Decision:**

```text
Go với pilot nhỏ, có human-in-the-loop.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Nhóm chọn Go vì actor, current workflow và điểm nghẽn đối chiếu deadline đa nguồn đã xác định rõ, đồng thời có baseline thời gian và metric để kiểm tra hiệu quả. Research cho thấy calendar feed và reminder có thể xử lý phần có cấu trúc, còn AI được giới hạn ở bước trích xuất/so khớp thông báo không cấu trúc. Pilot có rủi ro thấp vì AI không tự ghi lịch, sinh viên xác nhận bằng nguồn gốc trước mọi thay đổi và hệ thống có cơ chế hoàn tác. Kết quả pilot sẽ quyết định giữ AI cho nhánh email/chat hay hạ nhánh đó về nhập tay.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Trong 2 tuần, chạy với 3-5 sinh viên và 20-30 thông báo đã ẩn dữ liệu nhạy cảm từ 3-4 kênh. Giai đoạn đầu dùng workflow bán thủ công: người dùng forward/paste thông báo, Rule nhập dữ liệu có cấu trúc, AI đề xuất các trường và bản ghi liên quan, sinh viên xác nhận rồi Rule ghi lịch. Đo ba số chính: (1) phút/người/ngày, (2) tỷ lệ trường tên việc-môn-deadline đúng trước khi sửa, và (3) số deadline hoặc thay đổi bị bỏ sót; ghi thêm tỷ lệ mục phải sửa/hoàn tác để phân tích lỗi.
```


**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng nhánh AI và quay về calendar feed + nhập tay nếu có bất kỳ deadline sai nào được ghi mà chưa qua xác nhận, nếu độ chính xác trích xuất dưới 90%, nếu workflow vẫn tốn trên 5 phút/ngày sau 2 tuần, hoặc nếu có deadline thuộc nguồn theo dõi bị bỏ sót. Khi rollback, vô hiệu hóa bước AI/auto-write, giữ log và bản sao lịch gần nhất, hoàn tác các mục sai, rồi đối soát lại với nguồn gốc trước khi tiếp tục dùng Rule-only.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
