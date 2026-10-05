# STM32 Lab 1

Repository chứa mã nguồn, firmware và báo cáo cho 10 exercise của Lab 1.

## Quy ước branch

- `main`: cấu trúc báo cáo LaTeX và cấu hình dùng chung.
- `exercise/01` đến `exercise/10`: mã nguồn của từng exercise.

## Build firmware

```powershell
cmake --preset Debug
cmake --build --preset Debug -j 4
```

Firmware được giữ trong Git:

- `build/Debug/*.elf`
- `build/Debug/*.hex`

Các file build trung gian khác không được commit.

## Build báo cáo

```powershell
cd report
latexmk -pdf -outdir=build main.tex
```

File kết quả: `report/build/main.pdf`.
