# Chiếu Sáng Tia Cực Tím (UV)

## Tổng Quan

Một tùy chọn khác để làm nổi bật các đặc điểm là sử dụng **bức xạ cực tím**, có bước sóng từ **10 đến 400nm**.

Sử dụng đèn huỳnh quang ('đèn đen') hoặc LED cực tím, khá dễ dàng để tạo ra bức xạ UV với bước sóng **365nm** trong dải **'UV-A gần'**.

> [!CAUTION]
> Vui lòng kiểm tra **an toàn quang sinh học** của chiếu sáng UV. Vì mắt người không còn phát hiện được bức xạ UV, không có phản xạ đóng mí mắt. Do đó, LED UV thường không còn ở Cấp Rủi Ro LED 1, mà ở Cấp Rủi Ro LED 2. **Che chắn, bao bọc và dán nhãn là bắt buộc.**

---

## Phần Cứng Cho Kiểm Tra UV

### Dải UV-A
- Ngay cả trong dải UV-A này, ống kính tiêu chuẩn hấp thụ một tỷ lệ lớn ánh sáng được phát ra
- Điều này cũng áp dụng cho quang học hệ thống camera tiêu chuẩn, kính lọc và thậm chí cả kính bảo vệ trên cảm biến
- Tuy nhiên, nhiều ứng dụng có thể được giải quyết với các thành phần tiêu chuẩn, vì kích thích bằng bức xạ UV gây ra **huỳnh quang trong vùng nhìn thấy** ở một số vật liệu

### Ứng dụng UV thực sự (bước sóng ngắn hơn)
- Cần quang học đặc biệt, ví dụ: làm từ **kính thạch anh**
- Cần cảm biến camera đặc biệt với đầu dò phù hợp
- Cảm biến CMOS thường chỉ nhạy UV đến 370nm

### Giải pháp mới
Cảm biến **'Pregius S IMX 487'** của SONY:
- 8 megapixel (2.74µm, 193 fps)
- Độ nhạy: **200 đến khoảng 1000nm**
- Có trong danh mục sản phẩm của nhiều nhà sản xuất camera

---

## Tại Sao Sử Dụng Bức Xạ UV?

Bức xạ bước sóng ngắn có xu hướng **phản xạ mạnh hơn** bức xạ bước sóng dài vì dao động bước sóng ngắn gây ra tương tác mạnh ngay cả ở độ xuyên thấp vào vật liệu.

**Ưu điểm:**
- Lý tưởng cho **kiểm tra bề mặt**
- Các đặc điểm nhỏ, bụi và vết xước đặc biệt rõ ràng
- Nhiều ứng dụng trong đó vật liệu được làm **phát sáng trong vùng nhìn thấy** bởi bức xạ UV

---

## Các Khả Năng Kiểm Tra Điển Hình

| Ứng dụng | Mô tả |
|----------|-------|
| **Kiểm tra PCB và mối hàn** | Độ phản xạ cao là lợi thế. Khuyết tật, vết xước hoặc đặc điểm rõ ràng có thể nhìn thấy |
| **Kiểm tra cáp sợi quang** | Bước sóng ngắn cho phép kiểm tra bề mặt cắt vì nó phản xạ cao và không chỉ được chiếu sáng khuếch tán |
| **Keo dán trong suốt** | Keo, chất bịt kín, v.v. hoạt động UV: Khi kích thích bằng tia cực tím, chúng thường tạo ra huỳnh quang xanh dương hoặc xanh lá trong dải bước sóng nhìn thấy |
| **Mực và thuốc nhuộm UV** | Bản in và tính năng bảo mật (thẻ tín dụng, tiền giấy, tem hộ chiếu, v.v.) có thể được kích thích, phát hiện và phân tích |
| **Hóa sinh** | Đánh dấu hóa học được gắn vào trình tự gene, protein, v.v., để quan sát và hiển thị bằng bức xạ UV |

---

## Quan Trọng Cho Thị Giác Máy

> [!CAUTION]
> Bức xạ UV không nhìn thấy được bằng mắt người. Do năng lượng cao, bức xạ UV bước sóng ngắn đặc biệt có thể dễ dàng gây hại cho **mắt, da và vật liệu**.
> 
> Các ứng dụng công nghiệp sử dụng bức xạ UV có thể yêu cầu các biện pháp an toàn tương tự như laser (**Cấp An Toàn Laser 3B**) nếu vượt quá mức năng lượng nhất định.
> 
> **Có thể cần**: Vùng an toàn, giới hạn chùm tia, tắt khi mở cửa an toàn, nhân viên an toàn trong công ty.

### Các lưu ý quan trọng:

1. **Xung nhịp đèn LED UV** nếu có thể. Điều này tránh phát xạ ánh sáng không cần thiết và mức năng lượng quan trọng dẫn đến cấp bảo vệ cao.

2. Đèn LED UV (rất đắt: LED đế kim loại với vỏ kính thạch anh!) nếu không sẽ thường **trở nên rất nóng và hỏng sớm**.

3. Sử dụng **bộ lọc bandpass băng hẹp** ngăn ảnh hưởng ánh sáng gây nhiễu từ ánh sáng ban ngày. Những bộ lọc này nên được khớp chính xác với huỳnh quang.
