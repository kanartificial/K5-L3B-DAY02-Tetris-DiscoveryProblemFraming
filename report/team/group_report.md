# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Tetris
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Giảng viên/TA phải rà soát sơ bộ thủ công định dạng và tiêu chí rubric của bài tập lớn/tiểu luận trước khi đọc sâu nội dung, trong khi sinh viên vẫn thường nộp bài còn lỗi quy cách hoặc sót tiêu chí.
- Quyết định cuối: **Not Yet**

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | KimY | Khi làm bài tập nhóm nhưng có thành viên thường xuyên chậm tiến độ, tôi muốn biết rõ tình trạng công việc và những khó khăn của từng người để tránh ảnh hưởng đến deadline chung |  Nhóm trưởng, thành viên nhóm| Nhóm trưởng phải liên tục hỏi tiến độ từng thành viên, chờ phản hồi và tổng hợp thông tin thủ công; khó biết nguyên nhân chậm tiến độ.| |
| 2 | KimY| Khi có một vấn đề, nghiên cứu mà tôi cảm thấy mới và quan tâm, tôi cần tìm hiểu, đọc các bài báo liên quan để rút ra insight cho bản thân | Sinh viên| Mất nhiều thời gian tìm kiếm, chọn lọc, đọc hiểu và tổng hợp tài liệu. Lần gần nhất mất khoảng 3 tiếng.| |
| 3 | Thao | Sinh viên mất nhiều thời gian tìm kiếm, đọc và tổng hợp thông tin từ nhiều tài liệu khác nhau khi làm bài tập, tiểu luận và nghiên cứu. | Sinh viên | Bước 2, 3, 4 và 6: mất nhiều thời gian tìm kiếm, đọc hiểu, xác định thông tin quan trọng và đối chiếu giữa các tài liệu; chưa có số liệu đo cụ thể. | |
| 4 | Thao | Sinh viên gặp khó khăn khi quản lý nhiều deadline và sắp xếp thứ tự ưu tiên các nhiệm vụ từ nhiều môn học. | Sinh viên| Bước 2, 3, 4 và 5: mất thời gian tổng hợp deadline từ nhiều nguồn, ước lượng khối lượng công việc và xác định việc cần ưu tiên; chưa có số liệu đo cụ thể. | |
| 5 | Thao | Sinh viên gặp khó khăn trong việc phối hợp và theo dõi tiến độ khi làm bài tập nhóm do các thành viên cập nhật thông tin không đồng đều.| Sinh viên | Bước 4, 5 và 6: thông tin tiến độ phân tán ở nhiều nhóm chat và tài liệu; nhóm trưởng phải chủ động nhắc nhở, kiểm tra và tổng hợp; chưa có số liệu đo cụ thể. | |
| 6 | Tran | Khi chấm bài tập lớn/tiểu luận của 40–50 sinh viên, tôi muốn rà soát nhanh tính hợp lệ của bài nộp (đúng cấu trúc, đủ mục yêu cầu, trích dẫn chuẩn), để dành thời gian nhận xét sâu về nội dung | Giảng viên, TA | Bước 2, 3, 4 (kiểm tra định dạng, mục lục và trích dẫn): khoảng 7–8 phút/bài | |
| 7 | Tran | Khi sinh viên bắt đầu làm bài tập lớn/đồ án, tôi muốn trả lời nhanh các thắc mắc về quy định nộp bài và tiêu chuẩn trình bày, để không phải lặp lại cùng một câu trả lời trên kênh chat lớp | TA | Bước 3 và 4 (tra cứu đề cương 20+ trang và soạn câu trả lời): 4–5 phút/câu hỏi, lặp lại 15–20 lần/tuần | |
| 8 | Tran | Khi chuẩn bị tài liệu cho nghiên cứu/tiểu luận, tôi muốn đọc hiểu và trích xuất luận điểm chính từ 5–7 bài báo khoa học tiếng Anh, để viết phần tổng quan tài liệu kịp tiến độ nhóm | Sinh viên | Bước 3 (đọc chi tiết, dịch và hiểu phương pháp, kết quả): 90–120 phút/bài báo | |
| 9 | Anh | Khi cần reproduce kết quả của một paper, tôi muốn tái hiện được điều kiện thí nghiệm và kết quả đã báo cáo, để có baseline đáng tin cậy cho nghiên cứu tiếp theo | RA, research student | Thiết lập môi trường và cấu hình (2–8 giờ); debug và điều chỉnh (4–16 giờ thao tác) | |
| 10 | Anh | Khi một thí nghiệm không đạt kết quả mong đợi, tôi muốn xác định nguyên nhân đến từ implementation, dữ liệu hay giả thuyết nghiên cứu, để quyết định có nên tiếp tục hướng thử nghiệm đó | RA, research student | Đọc code, logs và so sánh các lần chạy (1–4 giờ); đưa ra giả thuyết (30 phút–1,5 giờ); chạy thí nghiệm kiểm chứng (1–4 giờ thao tác) | |
| 11 | Anh | Khi mới tham gia một dự án nghiên cứu chưa có kiến thức nền tảng, tôi muốn hiểu các khái niệm và công trình tiền đề, để đọc hiểu được các paper chính và bắt đầu đóng góp | Research student mới | Tìm tài liệu nền tảng (2–5 giờ); học kiến thức tiền đề (12–35 giờ); đọc và hiểu paper chính (4–10 giờ) | |
| 12 | KimY| Khi bắt đầu một tuần học mới, tôi muốn nắm được tất cả bài tập, deadline và lịch báo cáo của các môn để không bỏ sót nhiệm vụ quan trọng| Sinh viên| Phải kiểm tra thông tin từ nhiều nguồn như nhóm chat, thông báo giảng viên và hệ thống học tập rồi tổng hợp thủ công.| |

### 2.2. Cluster


| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A. Tìm kiếm và khai thác tri thức | #2, #3, #8, #9, #10 | Sinh viên mất nhiều thời gian tìm kiếm, đọc hiểu, tổng hợp và khai thác thông tin từ tài liệu khoa học; gặp khó khăn khi tái hiện hoặc kiểm chứng kết quả nghiên cứu. |
| B. Quản lý và hoàn thành nhiệm vụ học tập | #4, #6, #7, #11, #12 | Sinh viên gặp khó khăn trong việc nắm bắt yêu cầu, quy định, xây dựng nền tảng kiến thức và tổ chức công việc để hoàn thành bài tập đúng yêu cầu. |
| C. Phối hợp và theo dõi công việc nhóm | #1, #5 | Sinh viên khó nắm bắt tiến độ, tình trạng và khó khăn của từng thành viên, dẫn đến phối hợp thiếu hiệu quả và nguy cơ trễ deadline chung. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian rà soát, đối chiếu và hoàn thiện bài tập lớn/tiểu luận theo rubric môn học mà chất lượng phản hồi không đổi
├── Opportunity A: Sinh viên gặp khó khăn khi đối chiếu bài làm với các quy định định dạng và tiêu chí chấm (rubric) dài nhiều trang, dẫn đến nộp sai quy cách (#6, #7)
├── Opportunity B: Mất nhiều thời gian tìm kiếm, đọc hiểu và trích xuất thông tin chuẩn xác từ các tài liệu khoa học/bài báo để đưa vào bài (#2, #3, #8)
└── Opportunity C: Người chấm (TA/Giảng viên) mất quá nhiều thời gian kiểm tra các lỗi hình thức cơ học (font, lề, số trang, mục lục, trích dẫn) trước khi đọc nội dung thật (#6)
     ✗ "Tool AI tự động viết và hoàn thiện bài tiểu luận"       ← solution, gạch bỏ khỏi tầng này
     ✗ "Chatbot AI chấm điểm tự động thay thế trợ giảng"         ← solution, gạch bỏ khỏi tầng này
     ✗ "Phần mềm OCR tự động sửa lỗi định dạng bài nộp"         ← solution, gạch bỏ khỏi tầng này
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- *"Tool AI tự động viết và hoàn thiện bài tiểu luận":* Đây là giải pháp công nghệ mang tính "solution-first" và vi phạm liêm chính học thuật; bản chất nhu cầu thật (opportunity) là sinh viên cần nắm bắt nhanh cấu trúc yêu cầu và trích xuất thông tin tham khảo đúng trọng tâm.
- *"Chatbot AI chấm điểm tự động thay thế trợ giảng":* Đây là công cụ công nghệ; bản chất nhu cầu thật là giảm tải các bước kiểm tra quy cách cơ học (checklist định dạng, đủ mục rubric) để người chấm tập trung vào đánh giá lập luận.
- *"Phần mềm OCR tự động sửa lỗi định dạng bài nộp":* Đây là tính năng phần mềm can thiệp trực tiếp vào sản phẩm của sinh viên; bản chất nhu cầu thật là sinh viên và người chấm cần một cơ chế đối soát nhanh để biết bài nộp đã khớp với tiêu chuẩn của đề tài hay chưa.

### 2.4. Chấm điểm shortlist (1–5)

| # | Candidate (Tóm tắt) | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 6 | Rà soát sơ bộ định dạng & tiêu chí bài tập lớn| 4 | 5 | 4 | 4 | 5 | 5 | 5 | **32** |
| 3 | Tìm kiếm, đọc hiểu và tổng hợp tài liệu| 5 | 4 | 4 | 4 | 5 | 5 | 5 | **32** |
| 7 | Giải đáp thắc mắc lặp lại về quy chế đồ án| 4 | 5 | 4 | 4 | 4 | 4 | 5 | **30** |


**Candidate được chọn:**

- **#6 — Rà soát sơ bộ định dạng và tiêu chí bài tập lớn.**

**Vì sao chọn:**

- Có Actor rõ ràng: giảng viên/TA trực tiếp rà soát bài nộp; sinh viên thực hiện bài tập lớn, tiểu luận là bên chịu ảnh hưởng.
- Quy trình cụ thể: tiếp nhận yêu cầu, đối chiếu định dạng, kiểm tra tiêu chí và phát hiện nội dung chưa đáp ứng.
- Pain point có tính thực tiễn: người chấm mất thời gian kiểm tra các yêu cầu cơ học lặp lại; sinh viên có thể mất thời gian đối chiếu nhiều tiêu chí và vẫn bỏ sót yêu cầu.
- Có khả năng đo lường hiệu quả thông qua thời gian rà soát và số lỗi hoặc tiêu chí bị bỏ sót.
- Phù hợp với phạm vi triển khai của lab, có thể so sánh giữa phương pháp thủ công, Rule-based và AI Workflow.
- Có tiềm năng ứng dụng AI để hỗ trợ đọc hiểu yêu cầu, kiểm tra tài liệu và chỉ ra những điểm chưa đáp ứng tiêu chí.

**Vì sao loại các candidate còn lại:**

- **#3 — Tìm kiếm, đọc hiểu và tổng hợp tài liệu:** Có tiềm năng ứng dụng AI cao nhưng phạm vi rộng, dễ trùng lặp với các công cụ AI hỗ trợ nghiên cứu hiện có. Cần giới hạn rõ hơn phạm vi tài liệu và đầu ra.
- **#7 — Giải đáp thắc mắc về quy chế đồ án:** Có quy trình và Actor rõ ràng nhưng phạm vi nội dung tương đối hẹp, có thể giải quyết bằng hệ thống tra cứu tài liệu hoặc chatbot RAG đơn giản.

**Xử lý bất đồng (nếu có):** Nhóm từng bất đồng giữa hai candidate cùng 32 điểm: "Tìm kiếm, đọc hiểu và tổng hợp tài liệu" và "Rà soát sơ bộ định dạng và tiêu chí bài tập lớn". Sau khi thảo luận, nghiên cứu và đánh giá lại, nhóm chốt candidate "Rà soát sơ bộ định dạng và tiêu chí bài tập lớn".

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên thường xuyên mắc lỗi định dạng hoặc bỏ sót tiêu chí trong rubric khi làm bài tập lớn, tiểu luận.| Value| 5|1 | Có |
| 2 |  Những lỗi này gây hậu quả đáng kể như mất điểm, phải chỉnh sửa nhiều lần hoặc nộp muộn. | Value| 5 | 1 | Có |
| 3 | Sinh viên mất nhiều thời gian tự đối chiếu bài làm với rubric nhưng vẫn dễ bỏ sót lỗi. | Value | 4 |1  | Có |
| 4 | Các yêu cầu định dạng và rubric đủ rõ ràng để xác định bài làm có đáp ứng tiêu chí hay không một cách khách quan. | Feasibility | 5 | 1 | Có |
| 5 | Các phương pháp hiện tại như checklist, template hoặc công cụ kiểm tra có sẵn chưa giải quyết đủ tốt vấn đề. | Viability | 4 | 1 | Có |
| 6 | Sinh viên sẵn sàng dành thời gian kiểm tra và chỉnh sửa bài trước khi nộp nếu việc kiểm tra mang lại giá trị rõ ràng.| Value | 4 | 1 | Sau #1–#5 |

Giả định nhóm kiểm chứng trong buổi này: **Giả định #1, #2, #3, #4 và #5** (các giả định có mức độ quan trọng cao 4–5 và mức độ bằng chứng hiện tại thấp 1/5).

### 3.2. Kiểm chứng

Cách đã dùng: **Survey (Khảo sát trực tuyến qua Google Forms với mẫu N = 20 sinh viên) kết hợp Phỏng vấn sâu (The Mom Test)**. Bảng tổng hợp: [cp4-survey-result.md](../assets/cp4-survey-result.md); dữ liệu gốc: [cp4-survey-result.xlsx](../assets/cp4-survey-result.xlsx).

#### 1. Kết quả phân tích số liệu thực tế từ khảo sát (N = 20 sinh viên)

* **Đối tượng khảo sát (Câu 1 & 2):**
  - **Cơ cấu năm học:** 50% sinh viên Năm 3–4 (10 bạn); 25% sinh viên Năm 1–2 (5 bạn); 25% sinh viên đang làm đồ án tốt nghiệp (5 bạn).
  - **Khối lượng bài tập lớn/học kỳ:** 50% làm 1–2 bài/kỳ (10 bạn); 45% làm 3–5 bài/kỳ (9 bạn); 5% làm trên 5 bài/kỳ (1 bạn).
* **Tỷ lệ từng bị phạt/nhắc nhở lỗi hình thức, quy cách (Câu 3 - Xác nhận Giả định #1 & #2):**
  - **95% sinh viên (19/20 bạn)** xác nhận **từng bị trừ điểm hoặc bị nhắc nhở** vì các lỗi hình thức/quy cách (chỉ duy nhất 1 bạn chưa từng bị).
  - **Top các lỗi quy cách phổ biến nhất:**
    1. *Sai quy chuẩn trích dẫn nguồn (citation) / danh mục tài liệu tham khảo:* **65% (13/20 bạn)** gặp phải.
    2. *Đánh số hình ảnh, bảng biểu không đúng chuẩn hoặc thiếu danh mục:* **65% (13/20 bạn)** gặp phải.
    3. *Sai font chữ, cỡ chữ, giãn dòng, căn lề trang:* **55% (11/20 bạn)** gặp phải.
    4. *Đặt tên file nộp bài sai cấu trúc yêu cầu của giảng viên/hệ thống:* **55% (11/20 bạn)** gặp phải.
    5. *Sai quy cách trang bìa, thiếu lời cam đoan/thông tin đề tài:* **35% (7/20 bạn)** gặp phải.
* **Tỷ lệ nộp bài xong mới phát hiện bỏ sót tiêu chí Rubric (Câu 4 - Xác nhận Giả định #1 & #3):**
  - **90% sinh viên (18/20 bạn)** từng rơi vào cảnh nộp bài xong mới biết nhóm mình bỏ sót yêu cầu/tiêu chí trong rubric (trong đó **40% bị thường xuyên** ở hầu hết các kỳ học; **50% bị thỉnh thoảng** 1–2 lần).
  - Chỉ có **10% (2 bạn)** chưa từng bị sót tiêu chí.
* **Cách rà soát hiện tại (Workaround - Câu 5 - Kiểm chứng Giả định #3 & #5):**
  - **65% (13 bạn):** Tự đọc lướt bằng mắt từ đầu đến cuối file Word/PDF.
  - **60% (12 bạn):** Phân công 1 bạn trong nhóm làm nhiệm vụ "soát lỗi" thủ công trước giờ nộp.
  - **20% (4 bạn):** Dùng công cụ kiểm tra chính tả/ngữ pháp (Grammarly, LanguageTool).
  - **10% (2 bạn):** Dán nội dung vào ChatGPT/Claude để hỏi chung chung.
  - *Nhận xét:* Câu hỏi cho phép chọn nhiều đáp án. Hai cách phổ biến nhất đều là rà soát thủ công (65% và 60%), trong khi công cụ kiểm tra và chatbot AI chỉ được dùng ở mức 20% và 10%. Điều này phù hợp với tình trạng sinh viên vẫn thường xuyên sót lỗi.
* **Đánh giá mức độ rõ ràng của Rubric nhận được (Câu 6 - Thang 1–5 - Phản biện Giả định #4):**
  - Điểm trung bình: **3,05 / 5**.
  - Đáng chú ý: **40% sinh viên (8/20 bạn)** đánh giá độ rõ ràng ở mức thấp (điểm 1 và 2). Điều này bác bỏ một phần Giả định #4: rubric thực tế thường không đủ rõ ràng hoặc quá dài dòng, khiến sinh viên rất khó tự đối chiếu một cách khách quan.

---

#### 2. Interview snapshot (Trích xuất trường hợp điển hình từ khảo sát)

> Xem bản ghi chép chi tiết tại: [report/assets/cp4-interview-snapshot-1.md](../assets/cp4-interview-snapshot-1.md)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên Năm 3 (làm 3–5 bài tập lớn/tiểu luận mỗi kỳ, thường xuyên làm việc nhóm) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Nhiều khi cả nhóm thức trắng đêm làm nội dung, đến sát giờ nộp mới cuống cuồng phân công một bạn đọc lướt lại toàn bộ file 30 trang. Cứ đinh ninh đủ bài rồi, đến lúc thầy chấm trả điểm mới biết nhóm quên mất tiêu chí danh mục hình ảnh và bị trừ mất 0.5 điểm oan."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Đợt nộp báo cáo tiểu luận giữa kỳ môn Cơ sở dữ liệu nâng cao (cách đây 3 tuần) |
| Hiện đang xử lý bằng cách nào (workaround)? | Phân công 1 bạn trong nhóm làm nhiệm vụ "soát lỗi cơ học" trước giờ nộp 30–45 phút; bạn này mở file PDF/Word và đối chiếu đề cương bằng mắt |
| Mất bao lâu, bao lần? | Mất 45–60 phút cho mỗi bài báo cáo (20–35 trang); mỗi học kỳ có 3–4 đợt nộp dồn dập vào tuần 8 và tuần 15 |
| Insight / opportunity rút ra | Sinh viên rất cần một cơ chế tự động đối soát nhanh file bài làm với rubric (kiểm tra font, lề, số bảng hình, chuẩn trích dẫn) để phát hiện sớm các thiếu sót trước khi submit chính thức |

---

#### 3. Tổng hợp

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Khảo sát thực tế Google Forms | 20 sinh viên (Năm 1–2: 5, Năm 3–4: 10, Đồ án tốt nghiệp: 5) | • **Xác nhận Giả định #1, #2, #3:** 95% (19/20) từng bị trừ điểm hoặc nhắc nhở vì lỗi hình thức (trích dẫn 65%, bảng hình 65%); 90% (18/20) nộp bài xong mới biết sót tiêu chí rubric.<br>• **Xác nhận Giả định #5:** 65% tự đọc lướt và 60% giao 1 bạn soát thủ công; các công cụ sinh viên đang dùng như Grammarly, LanguageTool chủ yếu để kiểm tra chính tả, ngữ pháp, chưa thay thế bước đối soát rubric. Tuy nhiên, Grammarly AI Grader đã có tính năng đối chiếu với rubric (xem mục 3.3), nên giả định này mới được xác nhận một phần. | • **Phản biện Giả định #4:** Có tới 40% sinh viên chấm điểm rubric ở mức 1–2 (kém rõ ràng). Do đó không thể giả định rubric luôn chuẩn hóa, hệ thống cần có bước trích xuất/làm rõ rubric trước khi kiểm tra bài.<br>• 1 sinh viên (5%) chưa từng bị trừ điểm vì các lỗi hình thức được liệt kê; 2 sinh viên (10%) chưa bao giờ sót tiêu chí rubric. |

---

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
- **Mở rộng góc nhìn giá trị:** Ban đầu nhóm chỉ nhìn bài toán từ phía áp lực của **Trợ giảng / Giảng viên** (mất 8 phút/bài kiểm tra cơ học). Dữ liệu khảo sát 20 sinh viên chứng minh **phía người học cũng chịu ảnh hưởng rõ rệt**: 90% nộp bài xong mới biết sót tiêu chí rubric, 95% từng bị trừ điểm hoặc nhắc nhở vì lỗi quy cách.
- **Xác định rõ phạm vi can thiệp (Boundary):**
  - Công cụ **tập trung đúng vào các lỗi hình thức có tỷ lệ vi phạm cao nhất theo khảo sát:** trích dẫn chuẩn APA/IEEE (65%), danh mục bảng/hình (65%), quy chuẩn font/lề (55%) và đối chiếu đủ mục rubric (90% từng bỏ sót).
  - Giữ vững nguyên tắc: **Không can thiệp vào việc chấm nội dung hay cho điểm**, mà đóng vai trò là **bảng kiểm tra tính hợp lệ & đối chiếu rubric (Compliance Checklist)** phục vụ cả sinh viên trước khi nộp lẫn người chấm khi thu bài.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Microsoft Word Editor | [Microsoft Editor](https://support.microsoft.com/en-us/word/check-grammar-spelling-and-more-in-word-for-the-web) | Rà soát chính tả, ngữ pháp, cách diễn đạt | Tích hợp trong Word, hỗ trợ sửa lỗi viết | Không phải công cụ chuyên kiểm tra toàn bộ rubric riêng của từng môn | Phân biệt lỗi ngôn ngữ với lỗi tuân thủ tiêu chí |
| Grammarly AI Grader | [Grammarly AI Grader](https://support.grammarly.com/hc/en-us/articles/38552360525837-AI-Grader-user-guide) | Đối chiếu bài viết với rubric, đưa phản hồi trước khi nộp | Cho phép cung cấp rubric, nhận gợi ý theo tài liệu và đoạn văn | Điểm dự đoán không phải điểm chính thức; một số tính năng phụ thuộc gói dịch vụ | Cần nghiên cứu kỹ mức độ khác biệt so với công cụ đã có |
| Turnitin Feedback Studio | [Turnitin Rubric](https://guides.turnitin.com/hc/en-us/articles/23859968188429-Reviewing-your-grade-and-rubric) | Xem tiêu chí rubric và phản hồi đánh giá | Rubric gắn với tiêu chí giảng viên sử dụng | Chủ yếu phục vụ quy trình đánh giá và phản hồi, không đồng nghĩa với kiểm tra trước nộp tự động | Nên gắn kết quả kiểm tra với từng tiêu chí cụ thể |
| Grammarly Plagiarism Checker | [Plagiarism Checker](https://support.grammarly.com/hc/en-us/articles/115000091452-Plagiarism-Checker-user-guide) | Kiểm tra tương đồng nội dung và rủi ro trích dẫn | Hỗ trợ rà soát nguồn và thông tin trích dẫn | Không trực tiếp xác minh toàn bộ yêu cầu cấu trúc, định dạng và nội dung rubric | Không đánh đồng kiểm tra đạo văn với kiểm tra rubric |


---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```
HIỆN TẠI — 21 phút/bài (Tổng ~15,75 tiếng cho lớp 45 sinh viên)

[1. Tải bài: 1'] → [2. Kiểm tra format: 3'] → [3. Soát đủ mục rubric: 3'] → [4. Soát trích dẫn: 2'] 
                   └────────────────── BOTTLENECK CƠ HỌC: 8' ──────────────────┘
→ [5. Đọc sâu nội dung & lập luận: 9'] → [6. Viết nhận xét & nhập điểm: 3']

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Giảng viên | Bài làm của sinh viên được nộp dưới dạng file Word/PDF | File bài làm được tải về và sẵn sàng kiểm tra | 1 phút/bài | Thực hiện với từng bài nộp |
| 2 | Giảng viên | File bài làm | Xác định lỗi định dạng như font chữ, căn lề, giãn dòng, đánh số trang | 3 phút/bài | Kiểm tra thủ công theo yêu cầu của đề bài |
| 3 | Giảng viên | File bài làm và rubric/chỉ dẫn bài tập | Danh sách các mục đã đáp ứng hoặc còn thiếu | 3 phút/bài | Phải đối chiếu từng tiêu chí trong rubric |
| 4 | Giảng viên | Nội dung bài làm và quy định trích dẫn | Phát hiện các lỗi hoặc điểm chưa phù hợp trong trích dẫn | 2 phút/bài | Kiểm tra cách trích dẫn và danh mục tài liệu tham khảo |
| 5 | Giảng viên | Bài làm đã qua bước rà soát sơ bộ | Đánh giá về nội dung và lập luận của bài làm | 9 phút/bài | Cần đánh giá chuyên môn, không thể chỉ dựa vào kiểm tra hình thức |
| 6 | Giảng viên | Kết quả đánh giá và nhận xét | Nhận xét hoàn chỉnh và điểm số được nhập vào hệ thống | 3 phút/bài | Tổng hợp nhận xét và nhập điểm cho sinh viên |


*Ghi chú: "Giảng viên" trong các bảng quy trình bao gồm cả TA được phân công chấm bài.*

**Bottleneck chính:**
- Giảng viên mất nhiều thời gian cho các thao tác rà soát thủ công, lặp đi lặp lại như kiểm tra định dạng, đối chiếu rubric và kiểm tra trích dẫn.
- Ba thao tác này chiếm tổng cộng **8 phút/bài (38,1% tổng thời gian)**, tương đương **6 tiếng với 45 sinh viên**.
- Việc phải kiểm tra từng tiêu chí bằng tay dễ dẫn đến bỏ sót lỗi, thiếu nhất quán giữa các bài và làm tăng khối lượng công việc của giảng viên.
- Đây là công đoạn có tiềm năng ứng dụng AI và Rule-based để tự động rà soát sơ bộ, phát hiện lỗi và đưa ra cảnh báo. Giảng viên vẫn chịu trách nhiệm đọc sâu nội dung, đánh giá lập luận và quyết định điểm số cuối cùng.


### 4.2. Quy trình tương lai

```text
TƯƠNG LAI — khoảng 16 phút/bài (Tổng ~12 tiếng cho lớp 45 sinh viên, tiết kiệm 3,75 tiếng)

[1. Tải bài nộp & rubric vào hệ thống: 1']                                 ← CON NGƯỜI
→ [2. Quét tự động và xuất Compliance Checklist: 1']
      - Font, lề, số trang, bảng/hình; tổng hợp báo cáo                    ← RULE
      - Đối chiếu cấu trúc với rubric, rà soát trích dẫn                   ← AI
→ [3. Giảng viên/TA xác minh cảnh báo với bài gốc: 2']                     ← CON NGƯỜI (HITL)
→ [4. Đọc sâu nội dung & lập luận học thuật: 9']                           ← CON NGƯỜI
→ [5. Viết nhận xét chuyên môn & nhập điểm chính thức: 3']                 ← CON NGƯỜI (Quyết định điểm số 100%)

BOUNDARY:
- AI tuyệt đối KHÔNG tự cho điểm, không đánh giá độ hay/dở của lập luận học thuật, không tự ý gửi điểm hoặc phản hồi cho sinh viên.
- Mọi cảnh báo lỗi về rubric hay trích dẫn bắt buộc phải trích xuất kèm số trang, vị trí đoạn văn cụ thể để con người kiểm chứng được ngay.

PHƯƠNG ÁN QUAY VỀ (FALLBACK):
- Khi file bị mã hóa, lỗi font không parse được, hoặc AI đưa ra độ tin cậy thấp (<80% confidence): Hệ thống tự động gắn nhãn [Cần kiểm tra thủ công].
- Giảng viên/TA bỏ qua bước checklist, mở file gốc và đối chiếu rubric thủ công bằng mắt theo quy trình cũ.
```


| Bước | Actor           | Input                                                    | Output                                                                                            | Thời gian / tần suất | Ghi chú                                                                                                                                                                             |
| ---- | --------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Giảng viên      | Bài làm của sinh viên dưới dạng Word/PDF                 | File được tải lên và sẵn sàng kiểm tra                                                            | 1 phút/bài           | Giảng viên chọn bài làm và rubric tương ứng.                                                                                                                                        |
| 2    | Rule-based + AI | File bài làm, rubric và quy định định dạng, trích dẫn    | Báo cáo rà soát sơ bộ gồm lỗi định dạng, mục rubric có thể bị thiếu và bất thường trong trích dẫn | 1 phút/bài           | TỰ ĐỘNG. Rule-based kiểm tra các tiêu chí định dạng xác định được. AI hỗ trợ kiểm tra cấu trúc nội dung và trích dẫn. Các phát hiện chỉ là cảnh báo, không phải kết luận chấm điểm. |
| 3    | Giảng viên      | Báo cáo rà soát tự động và bài làm gốc                   | Danh sách lỗi đã được xác nhận hoặc loại bỏ cảnh báo sai                                          | 2 phút/bài           | Giảng viên kiểm chứng các cảnh báo, đặc biệt với tiêu chí mơ hồ hoặc yêu cầu đánh giá ngữ nghĩa.                                                                                    |
| 4    | Giảng viên      | Nội dung bài làm, rubric và kết quả rà soát đã xác minh  | Đánh giá chuyên môn về nội dung, lập luận, phương pháp và mức độ đáp ứng yêu cầu học thuật        | 9 phút/bài           | Giảng viên trực tiếp đọc sâu và đánh giá chất lượng bài làm. AI không thay thế quyết định chuyên môn.                                                                               |
| 5    | Giảng viên      | Kết quả đánh giá chuyên môn và danh sách lỗi đã xác minh | Nhận xét hoàn chỉnh và điểm số được nhập vào hệ thống                                             | 3 phút/bài           | Giảng viên tổng hợp nhận xét, quyết định điểm số cuối cùng và hoàn tất chấm bài.                                                                                                    |

**Sau cải tiến**:
- Bottleneck cơ học được rút ngắn: Các bước kiểm tra định dạng, rubric và trích dẫn trước đây mất 8 phút/bài, nay dự kiến còn 3 phút/bài (1 phút tự động và 2 phút xác minh).
- Bottleneck còn lại: Bước 4 — Đọc sâu nội dung và lập luận, chiếm 9 phút/bài (56,25% tổng thời gian). Đây là công đoạn cần đánh giá chuyên môn của giảng viên.
- Rủi ro mới: Rule-based hoặc AI có thể đưa ra cảnh báo sai hoặc bỏ sót lỗi, làm tăng thời gian xác minh.
- Boundary: AI không tự chấm điểm, không tự sửa bài làm và không thay đổi số liệu đánh giá. Giảng viên quyết định kết quả cuối cùng.
- Fallback: Khi kiểm tra tự động thất bại hoặc không đáng tin cậy, giảng viên quay về quy trình rà soát thủ công theo rubric gốc.


### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| **Số bước** | 6 bước | 5 bước | Gộp 3 bước kiểm tra thủ công thành 1 bước tự động và 1 bước xác minh |
| **Tổng thời gian** | 21 phút/bài (~15,75 tiếng/lớp 45 SV) | ~16 phút/bài (~12 tiếng/lớp 45 SV) | Giảm khoảng 24% tổng thời gian chấm; riêng khâu kiểm tra quy cách giảm 62,5% (từ 8 phút xuống 3 phút) |
| **Số bước thủ công** | 6 / 6 bước | 4 / 5 bước | Khâu đọc hiểu chuyên môn và quyết định điểm số vẫn thuộc 100% về con người |
| **Bottleneck chính** | Khâu rà soát cơ học định dạng, mục lục, trích dẫn (8 phút/bài) | Khâu đọc sâu nội dung và đánh giá lập luận (9 phút/bài) | Nút thắt chuyển sang khâu đòi hỏi chuyên môn của người chấm |
| **Rủi ro mới phát sinh** | Không có rủi ro từ AI; chủ yếu là mệt mỏi và dễ sót lỗi thủ công | AI nhận diện nhầm cấu trúc hoặc báo sai lỗi trích dẫn (False Positive/Negative); người chấm quá ỷ lại vào checklist | Xử lý bằng Boundary: AI bắt buộc dẫn chứng số trang; người chấm chỉ coi checklist là công cụ hỗ trợ rà soát sơ bộ |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Giảng viên và Trợ giảng (TA) phụ trách chấm bài tập lớn/tiểu luận môn học (từ 15 trang trở lên), cùng sinh viên thực hiện bài nộp |
| **Quy trình** | Nhận file bài làm (Word/PDF) → Kiểm tra định dạng cơ học (font, lề, số trang, danh mục bảng/hình) → Đối chiếu mục lục với các tiêu chí rubric → Rà soát chuẩn trích dẫn tài liệu tham khảo → Đọc sâu nội dung và lập luận → Viết nhận xét và nhập điểm lên hệ thống |
| **Bottleneck** | Khâu rà soát thủ công định dạng, đối chiếu danh mục rubric và kiểm tra chuẩn trích dẫn (bước 2, 3, 4) mất tới **8 phút/bài (chiếm 38,1% tổng thời gian)** |
| **Impact** | • *Người chấm:* Với lớp 45 sinh viên mất ~6 tiếng làm việc cơ học lặp đi lặp lại; áp lực deadline (3–5 ngày) dẫn đến kiệt sức, nhận xét chuyên môn bị sơ sài hoặc trễ hạn trả bài.<br>• *Người học:* Khảo sát N = 20 cho thấy 95% từng bị trừ điểm hoặc nhắc nhở vì lỗi hình thức, 90% nộp xong mới biết sót tiêu chí rubric |
| **Success Metric** (baseline → target, cách đo) | • *Baseline:* Thời gian rà soát quy cách là 8 phút/bài; tổng thời gian chấm là 21 phút/bài (ước tính của nhóm từ Problem Card, chưa bấm giờ thực tế với giảng viên/TA).<br>• *Target:* Giảm thời gian rà soát quy cách xuống dưới 2 phút/bài (giảm 75%); tổng thời gian chấm giảm xuống dưới 15 phút/bài.<br>• *Cách đo:* Bấm giờ thực tế trên mẫu thử nghiệm 20 bài trong đợt nộp bài tiếp theo |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | • AI tuyệt đối KHÔNG tự cho điểm, không đánh giá độ hay/dở của lập luận học thuật, không tự ý gửi điểm/phản hồi cho sinh viên.<br>• Mọi cảnh báo lỗi về rubric hay trích dẫn bắt buộc phải trích xuất kèm số trang, vị trí đoạn văn cụ thể.<br>• Con người (TA/Giảng viên) giữ 100% quyền duyệt nội dung và quyết định điểm số (HITL) |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- **Phản biện 1:** *"Success Metric hiện tại chỉ đo về tốc độ/thời gian, chưa đo chất lượng của việc kiểm tra (nếu làm nhanh hơn nhưng bỏ sót nhiều lỗi hơn thì sao)?"*
  - *Nhóm đồng ý:* Nhóm bổ sung tiêu chí đo chất lượng ở phiên bản v1: Tỷ lệ phát hiện đúng lỗi quy cách (Precision/Recall) phải đạt ≥ 90% so với bộ lỗi chuẩn do giảng viên/TA xác nhận.
- **Phản biện 2:** *"Có nên để AI gợi ý luôn mức điểm trừ cho từng lỗi hình thức (ví dụ: trừ 0.5 điểm nếu thiếu mục lục) không?"*
  - *Nhóm không đồng ý:* Nhóm kiên quyết giữ vững Boundary: AI chỉ đóng vai trò trích xuất bảng checklist Đạt/Chưa đạt kèm bằng chứng; việc trừ bao nhiêu điểm hoàn toàn thuộc quyền quyết định sư phạm của giảng viên.
- **Phản biện 3:** *"Impact chưa tường minh và gây hiểu nhầm. Nếu giảng viên không có thời hạn chấm bài quá gấp, tiết kiệm 5 phút/bài không nhất thiết làm tăng chất lượng feedback."*
  - *Nhóm đồng ý:* Impact ở v1 được sửa thành: "Việc dành 8 phút/bài để rà soát các yêu cầu cơ học làm tăng tổng khối lượng chấm bài. Điều này có thể ảnh hưởng đến tiến độ trả bài và thời gian dành cho đánh giá chuyên môn khi giảng viên có quỹ thời gian giới hạn."

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô: Độ mơ hồ thấp – Độ phức tạp trung bình.**

**Vì sao:**

- Độ mơ hồ thấp đối với các tiêu chí có quy định rõ ràng như font chữ, căn lề, giãn dòng, đánh số trang và cấu trúc trích dẫn. Tuy nhiên, một số tiêu chí rubric liên quan đến nội dung và mức độ đáp ứng yêu cầu có thể cần diễn giải ngữ nghĩa.
- Độ phức tạp trung bình vì hệ thống phải xử lý nhiều loại tài liệu Word/PDF, trích xuất nội dung, đối chiếu với rubric và kết hợp nhiều phương pháp kiểm tra.
- Các tiêu chí định dạng có thể xử lý bằng Rule-based, trong khi việc nhận diện cấu trúc nội dung và các dấu hiệu bất thường trong trích dẫn cần AI hỗ trợ.
- Kết quả cuối cùng vẫn cần giảng viên xác minh và đánh giá chuyên môn.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Chuẩn hóa rubric và checklist để giảng viên kiểm tra bài làm theo một quy trình thống nhất. | Khi số lượng bài ít, tiêu chí đơn giản và giảng viên có đủ thời gian kiểm tra thủ công. | Vẫn tốn thời gian, dễ bỏ sót lỗi và phụ thuộc vào người kiểm tra. | Không |
| **Rule** | Sử dụng các quy tắc cố định để kiểm tra font chữ, căn lề, giãn dòng, cấu trúc tài liệu và một số quy định trích dẫn. | Khi các tiêu chí kiểm tra có cấu trúc rõ ràng và có thể biểu diễn thành điều kiện cụ thể. | Khó hiểu ngữ cảnh, không đánh giá được cấu trúc nội dung hoặc các tiêu chí rubric mang tính ngữ nghĩa. | Không |
| **Workflow** | Kết hợp Rule-based và AI trong quy trình tự động: trích xuất tài liệu → kiểm tra định dạng bằng Rule → AI rà soát cấu trúc nội dung và trích dẫn → tạo báo cáo cảnh báo → giảng viên xác minh. | Khi quy trình có các bước cố định, đầu vào và đầu ra xác định, cần kết hợp kiểm tra theo quy tắc và xử lý ngôn ngữ tự nhiên. | AI có thể cảnh báo sai, bỏ sót lỗi hoặc hiểu sai rubric; cần cơ chế xác minh và fallback thủ công. | **Có** |
| **Agent** | AI tự phân tích tài liệu, lựa chọn cách kiểm tra, điều chỉnh chiến lược và tự thực hiện nhiều hành động để hoàn thành việc rà soát. | Khi quy trình phức tạp, thay đổi theo từng trường hợp và cần AI tự lập kế hoạch, sử dụng công cụ hoặc ra quyết định qua nhiều bước. | Khó kiểm soát, khó dự đoán kết quả, tăng chi phí và nguy cơ AI tự đưa ra kết luận không phù hợp. | Không |

**Mức chọn: Workflow**

**Vì sao không chọn mức đơn giản hơn:**

- **Không chọn No AI:** Chỉ chuẩn hóa checklist chưa giải quyết được khối lượng thao tác rà soát lặp lại. Giảng viên vẫn phải tự kiểm tra từng bài.
- **Không chọn Rule:** Rule-based phù hợp với tiêu chí định dạng có điều kiện rõ ràng nhưng chưa đủ khả năng phân tích cấu trúc nội dung, nhận diện sự thiếu hụt về mặt ngữ nghĩa hoặc kiểm tra các trường hợp trích dẫn phức tạp.
- **Workflow phù hợp nhất:** Kết hợp ưu điểm của Rule-based trong kiểm tra tiêu chí xác định và AI trong xử lý nội dung ngôn ngữ tự nhiên. Quy trình có đầu vào, đầu ra và các bước kiểm soát rõ ràng, đồng thời giữ quyền quyết định cuối cùng cho giảng viên.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Phân tích bài làm và rubric để tạo báo cáo rà soát sơ bộ: phát hiện các mục có khả năng bị thiếu, nhận diện cấu trúc nội dung chưa phù hợp và các dấu hiệu bất thường trong trích dẫn. Kết hợp với Rule-based để phát hiện lỗi định dạng. |
| **Judgment** — con người cân nhắc, quyết định gì? | Giảng viên kiểm tra tính chính xác của các cảnh báo, xác định lỗi thực tế, đánh giá chất lượng nội dung, lập luận và mức độ đáp ứng yêu cầu học thuật. |
| **Action** — hành động cuối cùng là gì, ai làm? | Hệ thống tự động tạo báo cáo rà soát. Giảng viên xác minh cảnh báo, đọc sâu bài làm, viết nhận xét và quyết định điểm số cuối cùng. |
| **Outcome** — đo kết quả bằng gì? | Tổng thời gian chấm mỗi bài (mục tiêu giảm từ 21 xuống 16 phút); thời gian kiểm tra cơ học (từ 8 xuống 3 phút); tỷ lệ phát hiện lỗi chính xác; tỷ lệ cảnh báo sai và tỷ lệ bỏ sót lỗi. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | File bài làm Word/PDF, rubric tương ứng và quy định định dạng, trích dẫn. Các dữ liệu này có sẵn từ bài nộp và tài liệu hướng dẫn của giảng viên. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Thu thập kết quả giảng viên xác nhận hoặc loại bỏ từng cảnh báo, các lỗi hệ thống bỏ sót và phản hồi về mức độ hữu ích của báo cáo. Sử dụng dữ liệu này để điều chỉnh quy tắc kiểm tra, prompt và cách xử lý của AI. |

### 6.4. Hai câu hỏi của Google PAIR

- **Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)? Bằng chứng:**

  Người dùng muốn được **hỗ trợ (augment)** thay vì giao hoàn toàn công việc cho AI. AI và Rule-based chỉ đảm nhận việc rà soát sơ bộ những tiêu chí có thể tự động hóa, giúp giảng viên giảm thời gian kiểm tra lặp lại. Giảng viên vẫn trực tiếp xác minh cảnh báo, đọc sâu nội dung, đánh giá lập luận và quyết định điểm số. Điều này được thể hiện trong quy trình tương lai khi có riêng bước 3 để giảng viên xác minh kết quả tự động và bước 4, 5 dành cho đánh giá chuyên môn và hoàn tất chấm bài.

- **AI sai kiểu nào tệ hơn, báo nhầm hay bỏ sót? Vì sao, và thiết kế đã xử lý thế nào:**

  **Bỏ sót lỗi (False Negative) nghiêm trọng hơn báo nhầm (False Positive)** vì một lỗi định dạng, thiếu tiêu chí rubric hoặc bất thường trong trích dẫn không được phát hiện có thể khiến giảng viên bỏ qua vấn đề khi rà soát sơ bộ. Tuy nhiên, báo nhầm quá nhiều cũng làm tăng thời gian xác minh và giảm niềm tin vào hệ thống.

  Thiết kế xử lý bằng cách:
  - Các phát hiện của AI chỉ là cảnh báo, không phải kết luận cuối cùng.
  - Giảng viên kiểm tra lại báo cáo với bài làm gốc và rubric trước khi xác nhận lỗi.
  - Với tiêu chí không chắc chắn hoặc khó đánh giá tự động, hệ thống đánh dấu cần kiểm tra thủ công thay vì đưa ra kết luận chắc chắn.
  - Không sử dụng kết quả AI để tự động trừ điểm hoặc thay đổi điểm số.
  - Khi hệ thống gặp lỗi, không xử lý được tài liệu hoặc kết quả không đáng tin cậy, giảng viên quay về quy trình kiểm tra thủ công theo rubric gốc.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Giảng viên và trợ giảng (TA) phụ trách chấm bài tập lớn, tiểu luận từ 15 trang trở lên. |
| **Quy trình** | 1. Nhận bài làm Word/PDF. 2. Kiểm tra định dạng (font, lề, số trang, danh mục bảng/hình). 3. Đối chiếu cấu trúc bài với rubric. 4. Kiểm tra trích dẫn và tài liệu tham khảo. 5. Đọc và đánh giá nội dung chuyên môn. 6. Viết nhận xét và quyết định điểm số. |
| **Bottleneck** | Bước 2–4: Giảng viên phải kiểm tra thủ công các yêu cầu về định dạng, cấu trúc và trích dẫn. Công việc này mất khoảng 8 phút/bài, chiếm 38,1% tổng thời gian chấm 21 phút/bài. |
| **Impact** | Việc dành 8 phút/bài để rà soát các yêu cầu cơ học làm tăng tổng khối lượng chấm bài. Với lớp 45 bài, thời gian rà soát ước tính khoảng 6 giờ. Điều này có thể ảnh hưởng đến tiến độ trả bài và thời gian dành cho đánh giá chuyên môn khi giảng viên có quỹ thời gian giới hạn. |
| **Success Metric** (baseline → target, cách đo) | 1. Thời gian rà soát (gồm xác minh): 8 phút/bài → không quá 3 phút/bài (giảm ít nhất 62,5%). 2. Tổng thời gian chấm: 21 phút/bài → không quá 16 phút/bài (giảm ít nhất khoảng 24%). 3. Precision và Recall phát hiện lỗi quy cách đạt ít nhất 90%. 4. Đo bằng cách bấm giờ và đối chiếu kết quả với bộ lỗi chuẩn do giảng viên/TA xác nhận trên tối thiểu 20 bài thử nghiệm. |
| **Boundary** | AI không tự chấm điểm, không quyết định mức trừ điểm, không tự sửa nội dung bài làm và không gửi kết quả cho sinh viên. AI chỉ đưa ra checklist Đạt/Chưa đạt/Cần kiểm tra kèm bằng chứng. Giảng viên hoặc TA xác nhận các cảnh báo và quyết định kết quả cuối cùng. |
| **AI intervention point** | Sau khi nhận file bài làm và rubric, trước bước đọc sâu nội dung. AI hỗ trợ đối chiếu cấu trúc, kiểm tra các tiêu chí hình thức và rà soát trích dẫn; đưa ra danh sách lỗi nghi ngờ kèm số trang hoặc vị trí liên quan để giảng viên kiểm tra. |
| **Mức chọn** | Workflow (kết hợp Rule và AI). |
| **Rủi ro & người kiểm tra** | Rủi ro: AI nhận diện sai cấu trúc tài liệu, bỏ sót lỗi, cảnh báo sai, hiểu sai rubric hoặc chỉ ra vị trí không chính xác. Người kiểm tra: Giảng viên/TA rà soát các cảnh báo trước khi sử dụng; trường hợp không đủ bằng chứng phải đánh dấu Cần kiểm tra, không tự kết luận. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Giảng viên, TA và sinh viên. | Tập trung vào giảng viên và TA phụ trách chấm bài. | Xác định rõ người trực tiếp thực hiện quy trình và chịu ảnh hưởng của bottleneck. |
| Bottleneck | Rà soát thủ công mất 8 phút/bài. | Xác định cụ thể bước 2–4, mất 8 phút/bài, chiếm 38,1% tổng thời gian. | Làm rõ vị trí gây tốn thời gian để xác định phạm vi can thiệp. |
| Impact | Chấm bài lâu dẫn đến quá tải, nhận xét sơ sài hoặc trễ hạn trả bài. | Việc rà soát cơ học làm tăng khối lượng công việc và có thể ảnh hưởng đến tiến độ trả bài hoặc thời gian đánh giá chuyên môn khi quỹ thời gian giới hạn. | Tránh khẳng định quan hệ nhân quả chưa được chứng minh. Tiết kiệm thời gian không đồng nghĩa chắc chắn với nâng cao chất lượng nhận xét. |
| Success Metric | Chỉ đo thời gian: rà soát từ 8 xuống dưới 2 phút/bài, tổng thời gian từ 21 xuống dưới 15 phút/bài. | Rà soát không quá 3 phút/bài, tổng thời gian không quá 16 phút/bài, kết hợp Precision, Recall ≥90% và đối chiếu với bộ lỗi chuẩn. | Đảm bảo hệ thống không chỉ xử lý nhanh mà còn phát hiện lỗi đủ chính xác; target thời gian được chỉnh cho khớp thiết kế gồm 1 phút tự động và 2 phút xác minh. |
| Boundary | AI không tự cho điểm, không đánh giá lập luận, không tự gửi điểm/phản hồi; cảnh báo phải có vị trí cụ thể. | Bổ sung không quyết định mức trừ điểm, không tự sửa nội dung bài làm; đầu ra có trạng thái Cần kiểm tra khi thiếu bằng chứng. | Đảm bảo giảng viên giữ quyền quyết định và hạn chế rủi ro do AI đưa ra kết luận sai. |
| AI intervention point | Chưa xác định rõ. | Can thiệp tại bước kiểm tra định dạng, cấu trúc và trích dẫn trước khi đánh giá nội dung chuyên môn. | Giới hạn phạm vi AI vào công đoạn có bottleneck rõ ràng. |
| Mức chọn | Chưa thống nhất. | Workflow kết hợp Rule và AI. | Các lỗi định dạng có thể kiểm tra bằng quy tắc; AI hỗ trợ các tiêu chí cần hiểu ngữ cảnh. Chưa có bằng chứng cần Agent tự chủ. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---|---|---|---|
| 1 | Độ chính xác phát hiện lỗi (Precision) | Precision ≥90% so với bộ lỗi chuẩn do giảng viên/TA xác nhận. | Precision <90%, xuất hiện quá nhiều cảnh báo sai. |
| 2 | Khả năng phát hiện đầy đủ lỗi (Recall) | Recall ≥90% so với tổng số lỗi trong bộ dữ liệu kiểm thử. | Recall <90%, bỏ sót nhiều lỗi thực tế. |
| 3 | Tính chính xác của bằng chứng | Ít nhất 95% cảnh báo đúng có vị trí trang/đoạn và tiêu chí rubric tương ứng chính xác để người kiểm tra đối chiếu được. | Dẫn sai vị trí, sai tiêu chí hoặc không thể xác minh cảnh báo từ tài liệu gốc. |
| 4 | Thời gian xử lý | Thời gian rà soát bằng hệ thống, bao gồm thời gian giảng viên xác nhận cảnh báo, trung bình không quá 3 phút/bài. | Thời gian trung bình trên 3 phút/bài hoặc không giảm đáng kể so với baseline. |
| 5 | Tuân thủ giới hạn và quyền kiểm soát | 100% kết quả chỉ dừng ở checklist và cảnh báo; không tự sửa bài, chấm điểm hoặc gửi phản hồi khi chưa được duyệt. | Tự ý chỉnh sửa tài liệu, quyết định điểm số hoặc đưa ra kết luận chắc chắn khi thiếu bằng chứng. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Cao** | Pain phía sinh viên có bằng chứng (N = 20: 95% từng bị trừ điểm/nhắc nhở vì lỗi quy cách, 90% nộp xong mới biết sót tiêu chí). Nhưng Actor của v1 là giảng viên/TA, trong khi báo cáo chưa có bản ghi phỏng vấn hoặc bấm giờ nào từ nhóm này. Baseline 8 và 21 phút/bài vì vậy chưa được kiểm chứng; chưa biết giảng viên/TA có sẵn sàng dùng hay không. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Trung bình** | Đầu ra là checklist Đạt/Chưa đạt/Cần kiểm tra kèm số trang, dễ đối chiếu với bài gốc và không bắt buộc phải tin AI. Tuy nhiên, chưa thử với người dùng thật; nhiều cảnh báo sai sẽ làm tăng thời gian xác minh, còn người chấm có thể ỷ lại vào checklist và bỏ qua lỗi AI không báo. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Trung bình** | Input (Word/PDF, rubric) có sẵn; các tiêu chí font, lề, số trang biểu diễn được bằng Rule. Rủi ro nằm ở việc trích xuất cấu trúc từ PDF, ở rubric chưa rõ (40% sinh viên chấm độ rõ ràng ở mức 1–2) và ở ngưỡng Precision/Recall ≥ 90% chưa được thử. Nhóm cũng chưa có bộ lỗi chuẩn để đo. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **Cao** | Bài làm chứa thông tin cá nhân và sản phẩm học thuật của sinh viên. Nhóm chưa xác nhận trường/khoa có cho phép đưa dữ liệu này vào dịch vụ LLM bên ngoài hay không, chưa ước tính chi phí và chưa có đơn vị vận hành, cập nhật rubric lâu dài. Grammarly AI Grader đã hỗ trợ đối chiếu với rubric, nên cũng cần làm rõ khác biệt của giải pháp. |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:** Value và Viability đang ở mức Cao nên chưa đủ điều kiện Go. Chưa chọn No-Go vì cả hai rủi ro đều có thể kiểm chứng nhanh và chưa có bằng chứng cho thấy No AI hoặc Rule đã đủ. Boundary và tiêu chí đánh giá đã rõ, nên bước tiếp theo là lấy dữ liệu từ đúng Actor và xác nhận điều kiện dữ liệu trước khi xây.

**Nếu Go — pilot nhỏ nhất:** Chưa áp dụng. Sau khi đạt các điều kiện bên dưới, pilot dự kiến gồm 1 môn và tối thiểu 20 bài đã ẩn danh; kết quả chỉ dành cho giảng viên/TA, không gửi cho sinh viên và không dùng để tính điểm.

**Nếu Not Yet — cần kiểm chứng gì trước (trong 2 tuần):**

| # | Rủi ro | Việc cần làm | Điều kiện đạt |
|---:|---|---|---|
| 1 | Value | Phỏng vấn theo The Mom Test 3–5 giảng viên/TA về đợt chấm gần nhất; bấm giờ bước 2–4 trên tổng tối thiểu 20 bài thật. | Trung vị thời gian rà soát ≥ 5 phút/bài và ít nhất 3/5 người đang tự làm bước rà soát này, đồng ý thử checklist trong đợt chấm tới. |
| 2 | Viability | Hỏi khoa/phòng đào tạo về quy định đưa bài sinh viên vào LLM; ước tính chi phí mỗi bài; xác định người vận hành. | Có xác nhận cho phép, tối thiểu với bài đã ẩn danh, và có người chịu trách nhiệm vận hành. |
| 3 | Feasibility | Giảng viên/TA lập bộ lỗi chuẩn trên 20 bài đã ẩn danh; chạy thử Rule + prompt, chưa cần xây sản phẩm. | Đạt tiêu chí 1–3 ở mục 7: Precision và Recall ≥ 90%, ít nhất 95% cảnh báo đúng có vị trí và tiêu chí chính xác. |
| 4 | Usability | Cho giảng viên/TA xác minh checklist mẫu trên bài thật; bấm giờ cả thời gian xác minh. | Thời gian rà soát gồm xác minh trung bình không quá 3 phút/bài. |
| 5 | Mức can thiệp | Đo riêng kết quả của Rule và checklist/template trên cùng 20 bài. | AI tạo ra cải thiện rõ về Recall hoặc thời gian so với Rule; nếu không, chọn mức đơn giản hơn. |

**Nếu No-Go — nên làm gì thay AI:** Chưa áp dụng. Nếu chạm ngưỡng dừng, nhóm dùng template chuẩn, checklist rubric cho sinh viên tự kiểm tra trước khi nộp và script Rule cho các lỗi định dạng.

**Ngưỡng dừng:**

- Nếu sau 2 tuần, trung vị thời gian rà soát đo được dưới 5 phút/bài hoặc dưới 3/5 giảng viên/TA đồng ý thử → dừng hướng cho người chấm; quay về template + checklist, xem xét chuyển Actor sang sinh viên.
- Nếu sau 2 vòng chỉnh prompt trên 20 bài, Precision hoặc Recall vẫn dưới 90% → bỏ phần AI, chỉ giữ Rule cho lỗi định dạng và rà soát thủ công phần còn lại.
- Nếu thời gian rà soát gồm xác minh vẫn từ 4 phút/bài trở lên (chưa giảm được một nửa so với baseline giả định 8 phút) → dừng, quay về quy trình thủ công có checklist.
- Nếu không được phép đưa bài sinh viên vào LLM, kể cả khi đã ẩn danh, và không có phương án xử lý nội bộ → No-Go với AI, chỉ dùng Rule + checklist.
- Nếu có dù chỉ 1 trường hợp hệ thống tự cho điểm, tự sửa bài hoặc gửi kết quả khi chưa được duyệt → dừng ngay và xem lại thiết kế (vi phạm tiêu chí 5 ở mục 7).

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- **Lệch Actor và bằng chứng:** Khảo sát và interview snapshot đều đến từ sinh viên, trong khi Problem Statement v1 đặt giảng viên/TA làm Actor. Các số 8 và 21 phút/bài cần được đo lại trực tiếp với nhóm này.
- **Mẫu khảo sát nhỏ:** N = 20 chưa đại diện cho toàn bộ sinh viên; dữ liệu tự báo cáo nên có thể chịu sai lệch do trí nhớ. Khảo sát cũng chưa tách lỗi theo ngành hoặc loại bài.
- **Thời gian tương lai mới là ước tính:** Các mốc 3 phút/bài cho khâu rà soát và 16 phút/bài cho tổng thời gian chấm chưa được đo trên bài thật.
- **Chưa kiểm chứng kỹ thuật:** Chưa chạy Rule hoặc LLM trên bài thật, chưa có bộ lỗi chuẩn, nên ngưỡng Precision/Recall ≥ 90% và ngưỡng tin cậy 80% mới là mục tiêu thiết kế.
- **Rubric không đồng đều:** Giả định #4 bị phản bác một phần; hệ thống có thể không xử lý tốt rubric mơ hồ nếu chưa có bước làm rõ tiêu chí.
- **Chưa làm rõ điều kiện vận hành:** Chưa có thông tin về quy định dữ liệu, chi phí, người vận hành và so sánh trực tiếp với Grammarly AI Grader.

**Hướng tiếp theo:**

1. Thực hiện 5 việc kiểm chứng ở mục 8.2 trong 2 tuần, sau đó đánh giá lại 4 rủi ro và cập nhật Go / No-Go.
2. Cập nhật baseline, target và quy trình tương lai theo dữ liệu đo được từ giảng viên/TA.
3. Xây bộ eval từ 20 bài đã ẩn danh, bao gồm trường hợp rubric mơ hồ, file PDF khó trích xuất và bài không có lỗi.
4. Dùng cùng bộ eval để so sánh No AI, Rule và Workflow trước khi đầu tư xây dựng.
5. Nếu hướng giảng viên/TA không đạt, đánh giá hướng sinh viên tự kiểm tra trước khi nộp, vì đây là nhóm đã có tín hiệu pain rõ nhất.

---

## 10. Tài liệu tham khảo

**Dữ liệu của nhóm:**

- Khảo sát Google Forms với 20 sinh viên: [bảng tổng hợp](../assets/cp4-survey-result.md), [dữ liệu gốc](../assets/cp4-survey-result.xlsx).
- Interview snapshot: [report/assets/cp4-interview-snapshot-1.md](../assets/cp4-interview-snapshot-1.md).

**Công cụ đã research:**

- Microsoft. [Check grammar, spelling, and more in Word for the web](https://support.microsoft.com/en-us/word/check-grammar-spelling-and-more-in-word-for-the-web).
- Grammarly. [AI Grader user guide](https://support.grammarly.com/hc/en-us/articles/38552360525837-AI-Grader-user-guide).
- Grammarly. [Plagiarism Checker user guide](https://support.grammarly.com/hc/en-us/articles/115000091452-Plagiarism-Checker-user-guide).
- Turnitin. [Reviewing your grade and rubric](https://guides.turnitin.com/hc/en-us/articles/23859968188429-Reviewing-your-grade-and-rubric).

**Framework và phương pháp:**

- Torres, T. [Opportunity Solution Trees](https://www.producttalk.org/opportunity-solution-trees/); [The Interview Snapshot](https://www.producttalk.org/interview-snapshot/).
- Bland, D. và Osterwalder, A. [Assumptions Mapping](https://www.strategyzer.com/library/how-assumptions-mapping-can-focus-your-teams-on-running-experiments-that-matter), Strategyzer.
- Fitzpatrick, R. [The Mom Test](https://www.momtestbook.com/).
- Anthropic. [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents).
- Agrawal, A., Gans, J. và Goldfarb, A. [A Simple Tool to Start Making Decisions with the Help of AI](https://hbr.org/2018/04/a-simple-tool-to-start-making-decisions-with-the-help-of-ai), Harvard Business Review.
- Google PAIR. [People + AI Guidebook: User Needs](https://pair.withgoogle.com/chapter/user-needs/).
- Microsoft Research. [Guidelines for Human-AI Interaction](https://www.microsoft.com/en-us/research/publication/guidelines-for-human-ai-interaction/).
- Husain, H. và Shankar, S. [Advanced evals](https://www.lennysnewsletter.com/p/advanced-evals-how-to-find-and-fix), Lenny's Newsletter.
- Cagan, M. [The Four Big Risks](https://www.svpg.com/four-big-risks/), SVPG.
