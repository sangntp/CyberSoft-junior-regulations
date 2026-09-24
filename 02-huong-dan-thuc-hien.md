# HƯỚNG DẪN THỰC HIỆN NỘI QUY NHẬP HỌC (SOP THEO TỪNG VAI TRÒ)
> **Tài liệu chuẩn hóa quy trình vận hành nội bộ - Áp dụng từ ngày 01/09/2026**  
> **Mục tiêu cốt lõi:** Thiết lập cơ chế kiểm soát bắt buộc (Pre-Payment Gatekeeper): 100% Phụ huynh phải tiếp cận, đọc hiểu và xác nhận cam kết tuân thủ 17 Điều Nội Quy Nhập Học TRƯỚC KHI thực hiện thanh toán học phí. Tuyệt đối không thu tiền trước - giải thích sau.

---

## KHUNG CHỈ SỐ PHỄU CHUYỂN ĐỔI CRM (L0 ➔ L9)

Hệ thống quy chuẩn 10 trạng thái học viên thống nhất giữa các bộ phận:

| Mã Trạng Thái | Tên Trạng Thái | Định Nghĩa & Tính Chất | Bộ Phận Phụ Trách | SLA Thời Gian |
| :---: | :--- | :--- | :---: | :---: |
| **L0** | Data Thô (New Lead) | Lead mới đồng bộ từ Ads / Fanpage / Form Landing Page về CRM. | Marketing / CRM | < 2 Phút |
| **L0.1** | Lead Rác (Invalid) | Sai số, spam, sai độ tuổi tuyển sinh (< 8 tuổi hoặc > 17 tuổi). | Sales | Ngay cuộc gọi |
| **L1** | Tiếp Nhận (Assigned) | Lead hợp lệ phân bổ cho Sales, kiểm tra lịch sử chuẩn bị kịch bản. | Sales | < 15 Phút |
| **L2** | Đã Tiếp Xúc (Contacted)| Đã trao đổi với PH, xác nhận nhu cầu và giới thiệu lộ trình. | Sales | < 24 Giờ |
| **L3A** | Đặt Lịch Trải Nghiệm | Phụ huynh chốt lịch cho con tham gia buổi Trải Nghiệm 60 phút. | Sales sang Giáo vụ | Trước ca >= 4h |
| **L3B** | Đã Học Trải Nghiệm | Bé hoàn thành 60p học thử, có Bảng Rubric và Sản phẩm mini. | Giảng viên sang GVU | < 2 Giờ |
| **L3C** | Vắng Buổi Trải Nghiệm | Bé vắng không lý do. Sales thăm hỏi và dời lịch (tối đa 2 lần). | Sales & Giáo vụ | < 12 Giờ |
| **L4A** | Cân Nhắc & Gatekeeper | Sales gọi Golden Call tư vấn theo Rubric, giải thích 17 Điều Nội quy. | Sales | < 12h sau L3B |
| **L4B** | Đặt Cọc (Deposit) | Phụ huynh đặt cọc giữ chỗ mở lớp (thanh toán nốt trước KG 3 ngày). | Sales & Kế toán | Theo hạn cọc |
| **L5** | Đã Thanh Toán (Paid) | Phụ huynh hoàn tất 100% học phí khóa học chính thức. | Sales & Kế toán | < 30 Phút |
| **L5.1** | Bàn Giao Giáo Vụ | Đã có Phiếu Cam Kết đã ký kèm Handover Form gửi sang Giáo vụ. | Sales sang Giáo vụ | < 2 Giờ |
| **L5.2** | Đã Xếp Lớp (Enrolled) | Giáo vụ đón PH vào Zalo lớp, cấp tài khoản LMS và Lịch học. | Giáo vụ | Trước KG >= 24h |
| **L6** | Tái Tục (Renew/Upsell) | Học viên hoàn thành khóa/tầng, đăng ký học tiếp Tầng nâng cao. | Giáo vụ & Sales | Trước bế giảng 2b |
| **L8** | Tạm Dừng / Bảo Lưu | Học viên làm thủ tục bảo lưu, tạm dừng học có lý do chính đáng. | Giáo vụ | < 24 Giờ |
| **L9** | Tái Kích Hoạt | Học viên bảo lưu hết hạn hoặc học viên cũ quay lại học tiếp. | Sales / CSKH | Ngay tương tác |

