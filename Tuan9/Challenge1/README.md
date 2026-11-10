# Challenge 1 – House Prices (Ames Housing) – Nhóm 5, lớp DCT124C1, ĐH Sài Gòn

GVHD: TS. Đỗ Như Tài. Thành viên: Phạm Minh Khôi (3124411135), Trương Thuận Phú (3124411234),
Nguyễn Mạnh Thắng (3124411283), Nguyễn Hoàng Quân (3124411250).

## Cấu trúc
- `01_Paper/`  : báo cáo dạng paper (.docx + .pdf)
- `02_Slide/`  : slide thuyết trình (.pptx + .pdf)
- `03_Poster/` : poster A0 ngang 40x24 inch (.pptx + .pdf)
- `04_Code/`   : notebook `challenge1_house_prices_pipeline_v2.ipynb`, dữ liệu `data/`, hình `figs/`, kết quả `outputs/`
- `05_Evidence/`: `submission.csv`, các bảng kết quả CSV, và chỗ để ảnh chụp điểm Kaggle

## Cách chạy lại
1. Cài thư viện: `pip install -r 04_Code/requirements.txt`
2. Mở `04_Code/` làm thư mục làm việc rồi chạy toàn bộ notebook (Run All, khoảng 2–3 phút).
3. Notebook sinh lại `figs/*.png`, `outputs/*.csv`, `outputs/submission.csv`, `outputs/results_summary.json`.

## Kết quả chính (5-fold CV, RMSE trên log1p(SalePrice))
- Baseline tốt nhất (79 biến): Ridge 0,1218 (R² 0,9065)
- Mô hình nộp (FE + Ridge/Lasso/GBDT blend): RMSE 0,1127 ± 0,0076, R² 0,9202
- Public score Kaggle: [điền sau khi nộp]
