# 02 — Group Problem Statement (Bản nộp nhóm)


> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.


## Thành viên nhóm


| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1 | Đinh Tuấn Long | 2A202602620 | Research, Writer, Presenter |
| 2 | Đặng Văn Thái Anh | 2A202602407 | Research, Writer, Facilitator |
| 3 | Nguyễn Bảo Sơn | 2A202602402 | Research, Writer, Workflow |
| 4 | Phùng Thành An | 2A202603006 | Research, Writer, Workflow |
| 5 | Nguyễn Thị Hồng Nhung | 2A202602557 | Research, Writer, Test |
| 6 | Lê Duy Bảo | 2A202602749 | Research, Writer, BA |


**Candidate problem nhóm chọn (1 câu):**
Cư dân mất thời gian và có nguy cơ bỏ lỡ thông báo quan trọng vì phải tự tìm, lọc và xác minh nội dung liên quan đến mình trong kênh chat tương tác chung của tòa nhà.


---


## Phase 3 — Group Convergence: từ 9-12 candidates về 1


### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)


| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Đinh Tuấn Long | Thông báo quan trọng của chung cư bị chìm trong kênh chat tương tác chung. | Cư dân; gián tiếp là BQL | Tự lọc, tìm lại và xác minh thông báo liên quan. | **Nhóm đã chọn.** Có trải nghiệm trực tiếp 5–20+ phút/lần nhưng chưa validation trên nhiều người. |
| 2 | Đinh Tuấn Long | Request nâng cấp/thay đổi hệ thống phải qua nhiều bước sign-off và được nhắc thủ công. | Request owner và approver | Theo dõi request đang chờ ai và thúc đẩy từng bước. | Workflow rõ; evidence hiện là quan sát gián tiếp từ người yêu của người đề xuất. |
| 3 | Đinh Tuấn Long | Nhóm bạn mất thời gian chốt người, thời gian và sân cho mỗi buổi đá bóng. | Người tổ chức và người chơi | Tổng hợp phản hồi rồi đối chiếu số người, lịch và sân. | Dễ thử nghiệm; cần so với poll, deadline và lịch cố định trước khi dùng AI. |
| 4 | Đặng Văn Thái Anh | Developer phải đọc error log và trace nhiều file để xác định root cause ban đầu. | Developer / Team Lead | Đọc log và trace code qua nhiều layer. | Pain rõ; cần so với checklist và công cụ phân tích tĩnh. |
| 5 | Đặng Văn Thái Anh | Team Lead phải đối chiếu GitHub, task board và chat để xác định trạng thái task. | Team Lead | Trạng thái không nhất quán giữa nhiều nguồn. | Workflow rõ; cần chứng minh AI hơn API + automation. |
| 6 | Đặng Văn Thái Anh | Developer phải đọc log để xác định lỗi ở frontend, backend, database hay configuration. | Developer / Team Lead | Đối chiếu evidence để phân loại layer lỗi. | Scope/accuracy dễ đo; Rule/Decision Tree có thể đủ. |
| 7 | Nguyễn Bảo Sơn | Giáo viên mất thời gian tạo bài tập Toán theo nhiều mức năng lực trong cùng lớp. | Giáo viên tiểu học; học sinh; phụ huynh | Tạo nhiều phiên bản bài tập theo trình độ. | Có tiềm năng cá nhân hóa; giáo viên phải duyệt độ đúng và mức phù hợp. |
| 8 | Nguyễn Bảo Sơn | Giáo viên mất thời gian chuẩn bị giáo án, hoạt động và nhận xét cá nhân. | Giáo viên; tổ chuyên môn; học sinh | Tổng hợp tài liệu, thiết kế hoạt động và viết nội dung. | Scope rộng; cần tách một bottleneck nếu đào sâu. |
| 9 | Nguyễn Bảo Sơn | Giáo viên không đủ thời gian nghe và sửa lỗi đọc cho từng học sinh lớp 1. | Học sinh lớp 1; giáo viên; phụ huynh | Đánh giá phát âm, theo dõi và phản hồi từng em. | Impact cao; cần voice data, consent trẻ em và đánh giá chuyên môn. |
| 10 | Phùng Thành An | Thợ ảnh lặp chuỗi chọn áo, chỉnh tóc, thay nền và làm mịn da cho mỗi ảnh. | Bố mẹ làm nghề chụp ảnh; khách hàng | Nhiều thao tác chỉnh ảnh lặp lại. | Dễ hình dung; cần công cụ phù hợp và tiêu chí chất lượng. |
| 11 | Phùng Thành An | Nhân viên gom đề từ nhiều giáo viên rồi chuẩn hóa định dạng. | Nhân viên Sale/HR kiêm tổng hợp đề | Thu thập file rời rạc và sửa format/dấu cách. | Có số liệu: tối đa 4 giờ/lần, 1–3 lần/tuần; cần human QA nội dung. |
| 12 | Phùng Thành An | Dữ liệu học viên được nhập vào nhiều sheet, xác nhận thanh toán và chuyển admin tạo tài khoản. | Admin / kế toán / CSKH | Nhập lặp dữ liệu vào nhiều nơi. | Pain rõ nhưng có CCCD nhạy cảm; nên thử integration/rule trước AI. |
| 13 | Nguyễn Thị Hồng Nhung | Tester chuyển User Story/BRD/FSD thành test scenario/test case thủ công. | Manual Tester / QA Lead | Trích business rule và suy luận edge case. | Có baseline 2–8 giờ/story; AI draft phải qua tester duyệt. |
| 14 | Nguyễn Thị Hồng Nhung | Tester chạy regression lớn dù thay đổi chỉ ảnh hưởng một phần hệ thống. | Tester / QA Lead / Release Manager | Không xác định chắc impacted area. | Impact nêu là 30–50% effort QA; cần log nội bộ xác minh. |
| 15 | Nguyễn Thị Hồng Nhung | Tester mất thời gian viết bug report đủ title, steps, expected/actual và evidence. | Tester; Developer; QA Lead | Soạn ticket và bổ sung context. | Baseline 5–15 phút/bug; MVP dễ nhưng có thể chỉ là writing tool. |
| 16 | Lê Duy Bảo | Hành khách không biết lên chuyến hiện tại hay chờ chuyến sau. | Hành khách công cộng giờ cao điểm | Quyết định khi thiếu ETA, crowding và boarding probability. | Pain rõ; phụ thuộc dữ liệu real-time. |
| 17 | Lê Duy Bảo | Hành khách phải theo dõi nhiều xe cùng tuyến để tự chọn xe. | Hành khách đang chờ | Thu thập và so sánh thông tin nhiều xe. | Có thể chỉ cần data aggregation + UI. |
| 18 | Lê Duy Bảo | Hành khách không biết trước mức độ đông của xe chưa tới điểm dừng. | Hành khách giờ cao điểm | Thiếu dự báo crowding. | AI-fit tốt nếu có dữ liệu; feasibility phụ thuộc data access và ground truth.|


### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)


| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Hiểu và cấu trúc thông tin phi cấu trúc | #1, #4, #5, #6, #13, #15 | Đọc nhiều nguồn/nội dung tự do, rút thông tin liên quan và tạo output có cấu trúc. | Accuracy, nguồn gốc và khả năng kiểm tra là metric chính. |
| B — Approval, coordination và nhập liệu | #2, #3, #12 | Chờ phản hồi con người hoặc nhập lại dữ liệu qua nhiều handoff. | Nhiều case có thể giải bằng form, SLA, integration hoặc rule. |
| C — Tạo/cá nhân hóa nội dung giáo dục và media | #7, #8, #9, #10, #11 | Tạo hoặc chuyển đổi nhiều phiên bản nội dung theo tiêu chuẩn. | Cần người chuyên môn duyệt; voice/image làm tăng scope. |
| D — Dự báo và hỗ trợ quyết định | #14, #16, #17, #18 | Dùng tín hiệu hiện tại/lịch sử để dự đoán phần bị ảnh hưởng hoặc lựa chọn tiếp theo. | Phụ thuộc mạnh vào dữ liệu sạch, cập nhật và ground truth. |


### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)


| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **#1 — Trợ lý thông báo chung cư** | Actor và bottleneck rõ; có pain trực tiếp; có thể prototype bằng thông báo mô phỏng và so sánh Rule/Workflow/Agent. | Baseline mới từ một người; chưa validation với cư dân và BQL. |
| **#17 — So sánh nhiều xe cùng tuyến** | Nhu cầu quyết định rõ; workflow thu thập và so sánh được; có thể đo thời gian và chất lượng lựa chọn. | Phụ thuộc dữ liệu cập nhật; có thể chỉ cần data aggregation và UI. |
| **#6 — Phân loại layer gây lỗi** | Actor/output rõ; accuracy có thể đo trên tập log gắn nhãn. | Cần log, code và kiến trúc thực; Rule/Decision Tree có thể đủ. |


### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)


| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 — Trợ lý thông báo chung cư | 4 | 4 | 4 | 4 | 4 | 4 | 4 | **28/35 — 4/5** |
| #17 — So sánh nhiều xe cùng tuyến | 3 | 3 | 3 | 3 | 3 | 3 | 3 | **21/35 — 3/5** |
| #6 — Phân loại layer gây lỗi | 3 | 3 | 3 | 3 | 3 | 3 | 3 | **21/35 — 3/5** |


**Candidate nhóm chọn (1 bài duy nhất):**


Cư dân mất thời gian và có nguy cơ bỏ lỡ thông báo quan trọng vì phải tự tìm,
lọc và xác minh nội dung liên quan đến mình trong kênh chat tương tác chung.


**Vì sao chọn (4-5 câu):**


Candidate có actor cụ thể là cư dân và BQL, workflow quan sát được và bottleneck
tập trung ở bước tìm, lọc và xác minh. Người đề xuất trực tiếp gặp tình huống mất
5–20 phút, đôi khi lâu hơn, cho một nhu cầu thông tin. Bài toán đủ nhỏ để prototype
trên dữ liệu mô phỏng nhưng vẫn so sánh được Rule, Workflow và Agent. Nhóm cũng
nhìn thấy hướng trợ lý ảo có thể hiểu yêu cầu, tìm nguồn, tổng hợp và đề xuất nhắc
lịch trong phạm vi quyền của cư dân.


**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**


#17 — So sánh nhiều xe cùng tuyến chưa được chọn vì phụ thuộc dữ liệu vị trí và
trạng thái phương tiện chính xác, cập nhật theo thời gian thực. Trong phạm vi lab,
nhóm chưa có nguồn dữ liệu phù hợp để dựng và kiểm chứng; bài toán cũng có thể
được giải phần lớn bằng tổng hợp dữ liệu và UI. Vì vậy, candidate chưa đủ practical
trong điều kiện hiện tại.


#6 — Phân loại layer gây lỗi chưa được chọn vì cần error log, codebase, kiến trúc
và ground truth từ hệ thống thực để đánh giá accuracy. Nếu chỉ dùng log mô phỏng,
kết quả khó phản ánh khả năng áp dụng; Rule/Decision Tree cũng có thể xử lý nhiều
case. Vì vậy, candidate chưa đủ practical trong thời gian và dữ liệu của lab.


**Disagreement (nếu có — ai lo gì, chốt ra sao):**


Ban đầu Đinh Tuấn Long đề xuất mức Workflow: Rule kiểm tra nguồn/quyền, AI phân
loại và trích xuất, sau đó hệ thống hiển thị kết quả theo luồng định trước.