---

## VAI TRÒ 1: CHUYÊN VIÊN TƯ VẤN TUYỂN SINH (SALES)

> **Mục tiêu:** Tư vấn đúng năng lực của học viên; thực thi nghiêm ngặt cơ chế Cổng Chặn (Gatekeeper) — bảo đảm 100% Phụ huynh đọc, hiểu và ký cam kết 17 Điều Nội quy đào tạo trước khi cung cấp thông tin thanh toán.

```text
[L3B: Kết quả Rubric buổi Trải nghiệm 60p]
                   │
                   ▼
[Bước 1: Tư Vấn Lộ Trình & Khảo Sát Đầu Vào] ──(Trạng thái L4A)
                   │
                   ▼
[Bước 2: Kích Hoạt Gatekeeper - Phổ Biến 17 Điều Nội Quy]
                   │
                   ▼
[Bước 3: CỔNG CHẶN - Bắt Buộc Ký / Xác Nhận Cam Kết] ──(Offline tại quầy HOẶC Online qua E-Form)
                   │
                   ▼ (Chỉ mở khóa sau khi đã có Cam kết hợp lệ)
[Bước 4: Mở Cổng Thanh Toán - Cấp QR/STK & Nhận Tiền] ──(Trạng thái L5 / L4B)
                   │
                   ▼
[Bước 5: Lập Handover Form Bàn Giao Sang Giáo Vụ] ──(Trạng thái L5.1 - SLA < 2h)
```

### Bước 1: Tư vấn lộ trình dựa trên kết quả Trải nghiệm (Trạng thái L3B sang L4A)
* **Thời hạn SLA:** Gọi lại trong vòng < 12 giờ làm việc sau khi buổi học trải nghiệm 60 phút của bé kết thúc.
* **Hành động tiêu chuẩn:**
  1. Đọc kỹ Bảng đánh giá Rubric từ Giảng viên trải nghiệm: Nắm chắc điểm mạnh tư duy logic, phản xạ thao tác máy tính và mức độ tự tin của con.
  2. Thực hiện cuộc gọi Golden Call chúc mừng gia đình, gửi kèm video hoặc link sản phẩm mini do con tự tay lập trình trong buổi học để Bố Mẹ trực tiếp xem.
  3. Tư vấn trung thực, chuẩn xác Tầng học phù hợp theo khung đào tạo:
     * Tầng 1 - Cadet (Lớp 3 - 5): Nền tảng tư duy Scratch & GameMaker.
     * Tầng 2 - Agent (Lớp 6 - 8): Viết mã thực chiến với Python, Cấu trúc dữ liệu và ứng dụng AI.
     * Tầng 3 - Architect (Lớp 9 - 11): Kiến trúc hệ thống, Fullstack, AI APIs & Portfolio.
     * Tầng đệm - Overdrive (OD1): Học sinh lớn tuổi chưa có nền tảng tin học (theo đúng ví dụ minh họa Điều 1), học tách biệt để bảo đảm tâm lý tiếp thu.
* **Đầu ra:** Phụ huynh đồng thuận với khóa học đề xuất; cập nhật CRM sang trạng thái L4A (Đang cân nhắc / Chốt giải pháp).

