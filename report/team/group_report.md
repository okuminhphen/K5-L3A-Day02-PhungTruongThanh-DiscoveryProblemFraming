# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: PhungTruongThanh
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khó tìm và nhận biết các thông báo quan trọng (hạn nộp bài, đổi lịch) bị trôi trong kênh Discord học tập (Candidate B1).
- Quyết định cuối: Not Yet (Cần phỏng vấn thực tế ngoài nhóm và thử nghiệm quy ước No AI trước)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| A1 | Phụng | **Báo lỗi thiếu thông tin:** Khi nhận thông báo “máy bị lỗi”, tôi muốn có đủ thông tin về triệu chứng ngay từ đầu, để xác định cách xử lý nhanh hơn. | Nhân viên IT | Hỏi lại 2–3 lượt để lấy đủ mô tả và ảnh lỗi | "Nếu bắt điền biểu mẫu nhiều trường thì người dùng có lười rồi vẫn nhắn tin tự do không?" (Trường hỏi) |
| A2 | Phụng | **Yêu cầu hỗ trợ nằm rải rác:** Khi nhận yêu cầu hỗ trợ qua nhiều kênh, tôi muốn biết những việc nào còn chưa xử lý, để không bỏ sót yêu cầu. | Nhân viên IT | Đối chiếu trạng thái yêu cầu giữa nhiều kênh rời rạc | "Có thể quy định công ty chỉ dùng 1 kênh duy nhất không, tại sao phải gom nhiều kênh?" (Thanh hỏi) |
| A3 | Phụng | **Tìm và soạn lại hướng dẫn lỗi thường gặp:** Khi nhân viên hỏi cách xử lý một lỗi thường gặp, tôi muốn tìm nhanh hướng dẫn phù hợp, để hỗ trợ họ mà không phải soạn lại từ đầu. | Nhân viên IT | Tìm kiếm hướng dẫn cũ nằm rải rác | "Làm một trang FAQ/Wiki có giải quyết được không nếu người dùng vẫn ngại đọc bài dài?" (Trường hỏi) |
| B1 | Trường | **Khó tìm thông báo quan trọng trong Discord:** Khi kênh chat quá nhiều tin thảo luận, tôi muốn lọc nhanh các thông báo bài tập/lịch học quan trọng, để không bị trôi tin và lỡ hạn. | Học viên | Đọc lướt nhiều tin nhắn để nhận ra hạn nộp, đổi lịch | "Discord đã có tính năng ghim tin nhắn (Pinned) và kênh `#announcement`, tại sao vẫn bị trôi?" (Phụng hỏi) |
| B2 | Trường | **Chép deadline vào lịch cá nhân:** Khi có deadline mới công bố trên lớp, tôi muốn đưa nhanh vào lịch cá nhân, để nhận thông báo nhắc nhở tự động đúng hạn. | Học viên | Xác định giờ nộp và nhập lịch thủ công từng môn | "Một tuần có bao nhiêu deadline để việc nhập tay này trở thành vấn đề nghiêm trọng?" (Thanh hỏi) |
| B3 | Trường | **Conflict khi cùng sửa báo cáo:** Khi cả nhóm cùng viết báo cáo bài tập lớn, tôi muốn đồng bộ nội dung đang làm, để không bị ghi đè hoặc xung đột code/text. | Nhóm làm lab | Giải quyết xung đột nội dung khi ghép bài | "Nếu dùng Google Docs hoặc chia file Markdown riêng theo từng mục thì có còn bị conflict không?" (Phụng hỏi) |
| C1 | Thanh | **Khó chọn nội dung ưu tiên ôn từ nhiều PDF:** Khi chuẩn bị thi cuối kỳ từ hàng chục slide và tài liệu, tôi muốn biết các phần trọng tâm cần học, để ôn tập hiệu quả mà không lan man. | Sinh viên | Đọc và chọn lọc nội dung trọng tâm từ nhiều tài liệu | "Trọng tâm bài thi phụ thuộc vào đề giảng viên ra, làm sao công cụ biết được phần nào chắc chắn thi?" (Trường hỏi) |
| C2 | Thanh | **Điểm danh đầu giờ mất thời gian:** Khi bắt đầu buổi học/lab, tôi muốn ghi nhận sự có mặt nhanh chóng, để bắt đầu bài học đúng giờ mà không tốn thời gian gọi tên. | Giảng viên, sinh viên | Gọi tên và đọc lại danh sách từng người | "Trường hoặc lớp đã có mã QR quét điểm danh chưa, rào cản ở đây là công nghệ hay thói quen?" (Phụng hỏi) |
| C3 | Thanh | **Phải hướng dẫn lại thao tác điện thoại cho bố mẹ:** Khi bố mẹ gặp khó khi dùng smartphone, tôi muốn có cách hướng dẫn trực quan từ xa, để bố mẹ tự làm được mà không phải hỏi lại cùng một việc. | Bố mẹ, người hướng dẫn | Nhắc lại các thao tác nhiều lần vì người lớn tuổi chưa nhớ | "Vấn đề này quá phụ thuộc vào khả năng tiếp thu công nghệ của người lớn tuổi, liệu giải pháp số có khả thi?" (Trường hỏi) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Tìm và chọn thông tin cần thiết | A3, B1, C1 | Phải đọc hoặc tìm kiếm qua nhiều nội dung rời rạc để lấy đúng phần thông tin phù hợp |
| B — Tiếp nhận và theo dõi yêu cầu | A1, A2 | Thiếu thông tin ban đầu hoặc thiếu trạng thái minh bạch để xử lý và bàn giao công việc |
| C — Công việc hành chính lặp lại | B2, C2 | Các thao tác thủ công, lặp đi lặp lại định kỳ có quy trình từng bước tương đối rõ ràng |
| D — Phối hợp sửa tài liệu | B3 | Nhiều người cùng thao tác và thay đổi trên một tài liệu/báo cáo dẫn đến xung đột nội dung |
| E — Hướng dẫn thao tác và ghi nhớ | C3 | Người dùng khó nhớ các bước thao tác kỹ thuật và cần người khác hướng dẫn/nhắc lại nhiều lần |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian học viên tìm kiếm và nhận biết các thông báo quan trọng (hạn nộp, đổi lịch) trên Discord từ 15 phút/ngày xuống dưới 3 phút/ngày
├── Opportunity 1: Thông báo bài tập và đổi lịch bị trôi lẫn trong hàng trăm tin nhắn thảo luận hằng ngày trong các kênh chat chung
├── Opportunity 2: Tính năng ghim tin (Pinned Messages) không được dọn dẹp thường xuyên, lẫn lộn giữa thông báo cũ đã hết hạn và thông báo mới
└── Opportunity 3: Từ khóa tìm kiếm không đồng nhất giữa các môn/mentor, khiến việc dùng Discord Search khó ra đúng thông báo mới nhất
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ✗ *"Xây dựng bot Discord AI tự động tóm tắt tin nhắn"* ← Solution đội lốt opportunity (nhu cầu gốc là lọc nhận biết thông báo quan trọng, bot chỉ là một công cụ khả dĩ).
- ✗ *"Tạo kênh #announcement riêng và ping @everyone bắt buộc"* ← Solution đội lốt opportunity (đây là cách tổ chức kênh/quy định, chưa giải quyết được việc người dùng bị bội thực thông báo).
- ✗ *"Dùng chatbot hỏi đáp tự động trên Discord"* ← Solution đội lốt opportunity.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| B1 — Trường: Tìm thông báo quan trọng trên Discord | 5 | 5 | 3 | 4 | 5 | 5 | 4 | **31/35** |
| C1 — Thanh: Chọn nội dung ưu tiên ôn từ nhiều PDF | 5 | 4 | 3 | 3 | 3 | 4 | 4 | **26/35** |
| A1 — Phụng: Yêu cầu báo lỗi thiếu thông tin | 4 | 4 | 1 | 4 | 4 | 4 | 3 | **24/35** |

