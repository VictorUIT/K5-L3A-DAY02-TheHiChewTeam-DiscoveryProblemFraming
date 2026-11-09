# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Chu Thân Nhất
- MSSV:20A202603649
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: TheHiChewTeam
- Link repo nhóm:https://github.com/VictorUIT/K5-L3A-DAY02-TheHiChewTeam-DiscoveryProblemFraming 

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.
Problem: quản lý kênh youtube nhiều kênh mất nhiều thời gian và khó mở rộng

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian |Khi bắt tay vào 1 kênh mới thì luôn cần phải tìm kiếm đối thủ, video đối thủ, hiện đang hot trend vấn đề gì ...  |Bản thân | Mất thời gian 2-3 ngày để khảo sát 1 chủ đề đối với người làm lâu, mất 1 tuần đối với người mới |
| 2 | Lặp lại |Khi tôi cần tìm nội dung biên soạn cho 1 video, tôi phải tìm kiếm âm thanh nền, hình ảnh video phù hợp với chủ đề đang làm, sound effect trên internet hoặc trong kho biên tập cũ | Bản thân  | Mất thời gian (không cố định) tìm trên internet đối với những nội dung mới làm không quen vì chưa biết nguồn, hình ảnh, key phù hợp|
| 3 |Lặp lại |Làm thumbnail  hoặc sản xuất video. lấy video trên internet   | bản thân |mất thời gian idea, làm photoshop, thời gian quay chụp 1-2h
| 4 |Tốn thời gian | Biên tập video bằng capcut theo ý tưởng video đề ra  | Bản thân | Mất 1-2 h cho mỗi video, quản lý 5 kênh tốn 5h/ ngày|
| 5 |Lặp lại |tối ưu từ khóa SEO trên mỗi video/ mỗi kênh làm thế nào luốn được chấm điểm cao, đúng trend |Bản thân | Lặp lại mỗi 1 video, mỗi lần đăng là 1 lần SEO khác nhau 5-10p mỗi video |
| 6 | Lặp lại |Theo dõi chỉ số video sau khi đăng. Kiểm tra lại các chỉ số phân tích của từng video CTR, AVD, Tổng thời gian xem, tương tác like, share, video nào đang nổi lên nhanh, video nào có vấn đề cần được xem lại   | Bản thân | Việc lặp lại rất thường xuyên, mỗi kênh số lượng video hàng chục/ trăm video, việc xem lại tốn rất nhiều thời gian|
| 7 | Pain từ người khác | Chăm sóc khách hàng, trả lời hoặc tym bình luận để lấy tương tác kênh | Khách hàng và bản thân | Hàng nghìn bình luận |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Nghiên cứu thị trường #1  |Quy trình rõ ràng, dữ liệu youtube cho phép cào về | Giới hạn của cào youtube API là bao nhiêu |
| 2 |  làm hình ảnh/video #3 | Có thể tạo AI tự động tối ưu prompt và đề xuất phiên bản hình ảnh/ video. | AI nào/ model nào/ phương thức nào|
| 3 |Theo dõi hiệu suất video, phân tích Analytics #6 | Có khả năng lấy dữ liệu từ youtube API |  Giới hạn cào dữ liệu từ youtube API là bao nhiêu |

### Problem Card #1 Nghiên cứu thị trường và đối thủ YouTube

