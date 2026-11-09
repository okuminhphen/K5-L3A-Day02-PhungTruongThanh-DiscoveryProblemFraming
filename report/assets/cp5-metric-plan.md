# CP5 — Metric và kế hoạch đo B1

> Tài liệu hỗ trợ phần việc của Mai Văn Thanh, do AI hỗ trợ soạn.
> Đây là thiết kế đo đề xuất, chưa có dữ liệu pilot. Bản v0 hiệu chỉnh ở
> [báo cáo nhóm, mục 5](../team/group_report.md) dùng cùng định nghĩa bên dưới.
> CP6 hiện kết luận Not Yet; tài liệu này không xác nhận hiệu quả giải pháp.

## 1. Nguồn và giới hạn dữ liệu hiện có

| Nguồn trong repo | Có thể dùng | Chưa thể kết luận |
|---|---|---|
| [Báo cáo Trường, CP1 và Card #1](../individual/2A202603663_LeQuangTruong.md) | Mô tả quy trình; ước lượng khoảng 15 phút/ngày gộp đọc lướt và nhận biết tin quan trọng (C3–C4) | Chưa có thời gian từng bước hoặc baseline toàn bộ 6 bước C1–C6 |
| Cùng Card #1 | Một lần từng bỏ sót tin đổi lịch, do người viết tự thuật | Không quy đổi thành một lần/tháng hoặc tần suất chung |
| Cùng báo cáo, thông tin khoảng 40 thành viên lớp | Bối cảnh người dùng chung kênh | Không phải 40 mẫu đã kiểm chứng hoặc 40 người cùng gặp pain |
| [Báo cáo nhóm, CP3–CP6](../team/group_report.md) | Candidate B1; target dưới 3 phút/ngày; quyết định Not Yet; đã có research và kế hoạch phỏng vấn | Chưa chứng minh target khả thi hoặc đã đạt; CP4 chưa có phỏng vấn ngoài nhóm |

Số 15 × 5 = 75 phút/tuần chỉ là phép quy đổi từ ước lượng tự khai,
không bổ sung bằng chứng đo. Không tự chia 15 phút thành thời gian từng bước.

## 2. Phạm vi và đơn vị quan sát

- Đơn vị: **một học viên-ngày**, dùng mã ẩn danh; không suy rộng ra cả lớp.
- Người tham gia xác định trước kênh được phép đọc, môn/lớp liên quan và
  khoảng tin cần xử lý: từ mốc đã đọc lần trước đến mốc đóng quan sát hôm nay.
- Chỉ xét thông báo hạn nộp và đổi lịch liên quan trực tiếp đến học viên.
- Nếu mở Discord nhiều lần, cộng thời gian các phiên trong cùng ngày;
  không đếm lặp sự kiện đã xử lý, nhưng vẫn kiểm tin cập nhật/hủy và sửa
  trạng thái theo cùng mã sự kiện khi có thay đổi ở phiên sau.
- Chốt múi giờ Asia/Ho_Chi_Minh (GMT+7), khung ngày và phạm vi kênh trước đo.
- Ngày không truy cập vẫn ghi rõ lý do và trạng thái thiếu quan sát;
  không tự ghi thời gian bằng 0 hoặc coi không có thông báo.

## 3. Định nghĩa chỉ số

| Chỉ số | Điểm bắt đầu và kết thúc / cách tính |
|---|---|
| Thời gian tìm và xác nhận | Từ thao tác đầu tiên mở nguồn/khởi tạo lượt tìm đến khi kiểm đủ phạm vi và xác nhận danh sách, chỉ loại riêng thời gian lưu ghi chú/lịch. Hiện tại cộng C1–C4 và phần kiểm/đọc lại tại C6; No AI cộng N1–N3 và N5; Workflow cộng W1–W4 và phần kiểm cuối phiên nếu có. Gồm mọi lượt chờ xử lý, kiểm cập nhật/hủy, sửa nháp và fallback. Ước lượng 15 phút của C3–C4 chưa bao hết phạm vi này nên phải đo lại baseline |
| Tổng thời gian xử lý | Từ lúc bắt đầu mở nguồn hoặc khởi tạo lượt xử lý cho công việc này đến khi kiểm đủ phạm vi và lưu/sửa xong ghi chú/lịch, hoặc xác nhận không có việc cần ghi; gồm mở kênh, tìm, xác nhận nguồn, nhập ghi chú, C6/N5 kiểm cuối phiên, chờ xử lý, lỗi, fallback và sửa sai phát hiện trong thời gian theo dõi |
| Thời gian từng bước | Bấm giờ riêng mở/tới mốc chưa đọc, đọc-tìm, nhận biết-kiểm nguồn, ghi lại, kiểm đủ phạm vi/quay lại, sửa lỗi/fallback; bước có lặp phải cộng đủ |
| Quy mô đầu vào | Số tin nhắn trong cửa sổ quan sát, số kênh, số sự kiện chuẩn; dùng để tránh so ngày ít tin với ngày nhiều tin mà không giải thích |
| Recall sự kiện | Số sự kiện tìm đúng / số sự kiện trong danh sách chuẩn |
| Precision sự kiện | Số sự kiện tìm đúng / số mục sự kiện học viên ghi nhận |

Thời gian đo bằng phút, có thể lưu giây gốc. Ghi riêng thời gian gián đoạn
không liên quan và lý do; không âm thầm loại khỏi tổng. Nếu không thể tách
được gián đoạn, đánh dấu mẫu để đọc kết quả có ngữ cảnh.
Nếu phải chờ người đăng trả lời, ghi riêng thời gian chờ theo đồng hồ và
thời gian thao tác của học viên; đánh dấu chưa hoàn tất khi chưa xác nhận,
không báo phiên đã xong chỉ vì hệ thống đã tạo được danh sách nháp.

## 4. Danh sách chuẩn và cách đối chiếu

1. Một người khác người đang được đo, có quyền xem hợp lệ, kiểm **toàn bộ**
   kênh và cửa sổ tin đã chốt; không chỉ kiểm danh sách người đo tìm thấy.
2. Người kiểm lập danh sách chuẩn độc lập: mã sự kiện, loại, môn/lớp,
   đối tượng áp dụng, hạn/lịch và múi giờ nếu có, trạng thái, link tin gốc.
3. Nhiều tin nhắc cùng một sự kiện chỉ tính một lần. Dùng mã sự kiện ổn định;
   tin cập nhật gắn cùng mã và lấy trạng thái mới nhất tại mốc đóng quan sát.
4. Tin hủy vẫn phải ghi trạng thái hủy. Ghi hạn/lịch cũ như còn hiệu lực là sai;
   không tính mỗi bản cập nhật là một sự kiện mới để tăng mẫu.
5. Một mục đúng phải khớp sự kiện, đối tượng áp dụng, nội dung hạn/lịch và
   trạng thái mới nhất, kèm nguồn. Chưa rõ thì ghi chưa xác nhận, không đoán.
6. Ghi TP = đúng, FP = mục sai/không liên quan/trùng dư, FN = sự kiện chuẩn
   chưa tìm đúng. Mục sai hạn/trạng thái tạo FP và để sự kiện chuẩn thành FN.
7. Recall = TP/(TP+FN); precision = TP/(TP+FP). Nếu mẫu có 0 sự kiện chuẩn,
   recall là **N/A**, vẫn kiểm FP. Nếu không ghi nhận mục nào, precision là
   **N/A**; khi danh sách chuẩn có sự kiện mà không tìm được, recall = 0.
8. Trường hợp nguồn mâu thuẫn chuyển người đăng/điều phối xác nhận; ghi thiếu
   ground truth nếu chưa giải quyết, không coi phỏng đoán là đáp án chuẩn.

Khi tổng hợp nhiều ngày, cộng TP/FP/FN rồi tính tỷ lệ; không thay N/A bằng 0
hoặc lấy trung bình tỷ lệ của các ngày có lượng sự kiện khác nhau.

Chỉ lưu mã ẩn danh và dữ liệu cần thiết trong repo. Không đăng nội dung kênh
riêng, họ tên, email hay ảnh chưa che thông tin; quyền xem không đồng nghĩa
được phép công khai. Link nguồn riêng chỉ chia trong nơi nhóm được phép dùng.

## 5. Lịch đo và so sánh đề xuất

- **Người tham gia đề xuất:** 3–5 học viên thực sự theo dõi kênh đã chọn;
  dùng mã ẩn danh. Đây là số dự kiến tuyển cho phép đo, không phải số đã hỏi
  ở CP4. Phỏng vấn 2–3 người ngoài nhóm là việc kiểm chứng riêng.
- **Baseline: 3 ngày học thực tế** cùng học viên dùng cách hiện tại; ghi tất cả
  phiên, thời gian từng bước và chất lượng kết quả, không thay đổi quy ước giữa kỳ.
- **Thử No AI trong 5 ngày học**: thống nhất tag hạn nộp/đổi lịch và ghim tin
  theo phương án trong Card #1; người quản lý kênh đồng ý trước khi thay đổi.
- Ghi ai gắn tag/ghim, thời gian người đó bỏ ra và việc sửa/gỡ tin hết hiệu lực;
  không chuyển công sức sang người đăng rồi báo là tổng công sức đã giảm.
- Dùng cùng phạm vi kênh, định nghĩa và người kiểm nguồn cho hai giai đoạn.
  Ngày khác lượng tin hoặc không có sự kiện vẫn giữ, ghi rõ khi so sánh.
- Không loại ngày chậm, lỗi hoặc phải quay lại đọc thủ công. Ghi cả tổng thực tế,
  số ngày thiếu quan sát, lý do thiếu và thời gian sửa lỗi phát hiện muộn.
- Báo trung vị cùng khoảng min–max theo học viên; kèm số ngày, số sự kiện,
  recall/precision và công sức người quản lý. Mẫu nhỏ chỉ dùng cho pilot.
- Chỉ xem xét Rule/Workflow sau khi có kết quả No AI và mô tả rõ phần còn nghẽn.
  Không suy từ một ngày nhanh rằng AI cần thiết hoặc giải pháp đã hiệu quả.

### 5.1. Bảng baseline → target → cách đo

Các target dưới đây là **đề xuất để nhóm rà soát**, không phải kết quả hay
cam kết đã được người dùng duyệt.

| Chỉ số | Baseline hiện có | Target đề xuất | Cách đo / điều kiện đọc kết quả |
|---|---|---|---|
| Thời gian tìm và xác nhận | Khoảng 15 phút/ngày tự ước lượng cho C3–C4; cần đo lại đầy đủ phạm vi | Trung vị dưới 3 phút/học viên-ngày trong 5 ngày học thử | Cộng các phiên mỗi ngày; báo trung vị và min–max riêng từng học viên, không chỉ chọn ngày nhanh |
| Tổng thời gian hoàn tất | Chưa đo; lấy trung vị 3 ngày baseline làm mốc so | Không tăng so với baseline đã đo; báo cả công sức người quản lý | Cộng mở kênh, tìm, kiểm, nhập lịch, kiểm cuối phiên và lỗi; không lấy 15 phút làm tổng |
| Bỏ sót sự kiện | Một lần đổi lịch tự thuật, chưa có tỷ lệ | FN = 0 trong tập thử có sự kiện chuẩn, tương ứng recall 100% trên tập đó | Người kiểm độc lập rà toàn bộ nguồn, kể cả khi học viên/bot không tìm thấy gì; không dùng số lượt phản ánh làm mẫu số |
| Đúng hạn/lịch và trạng thái sau khi người dùng xác nhận | Chưa đo | 0 sai hạn/lịch hoặc trạng thái mới nhất; 100% mục xác nhận có nguồn | Đối chiếu từng sự kiện, cả tin sửa/hủy; mục chưa xác nhận giữ nhãn chưa rõ, không tính là tìm đúng |
| Đầu ra nháp nếu sau này thử Workflow | Chưa có bot hoặc mẫu đầu ra đã đo | Ít nhất 95% mục nháp khớp đủ thông tin với nguồn, đồng thời FN = 0 trên danh sách chuẩn | Tỷ lệ khớp = số mục nháp đúng / toàn bộ mục nháp, tính cả trùng dư và báo nhầm; đây là eval bổ sung ở v1, chưa phải kết quả CP5 |

Nếu không có sự kiện chuẩn, recall là N/A và chưa kiểm được target bỏ sót.
Nếu sự kiện quá ít, ghi rõ số sự kiện và giới hạn mẫu; không suy “đạt trong
pilot” thành bảo đảm không bao giờ bỏ sót. Không tính phần trăm tiết kiệm
từ 15 phút ước lượng xuống 3 phút mục tiêu.

Mốc **dưới 5 phút/ngày** ở CP6 là ngưỡng đề xuất để dừng nâng mức khi No AI
đã đủ dùng, khác mục tiêu cao hơn dưới 3 phút/ngày. Chỉ đọc ngưỡng này sau
khi đo cùng phạm vi, có sự kiện chuẩn và không có FN; nhóm cần tự xác nhận
có chấp nhận mức 3–5 phút không. Tỷ lệ reaction 👎 chỉ là phản hồi phụ,
không phát hiện được thông báo mà hệ thống đã bỏ sót.

## 6. Nhật ký trống để thu dữ liệu thật

Không điền ví dụ bằng số giả. Một dòng là một học viên-ngày; chi tiết phiên
và từng bước có thể ghi ở ghi chú, sau đó cộng vào các cột thời gian.

| Ngày / mã học viên / phiên | Phương án | Mã bước C/N/W/F | Số lần lặp | Tổng giây thao tác | Giây chờ | Giây gián đoạn ngoài việc | Ghi chú |
|---|---|---|---|---|---|---|---|
| | | | | | | | |
| | | | | | | | |

| Ngày / mã học viên | Giai đoạn | Kênh / cửa sổ tin | Số tin | Phút tìm-xác nhận | Phút tổng | Phút người quản lý | Lỗi / fallback / gián đoạn |
|---|---|---|---|---|---|---|---|
| | | | | | | | |
| | | | | | | | |

| Ngày / mã học viên | Sự kiện chuẩn | Mục ghi nhận | TP | FP | FN | Recall | Precision | Thiếu quan sát / ghi chú kiểm nguồn |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |
| | | | | | | | | |

| Mã sự kiện | Loại / môn / đối tượng | Trạng thái mới nhất / mốc hiệu lực | Nguồn được phép lưu | Người kiểm / lúc kiểm | Sai khác và cách xử lý |
|---|---|---|---|---|---|
| | | | | | |

## 7. Bàn giao CP4 và câu hỏi CP6

Theo [CHECKPOINTS.md](../../CHECKPOINTS.md) và [RULES.md](../../RULES.md):

- [ ] Phụng phụ trách CP4 theo bảng phân công mới; Trường hỗ trợ phỏng vấn
  thật 2–3 người ngoài nhóm từng gặp vấn đề, hoặc survey
  5–10 người; hỏi lần gần nhất, từng bước, thời gian, cách đang xử lý.
- [ ] Ghi vai trò ẩn danh, khi nào, hỏi bằng cách nào, số người thực tế;
  ghi cả tín hiệu phản bác. AI không đóng vai người được phỏng vấn.
- [ ] Thu/xác nhận nguồn tự khai, tách ước lượng khỏi bấm giờ; hỏi vì sao
  tag/ghim hiện có chưa đủ, thay vì giả định chắc chắn cần thêm công cụ.
- [ ] Nhóm duyệt phạm vi, target, ngưỡng chất lượng, quyền đọc/ghim và người
  kiểm chuẩn; cập nhật CP4 bằng dữ liệu thu thật rồi hiệu chỉnh v0/v1.

Câu hỏi phản biện để nhóm tự trả lời tại CP6, chưa phải kết luận:

- No AI còn nghẽn bước nào sau pilot? Rule có đủ hay thực sự cần hiểu ngữ cảnh?
- Nếu xét Workflow, AI làm đúng một bước nào; vì sao Rule chưa đủ và vì sao
  không cần Agent tự quyết bước tiếp theo?
- Eval có bắt được bỏ sót, sai hạn, tin cập nhật/hủy và thiếu nguồn không?
- Ai kiểm trước khi ghi lịch/chia sẻ? Khi không chắc, AI phải dừng ở đâu?
- Quyền đọc kênh, quyền lưu dữ liệu, chi phí và công sức vận hành do ai chịu?
- Nếu lỗi hoặc chất lượng không đạt, ai phát hiện và quay lại quy trình nào?