### Bước 2: Kích hoạt cơ chế Gatekeeper - Phổ biến Nội quy (Trạng thái L4A)
* **Nguyên tắc gác cổng:** Tuyệt đối KHÔNG gửi số tài khoản, mã QR thanh toán hoặc thúc ép đóng tiền ở bước này.
* **Hành động tiêu chuẩn:**
  1. Gửi bản toàn văn 01. Nội Quy Nhập Học (17 Điều) qua kênh liên lạc chính thức (Zalo/Email) cho Phụ huynh.
  2. Trực tiếp nhấn mạnh và giải thích cặn kẽ 5 Điểm cốt lõi bắt buộc nắm rõ trước khi thanh toán:
     * Chính sách Học phí (Điều 2.2): CyberSoft áp dụng nguyên tắc KHÔNG HOÀN HỌC PHÍ sau khi đăng ký (ngoại lệ chỉ áp dụng khi đi du học hoàn 80% buổi chưa học hoặc lỗi hoãn lớp > 3 tháng từ trung tâm).
     * Quỹ thời gian Gói Combo (Điều 2.3): Đăng ký gói Combo không áp dụng bảo lưu lẻ từng khóa mà áp dụng Khung thời hạn tối đa hoàn thành (Ví dụ: Combo 3 khóa hoàn thành trong tối đa 15 tháng).
     * Chuyên cần & Học bù Tutor (Điều 6): Nghỉ học có phép (báo trước >= 2 tiếng) được hỗ trợ tối đa 03 buổi học bù Tutor 1:1 miễn phí (30 - 60 phút/buổi).
     * Thời hạn thu hồi tài khoản LMS (Điều 11): Hệ thống tự động thu hồi tài khoản sau 07 ngày kể từ ngày bế giảng; con cần chủ động tải source code dự án về máy cá nhân.
     * Văn hóa lớp học & Đón trả an toàn (Điều 5 & Điều 17): Tinh thần tôn trọng bạn bè (chống Cyberbullying); phụ huynh đón con đúng giờ và đăng ký người đón ủy quyền để đảm bảo an toàn cho trẻ.
* **Đầu ra:** Phụ huynh xác nhận qua tin nhắn: "Tôi đã đọc, hiểu rõ 5 điểm cốt lõi và sẵn sàng thực hiện thủ tục cam kết nhập học".

### Bước 3: Cổng Chặn - Hướng dẫn ký và xác nhận cam kết Nội quy
* **Ý nghĩa:** Đây là điều kiện tiên quyết mang tính pháp lý. Chỉ khi hoàn tất bước này thì giao dịch tài chính mới được phép tiến hành.
* **Phân luồng thực hiện chuẩn hóa (Đồng bộ Offline & Online):**
  * **Trường hợp A - Phụ huynh tại Cơ sở (Offline):**
    * In bản cứng Phiếu Thông Tin Nhập Học & Bản Cam Kết Tuân Thủ 17 Điều Nội Quy.
    * Hướng dẫn Phụ huynh kiểm tra thông tin của bé, ký và ghi rõ họ tên tại quầy tư vấn.
    * Chụp ảnh scan bản cam kết đã ký lưu vào hồ sơ học viên trên CRM.
  * **Trường hợp B - Phụ huynh Từ xa (Online):**
    * Gửi đường link E-Form Xác Nhận Cam Kết Nội Quy Trực Tuyến qua Zalo chính chủ của Phụ huynh.
    * Hướng dẫn Phụ huynh kiểm tra thông tin, tích chọn đồng thuận toàn bộ 17 Điều Nội quy và bấm Gửi xác nhận.
    * Kiểm tra hệ thống để bảo đảm bản ghi xác nhận (gồm Timestamp, Số điện thoại và IP) đã được lưu thành công vào hồ sơ học viên.
* **Đầu ra:** Minh chứng Cam kết hợp lệ (File scan bản ký tay HOẶC Dữ liệu log E-Form có dấu thời gian) -> ĐỦ ĐIỀU KIỆN MỞ KHÓA BƯỚC THANH TOÁN.

### Bước 4: Mở Cổng Thanh Toán & Xác nhận tài chính (Trạng thái L4A sang L5 / L4B)
* **Điều kiện kích hoạt:** Bắt buộc đã có minh chứng Cam kết hợp lệ từ Bước 3.
* **Hành động tiêu chuẩn:**
  1. Cung cấp thông tin chuyển khoản chính thức của Học viện: Tên đơn vị thụ hưởng (Công ty TNHH Công nghệ Lập trình & AI CyberSoft), Số tài khoản ngân hàng hoặc cấp Mã QR thanh toán động.
  2. Hướng dẫn Phụ huynh ghi đúng cú pháp chuyển khoản chuẩn: `[Họ Tên Bé] - [SĐT Phụ Huynh] - [Mã Khóa Học]`.
  3. Nhận ảnh chụp chứng từ giao dịch từ Phụ huynh, chuyển Kế toán đối soát sao kê tài khoản ngân hàng.
  4. Sau khi Kế toán xác nhận tiền đã vào tài khoản: Xuất Biên lai điện tử / Phiếu thu hợp lệ gửi lại ngay cho Phụ huynh qua Zalo.