| Trường | Nội dung |
|---|---|
| Job Story |Khi bắt đầu xây dựng một kênh YouTube mới hoặc tìm kiếm ý tưởng video, tôi muốn nhanh chóng nghiên cứu thị trường, phân tích đối thủ và phát hiện xu hướng nội dung đang tăng trưởng, để lựa chọn đúng chủ đề có tiềm năng thu hút người xem. |
| Actor | YouTube Creator, người quản lý nội dung, nhóm sản xuất video.|
| Thời điểm / bối cảnh | Khi mở kênh mới, chuẩn bị kế hoạch nội dung hàng tuần hoặc tìm kiếm ý tưởng cho video tiếp theo.|
| Quy trình hiện tại (3–7 bước) | 1. Xác định chủ đề hoặc thị trường muốn tham gia. 2. Tìm kiếm các kênh đối thủ trên YouTube. 3. Truy cập từng kênh để xem video nổi bật. 4. Thu thập tiêu đề, lượt xem, ngày đăng và chủ đề video. 5. So sánh những video có lượt xem cao hoặc tăng trưởng nhanh. 6. Theo dõi xu hướng từ YouTube, TikTok và các nền tảng khác.7. Tổng hợp và lựa chọn chủ đề để sản xuất.|
| Bottleneck (bước nào, mất bao nhiêu phút) | Phải chuyển đổi giữa nhiều kênh và video, thu thập dữ liệu thủ công, khó xác định video nào thực sự đang tăng trưởng. Ước tính hiện tại: 2–3 ngày/người có kinh nghiệm, khoảng 1 tuần/người mới .|
| Impact (nếu không giải thì sao) |Tốn thời gian trước khi sản xuất; có nguy cơ bỏ lỡ xu hướng; lựa chọn chủ đề dựa trên cảm tính; đầu tư sản xuất video nhưng không có nhu cầu người xem. |
| Success metric (baseline → target) |Baseline: 2–3 ngày khảo sát.Target giả định: dưới 2 giờ cho một báo cáo nghiên cứu có cấu trúc; giảm ít nhất 70% thời gian khảo sát. |
| Phương án không dùng AI |Xây dựng danh sách đối thủ, sử dụng YouTube Search, YouTube Studio, Google Trends và Google Sheets để thu thập, lọc, so sánh dữ liệu.|
| Giả thuyết về AI (nếu có) |AI Agent có thể thu thập dữ liệu công khai, phân loại nội dung, phát hiện video có hiệu suất nổi bật, phân tích xu hướng và tạo báo cáo đề xuất chủ đề tiềm năng. |
| Cảm nhận nhanh | 	Agent + Workflow / Workflow đủ tốt thì không cần AI |

Quy trình nháp hiện tại:

