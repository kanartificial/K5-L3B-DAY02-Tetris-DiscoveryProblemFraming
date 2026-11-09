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
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

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