* **Đầu ra:** Biên lai đóng học phí có mã giao dịch hợp lệ; cập nhật trạng thái CRM lên L5 (Đã thanh toán 100%) hoặc L4B (Đã đặt cọc giữ chỗ).

### Bước 5: Lập Handover Form bàn giao sang Giáo vụ (Trạng thái L5 sang L5.1)
* **Thời hạn SLA:** Hoàn tất trong vòng < 2 giờ làm việc kể từ khi Kế toán duyệt thu tiền thành công.
* **Hành động tiêu chuẩn:**
  1. Sales truy cập CRM, điền đầy đủ Phiếu bàn giao học viên chính thức (Handover Form) bao gồm:
     * Thông tin hành chính: Họ tên bé, ngày sinh, lớp trường phổ thông, thông tin liên lạc của Bố/Mẹ.
     * Brief học thuật: Nền tảng công nghệ, cấu hình thiết bị máy tính tại nhà (Laptop/PC), đặc điểm tâm lý, lưu ý sức khỏe/thị lực.
     * Hồ sơ chuyên môn: Đính kèm Bảng đánh giá Rubric từ buổi Trải nghiệm 60p.
     * Hồ sơ tài chính: Mã biên lai thu tiền, số tiền thực thu, mã lớp dự kiến.
     * Bằng chứng Gatekeeper (Bắt buộc): Đính kèm link ảnh scan Bản cam kết ký tay (Offline) HOẶC link log E-Form xác nhận nội quy (Online).
  2. Bấm gửi hồ sơ bàn giao sang hàng đợi tiếp nhận của Bộ phận Giáo vụ.
  3. Cập nhật trạng thái Lead trên CRM sang L5.1 (Đã bàn giao Giáo vụ).
* **Đầu ra:** Phiếu Handover Form hoàn chỉnh hiển thị trên hệ thống phòng Giáo vụ.

---

## VAI TRÒ 2: CHUYÊN VIÊN GIÁO VỤ / VẬN HÀNH LỚP HỌC (ACADEMIC OPERATIONS)

> **Mục tiêu:** Kiểm duyệt hồ sơ bàn giao, bảo đảm tính hợp lệ của cam kết nội quy, sắp xếp lớp học đúng sĩ số chuẩn (SSTT) và đồng hành chăm sóc học viên suốt khóa học.

### Bước 1: Tiếp nhận và kiểm duyệt Handover Form (Trạng thái L5.1 sang L5.2)
* **Thời hạn SLA:** Phản hồi trong vòng < 2 giờ làm việc kể từ khi nhận thông báo từ Sales.
* **Tiêu chuẩn kiểm duyệt bắt buộc (Gatekeeper Checklist):**
  * [ ] Đã có biên lai thu học phí hợp lệ do Kế toán duyệt.
  * [ ] Đã có minh chứng Phụ huynh ký cam kết nội quy (ảnh chụp bản cứng hoặc dữ liệu log E-Form).
  * [ ] Đã có đầy đủ thông tin Brief học thuật và Bảng điểm Rubric trải nghiệm.
  * *Xử lý ngoại lệ:* Nếu thiếu bất kỳ điều kiện nào, Giáo vụ bấm Từ chối tiếp nhận (Reject) trên hệ thống và yêu cầu Sales hoàn thiện trong 30 phút.

### Bước 2: Xếp lớp trên hệ thống và khởi tạo tài nguyên học tập
* Dựa trên mã khóa học và khung giờ phụ huynh đã đăng ký:
  * Phân bổ học viên vào danh sách lớp chính thức theo chuẩn danh xưng: `JUNIOR K1 - 01`, `AGENT K10 - 01` hoặc `FASTTRACK OD1 - 01`.
  * Bảo đảm sĩ số lớp tiêu chuẩn (SSTT từ 6 đến 10 học viên) để tối ưu tương tác nhóm.
  * Khởi tạo tài khoản học tập LMS và liên kết tài khoản phòng học trực tuyến (Google Meet/ClassIn).
  * Chuyển trạng thái CRM sang L5.2 (Đã xếp lớp chính thức).

