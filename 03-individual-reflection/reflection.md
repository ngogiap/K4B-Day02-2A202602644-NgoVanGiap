# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Ngô Văn Giáp
- Mã học viên: 2A202602644
- Nhóm: B2-6h50p
- Candidate problem nhóm chọn: Gom nhóm chủ đề đánh giá và viết báo cáo điểm nổi bật tuần (Candidate #1 của Trần Anh Đăng)

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 8 vấn đề cá nhân từ bối cảnh sinh viên mới tốt nghiệp ở nhà (thức khuya chơi game, lướt video ngắn, áp lực bị hỏi tìm việc) | Đưa vào danh sách 3 candidate problems đa dạng lăng kính cho nhóm |
| Pitch Problem Card | Pitch bài toán "Người thân hỏi tìm việc đến đâu mà không có gì để báo" (Card #3) | Giúp nhóm phân tích rõ mối liên hệ giữa thói quen sinh hoạt và hiệu suất tạo ra output |
| Challenge bài của bạn khác | Phản biện bài toán "Tự học tiếng Anh" của bạn Đô về tính đo lường và chuẩn hóa tiêu chuẩn chấm điểm | Giúp nhóm nhận ra rủi ro khó định lượng và chuyển hướng chọn bài toán có baseline rõ ràng hơn |
| Gom trùng / cluster | Cùng nhóm gom 15 ý tưởng của 5 thành viên thành 4 cụm chủ đề chính (Học tập, Vận hành/Báo cáo, Tự động hóa lặp lại, Thói quen cá nhân) | Đưa các bài toán thói quen cá nhân (thức khuya, lướt clip) vào cụm D và loại bớt do không hợp dùng AI |
| Chọn candidate problem | Thảo luận và chấm điểm score theo 7 tiêu chí để đồng thuận chọn bài báo cáo tuần của anh Đăng | Thống nhất được candidate problem duy nhất có baseline 90 phút/tuần đo lường được |
| Validation / research | Cùng nhóm khảo sát 6 bạn học về nỗi đau làm báo cáo tuần và tìm hiểu hạn chế của Pivot Table Excel | Xác nhận pain thật nằm ở bước viết bài narrative chứ không phải ở bước đếm số thô |
| Workflow nhóm | Đóng góp ý kiến ranh giới Human Boundary ở bước Review bài draft trước khi gửi Slack | Đảm bảo AI không tự động post báo cáo khi chưa có sự kiểm duyệt của Analyst |
| Problem Statement | Cùng nhóm xây dựng ranh giới Boundary (Làm / Không làm) cho Problem Statement v1 | Làm rõ rủi ro Hallucination của AI và cách khống chế bằng dữ liệu thô |
| Rule / Workflow / Agent | Thảo luận lý do chọn mức Workflow thay vì Agent tự động hoàn toàn | Giúp nhóm chốt mô hình an toàn 5 bước, giữ Analyst làm người kiểm tra cuối |
| Decision | Đồng thuận quyết định Go với dự án Pilot 2 tuần | Chốt được 3 chỉ số cần đo và phương án rollback nếu AI trích sai số liệu |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc phản biện mạnh mẽ ranh giới Human Boundary ở bước 4 trong Future Workflow: bắt buộc Analyst phải đối chiếu số thô với Pivot Table trước khi bấm gửi Slack để tránh AI bịa số liệu.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm problem từ bối cảnh sinh viên ở quê | Gợi ý góc nhìn lăng kính tốn thời gian và pain người khác về lọc JD | Gợi ý ý tưởng "Quản lý chi tiêu cá nhân" rất hời hợt vì không có thu nhập | Bỏ hẳn ý quản lý chi tiêu, giữ lại bài toán tìm JD tuyển dụng thủ công |
| Problem Card | Đóng vai PM phản biện 3 Problem Cards cá nhân | Chỉ ra Card #3 (báo cáo tìm việc) thực chất là symptom của Card #1 (thức khuya chơi game) | AI gợi ý giải pháp Agent phức tạp quá đà cho việc nhắc nhở thức khuya | Giữ nguyên lựa chọn mức No-AI / Rule cứng cho thói quen cá nhân |
| Workflow | Gợi ý khung chuyển đổi Before/After ASCII | Giúp định dạng sơ đồ dòng chảy các bước trực quan | AI tự động bỏ qua bước kiểm tra lại dữ liệu thủ công | Bổ sung thêm bước Human Boundary và phương án Fallback khi AI sai |
| Research | Tìm kiếm công cụ giải bài toán báo cáo tuần | Liệt kê nhanh các tính năng của Jira Reports và Gemini in Docs | AI tự bịa ra một số con số thống kê tiết kiệm thời gian không có nguồn | Không dùng số liệu AI đưa ra, tự làm survey 6 bạn học để lấy quote thật |
| Problem Statement | Phản biện tính cụ thể của Problem Statement v0 | Gợi ý các câu hỏi xoáy vào tính đo lường được của Metric | Viết lại câu chữ bị chung chung kiểu "giúp tối ưu hiệu quả công việc" | Tự sửa Metric thành chỉ số cụ thể: từ 90 phút xuống dưới 21 phút/tuần |
| Rule / Workflow / Agent | So sánh ưu nhược điểm giữa Workflow và Agent | Phân tích rõ rủi ro cấp quyền tự động cho Agent | Đề xuất chọn Agent tự động gửi mail vì tưởng "ngầu" hơn | Cùng nhóm bác bỏ gợi ý của AI, chốt chọn Workflow 5 bước có người duyệt |
| Decision | Gợi ý các chỉ số đo lường cho bản Pilot | Gợi ý 3 chỉ số cần đo thực tế cho đợt thử nghiệm 2 tuần | Không đưa ra được phương án rollback cụ thể khi hệ thống lỗi | Tự quy định điều kiện rollback về Pivot Table nếu AI bịa số 2 tuần liền |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Quá trình làm việc nhóm hôm nay đã mang lại cho tôi nhiều bài học thực tế về tư duy "Problem first, not AI first". Khi nghe top 3 problems từ các bạn trong nhóm, tôi nhận ra bài toán thức khuya chơi game hay lướt clip của mình mang tính thói quen tâm lý cá nhân nhiều hơn, rất khó để định hình một workflow chuẩn hóa cho AI xử lý. Ngược lại, bài toán làm Báo cáo Phản hồi Tuần của anh Đăng có đường đi quy trình 5 bước cực kỳ mạch lạc và baseline đo lường 90 phút rất rõ ràng. Trong lúc thảo luận ở Phase 6, nhóm cũng từng suýt rơi vào bẫy "solution-first" khi một số thành viên muốn xây dựng một AI Agent tự động gửi thẳng báo cáo cho sếp cho "ngầu". Tuy nhiên, sau khi cả nhóm cùng ngồi phân tích rủi ro ảo giác số liệu (hallucination),chúng tôi đã chủ động đề xuất giữ lại ranh giới Human Boundary ở bước Review. Điều khó nhất đối với tôi khi viết Problem Statement chính là việc xác định ranh giới Boundary: phải làm sao để AI hỗ trợ tối đa việc soạn thảo bài narrative nhưng tuyệt đối không được tự ý bịa thêm bối cảnh ngoài dữ liệu thô. Nếu được làm lại, tôi sẽ challenge nhóm mạnh hơn ngay từ bước Quick Validation để phỏng vấn thêm Quản lý cấp cao, từ đó làm rõ hơn nữa kỳ vọng chất lượng của bài báo cáo đầu ra.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
