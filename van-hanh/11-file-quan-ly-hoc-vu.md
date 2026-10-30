# FILE QUẢN LÝ HỌC VỤ (EXCEL TẠM THAY LMS)

> **TÀI LIỆU NỘI BỘ.** Căn cứ: `02-huong-dan-thuc-hien.md` (Mục 0.3, 0.4). Trang này là **bản thiết kế**; tạo file thật là một bước riêng.

---

## 1. Nguyên tắc

- **LMS là bản chính thức.** Khi LMS chưa vận hành đầy đủ, cập nhật Excel quản lý trước, LMS sau; hai bên phải khớp (Mục 0.3).
- **Một file cho toàn bộ lớp đang chạy**, do tài khoản của trung tâm sở hữu; phân quyền chỉnh sửa theo vai trò, giáo viên chỉ xem phần lớp mình.
- **Một khóa của một học viên là một dòng.** Học viên học khóa mới thì thêm dòng mới, không sửa dòng cũ.
- **Mã lớp khớp tuyệt đối** giữa Excel, LMS, nhóm Zalo và thư mục Drive.
- **Ngày khai giảng chỉ nhập ở sheet Lớp.** Lịch các buổi tự tính từ đó.
- **Không gõ vào cột có công thức.** Khi chép dữ liệu, dán dạng giá trị.
- **Không xóa dòng.** Đổi trạng thái; biến động ghi ở sheet riêng.
- **Dữ liệu cá nhân:** không chia sẻ file ra ngoài trung tâm; không chụp màn hình gửi vào nhóm Zalo.

## 2. Các sheet

| # | Sheet | Mục đích | Ai cập nhật | Khi nào |
| --- | --- | --- | --- | --- |
| 1 | Lớp | Danh sách lớp và trạng thái | Giáo vụ | Khi mở lớp, đổi trạng thái |
| 2 | Lịch học | Ngày của từng buổi, tự tính | Giáo vụ (chỉ chỉnh buổi bị dời) | Khi dời buổi, nghỉ lễ |
| 3 | Học viên | Mỗi khóa của học viên một dòng, trạng thái hiện tại | Giáo vụ | Khi nhận bàn giao, khi đổi trạng thái |
| 4 | Điểm danh & bài tập | Có mặt, vắng, nộp bài từng buổi | Giáo vụ (giáo viên hỗ trợ) | Trong ngày học |
| 5 | Học bù | Theo dõi bù bài | Giáo vụ | Khi có buổi vắng, khi bù xong |
| 6 | Biến động | Nhật ký chuyển lớp, bảo lưu, chuyển nhượng, rút đăng ký, hoàn phí, nghỉ ngang | Giáo vụ | Khi có quyết định |
| 7 | Bảo lưu | Theo dõi hạn bảo lưu | Giáo vụ | Khi duyệt bảo lưu; ngày 5 hằng tháng |
| 8 | Chờ lên khóa | Học viên đã xong khóa, chờ lớp tiếp theo | Giáo vụ | Sau Demo Day; khi xếp được lớp |
| 9 | Chăm sóc | Nhật ký chăm sóc Phụ huynh và học viên | Giáo vụ | Mỗi lần liên hệ |
| 10 | Phản ánh | Theo dõi phản ánh đến khi đóng | Giáo vụ | Mỗi phản ánh |
| 11 | Vật phẩm | Xuất, hoàn, tồn chứng nhận và quà | Giáo vụ | Mỗi lần xuất, cuối tháng |
| 12 | Báo cáo | Chỉ số tổng hợp, chỉ xem | Tự tính | Xem thứ Hai hằng tuần |
| 13 | Danh mục | Danh sách giá trị cho ô chọn (trạng thái, hình thức, loại biến động...) | Trưởng phòng Học vụ | Khi đổi quy định |

## 3. Cột chính của từng sheet

**1. Lớp:** Mã lớp · Khóa · Tầng · Hình thức · Khung giờ · Phòng / Link Meet · Giáo viên chính · Mentor · Ngày khai giảng · Số buổi · Ngày Demo dự kiến (tự tính) · Trạng thái lớp · Sĩ số (tự đếm từ sheet Học viên) · Link thư mục lớp · Link nhóm Zalo · Ghi chú.

**2. Lịch học:** Mã lớp · Buổi 1 … Buổi N. Mặc định buổi sau = buổi trước + 7 ngày (theo tần suất học của lớp). Mỗi buổi có ô điều chỉnh: nhập số tuần dời thì các buổi sau tự dời theo (`02-huong-dan-thuc-hien.md`, Vai trò 2, Bước 7). Tô màu sẵn buổi Capstone, buổi nghiệm thu, Demo Day.