### Bước 3: Đón tiếp Phụ huynh và gửi Bộ Welcome Kit
* **Thời hạn SLA:** Tối thiểu >= 24 giờ trước buổi khai giảng đầu tiên.
* **Hành động tiêu chuẩn:**
  1. Thêm Phụ huynh vào nhóm Zalo lớp chính thức (thành phần nhóm gồm: Giáo vụ quản lý, Giảng viên chính, Mentor và các Phụ huynh trong lớp).
  2. Gửi thư chào mừng trang trọng, thông báo thời khóa biểu chi tiết, số phòng học tại cơ sở hoặc đường link phòng học cố định.
  3. Đính kèm đường link văn bản 01. Nội Quy Nhập Học để Phụ huynh lưu trữ tra cứu.
  4. Nhắc nhở phụ huynh chuẩn bị máy tính, cài đặt phần mềm học tập theo hướng dẫn kỹ thuật.

### Bước 4: Giám sát chuyên cần và điều phối học bù Tutor (Theo Điều 6)
* Theo dõi sĩ số lớp học hằng ngày thông qua báo cáo điểm danh của Giảng viên.
* Tiếp nhận thông báo xin phép vắng từ Phụ huynh (yêu cầu báo trước >= 2 tiếng).
* Điều phối ca học bù Tutor 1:1 (thời lượng 30 - 60 phút/buổi, tối đa 3 buổi/khóa) để bảo đảm học viên theo kịp tiến độ dự án.

### Bước 5: Quản trị bảo lưu, chuyển lớp và theo dõi gói Combo
* **Chuyển lớp (Điều 3):** Kiểm tra điều kiện thời lượng lớp hiện tại chưa vượt quá 50% tổng số buổi trước khi giải quyết.
* **Gói Lộ trình Combo (Điều 2.3):** Theo dõi hạn chót hoàn thành gói học theo Bảng quỹ thời gian (Combo 3 khóa: 15 tháng, Combo 6 khóa: 31 tháng). Chủ động liên hệ phụ huynh sắp xếp lớp tiếp theo khi có lịch mở lớp phù hợp.

### Bước 6: Thu hồi tài khoản LMS sau bế giảng (Theo Điều 11.3)
* **Thời hạn SLA:** Đúng 07 ngày (168 giờ) sau buổi Demo Day kết thúc khóa học.
* **Hành động tiêu chuẩn:**
  1. Gửi thông báo nhắc nhở học viên tải toàn bộ mã nguồn và sản phẩm dự án về máy tính cá nhân trong vòng 7 ngày sau bế giảng.
  2. Hết thời hạn 7 ngày, hệ thống tự động khóa quyền truy cập khóa học cũ trên LMS để bảo trì tài nguyên máy chủ.

---

## VAI TRÒ 3: BỘ PHẬN GIẢNG VIÊN & TRỢ GIẢNG / MENTOR (HỌC VỤ)

> **Mục tiêu:** Bảo đảm chất lượng giảng dạy thực chiến, duy trì kỷ luật phòng học, bảo vệ sức khỏe học đường và đánh giá năng lực học viên khách quan.

### Bước 1: Tiếp nhận thông tin lớp học trước khai giảng
* Xem xét danh sách học viên, nghiên cứu kỹ Brief học thuật và kết quả Rubric trải nghiệm để nắm bắt điểm mạnh, điểm yếu và đặc điểm tâm lý của từng học sinh.
* Kiểm tra phòng máy tính, đường truyền mạng, phần mềm thực hành sẵn sàng trước giờ học 15 phút.

### Bước 2: Triển khai Quy ước lớp học trong buổi học đầu tiên
* Dành 10 - 15 phút đầu buổi khai giảng để giới thiệu bản thân và mô hình đồng hành Three-Teacher Advantage (Giảng viên - Mentor - AI Mentor).
* Thống nhất các quy ước văn hóa lớp học:
  * Đi học đúng giờ, chào hỏi Thầy Cô và các bạn.
  * Kỷ luật công nghệ (Điều 5.2): Chỉ mở ứng dụng phục vụ bài học, tuyệt đối không chơi game, lướt web, xem video ngoài luồng trong giờ học.
  * Văn hóa tôn trọng (Điều 5.3): Tuyệt đối không chê bai, trêu chọc sản phẩm code của bạn bè (chống Cyberbullying).

