# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đặng Văn Thái Anh
- Mã học viên: 2A202602407 
- Nhóm: DPS
- Candidate problem nhóm chọn: Trợ lý ảo tổng hợp và tìm kiếm thông báo liên quan cho cư dân chung cư trong chat

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đã tự scan 10 problems theo 4 lăng kính (lặp lại/tốn thời gian/AI tốt hơn/pain từ người khác) từ góc nhìn Team Lead/BA/Developer; chọn top 3: (1) đọc log + trace nhiều file để tìm root cause; (2) tổng hợp tiến độ tuần từ GitHub/task board/chat; (3) phân loại layer của bug. Viết đủ 3 Problem Card kèm current/future workflow + fallback. | 3 bài có actor, workflow 3–7 bước, bottleneck chỉ rõ 1 chỗ và metric đo được — đây chính là 3 candidate #4, #5, #6 tôi pitch vào nhóm. |
| Pitch Problem Card | Pitch 3 candidate trong nhóm: #4 đọc log + trace nhiều file để tìm root cause ban đầu (Developer/Team Lead); #5 Team Lead đối chiếu GitHub + task board + chat để biết trạng thái task; #6 Developer phân loại lỗi thuộc frontend/backend/database/config. Mỗi bài trình bày 1–2 phút kèm pain, workflow và số đo baseline. | #6 "Phân loại layer gây lỗi" được nhóm giữ vào shortlist top 3 cùng #1 và #17; #4 và #5 bị loại ở shortlist nhưng gộp vào cluster A — pattern "đọc nhiều nguồn, rút thông tin liên quan, tạo output có cấu trúc". |
| Challenge bài của bạn khác | Ở vai trò Facilitator, tôi trực tiếp challenge Đinh Tuấn Long: bài #1 đã chọn nhưng đề xuất ban đầu là Workflow (validate → AI extract → index → retrieve → review → confirmation) là quá cứng cho câu hỏi tự nhiên thiếu dữ kiện; yêu cầu đổi sang Agent để hỗ trợ hội thoại nhiều lượt và chọn search/calendar/escalation theo từng lượt. Đồng thời hỏi thẳng nhóm về baseline recall, frequency bỏ lỡ và ownership BQL. | Nhóm chốt lại mức Agent là hypothesis prototype (không phải Go), giữ chat gốc + thêm permission/source gate + confirmation; bổ sung vào Disagreement và Phase 6.1. |
| Gom trùng / cluster | Đóng góp 3 candidate (#4, #5, #6) vào cluster A "Hiểu và cấu trúc thông tin phi cấu trúc" cùng #1, #13, #15; đề xuất pattern chung là "đọc nhiều nguồn → rút thông tin liên quan → output có cấu trúc" với metric chính là accuracy, nguồn gốc và khả năng kiểm tra. | Cluster A thành cluster lớn nhất bảng gom trùng; pattern này được nhóm dùng làm lăng kính để so sánh khi chấm shortlist và quyết định mức AI. |
| Chọn candidate problem | Tham gia chấm shortlist theo 7 tiêu chí (actor rõ, workflow rõ, pain có evidence, impact đo được, làm trong lab, so sánh R/W/A được, nhóm hiểu domain). Trong giai đoạn hội tụ, đồng tình chọn #1 thay vì #6 (của tôi) vì #1 có trải nghiệm trực tiếp 5–20+ phút/lần, đủ nhỏ để prototype và so được Rule/Workflow/Agent; #6 cần log/codebase thật để đo accuracy nên kém practical trong lab. | Nhóm đồng thuận chọn #1 với 28/35 điểm (4/5); #6 và #17 cùng 21/35 (3/5). Quyết định này được ghi vào Phase 3.3, 3.4 và giữ nguyên sang PS v0/v1. |
| Validation / research | Đóng góp research về Zalo @mention (làm tín hiệu relevance) và Zalo Reminder (đặt lịch ngay trong chat) trong bảng 4.2; rút bài học: tag không phải tín hiệu duy nhất, Agent chỉ đề xuất reminder, cư dân xác nhận trước khi tạo. | Bảng research đầy đủ 3 nguồn có link kiểm được; nhóm đi tới "không build mạng xã hội chung cư mới" và giữ chat gốc + thêm verified source/metadata/expiry. |
| Workflow nhóm | Phối hợp với Sơn và An (nhóm Workflow) đóng góp bước 5 trong current workflow (Cư dân tự lưu, đặt lịch hoặc ghi nhớ) và các lưu ý "phụ thuộc người/có thể bị quên"; đề xuất future workflow có RULE GATE ở cả đầu vào (source/audience/permission/expiry) và đầu ra (permission + citation + confidence/schema); Agent chỉ read-only tool, write tool qua confirmation. | Future workflow có 2 gate rõ ràng, agent boundary "không sửa tin, không tự cấp quyền, không tự hành động" được đưa thẳng vào Operational Boundary và Problem Statement v1. |
| Problem Statement | Đảm nhận vai trò Writer: soạn và sửa PS v0 sang v1 với 9 field (Actor, Workflow, Bottleneck, Impact, Success Metric, Boundary, AI intervention point, Mức chọn, Rủi ro & người kiểm tra). Boundary v1 phân tách rõ "Làm / Không làm" và đưa instruction-trong-dữ-liệu vào nhóm không tuân theo. | PS v1 có metric đo được trước/sau (median <2 phút, recall ≥95%, 100% source, 0 unauthorized, 0 unconfirmed reminder, giảm ≥50% câu hỏi lặp) và boundary làm/không làm — trở thành anchor cho phần Decision. |
| Rule / Workflow / Agent | Cùng Long giữ tranh luận về mức chọn: bảo vệ quan điểm "Rule-only không hiểu câu tự nhiên thiếu dữ kiện, Workflow cố định kém linh hoạt khi cần hỏi lại/chọn tool", đồng thời thừa nhận "Agent chỉ tự chủ ở đọc và đề xuất; Rule và con người giữ quyền". Trả lời 5 câu hỏi chốt trong bảng 6.1. | Nhóm chốt Agent là hypothesis prototype và vẫn phải chứng minh incremental value so với Rule/Workflow trước khi Go. |
| Decision | Đồng tình Decision = **Not Yet**: pain mới có 1 quan sát (5–20+ phút của 1 người), chưa có interview/survey, baseline đại diện, data được phép, taxonomy, permission model hay owner xác nhận; Agent có thể tạo thêm giá trị nhưng chưa vượt nguy cơ hallucination, injection, privacy, automation bias. Đóng góp pilot nhỏ nhất (30–50 thông báo mô phỏng có nhãn, 10–20 task shadow/read-only, đo task success/recall/median time/citation/safety violations) và exit/rollback (dừng Agent khi sai quyền, citation sai, injection, không tốt hơn Rule/Workflow). | Decision Not Yet + lý do 4 câu + pilot + điều kiện rollback được khóa trong bảng 6.3 và self-check nộp phần 02. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Là Facilitator, tôi trực tiếp challenge Đinh Tuấn Long để chuyển mức giải pháp từ Workflow sang Agent — quyết định định hình toàn bộ future workflow của nhóm. Ở vai trò Writer, tôi thiết kế cặp RULE GATE (đầu vào source/audience/permission/expiry + đầu ra permission/citation/confidence) và boundary "Làm / Không làm" trong PS v1 — hai lớp safety này là lý do nhóm chốt Decision = Not Yet thay vì Go dù đã chọn Agent làm hypothesis.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Brainstorm 8–10 vấn đề từ list trigger, mở rộng category theo gợi ý AI | Sinh candidate pool nhanh, gợi ý format trigger matrix 4×2 | Gợi ý vấn đề generic (giấc ngủ, focus, deadline) thiếu bối cảnh cá nhân; không hỏi phản biện về tần suất/impact | Lọc còn 3 vấn đề từng gặp trong dự án thật, tự chấm freq × impact bằng dữ liệu tuần qua |
| Problem Card | Rewrite 3 candidate card theo template, gợi ý metric placeholder | Format đồng nhất, nhắc các trường dễ thiếu (trigger, actor, cost) | AI điền placeholder rỗng, không thúc đẩy định lượng; đề xuất metric khó đo (vd: "cảm thấy mệt") | Ép mình điền số cụ thể (2h/ngày search docs, 30 phút recap meeting), bỏ metric không đo được |
| Workflow | Brainstorm step + sequence cho flow giải pháp nhóm, gợi ý tên phase | Gợi ý tên phase trung tính, nhắc bước handoff hay quên | Vẽ flow tuyến tính như process doc; thiếu decision gate, không gắn role rõ ràng | Vẽ lại thành flowchart có gate (ai review, ai sign-off) và ownership từng step — đây cũng là bài học tôi rút ra từ môn AI workflow |
| Research | Tổng hợp định nghĩa Agent / MCP / permission; list nguồn tham khảo | Gom định nghĩa nhanh, surface khái niệm MCP tôi chưa biết | Cho định nghĩa textbook, không cite case lỗi thật; hallucinate 1–2 "best practice" không truy ngược được | Đối chiếu với docs chính thức (Cursor SDK, MCP spec), thêm 1 incident cũ của nhóm làm case cụ thể |
| Problem Statement | Tinh gọn văn phong, viết lại PS v1 thành narrative mạch lạc | Bỏ lặp ý, gợi ý headline sắc hơn cho PS v2 | Cố "làm phẳng" xung đột — xoá luôn phần Disagreement của Long vì cho là "gây nhiễu flow" | Giữ nguyên Disagreement verbatim, không để AI xoá dấu vết phản biện vì đó là evidence cho Decision = Not Yet |
| Rule / Workflow / Agent | Brainstorm field cho 2 RULE GATE; list edge case permission/expiry | Gợi ý 10+ edge case cho input/output gate, đề xuất format checklist | Gate do AI sinh chỉ cover happy path; thiếu rollback gate khi agent fail hoặc xin quyền sai | Tự thêm rollback condition + pilot scope vào Decision Not Yet, biến 2 gate thành safety net thực sự chứ không phải checkbox |
| Decision | List pros/cons Go vs Not Yet, structure final decision theo binary | Ép framing binary, tóm tắt trade-off gọn trong 1 trang | Ngầm đẩy về Go vì sunk cost ("nhóm đã làm nhiều rồi"), không push câu hỏi "tại sao không No-Go" | Tách quyết định khỏi effort đã bỏ: thêm pilot 1 case + rollback trigger, đề xuất Not Yet dù hypothesis Agent đã được chấp nhận |

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
Có, nhóm tôi suýt rơi vào solution-first — lúc đầu Đinh Tuấn Long đề xuất Workflow (Rule lọc → AI trích xuất → hiển thị kết quả), nhưng khi cả nhóm thấy hướng "trợ lý ảo" nghe ngầu hơn thì ai cũng nghiêng về Agent, và tôi phải đứng ra kéo câu hỏi ngược: Workflow đã giải được bao nhiêu phần trăm vấn đề, và phần còn lại có thật sự cần agent hay chỉ là sở thích? Cuối cùng nhóm vẫn chốt Agent nhưng vì lý do đúng (cần hiểu câu hỏi tự nhiên, hỏi lại khi mơ hồ, chọn tool search/calendar/escalation theo từng lượt), chứ không phải vì "ngầu" — đó là bài học tôi nhớ nhất trong buổi làm nhóm: challenge không phải để phá, mà để tách "thích" khỏi "cần".

Tôi có đổi ý một lần sau khi tự đọc lại 5 câu hỏi chốt trong mục 6.1 — đặc biệt câu "Có hạ Agent xuống Workflow/Rule được không?". Lúc đầu tôi muốn viết Hypothesis theo hướng "Agent sẽ giải quyết X", nhưng khi đọc lại câu hỏi đó tôi nhận ra framing đó tilt về giải pháp và vô tình biến rollback thành "thất bại" thay vì "lựa chọn hợp lệ". Tôi đổi sang viết hypothesis dưới dạng "cần permission động + expiry + multi-turn disambiguation, Agent là một cách implement, Workflow/Rule là fallback" — đổi ý theo nghĩa đó là cập nhật model chứ không phải nhượng bộ.

Phần có dấu tay thật của tôi trong artifact cuối là cặp RULE GATE (đầu vào source/required fields/audience/permission/expiry + đầu ra permission/citation/confidence) trong Future Workflow — tôi thiết kế để nó thành safety net thực sự, không phải checklist hình thức; kèm theo đó là việc tôi giữ nguyên phần Disagreement trong bản nhóm, vì xoá xung đột đồng nghĩa xoá evidence cho Decision = Not Yet, và boundary "Làm / Không làm" trong PS v1 cũng là sản phẩm chung mà tôi góp phần phân loại hành động.

Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở pilot scope trong mục "Nếu Go — pilot nhỏ nhất" — hiện đang gộp 30–50 thông báo với 10–20 task, đó là framing "làm cho xong" hơn là "thu hẹp để học"; thu hẹp còn 10–15 thông báo + 5 task sẽ giúp nhóm phát hiện sớm failure case (ví dụ audience taxonomy chưa ổn) thay vì đợi pilot chạy xong mới biết.
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

