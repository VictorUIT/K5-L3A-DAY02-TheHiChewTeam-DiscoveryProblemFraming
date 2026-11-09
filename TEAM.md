# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm:
- Candidate problem nhóm chọn (1 câu):
- Quyết định cuối (Go / Not Yet / No-Go):

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Bình An | 2A202603606 | Tổng hợp báo cáo; đối chiếu bằng chứng CP4; rà soát CP5–CP6 | An041003 |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | | | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | | | Assumption map, snapshot hoặc survey |
| CP4 — Research | | | Bảng research có link |
| CP5 — Quy trình trước/sau | | | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | | | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | | | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | | | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenBinhAn-2A202603606

**Phần việc phụ trách:**

- Báo cáo cá nhân, tổng hợp bảng Pitch/Cluster/OST và bảng chấm điểm CP3 theo nội dung được cung cấp.
- Chuyển CSV thành snapshot, khớp bằng chứng với 6 giả định và tổng hợp research CP4.
- Rà soát hai bản CP5–CP6 riêng và đồng bộ bản CP6 theo CP5.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Cung cấp 5 vấn đề từ trải nghiệm và trao đổi với người thân; hoàn thiện 3 card, phản hồi trực tiếp các phản biện AI ở CP2.
- Tổng hợp Pitch thành một dòng mỗi người, bổ sung đủ 6 báo cáo và chuẩn bị câu hỏi phân công chéo.
- Đưa 27 phản hồi CSV vào bảng snapshot, tổng hợp tín hiệu xác nhận/phản bác và phân biệt phần được hỗ trợ với phần chưa đủ bằng chứng.
- Rà soát Workflow, metric, boundary và quyết định trong bản CP6 riêng; đối chiếu với nội dung CP5–CP6 hiện có trong báo cáo nhóm.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo cá nhân](report/individual/2A202603606_NguyenBinhAn.md), commit [AnReport — ef0116c](https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming/commit/ef0116c).
- [Báo cáo nhóm](report/team/group_report.md), mục 2–3; commit [CP3 — 4ad0033](https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming/commit/4ad0033) và [CP4 — f4e9496](https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming/commit/f4e9496).
- [27 snapshot](report/assets/cp4-interview-snapshot/README.md) và [CSV nguồn](report/assets/cp4-khao-sat.csv), commit [InterviewCP4 — 5a8edbe](https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming/commit/5a8edbe).

**Điều mình học được từ phần nhóm:**

- Phân biệt phản biện AI ở CP2 với câu hỏi thảo luận nhóm ở CP3.
- Phân biệt dữ liệu khảo sát tự thuật với baseline bấm giờ, và mục tiêu thử nghiệm với kết quả đã đạt.
- Không đồng nhất việc cân nhắc nhiều yếu tố với nhu cầu dùng Agent; cần so sánh với Rule và giữ người dùng quyết định cuối cùng.