### Bước 3: Kiểm soát an toàn không gian mạng và thực thi chuẩn Pomodoro
* **Thực thi chuẩn Pomodoro bảo vệ thị lực:** Cứ sau mỗi 20 phút học sinh tập trung lập trình trên màn hình, Giảng viên chủ động cho lớp nghỉ 5 phút để thực hiện các động tác chớp mắt, đảo mắt nhìn xa và vận động cơ thể nhẹ nhàng.
* **Kiểm soát an toàn mạng (Điều 12):** Hướng dẫn học sinh bật chế độ SafeSearch hoặc chỉ lấy tài nguyên hình ảnh/âm thanh từ các kho mở an toàn (`kenney.nl`, `itch.io`). Quản lý nghiêm ngặt hạn mức AI API (OpenAI/Firebase), không để học sinh chia sẻ API Key ra bên ngoài.
* **Bảo quản thiết bị (Điều 13):** Không cho phép học sinh mang đồ ăn, nước uống không có nắp đậy vào phòng máy; hướng dẫn sử dụng thiết bị đúng quy trình kỹ thuật.

### Bước 4: Điểm danh và ghi nhận nhật ký học tập
* Thực hiện điểm danh trên LMS ngay đầu buổi học.
* Ghi chép nhận xét cụ thể về mức độ tiếp thu, thái độ hợp tác và tiến độ hoàn thành bài tập của từng học viên sau mỗi buổi học.

### Bước 5: Chấm điểm Dự án cuối khóa và đề xuất tốt nghiệp
* Tổ chức buổi thuyết trình Demo Day, đánh giá sản phẩm Capstone của học viên công tâm theo Bảng tiêu chí Rubric (Điều 7 & Điều 8).
* Kiểm soát tính liêm chính học thuật: Phát hiện và xử lý nghiêm các trường hợp sao chép code trên mạng hoặc nhờ người làm hộ.
* Đề xuất chính sách học lại (Điều 9): Xem xét các trường hợp học sinh chuyên cần tốt nhưng kết quả đồ án chưa đạt để đề xuất Ban Học Vụ cấp suất học lại miễn phí hoặc hỗ trợ 50% học phí.

---

## VAI TRÒ 4: TRƯỞNG BỘ PHẬN HỌC VỤ & QUẢN TRỊ CHẤT LƯỢNG

> **Mục tiêu:** Giám sát tính tuân thủ quy trình liên phòng ban, kiểm soát chất lượng đào tạo và phê duyệt giải quyết các tình huống ngoại lệ.

### Bước 1: Kiểm toán định kỳ quy trình bàn giao (Audit SOP)
* Hằng tuần rà soát ngẫu nhiên 20% hồ sơ Handover Form trên hệ thống: Bảo đảm 100% hồ sơ đều có đầy đủ minh chứng Phụ huynh đã ký cam kết 17 Điều Nội quy trước khi đóng tiền.
* Kiểm tra tỷ lệ tuân thủ SLA của các bộ phận Sales (thời gian lập Handover < 2h) và Giáo vụ (thời gian duyệt xếp lớp < 2h).

### Bước 2: Quản trị chất lượng giảng dạy và khảo sát phụ huynh
* Định kỳ dự giờ ngẫu nhiên các lớp học Offline và Online để kiểm tra việc thực thi phương pháp sư phạm tích cực, nhịp nghỉ Pomodoro và kỷ luật an toàn số.
* Theo dõi chỉ số hài lòng của Phụ huynh sau buổi Trải nghiệm và sau mỗi chặng đào tạo.

### Bước 3: Phê duyệt và xử lý các trường hợp ngoại lệ
* **Bảo lưu và hoàn phí:** Xem xét hồ sơ và phê duyệt các trường hợp bảo lưu đặc biệt quá hạn hoặc trường hợp xin hoàn phí do đi du học (Điều 2.2).
* **Xét duyệt nhảy lớp (Jump Level - Điều 4):** Chủ trì hội đồng đánh giá năng lực khi có học viên đạt điểm Capstone >= 90/100 và vượt qua bài test kiểm tra vượt cấp.
* **Tiếp nhận khiếu nại (Điều 16):** Trực tiếp chỉ đạo xử lý dứt điểm các phản ánh từ phụ huynh trong thời hạn cam kết 48 đến 72 giờ làm việc.

---