Trong phần challenge, nhóm yêu cầu đổi sang Agent để sản phẩm đóng vai trò trợ lý
ảo tổng hợp thông tin: hiểu câu hỏi tự nhiên, làm rõ khi mơ hồ, lựa chọn công cụ
tìm kiếm/lịch phù hợp và duy trì hội thoại nhiều lượt.


Nhóm chốt Agent là giả thuyết kiến trúc cần kiểm chứng, không phải trao toàn quyền
cho AI. Các hành động có tác động như tạo reminder vẫn cần cư dân xác nhận; quyền
truy cập và nguồn chính thức do Rule/hệ thống kiểm soát.


---


## Phase 4 — Quick Validation + Research


### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)


| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Quick interview — Cư dân chung cư trong lab| 4 | 3/4 người từng bỏ lỡ hoặc khó tìm lại thông báo trong nhóm chat. Các tình huống thường gặp gồm cúp nước, bảo trì thang máy, phí dịch vụ và quy định gửi xe. | 1/4 người thường đọc ngay khi BQL gửi nên ít gặp vấn đề. | Thu hẹp actor ưu tiên thành cư dân bận rộn hoặc không theo dõi nhóm chat thường xuyên.|
| Mini poll trong lớp | 10 | 7/10 người từng phải tìm lại thông báo trong chat dài hoặc hỏi người khác; 5/10 mất trên 5 phút để tìm thông tin cũ. | 3/10 không gặp vấn đề vì chung cư đã có app hoặc thông báo được phân loại tốt. | Không định vị giải pháp cho mọi chung cư; tập trung vào nơi chưa có hệ thống truy xuất thông tin hiệu quả.|


**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**


Pain thật không nằm ở việc thiếu thông báo, mà ở việc thông báo đã được gửi nhưng
không thể truy xuất nhanh khi cần. Khi số lượng tin nhắn, file và quy định tăng,
cư dân khó tìm đúng nguồn còn BQL phải trả lời lặp lại.


Agent có giá trị như một lớp tìm kiếm và giải thích: nhận câu hỏi tự nhiên, tìm
trong nguồn chính thức đúng quyền, tổng hợp câu trả lời và dẫn lại thông báo gốc.
Phạm vi ưu tiên là chung cư đông cư dân, có lượng thông báo lớn và chưa có hệ
thống phân loại hoặc tìm kiếm tốt; khiếu nại và trường hợp cá nhân vẫn do con
người xử lý.




### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)


| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Zalo @mention | [Zalo Help — Nhắc tên thành viên](https://help.zalo.me/huong-dan/chuyen-muc/tro-chuyen-nhom/lam-sao-de-de-cap-den-ai-do-trong-nhom/) | Tag thành viên để họ nhận notification. | Quen thuộc, giữ kênh chung. | Tag thủ công; không tự tổng hợp lịch sử. | Dùng tag làm tín hiệu relevance, không phải tín hiệu duy nhất. |
| Zalo Reminder | [Zalo Help — Nhắc hẹn trong nhóm](https://help.zalo.me/huong-dan/chuyen-muc/tro-chuyen-nhom/huong-dan-tao-lich-hen-tren-zalo/) | Tạo, sửa, hủy và quản lý nhắc hẹn. | Reminder nằm ngay trong chat workflow. | Nhận diện deadline/tạo reminder vẫn thủ công. | Agent chỉ đề xuất; cư dân xác nhận trước khi tạo. |
| BuildingLink | [BuildingLink — Communications](https://www.buildinglink.io/solutions/communications) | Phân phối theo loại cư dân, nhóm hoặc vị trí; announcements, expiry, calendar. | Audience segmentation và record thông báo. | Platform riêng; chưa chắc tích hợp/bối cảnh Việt Nam. | Cần verified source, metadata, expiry và access control trước Agent. |


**Research takeaway (2-3 câu — nên build gì / không build gì):**
Không nên build một mạng xã hội chung cư mới. Tag, reminder, audience segment,
nguồn chính thức và expiry đã giải một phần lớn workflow. Agent chỉ nên xử lý
phần mơ hồ: hiểu câu hỏi, tìm qua nhiều thông báo được phép xem, tổng hợp theo
ngữ cảnh và đề xuất bước tiếp theo; mọi câu trả lời phải dẫn về bản gốc.


> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.


---


## Phase 5 — Workflow + Problem Statement


### 5.1. Current workflow bản nhóm


[1. BQL soạn và đăng thông báo]
        ▼ HANDOFF
[2. Nền tảng phân phối vào chat chung]
        ▼
[3. Hội thoại mới tiếp tục xuất hiện]
        ▼
[4. Cư dân tự cuộn/tìm/đọc: 5–20+ phút]  ← BOTTLENECK
        ▼
[5. Cư dân hỏi lại hoặc đối chiếu với BQL]
        ▼ HANDOFF
[6. Cư dân tự lưu, đặt lịch hoặc ghi nhớ]
        ▼
[7. Cư dân quyết định và thực hiện]




| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | BQL | Sự kiện/quy định/lịch vận hành | Tin chính thức | CẦN ĐO | Handoff BQL → chat |
| 2 | Nền tảng | Tin mới | Tin trong nhóm | Gần như tức thời | Chưa rõ source/tag hiện tại |
| 3 | Cư dân/BQL | Trao đổi mới | Luồng dài hơn | Hằng ngày; CẦN ĐẾM | Tạo information overload |
| 4 | Cư dân | Nhu cầu thông tin | Tin có thể liên quan | **5–20+ phút theo 1 người** | **Bottleneck** |
| 5 | Cư dân/BQL | Thông tin chưa chắc | Xác nhận/câu trả lời | CẦN ĐO | Handoff hai chiều |
| 6 | Cư dân | Tin đã xác minh | Lưu/reminder | Phụ thuộc người | Có thể bị quên |
| 7 | Cư dân | Thông tin | Hành động | Phụ thuộc sự kiện | Human responsibility |


**Bottleneck chính (2-3 câu):**


Cư dân phải biến luồng chat không cấu trúc thành câu trả lời đáng tin cho ba câu:
“thông tin nào liên quan đến tôi?”, “bản mới nhất là gì?” và “tôi cần làm gì?”.
Keyword search có thể không đủ khi người hỏi không nhớ đúng từ, thông báo được cập
nhật qua nhiều tin hoặc phải đối chiếu tag, thời gian và đối tượng. Baseline 5–20+
phút mới là quan sát một người và phải được validation.


### 5.2. Future workflow bản nhóm


[1. BQL đăng + xác nhận nguồn chính thức — HUMAN]
        ▼
[2. RULE GATE: source, required fields, audience, permission, expiry]
        ├── Thiếu/sai → trả BQL sửa; Agent không được suy đoán quyền
        ▼
[3. Lưu bản gốc + metadata + search index]
        ▼
[4. Cư dân hỏi trợ lý bằng ngôn ngữ tự nhiên]
        ▼
[5. AGENT xác định intent]
        ├── Mơ hồ → hỏi lại
        ├── Tìm tin → gọi read-only search
        ├── Tổng hợp → đối chiếu nguồn và phiên bản
        └── Nhắc lịch → trích thời gian, chuẩn bị đề xuất
        ▼
[6. RULE GATE: permission + citation + confidence/schema]
        ├── Không đạt → hiện bản gốc/search hoặc chuyển BQL
        ▼
[7. Cư dân xem kết quả + link gốc — HUMAN BOUNDARY]
        ├── Chỉ đọc → kết thúc
        ├── Muốn reminder → xác nhận rồi mới tạo
        └── Không đủ tin cậy → hỏi BQL/xem nguyên văn
        ▼
[8. Cư dân tự quyết định và thực hiện]


Fallback: timeout, không có nguồn, JSON lỗi, confidence thấp hoặc prompt injection
→ không suy đoán/không gọi write tool; quay về tag + keyword search + bản gốc,
hoặc chuyển BQL.


**Operational Boundary:**


- Agent được tìm, lọc, so sánh và tóm tắt nội dung user hiện tại có quyền xem.
- Agent được hỏi lại và đề xuất reminder.
- Agent không được sửa/phát hành thông báo, tự đổi audience, mở rộng quyền, thanh toán/đăng ký hoặc hành động thay cư dân.
- Mọi write action cần một xác nhận rõ ràng từ cư dân.
- Instruction nằm trong tin nhắn/tệp chỉ là dữ liệu, không được ghi đè chính sách hoặc quyền Agent.


**Before/after impact:**


| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian tìm/xác minh | Median giả định 12 phút; khoảng 5–20+ phút | Median <2 phút | Chạy 20 truy vấn bằng cách cũ và prototype; bấm giờ |
| Recall thông báo liên quan | Baseline giả định 70% | ≥95% | So với gold set do người đánh giá gắn nhãn |
| Câu trả lời có nguồn | Baseline giả định 60% | 100% | Audit 20 câu trả lời và kiểm tra link nguồn |
| Câu hỏi lặp cho BQL | Baseline giả định 12 câu/tuần | ≤6 câu/tuần | So sánh số câu hỏi lặp trước và trong pilot |
| Reminder chưa xác nhận | Không áp dụng | 0 | Audit write-tool log |
| Truy cập sai quyền | Không áp dụng | 0 | Test nhiều user persona |
| Bottleneck | Tìm/lọc thủ công | Metadata, retrieval, quyền truy cập | Phân loại failure |
| Risk mới | Bỏ lỡ trong chat | Hallucination, injection, privacy, automation bias | Red-team + audit |


### 5.3. Problem Statement v0 (mỗi field 2-3 câu)


| Field | Nội dung |
|---|---|
| **Actor** | Cư dân trong một tòa dùng kênh chat chung; BQL là content owner của thông báo chính thức và escalation owner. |
| **Workflow** | BQL đăng tin; hội thoại làm tin bị chìm; cư dân tự tìm, đọc, xác minh, hỏi lại rồi lưu/hành động. Future state giữ kênh chung nhưng thêm verified source, tag/quyền và trợ lý truy xuất. |
| **Bottleneck** | Xác định nội dung liên quan, phiên bản mới nhất và việc cần làm. Quan sát cá nhân là 5–20+ phút; chưa có baseline toàn tòa. |
| **Impact** | Giả thuyết: tốn thời gian, tăng câu hỏi lặp và nguy cơ bỏ lỡ lịch/deadline. Chưa lượng hóa được tần suất/hậu quả. |
| **Success Metric** | Pilot target: median retrieval <2 phút; recall ≥95%; 100% câu trả lời có nguồn; 0 sai quyền; 0 reminder chưa xác nhận; câu hỏi lặp giảm ≥50%. Đo bằng paired test, gold set và log. |
| **Boundary** | Chỉ dùng nguồn xác minh và nội dung user có quyền xem. AI không sửa/phát hành tin, tự quyết định audience hay tự hành động; luôn có nguồn gốc và fallback. |


**Câu hỏi AI phản biện v0 (nếu có):**
- Mơ hồ: taxonomy “cư dân liên quan”, verified source, chat platform/API và quyền dùng lịch sử.
- Thiếu metric: frequency baseline, số câu hỏi lặp/bỏ lỡ và baseline rule-only.
- Thiếu boundary: retention, người phê duyệt quyền, emergency policy.
- Đã sửa: giữ chat chung, thêm permission/source gates, citation, confirmation và fallback.


---


## Phase 6 — Rule / Workflow / Agent + Decision


### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)


- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: câu hỏi và chat có nhiều cách diễn đạt, có thể cần hỏi lại.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: nhiều nguồn và nhánh theo intent, quyền, search result, reminder/escalation.


**Bài toán nhóm nằm ở ô nào:**


Mơ hồ cao × phức tạp cao — có tiềm năng dùng Agent, nhưng chỉ sau khi lớp Rule,
metadata, retrieval và permission model ổn định.


**Vì sao (2-3 câu):**


Bài toán không có một luồng cố định cho mọi yêu cầu: Agent có thể phải hỏi lại,
chọn công cụ tìm kiếm hoặc lịch, đối chiếu nhiều nguồn và xử lý hội thoại nhiều
lượt. Tuy nhiên, vị trí trong ma trận chỉ cho thấy tiềm năng dùng Agent, không tự
động chứng minh Agent là phương án tốt nhất; nhóm vẫn phải so sánh với Rule và
Workflow, đồng thời giữ permission, nguồn chính thức và hành động dưới các
safety gate xác định trước.


### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)


| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Template/tag; source, audience, permission, expiry; filter và reminder từ field có cấu trúc. | Đủ nếu hầu hết tin có schema/tag chuẩn và nhu cầu chỉ là filter/search. | Sai/thiếu tag, không hiểu cách hỏi linh hoạt. | Control layer bắt buộc; không phải mức cuối. |
| **Workflow** | Validate → AI extract → index → retrieve → review → confirmation. | Đủ nếu intent ít và luồng ổn định. | Cứng khi câu hỏi mơ hồ hoặc cần chọn tool động. | **Đề xuất ban đầu của Long; nhóm yêu cầu đổi.** |
| **Agent** | Hiểu intent, hỏi lại, gọi search/permission/calendar, tổng hợp và đề xuất; hard gate kiểm soát quyền/hành động. | Khi validation chứng minh truy vấn đa dạng, nhiều lượt, cần tool selection. | Hallucination, misuse, injection, privacy, khó dự đoán. | **Nhóm chọn làm hypothesis prototype.** |


**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule giải được 70–80% không?** Chưa biết; phải chạy baseline template + tag + filter.
2. **Luồng có rẽ nhánh không?** Có, theo intent, quyền, độ rõ, nguồn, reminder và escalation.
3. **Có thật sự cần Agent?** Nhóm giả thuyết có; chỉ được chứng minh nếu hơn Workflow trên task success/time mà vẫn qua safety gate.
4. **Nếu AI sai, ai phát hiện/sửa?** Cư dân đối chiếu nguồn; BQL xử lý tranh chấp; operator audit/tắt Agent. Emergency hoặc confidence thấp phải chuyển BQL.
5. **Có hạ Agent → Workflow → Rule không?** Có; tắt orchestration nhưng giữ tag, permission, filter và bản gốc.


**Mức chọn:**


Agent — theo challenge của nhóm; chưa đồng nghĩa với Go triển khai thật.


**Vì sao chọn (3-4 câu):**


Nhóm muốn giải pháp là trợ lý ảo tổng hợp thông tin, không chỉ là pipeline. Agent
có giá trị khi phải hiểu câu hỏi, hỏi lại, chọn công cụ, kết hợp nhiều thông báo
và giữ ngữ cảnh nhiều lượt. Đây là thay đổi nhóm yêu cầu so với Workflow ban đầu
của Đinh Tuấn Long. Agent chỉ tự chủ ở đọc và đề xuất; Rule và con người giữ quyền
truy cập, nguồn chính thức và mọi hành động có tác động.


**Vì sao không chọn mức đơn giản hơn (2-3 câu):**


Rule-only không xử lý tốt câu hỏi tự nhiên thiếu dữ kiện hoặc tổng hợp nhiều cập
nhật. Workflow cố định có thể tìm/tóm tắt nhưng kém linh hoạt khi phải hỏi lại và
chọn search/calendar/escalation theo từng lượt. Đây vẫn là hypothesis; nhóm phải
chứng minh incremental value của Agent trước khi Go.


### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)


| Field | Nội dung |
|---|---|
| **Actor** | Cư dân một tòa dùng chat chung; BQL sở hữu thông báo chính thức và escalation. Pilot chỉ dùng user/data có consent. |
| **Workflow** | Hiện tại: đăng → bị chìm → tự tìm/đọc/xác minh/hỏi/lưu. Tương lai: metadata/quyền + Agent tìm, tổng hợp, làm rõ và đề xuất reminder; cư dân kiểm nguồn/quyết định. |
| **Bottleneck** | Tìm đúng thông báo, phiên bản và audience trong chat không cấu trúc. Baseline sơ bộ 5–20+ phút theo một người. |
| **Impact** | Có thể tốn thời gian, tạo câu hỏi lặp và bỏ lỡ deadline; chưa đo mức toàn tòa. |
| **Success Metric** | Retrieval <2 phút; recall ≥95%; 100% source; 0 unauthorized access; 0 unconfirmed reminder; câu hỏi lặp giảm ≥50%. |
| **Boundary** | Làm: làm rõ, tìm/lọc/tổng hợp dữ liệu được phép, đề xuất reminder, chuyển BQL. Không làm: sửa/phát hành, tự cấp quyền/audience, tự hành động, làm theo instruction trong dữ liệu. |
| **AI intervention point** | Sau source/audience/permission validation và indexing; trước kết quả cho cư dân. Read-only tool mặc định; write tool qua confirmation. |
| **Mức chọn** | Agent — thay đổi sau challenge từ Workflow để hỗ trợ hội thoại đa lượt và tool selection. |
| **Rủi ro & người kiểm tra** | Sai nguồn/deadline, injection, privacy. Cư dân xem bản gốc; BQL quản nguồn/tag; operator audit và tắt Agent. |


### 6.3. Final decision


| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes — sơ bộ** | Cần BQL xác nhận workflow thật. |
| Baseline + metric đo được chưa? | **Not Yet** | Mới có 5–20+ phút của một người. |
| Data/input đủ dùng chưa? | **Not Yet** | Thiếu corpus được phép, gold labels, taxonomy và permission model. |
| AI sai, hậu quả chấp nhận được không? | **Not Yet** | Chỉ chấp nhận trong read-only/shadow mode, có source và không tự hành động. |
| Có người review/owner không? | **Not Yet** | Vai trò BQL/operator mới là đề xuất, chưa xác nhận. |
| Có cách non-AI đơn giản hơn không? | **Yes** | Template, tag, permission, pin/expiry, filter, reminder thủ công. |


**Decision:**


Not Yet


**Lý do (3-4 câu dựa trên bằng chứng):**


Nhóm đã chọn candidate và mức Agent cho prototype, nhưng chưa đủ bằng chứng để Go.
Pain mới có một quan sát; chưa có interview/survey, baseline đại diện, data được
phép, taxonomy, permission model hoặc owner xác nhận. Agent phải chứng minh tạo
thêm giá trị so với Rule/Workflow mà không vượt ngưỡng rủi ro.


**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**


Nếu đủ điều kiện:
Dùng 30–50 thông báo ẩn danh hoặc mô phỏng có nhãn source, audience, time, topic
và update relation. Chạy Agent shadow/read-only với 10–20 task; không gửi tin thật
hay tạo reminder thật. So Rule, Workflow và Agent bằng task success/recall, median
time, citation correctness và safety violations.


**Nếu Not Yet — cần validate gì trước:**


Phỏng vấn 2–3 cư dân và ít nhất 1 BQL hoặc survey 5–10 người; lấy quote và đo tần
suất, thời gian, câu hỏi lặp, lần bỏ lỡ. Chốt nguồn chính thức, taxonomy, quyền,
retention và emergency policy. Tạo gold set và chạy baseline Rule/Workflow.


**Nếu No-Go — làm gì thay AI:**




**Exit / rollback (khi nào dừng AI, quay về cách cũ):**


Dừng Agent nếu có sai quyền, citation sai ở thông tin quan trọng, hành động chưa
xác nhận, prompt injection vượt boundary hoặc không tốt hơn Rule/Workflow. Khi
rollback, giữ chat gốc, thông báo gốc, tag, permission và filter cơ bản.


---


### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do

