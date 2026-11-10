# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Tetris
- Candidate problem nhóm chọn (1 câu): Giảng viên/TA phải rà soát sơ bộ thủ công định dạng và tiêu chí rubric của bài tập lớn/tiểu luận trước khi đọc sâu nội dung, trong khi sinh viên vẫn thường nộp bài còn lỗi quy cách hoặc sót tiêu chí.
- Quyết định cuối (Go / Not Yet / No-Go): Not Yet

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Khổng Ngọc Anh | 2A202603974| Trưởng nhóm, phụ trách quy trình, problem statement | kanartificial |
| 2 | Võ Thị Kim Ý | 2A202603965 | Phụ trách research, tìm kiếm giải pháp đã có và viết problem statement | KimY22-it |
| 3 | Lý Hà Trân Trân | 2A202603968 | Phụ trách kiểm chứng | TranHa161 |
| 4 | Vương Thu Thảo | 2A202603966 | Phụ trách phân tích vấn đề |ThuThaoVuong |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Cả nhóm | | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Lý Hà Trân Trân | | Assumption map, snapshot hoặc survey |
| CP4 — Research | Vương Thu Thảo| Võ Thị Kim Ý | Bảng research có link, bảng điểm shortlist |
| CP5 — Quy trình trước/sau | Khổng Ngọc Anh |Vương Thu Thảo| Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Khổng Ngọc Anh | Võ Thị Kim Ý | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Võ Thị Kim Ý | Vương Thu Thảo| Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Lý Hà Trân Trân | Vương Thu Thảo| 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### KhongNgocAnh-2A202603974

**Phần việc phụ trách:**

- Trưởng nhóm, phối hợp tích hợp bài làm trên repo chung.
- CP1–CP2: Scan problem, xây dựng 3 Problem Cards và quy trình nháp trong báo cáo cá nhân.
- CP3: Tổng hợp bảng pitch và đóng góp 3 candidate về hoạt động nghiên cứu.
- CP4: Xây dựng Assumption Map.
- CP5: Phụ trách quy trình trước/sau, bảng before/after và Problem Statement v0.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **CP1–CP2:** Viết báo cáo cá nhân với 3 Problem Cards: reproduce paper, debug kết quả nghiên cứu và xây dựng kiến thức nền tảng; bổ sung Job Story, quy trình, ước lượng thời gian, bottleneck và success metric.
- **CP3 – Mục 2.1:** Điền bảng pitch ban đầu của nhóm, trong đó đóng góp candidate #9–#11: reproduce paper, debug kết quả nghiên cứu và xây dựng nền tảng.
- **CP4 – Mục 3.1:** Điền 6 giả định về lỗi định dạng, thiếu tiêu chí rubric, tác động, thời gian tự rà soát, tính rõ ràng của yêu cầu, hạn chế của giải pháp hiện tại và mức sẵn sàng kiểm tra bài; phân loại và xác định thứ tự kiểm chứng.
- **CP5 – Mục 4.2, 4.3:** Xây dựng quy trình tương lai 5 bước, phân biệt vai trò Rule-based, AI và giảng viên; bổ sung input/output, thời gian dự kiến, boundary, fallback và bảng so sánh trước/sau. Các con số sau cải tiến là kỳ vọng, chưa phải kết quả đo thực tế.
- **CP5 – Mục 5:** Viết Problem Statement v0 gồm actor, quy trình, bottleneck, impact, success metric và boundary; ghi nhận phản biện về việc tiết kiệm thời gian chưa đủ để khẳng định chất lượng feedback tăng.
- **Điều phối repo:** Merge các pull request của thành viên và xử lý dấu xung đột merge trong báo cáo nhóm.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/individual/2A202603974_KhongNgocAnh.md`: Mục 2 (CP1), mục 3 (CP2); commit `cd975b0`, `273a3fb`, `ab4043b`.
- `report/team/group_report.md`: Mục 2.1, candidate #9–#11 và bảng pitch ban đầu; commit `3f2d205`.
- `report/team/group_report.md`: Mục 3.1, Assumption Map; commit `9ecaa32`.
- `report/team/group_report.md`: Mục 4.2, 4.3, quy trình tương lai và bảng before/after; commit `e3d92e2`.
- `report/team/group_report.md`: Mục 5, Problem Statement v0 và phản biện; commit `bfb26ef`.
- Commit tích hợp: `8c8a884`, `03fa2a8`, `fcd7774`, `2e415ac`, `a6c43dd`, `2ccffec`, `43ac41d` (merge pull request); `ead08f4` (xóa dấu xung đột merge).

### VoThiKimY-2A202603965

**Phần việc phụ trách:**

- CP1–CP2: Scan problem, xây dựng và phân tích 3 Problem Cards, quy trình nháp trong báo cáo cá nhân.
- CP3: Chấm điểm shortlist (1–5).
- CP4: Research giải pháp đã có
- CP5: Problem Statement v1 + tiêu chí đánh giá.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **CP1–CP2:** Viết báo cáo cá nhân với 5+ scan problem và 3 problem cards, phân tích Job Story, quy trình, ước lượng thời gian, bottleneck và success metric.
- **CP3 – Mục 2.4:** Chấm điểm shortlist (1–5), nêu lý do vì sao chọn candidate và vì sao không chọn 2 candidate còn lại.
- **CP4 – Mục 3.3:** Tìm kiếm, nghiên cứu các giải pháp hiện có, xem điểm mạnh, khoảng trống và rút ra vấn đề cần lứu ý cho nhóm.
- **CP6 - Mục 7:** Viết Problem Statement v1 gồm actor, quy trình, bottleneck, impact, success metric và boundary và tiêu chí đánh giá.
  
**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/individual/2A202603965_VoThiKimY.md`: Mục 2 (CP1), mục 3 (CP2); commit `1da573f`, `d139564`, `16f8110`.
- `report/team/group_report.md`: Mục 2.4 (CP3); commit `3e5584c`, `627906e`, `eb24ac9`.
- `report/team/group_report.md`: Mục 3.3 (CP4); commit  `8eb3620`.
- `report/team/group_report.md`: Mục 7 (CP6); commit`81c8fb8`.
  