```text

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi sản xuất thumbnail hoặc video bằng các công cụ AI, tôi muốn nhanh chóng tạo và tối ưu prompt để có được hình ảnh/video đúng ý tưởng, chân thực và đồng nhất với phong cách của kênh, để giảm thời gian thử nghiệm và nâng cao chất lượng sản phẩm. |
| Actor | YouTube Creator, người thiết kế thumbnail, người sản xuất video bằng AI. |
| Thời điểm / bối cảnh | Khi tạo thumbnail, xây dựng bối cảnh video, sản xuất video AI hoặc cần duy trì phong cách hình ảnh nhất quán giữa các video. |
| Quy trình hiện tại (3–7 bước) |1. Xác định ý tưởng và phong cách hình ảnh cần tạo. 2. Viết prompt mô tả hình ảnh/video. 3. Nhập prompt vào công cụ AI như GPT, Grok hoặc Google Flow. 4. Chờ AI tạo kết quả. 5. Đánh giá hình ảnh/video về độ chân thực, bố cục, ánh sáng và mức độ phù hợp. 6. Điều chỉnh prompt và tạo lại nhiều phiên bản. 7. Chọn kết quả phù hợp nhất và đưa vào CapCut để biên tập. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Phải liên tục chỉnh sửa prompt và tạo lại kết quả. Một sản phẩm có thể cần 10–30 lần thử nghiệm mới đạt yêu cầu. Khó duy trì tính nhất quán về phong cách giữa các lần tạo. |
| Impact (nếu không giải thì sao) | Tốn thời gian và chi phí sử dụng công cụ AI; tiến độ sản xuất chậm; chất lượng hình ảnh không đồng đều; khó mở rộng quy mô sản xuất nhiều video. |
| Success metric (baseline → target) | Baseline: 10–30 lần thử prompt/sản phẩm.Target giả định: giảm xuống 3–5 lần thử; giảm ít nhất 50% thời gian tạo hình ảnh/video mà vẫn đảm bảo chất lượng đầu ra. |
| Phương án không dùng AI | Xây dựng thư viện prompt mẫu, checklist đánh giá hình ảnh, preset phong cách và quy trình kiểm duyệt thủ công.|
| Giả thuyết về AI (nếu có) |Sử dụng AI để phân tích yêu cầu đầu vào, tự động tạo prompt chi tiết, tối ưu prompt dựa trên kết quả trước đó và đề xuất các phiên bản khác nhau. Có thể kết hợp mô hình ngôn ngữ với API của các nền tảng tạo ảnh/video. |
| Cảm nhận nhanh | Workflow + Agent|

Quy trình nháp hiện tại:

```text

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi quản lý một hoặc nhiều kênh YouTube với số lượng video lớn, tôi muốn tự động theo dõi và tổng hợp hiệu suất của từng video, để nhanh chóng nhận biết video đang tăng trưởng, video có vấn đề và đưa ra quyết định tối ưu nội dung.|
| Actor |YouTube Creator, người quản lý nhiều kênh, nhóm quản lý và phân tích nội dung. |
| Thời điểm / bối cảnh | Sau khi đăng video, trong quá trình theo dõi hiệu suất hàng ngày, hàng tuần hoặc khi cần đánh giá hiệu quả hoạt động của một kênh.|
| Quy trình hiện tại (3–7 bước) | 1. Truy cập YouTube Studio của từng kênh. 2. Kiểm tra danh sách video đã đăng. 3. Xem các chỉ số như Views, CTR, Average View Duration (AVD), Watch Time, Likes và Comments. 4. So sánh hiệu suất giữa các video. 5. Xác định video có lượt xem tăng trưởng bất thường hoặc hiệu suất thấp. 6. Phân tích nguyên nhân và đánh giá vấn đề. 7. Đưa ra phương án điều chỉnh tiêu đề, thumbnail hoặc nội dung video tiếp theo.|
| Bottleneck (bước nào, mất bao nhiêu phút) | 	Phải chuyển đổi giữa nhiều kênh, nhiều video và nhiều trang phân tích. Việc tổng hợp, so sánh và xác định video bất thường mất nhiều thời gian. Chưa có hệ thống cảnh báo và phân tích tập trung. |
| Impact (nếu không giải thì sao) | 	Bỏ lỡ thời điểm video đang tăng trưởng; không phát hiện sớm video có vấn đề; khó xác định chiến lược nội dung hiệu quả; mất thời gian quản lý khi số lượng kênh và video tăng lên.|
| Success metric (baseline → target) | 	Baseline: theo dõi và tổng hợp thủ công, thời gian chưa được đo chính xác. Target giả định: tự động tổng hợp dữ liệu; giảm ít nhất 70% thời gian kiểm tra; phát hiện các video có biến động hiệu suất đáng chú ý trong vòng 15 phút kể từ lần cập nhật dữ liệu thành công.|
| Phương án không dùng AI | 	Sử dụng YouTube Studio, xuất báo cáo CSV, Google Sheets hoặc Looker Studio để tổng hợp và tạo Dashboard theo dõi.|
| Giả thuyết về AI (nếu có) | Kết hợp YouTube Data API và YouTube Analytics API để thu thập dữ liệu; xây dựng Dashboard tập trung; AI phân tích biến động chỉ số, phát hiện bất thường, so sánh video và đưa ra gợi ý cải thiện. |
| Cảm nhận nhanh |  Workflow |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Problem #1: Chưa phân biệt dữ liệu công khai của đối thủ và dữ liệu Analytics riêng tư. | Có | Làm rõ chỉ sử dụng dữ liệu công khai để nghiên cứu đối thủ; không giả định có thể lấy CTR, AVD, Watch Time của đối thủ. |
| Problem #1: Chưa xác định rõ thế nào là video đang có xu hướng tăng trưởng.| Có | Bổ sung hướng so sánh lượt xem, thời điểm đăng và tốc độ tăng trưởng thay vì chỉ dựa vào tổng lượt xem. |
| Problem #1: Mục tiêu giảm từ 2–3 ngày xuống dưới 2 giờ chưa có kiểm chứng.| Có | Ghi nhận đây là Target giả định, cần đo lường qua phỏng vấn và thử nghiệm thực tế. |
|Problem #2: Chưa xác định AI/model nào có thể tối ưu prompt và tạo hình ảnh/video. | Có | Chưa cố định model; định hướng kết hợp LLM để tối ưu prompt với các công cụ tạo ảnh/video chuyên dụng. |
|Problem #2: Chưa có tiêu chí khách quan để đánh giá hình ảnh/video đạt yêu cầu. | Có |Bổ sung các tiêu chí đánh giá: độ chân thực, bố cục, ánh sáng, tính nhất quán và mức độ phù hợp với ý tưởng.  |
| Problem #2: Chưa làm rõ khả năng tích hợp trực tiếp với Google Flow, Grok và các nền tảng khác.| Có | 	Đưa khả năng tích hợp API, chi phí và giới hạn của từng nền tảng vào danh sách cần kiểm chứng. |
| Problem #3: Chưa phân biệt YouTube Data API và YouTube Analytics API.| Có | Làm rõ Data API phục vụ dữ liệu công khai; Analytics API phục vụ dữ liệu chuyên sâu của kênh được cấp quyền. |
|Problem #3: Chưa xác định giới hạn quota và tần suất cập nhật dữ liệu. | Có | 	Bổ sung quota, quyền OAuth và tần suất đồng bộ vào các yếu tố cần nghiên cứu kỹ thuật. |
| Problem #3: Chưa xác định giới hạn quota và tần suất cập nhật dữ liệu.| Có |  Bổ sung quota, quyền OAuth và tần suất đồng bộ vào các yếu tố cần nghiên cứu kỹ thuật.|
| Problem #3: Success Metric chưa có số liệu baseline thực tế.| Có |Chuyển các mục tiêu giảm 70% thời gian và phát hiện trong 15 phút thành giả thuyết cần đo lường, chưa xem là kết quả đã đạt được.  |
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Tham gia trao đổi và trình bày các vấn đề nhóm đang xem xét. |Giúp nhóm làm rõ các vấn đề tiềm năng trước khi lựa chọn hướng nghiên cứu. |
| Phản biện bài của bạn khác | ham gia đặt câu hỏi và phản biện để làm rõ vấn đề, tính khả thi và bằng chứng thực tế. Câu hỏi cụ thể hiện không còn nhớ chính xác. |Giúp tôi nhận ra cần đánh giá vấn đề dựa trên nhu cầu thực tế, không chỉ dựa vào ý tưởng giải pháp. |
| Nhận phản biện | Tiếp nhận các ý kiến phản biện về cách xác định Opportunity, quy trình và phạm vi vấn đề. | Tôi cùng nhóm điều chỉnh cách phân loại, loại bỏ những ý tưởng giải pháp đội lốt Opportunity.|
| Gom cluster / cây OST |Tham gia phân tích và phân loại các vấn đề thành 5 nhóm A–E, đồng thời xem xét mối liên hệ giữa các Opportunity. |Tham gia phân tích và phân loại các vấn đề thành 5 nhóm A–E, đồng thời xem xét mối liên hệ giữa các Opportunity. |
| Chọn candidate problem | Tham gia chấm điểm, so sánh và thảo luận các Candidate A–E.| Nhóm chọn Candidate B – Khó xác định thứ tự ưu tiên task, đạt 33/35 điểm, đồng hạng với E.|
| Kiểm chứng / research |Tham gia phỏng vấn và tìm hiểu trải nghiệm thực tế của người dùng về việc quản lý nhiều nhiệm vụ. |Có bằng chứng ban đầu cho Candidate A: người dùng từng quên task 1–6 giờ, khoảng 2–3 lần/tháng. Các Candidate B–E vẫn cần kiểm chứng thêm. |
| Quy trình nhóm | Tham gia phân tích quy trình người dùng khi tiếp nhận nhiều nhiệm vụ, xem xét cách lựa chọn công việc cần thực hiện trước.|Giúp nhóm thu hẹp phạm vi nghiên cứu vào quyết định lựa chọn task tiếp theo. |
| Problem Statement |Tham gia phân tích vấn đề cốt lõi, làm rõ khó khăn của người dùng khi có nhiều task cùng lúc và chưa xác định được thứ tự ưu tiên. |Giúp Problem tập trung vào khó khăn ra quyết định thay vì mở rộng thành bài toán quản lý toàn bộ công việc. |
| Mức can thiệp AI | Tham gia xem xét hướng Workflow và khả năng kết hợp AI với các quy tắc ưu tiên công việc.|Giúp nhóm có cơ sở so sánh giữa phương án thông thường và phương án có AI hỗ trợ, tránh mặc định phải sử dụng Agent. |
| Quyết định |	Tham gia thảo luận, phản biện và thống nhất lựa chọn Candidate B. |Nhóm thống nhất 100% thành viên chọn B làm vấn đề trọng tâm để tiếp tục nghiên cứu. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Hỗ trợ tìm kiếm và phân loại các vấn đề tiềm năng.|Gợi ý nhiều góc nhìn, giúp hệ thống hóa các vấn đề thành nhóm. | Một số vấn đề còn chung chung, chưa có bằng chứng thực tế.| Tôi xem xét lại các vấn đề dựa trên trải nghiệm và nhu cầu thực tế của người dùng.|
| CP2 Problem Card | Tham khảo cách xây dựng Job Story, Actor, Bottleneck và Impact.Tham khảo cách xây dựng Job Story, Actor, Bottleneck và Impact.| Giúp cấu trúc hóa nội dung và trình bày Problem rõ ràng hơn.| Có xu hướng đưa ra giải pháp AI quá sớm, một số Metric chỉ là giả định.| Tôi điều chỉnh để tập trung mô tả vấn đề, quy trình hiện tại và phân biệt giả thuyết với bằng chứng.|
| CP4 Research |Tham khảo cách tìm kiếm, phân loại và đánh giá bằng chứng cho các vấn đề. | Giúp định hướng các thông tin cần thu thập và những câu hỏi cần kiểm chứng.|AI không thể thay thế hoàn toàn việc phỏng vấn và xác minh trải nghiệm thực tế. |Tôi kết hợp với việc phỏng vấn người dùng và đánh giá mức độ đáng tin cậy của thông tin. |
| CP5 Quy trình |Hỗ trợ phân tích các bước trong quy trình quản lý và lựa chọn công việc. |Giúp chia nhỏ quy trình, xác định các bước có thể gây khó khăn cho người dùng và đề xuất hướng Workflow. |Một số quy trình AI đề xuất mang tính lý tưởng, chưa phản ánh đầy đủ cách người dùng thực hiện thực tế. |Tôi xem xét lại theo bối cảnh người dùng có nhiều task, deadline và mức độ ưu tiên khác nhau. |
| CP5–6 Problem Statement |Tham khảo cách diễn đạt và hoàn thiện Problem Statement. |Giúp câu chữ rõ ràng, có cấu trúc và tập trung vào vấn đề cốt lõi. |Có thể diễn đạt vấn đề theo hướng giải pháp hoặc đưa ra nhận định khi chưa đủ bằng chứng. | Có thể diễn đạt vấn đề theo hướng giải pháp hoặc đưa ra nhận định khi chưa đủ bằng chứng.|
| CP6 Mức can thiệp / quyết định |Tham khảo cách so sánh No AI, Rule, Workflow và Agent. |Giúp hiểu các mức độ can thiệp công nghệ và khả năng ứng dụng Workflow. |AI có thể thiên về đề xuất Agent mà chưa đánh giá đầy đủ chi phí và mức độ cần thiết. | Tôi ưu tiên xem xét Workflow và các quy tắc ưu tiên đơn giản trước khi quyết định có cần AI Agent hay không.|

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
 
