# Chiếu Sáng Trong Thị Giác Máy Công Nghiệp

Ánh sáng đóng vai trò trung tâm trong xử lý ảnh công nghiệp: **Không phải bản thân đối tượng được kiểm tra, mà chỉ là hình ảnh thị giác của đối tượng đó!** Điều này có nghĩa là chỉ điều kiện chiếu sáng đồng nhất mới tạo ra hình ảnh nhất quán của cùng một đối tượng.

> [!IMPORTANT]
> Điều kiện chiếu sáng dao động cần phải được tránh bằng mọi giá!

## Mục tiêu

- Chỉ khi các đặc tính kiểm tra mong muốn hoặc khuyết tật có thể được hiển thị với độ tương phản đủ lớn thì chúng mới có thể được xử lý bởi phần mềm xử lý ảnh.
- Thông thường đối tượng được chiếu sáng bởi nguồn sáng bên ngoài. Nguyên tắc này nghe rất đơn giản, nhưng trong thực tế nó lại là một trong những khó khăn chính trong thị giác máy công nghiệp để làm cho khuyết tật trên đối tượng hiển thị được với camera.

## Các Kỹ Thuật Chiếu Sáng Cơ Bản

### Chiếu sáng phản xạ trực tiếp (Direct Frontlight)

Bề mặt một phần rất sáng nhưng bị quá sáng, một phần tối do phản xạ toàn phần.

### Chiếu sáng khuếch tán dạng vòm (Diffuse Dome Light)

Bề mặt được chiếu sáng mượt mà nhờ ánh sáng tới đồng nhất.

### Chiếu sáng trường tối (Dark Field)

Các cạnh bên rất sáng. Vết xước và bụi có thể nhìn thấy được.

### Chiếu sáng nền (Backlight)

Chi tiết xuất hiện dưới dạng bóng đen. Không có thông tin bề mặt, đường viền lý tưởng cho ứng dụng đo lường.

---

## Ví Dụ Minh Họa Độ Khó

1. **Chai thủy tinh trong suốt**: Hãy tưởng tượng một chai thủy tinh trong suốt, với văn bản dập nổi ở đáy cần phải đọc được. Đối tượng kiểm tra và các đặc tính đều được làm từ cùng một vật liệu, và hơn nữa, chúng đều trong suốt! Điều tương tự áp dụng cho nhiều chữ dập nổi trên bề mặt vật liệu phẳng.

2. **Vết xước trên bề mặt kim loại**: Vết xước trên bề mặt kim loại thường không tạo ra thay đổi gì khác ngoài một vết khía cần được phát hiện. Một lần nữa, đây là tình huống kiểm tra trong đó khuyết tật phải được phát hiện mặc dù cùng vật liệu. Dập nổi và đúc khuôn trong vật liệu tương tự.

### So sánh kỹ thuật chiếu sáng

| Kỹ thuật | Hiệu ứng |
|----------|----------|
| Ánh sáng khuếch tán | Tạo bề mặt mờ với độ tương phản thấp của chữ dập |
| Trường tối | Chiếu sáng góc thấp làm nổi bật các cạnh và chữ lõm |

---

## Bức Xạ Điện Từ Tương Tác Với Vật Thể

Vai trò chính được thể hiện bởi ánh sáng và sự tương tác của nó trong chuỗi hiệu ứng giữa chiếu sáng, đối tượng kiểm tra và camera.

Vì các tính chất vật lý của đối tượng kiểm tra không thể bị ảnh hưởng, hoặc chỉ có thể bị ảnh hưởng ở mức độ hạn chế, **đối tượng quyết định chiếu sáng và camera!** Camera lại xác định quang học với khoảng cách làm việc và ren kết nối, định dạng dữ liệu và tốc độ dữ liệu cũng quyết định bản đồ thu nhận hình ảnh.

> [!TIP]
> Rất đáng để xem xét kỹ hơn về ánh sáng và cách nó tương tác với vật liệu và camera!

---

## Các Yếu Tố Chính Ảnh Hưởng Đến Hình Ảnh

### Ánh sáng
- **Bước sóng** (màu sắc)
- **Trực tiếp / khuếch tán**
- **Phân cực / không phân cực**
- **Góc chiếu**

### Đối tượng kiểm tra
- **Vật liệu**
- **Bề mặt, cấu trúc**
- **Hình học**
- **Màu sắc**

### Camera
- **Độ phân giải**
- **Cảm biến đơn sắc / màu**
- **Dải động và độ nhạy**