**Candidate được chọn:** B1 — Tìm thông báo quan trọng trên Discord (của Trường).

**Vì sao chọn:**
- Đạt điểm cao nhất (31/35) trên 7 tiêu chí.
- Quy trình cụ thể, phạm vi nhỏ, vừa sức giải quyết trong một buổi lab.
- Rất dễ tiếp cận đối tượng học viên ngay tại lớp để phỏng vấn kiểm chứng và đo lường tác động thực tế (nhóm chọn B1 vì bài toán rõ ràng, dễ đo lường chứ không phải vì có thể dùng AI).
- So sánh được rõ ràng giữa các mức can thiệp: No AI (kênh riêng/ghim tin), Rule (bot lọc keyword), Workflow và Agent.

**Vì sao loại các candidate còn lại:**
- **Loại C1 (Chọn nội dung ưu tiên ôn từ nhiều PDF — 26/35):** Trải nghiệm cá nhân rõ nhưng thời gian đọc/chọn chỉ là ước lượng; rất khó kiểm chứng ngay trong một buổi lab rằng việc rút ngắn thời gian chọn tài liệu vẫn đảm bảo chất lượng ôn thi.
- **Loại A1 (Yêu cầu báo lỗi thiếu thông tin — 24/35):** Dù có thể đo số lượt hỏi lại và thời gian tiếp nhận, nhưng hiện chưa có tình huống thật hay số liệu đo lường trực tiếp tại lớp; đối tượng nhân viên IT và người dùng nội bộ khó tiếp cận để kiểm chứng ngay trong buổi lab hơn so với học viên.

**Xử lý bất đồng (nếu có):**
- Điểm “nhóm hiểu domain” ở cả 3 dòng hiện là ước tính ban đầu của nhóm, cần được điều chỉnh lại sau khi kiểm chứng thực tế với người dùng.
- Nhóm thống nhất: B1 có bằng chứng ban đầu từ trải nghiệm của Trường; thời gian 15 phút/ngày chưa được đo và chưa thể coi là đại diện cho cả lớp. Sang CP4, nhóm phỏng vấn 2 học viên ngoài nhóm để kiểm tra cách tìm thông báo và những trường hợp bỏ sót/hiểu nhầm. Kết quả còn sơ bộ do mẫu nhỏ và thời gian đều là ước lượng.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Ngoài Trường, các học viên khác cũng mất thời gian tìm thông báo hạn nộp hoặc đổi lịch trên Discord. | Value | 5 | 2 | Có |
| 2 | Khó khăn chủ yếu nằm ở việc nhận ra thông báo quan trọng giữa nhiều tin thảo luận, không chỉ do học viên ít mở Discord. | Value | 5 | 1 | Có |
| 3 | Ghim tin, kênh thông báo riêng và tìm kiếm có sẵn chưa đủ giải quyết khó khăn trong bối cảnh lớp. | Value | 5 | 1 | Có |
| 4 | Học viên có thể tìm và mở đúng tin gốc từ một danh sách thông báo ngắn. | Usability | 4 | 1 | Sau khi xác nhận pain |
| 5 | Nhóm có thể tiếp cận hợp lệ các tin cần thiết và nhận biết bản thông báo mới nhất, kể cả khi lịch thay đổi. | Feasibility | 5 | 1 | Có |
| 6 | Ban quản trị cho phép cách tiếp cận dữ liệu dự kiến; công sức duy trì và chi phí phù hợp với nhóm. | Viability | 5 | 1 | Có, trước khi thử tích hợp |

**Giả định nhóm ưu tiên kiểm chứng trong buổi này:**

Ưu tiên giả định 1, 2 và 3: xác nhận vấn đề có xuất hiện ở học viên ngoài nhóm, xác định bước thực sự gây khó khăn và kiểm tra lý do các tính năng sẵn có chưa đủ. Đồng thời hỏi người quản lý kênh về quyền tiếp cận dữ liệu trước khi đề xuất tích hợp.

### 3.2. Kiểm chứng

