# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: TheHiChewTeam
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Người phải quản lý nhiều nhiệm vụ song song khó xác định thứ tự ưu tiên để chọn công việc cần thực hiện tiếp theo.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | [Nguyễn Bình An](../individual/2A202603606_NguyenBinhAn.md) | Khi xếp thời khóa biểu đầu học kỳ, tôi muốn nhanh chóng xử lý xung đột và phân bổ chưa hợp lý, để giảm chỉnh sửa thủ công và đáp ứng yêu cầu giảng dạy. | Người phụ trách xếp thời khóa biểu tại trường học. | Rà soát và chỉnh sửa thủ công, ước lượng mỗi bước 30 phút/lần. | Xung đột lịch do dữ liệu đầu vào hay quy tắc xếp lịch? (Ho Quoc Toan hỏi.) |
| 2 | [Vũ Đức Thắng](../individual/2A202603601_VuDucThang.md) | Khi tổng kết cuối tháng, tôi muốn biết tiền đã chi vào những nhóm nào, để hiểu nguyên nhân vượt ngân sách. | Cá nhân, sinh viên, người đi làm, gia đình. | Ghi chép và phân loại giao dịch; giả định 20–40 phút/ngày. | Ghi chép theo mẫu có đủ để kiểm soát chi tiêu không? (Nguyen Duc Minh hỏi.) |
| 3 | [Trần Quốc Tuấn Khanh](../individual/2A202603625_TranQuocTuanKhanh.md) | Khi bắt đầu ngày làm việc, tôi muốn xác định việc cấp thiết cần giải quyết, để tập trung đúng trọng tâm. | Technical Lead và thành viên phát triển. | Gom và đánh giá thông tin từ nhiều kênh để chọn task; chưa có số phút cụ thể. | Nếu hai task cùng gấp, bạn chọn theo tiêu chí nào? (Nguyễn Bình An hỏi.) |
| 4 | [Nguyen Duc Minh](../individual/2A202603633_NguyenDucMinh.md) | Khi nhận bài từ nhiều môn, tôi muốn tổng hợp các hạn nộp, để tránh quên bài tập quan trọng. | Sinh viên đại học học nhiều môn cùng học kỳ. | Tìm và ghi deadline từ nhiều nguồn; ước tính 15–25 phút/tuần. | Quên deadline do thiếu công cụ hay không cập nhật thường xuyên? (Trần Quốc Tuấn Khanh hỏi.) |
| 5 | [Ho Quoc Toan](../individual/2A202603668-HoQuocToan.md) | Khi gặp thuật ngữ hoặc từ tiếng Anh chưa hiểu, tôi muốn hiểu nghĩa trong ngữ cảnh, để theo kịp bài giảng và tài liệu chuyên ngành. | Sinh viên chuyên ngành AI. | Dừng tra nghĩa khoảng 2 phút/từ, làm gián đoạn tập trung. | Bạn kiểm tra nghĩa thuật ngữ đúng ngữ cảnh bằng cách nào? (Chu Thân Nhất hỏi.) |
| 6 | [Chu Thân Nhất](../individual/2A202603649_ChuThanNhat.md) | Khi mở kênh YouTube hoặc tìm ý tưởng video, tôi muốn nhanh chóng nghiên cứu đối thủ và xu hướng, để chọn chủ đề có tiềm năng thu hút người xem. | Nhà sáng tạo nội dung, người quản lý kênh và nhóm sản xuất video. | Chuyển giữa nhiều kênh, thu thập và so sánh dữ liệu thủ công; ước tính 2–3 ngày với người có kinh nghiệm, khoảng 1 tuần với người mới. | Bạn nhận biết video đang tăng trưởng dựa vào chỉ số nào? (Vũ Đức Thắng hỏi.) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A – Theo dõi và tổng quan công việc | Khó theo dõi toàn bộ task từ nhiều nguồn; dễ quên nhiệm vụ cũ khi nhận nhiệm vụ mới. | Thiếu góc nhìn tổng thể về công việc đang thực hiện, trạng thái và deadline. |
| B – Ưu tiên và lựa chọn công việc | Khó quyết định nên làm task nào trước; chưa rõ mức độ quan trọng và khẩn cấp của từng nhiệm vụ (giả thuyết). | Khó xác định thứ tự ưu tiên khi có nhiều task cùng lúc. |
| C – Hỗ trợ thực hiện công việc | Chưa biết cách bắt đầu hoặc lựa chọn phương pháp, công cụ phù hợp để hoàn thành task (giả thuyết). | Cần định hướng và nguồn lực trong quá trình thực hiện nhiệm vụ. |
| D – Duy trì tập trung và động lực | Dễ mất tập trung, thiếu động lực hoặc khó duy trì thói quen hoàn thành công việc (giả thuyết). | Khó duy trì sự tập trung và tính liên tục khi làm task. |
| E – Đánh giá tiến độ và điều chỉnh kế hoạch | Khó xác định mức độ hoàn thành, thời gian còn lại và thời điểm nên tạm dừng để chuyển task (giả thuyết). | Thiếu thông tin để đánh giá tiến độ và điều chỉnh kế hoạch kịp thời. |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Giảm bỏ sót nhiệm vụ và cải thiện khả năng hoàn thành đúng hạn
         của người phải quản lý nhiều task song song.
