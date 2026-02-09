# Chiếu Sáng Hồng Ngoại (IR)

## Tổng Quan

Dải bước sóng từ khoảng **780nm đến 1mm** (tức 1,000,000nm) được gọi là **bức xạ hồng ngoại** (giáp với dải bức xạ terahertz hiện đang được thảo luận nhiều, được sử dụng trong các "máy quét cơ thể").

Bức xạ IR thường được gọi là **bức xạ nhiệt**. Tuy nhiên, trong xử lý ảnh công nghiệp, hầu hết các ứng dụng nằm trong **vùng hồng ngoại gần**, bao gồm dải phổ từ **780 đến 3000nm**.

---

## Phần Cứng Cho Kiểm Tra IR

### Dải 780-1000nm
- Có thể kiểm tra với camera CMOS đơn sắc thông thường
- Độ nhạy giảm dần ở bước sóng này, nhưng về nguyên tắc là đủ

### Dải IR bước sóng dài hơn
- Cần cảm biến làm mát Peltier và vật liệu bán dẫn đặc biệt (InGaAs)
- Camera cho phân tích IR trung được gọi là **camera ảnh nhiệt**
- Quang học không còn làm từ kính thường, mà từ vật liệu như **germanium**

### Giải pháp thay thế tốt
Họ cảm biến **SenSWIR của Sony** (IMX 990 / IMX991 / IMX992 / IMX 993):
- Độ nhạy: 400-1700nm
- Độ phân giải: Lên đến 5 megapixel

> [!TIP]
> Cho các ứng dụng IR đơn giản với camera 'tiêu chuẩn', **LED 870nm hoặc 950nm** được ưu tiên. Bước sóng dài hơn dự kiến giảm tán xạ bề mặt và do đó cải thiện chiếu sáng mục tiêu.

---

## Tại Sao Sử Dụng Bức Xạ Hồng Ngoại?

Bức xạ bước sóng dài hơn là **bức xạ điện từ** và do đó dao động ít thường xuyên hơn bức xạ bước sóng ngắn, tạo ra ít tương tác với vật liệu hơn.

**Ưu điểm:**
- Có khả năng xuyên sâu hơn vào vật liệu
- Tạo ra ít phản xạ bề mặt hơn ánh sáng bước sóng ngắn
- Đôi khi thậm chí có thể nhìn xuyên qua một đối tượng
- Không nhìn thấy được bằng mắt người → phù hợp cho nơi làm việc mà ánh sáng thường gây phiền hà

---

## Các Khả Năng Kiểm Tra Điển Hình

| Ứng dụng | Mô tả |
|----------|-------|
| **Backlight cho vật liệu bán trong suốt** | Vật liệu không hoàn toàn trong suốt nhưng có màu, không còn hiển thị màu riêng trong IR và trở nên (hơn) trong suốt |
| **Kiểm tra bề mặt bất chấp in ấn** | Màu in trở nên vô hình trừ đen, có thể phát hiện vết nứt và khuyết tật bề mặt |
| **Ứng dụng OCR** | Trên tiền giấy, thẻ tín dụng, v.v. |
| **Độc lập với ánh sáng phòng** | Kết hợp với bộ lọc chặn ánh sáng ban ngày |
| **Không ảnh hưởng người vận hành** | Ở các trạm làm việc thủ công |

---

## Quan Trọng Cho Thị Giác Máy

> [!WARNING]
> Bức xạ hồng ngoại không nhìn thấy được bằng mắt người. Bức xạ IR thực sự không có năng lượng cao, nhưng về lâu dài có thể gây đau đầu, làm nóng các thụ thể trong mắt người và gây hại. Tuy nhiên, điều này chỉ xảy ra khi sử dụng nguồn sáng rất mạnh, nhìn trực tiếp vào đèn và trong nhiều giờ.

### Các lưu ý quan trọng:

1. **Xung nhịp đèn IR công nghiệp** nếu có thể. Bằng cách này, phát xạ ánh sáng không cần thiết và các cuộc thảo luận an toàn được tránh.

2. Sử dụng **bộ lọc bandpass băng hẹp** hoặc **bộ lọc màu** ngăn nhiễu do ánh sáng ban ngày.

3. **Ống kính hiệu chỉnh IR** tạo ra hình ảnh hoàn hảo. Ống kính tiêu chuẩn thường không được hiệu chỉnh cho ánh sáng hồng ngoại, tiêu cự cho bức xạ này có thể lệch đáng kể do **sắc sai (chromatic aberration)**.

4. **Không có bộ lọc cắt IR** trong camera. Hầu hết thời gian nó có thể được thay thế bằng phiên bản kính trong (nếu không tỷ lệ ảnh của quang học sẽ thay đổi).

5. **Quan sát độ nhạy cảm biến** của camera sử dụng. Có sự khác biệt đáng kể.

6. **Chú ý**: Ứng dụng sử dụng **ánh sáng phân cực** và **bộ lọc phân cực** trước ống kính **KHÔNG THỂ** thực hiện bằng bức xạ hồng ngoại, vì màng phân cực thường chỉ hiệu quả từ 400 đến 750nm.

7. **Chú ý**: Bản in inkjet (ngày hết hạn) trên thực phẩm, cũng như bản in trên giấy nhiệt (như hóa đơn tiền mặt, v.v.) đơn giản **biến mất** trong ảnh camera khi được chiếu sáng bằng bức xạ hồng ngoại.
