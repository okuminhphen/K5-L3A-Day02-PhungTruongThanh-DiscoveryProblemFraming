# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: PhungTruongThanh
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khó tìm và nhận biết các thông báo quan trọng (hạn nộp bài, đổi lịch) bị trôi trong kênh Discord học tập (Candidate B1).
- Quyết định cuối: Go / Not Yet / No-Go

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
├── Opportunity 1: Thông báo bài tập và đổi lịch bị trôi lẫn trong hàng trăm tin nhắn thảo luận hằng ngày trên server Discord (B1)
├── Opportunity 2: Người học gặp khó khi phải đọc lướt và lọc thông tin trọng tâm từ nhiều tài liệu/thông báo khác nhau (C1)
└── Opportunity 3: Hướng dẫn kỹ thuật và thông báo cũ khó tìm lại nhanh khi cần tra cứu (A3)
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
- Nhóm thống nhất: B1 có bằng chứng mới ở mức mô tả trong báo cáo (thời gian 15 phút/ngày chưa đo thực tế, chưa thể coi cả lớp đều gặp vấn đề). Nhóm quyết định đưa giả định này vào CP4 để phỏng vấn/khảo sát các bạn học viên khác trong lớp nhằm xác thực mức độ đau thật sự trước khi bước vào thiết kế giải pháp.

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
