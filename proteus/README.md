# Proteus – Exercise 1

## Linh kiện và kết nối

- Vi điều khiển: `STM32F103C6`.
- LED đỏ: cathode nối `PA5`, anode nối `3.3 V` qua điện trở 220–330 Ω.
- LED vàng: cathode nối `PA6`, anode nối `3.3 V` qua điện trở 220–330 Ω.
- Cấp nguồn và mass cho STM32 theo sơ đồ mẫu của Lab 1.

Hai LED được mắc active-low: GPIO mức thấp làm LED sáng.

## Firmware

Trong thuộc tính **Program File** của STM32 trên Proteus, chọn:

```text
build\Debug\LAB_1.hex
```

Đặt tần số clock mô phỏng là `8 MHz` để khớp cấu hình HSI của project.

Sau khi hoàn thiện mạch:

1. Lưu project Proteus vào thư mục này, ví dụ `exercise_01.pdsprj`.
2. Chụp schematic và lưu thành `report/source/picture/bai_1/ex01_proteus.png`.
3. Build lại report; hình sẽ tự xuất hiện trong mục Exercise 1.
