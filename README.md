# Học Sinh Data Cleaning Project

Làm sạch dữ liệu điểm học sinh bị lỗi, luyện kỹ năng xử lý dữ liệu bẩn.

## Dataset
[Messy Student Marks Dataset](https://www.kaggle.com/datasets/vedikagupta0/messy-student-marks-dataset-data-cleaning-practice) — 999 dòng, cố tình làm bẩn để luyện tập.

## Đã làm
- Sửa tên cột bị lỗi
- Tách số ra khỏi chữ (VD: "51 marks" → 51)
- Chuẩn hoá Grade, Gender
- Giữ lại 823/999 dòng sau khi làm sạch

## Insight
Điểm số không liên quan đến lớp học. Lớp 12 điểm trung bình thấp nhất, các lớp khác cũng không theo quy luật nào. Điểm trong dữ liệu là số ngẫu nhiên, không phải điểm thi thật.

## Công cụ
Python, Pandas, DuckDB, Matplotlib — Google Colab

## Giới hạn
Dữ liệu chỉ để luyện cleaning, không phản ánh về học lực thật. 
