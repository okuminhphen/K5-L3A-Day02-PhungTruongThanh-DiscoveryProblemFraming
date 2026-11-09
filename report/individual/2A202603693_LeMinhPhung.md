# Báo cáo cá nhân — 2A202603693_LeMinhPhung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Lê Minh Phụng
- MSSV:2A202603693
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:PhungTruongThanh
- Link repo nhóm: https://github.com/okuminhphen/K5-L3A-Day02-PhungTruongThanh-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                                                                                   | Ai chịu ảnh hưởng?                 | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                                                                                                                                             |
| --: | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Lặp lại                           | Khi nhân viên hỏi cách xử lý một lỗi thường gặp (kết nối máy in, reset mật khẩu, cài VPN nội bộ), tôi muốn tìm nhanh hướng dẫn phù hợp, để hỗ trợ họ mà không phải soạn lại từ đầu.             | Nhân viên IT, người yêu cầu hỗ trợ | Gặp 12–15 lần/tuần (chiếm ~40% tổng số ticket hỗ trợ); mất 15–20 phút/lần tìm lại file hướng dẫn cũ hoặc gõ lại từng bước qua tin nhắn.                                                                               |
|   2 | Tốn thời gian                     | Khi nhận thông báo “máy bị lỗi” hoặc “mạng lag” chung chung, tôi muốn có đủ thông tin về triệu chứng và mã lỗi ngay từ đầu, để xác định cách xử lý nhanh hơn mà không phải hỏi đi hỏi lại.      | Nhân viên IT, người báo lỗi        | Phải nhắn tin hỏi lại 2–3 lượt/yêu cầu để lấy ảnh màn hình và mô tả chi tiết; mất khoảng 20–25 phút làm rõ trước khi bắt tay vào xử lý; xảy ra với ~70% yêu cầu gửi đến.                                              |
|   3 | Tốn thời gian                     | Khi bàn giao máy tính cho nhân viên mới, tôi muốn kiểm tra đủ các bước chuẩn bị (cài đặt phần mềm tiêu chuẩn, cấp quyền thư mục, kích hoạt tài khoản), để họ có thể bắt đầu làm việc đúng ngày. | Nhân viên IT, nhân viên mới, HR    | Chuẩn bị 8–10 máy/tháng; từng thiếu bước cấp quyền VPN và tài khoản kho mã nguồn nội bộ cho 2 nhân viên mới trong tháng trước, khiến họ mất nửa ngày đầu ngồi chờ.                                                    |
|   4 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận yêu cầu hỗ trợ qua nhiều kênh rời rạc, tôi muốn biết những việc nào còn chưa xử lý và mức độ ưu tiên của chúng, để không bỏ sót yêu cầu quan trọng.                                    | Nhân viên IT, người yêu cầu hỗ trợ | Yêu cầu đến qua 4 kênh (tin nhắn Zalo, kênh Slack nội bộ, email và gặp trực tiếp tại bàn); mất 35–45 phút/ngày cuối giờ để gom vào bảng Excel theo dõi; tuần trước từng bỏ sót 2 yêu cầu qua email trong suốt 2 ngày. |
|   5 | Pain từ người khác                | Khi đã báo lỗi nhưng chưa được xử lý xong, nhân viên muốn biết tiến độ và thời gian dự kiến hoàn thành, để sắp xếp công việc của họ mà không phải thấp thỏm chờ đợi.                            | Người yêu cầu hỗ trợ, nhân viên IT | Có 15–20 lượt nhắn tin/gọi điện hỏi lại tiến độ mỗi tuần ("ticket của mình xử lý đến đâu rồi?", "khi nào dùng được máy?"); ghi nhận qua lịch sử chat trực tiếp trên Slack/Teams gây ngắt quãng công việc cả hai bên.  |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý giữ lại:** Giữ lại ý #4 (Cần đọc, tổng hợp nhiều kênh) và ý #5 (Pain từ người khác về tiến độ chờ đợi) vì đây là các vấn đề thường xuyên diễn ra ở các đội IT Helpdesk nội bộ khi chưa có quy trình ticketing tập trung.
- **Ý bỏ:** Bỏ ý "Xây dựng chatbot IT toàn năng tự động sửa mọi lỗi phần cứng và phần mềm cho công ty" do AI gợi ý ban đầu. Lý do bỏ: Đây là giải pháp công nghệ (solution trá hình), vi phạm nguyên tắc tập trung vào bài toán (problem framing); ngoài ra phạm vi quá rộng và phi thực tế vì nhiều sự cố vật lý bắt buộc IT phải thao tác trực tiếp.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                                         | Vì sao chọn                                                                                      | Điều còn chưa chắc                                                                   |
| ---: | --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
|    1 | Yêu cầu báo lỗi thiếu thông tin, IT phải hỏi lại nhiều lần (#2) | Tình huống cụ thể; đo được số lượt hỏi lại và thời gian thu thập thông tin (chiếm ~70% yêu cầu)  | Một biểu mẫu báo lỗi có đủ giải quyết không hay người dùng vẫn lười điền?            |
|    2 | Yêu cầu hỗ trợ nằm rải rác, khó biết việc nào chưa xử lý (#4)   | Có thể kiểm tra bằng lịch sử tin nhắn và danh sách công việc; từng có hậu quả thật (sót 2 email) | Có thật sự bỏ sót thường xuyên hay chỉ mất thời gian tổng hợp cuối ngày?             |
|    3 | Mất thời gian tìm và soạn lại hướng dẫn cho lỗi thường gặp (#1) | Công việc lặp lại nhiều lần (12–15 lần/tuần); có thể tận dụng tài liệu sẵn có                    | Tần suất có đủ cao? Tài liệu hiện tại có dễ tìm và còn đúng với phiên bản mới không? |

### Problem Card #1 — Báo lỗi thiếu thông tin

| Trường                                    | Nội dung                                                                                                                                                                                            |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi nhận thông báo “máy bị lỗi”, tôi muốn có đủ thông tin về triệu chứng ngay từ đầu, để xác định cách xử lý nhanh hơn.                                                                             |
| Actor                                     | Nhân viên IT tiếp nhận yêu cầu hỗ trợ nội bộ.                                                                                                                                                       |
| Thời điểm / bối cảnh                      | Nhân viên văn phòng gửi tin nhắn báo lỗi máy tính hoặc phần mềm trong giờ làm việc.                                                                                                                 |
| Quy trình hiện tại (3–7 bước)             | 1. Nhận tin báo lỗi (1') · 2. Hỏi thiết bị/phần mềm gặp lỗi (2') · 3. Lấy mô tả chi tiết và ảnh chụp lỗi (12') · 4. Hỏi các bước đã tự thử xử lý (5') · 5. Xác định hướng xử lý (5')                |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — Trao đổi qua lại để lấy đủ thông tin, đặc biệt khi người báo lỗi trả lời chậm hoặc mô tả mơ hồ: mất 12–15 phút/yêu cầu.                                                                    |
| Impact (nếu không giải thì sao)           | IT chậm bắt đầu xử lý; người báo lỗi phải chờ và bị gián đoạn công việc. Mức độ thực tế: xảy ra với ~70% yêu cầu báo lỗi (10–15 ticket/tuần), kéo dài thời gian xử lý sự cố thêm 20–25 phút mỗi ca. |
| Success metric (baseline → target)        | Số lượt hỏi bổ sung trung bình giảm từ 2.5 lượt xuống dưới 1 lượt/yêu cầu; thời gian thu thập đủ thông tin giảm từ 25 phút xuống dưới 5 phút; đếm trên các yêu cầu cùng loại.                       |
| Phương án không dùng AI                   | Dùng mẫu biểu mẫu (Google Form / Jira Service Management template) bắt buộc nhập: tên thiết bị, phần mềm, mô tả triệu chứng, ảnh chụp lỗi và các bước đã thử trước khi gửi.                         |
| Giả thuyết về AI (nếu có)                 | AI hỗ trợ nhận diện các trường thông tin còn thiếu trong tin nhắn mô tả tự do và tự động gợi ý câu hỏi bổ sung ngay lập tức cho người dùng.                                                         |
| Cảm nhận nhanh                            | Rule — thử biểu mẫu và kiểm tra trường bắt buộc trước.                                                                                                                                              |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 25 phút/lần tiếp nhận

[1. Nhận báo lỗi: 1']
→ [2. Hỏi thiết bị/phần mềm: 2']
→ [3. Lấy mô tả và ảnh lỗi: 12'] ← BOTTLENECK (chờ phản hồi & hỏi lại)
→ [4. Hỏi cách đã thử: 5']
→ [5. Xác định hướng xử lý: 5']
```

### Problem Card #2 — Yêu cầu hỗ trợ nằm rải rác

| Trường                                    | Nội dung                                                                                                                                                                                                                |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi nhận yêu cầu hỗ trợ qua nhiều kênh, tôi muốn biết những việc nào còn chưa xử lý, để không bỏ sót yêu cầu.                                                                                                           |
| Actor                                     | Nhân viên IT phụ trách theo dõi và phân phối yêu cầu hỗ trợ nội bộ.                                                                                                                                                     |
| Thời điểm / bối cảnh                      | Trong ngày làm việc khi nhận yêu cầu qua chat (Slack, Zalo), email hoặc trao đổi trực tiếp tại bàn.                                                                                                                     |
| Quy trình hiện tại (3–7 bước)             | 1. Kiểm tra từng kênh liên lạc (10') · 2. Ghi chép lại yêu cầu vào bảng (10') · 3. Đối chiếu trạng thái việc đã làm (15') · 4. Lập danh sách công việc còn tồn đọng (5') · 5. Sắp xếp thứ tự ưu tiên xử lý (5')         |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — Tìm kiếm và đối chiếu trạng thái yêu cầu giữa các kênh rời rạc: mất 15–20 phút cuối ngày vì phải rà soát tin nhắn xem việc nào đã xong, việc nào chưa ai nhận.                                                 |
| Impact (nếu không giải thì sao)           | Mất thời gian rà soát; có nguy cơ bỏ sót hoặc xử lý trùng. Trường hợp thật: Tuần trước bỏ sót 2 yêu cầu qua email trong suốt 2 ngày khiến phòng kinh doanh phàn nàn; 1 lỗi máy in bị 2 bạn IT cùng tới xử lý trùng lặp. |
| Success metric (baseline → target)        | Thời gian tổng hợp danh sách việc tồn mỗi ngày giảm từ 45 phút xuống dưới 10 phút; số yêu cầu bị bỏ sót hoặc xử lý trùng giảm từ 2–3 vụ/tháng về 0.                                                                     |
| Phương án không dùng AI                   | Thống nhất một kênh tiếp nhận chính thức duy nhất (kênh Slack `#it-helpdesk`) và duy trì một bảng Trello/Jira theo dõi có người phụ trách, trạng thái rõ ràng.                                                          |
| Giả thuyết về AI (nếu có)                 | Nếu vẫn phải nhận qua nhiều kênh, AI hỗ trợ trích xuất nội dung yêu cầu từ email/chat và đề xuất phân loại tự động vào bảng task để IT kiểm tra.                                                                        |
| Cảm nhận nhanh                            | No AI — thử thống nhất quy trình tiếp nhận trước.                                                                                                                                                                       |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 45 phút/ngày

[1. Kiểm tra các kênh: 10']
→ [2. Ghi yêu cầu: 10']
→ [3. Đối chiếu trạng thái: 15'] ← BOTTLENECK (rà soát tin nhắn trôi)
→ [4. Lập danh sách tồn: 5']
→ [5. Sắp xếp xử lý: 5']
```

### Problem Card #3 — Tìm và soạn lại hướng dẫn lỗi thường gặp

| Trường                                    | Nội dung                                                                                                                                                                                                              |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi nhân viên hỏi cách xử lý một lỗi thường gặp, tôi muốn tìm nhanh hướng dẫn phù hợp, để hỗ trợ họ mà không phải soạn lại từ đầu.                                                                                    |
| Actor                                     | Nhân viên IT trả lời yêu cầu hỗ trợ kỹ thuật nội bộ.                                                                                                                                                                  |
| Thời điểm / bối cảnh                      | Nhận câu hỏi về các lỗi đã từng xử lý nhiều lần, như kết nối máy in, reset mật khẩu, hoặc kết nối Wi-Fi/VPN.                                                                                                          |
| Quy trình hiện tại (3–7 bước)             | 1. Đọc yêu cầu (2') · 2. Xác định loại lỗi (2') · 3. Tìm hướng dẫn cũ trong kho tài liệu/chat (8') · 4. Kiểm tra và chỉnh sửa nội dung (5') · 5. Gửi hướng dẫn qua tin nhắn (1') · 6. Xác nhận kết quả thực hiện (2') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — Tìm hướng dẫn trong tài liệu hoặc tin nhắn cũ: mất 8–10 phút/lần vì tài liệu nằm rải rác trên Google Drive, tin nhắn ghim Slack hoặc máy tính cá nhân.                                                       |
| Impact (nếu không giải thì sao)           | IT lặp lại việc tìm và viết; người dùng chờ lâu hơn. Tần suất thực tế: Gặp 12–15 lần/tuần (chiếm ~40% ticket hỗ trợ); làm mất khoảng 3–4 tiếng/tuần của nhân viên IT.                                                 |
| Success metric (baseline → target)        | Thời gian từ lúc đọc yêu cầu đến khi gửi hướng dẫn phù hợp giảm từ 20 phút xuống dưới 5 phút; kiểm tra tỷ lệ hướng dẫn giúp người dùng tự xử lý thành công đạt >80%.                                                  |
| Phương án không dùng AI                   | Tạo thư mục hướng dẫn theo loại lỗi trên Notion Wiki, đặt tên file rõ ràng theo từ khóa và lưu sẵn các mẫu trả lời (canned responses) trên Slack/Teams.                                                               |
| Giả thuyết về AI (nếu có)                 | AI tìm kiếm hướng dẫn phù hợp với cách người dùng mô tả lỗi bằng ngôn ngữ tự nhiên, trích xuất chính xác đoạn cần thiết từ tài liệu nội bộ đã duyệt.                                                                  |
| Cảm nhanh nhanh                           | Chưa biết — cần thử khả năng tìm kiếm thông thường (keyword search/wiki) trước.                                                                                                                                       |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 20 phút/lần hỗ trợ

[1. Đọc yêu cầu: 2']
→ [2. Xác định loại lỗi: 2']
→ [3. Tìm hướng dẫn cũ: 8'] ← BOTTLENECK (tài liệu nằm rải rác)
→ [4. Kiểm tra và chỉnh: 5']
→ [5. Gửi: 1']
→ [6. Xác nhận kết quả: 2']
```

### Card muốn pitch nhất

- Card số: 1 (Báo lỗi thiếu thông tin)
- Vì sao: Đây là nguyên nhân gốc rễ (root cause) làm chậm toàn bộ quy trình xử lý của IT; chiếm tới 70% số yêu cầu tiếp nhận; giải quyết được bài toán này sẽ cắt giảm trực tiếp 15–20 phút gián đoạn công việc cho cả IT và nhân viên báo lỗi; dễ thử nghiệm giải pháp biểu mẫu (Rule) trước khi tính đến AI.
- Câu hỏi muốn nhóm phản biện: "Nếu áp dụng biểu mẫu bắt buộc nhập nhiều trường (thiết bị, ảnh lỗi, mô tả chi tiết), liệu nhân viên có cảm thấy phiền hà và bỏ qua biểu mẫu để tiếp tục nhắn tin trực tiếp không?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                                                      | Đồng ý? | Đã sửa gì                                                                                                                                                               |
| ----------------------------------------------------------------------------------------------------------------------- | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Có nhảy sang dùng AI nhận diện mô tả quá sớm không khi chỉ cần form bắt buộc?                                           | Đồng ý  | Đặt cảm nhận nhanh là Rule: ưu tiên thử nghiệm giải pháp không dùng AI (form có trường bắt buộc) trước; AI chỉ là phương án dự phòng khi người dùng vẫn gõ mô tả tự do. |
| Thời gian bottleneck 12 phút có phản ánh thời gian IT làm việc thật không hay là thời gian chết chờ người dùng trả lời? | Đồng ý  | Đã phân tách rõ: thời gian IT gõ hỏi chỉ mất 2-3 phút, còn 10-12 phút là thời gian chờ ngắt quãng khiến IT không thể tập trung làm việc khác.                           |
| Success metric giảm từ 2.5 lượt hỏi xuống dưới 1 lượt có đo được không?                                                 | Đồng ý  | Xác định đo bằng cách đếm số tin nhắn trao đổi trong thread ticket trên Slack/Helpdesk trước khi bắt đầu sửa.                                                           |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?                                                                                                                                                                                                                                                                                                                               | Kết quả / ảnh hưởng tới bài nhóm                                                                                                                     |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Pitch Problem Card         | Trình bày 3 candidate IT nội bộ, chọn pitch Candidate A1 (Báo lỗi thiếu thông tin)                                                                                                                                                                                                                                                           | Nhóm đưa A1 vào shortlist chấm điểm CP3                                                                                                              |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: <br>- Cho B1 (Trường): _"Discord đã có tính năng ghim tin nhắn và kênh #announcement, tại sao vẫn bị trôi?"_ <br>- Cho B3 (Trường): _"Nếu dùng Google Docs hoặc chia file Markdown riêng thì có còn conflict không?"_ <br>- Cho C2 (Thanh): _"Lớp đã có mã QR quét điểm danh chưa, rào cản là công nghệ hay thói quen?"_ | Giúp Trường và Thanh làm rõ bottleneck thật sự và tính khả thi của bài toán                                                                          |
| Nhận phản biện             | Câu hỏi tôi nhận được: _"Nếu bắt điền biểu mẫu nhiều trường thì người dùng có lười rồi vẫn nhắn tin tự do không?"_ (Trường hỏi)                                                                                                                                                                                                              | Tôi đã sửa gì: Đặt cảm nhận nhanh là Rule (thử biểu mẫu bắt buộc trước), bổ sung giả thuyết AI chỉ hỗ trợ gợi ý trường thiếu khi người dùng gõ tự do |
| Gom cluster / cây OST      | Điều phối và cùng nhóm gom 9 candidate thành 5 cluster (A đến E), dựng cây OST                                                                                                                                                                                                                                                               | Thống nhất nhóm bài toán "Tìm và chọn thông tin cần thiết" (Cluster A)                                                                               |
| Chọn candidate problem     | Chấm điểm shortlist 3 candidate (B1, C1, A1) trên 7 tiêu chí                                                                                                                                                                                                                                                                                 | Nhất trí chọn B1 (31/35) vì phạm vi hẹp, dễ tiếp cận học viên để kiểm chứng tại lab                                                                  |
| Kiểm chứng / research      | Phụ trách research giải pháp có sẵn: tra cứu tài liệu chính thức của Discord về Search, Pin và Announcement Channels (CP4)                                                                                                                                                                                                                   | Đưa ra bảng so sánh công cụ, nhận diện khoảng trống và kết luận chưa cần vội dùng AI ở mục 3.3 group_report.md                                       |
| Quy trình nhóm             | Cùng Thanh và Trường xây dựng quy trình trước/sau; làm rõ bottleneck bước đọc lướt tin nhắn và quy định boundary đính kèm link gốc (CP5)                                                                                                                                                                                                     | Hoàn thiện sơ đồ 5 bước hiện tại và 4 bước tương lai có gắn nhãn Rule, AI, HITL                                                                      |
| Problem Statement          | Phản biện bản v0 và đóng góp xây dựng bản v1 (CP5–CP6)                                                                                                                                                                                                                                                                                       | Bổ sung thêm metric chất lượng trích xuất (độ chính xác ≥95%) vào v1 thay vì chỉ đo tốc độ                                                           |
| Mức can thiệp AI           | Hỗ trợ Trường so sánh 4 mức can thiệp; trả lời 2 câu hỏi Google PAIR (CP6)                                                                                                                                                                                                                                                                   | Thống nhất chọn Workflow có kiểm duyệt, kiên quyết loại bỏ mức Agent                                                                                 |
| Quyết định                 | Cùng nhóm đánh giá 4 rủi ro, bảo vệ quan điểm chọn kết luận "Not Yet" và thiết lập 2 ngưỡng dừng (CP6)                                                                                                                                                                                                                                       | Nhóm thống nhất không vội vàng làm AI khi chưa có phỏng vấn ngoài nhóm và chưa thử No AI                                                             |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                                       | AI hữu ích ở đâu?                                                    | AI sai hoặc hời hợt ở đâu?                                           | Tôi sửa gì bằng nhận định của mình?                                                                    |
| ------------------------------ | ------------------------------------------------------------ | -------------------------------------------------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| CP1 Scan                       | Gợi ý thêm các vấn đề xoay quanh công việc IT                | Mở rộng góc nhìn về các thao tác lặp lại                             | Gợi ý làm "AI chatbot toàn năng" (solution trá hình)                 | Loại bỏ giải pháp trá hình, giữ lại problem thật về tổng hợp ticket và tài liệu                        |
| CP2 Problem Card               | Đóng vai "PM hoài nghi" phản biện card #1                    | Chỉ ra ranh giới giữa thời gian làm thật và thời gian chờ ngắt quãng | Thúc ép nhảy sang giải pháp AI quá sớm                               | Đổi cảm nhận nhanh thành "Rule" (thử form bắt buộc trước)                                              |
| CP4 Research                   | Hỗ trợ cấu trúc bảng research và đối chiếu tính năng Discord | Tổng hợp nhanh các tính năng sẵn có                                  | Chưa nêu điều kiện cần bật Community Server cho Announcement         | Tự tra cứu lại tài liệu chính thức của Discord để bổ sung rủi ro/điều kiện thực tế                     |
| CP5 Quy trình                  | Chuyển đổi mô tả các bước sang sơ đồ ASCII                   | Định dạng các khối quy trình trực quan, nhanh gọn                    | AI tự ý gộp bước đọc tin và bước lưu lịch làm một, làm mờ bottleneck | Tách riêng bước đọc lướt lọc tin để làm rõ điểm nghẽn chính                                            |
| CP5–6 Problem Statement        | Phản biện các trường nội dung trong Problem Statement v0     | Nhắc nhở thiếu metric chất lượng (chỉ đo thời gian)                  | Gợi ý giao toàn quyền cho bot tự động ghi vào lịch                   | Giữ vững boundary con người kiểm duyệt (HITL) và thêm tiêu chí trích xuất chính xác ≥95%               |
| CP6 Mức can thiệp / quyết định | So sánh các phương án trên ma trận Ambiguity × Complexity    | Cung cấp góc nhìn phân định giữa Workflow và Agent                   | Nghiêng về việc chọn "Go" làm AI ngay để hoàn thành đồ án            | Tự đưa ra quyết định "Not Yet" vì tôn trọng dữ liệu CP4 chưa phỏng vấn ngoài nhóm và kết luận research |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Nhóm chọn bài toán tìm thông báo quan trọng trên Discord vì có thể tiếp cận học viên để kiểm chứng ngay trong buổi lab. So với bài toán chọn nội dung ôn thi từ PDF, bài toán này có phạm vi hẹp và dễ quan sát hơn. Việc so sánh cho thấy một vấn đề đáng làm còn cần phù hợp với khả năng kiểm chứng của nhóm.
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Nhóm đã cân nhắc giải pháp bot Discord khi chưa có đủ dữ liệu từ người dùng. Research sau đó cho thấy Discord đã có Search, ghim tin và kênh thông báo. Nhóm cần quay lại xác định khó khăn thực tế và kiểm tra hiệu quả của các tính năng sẵn có trước khi quyết định dùng AI.
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Câu hỏi của Trường về việc người dùng có ngại điền biểu mẫu bắt buộc đã làm rõ hạn chế của phương án tiếp nhận lỗi IT. Báo cáo sau đó ưu tiên thử biểu mẫu và quy tắc kiểm tra thông tin trước, thay vì mặc định cần AI. Đây là tình huống có thể dùng để giải thích sự thay đổi quan điểm sau phản biện.
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Hai cuộc phỏng vấn ngoài nhóm ghi nhận những lần tìm thông báo mất vài phút, nhưng cũng có trường hợp tìm rất nhanh khi nhớ đúng từ khóa hoặc biết đúng kênh. Kết quả này chưa xác nhận giả định mười lăm phút mỗi ngày. Nó cho thấy khó khăn còn liên quan đến việc nhận biết bản cập nhật và đọc đủ yêu cầu.
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó khăn khi viết Problem Statement nằm ở việc phân biệt số liệu ước lượng với baseline đã đo. Nhóm có thể đặt mục tiêu giảm thời gian tìm kiếm, nhưng cần ghi rõ cách đo và đối tượng thử nghiệm. Boundary cũng phải xác định việc AI được hỗ trợ và việc học viên phải tự kiểm tra.
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, việc nên ưu tiên là phỏng vấn và đo thời gian thực tế trước khi xây dựng phương án công nghệ. Nhóm cũng cần thử cách tổ chức thông báo đơn giản hơn. Một câu hỏi phản biện cần đặt sớm là liệu hướng dẫn dùng Search và cập nhật tin ghim có đủ giải quyết khó khăn hay chưa.
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.
Bài toán nhóm chọn là giúp học viên tìm và nhận biết đúng thông báo hạn nộp hoặc đổi lịch trên Discord. Quy trình hiện tại gồm tìm tin, kiểm tra thời điểm và phạm vi áp dụng, rồi tự lưu lịch hoặc ghi chú. Metric dự kiến là giảm thời gian tìm thông báo xuống dưới ba phút mỗi ngày, nhưng baseline mười lăm phút vẫn cần được đo lại. Boundary yêu cầu AI không tự sửa lịch cá nhân và người học phải kiểm tra thông báo gốc trước khi hành động. Nếu cần công nghệ, nhóm cân nhắc Workflow gồm lọc tin theo quy tắc, AI trích xuất thông tin và con người kiểm tra. Quyết định hiện tại là Not Yet vì nhóm còn cần đo baseline và thử phương án No AI trước.

---

## 7. Tài liệu tham khảo

1. **Discord Inc.**, _How to Use Search on Discord_, Discord Support, 2024. [Link](https://support.discord.com/hc/en-us/articles/115000468588-How-to-Use-Search-on-Discord)
2. **Discord Inc.**, _Pin Messages FAQ_, Discord Support, 2024. [Link](https://support.discord.com/hc/en-us/articles/221421867-Pin-Messages-FAQ)
3. **Discord Inc.**, _Announcement Channel FAQ_, Discord Support, 2024. [Link](https://support.discord.com/hc/en-us/articles/360032008192-Announcement-Channel-FAQ)
4. **David Bland & Alexander Osterwalder**, _Testing Business Ideas: A Field Guide for Rapid Experimentation_, Wiley, 2019.
5. **Rob Fitzpatrick**, _The Mom Test_, 2013.
6. **Google PAIR**, _People + AI Guidebook_, Google, 2021. [Link](https://pair.withgoogle.com/guidebook/)
7. **Jeff Gothelf & Josh Seiden**, _Lean UX_, O'Reilly Media, 2021.