│
├── Opportunity A: Khó nắm bắt tổng quan công việc
│   Task nằm ở nhiều nguồn; dễ quên nhiệm vụ cũ khi nhận nhiệm vụ mới.
│
│
├── Opportunity B: Khó xác định thứ tự ưu tiên
│   Chưa biết nên thực hiện công việc nào trước khi có nhiều task.
│
├── Opportunity C: Khó bắt đầu và thực thi task
│   Khó xác định cách thực hiện hoặc lựa chọn công cụ phù hợp.
│
├── Opportunity D: Khó duy trì tập trung và động lực
│   Bị phân tâm hoặc thiếu động lực với nhiệm vụ kéo dài.
│
└── Opportunity E: Khó đánh giá và điều chỉnh tiến độ
    Chưa rõ mức độ hoàn thành, thời gian còn lại và khi nào nên chuyển task.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ~~Xây dựng dashboard tổng quan task~~ → Giải pháp cho Opportunity A.
- ~~AI quyết định task nên làm~~ → Giải pháp dự kiến cho Opportunity B.
- ~~AI gợi ý cách làm và công cụ~~ → Giải pháp dự kiến cho Opportunity C.
- ~~Hệ thống phần thưởng như Duolingo~~ → Giải pháp dự kiến cho Opportunity D.
- ~~Tự động tính % hoàn thành và đề xuất pending~~ → Giải pháp dự kiến cho Opportunity E.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| A – Theo dõi và quản lý task | 5 | 4 | 5 | 3 | 5 | 5 | 5 | **32** |
| B – Xác định thứ tự ưu tiên task | 5 | 5 | 5 | 3 | 5 | 5 | 5 | **33** |
| C – Hỗ trợ thực hiện task | 5 | 4 | 5 | 3 | 5 | 5 | 5 | **32** |
| D – Duy trì tập trung và động lực | 4 | 3 | 3 | 2 | 3 | 3 | 2 | **20** |
| E – Đánh giá tiến độ và điều chỉnh kế hoạch | 5 | 5 | 4 | 4 | 5 | 5 | 5 | **33** |

**Candidate được chọn:** B – Khó xác định thứ tự ưu tiên giữa nhiều nhiệm vụ (33/35 điểm).

**Vì sao chọn:**

B đạt 33/35 điểm, đồng hạng cao nhất với E. Nhóm chọn tập trung vào quyết định “nên làm task nào tiếp theo” khi các nhiệm vụ có deadline, độ quan trọng và mức độ khẩn cấp khác nhau. Phạm vi này cụ thể, vừa sức lab và có thể so sánh các cách giải quyết từ quy tắc ưu tiên đơn giản đến AI hỗ trợ.

**Vì sao loại các candidate còn lại:**

- **A – Theo dõi và quản lý task (32/35):** Tập trung vào tổng hợp thông tin công việc. Nhóm ưu tiên nghiên cứu bước lựa chọn task sau khi đã nắm danh sách; A có thể hỗ trợ B.
- **C – Hỗ trợ thực hiện task (32/35):** Mỗi công việc cần phương pháp và công cụ khác nhau, khiến phạm vi khó giới hạn trong thời gian lab.
- **D – Duy trì tập trung và động lực (20/35):** Điểm thấp nhất, quy trình chưa rõ, tác động khó đo và nhóm ít am hiểu domain hơn các candidate khác.
- **E – Đánh giá tiến độ và điều chỉnh kế hoạch (33/35):** Đồng điểm với B, nhưng đánh giá mức độ hoàn thành và thời gian còn lại phụ thuộc nhiều dữ liệu khó chuẩn hóa. B dễ thu hẹp vào việc chọn thứ tự từ thông tin đã biết hơn.

