# Các Loại Chiếu Sáng

## "Trắng" Không Giống "Trắng"

Ngay cả ánh sáng 'trắng' cũng có thể được tạo ra theo nhiều cách khác nhau. Tùy thuộc vào vấn đề, yêu cầu chiếu sáng, kích thước đối tượng và kích thước lắp đặt, các loại sau được sử dụng:

| Loại | Đặc điểm chính |
|------|---------------|
| **Đèn LED** | Tuổi thọ dài, bền cơ học, có thể đặt trong gần như bất kỳ hình dạng vỏ nào |
| **Đèn halogen sợi đốt** | Phổ liên tục với phân bố cường độ dạng chuông |
| **Đèn huỳnh quang** (tần số cao) | Phát ra trong các dải bước sóng cụ thể |

### Đèn LED - Vai trò đặc biệt

Đèn LED đóng vai trò đặc biệt trong xử lý ảnh. Các đặc tính như tuổi thọ dài, độ bền cơ học và khả năng được đặt trong hầu hết mọi hình dạng vỏ khiến chúng lý tưởng để sử dụng.

Màu sáng có thể là:
- Trắng
- Đỏ, Xanh lá, Xanh dương
- Hồng ngoại
- Cực tím

> [!TIP]
> Điều này giúp giải quyết các ứng dụng mà không thể thực hiện được với các loại chiếu sáng khác.

---

## Khái Niệm Nhiệt Độ Màu

Không phải mọi nguồn sáng trắng đều có cùng sắc thái trắng với người xem. Với các hệ thống camera màu (và đơn sắc), cũng có thể thấy các hiệu ứng màu trong ảnh hoặc dịch chuyển đáng kể trong giá trị xám.

### Nguồn gốc thuật ngữ

Nhiệt độ màu được đo và báo cáo theo đơn vị Kelvin (K) và là thước đo màu sắc biểu kiến của nguồn sáng. Phổ mà mắt người có thể nhìn thấy nằm trong khoảng **2,790 đến 11,000 Kelvin**.

Giải thích vật lý dựa trên định nghĩa của Max Planck về 'vật đen':
- Vật đen hấp thụ tất cả bức xạ tới và không phản xạ gì
- Nhiệt độ màu là nhiệt độ của vật đen mà tại đó phát xạ ánh sáng tạo ra cùng ấn tượng màu như chiếu sáng thực tế
- **Vật đen ở 5500K** có phổ bức xạ gần với ánh sáng ban ngày

### So sánh các nguồn sáng

| Nguồn sáng | Hiệu ứng trên ảnh |
|------------|------------------|
| **Ánh sáng ban ngày** | Màu bình thường như mắt người nhìn thấy. Vùng tham chiếu trắng xuất hiện xám nhạt |
| **LED trắng** | Logo xanh sáng hơn, ảnh có hiệu ứng màu lạnh tổng thể do ánh xanh |
| **Đèn huỳnh quang trắng** | Bề mặt tham chiếu trắng xuất hiện vàng-xanh lá, tông xanh lá sáng nhẹ hơn |
| **Đèn halogen** (không có bộ lọc cắt IR) | Bề mặt tham chiếu trắng xuất hiện cam-đỏ, ảnh hoàn toàn đổi màu |

---

## Quan Trọng Cho Thị Giác Máy

> [!WARNING]
> Tùy thuộc vào chiếu sáng 'trắng' được sử dụng, ảnh camera sẽ có màu ít nhiều khác nhau:
> - **LED trắng** xuất hiện rất xanh dương
> - Ảnh từ **đèn huỳnh quang** xuất hiện xanh lá
> - **Đèn halogen** tạo ấn tượng màu rất vàng do thành phần đỏ và hồng ngoại tăng

### Các lưu ý quan trọng:

1. **Ánh sáng ngoại lai và ánh sáng ban ngày** thay đổi lớn đặc tính của ánh sáng màu và cần tránh trong các ứng dụng màu. **Che chắn vùng kiểm tra!**

2. **Độ nhạy cảm biến camera** không giống nhau cho các màu khác nhau. Các hiệu ứng méo bổ sung xảy ra.

3. **Cân bằng trắng** có thể sửa các thành phần màu RGB không đồng nhất - thực hiện trong camera, trên frame grabber hoặc bằng phần mềm trên PC.

4. **Quá trình lão hóa**: Nhiệt độ màu của chiếu sáng dịch chuyển theo thời gian:
   - Đèn halogen phát sáng tối hơn (nhiều thành phần đỏ hơn)
   - Chất huỳnh quang trong LED trắng bị phá hủy (phát xạ xanh gốc trở nên nổi bật hơn)
   - **Cần hiệu chuẩn định kỳ!**

5. **Lỗi quang học**: Sắc sai dọc và ngang có thể được bù bằng quang học chất lượng cao để tránh viền màu hoặc xám.

6. **Giải pháp đơn giản** với camera đơn sắc: Sử dụng ánh sáng đơn sắc (xanh, xanh lá, đỏ, v.v.) như đèn LED tạo ra. Kết quả là hình ảnh có độ tương phản cao hơn.
