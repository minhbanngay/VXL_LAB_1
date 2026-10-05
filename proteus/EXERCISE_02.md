# Proteus - Exercise 2

## Kết nối

- STM32F103C6 chạy ở 8 MHz.
- LED đỏ: cathode nối PA5.
- LED vàng: cathode nối PA6.
- LED xanh: cathode nối PA7.
- Anode của mỗi LED nối 3.3 V qua điện trở 220-330 ohm.

Các LED mắc active-low: GPIO ở mức thấp thì LED sáng.

## Firmware

Chọn file sau cho thuộc tính **Program File** của STM32:

```text
build\Debug\LAB_1.hex
```

Chương trình lặp theo chu kỳ: đỏ 5 giây, vàng 2 giây, xanh 3 giây.

Sau khi mô phỏng, lưu ảnh sơ đồ thành:

```text
report\source\picture\bai_1\ex02_proteus.png
```
