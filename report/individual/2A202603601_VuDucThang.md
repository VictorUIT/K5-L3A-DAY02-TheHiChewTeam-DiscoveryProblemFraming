# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Đức Thắng
- MSSV: 2A202603601
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: TheHiChewTeam
- Link repo nhóm:https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Khi tôi tiếp nhận feedback từ nhiều người, nhiều kênh nhưng không biết feedback nào cần ưu tiên để tránh trễ deadline.|Trưởng nhóm , thành viên | Feedback xuất hiện từ nhiều kênh: Email, Zalo, Messenger, Jira, Google Forms, mất nhiều thời gian tổng hợp  | |
| 2 |Khi tra cứu thông tin, tài liệu học tập , tôi muốn biết thông tin vào đáng tin, và được phép trích dẫn , để trách dùng nguồn có thông tin sai lệch |Sinh viên,học sinh, người cần tìm tài liệu| Thông tin không thống nhất giữa các nguồn| |
| 3 |Khi cuối tháng, tôi muốn biết tiền đã tiêu vào những nhóm nào, để hiểu vì sao ngân sách bị vượt |Cá nhân, sinh viên,người đi làm,gia đình. |Phát sinh giao dịch mỗi ngày từ tiền mặt, chuyển khoản, ví. Có thể phát sinh với tần suất từ 5-20 |  |
| 4 |Khi có nhiều cuộc hẹn và việc cá nhân, tôi muốn biết việc nào có thể bị trễ hoặc xung đột, để chủ động sắp xếp lại | Cá nhân, sinh viên , người đi làm | Có nhiều cuộc hẹn trong 1 ngày, Các cuộc hẹn quá sát giờ nhau thời gian di chuyển không đủ  | |
| 5 |Khi nhận thấy mình ngủ hoặc vận động kém trong nhiều ngày, tôi muốn biết nguyên nhân liên quan đến thói quen nào, để điều chỉnh sớm |Người đi làm , sinh viên |Thời gian ngủ thấp hơn nhu cầu cá nhân trong nhiều ngày liên tiếp, thời gian vận động dưới mục tiêu đặt ra, số bước chân giảm so với mức trung bình 7 ngày trước, Thời gian sử dụng điện thoại vào ban đêm| |
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | AI phân tích và ưu tiên Feedback từ nhiều kênh | Có Actor rõ, có thể đo thời gian xử lý, phân loại feedback, phát hiện trùng lặp và mức độ ưu tiên | Cần khảo sát cách các nhóm dự án hiện đang xử lý feedback và xác định mức độ ảnh hưởng đến deadline |
| 2 | AI phân tích và quản lý chi tiêu cá nhân| Giúp người dùng biết tiền được sử dụng vào đâu, phát hiện nhóm chi tiêu tăng bất thường và cảnh báo vượt ngân sách | Cần dữ liệu giao dịch thực tế và giải quyết việc phân loại các khoản chi không rõ nội dung. |
| 3 | AI kiểm chứng độ tin cậy của nguồn thông tin | Giúp sinh viên, người nghiên cứu xác minh nguồn, đối chiếu thông tin và trích dẫn chính xác. | Khó xác định độ tin cậy tuyệt đối của một nguồn thông tin |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận feedback từ nhiều người ở nhiều kênh, tôi muốn biết feedback nào cần ưu tiên, để không sửa lan man và trễ deadline. |
| Actor |Trưởng nhóm , thành viên |
| Thời điểm / bối cảnh | Khi đang phát triển sản phẩm, khi đang làm việc gì đó mà có đội nhóm |
| Quy trình hiện tại (3–7 bước) |Nhận feedback từ nhiều kênh, Đọc từng phản hồi, Tổng hợp vào một nơi, Tìm phản hồi trùng lặp, Đánh giá mức độ quan trọng , Đưa ra feedback quan trọng cần ưu tiên|
| Bottleneck (bước nào, mất bao nhiêu phút) | Tổng hợp và phân loại feedback thủ công , mất khoảng 50 phút - 100 phút  |
| Impact (nếu không giải thì sao) | Bỏ lỡ phần quan trọng ,tốn thời gian trong việc tổng hợp|
| Success metric (baseline → target) | Giảm thời gian tổng hợp , Độ chính xác khi phân loại feedback quan trọng |
| Phương án không dùng AI | Sử dụng Google Forms, Trello, Jira hoặc Excel để tập trung feedback và phân loại bằng quy tắc thủ công.|
| Giả thuyết về AI (nếu có) | AI có thể đọc nội dung, phân loại phản hồi, phát hiện nội dung trùng lặp, đánh giá mức độ nghiêm trọng và đề xuất thứ tự xử lý |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

