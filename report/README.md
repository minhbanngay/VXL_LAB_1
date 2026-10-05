# Cấu trúc báo cáo Lab 1

- `main.tex`: file chính để build báo cáo.
- `preamble.tex`: trang bìa và thông tin sinh viên.
- `source/content/bai_1.tex`: đề bài và bố cục báo cáo của 10 exercise.
- `source/picture/bai_1/`: hình hướng dẫn gốc và ảnh kết quả Proteus bổ sung.
- `references.bib`: tài liệu tham khảo.

## Cách điền báo cáo

Trong `bai_1.tex`, tìm lần lượt:

```latex
\subsection{Exercise 1}
\subsection{Exercise 2}
...
\subsection{Exercise 10}
```

Mỗi exercise đã ghi rõ cần nộp sơ đồ Proteus, source code hoặc cả hai. Thêm nội dung ngay dưới các dòng `Report 1`, `Report 2` tương ứng.

## Build

```powershell
latexmk -pdf -outdir=build main.tex
```

PDF được tạo tại `build/main.pdf`.
