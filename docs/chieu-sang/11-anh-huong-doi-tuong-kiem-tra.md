# Ảnh Hưởng Của Đối Tượng Kiểm Tra

## Các Yếu Tố Ảnh Hưởng Đến Tạo Ảnh 2D

Ngay cả với cùng công nghệ chiếu sáng, bản thân **đối tượng được kiểm tra** có ảnh hưởng lớn nhất đến hình ảnh video kết quả sẽ được xử lý sau đó.

---

## Ba Yếu Tố Chính

### 1. Màu sắc

Màu sắc vật liệu ảnh hưởng trực tiếp đến cách ánh sáng tương tác:

| Đặc tính | Ảnh hưởng |
|----------|-----------|
| Trong suốt | Ánh sáng truyền qua |
| Bán trong suốt | Ánh sáng truyền qua một phần |
| Trắng | Phản xạ tất cả bước sóng |
| Màu (đỏ, xanh lá, ...) | Phản xạ có chọn lọc |
| Đen | Hấp thụ hầu hết ánh sáng |

---

### 2. Hình dạng (Tính chất hình dạng vĩ mô)

**Hình học bề mặt** có ảnh hưởng rất lớn đến tạo ảnh:

| Loại bề mặt | Hành vi ánh sáng |
|-------------|------------------|
| Phẳng | Phản xạ đều, dễ chiếu sáng |
| Bậc thang | Tạo bóng, cần nhiều góc chiếu |
| Bề mặt nghiêng | Phản xạ lệch hướng |
| Hình cầu | Phản xạ theo nhiều hướng, điểm sáng tập trung |
| Hình trụ | Phản xạ theo một trục, dạng dải sáng |

---

### 3. Kết cấu (Tính chất hình dạng vi mô)

Tính chất hình dạng vi mô thường **gây ra nhiều khó khăn nhất**:

#### Tương tác ánh sáng với đặc tính vật liệu

| Vật liệu | Đặc điểm tương tác |
|----------|-------------------|
| **Nhựa** | Có thể bán trong suốt, phản xạ khuếch tán |
| **Kim loại** | Phản xạ cao, có thể bóng hoặc mờ |
| **Thủy tinh** | Trong suốt, phản xạ bề mặt, khúc xạ |
| **Gốm sứ** | Phản xạ khuếch tán, bề mặt mờ |

#### Kết cấu bề mặt

| Kết cấu | Hiệu ứng |
|---------|----------|
| Chải song song | Phản xạ định hướng theo một trục |
| Chải tròn | Phản xạ xoay tròn |
| Có rãnh | Tạo mẫu sáng tối |
| Xốp | Hấp thụ và tán xạ cao |
| Mịn | Phản xạ gương |
| Thô | Phản xạ khuếch tán |
| Sợi | Phản xạ phức tạp theo hướng sợi |

---

## Điển Hình: Chi Tiết Phức Tạp

Nhiều chi tiết công nghiệp kết hợp nhiều đặc tính trên cùng một đối tượng:

```
Ví dụ: Vỏ điện thoại kim loại
├── Mặt trước: Kính (trong suốt + phản xạ)
├── Viền: Kim loại chải (phản xạ định hướng)
├── Lưng: Nhựa mờ (khuếch tán)
└── Logo: In màu (hấp thụ chọn lọc)
```

> [!TIP]
> Với các chi tiết phức tạp như vậy, **ánh sáng khuếch tán** thường là giải pháp tốt nhất vì nó tạo ra chiếu sáng đồng nhất bất kể hướng bề mặt.

---

## Hướng Dẫn Chọn Chiếu Sáng Theo Đặc Tính

| Đặc tính đối tượng | Chiếu sáng khuyến nghị |
|-------------------|----------------------|
| Bề mặt bóng, phản xạ | Khuếch tán vòm / đồng trục |
| Bề mặt mờ, khuếch tán | Trực tiếp hoặc bên |
| Cạnh và đường viền | Trường tối hoặc backlight |
| Vết xước, khuyết tật nhỏ | Trường tối góc thấp |
| Đo kích thước | Backlight |
| Trong suốt | Backlight hoặc trường tối |
| Nhiều màu sắc | Ánh sáng màu phù hợp |
| Bề mặt cong | Chiếu sáng vòng hoặc vòm |

---

## Kết Luận

> [!IMPORTANT]
> Hiểu rõ **tính chất vật liệu, hình dạng và kết cấu** của đối tượng kiểm tra là bước đầu tiên quan trọng nhất để chọn chiếu sáng phù hợp.
> 
> Không có giải pháp "một kích cỡ phù hợp tất cả" - mỗi ứng dụng cần được phân tích riêng!