Nhận feedback từ nhiều kênh -> Đọc và tổng hợp thủ công->Phân loại phản hồi->Tìm feedback trùng lặp->Xác định mức độ ưu tiên

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cuối tháng, tôi muốn biết tiền đã tiêu vào những nhóm nào, để hiểu vì sao ngân sách bị vượt |
| Actor | Cá nhân, sinh viên,người đi làm,gia đình|
| Thời điểm / bối cảnh | Khi phát sinh giao dịch hằng ngày và khi tổng kết tài chính cuối tháng|
| Quy trình hiện tại (3–7 bước) | Phát sinh giao dịch mua sắm hoặc thanh toán->Ghi nhận khoản chi->Nhập số tiền vào ứng dụng->Phân loại khoản chi->Tổng hợp->So sánh->Tìm nguyên nhân|
| Bottleneck (bước nào, mất bao nhiêu phút) | Ghi chép và phân loại các giao dịch thủ công, giả định mất 20–40 phút/ngày nếu có nhiều giao dịch|
| Impact (nếu không giải thì sao) |Không kiểm soát được dòng tiền, phát hiện vượt ngân sách muộn, khó xác định nhóm chi tiêu gây lãng phí |
| Success metric (baseline → target) | Thời gian phân loại: 30 -> 5 phút/ngày.Độ chính xác phân loại giao dịch: mục tiêu từ 90%.Tỷ lệ giao dịch được phân loại: mục tiêu 100%|
| Phương án không dùng AI | Sử dụng Excel, Google Sheets hoặc ứng dụng quản lý tài chính có quy tắc phân loại giao dịch.|
| Giả thuyết về AI (nếu có) | AI có thể đọc nội dung giao dịch, phân loại chi tiêu, phát hiện khoản chi bất thường và phân tích nguyên nhân ngân sách bị vượt|
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:
Phát sinh giao dịch->Ghi nhận khoản chi->Nhập dữ liệu vào hệ thống->Phân loại->Tổng hợp->Só sánh->Phân tích vì sao vượt

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tra cứu thông tin, tài liệu học tập , tôi muốn biết thông tin vào đáng tin, và được phép trích dẫn , để trách dùng nguồn có thông tin sai lệch |
| Actor | Sinh viên, học sinh, người cần tìm tài liệu|
| Thời điểm / bối cảnh |Khi học tập , làm bài tập lớn, chuẩn bị luận văn |
| Quy trình hiện tại (3–7 bước) |Tìm kiếm thông tin trên Internet->Mở nhiều website và tài liệu->Kiểm tra tác giả và đơn vị xuất bản->Kiểm tra thời gian xuất bản->Đối chiếu thông tin giữa các nguồn |
| Bottleneck (bước nào, mất bao nhiêu phút) | Kiểm tra độ tin cậy và đối chiếu nội dung giữa các nguồn, giả định mất 30–60 phút/chủ đề. |
| Impact (nếu không giải thì sao) | Sử dụng thông tin sai lệch, trích dẫn tài liệu không chính thống ảnh hướng đến quá trình học tập và làm việc|
| Success metric (baseline → target) |Thời gian kiểm chứng: 45 -> 15 phút/chủ đề.Tỷ lệ truy xuất được nguồn gốc: mục tiêu từ 95%.
Tỷ lệ trích dẫn đúng định dạng và đúng tài liệu: mục tiêu từ 95%. |
| Phương án không dùng AI | Kiểm tra thủ công thông qua Google Scholar, thư viện trường, website của cơ quan xuất bản và các cơ sở dữ liệu học thuật |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

Tìm kiếm thông tin->Mở nhiều nguồn tài liệu->Kiểm tra tác giả và đơn vị xuất bản->Đối chiếu nội dung giữa các nguồn->Đánh giá độ tin cậy

### Card muốn pitch nhất

- Card số: 2
- Vì sao: tôi muốn quản lý chi tiêu 1 cách hợp lý , muốn biết được khoản nào đang chi tiêu vượt mức, muốn biết 
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Cách đặt tên “AI phân tích và ưu tiên feedback” đã đưa giải pháp vào problem, trong khi problem cần mô tả việc xử lý feedback. | Đồng ý | Đổi thành: “Khi nhận feedback từ nhiều người ở nhiều kênh, tôi muốn xác định feedback nào cần ưu tiên, để tập trung sửa các vấn đề ảnh hưởng đến deadline.” |
| Card #1 chưa nêu rõ feedback đến từ những kênh nào, tần suất bao nhiêu và bước nào thực sự mất nhiều thời gian nhất. | Đồng ý | Bổ sung các kênh thực tế, số feedback trong một chu kỳ và đo riêng thời gian đọc, gom nhóm, loại trùng và ưu tiên thay vì gộp thành 50–100 phút. |
| Success metric của Card #1 còn chung chung (“giảm thời gian”, “độ chính xác”), chưa có baseline, target và cách đo. | Đồng ý | Sửa thành dạng đo được, ví dụ: thời gian xử lý từ 80 phút xuống dưới 30 phút/lần; ít nhất 90% feedback được gắn đúng nhóm và mức ưu tiên qua kiểm tra thủ công trên một mẫu cố định. |
| Card #2 và #3 đang dùng số liệu “giả định”, đồng thời phạm vi actor quá rộng nên chưa chứng minh được đây là pain của một nhóm cụ thể. | Đồng ý | Ghi rõ số liệu là cần kiểm chứng; thu hẹp actor và bối cảnh, ví dụ sinh viên tự quản lý chi tiêu trong tháng hoặc sinh viên kiểm chứng nguồn khi làm bài nghiên cứu. Chỉ giữ baseline sau khi bấm giờ hoặc ghi nhận giao dịch thực tế. |
| Card #3 mô tả “độ tin cậy tuyệt đối” quá khó đo và có nguy cơ để AI tự kết luận nguồn đúng/sai. | Đồng ý | Đổi mục tiêu thành kiểm tra các dấu hiệu có thể quan sát: tác giả, đơn vị xuất bản, ngày xuất bản, nguồn gốc trích dẫn và mức độ nhất quán giữa các nguồn; vẫn để người dùng quyết định nguồn cuối cùng. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