**Cách làm:** Nhóm phỏng vấn nhanh 2 học viên ngoài nhóm bằng câu hỏi gợi nhớ về sự việc đã xảy ra: lần gần nhất cần tìm thông báo, các bước tìm, thời gian và cách đo, trường hợp bỏ sót/hiểu nhầm, trải nghiệm với Search/ghim/kênh thông báo, và lần tìm nhanh không gặp khó khăn. Tên được thay bằng mã P1/P2. Ngày và hình thức phỏng vấn chưa có trong ghi chép, cần bổ sung nếu còn nhớ.

#### Interview Snapshot P1

| Trường | Ghi nhận |
|---|---|
| Người được hỏi | P1 — học viên ngoài nhóm, dùng Discord lớp |
| Thời điểm và cách hỏi | Ngày/hình thức phỏng vấn chưa được ghi lại. Sự việc gần nhất được kể: tối thứ Năm tuần trước. |
| Lần gần nhất gặp vấn đề | P1 tìm hạn nộp bài cá nhân: mở kênh thông báo, thấy tin cũ, chuyển sang kênh học tập, kéo tìm nhưng không thấy, rồi hỏi bạn cùng lớp và mở tin gốc qua link được gửi. |
| Mất bao lâu, bao lần? | Khoảng 5 phút tự tìm và chờ bạn trả lời thêm vài phút; P1 ước lượng, không bấm giờ. |
| Kết quả / workaround | Tìm được hạn tối thứ Sáu, chụp phần hạn nộp và đặt nhắc trên điện thoại. Từng bỏ sót yêu cầu nộp link sản phẩm khi đọc lướt trên điện thoại và bổ sung sau khi được nhắc. |
| Công cụ có sẵn / tín hiệu phản bác | Tìm “record” không ra, đổi sang “ghi hình” thì tìm được. Tin mới, tiêu đề và giờ rõ trong kênh thông báo được tìm nhanh. P1 chưa dùng ghim tin. |
| Câu nói đáng nhớ | “Khoảng 5 phút tự tìm, rồi đợi bạn trả lời thêm vài phút nữa.” |
| Insight / giới hạn | Việc chuyển kênh và phụ thuộc vào link từ bạn làm tăng thời gian tìm trong lần này; một trường hợp chưa đủ để kết luận đây là pattern chung. |

#### Interview Snapshot P2

| Trường | Ghi nhận |
|---|---|
| Người được hỏi | P2 — học viên ngoài nhóm, dùng Discord lớp |
| Thời điểm và cách hỏi | Ngày/hình thức phỏng vấn chưa được ghi lại. Sự việc gần nhất được kể: chiều thứ Bảy vừa rồi. |
| Lần gần nhất gặp vấn đề | P2 tìm giờ học Chủ nhật trên điện thoại bằng Search với từ “Chủ nhật”, mở nhầm lịch tuần trước, rồi xem ngày đăng và mở tin tuần này. P2 đọc thêm vì tin đề cập lịch của hai lớp. |
| Mất bao lâu, bao lần? | Khoảng 3–4 phút; P2 ước lượng, không bấm giờ. |
| Kết quả / workaround | Tìm được giờ học 14:00, thêm vào lịch điện thoại và gửi link tin cho bạn cùng lớp. Từng lưu ảnh của thông báo cũ và không nhận ra hạn nộp đã được sửa trong tin nhắn; biết tin gia hạn qua bạn vào hôm sau. |
| Công cụ có sẵn / tín hiệu phản bác | Search và kênh thông báo được dùng khi tìm lịch. Ghim tin giúp tìm hướng dẫn nộp bài khi P2 biết tài liệu đã được ghim. Tìm nhanh khi từ khóa trùng với tên bài và hạn nằm ngay đầu tin. |
| Câu nói đáng nhớ | “Những lần tìm lâu thì thường mình chỉ nhớ nội dung mang máng.” |
| Insight / giới hạn | Việc nhớ không chính xác từ khóa, phân biệt lịch tuần này với tuần trước và nhận ra bản cập nhật có thể gây khó; P2 cũng tìm nhanh khi nhớ từ khóa chính xác. Đây vẫn là một trường hợp đơn lẻ. |

