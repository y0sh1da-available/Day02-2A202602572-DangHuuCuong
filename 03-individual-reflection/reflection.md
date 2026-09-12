# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đặng Hữu Cương
- Mã học viên: 2A202602572
- Nhóm: Cửa B Zone C
- Candidate problem nhóm chọn: Chuyển đổi tài liệu học thuật (reading/slide 30–50 trang) thành AI Audio Podcast & Micro-learning để học on-the-go trên xe bus, giúp sinh viên ngoại trú giải phóng 15h thời gian chết mỗi tuần và giảm áp lực học đêm khi đã kiệt sức.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 7 vấn đề bám sát trải nghiệm 3h đi xe bus mỗi ngày (nội thành ⇄ VinUni) theo 4 lăng kính, đưa ra số liệu bấm giờ thật | Tạo ra danh sách candidate có dữ liệu đo lường cụ thể nhất trong nhóm (15h dead time/tuần, 90-120' đọc đêm) |
| Pitch Problem Card | Pitch Card #1 trong 2 phút: biến 15h say xe trên bus thành AI Audio Podcast + Active Recall giải phóng học đêm | Thuyết phục cả nhóm nhìn thấy rõ nút thắt cổ chai và sự chênh lệch giữa 125' đọc đêm mệt mỏi và 35' học chủ động |
| Challenge bài của bạn khác | Chất vấn bài Math OCR của Đức (Mathpix đã làm quá tốt) và bài Airflow Log của Lộc (thiếu môi trường test thật trong lab) | Giúp nhóm nhận diện sớm rủi ro "làm lại bánh xe lịch sử" và tránh chọn đề tài có domain quá hẹp khó làm trong 4 tiếng |
| Gom trùng / cluster | Cùng Đức và Lộc gom 9 candidate problems thành 3 cụm: Học on-the-go, Số hóa tài liệu Toán, và Vận hành DataOps | Giúp cấu trúc lại toàn bộ ý tưởng rời rạc của các thành viên thành bức tranh tổng thể trước khi chấm điểm |
| Chọn candidate problem | Bảo vệ bài toán #1 bằng 5 luận điểm: cả 3 đều hiểu sâu domain, có sẵn slide thật để test, workflow trước/sau rất rõ | Nhóm đạt đồng thuận tuyệt đối (35/35 điểm), thống nhất 100% chọn bài AI Audio on-the-go làm đề tài chính |
| Validation / research | Cung cấp dữ liệu phỏng vấn người thật từ nhật ký di chuyển của bản thân; cùng Lộc phân tích khoảng trống của NotebookLM & Speechify | Rút ra bài học cốt lõi: NotebookLM thiếu câu hỏi phản xạ (Active Recall), Speechify chỉ đọc vẹt cơ học |
| Workflow nhóm | Trực tiếp bóc tách bảng 6 bước Current State và 5 bước Future State, đồng thời dựng sơ đồ trực quan ASCII & Mermaid | Định hình rõ nút thắt cổ chai ở bước đọc đêm kiệt sức và thiết kế chốt chặn Human Boundary ở bước review câu hỏi |
| Problem Statement | Cùng nhóm hoàn thiện 6 fields của PS v0 và nâng cấp lên PS v1 với đầy đủ ranh giới Làm / Không làm | Chốt chặn rủi ro AI ảo giác bằng quy định bắt buộc xuất kèm bản tóm tắt One-page Cheat Sheet đối chiếu |
| Rule / Workflow / Agent | Lập luận trả lời 5 câu hỏi chốt để phản biện mức Agent (over-engineering) và Rule (không hiểu ngữ nghĩa học thuật) | Dẫn dắt nhóm thống nhất lựa chọn giải pháp Workflow tuyến tính có Human-in-the-loop |
| Decision | Đề xuất kịch bản Smallest Pilot trên 1 slide môn học thật và xác định tiêu chí Rollback định lượng sau 2 tuần | Giúp nhóm đưa ra quyết định GO tự tin, có kế hoạch hành động cụ thể và có đường lui an toàn |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là toàn bộ cấu trúc sơ đồ Workflow trước/sau (cắt giảm từ 125' xuống 35') với các mốc thời gian định lượng từ chính trải nghiệm 3h đi xe bus VinUni của tôi, cùng cơ chế chèn 3 câu hỏi Active Recall vào cuối audio để loại bỏ hoàn toàn bẫy nghe thụ động.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Mở rộng góc nhìn từ vấn đề di chuyển 3h/ngày theo 4 lăng kính | Bóc tách vấn đề di chuyển thành các hệ quả sinh hoạt: cạn kiệt năng lượng, lệch pha họp nhóm | AI gợi ý ý tưởng "AI tối ưu đường đi tránh tắc đường cho xe bus" rất phi thực tế | Loại bỏ ý tưởng đó vì xe VinBus chạy lộ trình cố định; tập trung chuyển hóa thời gian chết trên xe |
| Problem Card | Đóng vai trò skeptical PM để phản biện cấu trúc Problem Card #1 | Cảnh báo việc chỉ nghe audio dễ khiến sinh viên nghe thụ động và ngộ nhận là đã hiểu bài | AI gợi ý chung chung "thêm tính năng chatbot hỏi đáp", làm loãng quy trình | Tự bổ sung bước "Review 3 câu hỏi phản xạ" và "One-page Cheat Sheet" để tạo Human Boundary |
| Workflow | Sinh mã Mermaid và sơ đồ ASCII chuẩn hóa cho Before/After workflow | Dựng sơ đồ trực quan rất nhanh, phân biệt rõ màu sắc giữa Bottleneck và Human Boundary | AI tự vẽ thêm các bước rườm rà như "tự động đồng bộ LMS và chấm điểm" | Lược bỏ các bước thừa, giữ pipeline tinh gọn 5 bước bám sát đúng thời lượng 20 phút ngồi trên xe bus |
| Research | Tìm kiếm thông tin tính năng của NotebookLM và Speechify | Cung cấp nhanh cấu trúc podcast 2 host của NotebookLM và hạn chế đọc nguyên văn của Speechify | AI trích dẫn số liệu thị phần người dùng không có căn cứ xác thực | Tự kiểm tra link web chính thức (notebooklm.google.com, speechify.com) và tự đúc kết bài học cho nhóm |
| Problem Statement | Phản biện tính khả thi và đo lường của các field trong PS v0 | Chỉ ra rằng metric "tiếp thu kiến thức chất lượng cao" còn mơ hồ, chưa có cách đo định lượng | AI đề xuất làm "bài kiểm tra 30 câu", quá nặng nề cho việc học nhanh on-the-go | Sửa thành tiêu chí đo lường thực tế: "trả lời đúng ít nhất 2/3 câu hỏi phản xạ nhanh dạng Active Recall" |
| Rule / Workflow / Agent | Phản biện việc lựa chọn giữa Workflow và Agent | Giúp cấu trúc 5 câu hỏi chốt để kiểm tra ranh giới giữa Rule, Workflow và Agent | AI ban đầu thiên vị gợi ý làm Agent tự lập kế hoạch học tập cá nhân | Kiên quyết chọn Workflow vì quy trình tuyến tính; làm Agent là over-engineering tốn kém |
| Decision | Gợi ý cấu trúc cho Smallest Pilot và tiêu chí Exit | Đưa ra khung 3 chỉ số đo lường cần thiết cho đợt thử nghiệm đầu tiên | Tiêu chí rollback của AI đưa ra quá chung chung ("khi người dùng không hài lòng") | Định lượng rõ tiêu chí rollback: "sau 2 tuần pilot nếu tỷ lệ đúng quiz < 50% thì dừng phát triển AI" |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

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
Quá trình làm việc nhóm Day 02 hôm nay đã mang lại cho tôi bài học sâu sắc nhất từ trước đến nay về nguyên tắc "Problem first, not AI first". Khi lắng nghe top 3 bài của Đức và Lộc, tôi nhận ra một bài toán kỹ thuật dù nghe rất phức tạp như sửa script crawler hay đọc log Airflow vẫn có thể bị loại nếu đối tượng sử dụng quá hẹp và nhóm không thể giả lập môi trường để kiểm chứng thực tế trong buổi lab. Nhóm tôi cũng có thời điểm suýt rơi vào bẫy solution-first khi Lộc và Đức hào hứng muốn nâng cấp đề tài thành một Multi-Agent tự động quét thông báo trên Canvas và tự tra cứu tài liệu mở rộng. Khi đó, tôi đã dùng chính 5 câu hỏi chốt của bài học để thuyết phục nhóm rằng quy trình học bài là một đường ống tuyến tính cố định, việc làm Agent chỉ làm tăng chi phí và rủi ro hallucination không đáng có. Đến lúc bị Đức challenge thẳng thắn rằng "nghe audio thì làm sao hiểu được slide có công thức và biểu đồ", tôi không hề bảo vệ giải pháp một cách cố chấp mà lập tức thay đổi nhận thức. Tôi hiểu rằng điểm yếu chí mạng của âm thanh là thiếu trực quan, nên đã bổ sung ngay bản "One-page Cheat Sheet" tóm tắt từ khóa song song với podcast và thu hẹp phạm vi ban đầu chỉ áp dụng cho tài liệu lý thuyết. Điều thử thách nhất với tôi khi viết Problem Statement không phải là nghĩ ra tính năng AI, mà là định nghĩa ranh giới Boundary — phải dũng cảm vạch rõ những gì AI tuyệt đối không được làm để con người luôn nắm quyền kiểm soát chất lượng. Đóng góp lớn nhất mang đậm dấu tay của tôi trong bài nộp nhóm chính là việc số hóa toàn bộ trải nghiệm 3 tiếng đi xe bus của bản thân thành một quy trình Before/After định lượng từ 125 phút xuống 35 phút. Nếu có cơ hội làm lại từ đầu buổi lab, tôi sẽ chủ động challenge nhóm chạy thử nghiệm nghe 5 phút trên một tài liệu thực tế ngay từ Phase 4 để có dữ liệu phản hồi tại chỗ thay vì chỉ dựa vào khảo sát lý thuyết.
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