**Xử lý bất đồng (nếu có):** Không có bất đồng. 100% thành viên thống nhất chọn B để tiếp tục nghiên cứu và kiểm chứng.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Bằng chứng ban đầu (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người dùng khó chọn task trước. | Value | 5 | 1 | Cao |
| 2 | Chọn task chưa phù hợp gây hậu quả. | Value | 5 | 1 | Cao |
| 3 | Chỉ sắp xếp theo deadline chưa đủ. | Value | 5 | 1 | Cao |
| 4 | Có đủ dữ liệu đầu vào để xếp ưu tiên. | Feasibility | 5 | 1 | Cao |
| 5 | Người dùng sẵn sàng tham khảo đề xuất. | Usability | 4 | 1 | Cần kiểm |
| 6 | Người dùng chấp nhận cung cấp dữ liệu. | Viability | 5 | 1 | Cần kiểm |

Giả định nhóm kiểm chứng trong buổi này: 1–3 qua tần suất khó khăn, thời gian cân nhắc, hậu quả và cách quản lý hiện tại. Giả định 4–6 được đối chiếu với câu trả lời hiện có để xác định phần còn thiếu bằng chứng.

### 3.2. Kiểm chứng

Cách đã dùng: Khảo sát, 27 phản hồi trong [CSV do nhóm cung cấp](../assets/cp4-khao-sat.csv). Mốc thời gian trong file: 09/11/2026, từ 11:04 đến 15:29. Xem [27 snapshot theo mẫu](../assets/cp4-interview-snapshot/README.md).

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Câu 5–6: khó khăn và thời gian cân nhắc | 27 phản hồi | 22/27 ghi nhận khó khăn ít nhất 1 lần trong 7 ngày; 13/27 gặp từ 2 lần; 12/27 cân nhắc từ 6 phút trở lên. | 5/27 không gặp khó khăn; 7/27 cân nhắc dưới 1 phút. |
| Câu 7–8: hậu quả và tình huống cụ thể | 27 phản hồi | 13/27 chọn ít nhất một hậu quả ở câu 7; 14/27 kể tình huống chọn task chưa phù hợp ở câu 8. | 14/27 chọn không gây khó khăn đáng kể ở câu 7. Câu 8 không giới hạn cùng kỳ 7 ngày; không cộng hai nhóm thành số trường hợp độc lập. |
| Câu 9–10: cách quản lý và mức độ đáp ứng | 27 phản hồi; 7 có dùng sắp xếp theo deadline | Trong 7 phản hồi có dùng deadline, 4 vẫn gặp khó khăn; 11/27 đánh giá cách hiện tại chỉ đáp ứng một phần hoặc hầu như không đáp ứng. | 3/7 phản hồi có dùng deadline không gặp khó khăn; 16/27 cho rằng cách hiện tại đáp ứng phần lớn hoặc hoàn toàn. |

Đối chiếu bằng chứng theo giả định:

| Giả định | Bằng chứng trong CSV / snapshot | Kết luận và phần cần kiểm tiếp |
|---|---|---|
| **1. Khó chọn task trước** | Câu 5: 22/27 có khó khăn; câu 6: 12/27 cân nhắc ≥6 phút. Ví dụ [02](../assets/cp4-interview-snapshot/cp4-interview-snapshot-02.md), [07](../assets/cp4-interview-snapshot/cp4-interview-snapshot-07.md). Phản bác: [03](../assets/cp4-interview-snapshot/cp4-interview-snapshot-03.md), [04](../assets/cp4-interview-snapshot/cp4-interview-snapshot-04.md) không gặp khó khăn. | **Được hỗ trợ ban đầu trong mẫu**, không đúng với mọi người. Tập trung vào nhóm gặp khó khăn lặp lại thay vì tất cả người có nhiều task. |
| **2. Chọn chưa phù hợp gây hậu quả** | Câu 7: 13/27 ghi nhận hậu quả; câu 8: 14/27 có tình huống. [02](../assets/cp4-interview-snapshot/cp4-interview-snapshot-02.md) chọn bài dễ trước rồi phải thức đêm; [18](../assets/cp4-interview-snapshot/cp4-interview-snapshot-18.md) kể trễ bàn giao 2 ngày. | **Có bằng chứng tự thuật**, chưa chứng minh quan hệ nhân quả. 14/27 không ghi nhận hậu quả đáng kể ở câu 7; cần phân biệt ưu tiên sai với thiếu thời gian, phân tâm hoặc ước lượng sai. |
| **3. Chỉ deadline chưa đủ** | Câu 9 kết hợp câu 5: 4/7 phản hồi có dùng deadline vẫn gặp khó khăn ([05](../assets/cp4-interview-snapshot/cp4-interview-snapshot-05.md), [14](../assets/cp4-interview-snapshot/cp4-interview-snapshot-14.md), [17](../assets/cp4-interview-snapshot/cp4-interview-snapshot-17.md), [22](../assets/cp4-interview-snapshot/cp4-interview-snapshot-22.md)); 3/7 không gặp. | **Hỗ trợ một phần**. Các phản hồi còn dùng cách khác, nên chưa kiểm nghiệm riêng “chỉ deadline”. Cần so sánh cùng danh sách task giữa xếp theo deadline và xếp thêm độ quan trọng, thời lượng, phụ thuộc. |
| **4. Đủ dữ liệu đầu vào** | Câu 11: 25/27 muốn biết deadline, 22/27 độ quan trọng, 8/27 thời lượng, 5/27 phụ thuộc. CSV không chứa danh sách task hiện tại với giá trị cụ thể của từng trường. | **Chưa xác nhận**. Mong muốn có thông tin khác với dữ liệu đã sẵn có. Cần kiểm tra trên danh sách task thật xem trường nào có, thiếu và mất bao lâu để bổ sung. |
| **5. Sẵn sàng tham khảo đề xuất** | Câu 12 có mong muốn được hỗ trợ; bản ghi 21 trong [CSV](../assets/cp4-khao-sat.csv) muốn phương pháp quản lý phù hợp. Chưa có câu hỏi trực tiếp hoặc thử nghiệm sử dụng đề xuất xếp ưu tiên. | **Chưa kiểm chứng trực tiếp**. Cho người dùng xem thứ tự đề xuất trên task của họ, ghi nhận chọn dùng, sửa hay bỏ và lý do; không suy từ mong muốn sang hành vi chấp nhận. |
| **6. Chấp nhận cung cấp dữ liệu** | CSV có phản hồi về trải nghiệm, nhưng không hỏi chấp nhận nhập task, chia sẻ lịch/tin nhắn, kết nối tài khoản hay giới hạn dữ liệu. | **Chưa kiểm chứng**. Cần làm rõ dữ liệu tối thiểu, phạm vi chia sẻ và thử việc nhập/chọn task chủ động; trả lời khảo sát không đồng nghĩa chấp nhận cấp quyền truy cập. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- Thu hẹp từ “mọi người có nhiều task” sang người quản lý nhiều nhiệm vụ và gặp khó khăn lặp lại khi chọn việc tiếp theo; 5/27 không gặp khó khăn và 16/27 đã thấy cách hiện tại đáp ứng phần lớn hoặc hoàn toàn.
- Tập trung vào bước chọn task kế tiếp, với thời gian cân nhắc và tình huống chọn chưa phù hợp; tách khỏi bài toán tổng hợp mọi nguồn tin, duy trì động lực và ước lượng tiến độ.
- Giữ giả định “deadline chưa đủ” ở mức cần so sánh, chưa mặc định phải dùng AI. Chưa coi dữ liệu task đầy đủ, việc chấp nhận đề xuất và chấp nhận chia sẻ dữ liệu là đã được xác nhận.

Problem sau đối chiếu: Người quản lý nhiều nhiệm vụ, thường xuyên phân vân khi chọn việc tiếp theo, cần xác định task phù hợp với deadline và độ quan trọng để giảm thời gian cân nhắc và hạn chế những lần lựa chọn dẫn đến dồn việc hoặc trễ hạn.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Ma trận Eisenhower — No AI | [Asana: Eisenhower Matrix](https://asana.com/resources/eisenhower-matrix) | Phân loại task theo khẩn cấp và quan trọng thành bốn nhóm hành động. | Quy tắc minh bạch, người dùng tự đánh giá. | Nhận định của nhóm: vẫn cần tự xác định mức độ quan trọng và xử lý thứ tự giữa các task trong cùng một nhóm. | Dùng làm phương án đơn giản để so sánh trước khi thêm AI. |
| Todoist Filters — Rule | [Todoist: Introduction to filters](https://www.todoist.com/help/todoist/features/introduction-to-filters-V98wIH) | Lọc danh sách theo ngày, mức ưu tiên, nhãn và dự án để thu hẹp task cần xem. | Có thể kết hợp nhiều điều kiện theo quy tắc. | Nhận định của nhóm: bộ lọc chỉ hữu ích khi các thuộc tính task được điền; chưa chứng minh giảm thời gian chọn task cho nhóm người dùng này. | Thử kết hợp ngày và mức ưu tiên; ghi trường dữ liệu thiếu và thời gian bổ sung. |
| Motion Auto-scheduling | [Motion: Auto-scheduling](https://www.usemotion.com/help/time-management/auto-scheduling) | Xếp task vào lịch theo thời lượng, deadline, mức ưu tiên và thời gian trống; điều chỉnh khi lịch thay đổi. | Đã có chức năng kết hợp nhiều yếu tố và tự sắp lịch. | Theo tài liệu, hard deadline có thể khiến task được xếp ngoài giờ làm; nhận định của nhóm: đầu vào thiếu hoặc sai cần được thử trước khi dựa vào lịch đề xuất. | Nhu cầu đã có công cụ xử lý một phần; so sánh với cách có sẵn, giới hạn giờ làm và cho người dùng kiểm tra. |


---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```
flowchart TD
    S1["S1. Nhận bài/việc mới<br/>LMS, nhóm chat, email, giảng viên"]
    S2["S2. Thông tin được giữ nguyên<br/>trong từng nguồn riêng lẻ"]
    S3["S3. Người học nhớ và chọn bài<br/>dựa trên trí nhớ"]
    S4["S4. Tìm lại yêu cầu và hạn nộp<br/>trong nguồn tương ứng"]
    S5["Bắt đầu thực hiện bài/việc"]

    S1 --> S2 --> S3 --> S4 --> S5

    style S3 fill:#fff2cc,stroke:#d6a500
    style S4 fill:#f4cccc,stroke:#cc0000

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 |Người học |Thông báo giao bài, yêu cầu của giảng viên, hạn nộp | Biết có bài tập/công việc mới|Chưa đo |Thông tin đến từ LMS, nhóm chat, email và giảng viên trên lớp. |
| 2 |Người học |Thông tin từ các nguồn khác nhau | Thông tin vẫn nằm phân tán trong từng nguồn | Chưa đo|Chưa có danh sách chung để tổng hợp bài tập và công việc.|
| 3 |Người học | Những bài tập/công việc còn nhớ|Một bài được chọn để thực hiện |Khoảng 2 phút/lần chọn|Quyết định chủ yếu dựa vào trí nhớ, chưa có cơ chế xếp hạng ưu tiên |
| 4 |Người học|Bài tập/công việc đã chọn | Tìm được yêu cầu và hạn nộp để bắt đầu làm|Khoảng 10 phút/lần tìm |Phải truy cập lại nguồn tương ứng để tìm thông tin. |
| 5 |Người học |Yêu cầu và hạn nộp đã tìm được | Có đủ thông tin để bắt đầu làm bài/việc|Chưa đo |Chưa có dữ liệu về thời gian hoàn thành hoặc hiệu quả của bước này. |

**Bottleneck chính:**
Thông tin bị phân tán: Bài tập và công việc nằm ở nhiều nguồn khác nhau (LMS, nhóm chat, email, thông báo trực tiếp), chưa được tổng hợp thành một danh sách thống nhất.

Phụ thuộc vào trí nhớ: Người học lựa chọn công việc dựa trên những gì còn nhớ, dẫn đến nguy cơ bỏ sót nhiệm vụ hoặc lựa chọn sai thứ tự ưu tiên.

Mất thời gian tìm kiếm: Việc tìm lại yêu cầu và hạn nộp mất khoảng 10 phút mỗi lần. Nếu tính cả thời gian lựa chọn công việc (khoảng 2 phút), tổng thời gian ước tính là 12 phút cho một lượt có cả hai công đoạn.

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

- [CSV khảo sát do nhóm cung cấp — 27 phản hồi](../assets/cp4-khao-sat.csv).
- [Danh sách 27 snapshot khảo sát](../assets/cp4-interview-snapshot/README.md).
- [Asana — The Eisenhower Matrix](https://asana.com/resources/eisenhower-matrix), truy cập 09/11/2026.
- [Todoist — Introduction to filters](https://www.todoist.com/help/todoist/features/introduction-to-filters-V98wIH), truy cập 09/11/2026.
- [Motion — Auto-scheduling](https://www.usemotion.com/help/time-management/auto-scheduling), truy cập 09/11/2026.
