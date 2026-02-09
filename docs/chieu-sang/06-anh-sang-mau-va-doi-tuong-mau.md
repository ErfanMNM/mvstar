# Ánh Sáng Màu và Đối Tượng Màu

## Pha Trộn Màu Cộng - Trộn Ánh Sáng Màu

Nếu bạn chiếu sáng một bề mặt trên tường bằng ba nguồn sáng: một điểm **đỏ**, một **xanh lá** và một **xanh dương**, bạn sẽ có được **ánh sáng trắng** trong vùng chồng chéo của các điểm sáng.

Điều này cũng có thể được giải thích bằng phổ của các LED màu: Nếu bạn kết hợp các phổ xanh dương, xanh lá và đỏ, bạn sẽ có được phổ khá hoàn chỉnh của tất cả các bước sóng - đó là ánh sáng trắng.

> [!NOTE]
> Nguyên tắc pha trộn ánh sáng này được gọi là **mô hình RGB** (mọi màn hình hoạt động theo nguyên tắc này). Chúng ta gọi đây là **màu ánh sáng**.

---

## Sử Dụng LED Màu

Tất cả các loại ánh sáng màu có thể được sử dụng cho chiếu sáng. Tuy nhiên, trong xử lý ảnh công nghiệp, việc sử dụng đèn LED đã trở nên phổ biến.

**Ưu điểm thực tế:**
- Phổ phát xạ thường khá hẹp
- Các dải bước sóng lân cận có thể bị chặn rất tốt bởi bộ lọc
- Ngược lại cũng quan trọng: Bộ lọc cho phép ánh sáng màu đi qua và chặn bất kỳ ánh sáng ngoại lai nào có thể gây nhiễu

---

## Pha Trộn Màu Trừ - Màu và Thuốc Nhuộm Trong Đối Tượng

Các chi tiết cần kiểm tra thường có màu. Thành phần được tạo màu bằng sắc tố hoặc thuốc nhuộm.

Ngoài các bộ lọc màu có thể vặn vào ống kính camera, mực in cũng hoạt động theo nguyên tắc này:
- Trộn **vàng và đỏ tươi** → **đỏ**
- Trộn **đỏ tươi và lục lam** → **xanh dương**
- Và cứ thế tiếp tục...

Vật thể không phản xạ tất cả ánh sáng tới, mà trừ đi một phần. Đây được gọi là **màu vật thể**.

> [!NOTE]
> Mô hình màu được gọi là **mô hình CMY(K)** theo các màu cyan, magenta và yellow. (Màu K=Key đại diện cho đen, cần phải thêm vào khi in để có được màu rất tối và tông đen.)

---

## Ánh Sáng Màu và Đối Tượng Màu

Trong xử lý ảnh công nghiệp, cả hai hiệu ứng được kết hợp. Với chiếu sáng màu, **màu vật thể bổ sung có thể được làm tối** và **cùng màu vật thể có thể được làm sáng**.

### Ví dụ 1: Làm sáng bản in đỏ

Một bản in đỏ hấp thụ gần như tất cả các màu trừ đỏ khi được chiếu sáng bằng ánh sáng trắng. Nó phản xạ chúng trở lại người xem.

**Nếu sử dụng chiếu sáng đỏ**: Không có ánh sáng đỏ nào bị hấp thụ, tức là gần như toàn bộ lượng ánh sáng được phản xạ đến camera. **Bản in đỏ xuất hiện rất sáng.**

### Ví dụ 2: Làm tối bản in đỏ

Một bản in đỏ hấp thụ gần như tất cả các màu trừ đỏ khi được chiếu sáng bằng ánh sáng trắng. Nó phản xạ chúng trở lại người xem.

**Nếu sử dụng chiếu sáng xanh lá**: Gần như toàn bộ lượng ánh sáng bị hấp thụ bởi màu in đỏ. **Bản in đỏ xuất hiện rất tối.**

### Ví dụ 3: Kim loại và hợp kim

Hai kim loại trong bảng tuần hoàn và một số hợp kim có màu:
- **Vàng và các vật thể màu vàng** (ví dụ: đồng thau) có thể xuất hiện tối hơn khi sử dụng ánh sáng xanh dương và có thể phân biệt với các kim loại màu bạc khác
- **Đồng** có thể được làm tối hơn bằng ánh sáng xanh lá hoặc xanh dương theo nguyên tắc pha trộn màu trừ

---

## So Sánh Hiệu Ứng Các Loại LED

| Loại LED | Hiệu ứng trên ảnh |
|----------|------------------|
| **Ánh sáng ban ngày** | Tông xám bình thường. Màu sáng xuất hiện sáng, màu tối bình thường tối |
| **LED trắng** | Tông xám bình thường. Màu sáng xuất hiện sáng, màu tối bình thường tối |
| **LED xanh dương** | Logo xanh (góc trên bên trái) sáng hơn nhiều, tất cả tông vàng, cam và đỏ trở nên tối |
| **LED xanh lá** | Vùng đỏ xung quanh logo bị tối hơn nhiều, tông vàng-cam xám trung bình |
| **LED đỏ** | Vùng đỏ và cam gần như trắng, logo xanh và xanh lá xuất hiện rất tối |
| **LED hồng ngoại** | Ngoại trừ logo xanh lá với tỷ lệ đen cao, hầu hết mọi thứ biến mất |

---

## Bảng Hướng Dẫn Chọn Màu Ánh Sáng

| Mục tiêu | Màu ánh sáng khuyến nghị |
|----------|-------------------------|
| Làm sáng đối tượng đỏ | LED đỏ |
| Làm tối đối tượng đỏ | LED xanh lá hoặc xanh dương |
| Làm sáng đối tượng xanh lá | LED xanh lá |
| Làm tối đối tượng xanh lá | LED đỏ |
| Phân biệt vàng/bạc | LED xanh dương |
| Xuyên qua bao bì màu | LED hồng ngoại |