### LyHaTranTran-2A202603968

**Phần việc phụ trách:**

- CP3: Xây dựng Opportunity Solution Tree rút gọn.
- CP4: Phụ trách kiểm chứng bằng survey và interview snapshot.
- CP6: Đánh giá 4 rủi ro và đề xuất quyết định cuối.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **CP3 – Mục 2.1:** Pitch 3 candidate #6, #7, #8; candidate #6 (Rà soát sơ bộ định dạng và tiêu chí bài tập lớn) được nhóm chọn.
- **CP3 – Mục 2.3:** Xây dựng cây OST gồm outcome và 3 opportunity; gạch bỏ 3 ý là solution đội lốt opportunity và giải thích lý do.
- **CP4 – Mục 3.2:** Tổng hợp kết quả khảo sát N = 20 sinh viên, lập interview snapshot, bảng tín hiệu xác nhận/phản bác và ghi lại cách nhóm sửa problem sau kiểm chứng.
- **CP6 – Mục 8:** Đánh giá 4 rủi ro, đề xuất quyết định Not Yet, kế hoạch kiểm chứng và ngưỡng dừng.
- **Mục 9, 10:** Tổng hợp hạn chế, hướng tiếp theo, tài liệu tham khảo.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: Mục 2.1 (dòng #6–#8), 2.3, 3.2, 8, 9, 10.
- `report/assets/cp4-interview-snapshot-1.md`.
- `report/individual/2A202603968_LyHaTranTran.md`: Problem Card #1–#3 là nguồn của candidate #6–#8.
- Commit: `8fc2c15` (mục 2.3), `0cf3587` (mục 3.2 và interview snapshot).

### VuongThuThao-2A202603966

**Phần việc phụ trách:**

- Phân tích và lựa chọn vấn đề, xác định mức độ can thiệp AI cho bài toán nhóm.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **CP3 – Mục 2.2:** Phân nhóm các candidate theo pattern chung (Cluster).
- **CP3 - Mục 2.4:** Research về bảng chấm điểm shortlist.
- **CP6 – Mục 6:** Phân tích các mức can thiệp AI, lựa chọn Workflow và xác định boundary, fallback.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: Mục 2.2, mục 2.4, mục 6 (CP6).
- Commit GitHub: commit `9d88f97`, `a929a09`, `1d96b2a`