## VAI TRÒ 5: BỘ PHẬN KẾ TOÁN / THU NGÂN (FINANCE)

> **Mục tiêu:** Kiểm soát tính hợp chuẩn của chứng từ tài chính, chỉ xác nhận thu tiền khi đã có cam kết và thực hiện hoàn phí đúng quy chế.

### Bước 1: Kiểm soát điều kiện thu tiền (Gatekeeper Finance)
* Đối với thu tiền mặt tại quầy: Chỉ nhận tiền và xuất phiếu thu khi Phiếu đăng ký nhập học đã có đầy đủ chữ ký xác nhận cam kết nội quy của Phụ huynh.
* Đối với chuyển khoản: Đối soát sao kê ngân hàng khớp đúng cú pháp và số tiền quy định.

### Bước 2: Xuất biên lai hợp lệ
* Xuất Biên lai điện tử / Phiếu thu có in kèm điều khoản quy định: "Khách hàng xác nhận đã đọc, hiểu rõ và đồng ý tuân thủ toàn bộ Nội Quy Nhập Học CyberSoft Junior có hiệu lực từ ngày 01/09/2026, bao gồm chính sách không hoàn lại học phí sau khi đăng ký".

### Bước 3: Thẩm định hồ sơ hoàn phí ngoại lệ (Theo Điều 2.2)
* Tiếp nhận hồ sơ đề xuất từ Ban Học Vụ (kèm giấy tờ xác minh đi du học/định cư hoặc biên bản xác nhận lỗi từ trung tâm).
* Tính toán số tiền hoàn trả theo công thức chuẩn: Hoàn 80% học phí của các buổi học chưa diễn ra, khấu trừ các chi phí quà tặng/ưu đãi liên quan.
* Thực hiện lệnh chuyển khoản hoàn tiền cho phụ huynh trong vòng tối đa 30 ngày làm việc kể từ ngày nhận đủ hồ sơ hợp lệ.

---

## VAI TRÒ 6: BỘ PHẬN IT & QUẢN TRỊ HỆ THỐNG LMS (TECHNICAL SUPPORT)

> **Mục tiêu:** Thiết lập hàng rào kỹ thuật (Technical Gatekeeper) trên Landing Page và tự động hóa quy trình quản trị tài khoản học tập.

### Bước 1: Cấu hình Cổng xác nhận cam kết trên hệ thống đăng ký
* Xây dựng giao diện Form đăng ký trực tuyến: Tích hợp hộp tóm tắt 5 Điểm cốt lõi và ô tick cam kết bắt buộc.
* Cài đặt logic chặn: Mã VietQR hoặc thông tin tài khoản ngân hàng chỉ hiển thị sau khi người dùng đã tích chọn đồng ý cam kết và bấm nút xác nhận.
* Lưu trữ tự động dữ liệu xác nhận (gồm Họ tên, Số điện thoại, Timestamp và Địa chỉ IP) vào cơ sở dữ liệu để phục vụ đối soát.

### Bước 2: Tự động hóa quy trình thu hồi tài khoản (LMS Auto-Revoke)
* Cấu hình hệ thống LMS tự động đếm ngược 07 ngày (168 giờ) kể từ ngày bế giảng chính thức của từng lớp.
* Hết thời hạn 7 ngày, hệ thống tự động khóa quyền truy cập khóa học của học viên theo đúng quy định tại Điều 11.3.

---

## PHẦN 7: MA TRẬN PHỐI HỢP & XỬ LÝ SỰ CỐ TRANH CHẤP NGOẠI LỆ

