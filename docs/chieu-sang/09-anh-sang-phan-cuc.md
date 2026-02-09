# Ánh Sáng Phân Cực

## Tổng Quan

Ánh sáng có thể được **phân cực** bằng cách sử dụng **màng phân cực** ở phía trước bất kỳ đèn công nghiệp nào. Màng linh hoạt từ độ dày **0.25mm đến 1mm** có sẵn cho mục đích này. Các bộ lọc dày hơn từ 2mm thường được cung cấp dưới dạng tấm nhựa cứng.

Ngoài ra, một **bộ lọc phân cực thủy tinh** được đặt trước ống kính để chọn lọc chặn hoặc truyền ánh sáng phân cực.

---

## Giảm Phản Xạ

Bằng cách sử dụng **màng phân cực trên đèn** và **bộ lọc phân cực trên ống kính**, các phản xạ gây nhiễu có thể được tránh trên:

- ✅ Bề mặt chất lỏng như nước, v.v.
- ✅ Bề mặt kính
- ✅ Bề mặt nhựa mịn, phản xạ
- ✅ Vật liệu kim loại bóng

---

## Mẹo Xử Lý Màng Phân Cực

### 1. Sử dụng bộ phân cực chế sẵn
Nếu có bộ phân cực và giá đỡ chế sẵn cho đèn, bạn có thể tiết kiệm nhiều công việc cắt và lắp đặt. Các đường cắt hình vòng với lỗ ở giữa đặc biệt khó.

### 2. Khoảng cách với nguồn sáng nóng
Giữ khoảng cách nhất định giữa nguồn sáng nóng và màng. Các phân tử hóa học được sử dụng làm thuốc nhuộm nhạy cảm với nhiệt.

> [!WARNING]
> Màng tiêu chuẩn có thể phân hủy ở nhiệt độ trên khoảng **70°C**.

### 3. Độ dày màng
Độ dày của màng ít ảnh hưởng đến hiệu ứng phân cực. Tuy nhiên, màng dày hơn giữ hình dạng tốt hơn và thường dễ lắp đặt trước đèn hơn.

### 4. Keo dán đặc biệt
Vui lòng chỉ sử dụng **keo dán đặc biệt cho màng phân cực**.

### 5. Dải bước sóng hiệu quả
Màng phân cực thông thường thường hoạt động từ **400 đến khoảng 780nm**.

> [!CAUTION]
> Chúng **KHÔNG phù hợp** cho chiếu sáng hồng ngoại. Mua màng đặc biệt cho IR (rất đắt)!

### 6. Giảm truyền sáng
Truyền sáng của màng phân cực mà không có hiệu ứng loại bỏ đã bị giảm **35 đến 40%** bởi bộ lọc thứ hai trước ống kính.

Bộ lọc trước ống kính làm giảm lượng ánh sáng truyền qua nhiều hơn nữa.

**Giải pháp**: Nếu điều chỉnh thời gian phơi sáng và khẩu độ không giúp được, sử dụng **đèn LED với bộ điều khiển nhấp nháy (flash controller)**.

### 7. Ánh sáng laser
Ánh sáng laser thường đã được **phân cực tuyến tính** sẵn.

---

## Sơ Đồ Nguyên Lý

```
         Camera
           ↓
    ┌─────────────┐
    │ Bộ lọc      │ ← Bộ lọc phân cực (chặn ánh sáng phân cực song song)
    │ phân cực    │
    └─────────────┘
           ↓
      ═══════════
       Đối tượng
      ═══════════
           ↑
    ┌─────────────┐
    │ Màng        │ ← Màng phân cực (tạo ánh sáng phân cực)
    │ phân cực    │
    └─────────────┘
           ↑
        [ĐÈN]
```

**Nguyên lý hoạt động:**
1. Đèn phát ánh sáng không phân cực
2. Màng phân cực trên đèn tạo ánh sáng phân cực theo một hướng
3. Phản xạ từ bề mặt bóng giữ nguyên hướng phân cực
4. Bộ lọc phân cực xoay 90° trước camera chặn ánh sáng phản xạ này
5. Ánh sáng từ bề mặt mờ/khuếch tán mất phân cực → đi qua bộ lọc

---

## Bảng Tóm Tắt Ứng Dụng

| Bề mặt | Vấn đề | Giải pháp phân cực |
|--------|--------|-------------------|
| Kính | Phản xạ mạnh | Phân cực chéo loại bỏ phản xạ |
| Nhựa bóng | Điểm sáng | Phân cực làm mờ điểm sáng |
| Kim loại đánh bóng | Chói | Giảm chói, thấy chi tiết bề mặt |
| Chất lỏng | Phản xạ bề mặt | Nhìn xuyên qua bề mặt |
