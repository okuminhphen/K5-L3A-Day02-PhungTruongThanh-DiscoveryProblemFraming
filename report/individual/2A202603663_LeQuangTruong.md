# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: LÊ QUANG TRƯỜNG
- MSSV:2A202603663
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:PhungTruongThanh
- Link repo nhóm:https://github.com/okuminhphen/K5-L3A-Day02-PhungTruongThanh-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                                                                    | Ai chịu ảnh hưởng?                           | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                                                                     |
| --: | --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Cần đọc, tổng hợp nhiều thông tin | Khi kênh Discord của lớp có hơn 100 tin chưa đọc sau một ngày bận, tôi muốn thấy ngay tin nào có hạn nộp hoặc đổi lịch, để không bỏ sót việc cần làm.                            | Học viên lớp L3A (~40 người dùng chung kênh) | Lướt lại ~15 phút/ngày, 5 ngày/tuần = ~75 phút/tuần. Từng bỏ sót 1 tin đổi lịch học. Bằng chứng: ảnh chụp số tin chưa đọc, link tin đổi lịch. |
|   2 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận đề lab trên GitHub gồm 4–5 file (README, CHECKPOINTS, RUBRIC, SUBMISSION), tôi muốn biết ngay mình phải nộp gì, lúc nào và ở đâu, để không phải mở đi mở lại từng file. | Học viên mới làm lab, người chưa quen GitHub | Đọc hết ~20 phút. Trong 1 buổi lab mở lại SUBMISSION.md ≥3 lần để kiểm tra deadline. Bằng chứng: lịch sử tab đã mở, ghi chú tay.              |
|   3 | Lặp lại                           | Khi mỗi buổi lab có deadline khác nhau (sáng 23h59 cùng ngày, chiều/tối 11h59 hôm sau), tôi muốn deadline tự có sẵn trong lịch cá nhân, để không phải chép tay và tính lại giờ.  | Học viên học nhiều buổi mỗi tuần             | Chép tay ~5 phút/buổi, ~3 buổi/tuần = ~15 phút/tuần. Từng nhập nhầm múi giờ 1 lần. Bằng chứng: sự kiện lịch bị sửa lại, ảnh chụp.             |
|   4 | Tốn thời gian                     | Khi 3–4 bạn cùng sửa một file báo cáo rồi `git push`, tôi muốn push một lần là xong, để không bị conflict và phải ngồi gỡ.                                                       | Nhóm 3–4 người làm chung một repo            | Conflict ~2 lần/buổi lab, mỗi lần gỡ ~10 phút = ~20 phút/buổi (trên 240 phút). Bằng chứng: thông báo lỗi Git, commit "merge" trong lịch sử.   |
|   5 | Pain từ người khác                | Khi bạn cùng nhóm chưa biết dùng Git và hỏi lại cách clone, commit, push, tôi muốn bạn ấy tự làm được sau vài phút, để cả nhóm khỏi đứng chờ.                                    | Bạn cùng nhóm chưa quen Git (2/4 người)      | Mỗi lần chỉ ~10 phút, mỗi bạn hỏi lại ~2 lần. Bằng chứng: tin nhắn nhóm kiểu "push sao vậy", ảnh chụp lỗi bạn gửi.                            |
|   6 | Tốn thời gian                     | Khi sắp thi hoặc sắp có bài kiểm tra và tôi có ghi chú rải rác ở nhiều nơi (vở, Discord, Google Docs), tôi muốn gom lại thành một bản ôn, để không mất cả buổi tối đi tìm.       | Học viên ôn bài trước bài kiểm tra           | Gom ghi chú ~60–90 phút mỗi lần, ~1 lần/tháng. Bằng chứng: danh sách ghi chú ở 3 nơi, ảnh chụp.                                               |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- ***

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                                                               | Vì sao chọn                                                                                        | Điều còn chưa chắc                                                                   |
| ---: | ------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
|    1 | Hơn 100 tin chưa đọc trên Discord lớp, khó thấy tin có hạn nộp hoặc đổi lịch (CP1 #1) | Actor rõ (~40 học viên), mất ~75 phút/tuần, từng bỏ sót 1 tin đổi lịch, có ảnh chụp làm bằng chứng | Chưa rõ lọc bằng từ khóa có đủ không, hay cần AI để hiểu ngữ cảnh                    |
|    2 | Phải chép tay deadline từng buổi lab vào lịch cá nhân (CP1 #3)                        | Quy trình ngắn, vẽ được, ~15 phút/tuần, từng nhập nhầm múi giờ                                     | Chưa biết deadline có nguồn cố định để lấy tự động không, hay mỗi buổi viết một kiểu |
|    3 | Conflict khi cả nhóm cùng sửa một file rồi `git push` (CP1 #4)                        | Bottleneck rất cụ thể (~20 phút/buổi lab), có thông báo lỗi và lịch sử commit làm bằng chứng       | Chưa chắc nguyên nhân là thiếu kỹ năng Git hay do cách chia việc trong nhóm          |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                                       |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi kênh Discord của lớp có hơn 100 tin chưa đọc sau một ngày bận, tôi muốn thấy ngay tin nào có hạn nộp hoặc đổi lịch, để không bỏ sót việc cần làm.          |
| Actor                                     | Học viên lớp L3A (~40 người dùng chung kênh)                                                                                                                   |
| Thời điểm / bối cảnh                      | Cuối ngày hoặc sáng hôm sau, khi mở Discord sau lúc bận học, làm lab hoặc đi làm thêm                                                                          |
| Quy trình hiện tại (3–7 bước)             | Mở Discord → cuộn lên đầu chỗ chưa đọc → đọc lướt từng tin → tự nhận ra tin nào liên quan hạn nộp/đổi lịch → ghi lại vào lịch hoặc ghi chú → quay lại đọc tiếp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước "đọc lướt từng tin" và "tự nhận ra tin nào quan trọng": ~15 phút/ngày                                                                                     |
| Impact (nếu không giải thì sao)           | Mất ~75 phút/tuần. Có thể bỏ sót thông báo đổi lịch hoặc hạn nộp (đã xảy ra 1 lần)                                                                             |
| Success metric (baseline → target)        | Thời gian xử lý tin chưa đọc: 15 phút/ngày → dưới 3 phút/ngày. Số thông báo quan trọng bị bỏ sót: 1 lần/tháng → 0                                              |
| Phương án không dùng AI                   | Ghim tin quan trọng, quy ước tag `[HẠN NỘP]` / `[ĐỔI LỊCH]` trong tiêu đề tin nhắn, mở bộ lọc thông báo chỉ khi được nhắc tên                                  |
| Giả thuyết về AI (nếu có)                 | AI đọc kênh và tóm tắt mỗi ngày: liệt kê tin có hạn nộp/đổi lịch kèm link tin gốc. Con người vẫn kiểm tra lại link gốc trước khi tin                           |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                       |

Quy trình nháp hiện tại:

```text
[Mở Discord] -> [Cuộn tới chỗ chưa đọc] -> [Đọc lướt từng tin] -> [Tự nhận ra tin quan trọng] -> [Ghi vào lịch/ghi chú] -> [Đọc tiếp]
NGHẼN: ~15 phút/ngày, dễ sót
```

### Problem Card #2

| Trường                                    | Nội dung                                                                                                                                                                        |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi mỗi buổi lab có deadline khác nhau (sáng 23h59 cùng ngày, chiều/tối 11h59 hôm sau), tôi muốn deadline tự có sẵn trong lịch cá nhân, để không phải chép tay và tính lại giờ. |
| Actor                                     | Học viên học nhiều buổi mỗi tuần                                                                                                                                                |
| Thời điểm / bối cảnh                      | Đầu mỗi buổi lab hoặc khi nhận lịch học mới của tuần                                                                                                                            |
| Quy trình hiện tại (3–7 bước)             | Đọc lịch/đề → xác định buổi sáng hay chiều/tối → tính giờ nộp theo múi giờ GMT+7 → mở Google Calendar → tạo sự kiện thủ công → đặt nhắc                                         |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước "tính giờ nộp" và "tạo sự kiện thủ công": ~5 phút/buổi, ~3 buổi/tuần                                                                                                       |
| Impact (nếu không giải thì sao)           | Mất ~15 phút/tuần. Nhập sai giờ hoặc múi giờ thì nộp trễ (đã nhập nhầm 1 lần)                                                                                                   |
| Success metric (baseline → target)        | Thời gian thiết lập deadline: 5 phút/buổi → dưới 30 giây/buổi. Số lần nhập sai giờ: 1 lần/tháng → 0                                                                             |
| Phương án không dùng AI                   | Giáo vụ gửi một file lịch `.ics` chung có sẵn deadline. Học viên chỉ cần bấm "Thêm vào lịch"                                                                                    |
| Giả thuyết về AI (nếu có)                 | Không cần AI. Đây là bài toán quy tắc: buổi sáng = 23h59 cùng ngày, buổi chiều/tối = 11h59 hôm sau                                                                              |
| Cảm nhận nhanh                            | Rule                                                                                                                                                                            |

Quy trình nháp hiện tại:

```text
[Đọc lịch/đề] -> [Xác định sáng hay chiều/tối] -> [Tính giờ nộp GMT+7] -> [Mở Calendar] -> [Tạo sự kiện thủ công] -> [Đặt nhắc]
                                                  ^^^^^^^^^^^^^^^^^^^^^^   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
                                                  NGHẼN: ~5 phút/buổi, dễ nhầm giờ
```

### Problem Card #3

| Trường                                    | Nội dung                                                                                                                                                                    |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi 3–4 bạn cùng sửa một file báo cáo rồi `git push`, tôi muốn push một lần là xong, để không bị conflict và phải ngồi gỡ.                                                  |
| Actor                                     | Nhóm 3–4 người làm chung một repo                                                                                                                                           |
| Thời điểm / bối cảnh                      | Trong buổi lab 4 tiếng, khi cả nhóm cùng viết `group_report.md` và `TEAM.md`                                                                                                |
| Quy trình hiện tại (3–7 bước)             | Mỗi người sửa file trên máy → `git add`/`commit` → `git push` bị từ chối vì người khác đã push → `git pull` → mở file, thấy dấu conflict → ngồi gỡ tay → commit lại và push |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước "thấy dấu conflict và gỡ tay": ~10 phút/lần, ~2 lần/buổi                                                                                                               |
| Impact (nếu không giải thì sao)           | Mất ~20 phút/buổi (khoảng 8% của 240 phút). Có nguy cơ mất nội dung nếu gỡ sai                                                                                              |
| Success metric (baseline → target)        | Số lần conflict mỗi buổi: 2 → 0. Thời gian gỡ lỗi: 20 phút/buổi → 0                                                                                                         |
| Phương án không dùng AI                   | Quy ước: mỗi người chỉ sửa mục của mình, luôn `git pull` trước khi sửa, push ngay sau mỗi lần sửa nhỏ. Hoặc chia mỗi người một file riêng rồi gộp                           |
| Giả thuyết về AI (nếu có)                 | Không cần AI. Nguyên nhân là cách phối hợp, nên giải bằng quy ước nhóm                                                                                                      |
| Cảm nhận nhanh                            | No AI                                                                                                                                                                       |

Quy trình nháp hiện tại:

```text
[Sửa file] -> [add/commit] -> [push bị từ chối] -> [pull] -> [Thấy dấu conflict] -> [Gỡ tay] -> [Commit lại và push]
NGHẼN: ~10 phút/lần, ~2 lần/buổi
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Ảnh hưởng nhiều người nhất (~40 học viên), mất nhiều thời gian nhất (~75 phút/tuần), đã gây hậu quả thật (bỏ sót 1 thông báo đổi lịch), và là card duy nhất có chỗ hợp lý cho AI.
- Câu hỏi muốn nhóm phản biện: Nếu chỉ lọc theo từ khóa như "deadline", "nộp", "đổi lịch" thì đã đủ chưa? AI chỉ đáng dùng khi từ khóa bỏ sót hoặc nhận nhầm nhiều. Điều đó có đúng không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                  | Đồng ý?         | Đã sửa gì                                                                                     |
| ----------------------------------------------------------------------------------- | --------------- | --------------------------------------------------------------------------------------------- |
| Con số 15 phút/ngày chỉ là ước lượng, chưa đo thật                                  | Đồng ý          | Sẽ tự bấm giờ 3 ngày liên tiếp rồi ghi lại số thật                                            |
| Chưa chứng minh phương án không AI (quy ước tag, ghim tin) đã thử và không hiệu quả | Đồng ý          | Thêm bước thử quy ước tag 1 tuần rồi đo lại thời gian                                         |
| AI tóm tắt có thể bỏ sót hoặc hiểu sai tin quan trọng, nguy hiểm hơn việc đọc tay   | Đồng ý một phần | Thêm điều kiện: mỗi mục tóm tắt phải kèm link tin gốc và con người kiểm tra lại trước khi tin |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?                                                                                                                                                                                                                                                                                                                                                                                             | Kết quả / ảnh hưởng tới bài nhóm                                                                                                |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Pitch Problem Card         | Em pitch 3 card: B1 (thông báo quan trọng bị trôi trong Discord), B2 (chép deadline vào lịch cá nhân) và B3 (conflict khi cả nhóm cùng sửa báo cáo). Em nói B1 trước vì card này ảnh hưởng nhiều người nhất và mất nhiều thời gian nhất.                                                                                                                                                                   | Nhóm chọn B1 làm vấn đề chung, được 31/35 điểm (mục 2.4 báo cáo nhóm).                                                          |
| Phản biện bài của bạn khác | Câu hỏi em đã đặt: hỏi Phụng ở A1 là nếu bắt điền biểu mẫu nhiều trường thì người dùng có lười rồi vẫn nhắn tin tự do không; hỏi Phụng ở A3 là làm trang FAQ/Wiki thì có giải quyết được không nếu người dùng ngại đọc bài dài; hỏi Thanh ở C1 là làm sao công cụ biết phần nào chắc chắn thi; hỏi Thanh ở C3 là giải pháp số có khả thi không khi còn phụ thuộc vào khả năng tiếp thu của người lớn tuổi. | Các câu hỏi này được ghi trong bảng pitch (mục 2.1).                                                                            |
| Nhận phản biện             | Câu hỏi em nhận được: Phụng hỏi vì sao B1 vẫn bị trôi dù Discord đã có ghim tin và kênh #announcement; Thanh hỏi một tuần có bao nhiêu deadline để việc chép tay thành vấn đề (B2); Phụng hỏi nếu chia file Markdown theo mục thì còn conflict không (B3). Em đã sửa gì: em nhận rằng con số 15 phút/ngày chỉ là em ước lượng, chưa đo, nên nhóm đưa việc kiểm chứng vào CP4.                              | Nhờ câu hỏi về ghim tin và #announcement, nhóm quyết định thử No AI/Rule trước chứ không đi thẳng sang AI (mục 5, phản biện 2). |
| Gom cluster / cây OST      | Em hỗ trợ CP3, người làm chính là Phụng. B1 của em nằm trong cluster A cùng với A3 và C1.                                                                                                                                                                                                                                                                                                                  | Gốc cây OST xoay quanh B1: giảm thời gian tìm và nhận biết thông báo quan trọng trên Discord.                                   |
| Chọn candidate problem     | B1 của em được chọn. Điểm "Pain có bằng chứng" chỉ được 3/5 vì baseline 15 phút/ngày là em ước lượng, chưa đo thật.                                                                                                                                                                                                                                                                                        | Nhóm ghi nhận hạn chế này và đưa thành giả định cần kiểm chứng ở CP4.                                                           |
| Kiểm chứng / research      | Đến lúc em viết thì nhóm chưa phỏng vấn bạn nào ngoài nhóm, em cũng chưa phỏng vấn ai. Phần em có mới là mô tả trải nghiệm của mình ở CP1 và CP2.                                                                                                                                                                                                                                                          | Giả định 1 đến 3 (Value) vẫn chưa được kiểm chứng, nên nhóm chọn Not Yet.                                                       |
| Quy trình nhóm             | Em không làm phần này (người chính là Thanh). Quy trình 5 bước ở mục 4.1 của báo cáo nhóm lấy ý từ Problem Card #1 của em.                                                                                                                                                                                                                                                                                 | Điểm nghẽn của nhóm (đọc lướt tin chat, khoảng 10 phút/ngày) trùng với điểm nghẽn trong card của em.                            |
| Problem Statement          | Em không viết phần này (người chính là Thanh). Con số 15 phút/ngày và việc sót thông báo khoảng 1 lần/tháng lấy từ Problem Card #1 của em.                                                                                                                                                                                                                                                                 | Các con số này bị phản biện là ước lượng của một người, nhóm đồng ý đo lại ở bước pilot.                                        |
| Mức can thiệp AI           | TEAM.md giao em làm chính mục này, nhưng trong báo cáo nhóm phần này do bạn khác viết và commit, em chưa trực tiếp viết.                                                                                                                                                                                                                                                                                   | Nhóm so sánh 4 mức, loại Agent và ưu tiên thử No AI/Rule trước khi dùng Workflow.                                               |
| Quyết định                 | TEAM.md giao em làm chính mục này, nhưng phần quyết định trong báo cáo nhóm do bạn khác viết và commit, em chưa trực tiếp viết.                                                                                                                                                                                                                                                                            | Nhóm kết luận Not Yet, kèm các việc cần kiểm chứng và ngưỡng dừng.                                                              |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                                        | AI hữu ích ở đâu?                                     | AI sai hoặc hời hợt ở đâu?                                         | Tôi sửa gì bằng nhận định của mình?                                 |
| ------------------------------ | ------------------------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------- |
| CP1 Scan                       | Em nhờ AI làm bảng mẫu 6 vấn đề và cách viết Job Story.       | Em biết cách viết Job Story và cần ghi bằng chứng gì. | Các con số trong bảng là số ví dụ của AI, em chưa đo.              | Em ghi rõ các số này là ước lượng, sau sẽ tự bấm giờ để có số thật. |
| CP2 Problem Card               | Em nhờ AI chọn top 3, điền 3 card và viết bảng phản biện.     | Có khung card đủ các trường cần điền.                 | Bảng "AI phản biện" là AI tự viết, chưa phải người thật phản biện. | Em chọn B1 để pitch, và nhận phản biện thật từ Phụng, Thanh ở CP3.  |
| CP4 Research                   | Em không dùng AI ở phần này.                                  | —                                                     | —                                                                  | —                                                                   |
| CP5 Quy trình                  | Em không dùng AI ở phần này.                                  | —                                                     | —                                                                  | —                                                                   |
| CP5–6 Problem Statement        | Copilot trong VS Code điền thử mục CP6 vào `group_report.md`. | Gợi ý cách chia các mục.                              | Nội dung trùng phần nhóm đã viết, dễ ghi đè bài của bạn khác.      | Em hoàn tác, không đưa vào báo cáo nhóm.                            |
| CP6 Mức can thiệp / quyết định | Em hỏi AI để hiểu các bước CP6 và lý do chọn Not Yet.         | Em hiểu rõ hơn 4 mức và 4 rủi ro.                     | AI hay nghiêng về chọn Workflow sớm dù nhóm chưa phỏng vấn ai.     | Em đồng ý giữ Not Yet, phải kiểm chứng ngoài nhóm trước.            |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Sau khi nghe top 3 problems của các bạn khác em mới thấy mình bị mắc kẹt ở chỗ nhận thức vấn đề vì khi nhận đc vấn đềmà không bóc tách đượcbản chất của vấn đ, nó mắc kẹt ở đâu ở chỗ nào.Qua đó em rút ra được kinh nghiệm là một bài toán chuẩn chỉ cần phải có một quy trình cụ thể và đo lường được bằng số liệu thay vì chỉ giải quyết vấn đề trc mắt.
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Nhóm em có dính bẫy này ngay từ đầu như vừa nhìn thấy tin nhắn của Discord hay trôi đi là bọn em nghĩ luôn đến làm một AI tóm tắt nội dung và tạo thông báo bắt buộc. May sao bọn em đọc lại kĩ thấy sai bản chất lên nhóm đã lên lại ý tưởng và phân tích lại xem nó sai ở đâu.
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có, nhóm em đã "quay xe" chỗ dữ liệu baseline. lúc đầu em tưởng con số 15 phút mỗi ngày là chuẩn vì bản thân bị vậy.Nhưng đến khi nghe mọi người phản biện rằng Làm gì mà mất nhiều thế, ai cx như bạn ak chính vì những câu nói ý mà em đã nhận ra sự chủ quan của mình.Thế là cả nhóm đồng ý hạ quyết định xuống "Not Yet", đưa giả định vào bảng để đi phỏng vấn lại từ đầu.
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Bất ngờ nhất là lúc research mấy tính năng có sẵn của Discord như Search hay Pin Message. Hóa ra công cụ người ta tích hợp sẵn từ rất lâu, dùng khéo léo một chút là giải quyết được phần lớn vấn đề rồi. Lúc đó em mới nhận ra là đôi khi cứ làm phức tạp hóa vấn đề bằng AI trong khi nguyên nhân gốc rễ chỉ là do thói quen và sự thiếu kỷ luật trong cách giao tiếp của con người.
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất khi viết Problem Statement là làm sao em tìm đúng vào trọng tâm gây mất thời gian nhất vì em hay bị lan man là nó trôi đi thành kể khổ ngay. Ngoài ra, việc chọn đúng metric để đo lường và vạch ra ranh giới cho AI cũng vắt óc suy nghĩ.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại từ đầu, em sẽ ép nhóm đi phỏng vấn và bấm giờ thực tế ngay từ những ngày đầu chứ không ngồi nhà tự tưởng tượng ra con số nữa. Về phần phản biện, em sẽ cứng rắn hơn với mấy ý tưởng thích dùng công nghệ phức tạp, bắt nhóm phải chứng minh cho bằng được là các công cụ thủ công hiện tại đã không còn phù hợp nữa thì mới được phép nghĩ đến chuyện dùng AI.
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.
Bài toán của nhóm xuất phát từ thực tế học viên hay bị trôi thông báo quan trọng trên Discord. Nhóm bóc tách quy trình hiện tại thành 5 bước thủ công để tìm ra điểm nghẽn nằm ở khâu đọc lót tin nhắn, từ đó đặt mục tiêu kéo thời gian tìm kiếm từ 15 phút xuống dưới 3 phút mỗi ngày. để an toàn nhóm luôn phải vạch ra rõ ranh giới cho AI ko được làm việc gì, không được tự ý hành động và luôn phải đánh kèm link minh họa để kiểm chứng.Cuối cùng, vì thấy còn thiếu dữ liệu thực tế và chưa tận dụng hết các tính năng có sẵn, nhóm chốt quyết định "Not Yet" để đi kiểm chứng kỹ càng và thử nghiệm quy ước No AI trước khi tốn sức để code code.

---

## 7. Tài liệu tham khảo

1. VinUni-AI20k, _K5-L3-Day02-DiscoveryProblemFraming_: README.md, CHECKPOINTS.md, docs/01-worksheet.md, docs/02-deliverable-example.md. https://github.com/VinUni-AI20k/K5-L3-Day02-DiscoveryProblemFraming
2. Nhóm PhungTruongThanh, _Báo cáo nhóm — Day 02 Discovery & Problem Framing_ (`report/team/group_report.md`) và `TEAM.md`. https://github.com/okuminhphen/K5-L3A-Day02-PhungTruongThanh-DiscoveryProblemFraming
3. Discord Inc., _How to Use Search on Discord_, Discord Support. https://support.discord.com/hc/en-us/articles/115000468588-How-to-Use-Search-on-Discord
4. Discord Inc., _Pin Messages FAQ_, Discord Support. https://support.discord.com/hc/en-us/articles/221421867-Pin-Messages-FAQ
5. Discord Inc., _Announcement Channel FAQ_, Discord Support. https://support.discord.com/hc/en-us/articles/360032008192-Announcement-Channel-FAQ
6. Google PAIR, _People + AI Guidebook_ (phần Augment vs Automate và xử lý lỗi). https://pair.withgoogle.com/guidebook/

-