| Tình huống phát sinh | Bộ phận chủ trì | Bộ phận phối hợp | Hành động tiêu chuẩn & Căn cứ xử lý |
| :--- | :---: | :---: | :--- |
| **Phụ huynh không đồng ý quy định Không hoàn phí** | **Sales** | Quản lý Học vụ | Giải thích nguyên tắc bảo đảm sĩ số chuẩn và chi phí phòng máy cố định. Nếu Phụ huynh vẫn không đồng ý, **tuyệt đối không thu tiền**, hướng dẫn đăng ký khóa ngắn hạn hoặc dừng tiếp nhận. |
| **Phụ huynh tự chuyển khoản trước khi ký cam kết** | **Sales** | Kế toán | Kế toán tạm giữ tiền ở trạng thái chờ đối soát. Sales liên hệ ngay hướng dẫn Phụ huynh ký bổ sung bản cam kết để làm căn cứ xuất biên lai và xếp lớp. |
| **Học viên vi phạm kỷ luật, trêu chọc bạn trong lớp** | **Giảng viên** | Giáo vụ | Áp dụng quy trình kỷ luật 3 bước (Điều 5.3): Nhắc nhở riêng lần 1 -> Lập biên bản báo Phụ huynh lần 2 -> Buộc thôi học không hoàn phí lần 3 nếu tái phạm nghiêm trọng. |
| **Phụ huynh thắc mắc tài khoản LMS bị khóa sau 7 ngày bế giảng** | **Giáo vụ** | IT Support | Giáo vụ gửi lại trích dẫn Điều 11.3 trong bản cam kết Phụ huynh đã xác nhận. Giải thích quy định bảo trì hệ thống và tư vấn lộ trình học tiếp theo. |
| **Nhờ người lạ hoặc xe công nghệ (Grab/Be) đến đón trẻ** | **Giáo vụ** | Bảo vệ cơ sở | Đối chiếu thông tin ủy quyền của Phụ huynh trên nhóm Zalo lớp (tên tài xế, biển số xe) theo Điều 17.2. Nếu không có thông báo trước, giữ trẻ tại sảnh và gọi điện xác minh trực tiếp với cha mẹ. |

---

## PHỤ LỤC: MẪU PHIẾU BÀN GIAO HỌC VIÊN CHÍNH THỨC (HANDOVER FORM MẪU)

```text
================================================================================
            CYBERSOFT JUNIOR - PHIẾU BÀN GIAO HỌC VIÊN CHÍNH THỨC
                         (SALES SANG GIÁO VỤ & VẬN HÀNH)
================================================================================

[PHẦN 1: THÔNG TIN HÀNH CHÍNH]
- Mã Lead / Mã Học Viên: LD-2026-..........
- Họ và tên học viên: ................................. Độ tuổi: ...... Lớp trường: ......
- Họ và tên Phụ huynh: ................................. Số điện thoại Zalo: ................
- Email nhận tài liệu/LMS: .............................................................

[PHẦN 2: BRIEF HỌC THUẬT CHUYÊN SÂU]
- Nền tảng công nghệ của bé: [ ] Chưa từng học  [ ] Đã học Scratch  [ ] Đã học Python
- Thiết bị học tại nhà: [ ] PC để bàn   [ ] Laptop cá nhân   (HĐH: Windows / MacOS)
- Đặc điểm tính cách: [ ] Hướng ngoại, năng động   [ ] Nhút nhát, cần động viên nhiều
- Ghi chú sức khỏe/thị lực: ............................................................

[PHẦN 3: KẾT QUẢ ĐÁNH GIÁ TRẢI NGHIỆM 60 PHÚT (RUBRIC)]
- Điểm đánh giá tư duy logic: ....../10  |  Kỹ năng thao tác máy: ....../10
- Đánh giá của Giảng viên trải nghiệm: .................................................
- Sản phẩm mini bé đã hoàn thành: .....................................................

[PHẦN 4: THÔNG TIN KHÓA HỌC & TÀI CHÍNH]
- Khóa học đăng ký: [ ] Tầng 1 Cadet   [ ] Tầng 2 Agent   [ ] Tầng đệm Overdrive
- Hình thức học: [ ] Offline tại cơ sở ...................   [ ] Online qua Google Meet
- Tình trạng học phí: [ ] Đã thanh toán 100%   [ ] Đã cọc giữ chỗ (Hạn nộp nốt: ...)
- Mã biên lai / Giao dịch Kế toán: ....................................................

[PHẦN 5: MINH CHỨNG CAM KẾT NỘI QUY (BẮT BUỘC)]
- Hình thức cam kết: [ ] Bản cứng ký tay tại quầy   [ ] Xác nhận E-Form điện tử
- Link hình ảnh scan cam kết / Link log Form: ..........................................
--------------------------------------------------------------------------------
Nhân viên Sales bàn giao: ...........................  Thời gian: .../.../2026
Giáo vụ duyệt tiếp nhận: ............................  Thời gian: .../.../2026
================================================================================
```