Khi nghe các nhóm khác trình bày, tôi nhận ra rằng một vấn đề có giá trị không nhất thiết phải là vấn đề lớn nhất, mà phải là vấn đề xảy ra thường xuyên, gây ảnh hưởng rõ ràng và có bằng chứng thực tế. Tôi học được cách nhìn nhận vấn đề từ nhiều góc độ khác nhau, đặc biệt là người trực tiếp gặp vấn đề và những người chịu ảnh hưởng.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có. Khi xây dựng ba Problem Card, nhóm tôi đã sớm nghĩ đến việc sử dụng AI Agent để nghiên cứu đối thủ, AI tối ưu prompt và Dashboard tự động phân tích YouTube Analytics. Tuy nhiên, đây mới là những giải pháp dự kiến, trong khi nhóm chưa xác minh đầy đủ mức độ nghiêm trọng của vấn đề và nhu cầu thực tế của người dùng. Nhóm nhận ra điều này khi tiến hành phản biện các Problem Card. Sau đó, chúng tôi quay lại làm rõ Job Story, quy trình hiện tại, Bottleneck, Impact và Success Metric.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Không, Khi được phản biện tôi giải thích vấn đề rõ hơn để mọi người hiểu. Ví dụ khi tôi bảo xây dựng quản lý kênh youtube, làm sao để mở rộng số lượng kênh có thể quản lý, thì các bạn chỉ tập trung vào quản lý chứ chưa hiểu hết làm thế nào để edit, làm thế nào để quản lý nhạc, làm nội dung, content mà mỗi kênh có 1 phong cách riêng.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Một số công việc tưởng chừng đơn giản như nghiên cứu đối thủ, tạo prompt hình ảnh và kiểm tra hiệu suất video thực tế lại có thể tiêu tốn rất nhiều thời gian khi phải thực hiện thường xuyên và quản lý nhiều kênh. Tôi nhận ra rằng vấn đề không chỉ nằm ở thao tác riêng lẻ mà còn nằm ở việc phải chuyển đổi giữa nhiều công cụ và tổng hợp dữ liệu thủ công. Tuy nhiên, các con số về thời gian hiện tại mới là quan sát và ước tính ban đầu, chưa phải kết quả khảo sát đại diện. Vì vậy, tôi cho rằng cần tiếp tục phỏng vấn Creator để xác minh mức độ phổ biến và mức độ nghiêm trọng của những vấn đề này.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất đối với tôi là xác định đúng vấn đề cốt lõi mà người dùng thực sự gặp phải, thay vì mô tả một công việc hoặc đưa ra giải pháp ngay từ đầu. Ví dụ, việc tạo hình ảnh bằng AI không đơn thuần là cần một công cụ tạo ảnh tốt hơn, mà vấn đề nằm ở quá trình thử nghiệm prompt nhiều lần, khó kiểm soát chất lượng và thiếu tính nhất quán. Bên cạnh đó, việc xây dựng Success Metric cũng khó khăn vì cần có số liệu Baseline thực tế để xác định mục tiêu cải thiện hợp lý. Tôi cũng phải cân nhắc ranh giới giữa những gì AI có thể làm và những gì vẫn cần con người kiểm soát.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu được làm lại, tôi sẽ dành nhiều thời gian hơn để phỏng vấn người dùng trước khi lựa chọn ba vấn đề ưu tiên. Tôi sẽ yêu cầu mỗi Problem phải có bằng chứng cụ thể về tần suất xảy ra, thời gian xử lý và hậu quả nếu không giải quyết.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán của nhóm tôi là hỗ trợ người dùng gặp khó khăn khi phải xác định thứ tự ưu tiên giữa nhiều nhiệm vụ cùng lúc. Để hiểu vấn đề, nhóm phân tích quy trình người dùng tiếp nhận task, xem xét deadline, mức độ quan trọng và khẩn cấp trước khi quyết định nên làm công việc nào. Tiếp theo, nhóm cần xây dựng Metric như thời gian đưa ra quyết định, tỷ lệ hoàn thành task đúng hạn và tỷ lệ bỏ sót nhiệm vụ để đánh giá hiệu quả. Về Boundary, nhóm giới hạn bài toán ở việc đề xuất thứ tự ưu tiên, không mở rộng sang tự động thực hiện toàn bộ công việc hoặc quản lý mọi khía cạnh năng suất cá nhân. Về mức độ can thiệp AI, nhóm có thể bắt đầu bằng Rule-based dựa trên deadline và mức độ quan trọng, sau đó cân nhắc Workflow hoặc AI Agent nếu cần xử lý nhiều thông tin và ngữ cảnh phức tạp. Cuối cùng, nhóm lựa chọn Candidate B vì đạt 33/35 điểm, có phạm vi tương đối rõ ràng và phù hợp với khả năng triển khai trong bài lab.

---

## 7. Tài liệu tham khảo

-
