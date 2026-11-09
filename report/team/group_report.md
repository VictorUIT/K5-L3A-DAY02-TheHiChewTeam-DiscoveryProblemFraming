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

Bối cảnh
Đối tượng nghiên cứu là những người phải quản lý và thực hiện nhiều công việc cùng lúc, chẳng hạn người làm nhiều công việc, nhân viên tham gia nhiều dự án hoặc sinh viên vừa học vừa làm.

Các nhiệm vụ được giao thông qua nhiều nguồn như Zalo, Messenger, Telegram, Discord, email hoặc các công cụ quản lý công việc. Thông tin về deadline, yêu cầu, mức độ quan trọng và tiến độ có thể nằm rải rác ở những nguồn khác nhau.

Trong quy trình hiện tại được ghi nhận từ trải nghiệm người dùng, việc theo dõi nhiệm vụ chủ yếu dựa vào trí nhớ và việc đọc lại tin nhắn. Khi tiếp nhận nhiệm vụ mới, người dùng có thể bỏ quên những nhiệm vụ cũ hoặc khó xác định công việc nào cần được ưu tiên.

```
flowchart TD
    A["1. Tiếp nhận nhiệm vụ từ nhiều nguồn<br/>Chat, email, công cụ quản lý"]
    B["2. Ghi nhớ hoặc theo dõi task riêng lẻ<br/>Thông tin chưa được tổng hợp đầy đủ"]
    C["3. Kiểm tra các nhiệm vụ đang có<br/>Nhớ task cũ, tìm lại thông tin"]
    D["4. Xem deadline, yêu cầu<br/>và mức độ quan trọng"]
    E["5. So sánh và quyết định<br/>task cần làm trước"]
    F["6. Thực hiện công việc đã chọn"]
    G{"Có task mới<br/>phát sinh?"}
    H(["Tiếp tục thực hiện kế hoạch"])

    A --> B --> C --> D --> E --> F --> G
    G -->|Có| A
    G -->|Không| H

    classDef bottleneck fill:#fff0d9,stroke:#c57b13,color:#633d0b,stroke-width:2px
    class E bottleneck

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Người quản lý nhiều công việc|Thông báo, tin nhắn, email và yêu cầu từ người giao việc | Nhận biết có nhiệm vụ mới cần thực hiện| Chưa đo|Nhiệm vụ phát sinh từ nhiều nguồn |
| 2 | Người dùng| Những nhiệm vụ đã tiếp |Thông tin nhiệm vụ được ghi nhớ hoặc lưu tại từng nguồn |Chưa đo |Chưa có danh sách tổng hợp đầy đủ trong quy trình được mô tả |
| 3 | Người dùng| Trí nhớ, tin nhắn cũ, email hoặc danh sách công việc đang có|Xác định những nhiệm vụ còn phải thực hiện |Chưa đo; được người dùng mô tả là tốn thời gian | Có nguy cơ bỏ sót nhiệm vụ|
| 4 |Người dùng |Deadline, yêu cầu, độ quan trọng và thông tin liên quan | Thông tin phục vụ việc lựa chọn thứ tự ưu tiên| Chưa đo|Một số thông tin có thể thiếu hoặc cần tìm lại |
| 5 | Người dùng| Danh sách nhiệm vụ và thông tin đã thu thập| Quyết định nhiệm vụ cần thực hiện trước|Chưa đo; có thể mất thời gian cân nhắc |Bottleneck nghiên cứu của Candidate B |
| 6 | Người dùng| Nhiệm vụ được lựa chọn|Bắt đầu hoặc tiếp tục thực hiện công việc |Chưa đo | Thứ tự công việc có thể thay đổi khi phát sinh nhiệm vụ mới|

**Bottleneck chính:**
Bottleneck được nhóm tập trung nghiên cứu là việc xác định thứ tự ưu tiên giữa nhiều nhiệm vụ khi thông tin chưa được tổng hợp đầy đủ và các yếu tố ưu tiên chưa được đánh giá một cách nhất quán.

Khi nhiều nhiệm vụ cùng tồn tại, người dùng phải tự cân nhắc deadline, mức độ quan trọng, thời gian dự kiến, mức độ hoàn thành và những yêu cầu phát sinh. Việc đánh giá phụ thuộc vào trí nhớ, thông tin thu thập được và kinh nghiệm cá nhân.

Ngoài ra, việc phải tìm lại yêu cầu công việc từ nhiều nguồn có thể khiến quá trình ra quyết định mất thêm thời gian và dễ bỏ sót thông tin quan trọng.

Dữ liệu tự thuật đã ghi nhận tình trạng quên nhiệm vụ khi chuyển giữa các công việc, làm phát sinh nhu cầu tìm lại yêu cầu và phải làm gấp để kịp deadline. Nhóm cũng cho biết đã tiến hành thu thập bổ sung thông tin ở CP4.

Giới hạn bằng chứng: Hiện chưa có số liệu bấm giờ đáng tin cậy cho từng bước và tổng thời gian của quy trình. Chưa đủ cơ sở kết luận bước lựa chọn ưu tiên là bước mất nhiều phút nhất hoặc là nguyên nhân trực tiếp của mọi trường hợp trễ hạn.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước |6 bước |6 bước |Quy trình không nhất thiết giảm số bước, nhưng thay đổi cách xử lý và mức độ hỗ trợ |
| Tổng thời gian |Chưa có số liệu đo thực tế; người dùng ghi nhận việc tìm kiếm và cân nhắc mất thời gian |Kỳ vọng giảm so với quy trình hiện tại; chưa xác định số phút cụ thể | Cần đo baseline và thử nghiệm mới xác định mức cải thiện|
| Số bước thủ công | 6/6 bước|3/6 bước (bước 1, 5 và 6) |Bước 2–4 do Rule/AI hỗ trợ; bước 6 còn cần người dùng cập nhật tiến độ |
| Bottleneck chính |Khó lựa chọn task ưu tiên khi thông tin phân tán và phải tự cân nhắc nhiều yếu tố |Kiểm tra, đánh giá mức độ phù hợp của phương án AI đề xuất | Bottleneck tương lai chưa được kiểm chứng|
| Rủi ro mới phát sinh |Quên task, thiếu thông tin, lựa chọn ưu tiên chưa nhất quán |AI đề xuất sai, dữ liệu đầu vào thiếu, người dùng phụ thuộc quá mức vào hệ thống |Kiểm soát bằng giải thích đề xuất, xác nhận thủ công và Fallback |

Success Metric dự kiến

| Chỉ số | Baseline | Target | Cách đo | 
|---:|---|---|---|
| 1 |Thời gian xác định thứ tự ưu tiên |Chưa đo; người dùng cho biết quá trình này có thể mất thời gian |Giảm so với baseline sau khi đo; ngưỡng cụ thể cần nhóm chốt | Bấm giờ từ khi bắt đầu xem danh sách task đến khi xác nhận thứ tự ưu tiên |
| 2 | Thời gian tìm kiếm lại thông tin nhiệm vụ| Chưa đo; được phản ánh là tốn thời gian| Giảm so với baseline sau khi đo| Bấm giờ từ lúc bắt đầu tìm đến khi tìm đúng thông tin|
| 3 |Tỷ lệ task bị bỏ sót |Chưa có baseline định lượng đáng tin cậy cho nhóm người dùng mục tiêu |Giảm so với baseline sau kiểm chứng | Theo dõi số task bỏ sót trên tổng số task được giao trong một khoảng thời gian|
| 4 |Tỷ lệ task hoàn thành đúng hạn |Chưa xác định | Cải thiện so với baseline| Đối chiếu thời hạn và thời điểm hoàn thành thực tế|
| 5 |Mức độ phù hợp của thứ tự AI đề xuất | Chưa có vì chưa thử nghiệm AI|Cần xác định qua thử nghiệm với người dùng |Ghi nhận tỷ lệ đề xuất được chấp nhận và lý do điều chỉnh |

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

# 8. Quyết định (CP6)

## 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | AI có tạo thêm giá trị và được dùng không? | **Cao** | CP4 hỗ trợ ban đầu cho nhu cầu ưu tiên task, nhưng 16/27 phản hồi thấy cách hiện tại đáp ứng phần lớn hoặc hoàn toàn. Chưa có đối chứng AI–Rule hoặc hành vi chấp nhận đề xuất; giả định 5 chưa được kiểm chứng trực tiếp. |
| **Usability** | Người dùng có hiểu và sửa được kết quả không? | **Trung bình** | CP5 có cơ chế xem lý do, sửa và duyệt, nhưng chưa thử thao tác với người dùng; công nhập liệu có thể làm tăng tổng thời gian. |
| **Feasibility** | Dữ liệu có đủ để xếp ưu tiên không? | **Cao** | Giả định 4 của CP4 chưa xác nhận. Câu 11 phản ánh thông tin mong muốn, không chứng minh task hiện tại có đủ giá trị deadline, độ quan trọng, thời lượng và phụ thuộc. |
| **Viability** | Có phù hợp quyền truy cập, chi phí và vận hành không? | **Trung bình** | Giả định 6 chưa được kiểm chứng; task có thể chứa nội dung cá nhân/nội bộ. Phạm vi thử giới hạn ở task người dùng chủ động cung cấp, chưa kết nối tự động chat/email; cần đo chi phí và thống nhất phạm vi sử dụng dữ liệu. |

## 8.2. Kết luận

**Quyết định: Not Yet.** Chưa triển khai Workflow AI hoặc mở rộng sản phẩm trước khi xử lý hai rủi ro Cao: giá trị tăng thêm so với Rule và mức đầy đủ dữ liệu đầu vào.

**Lý do:** Giữ thiết kế To-Be của CP5 và lựa chọn Workflow để kiểm chứng, nhưng chưa có baseline bấm giờ, danh sách task đủ thuộc tính và thử nghiệm người dùng chấp nhận đề xuất. Có quy trình và sơ đồ chưa chứng minh cần AI hoặc đã đủ điều kiện bắt đầu pilot AI.

**Việc thực hiện trước khi xem xét Go:**

1. Tuyển 3–5 người thuộc Actor mục tiêu, có khó khăn lặp lại khi chọn việc tiếp theo; thống nhất task và trường dữ liệu được phép sử dụng. Trả lời khảo sát không đồng nghĩa chấp nhận chia sẻ lịch hoặc tin nhắn.
2. Ghi task trong 1 tuần. Trường tối thiểu: ID/tên, deadline hoặc xác nhận không có hạn, độ quan trọng và trạng thái; phụ thuộc cần được xác nhận. Bổ sung thời lượng và thời gian khả dụng khi kiểm tra xung đột thời gian. Ghi công bổ sung dữ liệu, không âm thầm loại task thiếu.
3. Đo ít nhất 10 lượt chọn ưu tiên As-Is trên nhóm thử và xây dựng đối chứng Rule. Tính công tìm lại thông tin, nhập/cập nhật, kiểm tra và xác nhận theo các ranh giới ở mục 7.
4. Thử prototype hiển thị lý do, sửa và xác nhận. Sau khi dữ liệu, phạm vi sử dụng và baseline sẵn sàng, mới xem xét bắt đầu pilot AI; quyết định hiện tại vẫn là Not Yet.

**Pilot nhỏ nhất sau khi đủ điều kiện:** 3–5 người trong 2 tuần, có ít nhất 10 cặp lượt lập kế hoạch so sánh được giữa Rule và Workflow AI. Dùng cùng bản sao dữ liệu task và bộ ràng buộc; thay đổi thứ tự thử hai phương án giữa các lượt/người để giảm ảnh hưởng ghi nhớ. Ghi kết quả từng người, không coi số lượt là số người độc lập.

- **Rule:** Người dùng áp dụng checklist/quy tắc ưu tiên minh bạch và chốt kết quả.
- **Workflow:** Giữ nguyên sáu bước CP5; AI chỉ đề xuất ở bước 4, người dùng duyệt ở bước 5.
- **Đo:** Tổng thời gian kể cả công nhập, chờ xử lý và sửa; chất lượng đầu ra theo năm tiêu chí; lý do bỏ hoặc chỉnh đề xuất; task bỏ sót và đúng hạn.
- **Xét tiếp tục:** Chỉ xem xét Go cho bước thử tiếp theo nếu đạt target tổng thời gian, mức phù hợp, tiêu chí an toàn và không làm xấu các chỉ số bỏ sót/đúng hạn. Không suy rộng thành hiệu quả đã chứng minh cho mọi người dùng.

**Ngưỡng dừng:**

| Điều kiện | Ngưỡng / thời điểm đánh giá | Hành động |
|---|---|---|
| Dữ liệu đầu vào | Sau 1 tuần, dưới 60% task có đủ trường tối thiểu đã thống nhất | Chưa bắt đầu pilot AI; sửa cách nhập/cập nhật và kiểm chứng lại giả định 4. |
| Tính đúng đắn và quyền kiểm soát | Bất kỳ lượt nào AI tự sửa dữ liệu gốc, bỏ sót task khẩn cấp, vi phạm phụ thuộc cứng hoặc hệ thống áp dụng khi chưa được duyệt | Dừng ngay phần AI, quay về Rule/thủ công và kiểm tra nguyên nhân. |
| Mức phù hợp | Sau ít nhất 10 lượt hợp lệ, trên 30% lượt phải sửa vì AI hiểu sai dữ liệu/ngữ cảnh | Không mở rộng; xem lại dữ liệu và cách đề xuất. |
| Mức sử dụng | Trong 2 tuần thử, gợi ý bị bỏ qua vì không hữu ích ở trên 50% số ngày có dùng hệ thống và có phát sinh nhu cầu chọn task | Xem lại Value/Usability; không mở rộng thành phần AI. |
| Giá trị tăng thêm | Kết thúc 2 tuần và có ít nhất 10 cặp lượt hợp lệ, trung vị tổng thời gian Workflow không giảm ít nhất 20% so với Rule, hoặc làm xấu tỷ lệ bỏ sót/đúng hạn | Giữ Rule/checklist; chưa tiếp tục đầu tư AI theo giả thuyết hiện tại. |
| Chi phí và phạm vi dữ liệu | Vượt mức chi phí đã thống nhất trước thử hoặc xử lý ngoài dữ liệu người dùng cho phép | Dừng phần AI, kiểm tra cấu hình/phạm vi sử dụng trước khi thử lại. |

Các phần trăm, thời lượng và quy mô thử ở mục 7–8 là **mục tiêu thiết kế thử nghiệm**, không phải kết quả thu thập và không phải tiêu chuẩn chung cho mọi sản phẩm.

**Phương án thay thế:** Tiếp tục danh sách task tập trung, kiểm tra dữ liệu, lọc theo Rule và sắp xếp thủ công như fallback của CP5. Nếu cách này đủ đáp ứng, không cần nâng lên AI hoặc Agent.

---
## 9. Hạn chế và hướng tiếp theo

---

## 9. Hạn chế và hướng tiếp theo
Hạn chế của quá trình nghiên cứu và phương án đề xuất:

1. Thiếu số liệu thời gian đo trực tiếp. Người dùng đã phản ánh việc tìm lại thông tin và quyết định thứ tự ưu tiên mất thời gian, nhưng nhóm chưa có số phút đáng tin cậy cho từng bước hoặc toàn bộ quy trình. Vì vậy, chưa thể kết luận hệ thống sẽ tiết kiệm bao nhiêu thời gian hay sử dụng các mốc 60 phút → 15/20 phút làm kết quả thực tế.
   
2. Bằng chứng về tác động chưa xác lập quan hệ nhân quả. Việc quên task, phải tìm lại yêu cầu hoặc làm gấp đã xuất hiện trong trải nghiệm người dùng. Tuy nhiên, chưa thể khẳng định tất cả những tình huống đó đều do xác định sai thứ tự ưu tiên; thông tin phân tán và cách theo dõi task cũng có thể đóng góp vào vấn đề.

3. Khả năng khái quát hóa còn hạn chế. Actor mục tiêu bao gồm người quản lý nhiều công việc cùng lúc, nhưng nhu cầu của từng nhóm (người làm nhiều dự án, sinh viên vừa học vừa làm, nhân viên văn phòng...) có thể khác nhau. Những dữ liệu thu thập tại CP4 cần được đối chiếu theo nguồn và cách lấy mẫu trước khi suy rộng cho toàn bộ đối tượng.

4. Quy trình To-Be mới là thiết kế, chưa được kiểm nghiệm. Nhóm chưa đo thời gian nhập liệu, kiểm tra thông tin, AI phân tích, người dùng duyệt và cập nhật tiến độ; do đó chưa biết phần thời gian tiết kiệm có đủ bù cho công nhập liệu và kiểm tra đề xuất hay không.

5. Chất lượng AI phụ thuộc dữ liệu đầu vào. Task có thể thiếu deadline, độ quan trọng, thời gian dự kiến hoặc quan hệ phụ thuộc. AI có nguy cơ đánh giá sai mức khẩn cấp, bỏ sót ràng buộc hoặc tạo lý do không có căn cứ. Hệ thống cần báo thiếu dữ liệu, giải thích đề xuất, cho phép sửa thủ công và không tự áp dụng quyết định.

6. Tính khả thi tích hợp và bảo mật chưa được xác nhận. Việc thu thập dữ liệu từ Zalo, Messenger, Telegram, email hay các công cụ quản lý phụ thuộc quyền truy cập và khả năng tích hợp của từng nền tảng. Nội dung task có thể chứa dữ liệu cá nhân/nội bộ nên không mặc định được phép chuyển sang mô hình AI bên ngoài.

7. Chưa chứng minh giá trị tăng thêm của AI so với Rule. Phân tích đa yếu tố và đề xuất theo ngữ cảnh là định hướng nhóm lựa chọn, nhưng mức hiệu quả cần được kiểm tra trên cùng bộ task so với checklist hoặc quy tắc ưu tiên đơn giản. Workflow có AI là phương án để thử nghiệm, không phải kết quả đã được xác nhận là tối ưu.

Hướng tiếp theo:

* Đo baseline thực tế: Theo dõi các lượt xác định thứ tự ưu tiên của người dùng, bấm giờ từng công đoạn và toàn quy trình, đồng thời ghi nhận task bị bỏ sót hoặc trễ hạn. Không tính các câu trả lời mô phỏng thành dữ liệu khảo sát thực tế.
* Thử nghiệm pilot quy mô nhỏ: Dùng danh sách task thực tế đã được người tham gia cho phép sử dụng; so sánh hai phương án Rule/checklist và Workflow có AI đề xuất ưu tiên trên các trường hợp tương đương, có cả task phát sinh hoặc deadline xung đột.
* Đánh giá đầu ra và trải nghiệm: Kiểm tra AI có bỏ sót task, làm sai deadline, suy diễn dữ liệu hay không; ghi nhận lý do người dùng thay đổi thứ tự gợi ý, thời gian toàn quy trình và tỷ lệ hoàn thành đúng hạn. Chốt ngưỡng thành công trước khi pilot.
* Kiểm soát quyền riêng tư và phạm vi hệ thống: Chỉ dùng dữ liệu được cấp quyền, ưu tiên nhập thủ công ở pilot; xác minh khả năng tích hợp từng nền tảng trước khi triển khai tự động. Người dùng luôn duyệt kết quả cuối cùng; khi AI không phù hợp thì quay về Rule hoặc sắp xếp thủ công.
* Ra quyết định sau thử nghiệm: Dựa trên kết quả đo để tiếp tục Workflow có AI, tinh chỉnh quy tắc, hoặc chỉ duy trì giải pháp No AI/Rule nếu AI không đem lại lợi ích đủ rõ.


## 10. Tài liệu tham khảo

1. [CP4 — Assumption Map, đối chiếu bằng chứng và research của nhóm](https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming/blob/main/report/team/group_report.md), mục 3.
2. [CSV khảo sát do nhóm cung cấp — 27 phản hồi](../assets/cp4-khao-sat.csv).
3. [Danh sách 27 snapshot khảo sát](../assets/cp4-interview-snapshot/README.md).
4. **CP5_da_chen_Mermaid.md** — bản CP5 được dùng làm nguồn cho As-Is, To-Be, Problem Statement v0, Boundary và Fallback; giữ nguyên file CP5 khi chỉnh CP6.
5. [Asana — The Eisenhower Matrix](https://asana.com/resources/eisenhower-matrix), truy cập 09/11/2026.
6. [Todoist — Introduction to filters](https://www.todoist.com/help/todoist/features/introduction-to-filters-V98wIH), truy cập 09/11/2026.
7. [Motion — Auto-scheduling](https://www.usemotion.com/help/time-management/auto-scheduling), truy cập 09/11/2026.
8. [Worksheet của lab](https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming/blob/main/docs/01-worksheet.md) — ma trận, mức can thiệp, Problem Statement v1 và quyết định theo bốn rủi ro.
