# Kỹ Thuật Chiếu Sáng

## Tương Tác Giữa Ánh Sáng, Đối Tượng và Camera

Tùy thuộc vào bề mặt của vật liệu, các hiệu ứng khác nhau xảy ra. Một phần ánh sáng tới bị **hấp thụ**, một phần bị **phản xạ** và một phần bị **tán xạ**, tùy thuộc vào bề mặt vật liệu.

Trong trường hợp vật liệu đục, bán trong suốt hoặc mờ, ánh sáng cũng có thể đi qua vật thể (**truyền qua**). Trong một số trường hợp, ánh sáng thậm chí bị **phân cực** hoặc **nhiễu xạ** tại bề mặt.

> [!NOTE]
> Thông thường một trong những hiệu ứng này không bao giờ xảy ra đơn độc; nó luôn là sự kết hợp của nhiều hiệu ứng. Ngay cả một gương quang học chất lượng cao cũng chỉ phản xạ khoảng 95% ánh sáng tới.

---

## Các Tham Số Chiếu Sáng

Ánh sáng có thể:
- Chiếu vào đối tượng kiểm tra ở một **góc chiếu nhất định**
- Có một **màu sắc nhất định** (đỏ, xanh lá, xanh dương, trắng với nhiệt độ màu cụ thể, hồng ngoại, cực tím)
- Là **trực tiếp** hoặc **khuếch tán**
- Có tính chất ánh sáng kết hợp (**laser**)

---

## Góc Chiếu Của Ánh Sáng

Một phương pháp quan trọng là sử dụng ánh sáng từ các hướng không gian khác nhau.

Ánh sáng có thể được hướng vào mẫu:
- Từ trên xuống
- Từ một bên ở góc nghiêng
- Từ bên cạnh, chiếu phẳng
- Từ phía đối diện

Tùy thuộc vào hình dạng bề mặt, tính chất vật liệu và cấu trúc, ánh sáng sẽ bị tán xạ, hấp thụ, phản xạ, truyền qua hoặc thậm chí tạo bóng trên vật thể và các đặc điểm kiểm tra của nó.

> [!IMPORTANT]
> Ngoài hướng chiếu sáng, điều rất quan trọng là ánh sáng song song hay khuếch tán.

---

## Các Kỹ Thuật Chiếu Sáng Cổ Điển

### 1. Chiếu sáng trực tiếp từ trên (Direct Top Light)

```
    Camera
       ↓
    [Đèn]
       ↓
    ═════
   Đối tượng
```

**Ánh sáng phản xạ trực tiếp**: Ánh sáng từ trên, không có bộ khuếch tán.

- Gây phản xạ mạnh trên bề mặt

---

### 2. Chiếu sáng khuếch tán (Diffuse Lighting)

**Ánh sáng phản xạ khuếch tán** được tạo ra bởi các bộ khuếch tán bổ sung và ít định hướng hơn.

Bao gồm:
- **Chiếu sáng vòm (Dome)**
- **Chiếu sáng đồng trục (Coaxial)**

- Tạo tình huống chiếu sáng đồng nhất

---

### 3. Chiếu sáng bên (Lateral Light)

**Ánh sáng bên ở các góc**: Thanh đèn định hướng trực tiếp, cũng dạng vòng, cũng khuếch tán.

- Tạo viền gợn sóng tối và bề mặt mờ

---

### 4. Trường tối (Dark Field)

Chiếu sáng ở góc nông từ tất cả các bên.

```
   Camera
      ↓
   ═════
  ↗     ↖
[Đèn] [Đèn]
```

- Với góc thấp hơn: nhấn mạnh các cạnh đường viền và ít ánh sáng trên bề mặt
- Với góc cực thấp: nhấn mạnh các cạnh đường viền mạnh nhất

---

### 5. Chiếu sáng nền (Backlight / Transmitted Light)

Chiếu sáng được sử dụng để chiếu sáng đối tượng từ phía sau.

```
   Camera
      ↓
   ═════
  Đối tượng
   ═════
    [Đèn]
```

- Ánh sáng từ dưới/phía đối diện của camera tạo ra **bóng đen (silhouette)** của đối tượng
- Lý tưởng cho ứng dụng đo lường đường viền

---

## Bảng Tổng Hợp Kỹ Thuật

| Kỹ thuật | Mô tả | Ứng dụng |
|----------|-------|----------|
| **Trực tiếp từ trên** | Không có bộ khuếch tán | Phát hiện bề mặt phản xạ |
| **Khuếch tán** | Với vòm hoặc đồng trục | Bề mặt bóng, tránh phản xạ |
| **Ánh sáng bên** | Thanh đèn ở góc | Phát hiện cấu trúc bề mặt |
| **Trường tối** | Góc rất thấp | Phát hiện cạnh, vết xước, bụi |
| **Sáng nền** | Từ phía sau đối tượng | Đo kích thước, đường viền |