**Tổng hợp:**

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Báo cáo cá nhân của Trường — CP2 | 1 người trong nhóm, không tính vào phỏng vấn CP4 | Mô tả việc đọc tin và từng bỏ sót thông báo; 15 phút/ngày là ước lượng | Chưa xác nhận mức độ phổ biến ngoài nhóm |
| Phỏng vấn học viên ngoài nhóm P1/P2 | 2 người | Cả hai kể được lần tìm thông báo mất vài phút theo ước lượng; có ví dụ bỏ sót chi tiết hoặc không nhận ra bản cập nhật | Search, ghim tin và kênh thông báo có ích khi nhớ đúng từ khóa, biết đúng kênh hoặc tin được trình bày rõ |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Nhóm giữ B1 nhưng làm rõ vấn đề không chỉ là tin nhắn bị trôi: người học có thể phải xác định đúng kênh, từ khóa, lớp áp dụng và bản cập nhật mới nhất; đọc lướt trên điện thoại hoặc lưu ảnh cũ cũng có thể khiến họ bỏ sót chi tiết. Hai cuộc phỏng vấn chưa xác nhận baseline 15 phút/ngày hoặc mức độ phổ biến trong cả lớp vì thời gian đều là ước lượng và mẫu còn nhỏ. Nhóm cần đo baseline thực tế và kiểm tra thêm cách tổ chức thông báo trước khi quyết định triển khai công nghệ.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro cần kiểm tra | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Discord Search** | [Hướng dẫn Search](https://support.discord.com/hc/en-us/articles/115000468588-How-to-Use-Search-on-Discord) | Tìm lại tin theo từ khóa, người gửi, kênh và thời gian | Có sẵn trên mọi client; hỗ trợ nhiều bộ lọc (from, in, has, before/after) | Cần kiểm tra người học có biết dùng cú pháp tìm kiếm và có nhớ từ khóa phù hợp không | Đo hiệu quả tìm kiếm sẵn có trước khi đề xuất công cụ mới |
| **Pinned Messages** | [Hướng dẫn ghim tin](https://support.discord.com/hc/en-us/articles/221421867-Pin-Messages-FAQ) | Truy cập lại các thông báo quan trọng đã được ghim | Giữ tin dễ truy cập ở đầu kênh, cho phép nhảy thẳng về tin gốc | Cần người có quyền Admin/Mod ghim; cần quy trình gỡ bỏ các thông báo đã hết hạn | Kiểm tra xem việc ghim và cập nhật tin thường xuyên có đủ giải quyết pain chưa |
| **Announcement Channels** | [Hướng dẫn kênh thông báo](https://support.discord.com/hc/en-us/articles/360032008192-Announcement-Channel-FAQ) | Tập trung và phát hành thông báo một chiều | Hỗ trợ đăng thông báo không bị trôi bởi tin chat, cho phép theo dõi kênh | Cần bật tính năng Community Server; hiệu quả ở lớp vẫn phụ thuộc vào cách tổ chức và ý thức người đăng | Thử cách tổ chức thông báo rõ ràng trước khi tăng độ phức tạp công nghệ |

*Ghi chú:* Các tính năng trên được xác nhận từ tài liệu chính thức của Discord; những khoảng trống trong bảng là điều nhóm cần kiểm tra tại lớp, chưa phải hạn chế đã được chứng minh.

**Kết luận research:**

```text
Discord đã có sẵn các tính năng tìm kiếm, ghim tin và kênh thông báo. Vì vậy, nhóm chưa có đủ căn cứ kết luận là cần AI. 
Bước tiếp theo là quan sát cách học viên sử dụng các tính năng này và xác định phần khó khăn còn lại. Nếu cách tổ chức lại kênh hoặc hướng dẫn dùng tìm kiếm có sẵn đáp ứng được mục tiêu, nhóm ưu tiên phương án đơn giản đó.
```

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII):

```text
HIỆN TẠI — 5 bước, ~15 phút/ngày, 5/5 bước thủ công

[1. Mở Discord & vào kênh lớp: 1']
→ [2. Cuộn lên tìm vị trí tin chưa đọc: 2']
→ [3. Đọc lướt hàng trăm tin chat để lọc thông báo quan trọng: 10'] ← BOTTLENECK (tin trôi, dễ sót)
→ [4. Đối chiếu tin nhắn xem có phải bản cập nhật mới nhất không: 1']
→ [5. Tự ghi chú deadline / đổi lịch vào sổ hoặc lịch cá nhân: 1']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Học viên | Thông báo ứng dụng Discord | Đã vào đúng kênh chat lớp học | ~1 phút / mỗi ngày | Thường làm vào cuối ngày hoặc sáng trước giờ học |
| 2 | Học viên | Hàng trăm tin nhắn mới tích lũy | Điểm bắt đầu đọc (tin chưa đọc gần nhất) | ~2 phút / mỗi ngày | Dễ bị trượt tay cuộn quá hoặc nản vì quá nhiều tin |
| 3 | Học viên | Dòng tin nhắn thảo luận hỗn tạp | Nhận diện tin có chứa deadline, đổi lịch | ~10 phút / mỗi ngày | **BOTTLENECK CHÍNH:** Tin quan trọng nằm lẫn trong thảo luận làm bài, spam sticker, meme |
| 4 | Học viên | Tin thông báo vừa tìm được | Xác định tin này còn hiệu lực hay đã bị sửa đổi | ~1 phút / mỗi ngày | Dễ nhầm nếu mentor đăng đính chính ở tin nhắn sau đó |
| 5 | Học viên | Nội dung ngày/giờ chính xác | Note cá nhân (Notion, Google Calendar, sổ tay) | ~1 phút / mỗi ngày | Nhập thủ công, có nguy cơ nhập sai múi giờ hoặc gõ nhầm |

**Bottleneck chính:** Bước 3 — Đọc lướt từng dòng tin nhắn thảo luận để tự nhận diện tin nào là thông báo quan trọng (hạn nộp, đổi lịch). Mất khoảng 10–12 phút/ngày vì thông báo bị trôi nhanh giữa hàng trăm tin chat thường ngày, gây mệt mỏi và rủi ro bỏ sót cao.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — 4 bước, ~2.5 phút/ngày, 1/4 bước thủ công

[1. Lọc tin nhắn từ người có thẩm quyền / kênh thông báo: 10s]   ← RULE (webhook/bot filter theo Role/Channel)
→ [2. Trích xuất hạn nộp, môn học, tóm tắt 1 câu kèm link gốc: 20s] ← AI (LLM trích xuất thực thể & tóm tắt)
→ [3. Hiển thị bảng tổng hợp thông báo mới trong ngày: 10s]         ← RULE (giao diện dashboard / bot digest)
→ [4. Học viên đọc tóm tắt, bấm link kiểm tra tin gốc & lưu lịch: 2'] ← CON NGƯỜI (HITL)

BOUNDARY: AI không tự ý thêm lịch vào Calendar của học viên; AI không suy đoán deadline nếu tin nhắn không ghi rõ ngày giờ; bắt buộc luôn hiển thị link dẫn tới tin nhắn Discord gốc.
PHƯƠNG ÁN QUAY VỀ: Nếu bot gặp sự cố hoặc bản tóm tắt AI thiếu thông tin, học viên dùng tính năng ghim tin (Pinned Messages) và kênh #announcement hoặc tìm kiếm theo cú pháp có sẵn.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 bước | 4 bước | Tự động hóa khâu gom tin và trích xuất |
| Tổng thời gian | ~15 phút/ngày | ~2.5 phút/ngày | Giảm hơn 80% thời gian tìm kiếm tin |
| Số bước thủ công | 5/5 bước | 1/4 bước (bước 4) | Con người chỉ đọc bản tóm tắt và kiểm chứng tin gốc |
| Bottleneck chính | Đọc lướt hàng trăm tin chat | Học viên kiểm tra tin gốc (kiểm soát an toàn) | Chuyển điểm nghẽn sang khâu xác nhận chất lượng (HITL) |
| Rủi ro mới phát sinh | — | AI trích xuất sai ngày giờ, bỏ sót thông báo viết ngầm | Khắc phục bằng boundary và bắt buộc đính kèm link tin gốc |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên tham gia học tập và làm bài tập trên kênh Discord chung của lớp (~40 học viên). |
| **Quy trình** | Hằng ngày mở Discord → cuộn tìm tin chưa đọc → đọc lướt qua hàng trăm tin chat thảo luận để lọc thông báo quan trọng → đối chiếu cập nhật mới nhất → ghi chú deadline vào lịch cá nhân. |
| **Bottleneck** | Khâu đọc lướt hàng trăm tin nhắn thảo luận để nhận ra thông báo hạn nộp hoặc đổi lịch (mất ~10–12 phút/ngày) vì tin nhắn quan trọng dễ bị trôi nhanh và lẫn lộn giữa tin chat thường nhật. |
| **Impact** | Mỗi học viên mất ~15 phút/ngày (~75 phút/tuần); từng xảy ra trường hợp học viên bỏ sót thông báo đổi lịch học hoặc nộp muộn bài tập; tạo tâm lý bất an, phải hỏi đi hỏi lại bạn cùng lớp. |
| **Success Metric** (baseline → target, cách đo) | **Baseline:** Mất ~15 phút/ngày để tìm và xử lý thông báo (ước lượng của Trường trong CP1–CP2); tỷ lệ bỏ sót thông báo quan trọng ~1 lần/tháng. <br>**Target:** Giảm thời gian tìm và nhận biết thông báo xuống dưới 3 phút/ngày; số thông báo quan trọng bị bỏ sót giảm về 0. <br>**Cách đo:** 3–5 học viên tự bấm giờ liên tục trong 1 tuần pilot; đếm số lần phản ánh bỏ sót hoặc nộp trễ deadline. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | - AI **không được** tự động thêm hoặc sửa sự kiện lịch cá nhân khi người dùng chưa xác nhận. <br>- AI **không được** suy đoán hoặc tự bịa ra hạn nộp nếu tin nhắn không nêu rõ ngày giờ cụ thể. <br>- AI **bắt buộc** phải dẫn link kèm trích dẫn nguyên văn tin nhắn gốc trên Discord để học viên bấm vào kiểm tra lại (Human-in-the-Loop) trước khi quyết định hành động. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- **Phản biện 1 (từ AI):** Baseline 15 phút/ngày và tần suất sót 1 lần/tháng mới chỉ là ước lượng chủ quan của 1 học viên (Trường), chưa có số liệu đo đạc thực tế của các bạn khác trong lớp.
  - *Nhóm đồng ý:* Nhóm xác định rõ con số 15 phút là giả thuyết ban đầu (đã ghi trong Assumption Map CP4) và sẽ tổ chức bấm giờ thực tế cho 3-5 học viên ở giai đoạn pilot để có baseline chuẩn xác.
- **Phản biện 2 (từ Phụng & Thanh):** Nếu giảng viên/mentor chỉ cần đăng thông báo vào kênh `#announcement` và khóa chat thì học viên có còn mất 15 phút không? Cần phân định rõ vấn đề do thói quen tổ chức kênh hay do công cụ.
  - *Nhóm đồng ý một phần:* Dù có kênh `#announcement`, thực tế trợ giảng và học viên vẫn thảo luận về việc gia hạn, dời lịch ngay trong thread bài học. Quy trình mới cần kết hợp cả quy ước kênh (No AI/Rule) trước khi phụ thuộc hoàn toàn vào AI.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ Trung bình — Độ phức tạp Thấp đến Trung bình** (Ô phù hợp cho **Workflow** kết hợp Rule).

Vì sao:
- **Độ mơ hồ (Ambiguity): Trung bình.** Thông báo trên Discord được viết bằng ngôn ngữ tự nhiên tự do, không theo khuôn mẫu cố định (ví dụ: *"mai dời sang chiều nhé"*, *"hạn chót lab 2 đẩy sang 23h59 Chủ nhật"*, *"thông báo nộp bổ sung"*), đôi khi xen lẫn tiếng lóng hoặc ngữ cảnh ngầm của lớp học. Do đó, các bộ lọc từ khóa đơn giản (Rule) dễ bị bỏ sót hoặc nhận diện sai. Tuy nhiên, kết quả mong muốn đầu ra lại rất cụ thể và có cấu trúc: loại sự kiện, môn học, thời hạn và tóm tắt ngắn.
- **Độ phức tạp (Complexity): Thấp đến Trung bình.** Quy trình xử lý tuần tự gồm các bước xác định trước: nhận tin nhắn qua Discord API → lọc người gửi → trích xuất thông tin/tóm tắt → hiển thị digest → học viên đối chiếu tin gốc. Không đòi hỏi hệ thống tự lập kế hoạch nhiều bước (multi-step planning) hay tự hành động ra ngoài môi trường mà chỉ cần một luồng xử lý cố định có người kiểm soát.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Thống nhất quy ước: Mọi deadline/đổi lịch bắt buộc đăng ở kênh `#announcement`, ghim tin quan trọng và gỡ ghim khi hết hạn. | Giảng viên, trợ giảng và ban cán sự lớp tuân thủ 100% quy ước đăng tin tập trung và dọn dẹp tin ghim đều đặn. | Rất khó duy trì kỷ luật; các trao đổi dời lịch đột xuất trong kênh chat thảo luận chung vẫn bị trôi. | Dự phòng nền tảng |
| **Rule** | Tạo Discord bot lọc tin nhắn theo từ khóa cố định (`deadline`, `hạn nộp`, `dời lịch`, `hoãn`, `nộp bài`) của người có vai trò Admin/Mentor. | Người đăng thông báo luôn sử dụng đúng các từ khóa quy định trong danh sách từ điển của bot. | **Báo nhầm:** câu hỏi thảo luận của học viên có chứa từ khóa bị bắt nhầm. **Bỏ sót:** giảng viên dùng cách nói tự nhiên (*"trưa mai nộp nhé"*, *"dời sang tuần sau"*) không khớp từ khóa. | Dùng làm bộ lọc thô tầng 1 |
| **Workflow** | **Rule** lọc tin theo Role người gửi + kênh → **AI** phân tích ngữ cảnh ngôn ngữ tự nhiên để xác định tính xác thực của thông báo, trích xuất hạn chót/lịch học kèm tóm tắt 1 câu → Bot gửi digest định kỳ kèm link tin gốc → **Con người (HITL)** bấm link gốc kiểm tra lại. | Khi muốn bắt trọn các thông báo viết tự do nhưng vẫn giữ luồng kiểm duyệt an toàn, không để AI tự quyết định thay con người. | Chi phí gọi API LLM (dù rất nhỏ); rủi ro AI ảo giác trích xuất sai ngày giờ nếu prompt không chặt chẽ (được chặn bằng link gốc). | **CHỌN (nếu bước kiểm chứng yêu cầu)** |
| **Agent** | Agent tự do đọc toàn bộ server, tự tương tác hỏi lại giảng viên khi thông báo chưa rõ, tự động điền vào Google Calendar cá nhân của từng học viên và tự nộp bài thay khi đến hạn. | Khi bài toán đòi hỏi hệ thống phải tự chủ ra quyết định mà không cần học viên can thiệp ở bất kỳ khâu nào. | Rủi ro vượt quyền cực lớn; bảo mật dữ liệu; chi phí cao; nếu agent hiểu sai hạn nộp sẽ dẫn đến nộp bài hỏng hoặc bỏ lỡ deadline mà học viên không hề hay biết. | **LOẠI BỎ** |

**Mức chọn:** **Workflow (Kết hợp Rule + AI trích xuất + Con người kiểm duyệt)** nếu cần giải pháp công nghệ; nhưng ưu tiên thử nghiệm **Rule + No AI** trước theo kết luận nghiên cứu.

**Vì sao không chọn mức đơn giản hơn:**
Nếu chỉ dùng **No AI** (quy ước kênh), kinh nghiệm thực tế cho thấy rất khó ép 100% người dạy và học viên tuân thủ nghiêm ngặt, nhất là trong các kỳ đồ án gấp rút khi thông báo dời lịch thường phát sinh ngay giữa thread chat. Nếu chỉ dùng **Rule** (keyword search), tỷ lệ bỏ sót (false negative) quá cao do sự phong phú của tiếng Việt và ngữ cảnh hội thoại, mà trong môi trường học tập thì bỏ sót deadline gây thiệt hại nặng nề hơn rất nhiều.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Dự đoán xem tin nhắn có chứa thông báo thời hạn/đổi lịch hợp lệ hay không; trích xuất thực thể có cấu trúc: *Môn học, Loại sự kiện, Thời gian cụ thể (chuẩn hóa sang giờ GMT+7)* và tạo bản tóm tắt 1 câu súc tích. |
| **Judgment** — con người cân nhắc, quyết định gì? | Học viên nhìn vào danh sách tóm tắt, quyết định thông báo này có liên quan đến nhóm/lớp của mình hay không và bấm link gốc để xác nhận tính chính xác trước khi lên kế hoạch. |
| **Action** — hành động cuối cùng là gì, ai làm? | Học viên tự tay thêm sự kiện vào lịch cá nhân hoặc sắp xếp thời gian làm bài nộp đúng hạn. Hệ thống không tự động can thiệp vào tài khoản hay bài nộp của học viên. |
| **Outcome** — đo kết quả bằng gì? | Thời gian tìm và xử lý thông báo của học viên giảm từ 15 phút/ngày xuống <3 phút/ngày; số ca trễ hạn do sót tin giảm về 0; tỷ lệ trích xuất chính xác thời hạn đạt >95%. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Nội dung văn bản tin nhắn, timestamp gửi, tên tác giả, role người gửi, tên kênh Discord. Dữ liệu này có sẵn 100% thông qua Discord Gateway API / Bot token. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Hai nút bấm reaction ngay dưới mỗi tin tóm tắt: 👍 (Trích xuất đúng) / 👎 (Trích xuất sai/báo nhầm). Ghi log lại các trường hợp học viên bấm 👎 để fine-tune prompt trích xuất. |

### 6.4. Hai câu hỏi của Google PAIR

- **Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)? Bằng chứng:**
  - **Người dùng muốn được hỗ trợ (Augment).** Học viên chỉ cần công cụ gom lại và trích xuất sẵn ngày giờ kèm đường dẫn trực tiếp đến tin nhắn gốc để họ tự kiểm tra và chủ động quản lý lịch của mình.
  - *Bằng chứng:* Việc ghi nhận lịch học và nộp bài liên quan trực tiếp đến điểm số cá nhân. Không học viên nào muốn giao quyền tự động (automate) hoàn toàn cho một con bot tự xếp lịch hay tự quyết định hạn nộp vì nếu bot sai thì sinh viên là người chịu hậu quả trực tiếp (trừ điểm, trượt môn).
- **AI sai kiểu nào tệ hơn, báo nhầm hay bỏ sót? Vì sao, và thiết kế đã xử lý thế nào:**
  - **BỎ SÓT (False Negative) TỆ HƠN NHIỀU.** Nếu AI báo nhầm một tin nhắn thường thành thông báo hạn nộp, học viên chỉ mất 2–3 giây liếc mắt và bỏ qua. Nhưng nếu AI bỏ sót một thông báo dời deadline lên sớm hoặc đổi phòng thi, học viên sẽ bị trễ bài hoặc vắng thi, dẫn đến hậu quả nghiêm trọng về học tập.
  - *Thiết kế xử lý:* Bộ lọc tầng 1 (Rule) được cấu hình với độ nhạy cao (recall ưu tiên), chấp nhận lấy dư tin nhắn từ tất cả những người có thẩm quyền (Mentor, TA, Ban cán sự). Ở tầng 2 (AI), prompt được chỉ dẫn thiên về thận trọng: nếu nghi ngờ một tin nhắn có khả năng là thông báo, vẫn đưa vào mục *"Thông báo cần chú ý"* kèm trích dẫn nguyên văn thay vì tự ý loại bỏ.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên lớp L3A (~40 người) theo dõi thông tin học tập, bài tập trên Discord. |
| **Quy trình** | Hằng ngày bot lắng nghe tin nhắn từ mentor/kênh chỉ định → AI trích xuất thông tin hạn nộp/đổi lịch → đăng bản digest tóm tắt 1 câu kèm link gốc mỗi ngày lúc 18h → học viên đọc tóm tắt, bấm link kiểm tra tin gốc và lưu lịch. |
| **Bottleneck** | Khâu đọc lướt hàng trăm tin chat thảo luận được giải quyết hoàn toàn bằng việc tự động hóa trích xuất. Điểm nghẽn duy nhất còn lại là thời gian học viên đối chiếu tin gốc (~1–2 phút/ngày để kiểm soát an toàn). |
| **Impact** | Tiết kiệm ~12–13 phút/ngày cho mỗi học viên (~60–65 phút/tuần); loại bỏ rủi ro bỏ sót deadline hoặc trễ hạn; giải tỏa căng thẳng tâm lý theo dõi tin trôi. |
| **Success Metric** (baseline → target, cách đo) | - **Thời gian tìm/nhận biết:** từ 15 phút/ngày (ước lượng) xuống dưới 3 phút/ngày (đo bằng bấm giờ trong 1 tuần pilot). <br>- **Tỷ lệ bỏ sót thông báo:** từ ~1 lần/tháng về 0 lần. <br>- **Chất lượng trích xuất AI:** Tỷ lệ trích xuất đúng hạn nộp và đúng môn học đạt ≥95% trên tổng số thông báo được xử lý. |
| **Boundary** | - AI tuyệt đối không tự sửa hay tạo lịch tự động trên tài khoản cá nhân của học viên. <br>- AI không suy đoán ngày giờ khi tin nhắn gốc viết mơ hồ; trong trường hợp đó phải gắn nhãn *"Cần xác nhận lại với người gửi"*. <br>- Bắt buộc 100% bản tóm tắt phải đính kèm URL dẫn thẳng đến tin nhắn Discord gốc (HITL). |
| **AI intervention point** | Bước 2 trong quy trình: Nhận diện ngữ cảnh và trích xuất thông tin có cấu trúc (Môn học, Hành động, Thời hạn ISO, Tóm tắt 1 câu) từ tin nhắn văn bản tự nhiên. |
| **Mức chọn** | **Workflow** (Rule lọc người gửi/kênh → AI trích xuất thực thể & tóm tắt → Bot gửi thông báo → Con người kiểm tra tin gốc). |
| **Rủi ro & người kiểm tra** | Rủi ro AI trích xuất nhầm ngày/giờ hoặc hiểu sai thông báo đính chính. Người kiểm tra: Học viên trực tiếp kiểm tra bằng cách bấm vào link tin gốc trước khi note lịch (Human-in-the-Loop). |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| **Quy trình** | Quy trình thủ công học viên tự mở Discord cuộn tin | Quy trình bán tự động: Bot lắng nghe → AI trích xuất → Học viên kiểm tra | Định hình rõ luồng vận hành công nghệ và vị trí con người kiểm soát |
| **Success Metric** | Chỉ đo thời gian (15' → 3') và số lần sót | Bổ sung thêm metric chất lượng trích xuất của AI (độ chính xác ≥95%) | Phản biện nhận được chỉ ra rằng nhanh hơn nhưng trích xuất sai ngày thì còn nguy hiểm hơn đọc tay |
| **AI intervention point** | Chưa xác định rõ ràng vị trí can thiệp | Xác định can thiệp tại bước trích xuất thực thể và tóm tắt thông báo | Đảm bảo tính minh bạch, không dùng AI tràn lan cho toàn bộ chu trình |
| **Mức chọn** | Chưa chốt mức can thiệp | Chốt mức Workflow | Loại trừ hoàn toàn mức Agent để tránh rủi ro tự ý hành động và chi phí không cần thiết |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | **Tính đầy đủ (No omission)** | Trích xuất đủ 100% các thông báo có chứa hạn nộp hoặc đổi lịch được đăng bởi Mentor/Admin. | Bỏ sót bất kỳ thông báo chính thức nào khiến học viên không nhận được tin. |
| 2 | **Độ chính xác ngày giờ (Temporal Accuracy)** | Thời gian hạn chót và ngày tháng được quy đổi chính xác theo múi giờ GMT+7 đúng như tin nhắn gốc. | Trích xuất sai ngày, sai giờ, hoặc hiểu nhầm các mốc thời gian tương đối (*"mai"*, *"thứ 5 tuần sau"*). |
| 3 | **Bảo toàn link gốc (Traceability)** | Mỗi dòng tóm tắt đều có clickable link trỏ chính xác về message ID của tin nhắn Discord gốc. | Thiếu link hoặc link dẫn sai tin nhắn, khiến học viên không thể tự kiểm chứng lại. |
| 4 | **Tính súc tích (Conciseness)** | Bản tóm tắt không quá 2 câu, nêu bật đúng: Môn học — Việc cần làm — Hạn chót. | Diễn đạt rườm rà, lặp lại toàn văn tin nhắn cũ hoặc đưa thêm bình luận không cần thiết của AI. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **Trung bình** | Hai phỏng vấn ngoài nhóm ghi nhận các lần tìm mất vài phút và trường hợp không nhận ra cập nhật; nhưng thời gian đều là ước lượng, mẫu nhỏ, đồng thời Search/ghim/kênh thông báo giúp tìm nhanh trong một số tình huống. Chưa thể kết luận về đa số học viên. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **Thấp** | Đầu ra là một danh sách tin tóm tắt kèm link gốc cực kỳ trực quan, gửi thẳng trong Discord — môi trường học viên đã quen dùng mỗi ngày; thao tác bấm link đối chiếu rất đơn giản. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Thấp** | Kỹ thuật làm Discord bot lắng nghe tin nhắn và gọi LLM API (Gemini/OpenAI) để trích xuất thực thể theo JSON Schema là hoàn toàn nằm trong tầm tay của nhóm sinh viên CNTT; chi phí API rất nhỏ (vài cent/tháng). |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **Trung bình** | Cần xin phép Admin server Discord lớp để thêm bot hoặc webhook đọc kênh; nếu server cấm bot bên thứ ba vì bảo mật thì giải pháp không thể triển khai được. |

### 8.2. Kết luận

**Quyết định:** **Not Yet** (Chưa vội xây dựng giải pháp AI ngay).

**Lý do:**
1. **Bằng chứng bên ngoài còn sơ bộ:** Nhóm đã phỏng vấn 2 học viên ngoài nhóm. Cả hai kể được tình huống cụ thể, nhưng thời gian là ước lượng và hai trường hợp chưa đủ xác nhận baseline 15 phút/ngày hoặc mức độ phổ biến trong lớp.
2. **Chưa kiểm chứng hết các giải pháp sẵn có (No AI / Rule):** Kết luận research mục 3.3 chỉ ra Discord đã có Pinned Messages, Announcement Channels và Search. Nếu lớp chỉ cần chấn chỉnh quy ước đăng bài và dọn dẹp tin ghim định kỳ mà giải quyết được 80% vấn đề, thì việc xây dựng thêm hệ thống AI là lãng phí và phức tạp hóa bài toán.

**Nếu Not Yet — cần kiểm chứng gì trước:**
1. **Mở rộng kiểm chứng với 1–3 học viên ngoài nhóm nữa** hoặc làm micro-survey 5–10 người. Hai phỏng vấn hiện tại là tín hiệu ban đầu, chưa đủ kết luận cho cả lớp; tập trung kiểm tra giả định 1, 2, 3 trong Assumption Map.
2. **Thử nghiệm giải pháp No AI trong 3–5 ngày:** Đề xuất ban cán sự lớp chỉ định kênh thông báo riêng và thực hiện quy tắc ghim tin rõ ràng; bấm giờ đo xem thời gian tìm kiếm của học viên có giảm về dưới 5 phút không.
3. **Xin phép Admin:** Trao đổi với giảng viên/quản trị viên server về khả năng tích hợp webhook hoặc bot đọc tin.

**Nếu sau đó kiểm chứng xác nhận vẫn nghẽn — pilot nhỏ nhất (Go với Workflow hẹp):**
- Xây dựng một script Python nhỏ chạy cục bộ (hoặc webhook n8n đơn giản), lắng nghe duy nhất tin nhắn từ Mentor trong kênh `#thao-luan-lab`.
- Dùng mô hình ngôn ngữ nhẹ để trích xuất và đẩy tóm tắt về một kênh riêng `#daily-digest` cho 5 học viên trong nhóm dùng thử trong 1 tuần.

**Ngưỡng dừng (Stop threshold):**
- Nếu sau 3 ngày thử nghiệm quy ước kênh (No AI) mà thời gian tìm thông báo của học viên giảm xuống **dưới 5 phút/ngày** và **không có ca nào bị sót tin**, nhóm sẽ **DỪNG LẠI Ở GIẢI PHÁP QUY ƯỚC (NO AI)** và không code thêm bot/AI.
- Nếu triển khai bot Workflow AI thử nghiệm mà sau 1 tuần tỷ lệ học viên phản hồi bấm 👎 (trích xuất sai hoặc báo nhầm) **vượt quá 15%**, nhóm sẽ **DỪNG BOT NGAY LẬP TỨC** và quay về sử dụng phương án ghim tin thủ công.

---

## 9. Hạn chế và hướng tiếp theo

- **Hạn chế lớn nhất:** Baseline 15 phút/ngày và tần suất sót tin khoảng 1 lần/tháng vẫn là ước lượng ban đầu của thành viên trong nhóm; hai phỏng vấn ngoài nhóm cũng chỉ có thời gian tự ước lượng, chưa có dữ liệu bấm giờ từ tập người dùng lớn hơn.
- **Rủi ro phụ thuộc nền tảng:** Phụ thuộc vào chính sách cấp quyền bot của Discord API và quy định bảo mật riêng của từng server trường học/tổ chức.
- **Hướng tiếp theo:** 
  1. Mở rộng phỏng vấn thêm 1–3 học viên ngoài nhóm hoặc khảo sát 5–10 người để xem các pattern trong hai snapshot có lặp lại không.
  2. Đo đạc baseline thời gian thật bằng cách tự bấm giờ trong 3 ngày liên tiếp.
  3. Thử nghiệm áp dụng quy tắc định dạng thông báo (`[DEADLINE]`, `[ĐỔI LỊCH]`) trước khi bắt tay viết code.

---

## 10. Tài liệu tham khảo

1. **Discord Inc.**, *How to Use Search on Discord*, Discord Support, 2024. [Link](https://support.discord.com/hc/en-us/articles/115000468588-How-to-Use-Search-on-Discord)
2. **Discord Inc.**, *Pin Messages FAQ*, Discord Support, 2024. [Link](https://support.discord.com/hc/en-us/articles/221421867-Pin-Messages-FAQ)
3. **Discord Inc.**, *Announcement Channel FAQ*, Discord Support, 2024. [Link](https://support.discord.com/hc/en-us/articles/360032008192-Announcement-Channel-FAQ)
4. **David Bland & Alexander Osterwalder**, *Testing Business Ideas: A Field Guide for Rapid Experimentation*, Wiley, 2019 (Tham khảo framework Assumption Mapping).
5. **Rob Fitzpatrick**, *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you*, 2013 (Tham khảo kỹ thuật phỏng vấn kiểm chứng).
6. **Google PAIR (People + AI Research)**, *People + AI Guidebook*, Google, 2021. [Link](https://pair.withgoogle.com/guidebook/) (Tham khảo bộ câu hỏi Augment vs Automate, Error Handling và Human-in-the-Loop).
7. **Jeff Gothelf & Josh Seiden**, *Lean UX: Designing Great Products with Agile Teams*, O'Reilly Media, 2021 (Tham khảo cấu trúc Problem Statement).