**3. Học viên:** Mã học viên · Họ tên · Ngày sinh · Họ tên Phụ huynh · SĐT Zalo · Mã lớp · Khóa · Hình thức của học viên · Gói (khóa lẻ / Combo n khóa) · Hạn hoàn thành Combo · Trạng thái học phí · Hạn đóng đủ · Ngày bàn giao · Ngày vào lớp · Số ngày chờ (tự tính) · Trạng thái học viên · Ghi chú.

**4. Điểm danh & bài tập:** Mã học viên · Mã lớp · từng mã buổi: Có mặt / Muộn / Vắng có lý do / Vắng không lý do; Nộp bài (thời điểm nộp) · Tỷ lệ chuyên cần (tự tính) · Tỷ lệ nộp bài (tự tính).

**5. Học bù:** Mã học viên · Mã lớp · Mã buổi vắng · Ngày vắng · Loại vắng · Phương án (bù nhóm / học ghép / bản ghi) · Ngày bù · Người dạy bù · Thời lượng · Số buổi bù đã dùng trong khóa (tối đa 03) · Kết quả · Trạng thái (Đúng hạn / Trễ hạn, tự tính theo SLA-34).

**6. Biến động:** Ngày · Mã học viên · Loại biến động · Lớp cũ · Lớp mới · Số buổi đã học · Giá trị liên quan · Người duyệt · Ngày duyệt · Link hồ sơ · Ghi chú.

**7. Bảo lưu:** Mã học viên · Khóa · Số buổi còn lại · Ngày bắt đầu · Hạn bảo lưu (tối đa 06 tháng) · Màu cảnh báo (xanh: còn hạn; vàng: còn dưới 30 ngày; đỏ: quá hạn) · Lần liên hệ gần nhất · Kết quả.

**8. Chờ lên khóa:** Mã học viên · Khóa vừa xong · Khóa tiếp theo · Học phí (đã đóng / Combo / chưa đóng) · Ngày kết thúc khóa · Số ngày chờ (tự tính; vàng khi trên 14 ngày, đỏ khi trên 30 ngày) · Lớp mới · Ngày vào lớp mới · Trạng thái (Đang chờ / Đã vào lớp / Ngừng học).

**9. Chăm sóc:** Ngày · Mã học viên · Mã lớp · Mốc (1 – 6 / chờ lớp / bảo lưu / cảnh báo sớm / vấn đề) · Kênh · Liên hệ Phụ huynh (có / không) · Trao đổi học viên (có / không) · Nội dung · Vấn đề · Việc tiếp theo · Hạn · Trạng thái.

**10. Phản ánh:** Mã phản ánh · Ngày giờ nhận · Kênh · Mã học viên / lớp · Loại · Mức (P0 – P3) · Mô tả · Người xử lý · Phương án 1 · Phương án 2 · Hẹn trả lời · Kết quả · Ngày đóng · Phụ huynh xác nhận.

**11. Vật phẩm:** Ngày · Loại · Lớp · Số lượng xuất · Danh sách học viên nhận · Số lượng hoàn kho · Tồn sau giao dịch · Người thực hiện.

**12. Báo cáo** (so sánh tuần này với tuần trước): số lớp đang chạy · sĩ số · chuyên cần · tỷ lệ nộp bài · học bù đúng hạn · học viên chờ lớp và số ngày chờ trung bình · học viên sắp hết hạn bảo lưu · phản ánh đang mở · tỷ lệ hoàn thành khóa · tái tục.

## 4. Lọc danh sách chăm sóc theo mốc

Từ sheet Lịch học, một bảng lọc tự liệt kê lớp có buổi rơi vào mốc chăm sóc trong khoảng ngày chọn (sau buổi 1, sau Capstone 1, sau Capstone 2, buổi nghiệm thu, Demo Day). Giáo vụ dùng bảng này mỗi sáng để biết hôm nay cần chăm sóc lớp nào. Sheet Lịch học phải cập nhật đúng thì bảng lọc mới đúng.

## 5. Khi LMS vận hành

Các sheet 1 – 5 chuyển dần sang LMS. Các sheet 6 – 11 giữ trên Excel cho đến khi LMS có chức năng tương ứng. Mỗi lần chuyển, Trưởng phòng Học vụ thông báo ngày bắt đầu dùng LMS làm nơi nhập duy nhất.
