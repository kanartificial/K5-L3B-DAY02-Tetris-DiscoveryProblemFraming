# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | KimY | Khi làm bài tập nhóm nhưng có thành viên thường xuyên chậm tiến độ, tôi muốn biết rõ tình trạng công việc và những khó khăn của từng người để tránh ảnh hưởng đến deadline chung |  | | |
| 2 | KimY| Khi có một vấn đề, nghiên cứu mà tôi cảm thấy mới và quan tâm, tôi cần tìm hiểu, đọc các bài báo liên quan để rút ra insight cho bản thân | | | |
| 3 | Thao | Sinh viên mất nhiều thời gian tìm kiếm, đọc và tổng hợp thông tin từ nhiều tài liệu khác nhau khi làm bài tập, tiểu luận và nghiên cứu. | | | |
| 4 | Thao | Sinh viên gặp khó khăn khi quản lý nhiều deadline và sắp xếp thứ tự ưu tiên các nhiệm vụ từ nhiều môn học. | | | |
| 5 | Thao | Sinh viên gặp khó khăn trong việc phối hợp và theo dõi tiến độ khi làm bài tập nhóm do các thành viên cập nhật thông tin không đồng đều.|  | | |
| 6 | Tran | Rà soát sơ bộ định dạng & tiêu chí bài tập lớn / tiểu luận (#3) | | | |
| 7 | Tran | Giải đáp thắc mắc lặp lại về quy chế / quy định làm đồ án (#1) | | | |
| 8 | Tran | Trích xuất luận điểm chính từ bài báo khoa học tiếng Anh (#4) | | | |
| 9 | Anh | 3. Reproduce paper | | | |
| 10 | Anh | 8. Debug kết quả nghiên cứu | | | |
| 11 | Anh | 2. Xây dựng nền tảng | | | |
| 12 | KimY| Khi bắt đầu một tuần học mới, tôi muốn nắm được tất cả bài tập, deadline và lịch báo cáo của các môn để không bỏ sót nhiệm vụ quan trọng| | | |

### 2.2. Cluster


| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A. Tìm kiếm và khai thác tri thức | #2, #3, #8, #9, #10 | Sinh viên mất nhiều thời gian tìm kiếm, đọc hiểu, tổng hợp và khai thác thông tin từ tài liệu khoa học; gặp khó khăn khi tái hiện hoặc kiểm chứng kết quả nghiên cứu. |
| B. Quản lý và hoàn thành nhiệm vụ học tập | #4, #6, #7, #11 | Sinh viên gặp khó khăn trong việc nắm bắt yêu cầu, quy định, xây dựng nền tảng kiến thức và tổ chức công việc để hoàn thành bài tập đúng yêu cầu. |
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
| 6 | Rà soát sơ bộ định dạng & tiêu chí bài tập lớn (Tran) | 4 | 5 | 4 | 4 | 5 | 5 | 5 | **32** |
| 8 | Tìm kiếm, đọc hiểu và tổng hợp tài liệu (Thao) | 5 | 4 | 4 | 4 | 5 | 5 | 5 | **32** |
| 7 | Giải đáp thắc mắc lặp lại về quy chế đồ án (Tran) | 4 | 5 | 4 | 4 | 4 | 4 | 5 | **30** |


**Candidate được chọn:**

- **#6 — Rà soát sơ bộ định dạng và tiêu chí bài tập lớn (Tran).**

**Vì sao chọn:**

- Có Actor rõ ràng: sinh viên thực hiện bài tập lớn, tiểu luận hoặc đồ án.
- Quy trình cụ thể: tiếp nhận yêu cầu, đối chiếu định dạng, kiểm tra tiêu chí và phát hiện nội dung chưa đáp ứng.
- Pain point có tính thực tiễn: sinh viên có thể mất thời gian đọc lại hướng dẫn, đối chiếu nhiều tiêu chí và bỏ sót yêu cầu.
- Có khả năng đo lường hiệu quả thông qua thời gian rà soát và số lỗi hoặc tiêu chí bị bỏ sót.
- Phù hợp với phạm vi triển khai Lab, có thể so sánh giữa phương pháp thủ công, Rule-based và AI Workflow.
- Có tiềm năng ứng dụng AI để hỗ trợ đọc hiểu yêu cầu, kiểm tra tài liệu và chỉ ra những điểm chưa đáp ứng tiêu chí.

**Vì sao loại các candidate còn lại:**

- **#8 — Tìm kiếm, đọc hiểu và tổng hợp tài liệu:** Có tiềm năng ứng dụng AI cao nhưng phạm vi rộng, dễ trùng lặp với các công cụ AI hỗ trợ nghiên cứu hiện có. Cần giới hạn rõ hơn phạm vi tài liệu và đầu ra.
- **#7 — Giải đáp thắc mắc về quy chế đồ án:** Có quy trình và Actor rõ ràng nhưng phạm vi nội dung tương đối hẹp, có thể giải quyết bằng hệ thống tra cứu tài liệu hoặc chatbot RAG đơn giản.

**Xử lý bất đồng (nếu có):** Thảo luận, bất đồng về camdidate Tìm kiếm, đọc hiểu và tổng hợp tài liệu và Rà soát sơ bộ định dạng và tiêu chí bài tập lớn, sau quá trình nghiên cứu và đánh giá lại thì chốt candidate Rà soát sơ bộ định dạng và tiêu chí bài tập lớn

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
| 6 | Sinh viên sẵn sàng dành thời gian kiểm tra và chỉnh sửa bài trước khi nộp nếu việc kiểm tra mang lại giá trị rõ ràng.| Value | 4 | 1 | Sau 1-4 |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này: **Giả định #1, #2, #3, #4 và #5** (các giả định có mức độ quan trọng cao 4–5 và mức độ bằng chứng hiện tại thấp 1/5).

### 3.2. Kiểm chứng

Cách đã dùng: **Survey (Khảo sát trực tuyến qua Google Forms với mẫu N = 20 sinh viên) kết hợp Phỏng vấn sâu (The Mom Test)**

#### 1. Kết quả phân tích số liệu thực tế từ khảo sát (N = 20 sinh viên)

* **Đối tượng khảo sát (Câu 1 & 2):**
  - **Cơ cấu năm học:** 50% sinh viên Năm 3–4 (10 bạn); 25% sinh viên Năm 1–2 (5 bạn); 25% sinh viên đang làm đồ án tốt nghiệp (5 bạn).
  - **Khối lượng bài tập lớn/học kỳ:** 50% làm 1–2 bài/kỳ (10 bạn); 45% làm 3–5 bài/kỳ (9 bạn); 5% làm trên 5 bài/kỳ (1 bạn).
* **Tỷ lệ từng bị phạt/nhắc nhở lỗi hình thức, quy cách (Câu 3 - Xác nhận Giả định #1 & #2):**
  - **95% sinh viên (19/20 bạn)** xác nhận **từng bị trừ điểm hoặc bị nhắc nhở** vì các lỗi hình thức/quy cách (chỉ duy nhất 1 bạn chưa từng bị).
  - **Top các lỗi quy cách phổ biến nhất:**
    1. *Sai quy chuẩn trích dẫn nguồn (citation) / danh mục tài liệu tham khảo:* **70% (14/20 bạn)** gặp phải.
    2. *Đánh số hình ảnh, bảng biểu không đúng chuẩn hoặc thiếu danh mục:* **60% (12/20 bạn)** gặp phải.
    3. *Đặt tên file nộp bài sai cấu trúc yêu cầu của giảng viên/hệ thống:* **55% (11/20 bạn)** gặp phải.
    4. *Sai font chữ, cỡ chữ, dãn dòng, căn lề trang:* **50% (10/20 bạn)** gặp phải.
    5. *Sai quy cách trang bìa, thiếu lời cam đoan/thông tin đề tài:* **35% (7/20 bạn)** gặp phải.
* **Tỷ lệ nộp bài xong mới phát hiện bỏ sót tiêu chí Rubric (Câu 4 - Xác nhận Giả định #1 & #3):**
  - **90% sinh viên (18/20 bạn)** từng rơi vào cảnh nộp bài xong mới biết nhóm mình bỏ sót yêu cầu/tiêu chí trong rubric (trong đó **35% bị thường xuyên** ở hầu hết các kỳ học; **55% bị thỉnh thoảng** 1–2 lần).
  - Chỉ có **10% (2 bạn)** chưa từng bị sót tiêu chí.
* **Cách rà soát hiện tại (Workaround - Câu 5 - Kiểm chứng Giả định #3 & #5):**
  - **60% (12 bạn):** Tự đọc lướt bằng mắt từ đầu đến cuối file Word/PDF.
  - **60% (12 bạn):** Phân công 1 bạn trong nhóm làm nhiệm vụ "soát lỗi" thủ công trước giờ nộp.
  - **20% (4 bạn):** Dùng công cụ kiểm tra chính tả/ngữ pháp (Grammarly, LanguageTool).
  - **10% (2 bạn):** Dán nội dung vào ChatGPT/Claude để hỏi chung chung.
  - *Nhận xét:* 100% sinh viên vẫn phụ thuộc vào rà soát thủ công bằng mắt trong trạng thái gấp gáp sát giờ nộp bài, giải thích vì sao vẫn liên tục sót lỗi.
* **Đánh giá mức độ rõ ràng của Rubric nhận được (Câu 6 - Thang 1–5 - Phản biện Giả định #4):**
  - Điểm trung bình: **3.05 / 5.0**.
  - Đáng chú ý: **40% sinh viên (8/20 bạn)** đánh giá độ rõ ràng ở mức thấp (điểm 1 và 2). Điều này bác bỏ một phần Giả định #4: rubric thực tế thường không đủ rõ ràng hoặc quá dài dòng, khiến sinh viên rất khó tự đối chiếu một cách khách quan.

---

#### 2. Interview snapshot (Trích xuất trường hợp điển hình từ khảo sát)

> Xem bản ghi chép chi tiết tại: [report/assets/cp4-interview-snapshot-1.md](../assets/cp4-interview-snapshot-1.md)

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên Năm 3–4 (làm 3–5 bài tập lớn/kỳ, thường xuyên bị trừ điểm lỗi quy cách và sót tiêu chí rubric) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Nhiều khi cả nhóm thức trắng đêm làm nội dung, đến sát giờ nộp mới cuống cuồng phân công một bạn đọc lướt lại toàn bộ file 30 trang. Cứ đinh ninh đủ bài rồi, đến lúc thầy chấm trả điểm mới biết nhóm quên mất tiêu chí danh mục hình ảnh và bị trừ mất 0.5 điểm oan."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Đợt nộp báo cáo tiểu luận giữa kỳ môn chuyên ngành tháng trước |
| Hiện đang xử lý bằng cách nào (workaround)? | Phân công một bạn trong nhóm ngồi rà lướt bằng mắt từng trang trước giờ deadline 30 phút |
| Mất bao lâu, bao lần? | Mất 45–60 phút mỗi lần rà soát bài nộp; mỗi học kỳ làm 3–4 môn là mất 3–4 lần rà soát căng thẳng trong tâm lý sợ sót lỗi |
| Insight / opportunity rút ra | Sinh viên rất cần một cơ chế tự động đối soát nhanh file bài làm với rubric (kiểm tra font, lề, số bảng hình, chuẩn trích dẫn) để phát hiện sớm các thiếu sót trước khi submit chính thức |

---

#### 3. Tổng hợp

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Khảo sát thực tế Google Forms | 20 sinh viên (Năm 1–2: 5, Năm 3–4: 10, Đồ án tốt nghiệp: 5) | • **Xác nhận Giả định #1, #2, #3:** 95% (19/20) từng bị trừ điểm lỗi hình thức (trích dẫn 70%, bảng hình 60%); 90% (18/20) nộp bài xong mới biết sót tiêu chí rubric.<br>• **Xác nhận Giả định #5:** 60% chỉ biết đọc lướt mắt hoặc giao 1 bạn làm thủ công, các công cụ sẵn có (Grammarly) chỉ xử lý chính tả mà không đối soát được rubric môn học. | • **Phản biện Giả định #4:** Có tới 40% sinh viên chấm điểm rubric ở mức 1–2 (kém rõ ràng). Do đó không thể giả định rubric luôn chuẩn hóa, hệ thống cần có bước trích xuất/làm rõ rubric trước khi kiểm tra bài.<br>• 1 sinh viên (5%) chưa từng bị phạt lỗi hình thức nhờ dùng template cố định. |

---

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
- **Mở rộng góc nhìn giá trị:** Ban đầu nhóm chỉ nhìn bài toán từ phía áp lực của **Trợ giảng / Giảng viên** (mất 8 phút/bài kiểm tra cơ học). Dữ liệu khảo sát 20 sinh viên chứng minh **phía người học cũng chịu nỗi đau tương đương**: 90% nộp bài xong mới biết sót rubric, 95% bị mất điểm oan uổng vì lỗi quy cách.
- **Xác định rõ phạm vi can thiệp (Boundary):**
  - Công cụ **tập trung đúng vào các lỗi hình thức có tỷ lệ vi phạm cao nhất theo khảo sát:** trích dẫn chuẩn APA/IEEE (70%), danh mục bảng/hình (60%), quy chuẩn font/lề (50%) và đối chiếu đủ mục rubric (90% từng bỏ sót).
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

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```
HIỆN TẠI — 21 phút/bài (Tổng ~15.75 tiếng cho lớp 45 sinh viên)

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
| 5 | Giảng viên | Bài làm đã qua bước rà soát sơ bộ | Nhận xét về nội dung, lập luận và kết quả đánh giá; điểm số được ghi nhận | 12 phút/bài (9 phút đọc sâu + 3 phút nhận xét, nhập điểm) | Cần đánh giá chuyên môn, không thể chỉ dựa vào kiểm tra hình thức |
| 6 | Giảng viên | Kết quả đánh giá và nhận xét | Nhận xét hoàn chỉnh và điểm số được nhập vào hệ thống | 3 phút/bài | Tổng hợp nhận xét và nhập điểm cho sinh viên |


**Bottleneck chính:**
- Giảng viên mất nhiều thời gian cho các thao tác rà soát thủ công, lặp đi lặp lại như kiểm tra định dạng, đối chiếu rubric và kiểm tra trích dẫn.
- Ba thao tác này chiếm tổng cộng **8 phút/bài (38,1% tổng thời gian)**, tương đương **6 tiếng với 45 sinh viên**.
- Việc phải kiểm tra từng tiêu chí bằng tay dễ dẫn đến bỏ sót lỗi, thiếu nhất quán giữa các bài và làm tăng khối lượng công việc của giảng viên.
- Đây là công đoạn có tiềm năng ứng dụng AI và Rule-based để tự động rà soát sơ bộ, phát hiện lỗi và đưa ra cảnh báo. Giảng viên vẫn chịu trách nhiệm đọc sâu nội dung, đánh giá lập luận và quyết định điểm số cuối cùng.


### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

<<<<<<< HEAD
```text
TƯƠNG LAI — khoảng 14.5 phút/bài (Tổng ~10.9 tiếng cho lớp 45 sinh viên, tiết kiệm gần 5 tiếng)

[1. Tải bài nộp & Rubric vào hệ thống: 0.5']                 ← RULE
→ [2. Quét kiểm tra format: font, lề, số trang, bảng/hình: 0.5'] ← RULE (Trích xuất metadata file docx/pdf)
→ [3. Đối chiếu mục lục với rubric & kiểm tra trích dẫn: 1']     ← AI (LLM semantic parser & matching)
→ [4. Xuất Bảng Compliance Checklist tự động: 0.5']          ← RULE (Tổng hợp báo cáo đạt/chưa đạt)
→ [5. Giảng viên / TA xem nhanh checklist: 1']               ← CON NGƯỜI (HITL - rà soát cảnh báo)
→ [6. Đọc sâu nội dung & lập luận học thuật: 9']             ← CON NGƯỜI
→ [7. Viết nhận xét chuyên môn & nhập điểm chính thức: 2']    ← CON NGƯỜI (Quyết định điểm số 100%)

BOUNDARY:
- AI tuyệt đối KHÔNG tự cho điểm, không đánh giá độ hay/dở của lập luận học thuật, không tự ý gửi điểm hoặc phản hồi cho sinh viên.
- Mọi cảnh báo lỗi về rubric hay trích dẫn bắt buộc phải trích xuất kèm số trang, vị trí đoạn văn cụ thể để con người kiểm chứng được ngay.

PHƯƠNG ÁN QUAY VỀ (FALLBACK):
- Khi file bị mã hóa, lỗi font không parse được, hoặc AI đưa ra độ tin cậy thấp (<80% confidence): Hệ thống tự động gắn nhãn [Cần kiểm tra thủ công].
- Giảng viên/TA bỏ qua bước checklist, mở file gốc và đối chiếu rubric thủ công bằng mắt theo quy trình cũ.
```
=======


Tổng thời gian dự kiến: 16 phút/bài, tương đương 12 giờ cho lớp 45 sinh viên. Quy trình gồm 5 bước, trong đó 4 bước có sự tham gia của giảng viên và 1 bước kiểm tra tự động.

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

>>>>>>> bfb26efbe59a8ae535ccc2fed3d8f830c0c228e3

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
<<<<<<< HEAD
| **Số bước** | 6 bước | 7 bước | Tách quy trình thành các bước xử lý tự động nhỏ hơn, minh bạch hơn |
| **Tổng thời gian** | 21 phút/bài (~15.75 tiếng/lớp 45 SV) | ~14.5 phút/bài (~10.9 tiếng/lớp 45 SV) | Giảm ~31% tổng thời gian chấm; riêng khâu kiểm tra quy cách giảm 75% (từ 8' xuống 2') |
| **Số bước thủ công** | 6 / 6 bước (100% người làm) | 3 / 7 bước (43% người làm) | Khâu đọc hiểu chuyên môn và quyết định điểm số vẫn thuộc 100% về con người |
| **Bottleneck chính** | Khâu rà soát cơ học định dạng, mục lục, trích dẫn (8 phút/bài) | Khâu đọc sâu nội dung & đánh giá lập luận (9 phút/bài) | Nút thắt chuyển dịch lành mạnh sang khâu đòi hỏi tư duy chuyên môn sư phạm |
| **Rủi ro mới phát sinh** | Không có (chỉ có mệt mỏi và dễ sót lỗi thủ công) | AI nhận diện nhầm tiêu đề hoặc báo sai lỗi trích dẫn (False Positive/Negative); người chấm quá ỷ lại vào checklist | Xử lý bằng Boundary: AI bắt buộc dẫn chứng số trang; người chấm chỉ coi checklist là công cụ hỗ trợ rà soát sơ bộ |
=======
| Số bước | 6 | 5 | Giảm 1 bước |
| Tổng thời gian/bài | 21 phút | 16 phút | Giảm 23% |
| Số bước thủ công | 6 | 4 | |
| Bottleneck chính | Các bước kiểm tra định dạng, trích dẫn | Bước đọc sâu của giảng viên | |
| Rủi ro mới phát sinh | | AI có thể cảnh báo sai hoặc lỗi | |
>>>>>>> bfb26efbe59a8ae535ccc2fed3d8f830c0c228e3

---

## 5. Problem Statement v0 (CP5)
lỗi
| Trường | Nội dung |
|---|---|
<<<<<<< HEAD
| **Actor** | Giảng viên và Trợ giảng (TA) phụ trách chấm bài tập lớn/tiểu luận môn học (từ 15 trang trở lên), cùng sinh viên thực hiện bài nộp |
| **Quy trình** | Nhận file bài làm (Word/PDF) → Kiểm tra định dạng cơ học (font, lề, số trang, danh mục bảng/hình) → Đối chiếu mục lục với các tiêu chí rubric → Rà soát chuẩn trích dẫn tài liệu tham khảo → Đọc sâu nội dung và lập luận → Viết nhận xét và nhập điểm lên hệ thống |
| **Bottleneck** | Khâu rà soát thủ công định dạng, đối chiếu danh mục rubric và kiểm tra chuẩn trích dẫn (bước 2, 3, 4) mất tới **8 phút/bài (chiếm 38.1% tổng thời gian)** |
| **Impact** | • *Người chấm:* Với lớp 45 sinh viên mất ~6 tiếng làm việc cơ học lặp đi lặp lại; áp lực deadline (3–5 ngày) dẫn đến kiệt sức, nhận xét chuyên môn bị sơ sài hoặc trễ hạn trả bài.<br>• *Người học:* Khảo sát N = 20 cho thấy 95% từng bị trừ điểm lỗi hình thức, 90% nộp xong mới biết sót tiêu chí rubric, gây mất điểm oan uổng |
| **Success Metric** (baseline → target, cách đo) | • *Baseline:* Thời gian rà soát quy cách là 8 phút/bài; tổng thời gian chấm là 21 phút/bài (đo bằng khảo sát N = 20 và phỏng vấn TA).<br>• *Target:* Giảm thời gian rà soát quy cách xuống dưới 2 phút/bài (giảm 75%); tổng thời gian chấm giảm xuống dưới 15 phút/bài; tỷ lệ phát hiện đúng lỗi quy cách đạt ≥ 90%.<br>• *Cách đo:* Bấm giờ thực tế trên mẫu thử nghiệm 20 bài trong đợt nộp bài tiếp theo |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | • AI tuyệt đối KHÔNG tự cho điểm, không đánh giá độ hay/dở của lập luận học thuật, không tự ý gửi điểm/phản hồi cho sinh viên.<br>• Mọi cảnh báo lỗi về rubric hay trích dẫn bắt buộc phải trích xuất kèm số trang, vị trí đoạn văn cụ thể.<br>• Con người (TA/Giảng viên) giữ 100% quyền duyệt nội dung và quyết định điểm số (HITL) |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- **Phản biện 1:** *"Success Metric hiện tại chỉ đo về tốc độ/thời gian, chưa đo chất lượng của việc kiểm tra (nếu làm nhanh hơn nhưng bỏ sót nhiều lỗi hơn thì sao)?"*
  - *Nhóm đồng ý:* Nhóm bổ sung tiêu chí đo chất lượng ở phiên bản v1: Tỷ lệ phát hiện đúng lỗi quy cách (Precision/Recall) phải đạt $\ge 90\%$ so với kiểm tra thủ công.
- **Phản biện 2:** *"Có nên để AI gợi ý luôn mức điểm trừ cho từng lỗi hình thức (ví dụ: trừ 0.5 điểm nếu thiếu mục lục) không?"*
  - *Nhóm không đồng ý:* Nhóm kiên quyết giữ vững Boundary: AI chỉ đóng vai trò trích xuất bảng checklist Đạt/Chưa đạt kèm bằng chứng; việc trừ bao nhiêu điểm hoàn toàn thuộc quyền quyết định sư phạm của giảng viên.
=======
| **Actor** | Giảng viên chấm đồ án, tiểu luận, bài tập|
| **Quy trình** | Nhận bài, soát lỗi định dạng, soát cấu trúc theo rubric, soát trích dẫn, nhận xét nội dung, chấm bài|
| **Bottleneck** | Qúa trình soát lỗi thủ công chiếm nhiều thời gian |
| **Impact** | Thời gian chấm lâu gây quá tải dẫn đến trễ hạn trả bài; thời gian đọc sâu phần nội dung bị rút ngắn khiến nhận xét cho sinh viên sơ sài|
| **Success Metric** (baseline → target, cách đo) | Thời gian kiểm tra định dạng và cấu trúc giảm từ 8 phút/bài xuống dưới 1.5 phút/bài; tổng thời gian chấm giảm từ 21 phút/bài xuống dưới 15 phút/bài; tỷ lệ phát hiện sót lỗi quy cách đạt >95% |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không tự chấm điểm, không tự sửa bài làm và không thay đổi số liệu đánh giá. Giảng viên quyết định kết quả cuối cùng.|

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:
- Impact chưa tường mình và gây hiểu nhầm. Ví dụ, nếu giảng viên không có thời hạn chấm bài quá gấp, tiết kiệm 5 phút/bài không nhất thiết làm tăng chất lượng feedback. Đề xuất sửa impact thành: "Việc dành 8 phút/bài để rà soát các yêu cầu cơ học làm tăng tổng khối lượng chấm bài. Điều này có thể ảnh hưởng đến tiến độ trả bài và thời gian dành cho đánh giá chuyên môn khi giảng viên có quỹ thời gian giới hạn.". Nhóm đồng ý với feedbackfeedback
>>>>>>> bfb26efbe59a8ae535ccc2fed3d8f830c0c228e3

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
